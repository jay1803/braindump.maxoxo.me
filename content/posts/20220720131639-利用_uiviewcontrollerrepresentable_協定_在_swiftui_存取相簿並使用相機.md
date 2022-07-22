+++
title = "利用 UIViewControllerRepresentable 協定在 SwiftUI 存取相簿並使用相機"
author = ["Max Zhang"]
tags = ["ref", "swift"]
draft = false
+++

## 使用 UIViewControllerRepresentable {#使用-uiviewcontrollerrepresentable}

要將 UIImagePickerController 整合到 [SwiftUI]({{< relref "20220704125155-swiftui.md" >}}) 專案中，我們可以使用 [UIViewControllerRepresentable]({{< relref "20220704125123-uiviewcontrollerrepresentable.md" >}}) 協定

```swift
struct ImagePicker: UIViewControllerRepresentable {
    func makeUIViewController(context: UIViewControllerRepresentableContext<ImagePicker>) -> UIImagePickerController {

        // Return an instance of UIImagePickerController
    }

    func updateUIViewController(_ uiViewController: UIImagePickerController, context: UIViewControllerRepresentableContext<ImagePicker>) {

    }
}
```

當初始化 ImagePicker 時，就會調用 makeUIViewController 方法。在該方法中，你需要實例化 (instantiate) UIImagePickerController，並配置其初始狀態。


## 在 SwiftUI 中創建 ImagePicker {#在-swiftui-中創建-imagepicker}

```swift
struct ImagePicker: UIViewControllerRepresentable {

    var sourceType: UIImagePickerController.SourceType = .photoLibrary

    func makeUIViewController(context: UIViewControllerRepresentableContext<ImagePicker>) -> UIImagePickerController {

        let imagePicker = UIImagePickerController()
        imagePicker.allowsEditing = false
        imagePicker.sourceType = sourceType

        return imagePicker
    }

    func updateUIViewController(_ uiViewController: UIImagePickerController, context: UIViewControllerRepresentableContext<ImagePicker>) {

    }
}
```


## 使用 ImagePicker 在 SwiftUI 視圖中加載相簿 {#使用-imagepicker-在-swiftui-視圖中加載相簿}


## 讓 Coordinator 採用 UIImagePickerControllerDelegate 協定 {#讓-coordinator-採用-uiimagepickercontrollerdelegate-協定}

必須採用兩個委託 (delegate)：UIImagePickerControllerDelegate 和 UINavigationControllerDelegate，以便與 UIImagePickerController 進行交互。
