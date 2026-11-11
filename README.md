# Combo Notch

*Combo Notch was called NikNotch until version 2.6.5. If you have NikNotch, it updates itself to Combo Notch.*

**Combo Notch turns the notch at the top of your MacBook screen into a live strip, like the iPhone's Dynamic Island.**
Music, timers, files and notifications appear around the notch, with extras for the lock screen and the desktop.
Hover over the notch and it grows into a full panel.

**[⬇ Download the latest version](../../releases/latest)**: under **Assets**, click the `.dmg` file.
More about it, pricing and the privacy policy: **[combostweaks.com/notch](https://combostweaks.com/notch)**.

**Needs:** an Apple silicon Mac (M1 or newer) with macOS 14.6 or later. It's made for MacBooks with a notch: it may run
on other Macs, but they aren't supported. Intel Macs can't run it. No account.

---

## Free and Pro

Everything is free right now. Pro is planned to start with version 2.7. After that, the notch and its music player
stay free, and everything else needs Pro. You'll be able to buy Pro once or monthly, from Lemon Squeezy.
To hear when it's on sale, join the waiting list on **[combostweaks.com/notch](https://combostweaks.com/notch)**.

One download for Free and Pro: a Pro licence key unlocks more of the same app.

## What it does

- **Music:** album art, controls and lyrics in the notch (Spotify, Apple Music and others).
- **The Tools tab:** units, emoji, a stopwatch, a scratchpad, links, a message that scrolls across the notch like an
  LED sign, a water reminder, sounds to focus or sleep to, Screen Time (off until you turn it on), and your sales and
  website visitors.
- **Timers**, your **calendar** with a Join button for video meetings, **weather** with a 7-day forecast, and your
  Mac's and AirPods' **battery**.
- **Notifications** from the apps you choose appear in the notch.
- **A shelf** you drag files onto, **clipboard history**, a colour picker and notes.
- **Smart Notch:** when several things are going on, the notch shows what matters most. See them all in the **Live** tab.
- **Command bar:** press **⌃⌥Space** (Control-Option-Space) and type, for example "timer 25 minutes" or "5 km to mi".
- **Lock screen and desktop:** lock-screen widgets, the song's moving video when you lock your Mac while music plays,
  Luxury Wallpapers, a depth clock, and Face Unlock (experimental, off by default: read the warning below).

## Privacy

No account, no usage analytics, no tracking and no crash reports. Some features talk to other companies, for example
weather, lyrics, and the AI features with your own key. The
**[privacy policy](https://combostweaks.com/privacy)** lists each one, what it sends and how to turn it off.

---

## How to install

Takes about 5 minutes.

**Before you start:** if you use Boring Notch, NotchNook or Atoll, quit it. Two notch apps at once fight over the notch.

### 1. Download
Open the [latest release](../../releases/latest) and, under **Assets**, click the file ending in **`.dmg`**
(for example `ComboNotch-2.6.16.dmg`). Double-click the downloaded file.

### 2. Drag it into Applications
A window opens with **Combo Notch**, an arrow and your **Applications** folder. Drag Combo Notch onto Applications.
("READ ME FIRST" in that window has these steps too.)

### 3. Open it, and click Done when macOS stops it
Double-click **Combo Notch** in Applications. macOS says something like **"Combo Notch" Not Opened**, because Combo
Notch isn't registered with Apple's paid developer programme yet. Click **Done**, not "Move to Bin". The wording varies
between macOS versions.

### 4. Allow it in Privacy & Security
1. Open **System Settings → Privacy & Security** and scroll down to **Security**, where it says Combo Notch was blocked.
2. Click **Open Anyway**, confirm with Touch ID or your password, then click **Open**.

You do this once: updates don't need it. No button? Open Combo Notch once more (step 3) and come back; it shows for
about an hour.

### 5. The welcome screens
A short setup, and everything is optional: the camera (for the mirror), your calendar, the app you play music with,
and what you'd like in the notch. You can change all of it later.

### 6. Say yes to the permissions you want
macOS asks for some straight after the first launch, some during setup (you can skip those), and some only when you
first use a feature. For **Accessibility** it shows a pop-up: click **Open System Settings** and switch Combo Notch on.
On its first run Combo Notch also turns on Open at Login, and macOS shows its usual "login item added" notice.

| Permission | What it's for | When macOS asks |
|---|---|---|
| Accessibility | The volume and brightness pop-ups, notifications in the notch, and Face Unlock | Straight after the first launch |
| Location | Lock-screen weather | Straight after the first launch |
| Bluetooth | Headphone and AirPods battery levels | Straight after the first launch |
| Downloads folder | Download progress in the notch | Straight after the first launch |
| Camera | Camera features such as the mirror and Face Unlock | During setup (you can skip it), or when you first use one |
| Calendars, Reminders | Your events and reminders in the notch | During setup (you can skip it) |
| Music, Apple Music | Controlling the Music app, and song details from Apple Music | The first time a song plays in Apple's Music app |
| Screen Recording | The 3D lean in Lid Close Effect, Screen Actions, and Screen Assistant screenshots | When you first use one of them |
| Spotify, Notes | Controlling Spotify, and syncing with Apple Notes | When you first use them |
| Local Network | Sharing files with LocalSend | When you first share |
| System audio recording | The real-time music waveform | When you turn it on |
| Touch ID | The Private Shelf and Face Unlock | When you use them |

That's it. **Hover over the notch** to open it.

---

## Using it

- **Hover** over the notch to open it, and move away to close it.
- **Swipe down** on the notch to open it, **up** to close it, **sideways** to switch between what's running.
- **⌃⌥Space** opens the command bar.
- **Right-click the notch** for Settings (to change anything) or Quit.
- It starts by itself when you log in (you can turn that off in Settings).

## Face Unlock (experimental, off by default)

When the camera recognises you, Face Unlock types your Mac password on the lock screen for you. Turn it on in
**Settings → Lock Screen → Face Unlock**.

**Please read first:** a Mac's camera sees only a flat picture, so this is much less secure than iPhone Face ID, and a
video of you could fool it. Keep the strictness on **Heavy**: then it needs a real blink or a small head turn, so a
photo of you won't unlock it. You can turn it off, and delete everything it stored, in the same place.

## Updates

Combo Notch updates itself. It checks about once a day, downloads new versions in the background, and installs them by
itself when it quits or after 10 idle minutes. Your settings and permissions are kept. To check straight away, click
**Check Now** in **Settings → Updates & About → Software Update**, or **Check for Updates…** in the menu bar icon's menu.

Every update is signed with our own key (this is separate from Apple's check in step 3), and Combo Notch refuses an
update that has been changed or damaged. Installed copies read `appcast.xml` from the latest release.

**Had NikNotch before version 2.3?** Install the latest version once by hand (steps 1 to 4), and it updates itself
from then on.

## If something's not right

- **The notch flickers, or two things fight over it:** another notch app is running. Quit it, and remove it from
  System Settings → General → Login Items.
- **No notifications in the notch:** switch Combo Notch on in System Settings → Privacy & Security → Accessibility,
  then search Combo Notch's Settings for "notifications" and check that the app you want notifications from is
  switched on.
- **AirPods' battery doesn't show:** check they're connected to this Mac, and that Combo Notch has Bluetooth permission.
- **To remove it:** right-click the notch → Quit, then move Combo Notch from Applications to the Bin.

Still stuck? Email **support@combostweaks.com** and say it's about Combo Notch. Never send your full licence key.

---

Combo Notch is a modified version of [Atoll](https://github.com/Atoll-Labs/Atoll), which is built on
[Boring Notch](https://github.com/TheBoredTeam/boring.notch). Face Unlock is based on
[Glance](https://github.com/jonnyoo/glance) (MIT). It's free software under the GNU General Public License v3
(GPL-3.0): every DMG includes the full source code ("Combo Notch source code.zip") and the licences of everything it
uses. Not affiliated with or endorsed by Apple, or the Atoll, Boring Notch or Glance authors.
