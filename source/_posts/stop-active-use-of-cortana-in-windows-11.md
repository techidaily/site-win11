---
title: Stop Active Use of Cortana in Windows 11
date: 2024-08-16T00:49:51.764Z
updated: 2024-08-17T00:49:51.764Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Active Use of Cortana in Windows 11
excerpt: This Article Describes Stop Active Use of Cortana in Windows 11
keywords: Cortana Disabling Guide,Windows 11 Cortana Off Switch,Stop Cortana Activation Windows 11,Turn Off Cortana Windows 11,Disable Cortana in Windows 11,End Cortana Use in Windows 11,Windows 11 Cortana Shutdown Methods
thumbnail: https://thmb.techidaily.com/46162ff1d50cb6f1b35f044048a0b2464ebecd738e59505ca40bf7c4a2c48673.png
---

## Stop Active Use of Cortana in Windows 11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-find-zen-with-these-10-game-choices-for-2024/"><u>[New] Find Zen with These 10 Game Choices for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-infinite-possibilities-with-ai-generating-viral-video-titles/"><u>[New] Infinite Possibilities with AI  Generating Viral Video Titles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-seamless-integration-from-gopro-to-popular-social-media-platforms-for-2024/"><u>[New] Seamless Integration  From Gopro to Popular Social Media Platforms for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-inspirational-insta-captions-to-elevate-your-social-presence/"><u>[Updated] Inspirational Insta Captions to Elevate Your Social Presence</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-ultimate-guide-to-utilizing-instagrams-inquiry-icon-for-2024/"><u>[Updated] The Ultimate Guide to Utilizing Instagram's Inquiry Icon for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-2023-roundup-premier-professionals-360-cameras/"><u>2024 Approved  2023 Roundup  Premier Professionals’ 360 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-make-windows-11-start-up-faster/"><u>3 Ways to Make Windows 11 Start Up Faster</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/5-immediate-actions-reviving-disabled-windows-defender-protection/"><u>5 Immediate Actions: Reviving Disabled Windows Defender Protection</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-driver-verifier-manager-w11-edition/"><u>Accessing Driver Verifier Manager W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-errors-when-transferring-images-from-iphone-to-pc/"><u>Addressing Errors When Transferring Images From iPhone to PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-cannot-locate-gpeditmsc-error-in-windows/"><u>Addressing the Cannot Locate Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-onedrives-incorrect-tag-issue/"><u>Addressing Windows Error: OneDrive’s Incorrect Tag Issue</u></a></li>
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-save-location-blunders-on-windows-devices/"><u>Avoiding Save Location Blunders on Windows Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/best-free-video-calls-featuring-screen-sharing-roundup/"><u>Best Free Video Calls Featuring Screen Sharing Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-widget-integration-in-windows-11/"><u>Boosting Productivity with Widget Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breached-bytebandit-ponder-the-path-for-a-possible-pivot/"><u>Breached ByteBandit: Ponder the Path for a Possible Pivot</u></a></li>
<li><a href="https://win11.techidaily.com/1719285734353-breathe-life-back-into-your-computers-print-command-wwinplusp/"><u>Breathe Life Back Into Your Computer's Print Command (WWin+P)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-youtube-playback-speed-delays-in-chrome/"><u>Fixing YouTube Playback Speed Delays in Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-make-the-most-of-your-iphone-12-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>How to Make the Most of Your iPhone 12 Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account From Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-plus-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 8 Plus 3 Ways To Unlock</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-multitasking-using-obs-studio-for-dynamic-streaming/"><u>In 2024, Mastering Multitasking  Using OBS Studio for Dynamic Streaming</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-speedy-integration-of-voice-input-feature-in-your-powerpoint-shows/"><u>In 2024, Speedy Integration of Voice Input Feature in Your PowerPoint Shows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-strategies-for-effective-b-roll-application/"><u>In 2024, Strategies for Effective B-Roll Application</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://ai-video.techidaily.com/reinstate-lost-files-via-winrecovery-center/"><u>Reinstate Lost Files via WinRecovery Center</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-artists-chromatic-companion/"><u>The Artist's Chromatic Companion</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-for-2024/"><u>Updated for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>