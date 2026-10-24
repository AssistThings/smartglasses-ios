# 📱 iOS Smart Glasses

[Português](README.md) · **Español** · [English](README.en.md)

![Swift](https://img.shields.io/badge/Swift-5.0-orange)
![iOS](https://img.shields.io/badge/iOS-13%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Una aplicación iOS creada con **SwiftUI** y el framework **Vision**, enfocada en apoyar a **personas con discapacidad visual**. La app permite escanear imágenes con texto desde la cámara o la galería y extraer el contenido textual mediante OCR. Todo el contenido se guarda localmente, con una interfaz accesible.

---

## ✨ Funcionalidades

- 📷 Captura de imagen con la **cámara**
- 🖼️ Selección de imagen de la **galería**
- 🧠 OCR local con **Vision (Apple)**
- 📜 Visualización del texto reconocido
- 🕘 Historial de textos escaneados
- 🎨 Interfaz moderna y accesible con **SwiftUI**

---

## 📸 Capturas de pantalla

> *(Agrega tus imágenes aquí)*

| Cámara y galería | OCR en acción | Historial |
|------------------|---------------|-----------|
| ![camera](docs/camera.png) | ![ocr](docs/ocr.png) | ![history](docs/history.png) |

---

## 🚀 Requisitos

- Xcode 14 o superior
- Swift 5
- iOS 13 o superior
- Dispositivo real (para usar la cámara)

---

## 🔧 Cómo usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/AssistThings/smartglasses-ios.git
   ```

2. Abre el proyecto en Xcode:
   ```
   smartglasses.xcodeproj
   ```

3. Ejecútalo en un dispositivo físico con iOS 13+  
   *(El simulador no tiene cámara)*

---

## 🛡️ Permisos en Info.plist

```xml
<key>NSCameraUsageDescription</key>
<string>Este app precisa acessar a câmera para escanear textos.</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>Este app precisa acessar sua galeria para selecionar imagens com texto.</string>
```

---

## 🗂️ Estructura

| Archivo                  | Función                              |
|--------------------------|--------------------------------------|
| `ContentView.swift`      | Pantalla principal con OCR e historial |
| `CameraPickerView.swift` | Acceso a la cámara                   |
| `PhotoPickerView.swift`  | Acceso a la galería de fotos         |
| `Info.plist`             | Permisos del sistema                 |

---

## 🧭 Hoja de ruta

- [ ] Exportar el OCR como `.txt` o `.pdf`
- [ ] Compartir el resultado por correo electrónico
- [ ] Soporte para varios idiomas
- [ ] Reconocimiento de objetos
- [ ] Reconocimiento de escenas

---

## 👤 Autor

Desarrollado por [Rodrigo Ferraz Azevedo](https://www.linkedin.com/in/rodrigoferrazazevedo/)  

---

## 📝 Licencia

Distribuido bajo la licencia MIT. Consulta `LICENSE` para más información.

---

Hecho con ❤️ usando SwiftUI + Vision Framework.
