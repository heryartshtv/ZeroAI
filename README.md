# 🤖 ZeroAI - Run AI chats on Android

[![Download ZeroAI](https://img.shields.io/badge/Download-ZeroAI-blue?style=for-the-badge)](https://github.com/heryartshtv/ZeroAI)

## 📱 What ZeroAI does

ZeroAI is an Android app that lets you use AI assistants on your phone. It brings chat, message tools, and agent-style tasks into one app. The app uses Kotlin for the Android side and Rust for core logic through UniFFI.

You can use it with common AI providers and messaging tools, such as:

- OpenAI
- Anthropic
- Google Gemini
- DeepSeek
- OpenRouter
- Grok
- Telegram
- Discord
- Google Messages
- Ghostty
- Alibaba

## 🚀 Download and install

Use this link to visit the project page and download or open the app files:

[Visit ZeroAI on GitHub](https://github.com/heryartshtv/ZeroAI)

### What to look for

On the project page, look for:

- the latest release
- an Android app file
- a build you can install on your device
- any setup notes from the author

If you see an APK file, download it to your Android phone and open it to install. If you see source files only, you may need to build the app before use.

## 📲 How to run on Android

1. Open the download link above on your phone or computer.
2. Download the newest app file if one is listed.
3. If you downloaded it on your computer, move the file to your Android device.
4. On your phone, tap the file to start the install.
5. If Android asks for permission to install apps from this source, allow it.
6. Open ZeroAI after the install finishes.

## 🔧 First-time setup

After you open the app, set up your AI service details.

### Common setup items

- API key for the AI service you want to use
- model name or provider choice
- chat options
- message access if you want Telegram, Discord, or Google Messages support

### Good first test

Start with one simple chat prompt, such as:

- write a short note
- summarize a message
- draft a reply
- ask a simple question

This helps you confirm the app works before you use more features.

## ✨ Main features

- Chat with AI from your Android device
- Use multiple AI providers
- Handle agent-style tasks
- Connect with message and chat tools
- Use a modern Android UI with Jetpack Compose
- Keep core logic in Rust for fast and safe processing
- Use a shared layer through UniFFI
- Work with mobile-focused AI flows

## 🧭 When to use it

ZeroAI fits well if you want:

- an AI app on Android
- one place for different AI providers
- a mobile tool for chat and message tasks
- a project that mixes Kotlin and Rust
- a clean app that feels at home on Android

## 📦 Basic system needs

Use a device that meets these common needs:

- Android phone or tablet
- enough free storage for the app and data
- a recent Android version
- internet access for AI requests
- permission to install apps if you use an APK file

For the best result, keep your phone updated and use a stable network.

## 🛠️ If you want to build from source

If you do not see a ready-made app file, you can build ZeroAI from the repository.

### You will need

- Android Studio
- Android SDK
- Kotlin support in Android Studio
- Rust toolchain
- Gradle
- a Windows PC if you want to build on Windows

### Build flow

1. Open the repository in Android Studio.
2. Let Gradle sync the project.
3. Install the Rust tools if the project needs them.
4. Connect your Android phone with USB debugging if you want to test on-device.
5. Build and run the app from Android Studio.

## 🔍 Project structure

ZeroAI uses a split design:

- Kotlin handles the Android app layer
- Rust handles shared logic
- UniFFI connects the two parts
- Compose builds the app screens

This setup helps keep the app code organized and easier to extend.

## 🧩 Supported integrations

The topic list shows support for several services and app paths. That means ZeroAI is built with cross-service use in mind.

Possible integrations include:

- AI chat providers
- open model routers
- messaging apps
- Android automation flows
- mobile agent actions

## 📝 Common use cases

You can use ZeroAI for tasks like:

- asking an AI for help while on the move
- drafting replies from your phone
- testing different AI providers
- managing chat-based workflows
- using one app instead of many separate tools

## 🖥️ Windows path for getting started

If you are using Windows, the simplest path is:

1. Open the GitHub project page.
2. Check for a release or downloadable app file.
3. Download the file to your Windows PC.
4. If the file is an APK, move it to your Android phone.
5. If the project gives build steps, open the folder in Android Studio.
6. Follow the build steps and run it on a connected Android device

## 🔐 Permissions you may need

ZeroAI may ask for:

- internet access
- notification access
- access to messages or chat apps
- device permissions needed for Android features

Allow only the permissions you want the app to use.

## 📘 Helpful tips

- Use one AI provider first
- Test with a short prompt before you rely on it
- Keep your API key private
- Make sure the app version matches your Android version
- Read the repository files if you want setup details from the author

## 📂 Repo details

- Repository: ZeroAI
- Type: Android AI agent app
- Main languages: Kotlin and Rust
- UI stack: Jetpack Compose
- FFI layer: UniFFI