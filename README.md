<img width="1200" height="630" alt="image-1790601851279" src="https://github.com/user-attachments/assets/2b6ecdf7-3cf7-4d7b-89c6-6bb7618c3dc2" />

# KiT is a quiet Windows companion that keeps your session awake (Light) or darkens the desktop without sleeping the PC (Night), with wakeable screensaver faces; Off returns ordinary Windows.

<img src="https://spric76.github.io/KIT/img/bar-light.png" width="366" alt="The KiT bar in Light, with Night and Off beside it">

 Single instance, no telemetry, no account, no cloud, no keystroke recording, no clipboard access, no fake input. SHA-256-verified releases on GitHub. Two launches: installer (current-user scope) and portable (no admin needed). Also on winget: `winget install --id SPRIC76.KIT -e`.

One program. Entirely local. No accounts. No telemetry. No theater (except the screensavers).

**[Download KiT](https://github.com/SPRIC76/KIT/releases/latest/download/KIT-Setup.exe)** · [See it first](https://spric76.github.io/KIT/) · [Trust](TRUST.md)

---

## Three modes

| Mode | What it does |
|---|---|
| **Light** | The PC and display stay awake. Quiet and ready. |
| **Night** | Wakeable dark — Screen darkens, the machine stays working. A touch of activity brings you back. |
| **Off** | Regular old sleepy Windows again. |

One gesture each. No schedules. No idle.  No hassle.

---

## The Instrument

A low-profile bar sits just above the taskbar — there when you want it, gone when you don’t. Double-click the tray icon to show or hide it. Right-click the tray for settings, Ghost, Hold Night, Auto after idle, and the Night faces.

### Toggles/Keybinds

| Keys | Mode |
|---|---|
| **Ctrl+Shift + D** | Light · Default mode |
| **Ctrl+Shift + K** | Night · Auto-wakes on mouse/keyboard activity |

Hold either 2 seconds for Off · double-tap to flip to the opposite mode (Light → Night, Night → Light).

### Options

- Optional **Ghost** — transparent, click-through Control Bar/UI Element.
- Optional **Hold Night** — stay dark until you say otherwise. **Esc** or **Space** leaves Hold Night.
- Optional **Auto after idle** — from Off or Light, enter Light or Night after 1, 5, 10, 15 or 30 quiet minutes.
- Optional **Night brightness** — how deep Night goes, from a soft dim to fully dark.
- Optional **Monitor brightness** — a convenience for displays with DDC/analog brightness controls; sets the panel's own brightness from the tray instead of reaching for its buttons, and does nothing on displays without DDC (most laptop panels).
- Optional run at sign-in.

Remembers how you left it.

### Night faces

Night screensavers/faces: Blackout, **Cosmos** (cosmic anomalous marbles), Slither, Orbit, DVD — or **Monitor off**, which turns your displays off to save power while everything else keeps running. Burn-safe motion. Built to feel alive, not busy.

<img src="https://spric76.github.io/KIT/img/face-cosmos-a.png" width="720" alt="Cosmos, one of Night's faces, as KiT draws it">

---

## Get KiT

Both launches live on the [latest release](https://github.com/SPRIC76/KIT/releases/latest).

See it first: [spric76.github.io/KIT](https://spric76.github.io/KIT/) — every mode and face, then the download.

| Launch | For | Download |
|---|---|---|
| **Installer** | Start menu, repair, uninstall | [`KIT-Setup.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT-Setup.exe) |
| **Portable** | No install — run from any folder | [`KIT.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT.exe) |

Installer: download [`KIT-Setup.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT-Setup.exe) → Next → Finish → open **KiT** from Start.  
Portable: download [`KIT.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT.exe) → double-click.

```bat
winget install --id SPRIC76.KIT -e
```

```bat
scoop bucket add kid https://github.com/SPRIC76/KIT
scoop install kid
```

More paths: [Download](docs/DOWNLOAD.md). How it earns trust: [Trust](TRUST.md).

---

Windows 10 or 11. Nothing else to install.

KiT · [Freeware](LICENSE)

[MK1 Made](https://mk1made.us) • *deliberately designed, intelligently refined*
<p align="right">Artificer Intelligence</p>
