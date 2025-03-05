---
title: "Reclaim Your Keyboard: Resolve Windows Snipping Command Issue"
date: 2025-02-25T16:09:07.629Z
updated: 2025-03-05T04:54:55.115Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reclaim Your Keyboard: Resolve Windows Snipping Command Issue"
excerpt: "This Article Describes Reclaim Your Keyboard: Resolve Windows Snipping Command Issue"
keywords: Fix Windows Sniping Error,Solve Keyboard Trigger,End Screen Cut Glitch,Windows Snipping Fix,Stop Snip Command Fail,Resolve Snipping Issue,Rectify Window Clip Mistake
thumbnail: https://thmb.techidaily.com/c45afa71b37443a1f59fe90234d68b3b0e50e4c51b39e47e7a2ccf645d397043.PNG
---

## Reclaim Your Keyboard: Resolve Windows Snipping Command Issue

 Whether you need to capture an error message or share something specific with someone, screenshots can be a lifesaver. The Win + Shift + S shortcut makes it easy to take screenshots with the Snipping Tool, but what if that shortcut stops responding?

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Computer

 It might sound simple, but restarting your computer often solves minor problems. This can help clear out any glitches that may prevent the shortcut from working correctly.

 To restart your computer, close any running programs. Now, open the Start menu and choose **Restart** in the list of options.

## 2\. Check Your Keyboard

 Check the keyboard for any dirt or debris that may obstruct the keys. Clean off dust, crumbs, and other particles with compressed air. Ensure that all the keys are working correctly and that none are stuck or pressed down. If the keys have been damaged or worn down, consider replacing your keyboard.

## 3\. Enable the Clipboard History

 If keyboard dirt and debris are not the issues, you may need to enable the clipboard history feature. This will help you restore any screenshots taken with Win + Shift + S that have been lost.

![Enable the Clipboard History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-the-clipboard-history.jpg)

 To enable it, open Settings and navigate to **System** \> **Clipboard**. There, you'll find the toggle for **Clipboard history** – turn it on.

 You can also use the Windows search bar to type in **Clipboard settings** and open it directly. If you prefer shortcuts, hit **Win + R** or type **ms-settings:clipboard** into Run.

## 4\. Turn on Snipping Tool Notification Toggle

 When you press Win + Shift + S on your keyboard, a notification should appear in the bottom-right corner of the screen. This notification toggle helps you quickly access screenshots taken with the shortcut.

 If you don't see a notification, that means the toggle is off, and you may need to enable it manually. Here's how to do it:

1. Right-click on Start and select **Settings**.
2. In the Settings window, navigate to **System** \> **Notifications**.
3. Under **Notifications from apps and other senders**, scroll down to the bottom and turn on the Snipping Tool notification toggle.  
![Turn on Snipping Tool Notification Toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-snipping-tool-notification-toggle.jpg)

 Once you have enabled this option, press **Win + Shift + S** to take a screenshot. If the shortcut works, you will see a notification that the screenshot is saved to the clipboard.

## 5\. Reset the Snipping Tool

 Another solution is to reset the Snipping Tool. It restores the default settings and can help if something goes wrong.

 To reset it, right-click on the **Start** menu and select **Installed apps**. Find **Snipping Tool** in the list, click three dots, and select **Advanced options**.

 You can also use **Win + R** or type **ms-settings:appsfeatures** in the Run dialog box to open Installed apps. From there, you can find the Advanced options for the Snipping Tool.

![Reset Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-snipping-tool.jpg)

 On the next page, scroll down to the **Reset** section. Select **Reset** and then click on **Reset** again in the confirmation popup. After resetting the Snipping Tool, check if the Win + Shift + S shortcut works.

## 6\. Reinstall the Snipping Tool

 If resetting doesn't solve the problem, try reinstalling the Snipping Tool. It will resolve any issues you may have with your current installation.

 To reinstall the Snipping Tool, open the System Settings. Select **Apps** \> **Installed apps**, then find and select **Snipping Tool** from the list of installed programs.

![Reset the Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-snipping-tool.jpg)

 Click the three dots and select **Uninstall**. Now follow the on-screen instructions to complete the process. Once done, download and install a new version of the Snipping Tool from the Microsoft Store app.

## 7\. Turn on Windows Hotkeys

 If your Windows hotkeys are disabled for some reason, the shortcut keys will not work. In such cases, you will need to enable the Windows hotkeys through the group policy editor. Here's how to do it:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **gpedit.msc** in the dialog box and hit Enter. This will open the Group Policy Editor window.  
![Turn on Windows Hotkeys Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-group-policy.jpg)
3. Navigate to the path:  

`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, double-click on the **Turn off Windows Key hotkeys** option.
5. Select Enabled in the settings window and click **Apply** \> **OK**.

 After making these changes, try taking a screenshot with Win + Shift + S shortcut. It should work now.

 One thing to remember is that this method will only work with Windows Pro and Enterprise editions. If you have the Home edition, you can't access the Group Policy Editor. In such a case, you'll need to [enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated, skip this method and use the Registry Editor instead.

 To enable Windows Hotkeys through the Registry Editor, follow these steps:

* Click on Start, type **regedit**, and hit **Enter**.
* If the UAC window pops up, click Yes to open the registry editor.  
`Navigate to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer`
* If you don't see the Explorer folder, right-click on **Policies** and select **New > Key**. Name the newly created key **Explorer**.
* Now right-click on **Explorer** and select **New** \> **DWORD 32-bit**.
* Name the DWORD **NoWinKeys**.
* Double-click on **NoWinKeys** and set the value data to **0**.  
![Turn on Windows Hotkeys Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-registry.jpg)
* Select Base as **Hexadecimal** and click **OK** to save the changes.

 After that, exit the registry editor and restart your computer. Once the system reboots, check if the issue has been resolved.

## 8\. Perform Some Generic Fixes

 There are a few general fixes that might help you get the Win + Shift + S keyboard shortcut working. Here's what you need to do:

1. Check the keyboard driver status and update it if needed.
2. Try [running the SFC utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to fix corrupted system files.
3. Make sure you are [running the latest version of Windows](https://www.makeuseof.com/update-windows-manually/).
4. [Run a full scan with your antivirus program](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and see if it solves the issue.
5. If the issue still persists, there's a chance that third-party applications are interfering with the Snipping Tool shortcut. In such a case, [try performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This will temporarily disable all the third-party applications and allow you to check if they were causing the issue.

## Taking Screenshots Is Easy With Shortcut Keys

 Keyboard shortcuts provide quick and easy access to different functions on your PC. It allows you to easily switch between applications and perform tasks. There are times, though, when the Win + Shift + S hotkey does not work properly. Hopefully, one of the above methods fixed this issue for you.

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-from-dull-to-dynamic-a-guide-to-chromatic-finesse/"><u>[New] 2024 Approved From Dull to Dynamic A Guide to Chromatic Finesse</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-in-depth-analysis-the-powerhouse-in-your-pocket-lightroom/"><u>[New] 2024 Approved In-Depth Analysis The Powerhouse in Your Pocket - Lightroom</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-capturing-life-in-motion-top-9-smartphone-props-for-dynamic-cinematography-for-2024/"><u>[New] Capturing Life in Motion Top 9 Smartphone Props for Dynamic Cinematography for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-unveiling-your-digital-world-how-to-establish-a-youtube-channel/"><u>[New] In 2024, Unveiling Your Digital World How to Establish a YouTube Channel</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-streamlined-recording-the-very-best-fullscreen-software/"><u>[Updated] In 2024, Streamlined Recording The Very Best Fullscreen Software</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-complete-directors-guide-to-powerdirector-24-software/"><u>2024 Approved Complete Director's Guide to PowerDirector '24 Software</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-page-not-found-mistakes-in-microsoft-store/"><u>Correcting 'Page Not Found' Mistakes in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-strategies-maximizing-wsl-android-resources/"><u>Cutting-Edge Strategies: Maximizing WSL Android Resources</u></a></li>
<li><a href="https://win11.techidaily.com/ease-of-virtualbox-installation-hinges-on-prerequisites/"><u>Ease of VirtualBox Installation Hinges on Prerequisites</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-setup-disabling-built-in-gpu-on-windows/"><u>Optimal Setup: Disabling Built-In GPU on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-operational-windows-alt-codes-47-characters/"><u>Repairing Non-Operational Windows Alt Codes (47 Characters)</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlocking-the-secrets-of-your-pcs-print-job-records-a-comprehensive-walkthrough-for-windows-10-users/"><u>Unlocking the Secrets of Your PC's Print Job Records - A Comprehensive Walkthrough for Windows 10 Users</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-features-of-the-truecaller-application-a-critical-analysis/"><u>Unveiling the Features of the Truecaller Application - A Critical Analysis</u></a></li>
<li><a href="https://win-hacks.techidaily.com/updating-your-sound-card-drivers-made-easy-a-step-by-step-guide-by-yl-computing/"><u>Updating Your Sound Card Drivers Made Easy: A Step-by-Step Guide by YL Computing</u></a></li>
<li><a href="https://win11.techidaily.com/win11-clearview-resolving-fuzzy-displays/"><u>Win11 ClearView: Resolving Fuzzy Displays</u></a></li>
</ul></div>

