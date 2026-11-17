# NSO Auto Continue — by t0ji

Windows launcher utility for repeating Hunting House with Ninja Saga Online's built-in auto battle.

Download the current package from [Releases](https://github.com/daffaari/nso-auto-continue/releases/latest). Extract it to a writable folder, close older Auto Continue copies, open the fullscreen AIR launcher at HH, then select it and press **Start pilihan**.

- Selects recognized groups containing more than one boss, clicks Fight, waits for Battle Complete, claims, handles the Level Up check, then repeats.
- Keeps the AIR launcher rendering outside the desktop while you work in other apps. Pause/F8 restores it.
- **Check Update** checks this public repository. A newer version is installed only after confirmation. The application pauses bots/restores launcher windows before restarting, and verifies download size, SHA-256, assembly identity, and version.
- Keeps the previous executable as `NSO-Auto-Continue.exe.previous`. Updates reopen paused; press Start when ready.

The calibrated AIR game area is 1366 x 705. The game must remain running; this tool does not provide auto battle itself. Chrome support is experimental; full Chrome-cycle validation is pending and Chrome minimize recovery is not supported. Live Level Up check input remains unverified; recognition uses original capture fixtures.

This repository contains public distribution files and release notes only. Application source is maintained in a separate private repository. Game captures, user logs, credentials, and source archives are not distributed here. This is an independent tool, not an official NSO product.
