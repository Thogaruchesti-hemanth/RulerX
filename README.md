# 📏 Screen Ruler Overlay

A professional **floating screen ruler overlay** for Android, built in **Java** with a clean architecture.  
Easily **measure**, **align**, or **aim** across any app — including games — using a **movable, rotatable, and transparent ruler** that stays on top of other apps.

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/ScreenRulerOverlay?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/ScreenRulerOverlay?style=flat-square)
![GitHub license](https://img.shields.io/github/license/YOUR_USERNAME/ScreenRulerOverlay?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Android-green?style=flat-square)

---

## ✨ Features

✅ **Overlay on top of any app** – works while gaming, browsing, or designing  
✅ **Draggable** – move freely anywhere on the screen  
✅ **Rotatable** – adjust ruler angle for perfect alignment  
✅ **Adjustable Transparency** – control visibility to your preference  
✅ **Auto-Hide** – hide ruler after inactivity  
✅ **Persistent Settings** – remembers position, rotation, and transparency  
✅ **Lightweight & Optimized** – minimal performance impact  

---

## 📸 Screenshots

| Overlay Ruler | Rotation | Transparency |
|---------------|----------|--------------|
| ![Overlay Example](docs/screenshot1.png) | ![Rotation](docs/screenshot2.png) | ![Transparency](docs/screenshot3.png) |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/ScreenRulerOverlay.git
cd ScreenRulerOverlay
````

### 2️⃣ Open in Android Studio

* Open **Android Studio**
* Select **Open an existing project**
* Choose the cloned folder

### 3️⃣ Build & Run

* Connect an Android device (or use an emulator)
* Click **Run ▶**

---

## 📱 Permissions

The app requires the **Draw Over Other Apps** permission to display the ruler:

```xml
<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW" />
```

On first launch, the app will guide you to enable it in **Settings**.

---

## 🛠️ Tech Stack

* **Language**: Java (Android)
* **Architecture**: Clean Architecture + MVVM
* **UI**: Custom View for scalable ruler
* **Persistence**: SharedPreferences for settings
* **Services**: Foreground Service for stable overlays

---

## 📂 Project Structure

```
com.example.ruleroverlay
│
├── data/                # Data storage & preferences
├── domain/              # Core business logic
├── ui/                  # Activities, overlay service, custom views
├── utils/               # Permission & helper utilities
└── App.java              # Application class
```

---

## ⚠️ Disclaimer

This tool is designed for **utility and measurement purposes**.
Using it in competitive games **may violate their terms of service**.
The author is **not responsible** for any misuse or consequences.

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 🌟 Show Your Support

If you find this project helpful, **please give it a ⭐ on GitHub** to help others discover it!
