# SA SHOOT

Windows downloads and the update channel for SA SHOOT.

## Download

[Download SA SHOOT Setup](https://github.com/salah-del/sa-shoot-releases/releases/download/v1.5/SA-SHOOT-Setup.exe)

[Release notes and files](https://github.com/salah-del/sa-shoot-releases/releases/tag/v1.5)

Close the game, download the setup application, and run it. Setup downloads the current release, verifies every part and the complete package using SHA-256, then installs to `%LOCALAPPDATA%\Programs\SA SHOOT`. It opens the game after installation. A SA SHOOT account is required before entering the lobby.

Allow approximately 25 GB of free disk space for download, extraction, installation and rollback files. Keep an internet connection available. The executable is not code-signed; Windows may show an unknown-publisher notice. No administrator rights or changes to Windows security settings are required.

If a download fails, run setup again. Completed verified parts are reused. If you already installed the game elsewhere, run setup with `--install-dir "D:\Games\SA SHOOT"`, replacing that path with your installation folder.

## Updates

The game checks the public `windows.json` channel on launch and periodically while running. A required update blocks new play; a match already in progress is allowed to finish. The updater verifies downloaded files before replacing the installation. Account data, settings and match history live separately from game files.

Players using builds earlier than 1.5 must install this update-enabled release once. The files ending in `.part00`, `.part01`, etc. are parts of a single ZIP and are handled automatically by setup and the updater; they are not individual installers.

## Public test status

Version 1.5 is an **early public test**, not a finished production release. It includes the login/lobby presentation updates, connection feedback, region selection, player identity/notifications, combat report and match history, and the download/update channel.

Known issue: intermittent Photon connection/TLS timeouts can prevent joining or reconnecting. Complete online match testing and a real 100-player concurrent load test have **not** passed. Local game/system tests do not establish online service capacity. GitHub hosts downloads; Photon and Unity services handle game connectivity.

This repository contains compiled downloads and channel metadata only. The Unity project, account credentials, diagnostic logs and development backups are not distributed here.
