---
title: Overcoming Erroneous Non-Existing Device Alert on Win 11
date: 2024-07-13T10:11:20.645Z
updated: 2024-07-14T10:11:20.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Erroneous Non-Existing Device Alert on Win 11
excerpt: This Article Describes Overcoming Erroneous Non-Existing Device Alert on Win 11
keywords: Windows 11 Error Fix,W11 False Devices Alert,Unknown Device Warning Win11,Resolve Win11 Alerts,Disable Non-Existent Device Windows,Win11 Erroneous Device Notify,Eliminate W11 Fake Errors
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
---

## Overcoming Erroneous Non-Existing Device Alert on Win 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to [running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

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

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to [unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

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
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-art-of-gamers-vocal-disguise-selecting-the-ultimate-toolkit/"><u>Updated In 2024, The Art of Gamers Vocal Disguise Selecting the Ultimate Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/surging-downloads-overcome-the-01kbs-stall-on-windows/"><u>Surging Downloads: Overcome the 0.1KB/S Stall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pathway-errors-with-windows-devices/"><u>Addressing Pathway Errors with Windows Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-channel-building-gear-a-quick-start-guide/"><u>[New] 2024 Approved  Channel-Building Gear  A Quick Start Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-gaming-excellence-recorded-best-pcmac-software-compiled/"><u>2024 Approved  Gaming Excellence Recorded  Best Pc/Mac Software Compiled</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-xbox-mic-in-windows-11/"><u>Troubleshooting Non-Functional Xbox Mic in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-screens-overcoming-windows-setup-woes/"><u>Secure Your Screens: Overcoming Windows Setup Woes</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-journey-into-jazz-mysteries-beyond-commonplace-knowledge-for-2024/"><u>New Journey Into Jazz Mysteries Beyond Commonplace Knowledge for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-wi-fi-showing-limited-access-in-windows-11/"><u>9 Ways to Fix Wi-Fi Showing Limited Access in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/top-hashtags-to-leverage-on-tiktok-for-more-followers/"><u>Top Hashtags to Leverage on TikTok for More Followers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-seamlessly-on-windows-1110-systems/"><u>Reinstating Synapse Seamlessly on Windows 11/10 Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-studio-audit-earnings-review/"><u>[New] YouTube Studio Audit  Earnings Review</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-vivo-y28-5g-by-fonelab-android-recover-data/"><u>The way to get back lost data from Vivo Y28 5G</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-windows-understanding-report-generation-and-analysis/"><u>The Art of Windows Understanding: Report Generation & Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oneplus-11-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On OnePlus 11 5G</u></a></li>
<li><a href="https://win11.techidaily.com/restore-steam-game-symbols-from-nowhere/"><u>Restore Steam Game Symbols From Nowhere</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-strategies-for-improving-youtubefacebook-video-quality/"><u>In 2024, Strategies for Improving YouTube/Facebook Video Quality</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functionality-to-windows-tablet-gestures/"><u>Restoring Full Functionality to Windows Tablet Gestures</u></a></li>
<li><a href="https://fake-location.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-memory-integrity-feature-grayed-out-on-windows-11/"><u>7 Ways to Fix the Memory Integrity Feature Grayed Out on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-key-differences-between-windows-terminal-and-powershell/"><u>Understanding Key Differences Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-online-video-editing-for-free-the-top-options-compared-for-2024/"><u>Updated Online Video Editing for Free The Top Options Compared for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-error-pitfalls-with-anydesk-on-windows-platforms/"><u>Avoiding Error Pitfalls with AnyDesk on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-lock-screen-timer-breakage/"><u>Repairing Window's Lock Screen Timer Breakage</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-insta-growth-hacks-todays-essential-hashtags-guide/"><u>2024 Approved  Insta Growth Hacks  Today's Essential Hashtags Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-beyond-imagination-the-real-world-significance-of-snapchat-emojis/"><u>[Updated] 2024 Approved  Beyond Imagination  The Real-World Significance of Snapchat Emojis</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-access-denied-a-comprehensive-guide-to-5-solutions/"><u>Winning Against 'Access Denied': A Comprehensive Guide to 5 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-games-on-windows-avoid-common-setup-pitfalls/"><u>Xbox Games on Windows: Avoid Common Setup Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/7-w11-ui-aspects-that-seem-out-of-place/"><u>7 W11 UI Aspects That Seem Out of Place</u></a></li>
<li><a href="https://win11.techidaily.com/a-slumberful-cycle-for-your-pcs-life/"><u>A Slumberful Cycle for Your PC's Life</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-0x800700e1-on-w10w11/"><u>Resolving Error Code: 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
</ul></div>
