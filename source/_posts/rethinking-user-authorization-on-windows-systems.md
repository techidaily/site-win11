---
title: Rethinking User Authorization on Windows Systems
date: 2024-08-23T06:10:14.362Z
updated: 2024-08-24T06:10:14.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rethinking User Authorization on Windows Systems
excerpt: This Article Describes Rethinking User Authorization on Windows Systems
keywords: WinUserAuthRevise,AccessControlWindows,IdentityManagementWin,AuthFlowRedesign,SecureLoginOS,CredentialChangeWin,WindowsAuthorizationUpdate
thumbnail: https://thmb.techidaily.com/ddb387910e1ac858898cd3858da4a32a6126aed2333f21b240bf9f3028949436.jpg
---

## Rethinking User Authorization on Windows Systems

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

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-immersive-worlds-unveiled-delving-into-mr-ar-and-vrs-distinctions/"><u>[New] Immersive Worlds Unveiled  Delving Into MR, AR, and VR's Distinctions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-secure-and-enhance-slack-communications-with-top-10-free-audio-apps/"><u>[New] Secure & Enhance Slack Communications with Top 10 Free Audio Apps</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-clipcraft-designer/"><u>[Updated] 2024 Approved  ClipCraft Designer</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-facebook-live-mastery-making-the-most-of-real-time-sharing-for-2024/"><u>[Updated] Facebook Live Mastery  Making the Most of Real-Time Sharing for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-action-in-pixelation-top-3-strategies-for-sports-gameplay-recordings/"><u>2024 Approved  Action in Pixelation  Top 3 Strategies for Sports Gameplay Recordings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-synergistic-campaigns-brands-and-youtube-hand-in-hand/"><u>2024 Approved  Synergistic Campaigns  Brands & YouTube Hand in Hand</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-games-on-windows-11-the-top-6-fps-measurement-software/"><u>Conquer Games on Windows 11: The Top 6 FPS Measurement Software</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-ad-ds-printing-woes-on-win-10-and-11-devices/"><u>Conquering AD DS Printing Woes on WIN 10 & 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/deciph-written-by-your-name/"><u>Deciph Written by [Your Name]</u></a></li>
<li><a href="https://win11.techidaily.com/embellish-your-windows-11-display-lively-and-animated-walls/"><u>Embellish Your Windows 11 Display: Lively and Animated Walls</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-performance-resurrecting-slow-excel-operations-on-windows/"><u>Enhance Performance: Resurrecting Slow Excel Operations on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/enhance-your-gaming-sims-4-on-camera-techniques/"><u>Enhance Your Gaming  Sims 4 on Camera Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-for-adjusting-windows-file-attributes/"><u>Expert Strategies for Adjusting Windows File Attributes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-video-splitter-online-and-offline-editors-for-dual-screen-videos/"><u>Free Video Splitter Online and Offline Editors for Dual-Screen Videos</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-brother-hl-l2n00d-printer-drivers-here/"><u>Get the Newest Brother HL-L2n00D Printer Drivers Here</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eradicate-partitioned-units-on-your-disk-in-a-flash/"><u>How to Eradicate Partitioned Units on Your Disk in a Flash</u></a></li>
<li><a href="https://win11.techidaily.com/hush-the-language-indicator-on-win11s-status-ui/"><u>Hush the Language Indicator on Win11’s Status UI</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-java-install-process-on-your-windows-pc/"><u>Mastering Java Install Process on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-elevates-windows-11-with-ai-powered-taskbar-assistant/"><u>Microsoft Elevates Windows 11 with AI-Powered Taskbar Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-default-search-settings-in-windows-11-version-11/"><u>Navigate to Default Search Settings in Windows 11, Version 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-stubborn-software-glitches-ps-and-windows-guide/"><u>Navigating Stubborn Software Glitches: PS & Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/obscuring-linguistic-icon-on-win11s-status-bar/"><u>Obscuring Linguistic Icon on Win11's Status Bar</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oppo-find-n3-flip-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo Find N3 Flip Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-low-vram-errors-in-magical-education-game-hogwarts/"><u>Overcoming Low VRAM Errors in Magical Education Game 'Hogwarts'</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-cloud-sync-linking-dropbox-and-google-drive-on-your-pc/"><u>Seamless Cloud Sync: Linking Dropbox & Google Drive on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-tasks-get-your-pcs-outlook-preview/"><u>Simplifying Tasks: Get Your PC's Outlook Preview</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-visual-composition-with-backdrop-blur-on-windows-11/"><u>Streamlining Visual Composition with Backdrop Blur on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-8-best-ways-to-fix-the-windows-operating-system-not-found-error/"><u>The 8 Best Ways to Fix the Windows Operating System Not Found Error</u></a></li>
<li><a href="https://win11.techidaily.com/unfreeze-windows-hibernate-with-simple-steps/"><u>Unfreeze Windows Hibernate with Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-potential-a-quick-fix-for-windows-pin/"><u>Unlock Potential: A Quick Fix for Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-techniques-for-full-ram-utilization-on-windows/"><u>Unveiling Hidden Techniques for Full RAM Utilization on Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-your-computers-display-with-new-rtx-1650-super-gpu-drivers-for-windows-1011-get-them-here/"><u>Update Your Computer's Display with New RTX 1650 Super GPU Drivers for WINDOWS 10/11 - Get Them Here</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-visual-appeal-with-fancywm-tech/"><u>Upgrade Your Visual Appeal with FancyWM Tech</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>