---
title: "Administrative Evolution: Reimagining Control in a Windows World"
date: 2024-08-08T13:15:25.921Z
updated: 2024-08-09T13:15:25.921Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Administrative Evolution: Reimagining Control in a Windows World"
excerpt: "This Article Describes Administrative Evolution: Reimagining Control in a Windows World"
keywords: Admin Control Shift,Windows Administration,Evolving IT Management,Reimagine Workflows,PC Power Dynamics,System Oversight Change,Global Control Revision
thumbnail: https://thmb.techidaily.com/db39cf974b891a971b269fa1b5c545ac5598c4412d012bd826ff7f5dff9de440.png
---

## Administrative Evolution: Reimagining Control in a Windows World

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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
<li><a href="https://vimeo-videos.techidaily.com/new-audio-enhancement-including-tracks-in-vimeo-clips-for-2024/"><u>[New] Audio Enhancement  Including Tracks in Vimeo Clips for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-generate-stellar-podcast-title-ideas/"><u>[Updated] How to Generate Stellar Podcast Title Ideas</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-improve-conference-efficiency-webcam-assisted-powerpoint/"><u>[Updated] In 2024, Improve Conference Efficiency  Webcam-Assisted PowerPoint</u></a></li>
<li><a href="https://tech-revival.techidaily.com/22-streamline-communication-leading-free-ai-email-services/"><u>22 Streamline Communication: Leading Free AI Email Services</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-a-spotless-system-restart-in-windows-11/"><u>Achieving a Spotless System Restart in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/audible-allure-choosing-background-beats-for-videos-for-2024/"><u>Audible Allure  Choosing Background Beats for Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-task-management-learn-filters-and-themes-customization-in-windows-11/"><u>Boost Productivity with Task Management: Learn Filters and Themes Customization in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-no-notification-policy-for-ws11-cameras/"><u>Bypassing No-Notification Policy for WS11 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unsigned-files-error-for-windows-1110/"><u>Bypassing Unsigned Files Error for Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-comprehensive-policies-reports-via-gpresult/"><u>Crafting Comprehensive Policies Reports via GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-harmony-windows-app-compatible-with-apple-and-microsoft-pcsmacs/"><u>Cross-Platform Harmony: Windows App Compatible with Apple & Microsoft PCs/Macs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-503-server-errors-identification-reasons-and-remedies/"><u>Decoding 503 Server Errors - Identification, Reasons, and Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/displaying-numeric-key-status-in-system-tray-for-win11-users/"><u>Displaying Numeric Key Status in System Tray for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/easing-shared-printer-usage-conflict/"><u>Easing Shared Printer Usage Conflict</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unresponsive-windows-service-error-error-1053/"><u>Eliminating the Unresponsive Windows Service Error (Error 1053)</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-repairing-your-windows-11-printer/"><u>Essential Tips for Repairing Your Windows 11 Printer</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-pick-prime-photo-organizers-for-windows/"><u>Excellent Pick: Prime Photo Organizers For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fan-the-fire-essential-tips-for-cooler-gameplay-on-overheated-windows-laptops/"><u>Fan the Fire: Essential Tips for Cooler Gameplay on Overheated Windows Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/faster-utorrent-file-sharing-a-guide-for-windows/"><u>Faster uTorrent File Sharing: A Guide for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11.</u></a></li>
<li><a href="https://win-answers.techidaily.com/get-unstuck-from-the-startup-loop-in-madden-nfl-22-expert-troubleshooting-tips-and-solutions/"><u>Get Unstuck From the Startup Loop in Madden NFL 22: Expert Troubleshooting Tips and Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-stalled-windows-batch-processes/"><u>Guide to Reactivating Stalled Windows Batch Processes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-no-hypervisor-detection-in-sandbox-mode/"><u>How to Address No Hypervisor Detection in Sandbox Mode</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/imbalances-can-lead-to-soil-depletion-or-pest-outbreaks-a-balanced-ecosystem-promotes-healthy-crops-and-resilience-against-diseases/"><u>Imbalances Can Lead to Soil Depletion or Pest Outbreaks; a Balanced Ecosystem Promotes Healthy Crops and Resilience Against Diseases</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-transformation-mp3-files-to-windows-compatible-audio-cds-with-imgburn/"><u>Immediate Transformation: MP3 Files to Windows-Compatible Audio CDs with ImgBurn</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-your-iphone-13-pro-max-from-your-apple-id-by-drfone-ios/"><u>In 2024, How To Unlink Your iPhone 13 Pro Max From Your Apple ID</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-melding-melodies-with-memories-in-cyberspace/"><u>In 2024, Melding Melodies with Memories in Cyberspace</u></a></li>
<li><a href="https://win11.techidaily.com/learn-how-to-turn-off-games-for-w11-suggestions/"><u>Learn How To Turn Off Games for W11 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-overcoming-forbidden-errors/"><u>Mastering the Art of Overcoming Forbidden Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-recovering-without-admin-creds/"><u>Mastering Windows 11: Recovering without Admin Creds</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-through-edges-webview2-controls/"><u>Optimizing System Resources Through Edge's WebView2 Controls</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-problem-zerosevennine/"><u>Overcoming System Problem ZeroSevenNine</u></a></li>
<li><a href="https://win11.techidaily.com/preempting-vagrant-start-issues-for-vms-on-win11os/"><u>Preempting Vagrant Start Issues for VMs on Win11OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-windows-11-mailcalendar/"><u>Quick Guide: Resetting Windows 11 Mail/Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insight-navigating-newly-opened-window-folders/"><u>Quick Insight: Navigating Newly Opened Window Folders</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-steam-sync-errors-in-windows/"><u>Remedying Steam Sync Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-iomap64-system-crashes-and-bsod-quickly-on-pcs/"><u>Resolve IOMap64 System Crashes and BSoD Quickly on PCs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/scandinavian-tech-showdown-skagen-falster-2-vs-apples-designer-phones/"><u>Scandinavian Tech Showdown: Skagen Falster 2 Vs. Apple's Designer Phones</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-sound-recording-on-windows-11/"><u>Streamline Your Sound Recording on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-essential-windows-shorthand/"><u>Streamline Your Workflow: Essential Windows Shorthand</u></a></li>
<li><a href="https://some-skills.techidaily.com/symbolizing-success-affordable-and-flexible-logo-crafting-from-templates-for-2024/"><u>Symbolizing Success  Affordable & Flexible Logo Crafting From Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/taming-erratic-errors-from-wins-protection-suite/"><u>Taming Erratic Errors From WINS Protection Suite</u></a></li>
<li><a href="https://win11.techidaily.com/taming-setting-turmoil-a-pubg-guide-for-pc-users/"><u>Taming Setting Turmoil: A PUBG Guide for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-6-key-steps-to-discovering-the-identity-of-your-pc-window-edition/"><u>The 6 Key Steps to Discovering the Identity of Your PC, Window Edition</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-techniques-for-net-healing-in-windows-max-156/"><u>Top 5 Techniques for .NET Healing in Windows (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-dangers-hacked-fingerprints-on-windows-pcs/"><u>Unlocking Dangers: Hacked Fingerprints on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-risks-associated-with-economical-licenses/"><u>Unveiling the Risks Associated with Economical Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/unwavering-erasure-made-simple-configuring-windows-trash-for-permanent-deletion/"><u>Unwavering Erasure Made Simple: Configuring Windows Trash for Permanent Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-cr2-photos-to-jpeg-format/"><u>Windows Guide: Converting CR2 Photos to JPEG Format</u></a></li>
</ul></div>
