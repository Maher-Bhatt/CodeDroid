<div align="center">

<img src="docs/07-github-readme-1280x420.png" alt="CodeDroid - a mobile code editor that actually runs your code" width="100%">

# `</>` CodeDroid

### A mobile code editor for Android — write & run code on your phone.

[![Release](https://img.shields.io/github/v/release/Maher-Bhatt/CodeDroid?color=C9A66B&label=release)](https://github.com/Maher-Bhatt/CodeDroid/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Maher-Bhatt/CodeDroid/total?color=C9A66B)](https://github.com/Maher-Bhatt/CodeDroid/releases)
![Platform](https://img.shields.io/badge/platform-Android%208%2B-C9A66B)
![Built with](https://img.shields.io/badge/Kotlin%20%2B%20Jetpack%20Compose-C9A66B?logo=kotlin&logoColor=white)

**[⬇ Download the latest APK](https://github.com/Maher-Bhatt/CodeDroid/releases/latest)**

</div>

---

## What is CodeDroid?

CodeDroid turns your phone into a real coding environment. Open a file, write code,
hit **Run** — Python and JavaScript execute **on-device**, no server, no cloud.

## Features

- ▶️ **Run on device** — Python (Chaquopy) & JavaScript (Rhino), fully offline execution
- 🎨 **18 languages** with syntax highlighting — Python, JavaScript, TypeScript, C, C++, Java, Kotlin, Go, Rust, PHP, Ruby, Swift, Dart, HTML/CSS, SQL, JSON, Markdown
- 🖥️ **Integrated terminal** — colored output, stdin, stop/clear/copy
- 🗂️ **File tabs**, find & replace, undo/redo, auto-close brackets, code folding
- 🌐 **Live HTML/CSS preview**
- ☕ **Warm dark theme** — premium brass palette, easy on the eyes
- ⌨️ **Coding keyboard toolbar** — quick symbols above the keyboard

## Showcase

<div align="center">
<img src="docs/05-multidevice-1920x1080.png" alt="CodeDroid screens" width="100%">
</div>

## Install

1. Download `app-release.apk` from the [Releases](https://github.com/Maher-Bhatt/CodeDroid/releases/latest) page.
2. Open it → allow **"install from unknown source"** → Install.
3. Needs internet on first launch (editor engine loads from CDN).
4. Android 8+ (arm64 devices).

## Tech stack

| Layer | Tech |
|-------|------|
| UI | Kotlin · Jetpack Compose · Material 3 |
| Editor | CodeMirror (in a WebView) |
| Python runtime | Chaquopy |
| JavaScript engine | Rhino |
| Storage | Storage Access Framework · DataStore |

## Build from source

```bash
git clone https://github.com/Maher-Bhatt/CodeDroid.git
# Open in Android Studio, let Gradle sync, then Run.
```

## Roadmap

- [ ] Bundle the editor offline (no CDN dependency)
- [ ] Google Drive sync
- [ ] More runtimes

---

<div align="center">

Built by **Maher Bhatt** · **Velocity Web**

</div>
