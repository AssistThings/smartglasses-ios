# 📱 iOS Smart Glasses

[Português](README.md) · [Español](README.es.md) · **English**

![Swift](https://img.shields.io/badge/Swift-5.0-orange)
![iOS](https://img.shields.io/badge/iOS-13%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

An iOS app built with **SwiftUI** and the **Vision** framework, designed to support **people with visual impairments**. The app scans images containing text from the camera or the photo library and extracts the text with OCR. Everything is stored locally, behind an accessible interface.

---

## ✨ Features

- 📷 Capture an image with the **camera**
- 🖼️ Pick an image from the **photo library**
- 🧠 On-device OCR with Apple **Vision**
- 📜 Display of the recognized text
- 🕘 History of scanned texts
- 🎨 Modern, accessible interface built with **SwiftUI**

---

## 📸 Screenshots

> *(Add your images here)*

| Camera and library | OCR in action | History |
|--------------------|---------------|---------|
| ![camera](docs/camera.png) | ![ocr](docs/ocr.png) | ![history](docs/history.png) |

---

## 🚀 Requirements

- Xcode 14 or later
- Swift 5
- iOS 13 or later
- A physical device (to use the camera)

---

## 🔧 How to use

1. Clone the repository:
   ```bash
   git clone https://github.com/AssistThings/smartglasses-ios.git
   ```

2. Open the project in Xcode:
   ```
   smartglasses.xcodeproj
   ```

3. Run it on a physical device with iOS 13+  
   *(The simulator has no camera)*

---

## 🛡️ Info.plist permissions

```xml
<key>NSCameraUsageDescription</key>
<string>Este app precisa acessar a câmera para escanear textos.</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>Este app precisa acessar sua galeria para selecionar imagens com texto.</string>
```

---

## 🗂️ Structure

| File                     | Purpose                              |
|--------------------------|--------------------------------------|
| `ContentView.swift`      | Main screen with OCR and history     |
| `CameraPickerView.swift` | Camera access                        |
| `PhotoPickerView.swift`  | Photo library access                 |
| `Info.plist`             | System permissions                   |

---

## 🧭 Roadmap

- [ ] Export OCR results as `.txt` or `.pdf`
- [ ] Share results by email
- [ ] Multi-language support
- [ ] Object recognition
- [ ] Scene recognition

---

## 👤 Author

Developed by [Rodrigo Ferraz Azevedo](https://www.linkedin.com/in/rodrigoferrazazevedo/)  

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for details.

---

Made with ❤️ using SwiftUI + Vision Framework.
