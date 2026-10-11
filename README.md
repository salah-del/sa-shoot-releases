# SA SHOOT

Windows downloads and the update channel for SA SHOOT.

## Download

[Download SA SHOOT Setup](https://github.com/salah-del/sa-shoot-releases/releases/download/v1.5/SA-SHOOT-Setup.exe)

[Release notes and files](https://github.com/salah-del/sa-shoot-releases/releases/tag/v1.5)

Download and open **SA-SHOOT-Setup.exe**, the graphical SA SHOOT launcher. Choose **DOWNLOAD** for a new installation, or **LOCATE GAME** and select the folder containing an existing `SA SHOOT.exe`. A compatible 1.5 installation is reused and needs only the approximately 850 KB launcher integration patch. An incompatible or damaged copy offers installation/repair.

**PLAY** appears only after the required files are installed and verified. Installation never starts the game automatically. Launch the prepared game through the launcher; directly opening its game executable is rejected. Older, unpatched copies need to pass through the new launcher once to enable this behavior. A registered SA SHOOT account is still required before entering the lobby.

Allow approximately 25 GB of free disk space for download, extraction, installation and rollback files. Keep an internet connection available. The executable is not code-signed; Windows may show an unknown-publisher notice. No administrator rights or changes to Windows security settings are required.

The launcher displays real downloaded bytes, speed and estimated remaining time. **PAUSE / RESUME** retains partial downloads; interrupted transfers retry from saved bytes when supported by the download server. Settings includes installation location, file verification and reduced motion. The default game folder is `%LOCALAPPDATA%\Programs\SA SHOOT`. The launcher keeps a separate copy and a Start-menu shortcut after installation or first play.

## Updates

The launcher checks `launcher.json` and verifies installed runtime files before granting a one-use local launch ticket. The game also checks `windows.json` while running. A required game update blocks new play; a match already in progress is allowed to finish. Account data, settings and match history live separately from game files. The local launcher ticket is an application entry check, not tamper-proof DRM.

Players using builds earlier than 1.5 must install this update-enabled release once. The files ending in `.part00`, `.part01`, etc. are parts of a single ZIP and are handled automatically by setup and the updater; they are not individual installers.

## Public test status

Version 1.5 is an **early public test**, not a finished production release. It includes the login/lobby presentation updates, connection feedback, region selection, player identity/notifications, combat report and match history, and the download/update channel.

The launcher integration patch also includes bounded snapshot pipelining and a fresh connection-route attempt for each new match. A two-client, same-computer online round with disconnect/reconnect passed. Intermittent Photon connection/TLS timeouts remain under review. A complete match across independent Internet connections and a real 100-player concurrent load test have **not** been validated. GitHub hosts downloads; Photon and Unity services handle game connectivity.

This repository contains compiled downloads and channel metadata only. The Unity project, account credentials, diagnostic logs and development backups are not distributed here.
