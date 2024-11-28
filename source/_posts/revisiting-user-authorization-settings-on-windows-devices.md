---
title: Revisiting User Authorization Settings on Windows Devices
date: 2024-11-20T17:28:05.120Z
updated: 2024-11-28T02:35:23.302Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revisiting User Authorization Settings on Windows Devices
excerpt: This Article Describes Revisiting User Authorization Settings on Windows Devices
keywords: User Auth Windows,Device Permissions,Windows Security,Credential Controls,Access Management,System Privileges,Authorization Settings
thumbnail: https://thmb.techidaily.com/afcb9c2878394644f41c39d4475ac640d665c752413696b921520d8ad80368e6.jpg
---

## Revisiting User Authorization Settings on Windows Devices

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-masterful-phone-apps-altering-speech-patterns/"><u>[New] 2024 Approved Masterful Phone Apps Altering Speech Patterns</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exceptional-aspects-of-inexpensive-asmr-microphones/"><u>[New] Exceptional Aspects of Inexpensive ASMR Microphones</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-audiovisual-alchemy-formulating-your-youtube-playlist/"><u>[Updated] Audiovisual Alchemy Formulating Your YouTube Playlist</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-rewind-to-save-incorporating-80s-vhs-in-todays-cinematic-edits/"><u>2024 Approved From Rewind to Save Incorporating 80S VHS in Today's Cinematic Edits</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/gain-immediate-control-overcoming-pin-locking/"><u>Gain Immediate Control: Overcoming PIN Locking</u></a></li>
<li><a href="https://win11.techidaily.com/get-personalized-chatbot-experience-local-clone-for-windows-at-no-cost/"><u>Get Personalized ChatBot Experience: Local Clone for Windows at No Cost.</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-fix-street-fighter-e6s-pc-stability-issues-a-comprehensive-guide/"><u>How to Fix Street Fighter E6's PC Stability Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-honor-90-pros-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Honor 90 Pros Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-generative-design-top-5-no-cost-open-source-ai-imaging-software-choices/"><u>Mastering Generative Design: Top 5 No-Cost, Open Source AI Imaging Software Choices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-unknown-issue-in-windows-setups/"><u>Navigating the 'Unknown' Issue in Windows Setups</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unspecified-obs-error-in-live-streaming-windows-11/"><u>Preventing Unspecified OBS Error in Live Streaming Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-missing-notification-issues-in-phone-link-app/"><u>Resolving Windows: Missing Notification Issues in Phone Link App</u></a></li>
<li><a href="https://win-howtos.techidaily.com/safari-cannot-open-the-page-easy-fix/"><u>Safari Cannot Open the Page [Easy Fix]</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-windows-11s-upgrade-issue-error-0x800f0922/"><u>Strategies for Fixing Windows 11'S Upgrade Issue: Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/the-age-indicator-for-your-laptop-or-desktop-system/"><u>The Age Indicator for Your Laptop or Desktop System</u></a></li>
</ul></div>

