+++
title = "UIMenuController"
author = ["Max Zhang"]
tags = ["swift"]
draft = false
+++

## Usage {#usage}

```swift
// 建立兩個新的選項
let mail = UIMenuItem(
  title: "寄送",
  action: #selector(ViewController.sendMail))
let facebook = UIMenuItem(
  title: "FB",
  action: #selector(ViewController.sendFB))

// 建立選單
let menu = UIMenuController.sharedMenuController()

// 將新的選項加入選單
menu.menuItems = [mail,facebook]

// 声明方法
func sendMail() {
    print("sendMail")
}

func sendFB() {
    print("sendFB")
}
```
