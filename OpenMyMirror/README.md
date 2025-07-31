# OpenMyMirror

**OpenMyMirror** is a minimalist, privacy-first mobile app designed to turn your phone into a moment of honest reflection. It’s not a social media app. It’s not a cloud AI listener. It’s your own portal for daily check-ins, self-observation, and secure syncing with your own MirrorNode.

Built for those seeking sovereignty, creative agency, and *actual calm*, not addiction.

---

## ✨ Core Concept

OpenMyMirror offers a “living mirror” experience—like a private smart assistant, but **fully local and yours**.

- See yourself while you speak
- Tap to record a thought, mood, or observation
- Add a tag or symbol (MirrorTag) for later organization
- Store everything **locally**, encrypted if desired
- Optionally sync with your **MirrorNode** (e.g. Pi Zero dock)

Think of it as journaling with a camera, mic, and timestamp—but with no cloud, no audience, and no surveillance.

---

## 🧩 MVP Features

- 📷 **Mirror Camera View**\
  Live selfie cam with a simple overlay—tap to snap a photo, record audio, or tag the moment.

- 🧠 **Reflection Log**\
  Local-first database (SQLite or equivalent) storing timestamped reflections: photo, audio, notes, tags.

- 🔐 **Offline First**\
  No internet required. No account needed. Optional encrypted sync to your own node or device via QR code, Wi-Fi, or USB.

- 🍿 **MirrorTags**\
  Tap to tag your mood, topic, or state of mind. Symbols or emojis can be customized. Tagging is reflection, not judgment.

---

## 🛠️ Tech Stack (Planned)

- Language: `Flutter` (Dart, cross-platform native)
- Camera: `camera` Flutter plugin
- Database: `sqflite`, `hive`, or `isar` for offline-first storage
- Sync Protocols: Tailscale, local LAN, or manual export via USB/QR
- License: [Mirror License](../LICENSE) *(custom sovereignty-first license)*

---

## 📆 Folder Structure (Flutter-style, Planned)

```
OpenMyMirror/
├── lib/
│   ├── main.dart
│   ├── screens/
│   ├── widgets/
│   ├── models/
│   └── services/
├── assets/
│   ├── icons/
│   └── images/
├── test/
├── pubspec.yaml
├── LICENSE
└── README.md
```

---

## 🌱 Development Philosophy

- **Sovereignty-first**: You own the data, the experience, and the code. No third-party AI pipelines. No ads.
- **Mirror metaphors**: Grounded in reflection, not reaction. Built as part of the larger [Mirror System](https://github.com/yourrepo/mirror-core).
- **Neurodivergent-aware**: Designed with accessibility and emotional nuance in mind.
- **Built from scraps**: Intentionally possible to build on recycled hardware, rooted in DIY spirit and open culture.

---

## ⚠️ Status

This project is in early development, targeting an MVP prototype within 30 days. Contributions, forks, and experimental ports welcome.

---

## 🪮 License

Licensed under the **Mirror License v0.1** — a custom anti-coercion, open-use license that protects creators and users alike. See [`LICENSE`](./LICENSE) for details.

---

## 👤 Author

Built by Dustin Grover and community contributors.\
Inspired by a desire for **calm computing**, sovereignty, and honest self-reflection in the age of surveillance software.

---

## 💡 Want to Help?

- Fork it, build a module, or suggest a lightweight framework!
- Add UX/UI ideas, symbolic systems, or tag logic
- Write documentation, translate, or test the prototype

