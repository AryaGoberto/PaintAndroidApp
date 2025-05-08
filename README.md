# SimplePaint_JetpackCompose

A simple **Paint application** built with **Jetpack Compose** that allows users to draw, erase, select colors, adjust brush size, reset, and save their artwork to the device gallery.

## Features

- 🖌️ **Free Drawing** on a Canvas using touch input
- 🌈 **Color Picker** (Red, Green, Blue, Black)
- 📏 **Brush Size Selector** (in pixels)
- 🧽 **Eraser Mode** to draw in white
- ♻️ **Reset Button** to clear the canvas
- 💾 **Save Button** to export drawing to the device gallery (with permission handling)

## Tech Stack

- **Kotlin** – Android’s preferred programming language
- **Jetpack Compose** – Modern UI toolkit
- **Material 3** – For clean and consistent components
- **Canvas API** – Core drawing surface
- **Coroutines** – For async image saving
- **Activity Result API** – Runtime permission handling

## Demo Video
<img src="https://github.com/AryaGoberto/PaintAndroidApp/blob/main/app/src/Demo/paintt.gif?raw=true" height="450" />


## How to Run

### Prerequisites:
- Android Studio Hedgehog or newer
- Android SDK 24+
- Physical Android device (recommended) or emulator

### Setup:

1. **Clone the repository**
   ```bash
   git clone https://github.com/AryaGoberto/SimplePaint_JetpackCompose.git
