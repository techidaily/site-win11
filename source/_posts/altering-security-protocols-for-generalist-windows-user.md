---
title: Altering Security Protocols for Generalist Windows User
date: 2024-06-25T09:48:40.134Z
updated: 2024-06-26T09:48:40.134Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Security Protocols for Generalist Windows User
excerpt: This Article Describes Altering Security Protocols for Generalist Windows User
keywords: Windows Security Update,Protocol Adjustment Tips,Secure Win User Access,General User Protocol,Enhanced Windows Protection,Optimize Window's Safety,Streamlining User Security
thumbnail: https://thmb.techidaily.com/8b5881e327b9c1ba2eb90535b5e52b8fb37d29efd85f95b1f8c43ff4375091ae.jpg
---

## Altering Security Protocols for Generalist Windows User

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
<li><a href="https://win11.techidaily.com/revive-the-lost-connection-top-9-remedies-for-missing-bluetooth-on-win-11/"><u>Revive the Lost Connection: Top 9 Remedies for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/expert-methods-purging-directdraw-problems-from-win1011-systems/"><u>Expert Methods: Purging DirectDraw Problems From WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/historical-code-to-contemporary-computing-windows-7-to-11-activation/"><u>Historical Code to Contemporary Computing: Windows 7 to 11 Activation</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-11-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-enhance-video-popularity-with-strategic-timestamps/"><u>[Updated] In 2024, Enhance Video Popularity with Strategic Timestamps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-your-youtube-identity-with-cool-titles/"><u>In 2024, Master Your YouTube Identity with Cool Titles</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unleashing-the-best-video-footage-with-gopro-for-2024/"><u>[Updated] Unleashing the Best Video Footage with GoPro for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximize-your-inspiration-free-pinterest-video-downloaders-for-2024/"><u>Maximize Your Inspiration  Free Pinterest Video Downloaders for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/radiant-tone-refactoring-pro/"><u>Radiant Tone Refactoring Pro</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/gif-geniuses-selection-top-tiktok-conversion-software-for-2024/"><u>GIF Geniuses' Selection  Top TikTok Conversion Software for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-ultimate-guide-from-script-writing-to-final-audio-in-videos-for-2024/"><u>[Updated] Ultimate Guide  From Script Writing to Final Audio in Videos for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-harnessing-hidden-auditory-elements-in-videos-a-2023-approach-to-enhanced-sound-recovery/"><u>New 2024 Approved Harnessing Hidden Auditory Elements in Videos A 2023 Approach to Enhanced Sound Recovery</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-jump-into-action-how-to-start-someones-tiktok-session/"><u>[New] Jump Into Action  How To Start Someone's TikTok Session</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-f04-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy F04 Phone Hassle-Free</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>