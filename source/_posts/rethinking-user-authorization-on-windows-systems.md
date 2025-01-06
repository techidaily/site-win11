---
title: Rethinking User Authorization on Windows Systems
date: 2025-01-05T18:45:53.403Z
updated: 2025-01-06T19:27:57.829Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/n-2024-elevate-your-learning-the-top-10-educational-historians-yt/"><u>[New] In 2024, Elevate Your Learning The Top 10 Educational Historians YT</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-ai-enhanced-naming-mastery-for-podcast-creatives/"><u>[Updated] 2024 Approved AI-Enhanced Naming Mastery for Podcast Creatives</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-live-streaming-pre-recorded-videos-the-facebook-approach/"><u>[Updated] Live Streaming Pre-Recorded Videos The Facebook Approach</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-the-future-of-computing-in-windows-11-for-2024/"><u>[Updated] The Future of Computing in Windows 11 for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dont-miss-out-secure-your-discounted-amazon-fire-hd/"><u>Don't Miss Out! Secure Your Discounted Amazon Fire HD</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/examining-the-impact-of-the-great-wall-in-shaping-chinas-historical-narrative-insights-from-yl-computing/"><u>Examining the Impact of the Great Wall in Shaping China's Historical Narrative - Insights From YL Computing</u></a></li>
<li><a href="https://win11.techidaily.com/fostering-vintage-gaming-experience-with-retroarch-shaders/"><u>Fostering Vintage Gaming Experience with RetroArch Shaders</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-s17t-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from S17t</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-solo-operation-of-auto-gpt-justifiable/"><u>Is Solo Operation of Auto-GPT Justifiable?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/memorial-day-special-save-400-on-the-e-zoom-segway-max-g2-electric-scooter-shop-now-at-zdnet/"><u>Memorial Day Special: Save $400 on the E-Zoom Segway Max G2 Electric Scooter - Shop Now at ZDNET!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-activation-error-code-0x803f700f/"><u>Navigating Through Windows Activation Error Code 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functionality-fixing-ccleaner-issues-on-windows-1011/"><u>Reinstating Functionality: Fixing CCleaner Issues on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-system-management-skills-with-these-20-cmd-commands/"><u>Step Up Your System Management Skills with These 20 CMD Commands</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-tweaking-windows-metadata-dates/"><u>The Ultimate Guide to Tweaking Windows Metadata Dates</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-microsoft-shop-error-x80131500/"><u>Unblocking Microsoft Shop Error X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-window-images-with-high-quality-standards/"><u>Unleashing Window Images with High-Quality Standards</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-win-os-anomalies-a-guide-to-debugging-errors-via-the-power-of-command-prompt/"><u>Unraveling Win-OS Anomalies: A Guide to Debugging Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-8-best-meme-maker-app-to-create-memes-with-your-own-picture/"><u>Updated 8 Best Meme Maker App to Create Memes with Your Own Picture</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10-stickers-reasons-to-delay-switching/"><u>Windows 10 Stickers: Reasons to Delay Switching</u></a></li>
</ul></div>

