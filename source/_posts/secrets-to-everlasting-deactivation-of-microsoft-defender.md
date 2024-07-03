---
title: Secrets to Everlasting Deactivation of Microsoft Defender
date: 2024-06-25T11:27:07.360Z
updated: 2024-06-26T11:27:07.360Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secrets to Everlasting Deactivation of Microsoft Defender
excerpt: This Article Describes Secrets to Everlasting Deactivation of Microsoft Defender
keywords: Defender Shutdown Secrets,Lasting Disable MS Defender,Eternal Defender Off Switch,Permanent MS Defender Stop,Endless Deactivate Defender,Perpetual Dismantle Defender,Infallible Disable Defender
thumbnail: https://thmb.techidaily.com/8e7429f26cf226f9f9f144f8b464e629b87419e8b1e2596cca527bf6aeb943f1.jpg
---

## Secrets to Everlasting Deactivation of Microsoft Defender

 Microsoft bundles an antivirus program with every copy of the Windows operating system. Microsoft Defender was released in 2006 and has since been integral to every new Windows operating system release. Surprisingly, it is good at identifying and isolating malware on your system and offering real-time protection.

 But have you ever tried disabling Microsoft Defender? Unless you install a third-party antivirus program, it continues to run and monitor your system. Even if you disable the real-time protection, it turns back on after some time. Don’t worry! We will discuss multiple methods to disable Microsoft Defender for good.

## Why Does Microsoft Make It Difficult to Disable Microsoft Defender?

 Microsoft Defender offers robust security against malware and has evolved over time. You can use it to keep your system safe from malware and do not need to spend on any third-party antivirus app. But Microsoft realizes that users can expose their system to attackers if they disable Microsoft Defender completely.

 So, as a fail-safe method, Microsoft Defender turns back on after some time, even if you disable it. In the older version of Windows, disabling real-time protection was enough, but now it takes a lot more to disable Microsoft Defender.

 But what if you want to install and use a third-party app that Microsoft Defender repeatedly flags as malicious? Or if you want to reduce the load on your system resources? Well, then you have to dive deep into Windows Security settings and disable real-time protection as well as other associated protection measures.

 This guide will teach you how to disable Microsoft Defender permanently. It will stay off until you undo the steps you perform in this guide. If you only want Microsoft Defender to turn off for a short amount of time, check out[how to turn off Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) for a more temporary solution.

## Disable Tamper Protection First

 Tamper Protection makes sure that no other apps can make changes to the Microsoft Defender settings on your computer. You don't need to[enable Tamper Protection](https://www.makeuseof.com/how-to-activate-tamper-protection-defender/) because it is active by default. If you want to completely disable Microsoft Defender (including real-time protection), you must disable Tamper Protection first. Here’s how to do it:

1. Press**Win + S** and type Windows Security. Click on the**Open** option to launch the app.
2. Click on the**Virus and threat protection** option on the home page.
3. Find the Virus and threat protection settings section and click on the**Manage settings** option.
4. Scroll down and click on the**Tamper Protection** toggle to disable it.  
![Disable Tamper Protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Disable-Tamper-Protection-2.jpg)
5. Close the Windows Security app.

## How to Disable Microsoft Defender in Windows 11

 We have already disabled Tamper Protection, so it won't interfere when you disable Microsoft Defender using GPE, Registry Editor, or any third-party tool. Here are the following methods that work flawlessly to disable the inbuilt security app on Windows 11:

### 1\. Disable Microsoft Defender Using Group Policy Editor

 Group Policy Editor is an excellent tool using which you can customize Windows settings with ease. However, it is only reserved for Windows Pro and Enterprise users. Check out[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you're using that version.

 Here’s how to disable Microsoft Defender using Group Policy Editor:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**gpedit.msc** in the text input area and press the Enter key.
2. Group Policy Editor will launch. Click on the**Computer Configuration** option on the home page.
3. Navigate to**Administrative Templates > Windows Components** .
4. Locate and click on the Microsoft Defender Antivirus option. Double-click on the**Turn-off Microsoft Defender Antivirus** policy to edit its settings.  
![Disable Windows Defender Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-policy-editor.jpg)
5. Select the**Enabled** radio button and click on the**Apply** button.
6. Lastly, click on the**OK** button and close the Group Policy Editor. Restart your system and open Windows Security.

### 2\. Disable Microsoft Defender Using Registry Editor

 Windows 11 Home users cannot use the Group Policy Editor. But you can tweak the registry to disable Microsoft Defender on your system. However, before making any changes, please create a registry backup and create a system restore point. That way, you can always undo any changes you make to the registry.

Repeat the following steps to disable Microsoft Defender:

1. Press**Win + S** to open Windows Search and type**Regedit** . Click on the**Run as administrator** button.
2. In the Registry Editor windows, go to the address bar and paste the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender
3. Right-click and select**New > DWORD (32-bit) Value** .
4. \`Click on the newly created DWORD (32-bit) Value and name it**DisableAntiSpyware** .
5. Double-click on the DisableAntiSpyware value and set the**Value Dat** a to**1** . Keep the**Base** as**Hexadecimal** .  
![Disable Windows Defender Using Group Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-registry-editor.jpg)
6. Close the Registry Editor and restart your system to apply changes.
7. Launch Windows Security and visit the Virus and threat protection section. You will see a “ **No active antivirus provider. Your device is vulnerable.** ” message.

### 3\. Disable Microsoft Defender Using CMD

 You can even use the Command Prompt app to disable Microsoft Defender. All you need to do is paste a registry modification command, and it will keep Microsoft’s default antivirus solution out of the picture. Here’s how to do it:

1. Press**Win + R** to launch the Run command box. Type**cmd** in the text input area and press**Ctrl + Shift + Enter** key to launch Command Prompt with admin privileges.
2. Now, type the following command and press the enter key:  
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
3. You will see a “**The operation completed successfully.** ” message after the successful execution of the above command.  
![Disable Windows Defender Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-cmd.jpg)
4. Type**exit** to close the Command Prompt window and restart your system.

### 4\. Disable Microsoft Defender Using Winaero Tweaker

 If you hate tweaking the registry or find running commands too complex, you can use a Windows customization program like Winaero Tweaker. It is a GUI application, so you will find it easier to search for various Windows settings and disable them in a few clicks.

Repeat the following steps:

1. Visit the[Winaero Tweaker download](https://winaero.com/download-winaero-tweaker/) page and download the installer file on your system.
2. Install Winaero Tweaker and right-click on the application and select the**Run as administrator** option.
3. Click on the search icon and type Defender. Click on the**Microsoft Defender \\ Disable Microsoft Defender** search result.  
![Disable Windows Defender Using Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-winaero-tweaker.jpg)
4. Then, click on the**Disable Microsoft Defender** checkbox. Scroll down and click on the**Reboot now** button.
5. Wait for your computer to restart. Microsoft Defender will be inactive on your system.

### 5\. Disable Microsoft Defender Using Ultimate Windows Tweaker

 Like Winaero Tweaker, the Ultimate Windows Tweaker is also a Windows customization app. You can easily enable and disable multiple Windows operating system settings and features which are otherwise very difficult to locate. Repeat the following steps:

1. Go to the[Ultimate Windows Tweaker download webpage](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the tool.
2. Extract all its files into a separate folder. Then select the tool and run it with administrator privileges.
3. Click on the**Search For Tweaks** option and type defender. Then click on the**Go** button and select the**Disable Microsoft Defender** option from the list.
4. Select the checkbox next to the**Disable Microsoft Defender** option and click on the**Apply Tweaks** button. You will see a Windows popup that will inform you whether the tweak was successful or not.  
![Disable Windows Defender Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-ultimate-windows-tweaker.jpg)
5. Finally, click on the**Close** button and restart your system.

## Permanently Disable Microsoft Defender on Windows 11

 Microsoft Defender is a pain to disable on your system because of multiple fail-safe methods built into Windows Security. So, disable Tamper Protection and then process with a method to disable Microsoft Defender. However, do not leave your system open to malware infestation, and use a third-party antivirus if you don’t like Defender.


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
<li><a href="https://win11.techidaily.com/boost-your-pcs-safety-with-these-7-password-generators/"><u>Boost Your PC's Safety with These 7 Password Generators</u></a></li>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/11-fresh-features-in-windows-11-post-update-milestone/"><u>11 Fresh Features in Windows 11, Post-Update Milestone</u></a></li>
<li><a href="https://win11.techidaily.com/examining-the-role-and-relevance-of-wasd-in-windows/"><u>Examining the Role and Relevance of WASD in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-address-winget-malfunctioning-in-windows-11/"><u>Easy Steps to Address Winget Malfunctioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pivotal-security-titans-winning-passwords-in-windows-11/"><u>Pivotal Security Titans: Winning Passwords in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-link-between-edge-and-irrelevant-taskers/"><u>The Link Between Edge and Irrelevant Taskers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-8-exemplary-templates-dominate-social-media-creatives/"><u>[Updated] 8 Exemplary Templates Dominate Social Media Creatives</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-rotate-your-iphone-videos-for-free-top-5-apps/"><u>New 2024 Approved Rotate Your iPhone Videos for Free Top 5 Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/fb-live-integration-with-cable-tv-for-2024/"><u>FB Live Integration with Cable TV for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-5-best-video-denoisers/"><u>2024 Approved 5 Best Video Denoisers</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-dominance-in-video-landscape-mirrorless-vs-dslr-cameras/"><u>[New] Dominance in Video Landscape  Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-prime-10-video-edits-boost-your-webcam-experience/"><u>2024 Approved  Prime 10 Video Edits  Boost Your Webcam Experience</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-webinar-archiving/"><u>[New] 2024 Approved  The Ultimate Guide to Webinar Archiving</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/trivia-trek-exploring-yts-fascinating-figures-and-infographics-for-2024/"><u>Trivia Trek  Exploring YT's Fascinating Figures and Infographics for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-comparative-look-at-rgb-and-srgb-for-designers/"><u>2024 Approved  A Comparative Look at Rgb and Srgb for Designers</u></a></li>
</ul></div>
