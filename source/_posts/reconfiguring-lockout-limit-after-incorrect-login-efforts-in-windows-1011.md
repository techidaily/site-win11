---
title: Reconfiguring Lockout Limit After Incorrect Login Efforts in Windows 10/11
date: 2024-12-02T01:18:38.095Z
updated: 2024-12-06T17:50:42.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconfiguring Lockout Limit After Incorrect Login Efforts in Windows 10/11
excerpt: This Article Describes Reconfiguring Lockout Limit After Incorrect Login Efforts in Windows 10/11
keywords: WinLockoutReset Guide,Correcting Logins Error,Adjusting Lockout Settings,Limit Reconfiguration Tips,Windows Login Failures,Reducing Account Locks,Efficient Password Strategies
thumbnail: https://thmb.techidaily.com/141f2083ce8f9807f7858bc78fabb4787ff1855b350de1df5ec61d6fc21bf535.jpg
---

## Reconfiguring Lockout Limit After Incorrect Login Efforts in Windows 10/11

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
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-enhancing-online-presence-obs-and-facebook-synergy/"><u>[New] 2024 Approved Enhancing Online Presence OBS & Facebook Synergy</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-unleashing-creativity-in-micro-videography-and-photography/"><u>[New] In 2024, Unleashing Creativity in Micro Videography and Photography</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-revisiting-the-golden-age-of-cinema-video-tutorials/"><u>[New] Revisiting the Golden Age of Cinema Video Tutorials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-fix-facebook-suggested-videos-not-showing-up-for-2024/"><u>[Updated] How to Fix Facebook Suggested Videos Not Showing Up for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-selection-best-5-free-convertors-for-video-from-gifs/"><u>2024 Approved Exclusive Selection Best 5 Free Convertors for Video From GIFs</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-errors-in-windows-media-playback/"><u>Correcting Errors in Windows Media Playback</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/directive-approach-to-prevent-fake-outputs-in-machine-learning/"><u>Directive Approach to Prevent Fake Outputs in Machine Learning</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-erase-google-chromes-default-webp-saving-on-your-pc/"><u>How to Erase Google Chrome's Default WebP Saving on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-try-connecting-your-device-bluetooth-pairing-error-in-windows-11-and-11/"><u>How to Fix the “Try Connecting Your Device” Bluetooth Pairing Error in Windows 11 & 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/instantly-post-photosvideos-to-twitter-skipping-retweets/"><u>Instantly Post Photos/Videos to Twitter, Skipping Retweets</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-google-pixel-fold-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Google Pixel Fold Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-notepad-on-windows-quick-fixes-guide/"><u>Reviving Your Notepad on Windows: Quick Fixes Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-updates/"><u>Unlock the Power of Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-canary-an-easy-guide-for-users/"><u>Unlocking Windows Canary: An Easy Guide for Users</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-to-fixing-error-code-0x80040610-in-windows/"><u>Unveiling the Secrets to Fixing Error Code 0X80040610 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-ways-to-address-exit-code-1-wow/"><u>Win-Friendly Ways to Address Exit Code: 1 WoW</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    