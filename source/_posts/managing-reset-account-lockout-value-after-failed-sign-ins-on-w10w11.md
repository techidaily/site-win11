---
title: Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
date: 2025-01-03T16:29:16.366Z
updated: 2025-01-06T18:27:37.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
excerpt: This Article Describes Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
keywords: Account Lockout Management,Windows 10/11 Login Issues,Reset Password After Fail,Sign-In Troubleshooting,W10 Security Settings,Lockout Policy Adjustment,Failed Sign-In Fixation
thumbnail: https://thmb.techidaily.com/3485122afbd86c9e9c462c3f4114e1a2939bb988f69531afc473f2a12af7b022.jpg
---

## Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-unrecognizable-images-with-picarts-feature/"><u>[New] 2024 Approved Unrecognizable Images with PicArt's Feature</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-unlock-advanced-editing-text-insertion-tips-on-images-in-microsofts-photos/"><u>[New] Unlock Advanced Editing Text Insertion Tips on Images in Microsoft's Photos</u></a></li>
<li><a href="https://win11.techidaily.com/conceal-or-reveal-the-taskbars-time-display/"><u>Conceal or Reveal the Taskbar's Time Display</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-individualized-gpo-settings-a-windows-11-masterclass/"><u>Crafting Individualized GPO Settings: A Windows 11 Masterclass</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-correcting-horizontal-streaks-in-monitor-images/"><u>Diagnosing and Correcting Horizontal Streaks in Monitor Images</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-common-windows-11-issues/"><u>Essential Tips for Common Windows 11 Issues</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-3gp-file-transformation-from-mpeg-online-with-moveavi-tool/"><u>Free 3GP File Transformation From MPEG Online with MoveAVI Tool</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-steam-issues-preventing-game-launch-on-windows-11/"><u>How to Mend Steam Issues Preventing Game Launch on Windows 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-face-fluidity-techniques-implementing-motion-blur-effects/"><u>In 2024, Face Fluidity Techniques Implementing Motion Blur Effects</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-screen-magnification-in-ms-teams/"><u>In 2024, Navigating Screen Magnification in MS Teams</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-win-11-screen-with-symbol-restoration/"><u>Reclaim Your Win 11 Screen with Symbol Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-starter-strategy-for-original-diablo/"><u>The Ultimate Starter Strategy for Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-windows-shared-drive-with-ease/"><u>Unblock Windows Shared Drive with Ease</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlock-the-secrets-6-premier-destinations-for-music-video-enthusiasts/"><u>Unlock the Secrets: 6 Premier Destinations for Music Video Enthusiasts</u></a></li>
<li><a href="https://fox-http.techidaily.com/unveiling-the-process-of-batched-tiktok-content-extraction/"><u>Unveiling the Process of Batched TikTok Content Extraction</u></a></li>
</ul></div>

