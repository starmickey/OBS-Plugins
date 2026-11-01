# 🎥 OBS Studio Scripts & Plugins

A curated collection of custom Lua scripts and tools for **OBS Studio** designed to enhance your live streams, marathons, and subathons.

---

## 🛠️ Included Scripts

### ⏱️ Days Countdown Timer (`countdown_timer.lua`)

A robust countdown timer script for OBS text sources that supports multi-day durations formatted neatly as **`DDd HHh MMm SSs`** (e.g., `02d 05h 30m 15s`).

#### Features

* **Full Multi-Unit Support:** Automatically splits total duration into Days, Hours, Minutes, and Seconds.
* **Smart Activation:** Automatically starts counting down when the designated text source becomes active in a scene.
* **Custom Final Text:** Displays a custom message (e.g., *"Starting soon (tm)"*) once the timer hits zero.
* **Hotkey & Reset Support:** Includes a manual reset button in the script properties and full frontend hotkey binding support to reset the timer on command.

---

## 📥 Installation

1. Download or clone this repository and save the `.lua` script file to a secure folder on your computer (OBS scripts run directly from your local drive).
2. Open **OBS Studio**.
3. In the top menu bar, navigate to **Tools** > **Scripts**.
4. In the **Lua Scripts** tab, click the **`+` (Add Scripts)** button at the bottom.
5. Locate and select your downloaded script file.

---

## ⚙️ Configuration & Usage

Once loaded into OBS's script manager, you can configure the script via the properties panel on the right side of the Scripts window:

* **Duration (minutes):** Set how long the countdown should last in total minutes (supports long-term timers up to 100,000+ minutes).
* **Text Source:** Select an existing Text Source (`Text (GDI+)` or `Text (FreeType 2)`) from your OBS scenes to display the countdown.
* **Final Text:** The message that will be shown once the countdown reaches `0`.
* **Reset Timer Button:** Manually reset and restart the countdown instantly.

> **Tip:** You can also bind a dedicated hotkey to **Reset Timer** via OBS's main **Settings > Hotkeys** menu so you can restart your countdown with a single keypress!

---

## 🚀 Future Additions

Stay tuned! More OBS automation tools, overlay scripts, and utility plugins will be added to this repository over time. 

---

## 📄 License

Feel free to use, modify, and adapt these scripts for your own streams!