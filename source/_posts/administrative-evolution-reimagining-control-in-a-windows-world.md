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

