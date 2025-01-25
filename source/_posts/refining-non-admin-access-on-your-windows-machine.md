---
title: Refining Non-Admin Access on Your Windows Machine
date: 2025-01-20T08:29:12.200Z
updated: 2025-01-25T06:57:38.711Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Refining Non-Admin Access on Your Windows Machine
excerpt: This Article Describes Refining Non-Admin Access on Your Windows Machine
keywords: Admin Restrictions,Windows Security,Limited User Accounts,Secure PC Management,Privacy Settings,Safe Windows Environment,Controlled Access Windows
thumbnail: https://thmb.techidaily.com/b419546ab6fdd218d829eb22a844376fcf0d2afcf21c79595fda949de5f6b103.jpg
---

## Refining Non-Admin Access on Your Windows Machine

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-complete-process-of-scheduling-google-meets/"><u>[New] In 2024, The Complete Process of Scheduling Google Meets</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-how-to-choose-between-filmora-and-democreator/"><u>[Updated] 2024 Approved How to Choose Between Filmora and Democreator</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/boost-productivity-in-resin-3d-printing-discover-the-elegoo-solution-kit-for-only-149/"><u>Boost Productivity in Resin 3D Printing: Discover the Elegoo Solution Kit for Only $149</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-ai-driven-tools-on-microsofts-platform/"><u>Discovering AI-Driven Tools on Microsoft's Platform</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-tips-for-diagnosing-and-correcting-wireless-adapteraccess-point-malfunctions-in-10-steps/"><u>Expert Tips for Diagnosing and Correcting Wireless Adapter/Access Point Malfunctions in 10 Steps</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-vivo-s17-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Vivo S17 Devices | Dr.fone</u></a></li>
<li><a href="https://fox-zero.techidaily.com/how-can-you-swiftly-identify-required-flipbuilder-button-configurations/"><u>How Can You Swiftly Identify Required FlipBuilder Button Configurations?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/list-of-8-youtube-outlets-skyrocketing-in-viewership/"><u>List of 8 YouTube Outlets Skyrocketing in Viewership</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-adjusting-admin-settings-on-windows-11/"><u>Master the Art of Adjusting Admin Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reestablish-uninterrupted-gameplay-in-gaming-environment/"><u>Reestablish Uninterrupted Gameplay in Gaming Environment</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-code-0xa00f4243-for-multiple-camera-usage/"><u>Sidestepping Error Code: 0XA00F4243 for Multiple Camera Usage</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unblocked-files-via-powershell-on-pc/"><u>Simplifying Unblocked Files via PowerShell on PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-instructions-for-implementing-gpt-nput-text-with-python/"><u>Step-by-Step Instructions for Implementing GPT-Nput Text with Python</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-hidden-net-identity-errors-windows/"><u>Tackling Hidden Net Identity Errors Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-shield-of-anonymity-network-file-security-on-windows/"><u>The Shield of Anonymity: Network File Security on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-vintage-pc-a-step-by-step-guide-to-windows-11-to-go-and-rufus/"><u>Transform Your Vintage PC: A Step-by-Step Guide to Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Samsung Galaxy A24? | Dr.fone</u></a></li>
</ul></div>

