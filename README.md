# 🥚 EggTimer (egg)

A minimalist, non-blocking terminal timer built for Linux power users. 

**EggTimer** allows you to set timers directly from your CLI. It runs in the background, keeping your terminal usable, and triggers a system-native notification and audio alert when time is up.

---

## ✨ Features
* **Zero UI Overload:** Stays out of your way until you need it.
* **Non-Blocking:** Built to be run as a background process.
* **Desktop Integrated:** Uses `libnotify` for standard Linux desktop alerts.
* **Audio Feedback:** Triggers a system alert sound for heads-up notification.
* **Python Powered:** Lightweight with no heavy dependencies.

## 🚀 Installation (The Arch Way)

1. **Clone the repo:**
   ```bash
   git clone https://github.com/MelodyLuciel/eggTimer.git
   cd eggTimer

2. **Make it Executable:**
   ```bash
   chmod +x egg.py
3. **Move it to your PATH:**
   ```bash
   sudo mv egg.py /usr/local/bin/egg

## 🛠️ Usage
* Set a timer in your terminal of choice
  ```bash
  egg 5 &
* Use decimals for seconds
  ```bash
  egg 0.30 &

## 📦 Dependencies

* python3
* libnotify (For notifications)
* pulseaudio or pipewire-pulse (for sound playback)

### Created with ❤️
