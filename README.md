# 📱 iOS Smart Glasses

**Português** · [Español](README.es.md) · [English](README.en.md)

![Swift](https://img.shields.io/badge/Swift-5.0-orange)
![iOS](https://img.shields.io/badge/iOS-13%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Um aplicativo iOS criado com **SwiftUI** e o framework **Vision**, com foco em auxiliar **pessoas com deficiência visual**. O app permite escanear imagens com texto via câmera ou galeria e extrair o conteúdo textual por OCR. Todo o conteúdo é armazenado localmente com uma interface acessível.

---

## ✨ Funcionalidades

- 📷 Captura de imagem pela **câmera**
- 🖼️ Seleção de imagem da **galeria**
- 🧠 OCR local com **Vision (Apple)**
- 📜 Exibição do texto reconhecido
- 🕘 Histórico de textos escaneados
- 🎨 Interface moderna e acessível com **SwiftUI**

---

## 📸 Capturas de Tela

> *(Adicione suas imagens aqui)*

| Câmera e Galeria | OCR em ação | Histórico |
|------------------|-------------|-----------|
| ![camera](docs/camera.png) | ![ocr](docs/ocr.png) | ![history](docs/history.png) |

---

## 🚀 Requisitos

- Xcode 14 ou superior
- Swift 5
- iOS 13 ou superior
- Dispositivo real (para usar câmera)

---

## 🔧 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/AssistThings/smartglasses-ios.git
   ```

2. Abra o projeto no Xcode:
   ```
   smartglasses.xcodeproj
   ```

3. Execute em um dispositivo físico com iOS 13+  
   *(O simulador não suporta câmera)*

---

## 🛡️ Permissões no Info.plist

```xml
<key>NSCameraUsageDescription</key>
<string>Este app precisa acessar a câmera para escanear textos.</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>Este app precisa acessar sua galeria para selecionar imagens com texto.</string>
```

---

## 🗂️ Estrutura

| Arquivo                | Função                              |
|------------------------|-------------------------------------|
| `ContentView.swift`    | Tela principal com OCR e histórico  |
| `CameraPickerView.swift` | Acesso à câmera                    |
| `PhotoPickerView.swift`  | Acesso à galeria de fotos         |
| `Info.plist`           | Permissões de sistema               |

---

## 🧭 Roadmap

- [ ] Exportar OCR como `.txt` ou `.pdf`
- [ ] Compartilhar resultado por e-mail
- [ ] Suporte a múltiplos idiomas
- [ ] Reconhecimento de objetos
- [ ] Reconhecimento de cenas

---

## 👤 Autor

Desenvolvido por [Rodrigo Ferraz Azevedo](https://www.linkedin.com/in/rodrigoferrazazevedo/)  

---

## 📝 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

Feito com ❤️ usando SwiftUI + Vision Framework.
