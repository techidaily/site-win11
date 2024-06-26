---
title: Next-Gen Access Management for Windows Administrators
date: 2024-06-25T11:29:58.574Z
updated: 2024-06-26T11:29:58.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Next-Gen Access Management for Windows Administrators
excerpt: This Article Describes Next-Gen Access Management for Windows Administrators
keywords: Win Admin Access Mgmt,Next-Gen WM AceMngt,Advanced WIN AceMgnt,Secure WM Access Manag,Enhanced Windows Admins,ProWX Windows AceMgr,Innovate WM AdmNt Sys
thumbnail: https://thmb.techidaily.com/bb05cc1f39777472d93269752aa648567cff43de237a4feeb628da33c12d9648.jpg
---

## Next-Gen Access Management for Windows Administrators

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

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/resolving-failures-restoring-java-on-windows-devices/"><u>Resolving Failures: Restoring Java on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-3d-paint-efficiency-with-these-tricks/"><u>Boost Your 3D Paint Efficiency With These Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-xfffeeee-error-on-your-office-printer/"><u>Eliminating XFFFEEEE Error on Your Office Printer</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsofts-activation-error-code-0x8007251d/"><u>Tackling Microsoft's Activation Error Code 0X8007251d</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-senior-accessibility-on-legacy-computers/"><u>Enhancing Senior Accessibility on Legacy Computers</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-approach-to-disable-unnecessary-windows-11-services/"><u>Proactive Approach to Disable Unnecessary Windows 11 Services</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-service-failures-fixing-steam-errors-on-windows-11/"><u>Mastery Over Service Failures: Fixing Steam Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-ordinary-to-outstanding-making-unique-discord-pfps/"><u>From Ordinary to Outstanding  Making Unique Discord Pfps</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-best-wmv-to-gif-converters-for-2024/"><u>Updated | Best WMV to GIF Converters for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-4-ways-to-record-internal-android-audio-no-rooting/"><u>[New] In 2024, 4 Ways to Record Internal Android Audio (No Rooting)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-monetize-like-a-pro-how-to-use-youtube-studio-on-any-device-for-2024/"><u>[Updated] Monetize Like a Pro  How to Use Youtube Studio on Any Device for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-capturing-online-clarity-a-zoomers-guide/"><u>2024 Approved  Capturing Online Clarity  A Zoomer's Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-silencing-the-distractions-leveraging-artificial-intelligence-in-signal-refinement/"><u>2024 Approved Silencing the Distractions Leveraging Artificial Intelligence in Signal Refinement</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-motorola-edge-40-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Motorola Edge 40 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-from-iphone-x-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock From iPhone X You Should Try Out</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-maximize-views-with-these-top-rated-keyword-analysis-tools/"><u>In 2024, Maximize Views with These Top-Rated Keyword Analysis Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>