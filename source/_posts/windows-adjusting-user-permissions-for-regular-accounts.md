---
title: "Windows: Adjusting User Permissions for Regular Accounts"
date: 2024-06-25T11:25:57.936Z
updated: 2024-06-26T11:25:57.936Z
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
<li><a href="https://win11.techidaily.com/how-to-resolve-unexpected-token-call-issues-on-windows-devices/"><u>How To Resolve “Unexpected Token Call” Issues on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-importance-of-consistent-windows-data-saves/"><u>The Importance of Consistent Windows Data Saves</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overwatch-2s-missing-graphics-driver-error/"><u>Fixing Overwatch 2'S Missing Graphics Driver Error</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/key-practices-in-the-pursuit-of-a-pristine-windows-setup/"><u>Key Practices in the Pursuit of a Pristine Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-top-tools-for-silencing-unwanted-sound-in-podcasts-and-recordings/"><u>New Top Tools for Silencing Unwanted Sound in Podcasts and Recordings</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-5-best-m4a-audio-editor-softwares-to-edit-your-m4a-filesthese-five-free-audio-editors-that-allow-you-to-edit-your-m4a-files-with-littl/"><u>New 2024 Approved Top 5 Best M4A Audio Editor Softwares to Edit Your M4A Files,these Five Free Audio Editors that Allow You to Edit Your M4A Files with Little to No Trouble</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-behind-the-scenes-manycams-recording-system-evolution/"><u>In 2024, Behind the Scenes  ManyCam's Recording System Evolution</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/x-studio-voice-synthesizer-windows-compatible/"><u>X-Studio Voice Synthesizer, Windows Compatible</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionize-vision-the-best-10-techniques-for-text-effects/"><u>2024 Approved  Revolutionize Vision - The Best 10 Techniques for Text Effects</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-chill-out-the-leading-10-calm-games/"><u>In 2024, Chill Out  The Leading 10 Calm Games</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-optimize-your-channels-an-introduction-to-youtube-statistics/"><u>[New] Optimize Your Channels  An Introduction to YouTube Statistics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-oppo-a18-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Oppo A18 for Streaming | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-amplify-content-reach-essential-strategies-to-skyrocket-views/"><u>[New] 2024 Approved  Amplify Content Reach  Essential Strategies to Skyrocket Views</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-high-def-camera-the-top-audio-mics-guide/"><u>[Updated] High-Def Camera  The Top Audio Mics Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>