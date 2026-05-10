<img width="730" height="242" alt="banner" src="https://github.com/user-attachments/assets/a9810b44-8d4c-4656-912f-e3c2072215e7" />

A minimalist PC game launcher.
---

## ✨ Highlights and Features

- 🕹️ **Native Gamepad Navigation:** Fully mapped for Xbox/PlayStation controllers. Browse, edit, and launch games without ever touching your mouse.
- 📖 **Game Journal:** Keep track of Beaten games, freeze titles in your *Backlog*, and stay updated with upcoming releases on the *Radar*.
- 🤖 **Auto-Healing & RAWG Integration:** Added an `.exe` and forgot the cover? The launcher automatically fetches high-resolution art (SteamGridDB), translated synopses, genres, and Metacritic scores (RAWG API) in the background.
- 🎨 **Fluid UI:** Clean interface, wide background art, Grid or Carousel modes, and subtle neon highlights.
- ⚡ **Lightweight & Optimized:** Minimizes to the system tray or closes completely when launching a game to free up 100% of your RAM.

---

## 📸 Gallery

Here is a look at GGameLauncher in action:

### Main View (Carousel / Banner)
<img width="1561" height="981" alt="image" src="https://github.com/user-attachments/assets/a218162a-cb37-4e29-9558-4770667a14b1" />

*Fluid navigation with full-screen wide art and automated game info.*

### Grid View
<img width="1571" height="980" alt="image" src="https://github.com/user-attachments/assets/4ccc1724-971e-429a-a8a6-c96ad93ecb30" />
*For those who prefer seeing their entire library at a glance.*

### Game Journal 
<img width="1577" height="985" alt="image" src="https://github.com/user-attachments/assets/b84e3796-e824-4747-875b-cbf2b4744306" />
*Track your progress, rate your games, and generate "Achievement Cards" to share.*

### Release Calendar
<img width="1573" height="977" alt="image" src="https://github.com/user-attachments/assets/e33ab43c-217d-4b81-993c-94ed5f0ce3c0" />
*Find out which games are coming out next week with integrated YouTube trailers.*

---

## 📥 How to Install and Use

1. Go to the [Releases](../../releases) tab here on GitHub.
2. Download the latest installer (`GGameLauncher_Setup.exe`).
3. Run the installer. 
4. Open the launcher, add your games' `.exe` files, or run an automatic scan!

---

## 🎮 Controls and Shortcuts

The launcher was designed to shine in your hands. Here is the current mapping:

| Action | Gamepad (Xbox) | Keyboard |
| :--- | :--- | :--- |
| **Launch Game / Confirm** | `A` | `Enter` |
| **Back / Minimize** | `B` | `Esc` |
| **Edit Selected Game** | `X` | `E` |
| **Upcoming Releases / Journal**| `Y` | - |
| **Add New Game** | `Start` / `Menu` | - |
| **Switch Tab / View Mode**| `RB` | `F2` |
| **Switch Tab / Edit Mode** | `LB` | `M` |
| **Toggle Sort Mode** | `LT` | `Mouse Click` |
| **Full Screen / Windowed** | `RT` | - |
| **Summon Launcher** | `Start` + `Back` (Hold) | `Ctrl` + `Shift` + `L` |

---

## 🛠️ Technologies Used

This project was built with:
* **[Flutter](https://flutter.dev/):** For the cross-platform UI.
* **[window_manager](https://pub.dev/packages/window_manager):** Advanced window control on Windows (Borderless, Blur, Tray).
* **[win32_gamepad](https://pub.dev/packages/win32_gamepad):** Native, lag-free communication with XInput controllers.
* **[audioplayers](https://pub.dev/packages/audioplayers):** Navigation sound effects.
* **APIs:** SteamGridDB (Art assets) and RAWG (Game data & metadata).

---

## 🤝 Contribution

This is a personal-use project.
