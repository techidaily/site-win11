---
title: Bypassing Admins Rights Issue in Win OS
date: 2024-08-15T23:44:31.018Z
updated: 2024-08-16T23:44:31.018Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Admins Rights Issue in Win OS
excerpt: This Article Describes Bypassing Admins Rights Issue in Win OS
keywords: Admin Rights Bypass Windows,WinOS Security Breach,User Privilege Escalation,Unauthorized Access in WinOS,Gaining Admin Control (Win),OS Vulnerability Exploit,Elevated Permission Risks Win
thumbnail: https://thmb.techidaily.com/db2dfa016aad5526d4e3599a68e42c8f3cfa167590fe6f17711d0d491d279f0c.jpg
---

## Bypassing Admins Rights Issue in Win OS

 Administrator accounts offer extensive control over the system, granting the ability to manage settings, install software, and access critical system files. However, occasionally, users may encounter issues when attempting to switch from their standard user account to an admin account.

 Below, we explore various effective fixes to resolve this problem permanently.

## 1\. Modify the User Account Control (UAC) Settings

 User Account Control (UAC) is a security feature that prevents users from making unauthorized changes to the computer. It typically appears as a dialog box, prompting you to confirm the action by clicking the "Yes" or "No" option.

 In the case of this specific error, you might be facing the issue because of misconfigured or incorrect UAC settings. Here is how you can ensure UAC is enabled and set to a suitable level:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "control" in the text field and click **Enter**.
3. In the following window, navigate to **System and Security** \> **Security and Maintenance**.
4. Choose **Change User Account Control settings**.
5. In the dialog that appears, move the slider to the desired level (recommended: notify only when apps try to make changes to your computer) and click **OK** to save the changes.  
![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

 Once done, close the Command Prompt and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Activate the Built-In Administrator Account

![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-built-in-admin-account.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows comes with a hidden administrator account that can allow you to have full control over the system. This account is typically disabled by default for security reasons but if you are having trouble switching to an administrator account, enabling the built-in Administrator account can be beneficial.

 Here's how to activate the built-in Administrator account:

1. Press the **Win** \+ **R** keys to open Run.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the following dialog.
4. Once you are in the Command Prompt, type the command below and hit **Enter** to execute it:  
net user administrator /active:yes
5. After the command executes successfully, you should see a message in Command Prompt confirming it. If you want to set a password for this administrator account, execute the following command:  
​​​​​​​net user administrator *
6. Follow the prompts to set a new password.

 Alternatively, you can also use the Local Users and Groups management console to make these changes. Here is how you can do that:

1. Open Run by pressing **Win** \+ **R** keys together.
2. Type "lusrmgr.msc" in Run and click **Enter**.
3. In the left pane, expand **Users** and right-click on **Administrator**.
4. Choose **Properties** from the context menu.
5. Uncheck the **Account is disabled** option and click **OK**.  
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-admin-account.jpg)

 This should successfully activate the built-in administrator account. You can now access the Settings app again and check if you can switch the account type easily now.

## 3\. Make the Changes in Safe Mode

 It's possible that a background process or application is causing interference with system processes, which could be preventing you from switching to an administrator account.

 To determine if this is the cause of the issue, you can [boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). Safe Mode launches the system with minimal drivers and programs, disabling any background processes that may be contributing to the problem. In this diagnostic state, you should be able to switch to the administrator account if such processes were previously causing the obstruction.

 Once you have booted into Safe Mode, try performing the action that was initially causing the problem. If it does not occur in Safe Mode, you can try eliminating the culprit by either uninstalling it manually or [using the System Restore utility](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) to revert to a stable, error-free state.

## 4\. Disable Your Antivirus Program

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If you are using a third-party security program on your computer, it might be preventing you from switching to an admin account because of security reasons.

 In this case, you can try to temporarily disable your security program and see if that helps you switch to an administrator account. You can do this by right-clicking on your antivirus icon in the taskbar and choosing the **Shields Control** \> **Disable until the computer is restarted** option.

 If this works, you can consider [switching to a better security program for your Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to prevent issues like this from occurring in the future.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Create a New Administrator Account

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Finally, if none of the methods above have helped you, you can try creating a new administrator account in Windows

 This will help with any corruption issues in the current account, as well as help you determine if the permission-related problems were user-specific. It is, however, important to note that you will require admin access to the system to proceed with the steps in this method, so you must enable the built-in administrator account beforehand.

 Once that is done, here is how you can proceed:

1. Open the Settings app by pressing the **Win** \+ **I** keys together.
2. Choose **Accounts** from the left pane and click on **Other users**.
3. Hit the **Add account** button for **Add other users** in the following window.  
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select **I don’t have this person’s sign-in information** \> **Add a user without a Microsoft account**.
5. In the next dialog, enter details like the username and password for the new account.
6. Click **Next**.
7. Once the account is created, click on the **Change account type** button associated with the newly created account.  
![The Change account type button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-change-account-type-option.jpg)
8. Expand the Account type dropdown and choose **Administrator** from the menu.
9. Click **OK** to save the changes.

 You can now log into the new administrator account and begin using it.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy Administrative Access to Your Windows System

 The inability to change an account type to Administrator in Windows can be caused by a number of reasons, such as misconfigured User Account Control (UAC) settings or underlying system issues. However, with the right troubleshooting methods, you can overcome the account type change challenge and enjoy administrative access to the system.

 Below, we explore various effective fixes to resolve this problem permanently.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/updated-conquer-common-issues-essential-windows-10-fixes/"><u>[Updated] Conquer Common Issues  Essential Windows 10 Fixes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-skyward-voyage-of-gopro-karma-analysis/"><u>2024 Approved  The Skyward Voyage of GoPro Karma Analysis</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/captivating-content-with-a-click-phones-and-youtube/"><u>Captivating Content with a Click  Phones & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-defective-battery-meter-on-windows-11-devices/"><u>Correcting Defective Battery Meter on Windows 11 Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-mp4-play-on-samsung-galaxy-a15-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Does MP4 play on Samsung Galaxy A15 5G?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/earning-a-living-with-social-media-snaps/"><u>Earning a Living with Social Media Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-accelerated-inputs-for-a-smooth-click-journey/"><u>Eliminating Accelerated Inputs for a Smooth Click Journey</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-of-windows-glass-hangout-guide/"><u>Essentials of Windows Glass Hangout Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-methods-to-insert-coding-examples-directly-into-word-sheets/"><u>Expert Methods to Insert Coding Examples Directly Into Word Sheets</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-severe-discord-js-error-on-pc-windows-10-and-11-guide/"><u>Fixing Severe Discord JS Error on PC: Windows 10 & 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-microsoft-edge-in-w11-os/"><u>How to Delete Microsoft Edge in W11 OS</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-iphone-15-pro-max-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your iPhone 15 Pro Max?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-windows-media-player-in-windows/"><u>How to Start Windows Media Player in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-infinix-note-30i-easily-by-drfone-android/"><u>In 2024, How To Unlock a Infinix Note 30i Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/installation-woes-microsoft-pc-manager-on-windows-xp/"><u>Installation Woes: Microsoft PC Manager on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/method-reinstate-windows-base-power-plan/"><u>Method: Reinstate Windows Base Power Plan</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/mod-video-editor-showdown-the-best-free-options/"><u>MOD Video Editor Showdown The Best Free Options</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-display-hiccup-error-code-x0001-geforce/"><u>Overcoming Display Hiccup: Error Code X0001, GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-disconnect-restarting-your-hotspot-in-windows-11/"><u>Overcoming the Disconnect: Restarting Your Hotspot in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premium-web-choices-for-shiny-3d-type-designs-for-2024/"><u>Premium Web Choices for Shiny, 3D Type Designs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-cannot-create-errors-for-files-in-windows/"><u>Remedying 'Cannot Create' Errors for Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cloud-sync-failures-windows-10-and-11/"><u>Resolving Cloud Sync Failures: Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-connection-problems/"><u>Resolving Steam Cloud Connection Problems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gameplay-mastery-fixing-frames-drops-in-valorant/"><u>Seamless Gameplay Mastery: Fixing Frames Drops in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/skip-the-haste-disabling-early-edge-tab-activation-in-win11/"><u>Skip the Haste: Disabling Early Edge Tab Activation in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-resurrect-winget-in-windows-os/"><u>Solutions to Resurrect Winget in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-method-to-create-an-automatic-text-transcription-program/"><u>Step-by-Step Method to Create an Automatic Text Transcription Program</u></a></li>
<li><a href="https://win11.techidaily.com/stop-zooming-start-scrolling-essential-mouse-repairs/"><u>Stop Zooming, Start Scrolling: Essential Mouse Repairs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-first-browser-view-in-windows-11/"><u>Tailoring Your First Browser View in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-11-themes-missed-by-many/"><u>Top Windows 11 Themes Missed by Many</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-computer-embracing-the-power-of-16gb/"><u>Upgrading Your Computer: Embracing the Power of 16GB</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-might-prefer-windows-11-to-apples-macos/"><u>Why You Might Prefer Windows 11 to Apple's macOS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-on-pause-four-simple-steps/"><u>Windows Update on Pause: Four Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/winx-backdrop-blues-solutions-for-a-colorful-ui/"><u>WinX Backdrop Blues: Solutions for a Colorful UI</u></a></li>
</ul></div>
