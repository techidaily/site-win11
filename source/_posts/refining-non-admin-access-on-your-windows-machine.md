---
title: Refining Non-Admin Access on Your Windows Machine
date: 2025-01-11T17:30:42.590Z
updated: 2025-01-18T22:41:10.407Z
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

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-maximizing-social-reach-with-tiktok-to-facebook-integration/"><u>[New] In 2024, Maximizing Social Reach with TikTok to Facebook Integration</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtube-tunes-heres-how-to-download-safely-and-free/"><u>[Updated] Youtube Tunes? Here's How to Download Safely & Free</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-your-iphone-experience-by-merging-ai-talents-of-chatgpt-and-siri/"><u>Boost Your iPhone Experience by Merging AI Talents of ChatGPT and Siri</u></a></li>
<li><a href="https://data-recovery.techidaily.com/1720600668019-bring-back-your-files-faster-than-ever-with-us/"><u>Bring Back Your Files Faster than Ever with Us</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-defense-integrating-firewall-filters-via-context-menu/"><u>Enhancing Windows 11 Defense: Integrating Firewall Filters via Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-reactivating-windows-update-features/"><u>Fast Track to Reactivating Windows Update Features</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-stop-halo-infinity-from-skipping-frames-and-freezing-up/"><u>How to Stop Halo Infinity From Skipping Frames and Freezing Up</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-ultimate-techniques-for-youtube-video-format-switching/"><u>In 2024, Ultimate Techniques for YouTube Video Format Switching</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-spatial-sound-in-windows-11/"><u>Mastering Spatial Sound in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/oculus-quest-gets-its-first-ever-language-app-mondlyback-buttonfilter-button/"><u>Oculus Quest Gets Its First-Ever Language App: MondlyBack ButtonFilter Button</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-internet-connection-via-vpn/"><u>Overcoming No Internet Connection via VPN</u></a></li>
<li><a href="https://win11.techidaily.com/power-on-performance-dispel-windows-11-sluggishness-quickly/"><u>Power on Performance: Dispel Windows 11 Sluggishness Quickly</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/prepise-mp4-do-gif-sestupne-a-kliknutelny-movavi-konverzer-na-internetu/"><u>Přepíše MP4 Do GIF Sestupně a Kliknutelný: Movavi Konverzér Na Internetu</u></a></li>
<li><a href="https://win-amazing.techidaily.com/resolving-problems-with-the-realtek-rtl8811au-network-adapter-drivers/"><u>Resolving Problems with the Realtek RTL8811AU Network Adapter Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-power-best-windows-apps-for-elevating-your-productivity-game/"><u>Unleash Power: Best Windows Apps for Elevating Your Productivity Game</u></a></li>
</ul></div>

