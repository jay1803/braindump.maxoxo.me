+++
title = "UINavigationController"
author = ["Max Zhang"]
tags = ["swift"]
draft = false
+++

## Usage {#usage}

```swift
navigationItem.largeTitleDisplayMode                    = .never
navigationController?.navigationBar.prefersLargeTitles  = false
/*
  导航栏是否透明，如果设置为透明，在计算 view 高度的时候会忽略导航
  如果设置为 false，则 view 的高度会忽略导航栏；
  如果设置为 true，则 view 的高度会加上导航栏，所以需要手动减去导航栏的高度；
*/
navigationController?.navigationBar.isTranslucent       = false
```


## 手動建立頁面 <span class="tag"><span class="ATTACH">ATTACH</span></span> {#手動建立頁面}

第一步先以刪除檔案的方式將 Storyboard 刪除，也就是下圖中列表的這隻檔案 Main.storyboard ：
![](/ox-hugo/_20220728_131719screenshot.png)

第二步接著看到 Info.plist ，找到並刪除 Main storyboard file base name 這個欄位。

{{< figure src="/ox-hugo/_20220728_131749screenshot.png" >}}

將 General &gt; Deployment Info &gt; Main Interface 這個欄位清空

{{< figure src="/ox-hugo/_20220728_131826screenshot.png" >}}

在 `AppDelegat`  類別中的 `application(application: UIApplication, didFinishLaunchingWithOptions launchOptions: [NSObject: AnyObject]?) -> Bool` 方法中手動加上頁面


## 建立 UINavigationController {#建立-uinavigationcontroller}

```swift
// 在 AppDelegate.swift 中將根視圖控制器設為一個 UINavigationController
func application(application: UIApplication,
  didFinishLaunchingWithOptions launchOptions: [NSObject: AnyObject]?) -> Bool {
    // 建立一個 UIWindow
    self.window = UIWindow(frame:
      UIScreen.mainScreen().bounds)

    // 設置底色
    self.window!.backgroundColor = UIColor.whiteColor()

    // 設置根視圖控制器
    let nav = UINavigationController(
      rootViewController: ViewController())
    self.window!.rootViewController = nav

    // 將 UIWindow 設置為可見的
    self.window!.makeKeyAndVisible()

    return true
}

// 接著轉到 ViewController.swift 的viewDidLoad()方法中，將導覽列的設定與按鈕設置寫入：
// 底色
self.view.backgroundColor = UIColor.darkGrayColor()

// 導覽列標題
self.title = "首頁"

// 導覽列底色
self.navigationController?.navigationBar.barTintColor =
  UIColor.lightGrayColor()

// 導覽列是否半透明
self.navigationController?.navigationBar.translucent = false

// 導覽列左邊按鈕
let leftButton = UIBarButtonItem(
  image: UIImage(named:"check"),
  style:.Plain ,
  target:self ,
  action: #selector(ViewController.check))
// 加到導覽列中
self.navigationItem.leftBarButtonItem = leftButton

// 導覽列右邊按鈕
let rightButton = UIBarButtonItem(
  title:"設定",
  style:.Plain,
  target:self,
  action:#selector(ViewController.setting))
// 加到導覽列中
self.navigationItem.rightBarButtonItem = rightButton

// 建立一個按鈕
let myButton = UIButton(frame: CGRect(
  x: 0, y: 0, width: 120, height: 40))
myButton.setTitle("Article", forState: .Normal)
myButton.backgroundColor = UIColor.blueColor()
myButton.addTarget(
  self,
  action: #selector(ViewController.article),
  forControlEvents: .TouchUpInside)
self.view.addSubview(myButton)

// 在ViewController中加上按鈕執行動作的方法：
func article() {
    self.navigationController?.pushViewController(
      ArticleViewController(), animated: true)
}

func check() {
    print("check button action")
}

func setting() {
    self.navigationController?.pushViewController(
      SettingViewController(), animated: true)
}
```
