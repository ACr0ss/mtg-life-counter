# Magic Life Tracker

A lightweight, responsive, and intuitive life counter app designed for **Magic: The Gathering – Commander** games.

Focused on fast interactions and clarity at the game table: no friction, no distractions, no unnecessary screens.

---

## ✨ Main Features (WIP)

- 📱 Supports **1 to 6 players**.
- 💖 Individual life tracking per player.
- ⚔️ Quick and intuitive **Commander damage tracking**.
- 🎨 Material Design 3 – clean and responsive layout.
- 🛠 Modular architecture using Kotlin, Jetpack Compose, and Hilt.
- 🧩 Clear separation of concerns via `core`, `feature`, and `designsystem` modules.

---

## 🧱 Architecture Overview

```text
MagicLifeTracker/
├── app/                    // Main app module
├── core/
│   ├── model/              // Shared data models: Player, Damage, etc.
│   ├── ui/                 // Reusable composables
│   └── designsystem/       // Theme, typography, color system
└── feature/
    ├── setup/              // Game setup screen
    └── tracker/            // Life and damage tracking screen
```

- **Jetpack Compose** for the entire UI.
- **Hilt** for dependency injection.
- **MVVM** architecture for state and business logic.
- Navigation handled via **Navigation Compose**.

---

## 📸 Screenshots (coming soon)

---

## 🛣️ Roadmap

- [x] Modular Compose + Hilt project base
- [x] Single-player UI layout
- [ ] Dynamic player setup (1–6)
- [ ] Commander damage buttons by player color
- [ ] Game reset functionality
- [ ] Visual feedback for 21+ damage received
- [ ] Optional game state persistence
- [ ] Light animations and accessibility tweaks

---

## 🤝 Contributions

This project is part of a personal recovery journey. Feedback, suggestions, and ideas are welcome once the foundation is stable 💙

---
