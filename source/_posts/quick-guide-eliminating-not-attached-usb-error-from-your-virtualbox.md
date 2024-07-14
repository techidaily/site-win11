---
title: "Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox"
date: 2024-07-13T10:04:52.570Z
updated: 2024-07-14T10:04:52.570Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox"
excerpt: "This Article Describes Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox"
keywords: Fix USB NotAttach in VBox,Removing VBBox USB Errors,Solve NotAttachedVBError,Eliminate VM USB Glitches,VirtualBox USB Issue Resolution,QuickGuide,Eradicate Not Attached Error (VBox)
thumbnail: https://thmb.techidaily.com/a23b6166dff1d71405deccff3c580ba47c280d1fae23b982db1e3d6f2479cd12.jpg
---

## Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many [different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the [official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.
6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.
4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the [official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

## Easily Connect USB Devices to Your Virtual Machine Once More

 VirtualBox needs the extension pack to enable connectivity for USB 2.0 and 3.0 devices. Check your USB devices for errors and verify that they mount properly on the host system. Reinstall USB drivers if you face the error again. Lastly, remove VirtualBox from the system and do a fresh installation.


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
<li><a href="https://ai-driven-video-production.techidaily.com/updated-experience-the-future-top-4k-video-demos-you-wont-want-to-miss/"><u>Updated Experience the Future Top 4K Video Demos You Wont Want to Miss</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ultimate-fidelity-in-mac-screen-and-audio-recording/"><u>In 2024, Ultimate Fidelity in Mac Screen & Audio Recording</u></a></li>
<li><a href="https://win11.techidaily.com/1719337024529-get-chrome-back-in-windows-11-quick-recovery-methods/"><u>Get Chrome Back in Windows 11 – Quick Recovery Methods.</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-locate-powershell-console/"><u>What to Do When Windows Can't Locate PowerShell Console</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-speed-setback-by-apps-with-innocuous-exteriors/"><u>Windows 11’S Speed Setback by Apps with Innocuous Exteriors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-android-fun-for-windows-users-through-google-play/"><u>Streamlining Android Fun for Windows Users Through Google Play</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-unlock-creative-potential-crafting-tiktok-videos-using-templates-for-2024/"><u>[New] Unlock Creative Potential  Crafting TikTok Videos Using Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-asus-rog-phone-8-pro-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Asus ROG Phone 8 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-server-stumbled-errors-in-microsoft-store/"><u>Steps to Eliminate Server Stumbled Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/windows-installation-manual-for-chatgpt/"><u>Windows Installation Manual for ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-free-live-streaming-software-and-app-for-all-platforms-2023-list/"><u>[New] Best Free Live Streaming Software and App for All Platforms [2023 List]</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-oculus-setup-fails-windows-1110-strategies/"><u>Addressing Oculus Setup Fails: Windows 11/10 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-shield-your-snapshots-from-times-tide-explore-cost-effective-solutions/"><u>2024 Approved  Shield Your Snapshots From Time's Tide - Explore Cost-Effective Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-web-sites-becoming-win-desktops/"><u>The Art of Web Sites Becoming Win Desktops</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-realme-note-50-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Realme Note 50 Location | Dr.fone</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-how-to-make-your-own-emoji-in-2-ways-step-by-step-guide/"><u>New 2024 Approved How to Make Your Own Emoji in 2 Ways Step-By Step Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-honor-x7b-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Honor X7b | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-facebooks-best-picture-enhancers-top-11-tools-ranked/"><u>[Updated] In 2024, Facebook's Best Picture Enhancers  Top 11 Tools Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-chromebook-shutter-magic-4-simple-steps/"><u>2024 Approved  Chromebook Shutter Magic - 4 Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/4-key-approaches-to-activate-a-dormant-windows-guard/"><u>4 Key Approaches to Activate a Dormant Windows Guard</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disruptions-preventing-unexpected-crashes-in-dwarf-fortress/"><u>Unraveling Disruptions: Preventing Unexpected Crashes in Dwarf Fortress</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-nubia-red-magic-8s-pro-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Nubia Red Magic 8S Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-n-options-for-home-users/"><u>Analyzing Windows N Options for Home Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-peek-through-the-curtain-viewers-disguised-commentaries/"><u>2024 Approved  Peek Through the Curtain  Viewers' Disguised Commentaries</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-stop-device-freeze-non-playing-fb-videos/"><u>[New] In 2024, Stop Device Freeze  Non-Playing FB Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-eye-opening-journey-with-q500/"><u>2024 Approved  The Eye-Opening Journey with Q500</u></a></li>
</ul></div>
