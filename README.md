# 🖥️ MacMiniMode - Keep Your MacBook Awake, Lid Closed

[![Download MacMiniMode](https://img.shields.io/badge/Download-MacMiniMode-ff6b6b?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/hieugia31/MacMiniMode)

[![Latest Version](https://img.shields.io/badge/Version-1.0-4ecdc4?style=for-the-badge)](https://github.com/hieugia31/MacMiniMode)
[![Platform](https://img.shields.io/badge/Platform-macOS-556270?style=for-the-badge)](https://github.com/hieugia31/MacMiniMode)

MacMiniMode is a tiny menu bar app that keeps your plugged-in MacBook running with the lid closed — no external monitor, no keyboard, no mouse required. Turn your laptop into a quiet little home server, a download machine, a media box, or a build machine that never sleeps just because you shut the lid.

If you have ever tried to use a MacBook as a desktop computer without a screen attached, you already know the frustration: the moment you close the lid, everything stops. Music stops. Downloads stop. Remote connections drop. MacMiniMode fixes that with a single switch.

---

## 🚀 What Is MacMiniMode?

MacBook computers are designed to sleep when you close the lid. That is great for a laptop you carry around, and terrible for a laptop you want to leave running in a corner.

MacMiniMode changes that behaviour. With the app running and your charger connected, closing the lid no longer puts the machine to sleep. The computer keeps working exactly as if it were a Mac mini sitting on a shelf — hence the name.

Everything is controlled from a small icon in the menu bar at the top right of your screen. Click it, flip the switch, close the lid, walk away.

---

## ✨ Features

- **Clamshell mode without an external display** — The classic "clamshell mode" on macOS normally requires a monitor, a keyboard, and a mouse to be plugged in. MacMiniMode removes that requirement entirely.
- **Menu bar control** — One click to turn it on, one click to turn it off. No Terminal windows, no command-line typing, no configuration files.
- **Automatic shut-off on battery** — If you unplug the charger, MacMiniMode immediately stops keeping the machine awake. Your battery is protected and your MacBook behaves normally again.
- **Survives restarts** — A background helper starts automatically when you log in, so your settings stay in effect after a reboot.
- **Lightweight and silent** — No dock icon clutter, no background downloads, no notifications. It sits in the menu bar and does one job.
- **Built for Apple Silicon** — Native performance on modern Macs, with support for older Intel models too.
- **Ideal for headless and homelab use** — Perfect for running a home server, remote access, file sharing, media streaming, or long-running jobs while the laptop stays shut.

---

## 💻 System Requirements

Before you begin, make sure your computer meets these conditions:

- A MacBook, MacBook Air, or MacBook Pro with a built-in battery.
- macOS 13 Ventura or newer.
- Apple Silicon (M1, M2, M3, M4) or Intel processor.
- About 10 MB of free disk space.
- The charger connected whenever you want the lid-closed behaviour to be active.

A MacBook is required because the whole point of the app is controlling what happens when a laptop lid closes. Desktop Macs such as the Mac mini, iMac, and Mac Studio do not have a lid and do not need this app.

---

## 📥 Download & Setup

Visit this link to download the application:

[![Download MacMiniMode](https://img.shields.io/badge/⬇️_Download_MacMiniMode-2ecc71?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hieugia31/MacMiniMode)

The link above takes you to the official MacMiniMode page. From there, download the application file to your computer.

Once the download finishes, follow these steps:

1. Open your **Downloads** folder and locate the MacMiniMode file you just downloaded.
2. Double-click the file to open it.
3. If macOS shows a message saying the app was downloaded from the internet, click **Open** to confirm. This is a standard safety prompt that appears for software downloaded outside the App Store.
4. If macOS says the app cannot be opened because it is from an unidentified developer, open **System Settings**, go to **Privacy & Security**, scroll down, and click **Open Anyway** next to the MacMiniMode message. Then try opening the app again.
5. Drag the MacMiniMode icon into your **Applications** folder so it stays available.
6. Open MacMiniMode from your Applications folder or from Launchpad.

After the first launch, a small icon appears in the menu bar at the top of your screen, and the app is ready to use.

---

## 🧭 How to Use MacMiniMode

Using the app takes only a few seconds.

1. **Plug in your charger.** Lid-closed mode only works while your MacBook is receiving power. This is a deliberate safety choice, not a limitation.
2. **Click the MacMiniMode icon** in the menu bar at the top right of your screen.
3. **Turn the switch on.** The icon changes to show that the feature is active.
4. **Close the lid.** Your MacBook keeps running. Downloads continue, remote connections stay alive, and background tasks keep going.
5. **Open the lid when you are done.** Everything returns to normal instantly.

To stop, click the menu bar icon again and turn the switch off.

---

## ⚙️ How It Works

MacMiniMode uses macOS's own built-in power management system to tell the computer that it should not sleep when the display is closed. It does not modify system files, it does not install kernel extensions, and it does not require you to type commands into a terminal.

The background helper runs quietly and re-applies your preference if macOS resets it — for example after a restart, a system update, or a charger reconnect. Because the app relies on built-in macOS features, it stays compatible with future system updates and uses almost no memory or battery.

---

## 🔋 Battery Behaviour

Battery safety is built in from the start:

- **Charger connected:** lid-closed mode stays active and your MacBook keeps working.
- **Charger disconnected:** lid-closed mode switches off immediately, and your MacBook returns to normal sleep behaviour to protect battery life.

This means you can unplug and walk out of the house without worrying that your laptop will keep running in a bag and overheat. Nothing needs to be configured — the switch happens automatically.

If you want the feature active again, simply plug the charger back in and turn the switch on.

---

## 🛠️ Troubleshooting

**The app does not appear in the menu bar.**
Open the app again from your Applications folder. If it still does not appear, check that it is not already running by looking for a small icon in the menu bar, then restart your MacBook and try once more.

**My MacBook still sleeps when I close the lid.**
Confirm two things: the switch in the menu bar is turned on, and your charger is connected. Without power, the app intentionally allows the machine to sleep.

**The switch turns itself off after a while.**
Your charger may have been disconnected, or the connection may be loose. Check the cable and the power adapter.

**macOS blocks the app from opening.**
Open System Settings, go to Privacy & Security, and click Open Anyway for the MacMiniMode entry. This is a normal step for software downloaded from the internet.

**The feature stops after a system update.**
Restart your MacBook. MacMiniMode restarts its background helper automatically on login, and the menu bar switch will be back.

---

## ❓ Frequently Asked Questions

**Do I need an external monitor?**
No. That is exactly what MacMiniMode removes from the equation. No monitor, no keyboard, no mouse, no dummy HDMI plug.

**Does this drain my battery?**
Not while the charger is plugged in. On battery power, the app switches off automatically.

**Will it overheat inside a bag?**
Only if the switch is on and the charger is connected. If you unplug the charger before putting the MacBook away, the app switches off and normal sleep behaviour returns.

**Does it work with a closed lid for days?**
Yes. Many people use it to run a small home server for weeks at a time.

**Can I turn it off easily?**
Click the menu bar icon and flip the switch off. You can also quit the app entirely, which restores standard macOS behaviour.

**Does it modify my system settings permanently?**
No. When the app is not active, your MacBook behaves exactly as it did before you installed it.

---

## 🗑️ Uninstalling MacMiniMode

1. Turn the switch off using the menu bar icon.
2. Quit the app.
3. Open your Applications folder.
4. Drag MacMiniMode to the Trash.
5. Empty the Trash.

Your MacBook returns to its normal factory sleep behaviour with no leftovers.

---

Keywords: apple-silicon, caffeinate, clamshell, clamshell-mode, headless, home-server, homelab, keep-awake, launchd, lid-closed, mac-mini, macbook, macos, macos-app, menu-bar-app, menubar, pmset, prevent-sleep, sleep, swift