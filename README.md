# Apna AI 🚀

[![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.0+-purple.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/Jetpack%20Compose-M3-blue.svg)](https://developer.android.com/jetpack/compose)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange.svg)](LICENSE)

**Apna AI** is an advanced Android application that brings emotionally aware, full-body 3D AI companions to life. Designed with Kotlin and Jetpack Compose, it features sub-second conversational voice intelligence, persistent user memory tracking, a real-time community feed, and seamless subscription checkout.

---

## 🌟 Key Features

- **🎙️ Ultra-Low Latency Voice Engine**: Interactive bi-directional speech processing in Hindi, English, and Hinglish.
- **🧍 Master 3D Characters**: 6 permanently locked companions (Sahil, Abhi, Karan, Riya, Navya, and Kaniska) with realistic anatomy, dynamic physics, and facial micro-expressions.
- **💬 Instagram-Style Chronological Chats**: Direct messaging with real-time Firestore listeners, instant polls, media attachments, and message sequencing.
- **📸 Community Stories & Feed**: Share ephemeral updates with zero-permission Android Photo Picker and live upload status trackers.
- **🔒 Privacy-Focused Architecture**: Clean Architecture with strict separation of concerns, zero hardcoded secrets, and server-side payment processing via Cashfree.

---

## 🛠️ Tech Stack & Architecture

- **UI Framework**: 100% Jetpack Compose with Material Design 3 (M3)
- **Programming Language**: Kotlin Coroutines & StateFlow
- **Backend & Database**: Firebase Firestore, Firebase Authentication, Cloud Functions
- **Networking**: OkHttp3, Retrofit, Kotlinx Serialization
- **Media Loading**: Coil Compose, Media3 ExoPlayer
- **Secrets Management**: Google Secrets Gradle Plugin & BuildConfig injection
