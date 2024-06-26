---
title: "Windows: Adjusting User Permissions for Regular Accounts"
date: 2024-06-25T09:53:51.675Z
updated: 2024-06-26T09:53:51.675Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows: Adjusting User Permissions for Regular Accounts"
excerpt: "This Article Describes Windows: Adjusting User Permissions for Regular Accounts"
keywords: Windows Security,Access Control,User Rights Management,Privilege Settings,Regular Account Policy,Permission Leveling,Guest Account Restrictions
thumbnail: https://thmb.techidaily.com/5b6554e76aaa2a052eebb5ed360ccf43529d16f47d56cedf742a90d738a59cc9.jpg
---

## Windows: Adjusting User Permissions for Regular Accounts

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/stepping-up-to-full-operating-system-windows-for-steam-deck/"><u>Stepping Up to Full Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-absence-of-battery-life-duration-in-pcs-running-win-11/"><u>Overcoming the Absence of Battery Life Duration in PCs Running Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-windows-task-management-addressing-misplaced-cpu-metrics/"><u>Fixes for Windows Task Management: Addressing Misplaced CPU Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-scripting-techniques-upgraded-file-system-interactions/"><u>Advanced Scripting Techniques: Upgraded File System Interactions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-window-resolutions/"><u>Enhancing Your Visual Experience with Window Resolutions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlocking-earnings-potential-dm-and-yo-showdown/"><u>Unlocking Earnings Potential  Dm & Yo Showdown</u></a></li>
<li><a href="https://some-approaches.techidaily.com/total-earning-summary-for-pewdiepie-star-for-2024/"><u>Total Earning Summary for PewDiePie Star for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagrowth-hack-secrets-for-scaling-to-1000month-fans-for-2024/"><u>InstaGrowth Hack  Secrets for Scaling to 1,000/Month Fans for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/maximize-your-creativity-a-detailed-instruction-manual-for-uploading-videos-on-youtube-for-2024/"><u>Maximize Your Creativity  A Detailed Instruction Manual for Uploading Videos on YouTube for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sky-hdr-perfection-top-website-reviews/"><u>2024 Approved  Sky HDR Perfection - Top Website Reviews</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-the-sound-of-success-a-beginners-guide-to-youtube-audio-downloads/"><u>Updated 2024 Approved The Sound of Success A Beginners Guide to YouTube Audio Downloads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-activation-lock-on-iphone-7-plus-4-easy-ways-by-drfone-ios/"><u>Bypass Activation Lock On iPhone 7 Plus - 4 Easy Ways</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-what-is-an-ai-artist/"><u>Updated In 2024, What Is an AI Artist?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>