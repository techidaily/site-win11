---
title: "Breaking Barriers: Reimagining Administrative Protocols on Windows"
date: 2025-02-27T18:05:20.587Z
updated: 2025-03-04T23:28:09.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breaking Barriers: Reimagining Administrative Protocols on Windows"
excerpt: "This Article Describes Breaking Barriers: Reimagining Administrative Protocols on Windows"
keywords: Admin Protocol Windows,Windoaks Reform,Breaking Admin Rules,Reimagined WinAdmin,Barriers in Windows Policy,Protocol Innovation Windows,New Windows Governance
thumbnail: https://thmb.techidaily.com/380105e59c8959c0073d444abec887193c4b497adc4a29c490c9f0b91ceeacb3.jpg
---

## Breaking Barriers: Reimagining Administrative Protocols on Windows

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/cclaimed-storytellers-with-photo-audio-symphony/"><u>[New] Acclaimed Storytellers with Photo-Audio Symphony</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-androids-secret-weapon-for-stunning-time-lagged-footage-for-2024/"><u>[Updated] Android's Secret Weapon for Stunning Time-Lagged Footage for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitpic-saver-streamline-ios-video-downloads-from-tweets/"><u>[Updated] TwitPic Saver Streamline iOS Video Downloads From Tweets</u></a></li>
<li><a href="https://win-docs.techidaily.com/creating-a-successful-online-boutique-with-massmail-a-step-by-step-guide/"><u>Creating a Successful Online Boutique with MassMail: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-the-error-when-amd-radeon-software-does-not-open/"><u>How To Resolve The Error When AMD Radeon Software Does Not Open</u></a></li>
<li><a href="https://fox-direct.techidaily.com/navigating-your-first-stride-into-snapseed-land-for-2024/"><u>Navigating Your First Stride Into Snapseed Land for 2024</u></a></li>
<li><a href="https://techidaily.com/new-windows-11-update-allows-integration-of-smartphone-images/"><u>New Windows 11 Update Allows Integration of Smartphone Images</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-freeze-in-the-epic-launcher-on-windows-pcs/"><u>Overcoming Freeze in the Epic Launcher on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revival-strategies-for-net-on-your-pc-max-156/"><u>Revival Strategies for .NET on Your PC (Max 156)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-a-dead-laptop-mouse-effective-solutions-for-stuck-or-non-responsive-usb-devices/"><u>Revive a Dead Laptop Mouse: Effective Solutions for Stuck or Non-Responsive USB Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/safari-tab-management-on-macos-monterey-enabling-self-destruct-feature-for-efficient-browsing/"><u>Safari Tab Management on macOS Monterey: Enabling Self-Destruct Feature for Efficient Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/scheme-for-activatingdeactivating-setup-service-on-pcs/"><u>Scheme for Activating/Deactivating Setup Service on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-to-your-digital-past-file-history-guide/"><u>The Window to Your Digital Past: File History Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-mysteries-of-windows-group-policies-3-different-perspectives/"><u>Unlocking the Mysteries of Windows Group Policies: 3 Different Perspectives</u></a></li>
</ul></div>

