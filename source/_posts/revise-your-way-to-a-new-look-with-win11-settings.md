---
title: Revise Your Way to a New Look with Win11 Settings
date: 2024-10-31T19:35:58.155Z
updated: 2024-11-01T22:07:07.346Z
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
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're a PowerShell enthusiast, why not take the time to learn these[useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-8-smooth-capture-tools-reviewed-for-2024/"><u>[Updated] Top 8 Smooth Capture Tools Reviewed for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-leading-nintendo-switch-combat-arcade-games-max-156/"><u>2024 Approved Leading Nintendo Switch Combat Arcade Games (Max 156)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-shrouded-screen-images-techniques-for-redacting-info/"><u>2024 Approved Shrouded Screen Images Techniques for Redacting Info</u></a></li>
<li><a href="https://tech-revival.techidaily.com/7-innovative-approaches-to-refine-gpt-interaction-quality/"><u>7 Innovative Approaches to Refine GPT Interaction Quality</u></a></li>
<li><a href="https://solve-latest.techidaily.com/customized-user-experience-enabled-by-cookiebot-technology/"><u>Customized User Experience Enabled by Cookiebot Technology</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-system-accessibility-with-elevated-privileges/"><u>Enhancing System Accessibility with Elevated Privileges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-audio-quality-on-a-damaged-logitech-g930-microphone-cut-out/"><u>How to Restore Audio Quality on a Damaged Logitech G930 Microphone Cut Out</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-8-screen-lock-without-password-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock iPhone 8 screen lock without password?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-science-and-magic-behind-full-circle-films/"><u>In 2024, The Science and Magic Behind Full Circle Films</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directory-management-windows-11-techniques/"><u>Mastering Directory Management: Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/merge-gmail-with-outlook-on-windows-a-detailed-guide/"><u>Merge Gmail with Outlook on Windows: A Detailed Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-top-6-to-do-apps-for-windows/"><u>Navigating the Top 6 To-Do Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-keyboard-mastery-typingaids-way/"><u>Quick Keyboard Mastery - TypingAid's Way</u></a></li>
<li><a href="https://win11.techidaily.com/regular-update-reactivating-microsoft-store-on-windows-pcs/"><u>Regular Update: Reactivating Microsoft Store on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unidentified-fingerprint-scanner-errors-in-windows/"><u>Solving Unidentified Fingerprint Scanner Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-restoring-the-functionality-of-windows-defenders-threat-barrier/"><u>Swift Remedies: Restoring the Functionality of Windows Defender's Threat Barrier</u></a></li>
</ul></div>

