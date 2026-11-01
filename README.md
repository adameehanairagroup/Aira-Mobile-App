# Aira AI — Official Android Mobile App (Flutter)

<p align="center">
  <img src="assets/icons/app_icon.png" width="128" height="128" alt="Aira AI Logo" style="border-radius: 28px;" />
</p>

<p align="center">
  <strong>Sovereign Intelligence • Engine v3.6</strong><br/>
  <em>Engineered by Er. Adam Eehan for Aira Group of Technology</em>
</p>

---

## 🚀 Overview

The official Android mobile application for **Aira AI**, bringing the full power of sovereign intelligence directly into an edge-optimized native mobile package.

### ✨ Features
- **1:1 Mirror of Aira Web Chat**: Zero deviations, 100% faithful to the official production WebChat (`https://airaai-gamma.vercel.app`).
- **Welcome Onboarding & Terms**: Full Gemini/OpenAI style onboarding, Terms of Service agreement, and guest limit enforcement.
- **Full Hardware Integration**: Pre-configured Android permissions for:
  - 🎙️ **Microphone**: Ultra-low latency voice interaction with Silero VAD & Sovereign TTS.
  - 📷 **Camera & Gallery**: Multimodal image attachment uploads.
- **Sovereign Dark Theme**: Edge-to-edge immersive AMOLED black interface (`#09090B`).
- **Smooth Navigation**: Android predictive back navigation with web history traversal.
- **Offline Guard**: Graceful network failure handling with instant 1-tap reconnection.

---

## 🛠️ How to Build the APK on PC (Acer Nitro V 15)

### Step 1: Clone the Repository
```bash
git clone https://github.com/adameehanairagroup/Aira-Mobile-App.git
cd Aira-Mobile-App
```

### Step 2: Fetch Dependencies
```bash
flutter pub get
```

### Step 3: Build the Release APK
```bash
flutter build apk --release
```

*(Or to build a split per ABI for smaller file size:)*
```bash
flutter build apk --release --split-per-abi
```

### Step 4: Locate Your APK
Once built, the production APK will be located at:
```
build/app/outputs/flutter-apk/app-release.apk
```

Install it directly to your phone via USB:
```bash
adb install build/app/outputs/flutter-apk/app-release.apk
```

---

## ⚙️ App Architecture

- **Framework:** Flutter 3.24+ / Dart 3.5+
- **Platform:** Android (minSdkVersion 21, targetSdkVersion 34)
- **Package ID:** `com.airagroup.aira_ai`
- **Architect & CEO:** Er. Adam Eehan ([Wikidata: Q141755677](https://www.wikidata.org/wiki/Q141755677))
- **Organization:** Aira Group of Technology

---

Copyright © 2026 Aira Group of Technology. All rights reserved.
