# Security

KiT is a small local Windows program. It holds no accounts, keeps no server, and opens the network only for the opt-in **Check for updates…** path, which talks to this repository's GitHub Releases and nothing else. The full account of what it does and refuses to do is in [Trust](TRUST.md).

## Reporting a problem

If you believe you have found a security issue in KiT, please open a [GitHub issue](https://github.com/SPRIC76/KIT/issues/new) with the version (tray menu shows it), what you saw, and how to reproduce it. If the details should not be public, say so in the issue and a private channel will be arranged before anything sensitive is shared.

You can expect an acknowledgement within a few days. Fixes ship as a normal release with SHA-256 digests beside the files.

## Verifying a download

Every release publishes `KIT-Setup.exe` and `KIT.exe` with matching `.sha256` files. Compare before you run:

```powershell
Get-FileHash .\KIT-Setup.exe
```

The tray updater refuses any download that is not served from GitHub Releases, enforces a size cap, and verifies the SHA-256 digest before it replaces the running copy.

## Scope

In scope: the shipped `KIT.exe` / `KIT-Setup.exe`, the updater, and the manifests published here (Scoop bucket, winget).  
Out of scope: third-party components as installed on your machine (Windows, Python, Tk, PyInstaller), and issues that require an already-compromised user account.

[MIT](LICENSE) · MK1 Enterprise
