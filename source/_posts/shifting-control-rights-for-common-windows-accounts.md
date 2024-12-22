---
title: Shifting Control Rights for Common Windows Accounts
date: 2024-12-19T17:59:13.747Z
updated: 2024-12-22T16:46:28.996Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-apowersoft-picks-top-pc-screen-recorder-reviewed-for-2024/"><u>[New] Apowersoft Picks Top PC Screen Recorder Reviewed for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-assessing-camera-multicam-systems-in-modern-living-spaces/"><u>[Updated] Assessing Camera Multicam Systems in Modern Living Spaces</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-finding-and-following-leading-biz-channels-online/"><u>[Updated] In 2024, Finding and Following Leading Biz Channels Online</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-breaking-down-the-selfie-security-on-insta/"><u>2024 Approved Breaking Down the Selfie Security on Insta</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-samsung-galaxy-s24-ultra-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/echo-dot-vs-homepod-mini-face-off-identifying-critical-contrasts/"><u>Echo Dot Vs. HomePod Mini Face-Off: Identifying Critical Contrasts</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-workflow-top-7-widgets-to-ignite-win-11-performance/"><u>Elevating Your Workflow: Top 7 Widgets to Ignite Win 11 Performance</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/empower-yourself-learning-the-ins-and-outs-of-io-screen-recorder-for-2024/"><u>Empower Yourself Learning the Ins and Outs of IO Screen Recorder for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-work-with-onedrive-files-without-wifi/"><u>How to Work with OneDrive Files Without WiFi</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-modern-design-with-microsoft-paints-fresh-features/"><u>Navigating Modern Design with Microsoft Paint's Fresh Features</u></a></li>
<li><a href="https://win11.techidaily.com/removing-obstacles-in-multi-user-printer-access/"><u>Removing Obstacles in Multi-User Printer Access</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-regaining-control-over-router-webpage/"><u>Strategies for Regaining Control over Router Webpage</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-screen-recording-faceoff-bandicam-versus-camtasiaenas/"><u>The Screen Recording Faceoff Bandicam Versus Camtasia'enas</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-managing-files-without-renaming-directories-on-windows-11/"><u>Top Tips for Managing Files without Renaming Directories on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-router-web-interfaces-in-windows-os/"><u>Unlocking Router Web Interfaces in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-door-entering-and-exiting-terminals-concentrated-state/"><u>Unlocking the Door: Entering & Exiting Terminal's Concentrated State</u></a></li>
</ul></div>

