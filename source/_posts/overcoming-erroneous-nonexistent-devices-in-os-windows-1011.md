---
title: "Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11"
date: 2024-06-25T11:37:43.449Z
updated: 2024-06-26T11:37:43.449Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11"
excerpt: "This Article Describes Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11"
keywords: Windows Device Errors,OS Debugging Tips,Win10/11 Fixes,Erroneous Devices Solve,Non-Existent Device Removal,OS Maintenance Guide,10/11 Device Troubleshooting
thumbnail: https://thmb.techidaily.com/e350204044526aae4dc95dcf2061d143539918222d877d21899914ec625ed9d1.jpg
---

## Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/1719288445449-overcoming-wwin-plus-printer-not-responding-issue-in-windows/"><u>Overcoming WWin + Printer Not Responding Issue in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-bluetooth-pairing-fail-in-windows-devices/"><u>Steps to Tackle Bluetooth Pairing Fail in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-0x800713f-error-on-the-windows-mail-service/"><u>How to Repair 0X800713f Error on the Windows Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-screen-snafus-with-sonic-frontiers-securing-smooth-play-on-w11/"><u>Navigating Screen Snafus with Sonic Frontiers - Securing Smooth Play on W11</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-installation-windows-cab-files-unpacked-and-utilized/"><u>Initiating Installation: Windows CAB Files Unpacked and Utilized</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-boost-virtual-engagement-select-top-10-recorder-software/"><u>[New] Boost Virtual Engagement  Select Top 10 Recorder Software</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-tones-where-to-access-google-pixel-music-for-2024/"><u>Top Tones  Where to Access Google Pixel Music for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-complete-guide-to-masterful-lunapic-photography/"><u>The Complete Guide to Masterful LunaPic Photography</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone 14 Pro Max</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/onetization-contest-dailymovement-vs-youtubes-earnings-battleground/"><u>The Monetization Contest  DailyMovement vs Youtube's Earnings Battleground</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-broadcasting-twitch-to-facebook-friends-easily/"><u>[Updated] 2024 Approved  Broadcasting Twitch to Facebook Friends Easily</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/screen-scribes-a-critical-look-at-modern-recorders-for-2024/"><u>Screen Scribes  A Critical Look at Modern Recorders for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-the-art-of-disabling-youtube-shorts/"><u>[New] Mastering the Art of Disabling YouTube Shorts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-practices-for-secondary-footage-management/"><u>[Updated] Best Practices for Secondary Footage Management</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/digital-domination-diaries/"><u>Digital Domination Diaries</u></a></li>
</ul></div>
