---
title: Step-by-Step Guide for Deleting MS Edge Win11
date: 2024-07-13T10:37:44.058Z
updated: 2024-07-14T10:37:44.058Z
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
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-oneplus-11-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass OnePlus 11 5G FRP</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-say-goodbye-to-shaky-footage-adobe-premiere-pro-stabilization-tips-and-tricks/"><u>Updated In 2024, Say Goodbye to Shaky Footage Adobe Premiere Pro Stabilization Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/dual-screen-delight-personalized-pixels-per-monitor-of-windows-1011/"><u>Dual Screen Delight: Personalized Pixels per Monitor of Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-what-lies-beneath-instagram-story-perceptions/"><u>[Updated] In 2024, What Lies Beneath  Instagram Story Perceptions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-starting-off-with-zoom-meetings-your-first-steps-guide/"><u>2024 Approved  Starting Off with Zoom Meetings  Your First Steps Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-14-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, iPhone 14 Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unleash-creativity-with-these-14-exceptional-text-animations/"><u>Unleash Creativity with These 14 Exceptional Text Animations</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-instantaneous-voice-eradication-technique-using-audacity/"><u>2024 Approved Instantaneous Voice Eradication Technique Using Audacity</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-skip-the-struggle-tips-on-avoiding-online-edgenuity-lessons/"><u>In 2024, Skip the Struggle  Tips on Avoiding Online Edgenuity Lessons</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-high-quality-sound-adjustment-apps-for-content-casters/"><u>[New] 2024 Approved  High-Quality Sound Adjustment Apps for Content Casters</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-10-great-moving-animation-powerpoint-techniques/"><u>Updated 2024 Approved 10 Great Moving Animation PowerPoint Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-reading-qr-codes-on-windows-devices/"><u>Essential Tips for Reading QR Codes on Windows Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-digital-fortune-makers-top-earning-youtubers/"><u>2024 Approved  Digital Fortune Makers  Top Earning YouTubers</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-elite-sound-mixers-for-superior-stream-quality-for-2024/"><u>Updated Elite Sound Mixers for Superior Stream Quality for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-superior-fb-video-tools-save-as-top-quality-mp4s/"><u>[New] In 2024, Superior FB Video Tools – Save as Top Quality MP4s</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gear-warriors-test-who-wins-gopro-hero5-black-vs-virb-ultra/"><u>2024 Approved  Gear Warriors Test  Who Wins? GoPro Hero5 Black Vs. VIRB Ultra</u></a></li>
<li><a href="https://extra-resources.techidaily.com/battle-royale-concrete-fists-vs-digital-screens/"><u>Battle Royale  Concrete Fists vs Digital Screens</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-launch-windows-11-access-control-panel/"><u>Locate and Launch Windows 11 Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-quick-recording-keyboard-shortcut-tips-for-win-11/"><u>Mastering the Art of Quick Recording: Keyboard Shortcut Tips for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-add-text-in-after-effects/"><u>Updated 2024 Approved How To Add Text In After Effects</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/driving-engagement-for-social-media-stardom-for-2024/"><u>Driving Engagement for Social Media Stardom for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-experience-in-roblox-addressing-account-restrictions/"><u>Fixing Blocked Experience in Roblox: Addressing Account Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942661716-new-10-matching-color-combination-that-works-together/"><u>New 10 Matching Color Combination That Works Together</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-installation-of-arm-based-windows-11-from-iso/"><u>Mastering the Installation of ARM-Based Windows 11 From ISO</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/go-pure-with-linux-avoid-wsl/"><u>Go Pure with Linux - Avoid WSL</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-and-optimizing-windows-11-service-usage-wisely/"><u>Prioritizing and Optimizing Windows 11 Service Usage Wisely</u></a></li>
</ul></div>
