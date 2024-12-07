---
title: Removing Microsoft Edge From Windows 11 Home Edition
date: 2024-12-06T05:42:57.787Z
updated: 2024-12-07T03:51:18.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Microsoft Edge From Windows 11 Home Edition
excerpt: This Article Describes Removing Microsoft Edge From Windows 11 Home Edition
keywords: Remove Edge in Win11,Stop Edge on Windows 11,Disable Edge Browser,End Microsoft Edge,Banish Edge From Win11,Eliminate Edge Win11,Uninstall Edge Version
thumbnail: https://thmb.techidaily.com/f55b120c68d76e4449cb5609ead97bf0a2f306573825bcc3d502f312c1d75f0b.png
---

## Removing Microsoft Edge From Windows 11 Home Edition

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-boosting-user-interaction-mastering-hashtag-use-on-instagram/"><u>[New] Boosting User Interaction Mastering Hashtag Use on Instagram</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-lore-of-roguelites-amidst-classic-rpgs/"><u>[New] In 2024, The Lore of Roguelites Amidst Classic RPGs</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-direct-route-uploading-from-youtube-to-dailymotion/"><u>[Updated] In 2024, Direct Route Uploading From YouTube to Dailymotion</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-unboxing-the-market-strategic-essentials-for-2024/"><u>[Updated] Unboxing the Market Strategic Essentials for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bypass-spotifys-predicted-podcast-selections/"><u>Bypass Spotify's Predicted Podcast Selections</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/cinematiccapture-easy-screen-recorder-for-win11-pcs/"><u>CinematicCapture Easy Screen Recorder for Win11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-win11-launch-speed-with-these-simple-tweaks/"><u>Enhance Win11 Launch Speed with These Simple Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-hyber-v-with-win11-tools/"><u>How to Stop Hyber-V with Win11 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/nostalgic-keys-to-contemporary-computing-windows-7-and-11/"><u>Nostalgic Keys to Contemporary Computing: Windows 7 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-failure-x80246007-issue-solution/"><u>Overcoming Windows Update Failure: X80246007 Issue Solution</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-win10-bsod-troubleshooting/"><u>Quick-Fix Guide to Win10 BSOD Troubleshooting</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-guide-getting-your-airplay-back-in-action-after-malfunctions/"><u>Step-by-Step Guide: Getting Your AirPlay Back in Action After Malfunctions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/strategies-to-fix-an-expanded-pagefilesys-file-size-problem/"><u>Strategies to Fix an Expanded Pagefile.sys File Size Problem</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-tasks-experience-microsofts-ai-copilot-on-the-windows-11-taskbar/"><u>Streamline Your Tasks: Experience Microsoft's AI Copilot on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win-docs.techidaily.com/windows-server-upgrade-successfully-transitioning-from-2012-r2-to-2016-without-issues/"><u>Windows Server Upgrade: Successfully Transitioning From 2012 R2 to 2016 without Issues</u></a></li>
</ul></div>

