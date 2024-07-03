---
title: "Step-by-Step: Setting Up DNS on Windows 11"
date: 2024-06-25T11:33:54.549Z
updated: 2024-06-26T11:33:54.549Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Setting Up DNS on Windows 11"
excerpt: "This Article Describes Step-by-Step: Setting Up DNS on Windows 11"
keywords: Windows DNS Setup Guide,DNS Installation W11,DNS Configuration Win11,Stepwise DNS Setup,Win11 DNS Setup Process,Configuring DNS in Win11,DNS Setup for Windows 11
thumbnail: https://thmb.techidaily.com/c010ac8c095463e82a02d0121c6ae49a6934a26c38ee953e2dee2be944508d80.jpg
---

## Step-by-Step: Setting Up DNS on Windows 11

 Clearing the DNS cache and restarting the DNS cache services are the first troubleshooting tips that anyone should try when diagnosing Windows network issues. But when you open the Service utility to stop or restart the service, all the options are grayed out in the context menu.

 But how do you configure the service if nothing works? Well, that’s where the trusty old method of registry tweaking comes in handy. We will elaborate on the process to disable and configure the DNS Client service as per your liking.

## How to Disable the DNS Client Service Using the Registry Editor

 Even if you try to use the Command Prompt and run the command to stop the service, it responds with a “the requested pause, continue, or stop is not valid for this service.” message. So, you need to edit the registry settings of the DNS Client service to disable it.

 However, fiddling with Windows Registry is a risky endeavor, and you should[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) as well as a[System Restore point](https://www.makeuseof.com/windows-reset-system-restore-difference/) . That way, you can always revert to the last known good system configuration.

Repeat the following steps to disable the DNS client service:

1. Press**Win + R** to[open the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type "regedit" and press**Ctrl + Shift + Enter** to open the Registry Editor with administrator privileges.
2. Navigate to the address bar in the Registry Editor windows and paste the following path:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\services\Dnscache`
3. In the Dnscache key, locate the**Start** DWORD value and double-click on it to edit its properties.
4. Change the**Value Data** to**4** and keep the base as**Hexadecimal** . Click on the**OK** button.  
![Disable the DNS Client Service Using Registry Editor-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-the-dns-client-service-using-registry-editor-1.jpg)
5. Close the Registry editor.
6. Press**Win + S** and type**services.msc** . Click on the**Run as administrator** option.
7. Locate the DNS Client service. You will see that the service is still running but the Startup Type field shows Disabled.  
![Disable the DNS Client Service Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-the-dns-client-service-using-registry-editor-2.jpg)
8. Close the Services utility and restart your system to apply the changes.
9. Relaunch the Services panel and find the DNS Client service. It will have a blank status and Startup Type as disabled.  
![Disable the DNS Client Service Using Registry Editor 3-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-the-dns-client-service-using-registry-editor-3-1.jpg)

 Now, DNS Client Service won’t start until you manually tweak its registry key again.

## Is It Possible to Configure the DNS Client Service Without the Registry Editor?

 Unfortunately, no. As we described above, you will have to manually change the registry value of the Start DWORD every time you want to stop the DNS Client service on your system.

 Even if you set the service to Manual mode, it will still not display anything in the context menu when you right-click on it. So, it is evident that Microsoft doesn’t want anyone tinkering with the DNS Client service in any condition.

 If you are curious about how to change the Startup Type of the DNS Client service using Registry Editor, here are the following Data Values and what they do:

**Hexadecimal Value Data (2)** \- DNS Client service is set to run automatically at startup.

**Hexadecimal Value Data (3)** \- DNS Client service is set to Manual mode but will automatically run at startup.

**Hexadecimal Value Data (4)** \- DNS Client service is set to Disabled mode and won’t run until you change the value.

 Open the Registry Editor with administrator privileges and navigate to the DNS Client service path as described in the previous section. Now, you can change the**Value Data** of the**Start DWORD value** to any of the numbers described above.

## How to Quickly Disable the DNS Client Service Using Command Prompt

 It is possible to disable the DNS Client Service using Command Prompt as well. All you need to do is run the command to change the Startup Type of the service to "Disabled". Here’s how to do it:

1. Press**Win + R** to open the Run command box. Type "cmd" and press the**Ctrl + Shift + Enter** keys to[start the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
2. Now, type the following command and press the**Enter** key to execute it:  
`reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Dnscache" /v Start /t REG_DWORD /d 4 /f`
3. After you see the “The operation completed successfully.” message, type "exit" and press**Enter** to close the Command Prompt window.  
![Disable the DNS Client Service Using CMD-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-the-dns-client-service-using-cmd-1.jpg)
4. **Restart** your system for the changes to take effect. DNS Client Service will remain disabled on your system.

## Tweak Your DNS Client Service Easily

 Microsoft makes it very difficult to disable the DNS Client service on Windows 10 and 11\. But you can use the registry hack to disable the service whenever the need arises. Or if you want to disable the service quickly, use the Command Prompt method.


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
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-sleep-state-in-windows-11s-usb-cores/"><u>How to Prevent Sleep State in Windows 11'S USB Cores</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-task-tracker-update-rate-in-windows-11/"><u>Enhancing Live Task Tracker Update Rate in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-hello-fingerprint-malfunctions-easily/"><u>Navigating Windows Hello Fingerprint Malfunctions Easily</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-clutter-eliminate-onedrive-symbol-from-explorer/"><u>Confronting Clutter: Eliminate OneDrive Symbol From Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-tutorial-to-edit-windows-files-metadata-dates/"><u>The Complete Tutorial to Edit Windows Files' Metadata Dates</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-dual-camera-request-error-code-0xa00f4243/"><u>Dealing with Dual Camera Request Error (Code 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-supercharge-video-memory-on-windows-devices/"><u>Tips to Supercharge Video Memory on Windows Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transform-your-footage-with-premiere-pros-advanced-techniques-for-360-editing/"><u>In 2024, Transform Your Footage with Premiere Pro's Advanced Techniques for 360° Editing</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-techs-choice-best-online-screen-capturing-tools/"><u>[New] In 2024, Tech's Choice  Best Online Screen Capturing Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/comedy-cache-hot-names-and-trends-in-the-laughter-world-for-2024/"><u>Comedy Cache  Hot Names & Trends in the Laughter World for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-amplify-videographic-excellence-choose-from-these-7-audios/"><u>[New] 2024 Approved  Amplify Videographic Excellence - Choose From These 7 Audios</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/creating-hit-tiktok-emote-videos/"><u>Creating Hit TikTok Emote Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/innovative-image-integration-software-for-visual-enthusiasts/"><u>Innovative Image Integration Software for Visual Enthusiasts</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-xiaomi-redmi-note-12-pro-4g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Xiaomi Redmi Note 12 Pro 4G Location Settings | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-google-pixel-fold-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Google Pixel Fold If I Forgot Security Code or Password? | Dr.fone</u></a></li>
</ul></div>
