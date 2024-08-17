---
title: Redefining Admin Control in Windows OS Security
date: 2024-08-15T23:45:02.368Z
updated: 2024-08-16T23:45:02.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redefining Admin Control in Windows OS Security
excerpt: This Article Describes Redefining Admin Control in Windows OS Security
keywords: Admin Control Security,Windows Admin Safeguard,Secure Admin Windows,OS Admin Protection,Redefine Admin Safety,Windows Admin Ops,OS Admin Defense
thumbnail: https://thmb.techidaily.com/5da3799a8bedda4d69cf1376b93deacb85f38c0ac9294944d02b8e17d908c0f4.png
---

## Redefining Admin Control in Windows OS Security

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

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-essential-tips-for-skyrocketing-your-instagram-followers/"><u>[New] Essential Tips for Skyrocketing Your Instagram Followers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-inside-stardust-an-extensive-exploration-of-stardew-valley-with-a-focus-on-its-enigmatic-island-ginger-isle/"><u>[New] Inside Stardust  An Extensive Exploration of Stardew Valley with a Focus on Its Enigmatic Island - Ginger Isle</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-finding-the-most-economical-streaming-apps-for-your-phone/"><u>[Updated] Finding the Most Economical Streaming Apps for Your Phone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-shaping-tomorrow-celebrating-the-top-6-in-nft-artistry/"><u>[Updated] Shaping Tomorrow  Celebrating the Top 6 in NFT Artistry</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-audio-to-video-bridge-easy-3-step-guide-for-mp3-to-youtube-uploads/"><u>2024 Approved  Audio-to-Video Bridge  Easy 3-Step Guide for MP3 to YouTube Uploads</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-10-innovative-mobile-layering-apps-for-android-and-iphone/"><u>2024 Approved  Top 10 Innovative Mobile Layering Apps for Android & iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-honor-v-purse-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://extra-resources.techidaily.com/androids-leading-collage-tools-the-ultimate-list/"><u>Android's Leading Collage Tools  The Ultimate List</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-techniques-to-prevent-disconnect-errors-during-discord-setup/"><u>Avoidance Techniques to Prevent Disconnect Errors During Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/captivating-viewers-with-youtubes-visual-polishing-for-2024/"><u>Captivating Viewers with Youtube's Visual Polishing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-edition-enhance-windows-11/"><u>Christmas Edition: Enhance Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-how-to-execute-system-file-checker-sfc/"><u>Command Line: How to Execute System File Checker (SFC)</u></a></li>
<li><a href="https://app-tips.techidaily.com/complete-guide-steps-to-safely-update-or-fresh-install-itunes-without-data-loss/"><u>Complete Guide: Steps to Safely Update or Fresh Install iTunes without Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/discover-why-your-windows-11-icons-are-diminishing/"><u>Discover Why Your Windows 11 Icons Are Diminishing</u></a></li>
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-downloads-for-your-canon-imageclass-mf4800-printing-needs/"><u>Easy Downloads for Your Canon ImageCLASS MF4800 Printing Needs</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-organization-synergizing-to-do-and-ifttt/"><u>Enhance Organization: Synergizing To-Do & IFTTT</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-team-chats-on-windows-1110/"><u>Ensuring Smooth Team Chats on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-alternatives-how-to-access-imessage-on-windows/"><u>Exploring Alternatives: How to Access iMessage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/expressive-ideas-on-a-canvas-direct-drawing-in-windows-11/"><u>Expressive Ideas on a Canvas: Direct Drawing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-device-stall-code-0x887a0006-guide/"><u>Fixing Device Stall: Code 0X887A0006 Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-iphone-12-mini-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From iPhone 12 mini</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/july-2024-linksys-security-credentials-revealed-managing-default-passwords-easily/"><u>July 2024 Linksys Security Credentials Revealed: Managing Default Passwords Easily</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win-rpc-failures-five-must-try-fixes/"><u>Navigating Win RPC Failures: Five Must-Try Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/non-light-no-problem-master-five-cures-for-backlit-keyboard-failure/"><u>Non-Light, No Problem: Master Five Cures for Backlit Keyboard Failure</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launch-failures-fixing-windows-speech-recognition/"><u>Overcoming Launch Failures: Fixing Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-techniques-for-unlocking-your-system-writable-files/"><u>Powerful Techniques for Unlocking Your System' Writable Files</u></a></li>
<li><a href="https://win11.techidaily.com/1719196389328-resolving-stuck-windows-update-problems-now/"><u>Resolving Stuck Windows Update Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-passwords-windows-file-integration-guide/"><u>Securely Storing Passwords: Windows File Integration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-windows-dism-hurdle-error-0x800f082f/"><u>Steering Clear of Windows' DISM Hurdle: Error 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-how-to-engage-windows-11s-system-restore-mechanism/"><u>Step-by-Step: How to Engage Windows 11'S System Restore Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-control-of-active-elements-post-sleep/"><u>Strategic Control of Active Elements Post-Sleep</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-a-guide-to-idle-shutdown-in-windows-11/"><u>Streamline System Use: A Guide to Idle Shutdown in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-git-management-harnessing-power-with-github-desktop-and-windows-11/"><u>The Art of Git Management: Harnessing Power with GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-moment-update-a-treasure-trove-of-features/"><u>Windows 11'S Moment Update - A Treasure Trove of Features?</u></a></li>
</ul></div>
