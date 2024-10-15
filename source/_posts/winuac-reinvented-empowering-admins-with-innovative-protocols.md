---
title: "WinUAC Reinvented: Empowering Admins with Innovative Protocols"
date: 2024-10-11T16:57:50.555Z
updated: 2024-10-15T20:41:25.599Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinUAC Reinvented: Empowering Admins with Innovative Protocols"
excerpt: "This Article Describes WinUAC Reinvented: Empowering Admins with Innovative Protocols"
keywords: Admin Power Tools,UAC Protocol Upgrade,Innovate User Control,Enhanced Security Admin,Advanced UAC Solutions,New UAC Techniques,Administrative Efficiency
thumbnail: https://thmb.techidaily.com/bca79052c5cd9d97263eb9f9d9f77145f2fe6968554def245326bd7e9d126f27.jpg
---

## WinUAC Reinvented: Empowering Admins with Innovative Protocols

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-a-drone-transformed-with-yuneecs-typhoon-q500/"><u>[New] A Drone Transformed with Yuneec's Typhoon Q500</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-best-mobile-and-desktop-mkv-software/"><u>[New] Best Mobile and Desktop MKV Software</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-immersive-worlds-confrontation-metaverse-vs-omniverse-explored/"><u>[Updated] Immersive Worlds Confrontation Metaverse Vs. Omniverse Explored</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-innovative-approaches-to-recording-and-editing-video-vo-for-2024/"><u>[Updated] Innovative Approaches to Recording and Editing Video VO for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/5770hdamdgpusupportwinxi/"><u>5770HDAMDGPUSupportWinXI</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-vivo-v27-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enterprises-evolve-with-open-access-to-chatgpt-whisper-apis/"><u>Enterprises Evolve with Open Access to ChatGPT, Whisper APIs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-invalid-profiles-on-windows-10-and-11-systems/"><u>Fixing Invalid Profiles on Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-updates-error-0x8024a205/"><u>How to Fix Windows Update's Error 0X8024a205</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-max-with-imei-code-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Pro Max with IMEI Code?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-selective-edits-blurring-images-in-ps-for-2024/"><u>Mastering Selective Edits Blurring Images in PS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-navigation-through-narrator-commands/"><u>Mastering the Art of Windows Navigation Through Narrator Commands</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-discords-devastating-javascript-problems-in-w10w11-systems/"><u>Overcoming Discord's Devastating Javascript Problems in W10/W11 Systems</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    