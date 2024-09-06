---
title: Pioneering a Fresh Approach to Admin Rights on Windows OS
date: 2024-09-05T08:43:09.265Z
updated: 2024-09-06T08:43:09.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pioneering a Fresh Approach to Admin Rights on Windows OS
excerpt: This Article Describes Pioneering a Fresh Approach to Admin Rights on Windows OS
keywords: Win Admin Access Guide,Windows RBAC Overhaul,Secure OS Permissions,User Rights Management,Enhanced OS Privilege,New Windows Authorization,OS Security Adjustments
thumbnail: https://thmb.techidaily.com/52f669a15e335bb29d06275250544e9470586ee079bd1c12147b53606781363c.jpg
---

## Pioneering a Fresh Approach to Admin Rights on Windows OS

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-video-constructor-suite/"><u>[New] 2024 Approved  Video Constructor Suite</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-harnessing-instagram-video-potential-crafting-a-strong-marketing-strategy-for-2024/"><u>[New] Harnessing Instagram Video Potential  Crafting a Strong Marketing Strategy for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-instagram-story-and-reels-transform-your-vocal-brand-with-these-tricks/"><u>[New] In 2024, Instagram Story & Reels  Transform Your Vocal Brand with These Tricks</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-make-waves-with-a-new-look-customize-pre-designed-brand-symbols/"><u>[New] In 2024, Make Waves with a New Look  Customize Pre-Designed Brand Symbols</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hacks-create-youtube-shorts-thumbnails-that-stand-out-quickly/"><u>[Updated] 2024 Approved  Hacks  Create YouTube Shorts Thumbnails That Stand Out Quickly</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-expert-choices-best-6-fb-lite-video-saves/"><u>[Updated] In 2024, Expert Choices  Best 6 FB Lite Video Saves</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-samsung-galaxy-m14-5g-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Samsung Galaxy M14 5G by Name | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/capturing-online-seminars/"><u>Capturing Online Seminars</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-kali-a-windows-users-guide/"><u>Dive Into Kali: A Windows User's Guide</u></a></li>
<li><a href="https://discover-blog.techidaily.com/effective-strategies-to-improve-page-ranking-on-google/"><u>Effective Strategies to Improve Page Ranking on Google</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-youtube-content-editing-in-adobe-premiere-for-2024/"><u>Elevate Your YouTube Content  Editing in Adobe Premiere for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-flicker-in-windows-os-a-step-by-step-guide/"><u>Eliminating Flicker in Windows OS: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-fullscreen-experience-tackling-windows-overscan/"><u>Enhance Fullscreen Experience: Tackling Windows Overscan</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-your-iphones-mtp-drivers-a-comprehensive-guide-to-solutions/"><u>Fixing Your iPhones' MTP Drivers - A Comprehensive Guide to Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-ctrl-key-malfunction-fixes-on-win11/"><u>Guiding You Through Ctrl Key Malfunction Fixes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-do-not-have-access-error-during-uninstall-on-windows-11/"><u>How to Overcome Do Not Have Access Error During Uninstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-xbox-game-update-issues-on-pc/"><u>How to Solve Xbox Game Update Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-windows-update-interruptions/"><u>How to Turn Off Windows Update Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-wirelessly-connect-a-ps3-dualshock-controller-to-windows/"><u>How to Wirelessly Connect a PS3 DualShock Controller to Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-apple-iphone-12-pro-max-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>In 2024, Apple iPhone 12 Pro Max Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-obs-timer-mastery-building-a-custom-countdown-timer/"><u>In 2024, OBS Timer Mastery  Building a Custom Countdown Timer</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-pro-audio-insight-expertly-selected-9-mic-recorder-devices/"><u>In 2024, Pro Audio Insight  Expertly Selected 9 Mic Recorder Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-protocols-and-performance-macos-meets-mixer/"><u>In 2024, Protocols and Performance  MacOS Meets Mixer</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-simple-guide-to-modify-vocal-effects-in-tiktok-videos/"><u>In 2024, Simple Guide to Modify Vocal Effects in TikTok Videos</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-the-dasung-paperlike-the-high-resolution-portable-e-ink-12-display-for-849-now-available-in-us/"><u>Introducing the Dasung Paperlike: The High-Resolution Portable E-Ink 12 Display for $849 - Now Available in U.S</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-techniques-for-clearing-ms-defender-log-on-pc/"><u>Master the Techniques for Clearing MS Defender Log on PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-restart-function-on-your-latest-iphone-15/"><u>Mastering the Restart Function on Your Latest iPhone 15</u></a></li>
<li><a href="https://win11.techidaily.com/mend-resolving-keyboard-issues-on-windows-11/"><u>Mend: Resolving Keyboard Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/off-the-cuff-tricks-to-work-with-onedrive-locally/"><u>Off-the-Cuff Tricks to Work with OneDrive Locally</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-multiscreen-woes-in-windows/"><u>Overcoming Multiscreen Woes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-adding-dolby-atmos-in-win-11-pro/"><u>Quick Steps for Adding Dolby Atmos in Win 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/rethinking-user-authorization-on-windows-systems/"><u>Rethinking User Authorization on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice!</u></a></li>
<li><a href="https://win11.techidaily.com/slash-cpu-usage-spikes-utilizing-windows-rm-wisdom/"><u>Slash CPU Usage Spikes: Utilizing Window's RM Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-autonomous-opens-in-microsoft-marketplace/"><u>Stopping Autonomous Opens in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-joining-onedrive-with-liveid-windows/"><u>The Ultimate Guide: Joining OneDrive with LiveID (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-typing-lag-seven-effective-fixes-for-win-os/"><u>Win over Typing Lag: Seven Effective Fixes for WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-trick-showhide-user-defined-directories/"><u>Windows 11 Trick: Show/Hide User-Defined Directories</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-gameplay-steps-to-recover-disconnected-league/"><u>Winning Back Gameplay: Steps to Recover Disconnected League</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>