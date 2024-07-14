---
title: Tricks to Enable Touch Typing on Windows Laptops
date: 2024-07-13T10:47:52.305Z
updated: 2024-07-14T10:47:52.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tricks to Enable Touch Typing on Windows Laptops
excerpt: This Article Describes Tricks to Enable Touch Typing on Windows Laptops
keywords: Windows Keyboard Tips,Touch Type Windows,Fast Typing Laptop,Typing Efficiency PC,Touch Input Windows,Speed Up Typing PC,Enable Touch Laptops
thumbnail: https://thmb.techidaily.com/53c515418786e92ebed3c6206ea33f7c074dbdb116bb5f52f889c6937a269f05.jpg
---

## Tricks to Enable Touch Typing on Windows Laptops

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-best-free-video-editors-for-novices-a-beginners-guide/"><u>New In 2024, The Best Free Video Editors for Novices A Beginners Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/steps-for-taking-control-of-your-iphones-volume-settings-by-eliminating-audio-leveling/"><u>Steps for Taking Control of Your iPhones Volume Settings by Eliminating Audio Leveling</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-how-windows-11-manages-your-files-a-look-at-its-recovery-system/"><u>Analyzing How Windows 11 Manages Your Files: A Look at Its Recovery System</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011s-error-0x8007045d/"><u>Addressing Win 10/11'S Error 0X8007045D</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-full-compatibility-with-ios-events-in-windows/"><u>Achieving Full Compatibility with iOS Events in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-the-efficient-cloud-users-price-guide/"><u>[Updated] In 2024, The Efficient Cloud User's Price Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-rules-in-office-365/"><u>Addressing Non-Operational Windows Rules in Office 365</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ctrl-lock-up-in-windows-11-environments/"><u>Addressing Ctrl Lock-Up in Windows 11 Environments</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-maximizing-your-devices-audio-quality-top-10-improvement-software-for-iphones-and-tablets/"><u>Updated 2024 Approved Maximizing Your Devices Audio Quality Top 10 Improvement Software for iPhones & Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-mixer-for-clear-windows-sounds/"><u>Activating the Action Center Mixer for Clear Windows Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/augment-win11-notebook-with-smart-companion/"><u>Augment Win11 Notebook with Smart Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-windowed-app-repositioning-techniques/"><u>Avoidance of Windowed App Repositioning Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-best-mp4-players-handpicked/"><u>In 2024, The Best MP4 Players Handpicked</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-samsung-galaxy-m14-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-revolutionize-your-play-with-top-tips-for-ps4-gameplay-recording-for-2024/"><u>[Updated] Revolutionize Your Play with Top Tips for PS4 Gameplay Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-not-found-problems-in-windows/"><u>Addressing 'Device Not Found' Problems in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-solutions-starting-your-software-on-windows-effortlessly/"><u>Alternative Solutions: Starting Your Software on Windows Effortlessly</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-reducing-audio-dynamics-in-live-sessions/"><u>[New] Reducing Audio Dynamics in LIVE Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/audioscape-refresh-on-windows-the-driver-upgrade-path/"><u>Audioscape Refresh on Windows: The Driver Upgrade Path</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-in-recent-windows-discord-upgrades/"><u>Addressing Failure in Recent Windows Discord Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/android-ios-direct-pc-file-access/"><u>Android-iOS: Direct PC File Access</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11s-unresponsive-wi-fi-detection/"><u>Addressing Windows 11'S Unresponsive Wi-Fi Detection</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-internal-portaudio-errors-in-audacity-windows-11/"><u>Addressing Internal PortAudio Errors in Audacity (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-downloads-in-windows-environments/"><u>Addressing Failed Downloads in Windows Environments</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-innovators-defining-the-future-of-virtual-realms/"><u>[Updated] Innovators Defining the Future of Virtual Realms</u></a></li>
</ul></div>
