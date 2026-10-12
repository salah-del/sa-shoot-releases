# SA SHOOT

Windows downloads for SA SHOOT.

## Download

[Download SA SHOOT Launcher 3.0](https://github.com/salah-del/sa-shoot-releases/releases/download/v1.6/SA-SHOOT-Setup.exe)

[Version 1.6 release notes](https://github.com/salah-del/sa-shoot-releases/releases/tag/v1.6)

Open **SA-SHOOT-Setup.exe**. Choose **DOWNLOAD** for a new installation, or **LOCATE GAME** and select the folder containing **SA SHOOT.exe** and **SA SHOOT_Data**.

Already on game 1.5? **UPDATE GAME** downloads about **827 MB** for 22 changed files, reusing the rest of the game. **PLAY** unlocks after all required files verify. Your account and settings are stored separately. A registered SA SHOOT account is required before entering the lobby.

## Updating the launcher

**If you have Launcher 2.0, download and open Launcher 3.0 once. Keep your game installed.** Version 2.0 did not have self-update functionality. Version 3.0 and later offer **UPDATE LAUNCHER** inside the application, preserve your game folder, and recover the previous launcher if the replacement fails to start.

## Updating the game

Only missing, changed or damaged files download. Large updates are split into resumable ranges; there is no fallback that downloads the whole game for an existing verified installation. A change to a Unity content file still requires downloading that changed file in full.

The launcher shows download bytes, speed and estimated remaining time. **PAUSE / RESUME** retains partial downloads. Settings include game location, verification/repair and reduced motion. The default game folder is `%LOCALAPPDATA%\Programs\SA SHOOT`. A separate launcher copy and Start-menu shortcut are kept after installation or first play.

New players need the complete current game, assembled automatically from verified content in this and earlier releases. Files named `.partNN` are download data, not individual installers. Keep an Internet connection and enough free disk space for downloads, installation and rollback; the launcher checks space before installing.

The launcher checks updates before play and after leaving a match. Game 1.6 also checks while running; an active match is allowed to finish before returning to the launcher for an update. Launch the game through the launcher. The local launch ticket is an application entry check, not tamper-proof DRM.

The executable is not code-signed, so Windows may display an unknown-publisher notice. No administrator access or changes to Windows security settings are required.

## Public test status

Version 1.6 is an **early public test**. It adds the industrial Wraith lobby, animated 2.5D portraits, updated interface and sound cues, and file-based game updates.

The real 1.5-to-1.6 local upgrade, all 284 runtime hashes, launcher handshake, resumable downloads, repair, interrupted-install recovery and launcher replacement/rollback were tested. Lobby routes, settings, Unity Play/Stop cycles and live region probes were also checked.

Earlier two-client same-computer online round/reconnection tests passed. Intermittent Photon connection/TLS timeouts remain under review. A complete match across independent Internet connections and a real 100-player concurrent load test have **not** been validated. GitHub hosts downloads; Photon and Unity services handle gameplay connectivity.

This repository contains compiled downloads and channel metadata only. The Unity project, source code, account credentials, diagnostic logs and development backups are not published here.
