# Download

Both launches live on the [latest release](https://github.com/SPRIC76/KIT/releases/latest). One program. Pick the path that fits.

| Launch | For | Download |
|---|---|---|
| **Installer** | Start menu, repair, uninstall | [`KIT-Setup.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT-Setup.exe) |
| **Portable** | No install — run from any folder | [`KIT.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT.exe) |

**Installer:** download [`KIT-Setup.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT-Setup.exe), run it, open **KiT** from Start. Run Setup again to repair. Remove it from **Settings → Apps**. No administrator required for ordinary use.

**Portable:** download [`KIT.exe`](https://github.com/SPRIC76/KIT/releases/latest/download/KIT.exe) and run it from any folder you like. To remove it, turn off **Run at Windows sign-in** in the tray, then delete the file. Preferences live quietly with your other app data — not beside the portable.

**Updates:** tray **Check for updates…** refreshes the copy you are already running. Setup remains the path for first install, repair, and uninstall.

## Winget

```bat
winget install --id SPRIC76.KIT -e
winget upgrade --id SPRIC76.KIT -e
winget uninstall --id SPRIC76.KIT -e
```

## Scoop

```bat
scoop bucket add kid https://github.com/SPRIC76/KIT
scoop install kid
scoop update kid
scoop uninstall kid
```

Or take either launch from the [latest release](https://github.com/SPRIC76/KIT/releases/latest). Digests (SHA-256) sit beside the files. [Verifying a download](../SECURITY.md#verifying-a-download) shows how to check one.

How it earns trust: [Trust](../TRUST.md).

KiT · [Freeware](../LICENSE)

[MK1 Made](https://mk1made.us) • *deliberately designed, intelligently refined*
<p align="right">Artificer Intelligence</p>
