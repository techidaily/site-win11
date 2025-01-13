---
title: Refining Non-Admin Access on Your Windows Machine
date: 2025-01-09T05:33:26.401Z
updated: 2025-01-12T20:41:58.566Z
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

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-of-hdr-photo-on-iphone-camera/"><u>[New] The Ultimate Guide of HDR Photo on iPhone Camera</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-premiers-top-12-gps-enhanced-surveillance-cameras/"><u>[Updated] 2024 Approved Premier's Top 12 GPS-Enhanced Surveillance Cameras</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-usb-c-vision-the-new-standard-in-monitors-hp-envy-27/"><u>[Updated] 2024 Approved USB-C Vision The New Standard in Monitors - HP Envy 27</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-top-10-best-add-ons-to-boost-your-gopro/"><u>[Updated] In 2024, Top 10 Best Add-Ons to Boost Your GoPro</u></a></li>
<li><a href="https://win11.techidaily.com/disable-microsofts-assistant-service-on-pc/"><u>Disable Microsoft's Assistant Service on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-144hz-ultrawide-displays-for-immersive-games/"><u>Elite 144Hz Ultrawide Displays for Immersive Games</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/google-stadia-reviewed-key-aspects-requiring-developmental-progress/"><u>Google Stadia Reviewed - Key Aspects Requiring Developmental Progress</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-resource-monitoring-ram-cpu-and-gpu-data-in-windows-11/"><u>Mastering Resource Monitoring: RAM, CPU & GPU Data in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-sound-dynamics-fixing-low-volume-woes/"><u>Maximizing Sound Dynamics: Fixing Low-Volume Woes</u></a></li>
<li><a href="https://win11.techidaily.com/pocket-sized-windows-patches-offline-methods/"><u>Pocket-Sized Windows Patches: Offline Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-continuous-restarting-on-windows-11/"><u>Quick Solutions for Continuous Restarting on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-troubleshooting-for-rdp-internal-error-on-windows-11/"><u>Streamlining Troubleshooting for RDP Internal Error on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-the-future-of-customer-relationships-on-facebooks-newsfeed/"><u>Unveiling the Future of Customer Relationships on Facebook's Newsfeed</u></a></li>
</ul></div>

