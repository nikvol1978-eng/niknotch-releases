# NikNotch

**NikNotch turns your MacBook's notch into a live island.** Music, timers, notifications, your AirPods' battery,
your calendar and more appear right where the camera is, and grow into a full panel when you hover over them.

It's a modified version of [Atoll](https://github.com/Atoll-Labs/Atoll), which is built on
[Boring Notch](https://github.com/TheBoredTeam/boring.notch). Free, no account, no analytics: your data stays on
your Mac.

**[⬇ Download the latest version](../../releases/latest)**: under **Assets**, click the `.dmg` file.

---

## What it does

- **Music:** album art and a moving visualiser in the notch; play, pause and skip from it, or swipe sideways.
- **Smart Notch:** when several things are going on (music, a timer, a meeting, an AI agent), the notch shows what
  matters most. Swipe or click the dots to switch, and see them all in the **Live** tab.
- **Notifications** from your apps appear in the notch for a few seconds.
- **Battery:** click the battery icon for your Mac's battery and your AirPods' left, right and case levels.
- **Timer and Pomodoro**, your **calendar**, **weather**, and a **shelf** to drop files on.
- **Command bar:** press **⌃⌥Space** (Control-Option-Space) and type "timer 25 minutes", "open Safari"…
- **AI agents (optional):** follow Claude Code, Codex or Cursor sessions, with a heads-up when they need you or finish.
- **Face Unlock (optional, experimental):** unlocks your Mac when it sees you. See the warning below.

**Needs:** a MacBook with a notch, running macOS 14.6 or later.

---

## How to install

Takes about 5 minutes. macOS blocks the app the first time it opens, because NikNotch is a free personal project and
isn't registered with Apple's paid developer programme. Steps 3 and 4 show how to allow it, and you only do that once.

**Before you start:** if you use Boring Notch, NotchNook or Atoll, quit it. Two notch apps at once fight over the notch.

### 1. Download
Open the [latest release](../../releases/latest) and, under **Assets**, click **`NikNotch-<version>.dmg`**.
Double-click the downloaded file.

### 2. Drag it into Applications
A window opens showing **NikNotch**, an arrow, and your **Applications** folder. Drag NikNotch onto Applications.
("READ ME FIRST" in that window has these same instructions.)

### 3. Open it, and click Done when macOS blocks it
Open your Applications folder and double-click **NikNotch**. macOS shows a message like:

> **"NikNotch" Not Opened**
> Apple could not verify "NikNotch" is free of malware that may harm your Mac or compromise your privacy.

Click **Done**. Don't click "Move to Bin". The exact wording varies between macOS versions.

### 4. Allow it in Privacy & Security
1. Open **System Settings** and click **Privacy & Security** in the sidebar.
2. Scroll down to **Security**. There's a line saying NikNotch was blocked.
3. Click **Open Anyway**, confirm with Touch ID or your password, then click **Open**.

No "Open Anyway" button? Try opening NikNotch once more (step 3) and come back. It shows for about an hour after
the last attempt.

### 5. The welcome screens
NikNotch opens with a short setup. Each screen explains itself, and everything is optional:
- **Camera:** only for the mirror, a quick look at yourself from the notch.
- **Calendar:** to show your upcoming events.
- **Music:** pick the app you play music with (Spotify, Apple Music…).
- **What you use:** choose what you'd like in the notch. You can change all of it later.

### 6. Say yes to the permissions you want
macOS asks the first time a feature needs each one:

| Permission | What it's for |
|---|---|
| Accessibility | Media keys, and showing your notifications in the notch |
| Bluetooth | AirPods and headphone battery levels |
| Location | Your local weather |
| Calendar, Reminders | Your events and reminders in the notch |
| Camera | The mirror, and Face Unlock if you turn it on |

For **Accessibility**, macOS shows a pop-up: click **Open System Settings** and switch NikNotch on in the list.

That's it. **Hover over the notch** to open it.

---

## Using it

- **Hover** over the notch to open it; move away to close it.
- **Swipe down** on the notch to open it, **up** to close it, **sideways** to switch between what's running.
- **⌃⌥Space** opens the command bar.
- **Right-click the notch → Settings** to change anything, or to quit.
- NikNotch starts by itself when you log in (turn that off in Settings → General).

## Face Unlock (experimental, off by default)

Face Unlock unlocks your Mac when it sees you, by typing your Mac password on the lock screen for you. Turn it on in
**Settings → Face Unlock**.

**Please read first:** a Mac's camera only sees a flat picture, so this is much less secure than iPhone Face ID, and
a video of you could fool it. Keep the strictness on **Heavy**: then it needs a real blink or a small head turn, so
a photo of you won't unlock it. You can switch it off, and delete everything it stored, in Settings → Face Unlock.

## Updates

NikNotch updates itself. It checks once a day, downloads new versions in the background, and installs them the next
time it quits (for example when you restart). Your settings and permissions are kept, and there's no warning to
click through again. To update straight away: **Settings → Software Update → Restart to Update**.

Every update is signed, and NikNotch refuses anything that isn't. Installed copies read `appcast.xml` from the latest
release.

**Got NikNotch before version 2.3?** Those copies can't update themselves. Install the latest DMG once by hand
(steps 1–4), and it updates itself from then on.

## If something's not right

- **The notch flickers, or two things fight over it:** another notch app is running. Quit it, and remove it from
  System Settings → General → Login Items.
- **No notifications in the notch:** switch NikNotch on in System Settings → Privacy & Security → Accessibility, and
  check the app isn't switched off in NikNotch's Settings → Appearance.
- **AirPods' battery doesn't show:** make sure they're connected to this Mac (Bluetooth menu), and that NikNotch has
  Bluetooth permission.
- **To remove it:** right-click the notch → Quit, then move NikNotch from Applications to the Bin.

---

NikNotch is free software under the GNU General Public License v3. Each DMG includes the complete source code
("NikNotch source code.zip") and the licences of everything it uses. Face Unlock is based on
[Glance](https://github.com/jonnyoo/glance) (MIT). Not affiliated with or endorsed by Apple, or the Atoll, Boring
Notch or Glance authors.
