---
title: Shifting Control Rights for Common Windows Accounts
date: 2025-01-18T06:18:34.082Z
updated: 2025-01-25T07:55:11.535Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shifting Control Rights for Common Windows Accounts
excerpt: This Article Describes Shifting Control Rights for Common Windows Accounts
keywords: Window User Rights Change,Access Shift in Windows,Windows Account Privileges,Rights Transfer Windows Users,Altering Account Permissions,Modify User Controls Windows,Transitioning Windows Authority
thumbnail: https://thmb.techidaily.com/1b4d426689bd18514a96cb95968cc5a755b1ea7a22bc00e9feef5b8e8bfa78d1.jpg
---

## Shifting Control Rights for Common Windows Accounts

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/ed-guerrilla-mic-guide-top-chip-selection-on-a-shoestring-for-2024/"><u>[Updated] Guerrilla Mic Guide Top Chip Selection on a Shoestring for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-the-ultimate-showdown-of-projectors-and-tvs-in-a-4k-setting/"><u>[Updated] The Ultimate Showdown of Projectors & TVs in a 4K Setting</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-video-capturing-essentials-top-8-apps-for-windows-users-for-2024/"><u>[Updated] Video Capturing Essentials Top 8 Apps for Windows Users for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-mastering-pc-games-screenshots-top-6-methods/"><u>2024 Approved Mastering PC Games Screenshots Top 6 Methods</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accelerate-creativity-in-photo-editing-using-pixlr/"><u>Accelerate Creativity in Photo Editing Using Pixlr</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-from-apple-iphone-11-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 From Apple iPhone 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-12-prominent-vivo-t2-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Vivo T2 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/losungsansatze-fur-die-fehlfunktion-der-vorlagen-signatur-in-microsoft-outlook/"><u>Lösungsansätze Für Die Fehlfunktion Der Vorlagen-Signatur in Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cmd-prompt-lack-of-admin-privileges/"><u>Resolving Cmd Prompt Lack of Admin Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-and-using-microsofts-code-assistant/"><u>Step-by-Step: Setting Up and Using Microsoft's Code Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/transform-workflow-efficiency-mastering-flow-launcher-basics/"><u>Transform Workflow Efficiency: Mastering Flow Launcher Basics</u></a></li>
</ul></div>

