---
title: "Simplify Your PC: Disable/Remove MS Edge W11"
date: 2024-09-11T09:37:27.664Z
updated: 2024-09-12T09:37:27.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplify Your PC: Disable/Remove MS Edge W11"
excerpt: "This Article Describes Simplify Your PC: Disable/Remove MS Edge W11"
keywords: Disable Microsoft Edge,Remove W11 Edge,Simplify Windows Experience,Stop Edge Usage,Optimize PC Performance,Eliminate Edge Bloatware,Streamline System Stability
thumbnail: https://thmb.techidaily.com/b0ea6d61080761dc873cfd8c694bea1246e45e087ea28aa28a47640ed6e89f83.jpg
---

## Simplify Your PC: Disable/Remove MS Edge W11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://discord-videos.techidaily.com/new-unraveling-the-creators-who-elevate-digital-expressions-for-2024/"><u>[New] Unraveling the Creators Who Elevate Digital Expressions for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-expert-strategies-for-configuring-and-assessing-fbs-instream-ads/"><u>[Updated] Expert Strategies for Configuring and Assessing FB's Instream Ads</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-gaming-gains-total-earnings-for-pewdiepie/"><u>[Updated] Gaming Gains Total Earnings for PewDiePie</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-go-global-with-music-transform-your-spotify-lists-into-youtube-videos/"><u>[Updated] In 2024, Go Global with Music Transform Your Spotify Lists Into YouTube Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-mastering-vrecorder-download-install/"><u>[Updated] In 2024, Mastering VRecorder Download, Install</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-instagram-video-edge-planning-for-maximum-marketing-success/"><u>2024 Approved The Instagram Video Edge Planning for Maximum Marketing Success</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-and-efficient-topmate-c302-companion-a-comprehensive-laptop-cooler-guide/"><u>Affordable & Efficient TopMate C302 Companion - A Comprehensive Laptop Cooler Guide</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-tecno-camon-20-premier-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Tecno Camon 20 Premier 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-mouseclicklock-usage-on-windows-pcs/"><u>Demystifying MouseClickLock Usage on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-132-wow-troubleshooting-guide/"><u>Eradicating Error #132: WoW Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-avoiding-file-explorer-oversights-in-windows-11/"><u>Expert Advice on Avoiding File Explorer Oversights in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-usb-availability-problem/"><u>Fixing Insufficient USB Availability Problem</u></a></li>
<li><a href="https://win11.techidaily.com/harness-free-note-tools-on-windows-11/"><u>Harness Free Note Tools on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-70-lite-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Honor 70 Lite 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-epic-escapades-in-playtime-paradise/"><u>In 2024, Epic Escapades in Playtime Paradise</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-security-using-powertoys-lockmaster/"><u>Mastering File Security: Using PowerToys' Lockmaster</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-system-restore-on-windows-11-quick-access-methods/"><u>Mastering System Restore on Windows 11: Quick Access Methods</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-top-rated-stop-motion-software-for-windows-and-macos-for-2024/"><u>New Top-Rated Stop Motion Software for Windows and macOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-hurdles-to-use-windows-with-steam-link/"><u>Overcoming Hurdles to Use Windows with Steam Link</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pc-predicament-simple-solutions-to-desktop-troubles/"><u>Purple PC Predicament: Simple Solutions to Desktop Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/refresh-your-screen-writers-with-a-trio-of-tricks/"><u>Refresh Your Screen' Writers with a Trio of Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-update-issues-with-error-code-0x30017-in-windows/"><u>Remedying Update Issues with Error Code 0X30017 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/smoothening-windows-steam-audio-performance/"><u>Smoothening Windows Steam Audio Performance</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-re-register-bluetooth-in-pcs-device-manager/"><u>Steps to Re-Register Bluetooth in PC's Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-content-transfer-within-windows-11s-shielded-mode-microsoft-edge-app-guard/"><u>Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamline-pcs-with-chatgpt-application/"><u>Streamline PCs with ChatGPT Application</u></a></li>
<li><a href="https://win11.techidaily.com/taming-windows-endless-file-explorer-opens/"><u>Taming Windows' Endless File Explorer Opens</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-free-media-players-for-windows/"><u>The 7 Best Free Media Players for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-roadmap-for-utilizing-the-calculator-in-windows-11/"><u>The Roadmap for Utilizing the Calculator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-potential-essential-tips-for-winning-with-wsl-2/"><u>Unlock Your Potential: Essential Tips for Winning with WSL 2</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-new-era-of-widget-selection-with-win11/"><u>Unveiling The New Era of Widget Selection with Win11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-login-strategy-move-from-a-pin-to-a-password-sign-in/"><u>Upgrading Your Login Strategy: Move From a PIN to a Password Sign-In</u></a></li>
</ul></div>

