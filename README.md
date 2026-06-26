# 🖥️ Dual-Monitor-Fix-PowerShell - Repair windows monitor display issues easily

[![Download Now](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/mariannecircumpolar189/Dual-Monitor-Fix-PowerShell/releases)

This tool fixes common problems with dual monitor setups on Windows 10 and 11. Use this if your computer fails to detect a second screen, shows the wrong resolution, or creates issues with extended displays. The script resets your display drivers and monitor settings to default values.

## 📋 System Requirements

Confirm your computer meets these requirements before you start:

*   Windows 10 or Windows 11 operating system.
*   Administrative access to your user account.
*   An active internet connection to download the tool.
*   Two or more monitors connected to your graphics card.

This tool works with common graphics cards from NVIDIA, AMD, and Intel. It manages hardware communication via the Windows display interface.

## 📥 Downloading the Software 

1. Visit the [official releases page](https://github.com/mariannecircumpolar189/Dual-Monitor-Fix-PowerShell/releases).
2. Look for the latest version heading at the top of the list.
3. Click the file ending in `.ps1` or the compressed `.zip` file if provided.
4. Save the file to your Downloads folder or your Desktop.

## ⚙️ Running the Fix

Follow these steps to run the repair tool on your machine. You do not need developer tools or complex software to use this.

1. Locate the file you saved in the previous step.
2. Right-click the file named `Dual-Monitor-Fix.ps1`.
3. Select the option that reads **Run with PowerShell**.
4. A blue window will appear on your screen. This is the command line interface.
5. If a security prompt appears, confirm that you want to run the script.
6. The script will open and begin its task. It will check your current display connections and reset your monitor cache.
7. Wait for the window to indicate that the process is finished.
8. Close the window and restart your computer to apply the changes.

## 🛠️ Troubleshooting

If your monitors do not return to normal, try these steps.

*   **Check cables:** Ensure that your HDMI, DisplayPort, or DVI cables fit tightly in both the monitor and the graphics card ports.
*   **Restart the script:** Run the script a second time if the first attempt stops early.
*   **Update drivers:** Visit the website of your graphics card manufacturer to download the latest driver software.
*   **Change ports:** Move your monitor cable to a different port on your graphics card if you have more than one available.
*   **Windows Updates:** Open your Windows Settings and ensure that your system has all recent updates installed.

## 🔍 How it Works

The tool automates a series of tasks that technicians usually perform by hand. It performs the following actions:

*   **Registry Clear:** It removes old monitor cache entries stored in the system registry. Windows creates these entries when it detects a new display. Sometimes these entries become corrupt, which causes your monitors to stop working correctly.
*   **Driver Reset:** It signals the graphics driver to rescan all display outputs. This forces the system to re-identify every monitor connected to your graphics card.
*   **Resolution Refresh:** It forces the display settings service to query your monitors for their native resolution. This fixes cases where the system shows an incorrect, blurry, or stretched image.
*   **Power Cycle:** It resets the display interface power state to clear minor electronic handshake errors between your GPU and your screen.

These steps pose no risk to your data. The script only modifies display settings and temporary system files.

## 🛡️ Safety and Privacy

This program performs local tasks only. It does not connect to external servers or send your personal data over the internet. The script executes only on your machine. You can open the file in standard text editors like Notepad to view the code if you want to verify its actions yourself.

## 💡 Frequently Asked Questions

**Does this fix screen flickering?**
Yes. Flickering is often caused by incorrect refresh rate settings. This script resets those settings to the values supported by your monitor.

**Will I lose my desktop icons?**
Sometimes, moving monitors or changing resolutions shifts your icons. You may need to drag them back to your preferred positions after the fix finishes.

**Can I use this on a laptop?**
This tool works with laptops that have external monitors connected. It does not affect the built-in laptop screen.

**Do I need to uninstall my current drivers first?**
No. This tool works alongside your existing drivers to fix communication errors. You do not need to delete or change your graphics driver software.

**What if the script shows an error in red text?**
Red text in the PowerShell window usually indicates that the script lacks the permissions needed to modify system settings. Ensure you are signed in as an administrator and try running the file again by right-clicking and selecting Run as Administrator.

**Does this provide long-term fixes?**
In most cases, yes. If monitor issues return, repeat the process. Hardware issues, such as faulty cables or broken ports, may require you to replace your physical equipment.