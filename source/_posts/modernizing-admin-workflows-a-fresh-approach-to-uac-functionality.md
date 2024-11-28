---
title: "Modernizing Admin Workflows: A Fresh Approach to UAC Functionality"
date: 2024-11-24T17:20:48.646Z
updated: 2024-11-28T00:18:20.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Modernizing Admin Workflows: A Fresh Approach to UAC Functionality"
excerpt: "This Article Describes Modernizing Admin Workflows: A Fresh Approach to UAC Functionality"
keywords: Modern Admin Systems,Streamlined Admin Procedures,Enhanced User Access Control,Efficient Admin Workflows,Updated UAC Management,Improved UAC Functionality,Administrative Process Innovation
thumbnail: https://thmb.techidaily.com/267319de45b47bfed89a5beeea4e8662c6ef68d4fb035ab41968a0873cebbd66.jpg
---

## Modernizing Admin Workflows: A Fresh Approach to UAC Functionality

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

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-top-picks-free-fb-to-mp4-file-transformers/"><u>[New] 2024 Approved Top Picks Free FB to MP4 File Transformers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-budget-friendly-tips-for-acquiring-high-end-gopros/"><u>[New] In 2024, Budget-Friendly Tips for Acquiring High-End GoPros</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-splashing-through-the-best-fluid-games-roundup/"><u>[New] In 2024, Splashing Through the Best Fluid Games Roundup</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-streamlined-steps-for-preserving-vimeo-recordings/"><u>2024 Approved Streamlined Steps for Preserving Vimeo Recordings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/5-ways-to-access-gpt-4-for-free/"><u>5 Ways to Access GPT-4 for Free</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-poco-x6-pro-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Poco X6 Pro</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-yet-powerful-top-wmv-video-editors-for-2024/"><u>Free Yet Powerful Top WMV Video Editors for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/harness-the-power-of-cookiebot-for-improved-web-analytics/"><u>Harness the Power of Cookiebot for Improved Web Analytics</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-a-specific-windows-bt-directory/"><u>How to Delete a Specific Windows ~BT Directory</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-failed-unzipping-in-windows-11-systems/"><u>How To Repair Failed Unzipping in Windows 11 Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-xiaomi-redmi-note-12-pro-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Xiaomi Redmi Note 12 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/keep-top-spot-for-note-taking-on-win-1011-oses/"><u>Keep Top Spot for Note Taking on Win 10/11 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-visibility-settings-for-win-11-cursors/"><u>Navigating Visibility Settings for Win 11 Cursors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-with-asana-on-windows-operating-systems/"><u>Overcoming Common Roadblocks with Asana on Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-file-explorer-crashes-with-proactive-windows-11-tips/"><u>Prevent File Explorer Crashes with Proactive Windows 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-proxy-in-windows-11/"><u>Setting Up Your Proxy in Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-path-to-personalization-adjusting-snapchat-videos-pace/"><u>The Path to Personalization Adjusting Snapchat Videos' Pace</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-desktop-expanding-context-menus/"><u>Win 11 Desktop: Expanding Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-god-mode-essential-tasks-to-enhance-efficiency/"><u>Windows 11 God Mode: Essential Tasks to Enhance Efficiency</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    