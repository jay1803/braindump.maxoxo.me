+++
title = "Docker"
author = ["Max"]
draft = false
+++

\#dev/docker #wiki


### Hierarchy of an APP {#hierarchy-of-an-app}


## Stack {#stack}


## Services {#services}


## Container {#container}


### Recap and cheat sheet {#recap-and-cheat-sheet}

\`\`\`sh


## List Docker CLI commands {#list-docker-cli-commands}

docker
docker container --help


## Display Docker version and info {#display-docker-version-and-info}

docker --version
docker version
docker info


## Execute Docker image {#execute-docker-image}

docker run hello-world


## List Docker images {#list-docker-images}

docker image ls


## List Docker containers (running, all, all in quiet mode) {#list-docker-containers--running-all-all-in-quiet-mode}

docker container ls
docker container ls --all
docker container ls -aq
\`\`\`


### Define a container with Dockerfile {#define-a-container-with-dockerfile}

Dockerfile defines what goes on in the environment inside your container.


## example dockfile {#example-dockfile}

\`\`\`sh


## Use an official Python runtime as a parent image {#use-an-official-python-runtime-as-a-parent-image}

FROM python:2.7-slim


## Set the working directory to /app {#set-the-working-directory-to-app}

WORKDIR /app


## Copy the current directory contents into the container at /app {#copy-the-current-directory-contents-into-the-container-at-app}

ADD . /app


## Install any needed packages specified in requirements.txt {#install-any-needed-packages-specified-in-requirements-dot-txt}

RUN pip install --trusted-host pypi.python.org -r requirements.txt


## Make port 80 available to the world outside this container {#make-port-80-available-to-the-world-outside-this-container}

EXPOSE 80


## Define environment variable {#define-environment-variable}

ENV NAME World


## Run app.py when the container launches {#run-app-dot-py-when-the-container-launches}

CMD ["python", "app.py"]
\`\`\`


### The app itself {#the-app-itself}

\`\`\`sh
还需要准备 requirements.txt 以及 app.py
使用 pip install -r requirements.txt 来配置环境


## -t 的意思是添加 tag 这样就能更容易识别 {#t-的意思是添加-tag-这样就能更容易识别}

配置好之后 docker build -t friendlyhello .
\`\`\`


### Build the app {#build-the-app}

\`\`\`sh


## -t 的意思是添加 tag 这样就能更容易识别 {#t-的意思是添加-tag-这样就能更容易识别}

配置好之后 docker build -t friendlyhello .
\`\`\`


### Run the app {#run-the-app}

\`\`\`sh
docker run -p 4000:80 friendlyhello


## run app in background {#run-app-in-background}

docker run -d -p 4000:80 friendlyhello


## stop app with container id {#stop-app-with-container-id}

docker container stop 1fa4ab2cf395
\`\`\`


### Share your image {#share-your-image}

\`\`\`sh


## Log in with your Docker ID {#log-in-with-your-docker-id}

docker login


## Tag the image {#tag-the-image}


## for example: docker tag friendlyhello john/get-started:part2 {#for-example-docker-tag-friendlyhello-john-get-started-part2}

docker tag image\_name username/repository:tag


## Publish the image {#publish-the-image}

docker push username/repository:tag


## Pull and run the image from the remote repository {#pull-and-run-the-image-from-the-remote-repository}

docker run -p 4000:80 username/repository:tag
\`\`\`


### Recap and cheat sheet {#recap-and-cheat-sheet}

\`\`\`sh


## Create image using this directory's Dockerfile {#create-image-using-this-directory-s-dockerfile}

docker build -t friendlyhello .


## Run "friendlyname" mapping port 4000 to 80 {#run-friendlyname-mapping-port-4000-to-80}

docker run -p 4000:80 friendlyhello


## Same thing, but in detached mode {#same-thing-but-in-detached-mode}

docker run -d -p 4000:80 friendlyhello


## List all running containers {#list-all-running-containers}

docker container ls


## List all containers, even those not running {#list-all-containers-even-those-not-running}

docker container ls -a


## Gracefully stop the specified container {#gracefully-stop-the-specified-container}

docker container stop <hash>


## Force shutdown of the specified container {#force-shutdown-of-the-specified-container}

docker container kill <hash>


## Remove specified container from this machine {#remove-specified-container-from-this-machine}

docker container rm <hash>


## Remove all containers {#remove-all-containers}

docker container rm $(docker container ls -a -q)


## List all images on this machine {#list-all-images-on-this-machine}

docker image ls -a


## Remove specified image from this machine {#remove-specified-image-from-this-machine}

docker image rm <image id>


## Remove all images from this machine {#remove-all-images-from-this-machine}

docker image rm $(docker image ls -a -q)


## Log in this CLI session using your Docker credentials {#log-in-this-cli-session-using-your-docker-credentials}

docker login


## Tag <image> for upload to registry {#tag-image-for-upload-to-registry}

docker tag <image> username/repository:tag


## Upload tagged image to registry {#upload-tagged-image-to-registry}

docker push username/repository:tag


## Run image from a registry {#run-image-from-a-registry}

docker run username/repository:tag
\`\`\`


## About Services {#about-services}


### Your first docker-compose.yml file {#your-first-docker-compose-dot-yml-file}

A docker-compose.yml file is a YAML file that defines how Docker containers should behave in production.


## example docker-compse.yml {#example-docker-compse-dot-yml}

\`\`\`py
version: "3"
services:
  web:

image: username/repo:tag
deploy:
  replicas: 5
  resources:
    limits:
      cpus: "0.1"
      memory: 50M
  restart\_policy:
    condition: on-failure
ports:

-   "80:80"

networks:

-   webnet

networks:
  webnet:
\`\`\`
This docker-compose.yml file tells Docker to do the following:


## Pull the image we uploaded in step 2 from the registry. {#pull-the-image-we-uploaded-in-step-2-from-the-registry-dot}


## Run 5 instances of that image as a service called web, limiting each one to use, at most, 10% of the CPU (across all cores), and 50MB of RAM. {#run-5-instances-of-that-image-as-a-service-called-web-limiting-each-one-to-use-at-most-10-of-the-cpu--across-all-cores--and-50mb-of-ram-dot}


## Immediately restart containers if one fails. {#immediately-restart-containers-if-one-fails-dot}


## Map port 80 on the host to web’s port 80. {#map-port-80-on-the-host-to-web-s-port-80-dot}


## Instruct web’s containers to share port 80 via a load-balanced network called webnet. (Internally, the containers themselves publish to web’s port 80 at an ephemeral port.) {#instruct-web-s-containers-to-share-port-80-via-a-load-balanced-network-called-webnet-dot--internally-the-containers-themselves-publish-to-web-s-port-80-at-an-ephemeral-port-dot}


## Define the webnet network with the default settings (which is a load-balanced overlay network). {#define-the-webnet-network-with-the-default-settings--which-is-a-load-balanced-overlay-network--dot}


### Run your new load-balanced app {#run-your-new-load-balanced-app}

\`\`\`sh


## we can use the docker stack deploy command we first run {#we-can-use-the-docker-stack-deploy-command-we-first-run}


## We get into the meaning of that command in part 4. If you don’t run docker swarm init you get an error that “this node is not a swarm manager." {#we-get-into-the-meaning-of-that-command-in-part-4-dot-if-you-don-t-run-docker-swarm-init-you-get-an-error-that-this-node-is-not-a-swarm-manager-dot}

docker swarm init


## Now let’s run it. You need to give your app a name. Here, it is set to getstartedlab {#now-let-s-run-it-dot-you-need-to-give-your-app-a-name-dot-here-it-is-set-to-getstartedlab}

docker stack deploy -c docker-compose.yml getstartedlab
\`\`\`


### Scale the app {#scale-the-app}

\`\`\`sh


## You can scale the app by changing the replicas value in docker-compose.yml, saving the change, and re-running the docker stack deploy command: {#you-can-scale-the-app-by-changing-the-replicas-value-in-docker-compose-dot-yml-saving-the-change-and-re-running-the-docker-stack-deploy-command}

docker stack deploy -c docker-compose.yml getstartedlab


## Take down the app and the swarm {#take-down-the-app-and-the-swarm}


## Take the app down with docker stack rm: {#take-the-app-down-with-docker-stack-rm}

docker stack rm getstartedlab


## Take down the swarm. {#take-down-the-swarm-dot}

docker swarm leave --force
\`\`\`


## recap and cheat sheet {#recap-and-cheat-sheet}

\`\`\`sh


## List stacks or apps {#list-stacks-or-apps}

docker stack ls


## Run the specified Compose file {#run-the-specified-compose-file}

docker stack deploy -c <composefile> <appname>


## List running services associated with an app {#list-running-services-associated-with-an-app}

docker service ls


## List tasks associated with an app {#list-tasks-associated-with-an-app}

docker service ps <service>


## Inspect task or container {#inspect-task-or-container}

docker inspect <task or container>


## List container IDs {#list-container-ids}

docker container ls -q


## Tear down an application {#tear-down-an-application}

docker stack rm <appname>


## Take down a single node swarm from the manager {#take-down-a-single-node-swarm-from-the-manager}

docker swarm leave --force
\`\`\`
