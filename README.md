# Monomode client

[**Download Monomode for Windows**](https://github.com/Monomode/client-updates/releases/latest/download/Monomode-Setup.msi)

## Install once

Run the installer to install Monomode or upgrade an existing installation. Use the **Monomode** desktop/Start menu shortcut to play.

From **1.0.16**, leaving **Launch Monomode** checked opens Monomode when you click **Finish** after installation, upgrade or repair. Uncheck it to leave the client closed. If an older installer did not launch on Finish, upgrade using the download above; this installer behavior cannot be repaired by a client JAR update alone.

The Windows installer from **1.0.15** onward starts without a debug terminal. If you installed 1.0.14, run this installer once to replace its console-enabled executable; normal automatic client updates cannot change that installed Windows executable setting.

## Future updates

1. Close the game and the Monomode/RSProx launcher window.
2. Open **Monomode** again from its shortcut.
3. The launcher checks for an approved client release, verifies it, and downloads it automatically when needed.

You do **not** need to download another installer for normal client releases. Starting RuneLite or RSProx directly bypasses the Monomode update check, so always reopen the Monomode shortcut after a game update.

Updates are installed in your user folder, not over files in Program Files. RuneLite profiles and settings are not reset. If an update download is interrupted, restarting Monomode retries it; previously verified client files are retained.

## Safety

Client update metadata is signed, and downloads are checked against the signing key embedded in the installer. This is separate from Windows Authenticode/SmartScreen publisher verification.

This repository hosts public player installers, client binaries and update metadata only. It does not contain the private game server repository, credentials, player data or signing private keys. Client releases are selected for Monomode's live game version; a newer official RuneScape revision is not automatically substituted.
