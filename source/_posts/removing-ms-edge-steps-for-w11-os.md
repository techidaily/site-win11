---
title: "Removing MS Edge: Steps for W11 OS"
date: 2024-12-15T17:28:05.795Z
updated: 2024-12-22T17:31:49.653Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Removing MS Edge: Steps for W11 OS"
excerpt: "This Article Describes Removing MS Edge: Steps for W11 OS"
keywords: W11 MS Edge Removal,Remove MS Edge Windows,Edge Switching W11,Disable Edge Browser,Uninstall Microsoft Edge,Clear MS Edge Cache,Switch Browsers W11
thumbnail: https://thmb.techidaily.com/d62120d0f92dda8643d1fb18ba050a4238aed422d93382b937c3fa171ed251d1.jpg
---

## Removing MS Edge: Steps for W11 OS

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-compress-to-caption-zip-to-srt-for-video-editors/"><u>[New] 2024 Approved Compress to Caption ZIP-to-SRT for Video Editors</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-unveiling-success-the-best-tools-for-youtube-seo-and-keyword-research/"><u>[New] 2024 Approved Unveiling Success The Best Tools for YouTube SEO and Keyword Research</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-utilizing-zoom-services-directly-from-your-inbox-gmail-edition/"><u>[Updated] 2024 Approved Utilizing Zoom Services Directly From Your Inbox - Gmail Edition</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-leading-6-task-assistants-that-work-with-windows-11/"><u>Discover the Leading 6 Task Assistants That Work with Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flip-page-film-narrative-guide-for-2024/"><u>Flip Page Film Narrative Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unfreeze-steam-game-server-status-in-windows-environments/"><u>How to Unfreeze Steam Game Server Status in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/hyper-v-layers-virtualizing-linux-within-windows/"><u>Hyper-V Layers: Virtualizing Linux Within Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-achieving-clear-sound-mixes-with-audio-ducking-techniques-in-adobe-premiere-pro-for-windows-users/"><u>In 2024, Achieving Clear Sound Mixes with Audio Ducking Techniques in Adobe Premiere Pro for Windows Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-k11x-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Oppo K11x</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/integrating-ai-in-your-android-with-chatgpt-widget/"><u>Integrating AI in Your Android with ChatGPT Widget</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-to-extract-device-info/"><u>Navigating Through Windows to Extract Device Info</u></a></li>
<li><a href="https://win-cheats.techidaily.com/recognizing-signs-of-a-dying-hard-drive-a-guide-by-yl-computing/"><u>Recognizing Signs of a Dying Hard Drive: A Guide by YL Computing</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintet-of-top-tier-write-enhancers-windows-edition/"><u>The Quintet of Top-Tier Write Enhancers (Windows Edition)</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-selecthighlight-functionality-window-edition/"><u>Unblock Select/Highlight Functionality, Window Edition</u></a></li>
</ul></div>

