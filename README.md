# NetMate for macOS — Downloads

Signed and notarized releases of **NetMate**, a menu-bar app that measures your connection, explains what slows it down, tracks data budgets per network, and saves data on slow or metered networks.

**[Download the latest version →](https://github.com/fil-technology/netmate-releases/releases/latest)**

- Requires **macOS 26** or later (Apple silicon and Intel).
- Each release is signed with Developer ID (Sviatoslav Fil, team L7T5538V86) and notarized by Apple. A `.sha256` checksum is attached to every release.

## Install

1. Download `NetMate-<version>.dmg` from the latest release.
2. Open it and drag **NetMate** to **Applications**.
3. Launch NetMate. It lives in the menu bar (⌥⌘N).
4. Optional: enable the Safari extension in Safari › Settings › Extensions.

Verify a download:

```bash
shasum -a 256 -c NetMate-1.1.0.dmg.sha256
```

## Privacy

No account, no telemetry, no backend. Measurements stay on your Mac. NetMate never intercepts encrypted traffic.

---

This repository contains release builds only. The source code is private.
