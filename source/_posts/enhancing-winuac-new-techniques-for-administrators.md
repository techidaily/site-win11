---
title: "Enhancing WinUAC: New Techniques for Administrators"
date: 2024-08-16T00:08:47.783Z
updated: 2024-08-17T00:08:47.783Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing WinUAC: New Techniques for Administrators"
excerpt: "This Article Describes Enhancing WinUAC: New Techniques for Administrators"
keywords: Admin Enhancement Tools,WinUAC Upgrades Secure,User Administration Advance,UAC Improvement Methods,Windows Security Update,Elevate Admin Controls,Strengthen UAC Management
thumbnail: https://thmb.techidaily.com/84120ce1dd040ef96ca974489513e09e6fd38ddc4b035ddddd4021d7d15c6c74.jpg
---

## Enhancing WinUAC: New Techniques for Administrators

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

## What Behaviors Does UAC Have for Administrators?

 Before you go about changing the way UAC acts for administrators, it helps to know what behaviors you can choose and what they mean. We’re going to list them below, along with the definitions that are listed on [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-administrators-in-admin-approval-mode).

 Here’s what you can choose:

* **Elevate without prompting**: Assumes that the administrator will permit an operation that requires elevation, and more consent or credentials aren't required. This minimizes the protection that is provided by UAC.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a privileged username and password. If the user enters valid credentials, the operation continues with the user's highest available privilege.
* **Prompt for consent on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the administrator to type the username and password. If the administrator enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for consent**: An operation that requires elevation of privilege prompts the administrator to select **Permit** or **Deny**. If the administrator selects **Permit**, the operation continues with the administrator's highest available privilege.
* **Prompt for consent for non-Windows binaries**: This prompt for consent is the default. When an operation for a non-Microsoft application requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.

 Now that you're familiar with the UAC behaviors for administrators, let’s see how to change them.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->

 To apply and save the changes, click on **OK**.

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enter one of the following variables in the text box for **Value date**:

| Variable | UAC Behavior                                 |
| -------- | -------------------------------------------- |
| 0        | Elevate without prompting                    |
| 1        | Prompt for credentials on the secure desktop |
| 2        | Prompt for consent on the secure desktop     |
| 3        | Prompt for credentials                       |
| 4        | Prompt for consent                           |
| 5        | Prompt for consent for non-Windows binaries  |

 So, if you were to, for example, change it to **Prompt for credentials**, you’d enter **3** in the **Value data** text box.

![Editing the ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-consentpromptbehavior-value-registry-editor.jpg)

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flawless-free-download-of-youtube-video-covers-no-hurdles/"><u>[New] In 2024, Flawless Free Download of YouTube Video Covers - No Hurdles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-correcting-muted-voice-in-obs-broadcasts-for-2024/"><u>[Updated] Correcting Muted Voice in OBS Broadcasts for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-easily-access-igtv-content-download-guide-for-pcmac-users/"><u>[Updated] In 2024, Easily Access IGTV Content  Download Guide for PC/Mac Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-facebook-avatar-create-your-own-cartoonish-character/"><u>[Updated] In 2024, Facebook Avatar  Create Your Own Cartoonish Character</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-mastering-tiktok-update-your-video-framing/"><u>[Updated] In 2024, Mastering TikTok  Update Your Video Framing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-preserving-profile-prestige-from-pretend-popularity-pitfalls-for-2024/"><u>[Updated] Preserving Profile Prestige From Pretend Popularity Pitfalls for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-sky-perspectives-in-stunning-hd-a-mi-drone-reality/"><u>[Updated] Sky Perspectives in Stunning HD  A Mi Drone Reality</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-social-media-visuals-aspect-ratio-decisions-for-2024/"><u>[Updated] Social Media Visuals  Aspect Ratio Decisions for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-mechanism-behind-cross-audio-blending/"><u>[Updated] Unveiling the Mechanism Behind Cross-Audio Blending</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-master-list-saving-your-favorite-ringtone-files/"><u>2024 Approved  Master List  Saving Your Favorite Ringtone Files</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mememolding-cutter/"><u>2024 Approved  MemeMolding Cutter</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-restoring-access-to-shared-windows-data/"><u>Breakthrough: Restoring Access to Shared Windows Data</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-wireless-divide-quick-fixes-for-windows-usb-adapter-issues/"><u>Bridging Wireless Divide – Quick Fixes for Windows' USB Adapter Issues</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-0x80246007-flaw-in-windows-11-updates/"><u>Bypassing 0X80246007 Flaw in Windows 11 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-forced-closure-errors-from-roblox-on-pcs/"><u>Bypassing Forced Closure Errors From Roblox on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-it-administrator-power-error-on-windows/"><u>Bypassing Limited IT Administrator Power Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-settings-for-windows-folders/"><u>Bypassing Read-Only Settings for Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-10-and-11s-vital-parts-required-errors/"><u>Bypassing Windows 10 & 11'S 'Vital Parts Required' Errors</u></a></li>
<li><a href="https://win11.techidaily.com/cant-open-handbrake-on-windows-try-these-fixes/"><u>Can't Open HandBrake on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-sound-simultaneously-with-video-in-snipping-tool-max-156/"><u>Capturing Sound Simultaneously with Video in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-intel-graphic-spec-limitations-a-guide-to-improvement/"><u>Circumventing Intel Graphic Spec Limitations: A Guide to Improvement</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-the-nvidia-cant-connect-error-in-windows-11/"><u>Circumventing the NVIDIA Can't Connect Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clarify-display-issues-windows-11-gpu-guide/"><u>Clarify Display Issues: Windows 11 GPU Guide</u></a></li>
<li><a href="https://win11.techidaily.com/classic-game-catch-up-storing-vintage-games-in-w11-folder/"><u>Classic Game Catch-Up: Storing Vintage Games in W11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-clean-automating-your-files-end-of-life-in-windows/"><u>Clear and Clean: Automating Your Files' End of Life in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clear-path-to-fixed-system-control-disruption-by-rogue-windows-software/"><u>Clear Path to Fixed System Control Disruption by Rogue Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-roadblocks-for-seamless-amd-software-setup/"><u>Clearing Roadblocks for Seamless AMD Software Setup</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-directdraw-confusion-on-newer-windows-editions/"><u>Clearing Up DirectDraw Confusion on Newer Windows Editions</u></a></li>
<li><a href="https://win11.techidaily.com/closing-the-gap-between-pc-and-androids-pace/"><u>Closing The Gap Between PC and Android's Pace</u></a></li>
<li><a href="https://win11.techidaily.com/coherent-ideas-at-a-glance-via-obsidian-canvas/"><u>Coherent Ideas at a Glance via Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/combat-lossed-graphics-a-guide-for-overwatch-2-players/"><u>Combat Lossed Graphics: A Guide for Overwatch 2 Players</u></a></li>
<li><a href="https://win11.techidaily.com/combat-strategies-for-operational-error-740-in-windows-devices/"><u>Combat Strategies for Operational Error #740 in Windows Devices</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/comprehensive-data-removal-advice-and-blog-posts-curated-by-stellar-experts/"><u>Comprehensive Data Removal Advice & Blog Posts Curated by Stellar Experts</u></a></li>
<li><a href="https://change-location.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/drive-your-display-to-new-heights-win-edition/"><u>Drive Your Display to New Heights - Win Edition</u></a></li>
<li><a href="https://program-issues.techidaily.com/fix-rockstar-game-services-are-unavailable-on-pc/"><u>Fix Rockstar Game Services Are Unavailable on PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-infinix-note-30-vip-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Infinix Note 30 VIP Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/premier-tactics-capturing-high-quality-sporting-live-events-for-2024/"><u>Premier Tactics  Capturing High-Quality Sporting Live Events for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamless-video-calls-in-your-inbox-setting-up-google-duo-on-gmail/"><u>Seamless Video Calls in Your Inbox: Setting Up Google Duo on Gmail</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-boost-mobile-apple-iphone-15-before-the-plan-expires-by-drfone-ios/"><u>Unlock Your Boost Mobile Apple iPhone 15 Before the Plan Expires</u></a></li>
</ul></div>
