---
title: Refining Non-Admin Access on Your Windows Machine
date: 2025-02-03T06:30:18.592Z
updated: 2025-02-03T18:40:14.673Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-experts-guide-to-effortless-video-submissions-on-igtv/"><u>[New] In 2024, The Expert's Guide to Effortless Video Submissions on IGTV</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-discovering-prime-frame-rates-for-top-tier-slow-motion-vids/"><u>[Updated] In 2024, Discovering Prime Frame Rates for Top-Tier Slow-Motion Vids</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-ultimate-oculus-rift-game-hits-of-the-season/"><u>[Updated] In 2024, Ultimate Oculus Rift Game Hits of the Season</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-live-action-sims-perfecting-your-videos-for-2024/"><u>[Updated] Live-Action Sims Perfecting Your Videos for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-current-insights-a-benefit-all/"><u>ChatGPT's Current Insights: A Benefit All</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/come-eclissare-il-tuo-hard-disk-con-partizioni-gpt-su-ssd-utilizzando-windows-passi-semplificati-per-windows-111087/"><u>Come Eclissare Il Tuo Hard Disk Con Partizioni GPT Su SSD Utilizzando Windows: Passi Semplificati per Windows 11/10/8/7</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gui-add-folders-to-windows-11s-taskbar/"><u>Elevate Your GUI - Add Folders to Windows 11'S Taskbar</u></a></li>
<li><a href="https://win-tricks.techidaily.com/essential-strategies-boosting-your-dj-sites-visibility-with-top-pcdj-insights/"><u>Essential Strategies: Boosting Your DJ Site's Visibility with Top PCDJ Insights!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-nokia-c210-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Nokia C210 to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-hourly-high-stakes-views-yts-1-to-10-rankings/"><u>In 2024, Hourly High-Stakes Views YT's #1 to #10 Rankings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-type-fixes-for-windows-11s-x80049dd3-error/"><u>Mastering the Art of Type Fixes for Windows 11'S X80049DD3 Error</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-enablingdisabling-regeditor-in-win11/"><u>Methods for Enabling/Disabling RegEditor in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-windows-11s-unwanted-apps-quickly/"><u>Navigate Through Windows 11'S Unwanted Apps Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eradicate-error-80080300-in-windows-team-collaboration/"><u>Steps to Eradicate Error 80080300 in Windows Team Collaboration</u></a></li>
<li><a href="https://win-solutions.techidaily.com/tech-tips-for-smoothing-out-your-minecraft-pc-playtime-latest-fixes/"><u>Tech Tips for Smoothing Out Your Minecraft PC Playtime - Latest Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-identifying-software-settlement-in-windows/"><u>The Art of Identifying Software Settlement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-components-configuration-console-in-windows-explored/"><u>The Components Configuration Console in Windows Explored</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-managing-printers-in-windows-1011/"><u>The Essentials of Managing Printers in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-premier-list-of-windows-video-editors/"><u>The Premier List of Windows Video Editors</u></a></li>
</ul></div>

