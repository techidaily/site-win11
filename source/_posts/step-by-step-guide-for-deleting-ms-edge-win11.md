---
title: Step-by-Step Guide for Deleting MS Edge Win11
date: 2024-06-25T11:37:10.704Z
updated: 2024-06-26T11:37:10.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide for Deleting MS Edge Win11
excerpt: This Article Describes Step-by-Step Guide for Deleting MS Edge Win11
keywords: Delete MS Edge,Win11 Edge Removal,Edge Browser Uninstall,Deleting Win11 Edge,Remove MS Edge Win11,Win11 Edge Delete Guide,MS Edge Uninstallation
thumbnail: https://thmb.techidaily.com/035705869a176d12c457c62dcd5ac8433382a242da2e6ee8d5c9aeccc24af52d.jpg
---

## Step-by-Step Guide for Deleting MS Edge Win11

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

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

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
<li><a href="https://win11.techidaily.com/finding-the-absent-hypervisor-fix-for-xc0351000-error/"><u>Finding the Absent Hypervisor - Fix for XC0351000 Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dual-users-conflict-with-one-ms-login/"><u>Bypassing Dual Users’ Conflict with One MS Login</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/re-activate-your-pc-addressing-error-code-22-in-windows-11/"><u>Re-Activate Your PC: Addressing Error Code 22 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-login-delays-windows-and-rust-edition/"><u>Resolving Steam Login Delays: Windows & Rust Edition</u></a></li>
<li><a href="https://win11.techidaily.com/winupgrade-hurdles-overcoming-error-code-xc004f050/"><u>WinUpgrade Hurdles: Overcoming Error Code Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-the-experts-choice-identifying-the-top-11-high-quality-fee-free-speech-alteration-tools-for-iphone-and-android-users/"><u>2024 Approved The Experts Choice Identifying the Top 11 High-Quality, Fee-Free Speech Alteration Tools for iPhone & Android Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-small-businesss-safest-video-conferencing-top-picks/"><u>2024 Approved  Small Business's Safest Video Conferencing Top Picks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-samsung-galaxy-xcover-7-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Samsung Galaxy XCover 7 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-how-to-take-photos-while-recording-videos-on-iphone/"><u>In 2024, How to Take Photos While Recording Videos on iPhone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/crafting-a-perfect-tiktok-identity-in-minutes-for-2024/"><u>Crafting a Perfect TikTok Identity in Minutes for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-edit-video-tags-with-ease-best-mp4-editors-for-windows-and-mac-for-2024/"><u>Updated Edit Video Tags with Ease Best MP4 Editors for Windows and Mac for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-honor-x50-gt-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Honor X50 GT using Video Repair Utility on Windows? </u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-2023-facebook-video-downloader-application-for-mobilewinmac/"><u>[New] 2024 Approved  2023 | Facebook Video Downloader Application for Mobile/Win/Mac</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enrich-your-brain-with-these-15-ultimate-science-youtubes/"><u>[Updated] Enrich Your Brain with These 15 Ultimate Science Youtubes</u></a></li>
</ul></div>
