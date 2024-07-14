---
title: Eliminate Edge and Keep Your System Clean (W11)
date: 2024-07-13T09:50:10.012Z
updated: 2024-07-14T09:50:10.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Edge and Keep Your System Clean (W11)
excerpt: This Article Describes Eliminate Edge and Keep Your System Clean (W11)
keywords: Clean W11 System,Edge Removal Guide,System Hygiene Tips,W11 Upkeep Secrets,Keep Systems Pure,Edgeless Computer Care,Maintain W11 Clarity
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## Eliminate Edge and Keep Your System Clean (W11)

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to [edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://win11.techidaily.com/unveiling-windowsstore-directory-secrets-for-users/"><u>Unveiling WindowsStore Directory Secrets for Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-failed-security-codes-in-game-launcher-windows-edition/"><u>Quick Fixes for Failed Security Codes in Game Launcher Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-sculpt-personalized-digital-laughs-now-for-2024/"><u>[New] Sculpt Personalized Digital Laughs Now for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-shaky-video-fix-it-for-free-the-best-online-stabilization-tools/"><u>Updated In 2024, Shaky Video? Fix It for Free The Best Online Stabilization Tools</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentiality-of-runtime-brokers-for-modern-os-functionality/"><u>The Essentiality of Runtime Brokers for Modern OS Functionality</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-leveraging-youtube-for-dynamic-instagram-stories/"><u>[Updated] In 2024, Leveraging YouTube for Dynamic Instagram Stories</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-identifying-top-video-capturing-tools-for-win11/"><u>[Updated] 2024 Approved  Identifying Top Video Capturing Tools for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-fault-eco-error/"><u>Resolved: Printer Fault #Eco-Error</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/toolbox-tutorial-windows-core-components-management/"><u>Toolbox Tutorial: Windows' Core Components Management</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-audio-clarity-10-pro-tips-for-high-quality-recordings/"><u>[Updated] Audio Clarity  10 Pro Tips for High-Quality Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-correcting-unresponsive-video-files/"><u>Tips for Correcting Unresponsive Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/androidios-techniques-screening-google-meets-for-2024/"><u>Android/iOS Techniques  Screening Google Meets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wonders-enhance-windows-11-explorer-visibility/"><u>Windowed Wonders: Enhance Windows 11 Explorer Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-winerror-with-code-0x8019/"><u>Resolving WinError with Code 0X8019</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-unidentified-usb-port-problems/"><u>Overcoming Windows 11'S Unidentified USB Port Problems</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-end-persistent-login-error-alerts-on-pc/"><u>Methods to End Persistent Login Error Alerts on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-no-cost-voice-modifier-transform-your-valorant-gameplay/"><u>In 2024, Ultimate No-Cost Voice Modifier  Transform Your Valorant Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/unveiling-advanced-features-of-vlc-for-2024/"><u>Unveiling Advanced Features of VLC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-windows-store-failures-error-x80072f30-guide/"><u>Swiftly Correcting Windows Store Failures: Error X80072F30 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719293621682-mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-absence-of-battery-life-duration-in-pcs-running-win-11/"><u>Overcoming the Absence of Battery Life Duration in PCs Running Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-voice-and-music-from-bluetooth-headset/"><u>Troubleshooting Windows: Voice & Music From Bluetooth Headset</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/direct-youtube-video-capture-guide-for-2024/"><u>Direct YouTube Video Capture Guide for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-viewership-with-effective-game-streaming/"><u>2024 Approved  Maximizing Viewership with Effective Game Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-zte-blade-a73-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any ZTE Blade A73 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-your-sub4sub-potential-the-critical-pre-entry-guide/"><u>2024 Approved  Unlocking Your Sub4sub Potential  The Critical Pre-Entry Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-guide-top-7-superior-wet-proof-camcorders/"><u>[Updated] Ultimate Guide  Top 7 Superior Wet-Proof Camcorders</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-monetize-youtube-video-the-ultimate-guide-to-ad-revenue/"><u>[New] Monetize YouTube Video | The Ultimate Guide to Ad Revenue</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-leading-10-streamlined-ad-free-tiktok-downloader-for-2024/"><u>[New] Leading 10  Streamlined, Ad-Free TikTok Downloader for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-guide-to-youtube-live-streaming/"><u>The Ultimate Guide to YouTube Live Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inoperative-windows-11-speech-recognition/"><u>Resolving Inoperative Windows 11 Speech Recognition</u></a></li>
</ul></div>
