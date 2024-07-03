---
title: Guidelines to Rectify Erroneous Device Listings in Windows
date: 2024-06-25T11:30:41.098Z
updated: 2024-06-26T11:30:41.098Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Rectify Erroneous Device Listings in Windows
excerpt: This Article Describes Guidelines to Rectify Erroneous Device Listings in Windows
keywords: Fixing WIN Errors,Eradicating WIN Listings,Remedying WIN Mislist,Cleaning WIN Errors,Correct WIN Device Err,Solve WIN List Flaws,Unlist WIN Devices Incorrectly
thumbnail: https://thmb.techidaily.com/b024a84a41e25a10e99a735d71f0138708aa747c63be7c3be4720f86eba5080f.jpg
---

## Guidelines to Rectify Erroneous Device Listings in Windows

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
<li><a href="https://win11.techidaily.com/navigating-ftdibussys-why-it-compromises-windows-memory/"><u>Navigating ftdibus.sys: Why It Compromises Windows Memory</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-avoiding-endless-xbox-app-cycle/"><u>Quick Cure: Avoiding Endless Xbox App Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-precision-crafting-win11-self-extractables/"><u>The Path to Precision: Crafting Win11 Self-Extractables</u></a></li>
<li><a href="https://win11.techidaily.com/an-effective-guide-to-fix-error-0xc0000001-on-windows-pcs/"><u>An Effective Guide to Fix Error 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-impact-on-performance-the-unseen-effect-of-disguised-software/"><u>Hidden Impact on Performance: The Unseen Effect of Disguised Software</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/delve-into-artificially-inspired-visuals-how-to-use-paint-cocreator-win11/"><u>Delve Into Artificially Inspired Visuals: How to Use Paint Cocreator (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/critical-hardware-scan-tools/"><u>Critical Hardware Scan Tools</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-14-plus-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On Apple iPhone 14 Plus</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-canon-tips-for-effective-time-lapse-photography/"><u>[New] Canon Tips for Effective Time-Lapse Photography</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-easy-steps-to-extract-and-save-your-youtube-watch-lists/"><u>[Updated] Easy Steps to Extract and Save Your YouTube Watch Lists</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-spellbinding-tones-validity-of-the-vocal-transformation-app-questioned-check-out-more/"><u>In 2024, Spellbinding Tones  Validity of the Vocal Transformation App Questioned - Check Out More</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/canvas-kids-discover-10-free-kid-friendly-art-makers-for-mac-for-2024/"><u>Canvas Kids  Discover 10 Free, Kid-Friendly Art Makers for Mac for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-deciphering-the-technicalities-of-recmeister-screen-recording/"><u>[New] In 2024, Deciphering the Technicalities of Recmeister Screen Recording</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-insiders-method-for-rl-recording-for-2024/"><u>[Updated] The Insider's Method for RL Recording for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-view-gpx-files-online-and-offline-solutions-of-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>How to View GPX Files Online and Offline Solutions Of Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-audience-friendly-approach-to-pc-audio-recording-using-audacity-gratis/"><u>Updated In 2024, Audience-Friendly Approach to PC Audio Recording Using Audacity Gratis</u></a></li>
</ul></div>
