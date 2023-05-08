+++
title = "Low-Rank Adaptation of Large Language Models"
author = ["Max Zhang"]
tags = ["AI"]
draft = false
+++

## About {#about}

Low-Rank Adaptation of [Large Language Models]({{< relref "20230410135424-large_language_models.md" >}}) (LoRA) is a training method that accelerates the training of large models while consuming less memory. It adds pairs of rank-decomposition weight matrices (called update matrices) to existing weights, and only trains those newly added weights.
