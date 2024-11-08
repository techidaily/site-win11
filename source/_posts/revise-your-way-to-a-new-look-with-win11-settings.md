---
title: Revise Your Way to a New Look with Win11 Settings
date: 2024-11-04T16:59:09.027Z
updated: 2024-11-07T16:33:03.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revise Your Way to a New Look with Win11 Settings
excerpt: This Article Describes Revise Your Way to a New Look with Win11 Settings
keywords: Windows Revamping Guide,Win11 Aesthetic Tweaks,New Appearance Win11,Personalize Win11,Win11 Style Adjustments,Update Windows Look,Customize Win11 UI
thumbnail: https://thmb.techidaily.com/2eefe00fc71984145735604d7f6409f58eabe8499747b0b476c4253bd9b978c9.jpg
---

## Revise Your Way to a New Look with Win11 Settings

 The Settings app in Windows 11 makes it simple for you to manage various settings and preferences on your computer. Whether you want to customize your computer's theme, manage network connections or check for system updates, the Windows Settings app is a central location for all your computer management needs.

 If the Windows 11 Settings app stops working, or if you want to restore it to its default settings, you can always reset it. You can reset the Windows Settings app using the search menu, Command Prompt or PowerShell. Let's go over all three methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Reset the Windows 11 Settings App Using the Search Menu

 The quickest way to reset the Windows 11 Settings app is through the search menu. So, let's start with that.

To reset the Windows 11 Settings app with the search menu:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to access the search menu.
2. Type**Settings** in the search box.
3. Select the**App settings** option from the right pane.
4. Scroll down to the Reset section and click the**Reset** button.
5. Select**Reset** again to confirm.  
![Reset Settings App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-in-windows-11.jpg)

 After completing the above steps, you can use one of the[many ways to access the Windows Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and configure it again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Reset the Windows 11 Settings App via PowerShell

 If you prefer to interact with your computer through a command-line interface, you can also use PowerShell to reset the Windows Settings app. Don’t worry, the process isn’t as intimidating as it might sound.

 Use these steps to reset the Windows 11 Settings app using PowerShell.

1. Click the**search icon** on the taskbar to open the search menu.
2. Type**Windows PowerShell** in the search box.
3. Select**Run as administrator** from the right side.
4. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
5. In the console, type the following command and press**Enter** to reset the Settings app.  
`Get-AppxPackage *Windows.ImmersiveControlPanel* | Reset-AppxPackage`  
![Reset Settings App Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're a PowerShell enthusiast, why not take the time to learn these[useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Reset the Windows 11 Settings App Using Command Prompt

 Another way to reset the Windows 11 Settings app is via Command Prompt. Similar to the method above, resetting the Settings app using Command Prompt only requires you to run a single command.

 To reset the Windows 11 Settings app using Command Prompt, use these steps:

1. Press**Win + X** or right-click the**start icon** to open the Power User menu and select**Run** from the list.
2. Type**cmd** in the text box and then press**Ctrl + Shift + Enter** on your keyboard to[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#how-to-run-command-prompt-as-an-administrator-through-the-windows-search-tool) .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, paste the following command and hit**Enter** :  
`PowerShell -ExecutionPolicy Unrestricted -Command "& {$manifest = (Get-AppxPackage *immersivecontrolpanel*).InstallLocation + '\AppxManifest.xml' ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}"`

![Reset Settings App Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-command-prompt.jpg)

 Once you run the above command, Windows will reset the Settings app on your computer.

 Do you find Command Prompt to be too complicated or boring to use? Here are some of[the best Command Prompt alternatives for Windows](https://www.makeuseof.com/best-command-prompt-alternatives-for-windows/) worth trying.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Resetting the Windows 11 Settings App

 Regardless of the method you use, resetting Windows 11 Settings app shouldn’t take more than a couple of minutes of your time. After that, you can start configuring your computer settings from scratch.

 If, however, resetting the Settings app does not solve your problem, you can try creating a new user account. Alternatively, you can consider factory resetting your Windows 11 computer and starting over.

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
<li><a href="https://extra-information.techidaily.com/new-boosted-visuals-a-beginners-guide-to-gopro-video-editing/"><u>[New] Boosted Visuals A Beginner's Guide to GoPro Video Editing</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-bring-life-to-graphics-adobe-blur-masterclass/"><u>[Updated] Bring Life to Graphics Adobe Blur Masterclass</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-realme-11-pro-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Realme 11 Pro</u></a></li>
<li><a href="https://win-advanced.techidaily.com/get-microsoft-va-training-content-in-multiple-formats-mp4-wmv-avi-and-flv/"><u>Get Microsoft VA Training Content in Multiple Formats: MP4, WMV, AVI & FLV</u></a></li>
<li><a href="https://win11.techidaily.com/how-crucial-is-pagefilesys-and-its-deletion-dilemran/"><u>How Crucial Is Pagefile.sys and Its Deletion Dilemran</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-high-disk-usage-caused-by-microsoft-telemetry-on-windows-10-systems/"><u>How to Fix High Disk Usage Caused by Microsoft Telemetry on Windows 10 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/light-shadow-and-subtlety-in-film-coloring/"><u>Light, Shadow & Subtlety in Film Coloring</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-windows-mobility-center-with-a-click/"><u>Quiet Windows Mobility Center with a Click</u></a></li>
<li><a href="https://win11.techidaily.com/recover-lost-dxgidll-in-windows-11-heres-how/"><u>Recover Lost Dxgi.dll in Windows 11, Here's How</u></a></li>
<li><a href="https://discover-dash.techidaily.com/risolvi-i-tuoi-dubbi-sullia-tecnologica-di-winxvideo-con-le-domande-piu-frequenti-e-le-loro-soluzioni/"><u>Risolvi I Tuoi Dubbi Sull'IA Tecnologica Di WinXVideo Con Le Domande Più Frequenti E Le Loro Soluzioni</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-correcting-windows-error-code-19-issues/"><u>Step-by-Step Guide: Correcting Windows Error Code 19 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/synchronizing-your-android-with-windows-11-webstreaming/"><u>Synchronizing Your Android with Windows 11 Webstreaming</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Oppo Reno 9A | Dr.fone</u></a></li>
</ul></div>

