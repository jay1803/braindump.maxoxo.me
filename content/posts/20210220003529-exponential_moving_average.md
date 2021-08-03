+++
title = "Exponential Moving Average"
author = ["Max"]
draft = false
+++

## 定义 {#定义}

An exponential moving average (EMA) is a type of moving average (MA) that
places a greater ****weight and significance on the most recent data**** points.


### 计算公式 {#计算公式}

\\(EMA\_{today} = (Value\_{today} (\frac{Smoothing}{1 + Days})) + (Value\_{yesterday}
   (1-\frac{Smoothing}{1 + Days}))\\)

While there are many possible choices for the smoothing factor, the most common choice is:
Smoothing = 2


## 取决于 {#取决于}


### Smoothing {#smoothing}


### 当天的股价 {#当天的股价}


### 昨天的股价 {#昨天的股价}


## 会影响 {#会影响}
