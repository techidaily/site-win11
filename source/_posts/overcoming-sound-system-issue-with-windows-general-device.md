---
title: Overcoming Sound System Issue with Windows General Device
date: 2024-06-25T11:45:03.986Z
updated: 2024-06-26T11:45:03.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Sound System Issue with Windows General Device
excerpt: This Article Describes Overcoming Sound System Issue with Windows General Device
keywords: WinSoundTroubleshoot,FixWindowsAudio,AudioSystemRepair,ResolveDeviceNoise,ClearWinMediaError,OptimizePCSound,EliminateWindowAudioIssues
thumbnail: https://thmb.techidaily.com/900dc848292f751f63b27f646fc76a619bc7384a4aedd9106177497020dbae72.jpg
---

## Overcoming Sound System Issue with Windows General Device

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  
![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.
5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  
`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/visual-clarity-in-note-taking-with-obsidian-design/"><u>Visual Clarity in Note-Taking with Obsidian Design</u></a></li>
<li><a href="https://win11.techidaily.com/quick-resolution-for-windows-dism-failure-code-0x800f082f/"><u>Quick Resolution for Windows' DISM Failure Code: 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-audio-configuration-for-spatiality/"><u>Windows 11 Audio Configuration for Spatiality</u></a></li>
<li><a href="https://win11.techidaily.com/address-fixing-non-responsive-function-keys-in-win-11-os/"><u>Address: Fixing Non-Responsive Function Keys in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/suppress-sound-enhancement-in-windows-os/"><u>Suppress Sound Enhancement in Windows OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-song-of-ice-and-fire-top-sites-to-snatch-game-of-thrones-ringtones/"><u>2024 Approved  A Song of Ice and Fire  Top Sites to Snatch Game of Thrones Ringtones</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-amplify-your-voice-basic-changes-on-audacity-made-simple/"><u>New Amplify Your Voice Basic Changes on Audacity Made Simple</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagram-backward-play-a-comprehensive-walkthrough/"><u>2024 Approved  Instagram Backward Play  A Comprehensive Walkthrough</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-online-subtitle-converters-our-recommended-10-for-2024/"><u>Free Online Subtitle Converters  Our Recommended 10 for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-excellent-avi-player-pcmobile-compatibility/"><u>In 2024, Excellent AVI Player - PC/Mobile Compatibility</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-art-of-visual-storytelling-ken-burns-effect-in-final-cut-pro-explained/"><u>Updated The Art of Visual Storytelling Ken Burns Effect in Final Cut Pro Explained</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-10-premium-multitrack-audio-editors-that-outshine-audacity/"><u>New 2024 Approved 10 Premium Multitrack Audio Editors That Outshine Audacity</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>