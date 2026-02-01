# Dih🥀

> Open-source click multiplier for Wayland, built in Rust. Fun, fast, and totally FOSS.

**Dih🥀** is a tool that multiplies your mouse clicks. Designed for gamers and enthusiasts, it works on Wayland and lets you boost your click speed dynamically.

---

## Features

* 🖱 Multiply mouse clicks based on CPS (clicks per second)
* 🎛 Adjustable **CPS Threshold** and **Multiplier**
* ⚡ Lightweight, written in Rust
* 🖥 Works on Wayland
* 🛠 Fully open-source — contributions welcome

---

## How It Works

1. **Launch Dih🥀**

   * Auto-detection of devices is available but may not always work 🙂. Use **manual selection** to pick your mouse.

2. **Set Parameters**

   * **CPS Threshold:** When your click rate exceeds this value, Dih🥀 will start multiplying clicks.

     * Recommended: `6 CPS` — ideal for gaming without interfering with normal usage.
   * **Multiplier:** The number of extra clicks added per original click.

3. **Activate / Deactivate**

   * Click **Activate** to enable Dih🥀, **Deactivate** to disable it.
   * A small indicator shows if the tool is currently active.

4. **Reset Selections**

   * Resets the CPS Threshold and Multiplier to default values.

---

## Installation
Make sure you have dependecies,install via mediafire it exceeds limit on git also unzip it,cd into it use ls to see install etc script,run both install and setup_rules script
Install Link:https://www.mediafire.com/file/n7zxuoqp4xdkncz/DihMouse.zip/file
* After running the scripts, **log out and log in** (or reboot).
* Dih🥀 will be added as a desktop entry — you can now launch it from your application menu.

## Dependencies

* Rust & Cargo
* g++
* CMake
* pkg-config
* libevdev
* Qt5-Declarative
* Qt5-QuickControls2
* uinput kernel module

## Contributing

Dih🥀 is fully open-source. Feel free to fork, submit issues, or create pull requests. Let’s make this tool even better together!



<img width="505" height="668" alt="Screenshot_20260201_234347" src="https://github.com/user-attachments/assets/74992970-8809-4ff1-a289-68b6d19746c0" />





