# BroDue

<img width="1920" height="1080" alt="Banner" src="https://github.com/user-attachments/assets/469c3789-4a20-41ab-8315-88b0fa249653" />

**BroDue** is a simple, privacy-friendly money manager for tracking what you lend and what you borrow - from friends, family, or anyone. Open source and free forever.

<p>
<a href="https://github.com/Arun-Kaswan-x/BroDue/releases/latest"><img alt="Download" src="https://img.shields.io/github/v/release/Arun-Kaswan-x/BroDue?label=download&color=5B6BA3" /></a>
<a href="LICENSE"><img alt="License" src="https://img.shields.io/github/license/Arun-Kaswan-x/BroDue?color=2E9E6E" /></a>
</p>

---

## 🔄 Live Sync - the core of BroDue

BroDue is built around **real-time shared money records**. One person creates a shared group, sends a code, and everyone stays on the same page - instantly.

| Feature | What it does |
|---|---|
| 🤝 **Join via Share Code** | A friend enters a simple share code and they're in - no setup, no extra accounts. |
| 👀 **Reader / Writer roles** | The owner controls access: **readers** can view, **writers** can add entries, and only the **owner** can edit, delete, or change roles. |
| ⚡ **Real-time updates** | New entries and changes appear instantly on every connected device. |
| 🔔 **Push notifications** | Every member gets a push notification when someone adds, edits, or deletes an entry - you never miss an update. |
| 📴 **Works Offline** | Keep using the app with no internet - everything syncs automatically when you're back online. |
| 🔒 **Private by design** | Data is tied to the owner's account; roles decide exactly what each person can see and do. |

---

## ✨ Features

- 👥 **People** - track everyone you transact with, sorted by name / value / recent activity
- 💸 **Money records** - "I received" / "I gave" entries with categories, notes and custom date-time
- 🗂️ **Custom categories** - create your own categories
- 📜 **Logs** - every transaction in one timeline with net balance trend graph and 5 display modes (Net / +ve / -ve / Send / Received)
- 📄 **Statements** - share as JPG/PDF text or image, per person
- 🔐 **Fingerprint Lock** - protect opening the app and/or individual actions (add entry, edit entry, archive, edit person) with biometrics
- ⚡ **Instant Lock** - optional: require fingerprint every time you minimize the app
- 🌙 **Theme support** - Light, Dark and AMOLED
- 🔄 **System Update** - in-app updates via GitHub Releases

---

## 📥 Download

Grab the latest APK from the [**Releases page**](https://github.com/Arun-Kaswan-x/BroDue/releases/latest).

> Requires Android 7.0+ (API 24). Sign in with Google.

---

## 🛠️ Build from source

1. Clone:
   ```bash
   git clone https://github.com/Arun-Kaswan-x/BroDue.git
   ```
2. Build & run in Android Studio, or:
   ```bash
   ./gradlew :app:assembleDebug
   ```

---

## 📁 Project layout

```
app/src/main/java/com/akk/brodue/    # App code (Kotlin)
app/src/main/res/                    # Layouts, drawables, values
data-send.html                       # Standalone data-import helper page
```

---

## 📄 License

Released under the [MIT License](LICENSE).
