---
title: Revising Windows Lockout Settings After Failed Login Attempts
date: 2024-12-09T06:31:38.218Z
updated: 2024-12-13T12:37:10.056Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising Windows Lockout Settings After Failed Login Attempts
excerpt: This Article Describes Revising Windows Lockout Settings After Failed Login Attempts
keywords: Windows Password Recovery,Lockout Policy Change,Failed Login Fix,Resetting Access Lockout,System Security Update,Unlocking Windows Error,Prevent Account Lockout
thumbnail: https://thmb.techidaily.com/6038b4e1d0b30613cb41c0ccc8733d5ac9ac78f0122128d3845aaea9056bae9f.jpg
---

## Revising Windows Lockout Settings After Failed Login Attempts

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-a-step-by-step-guide-to-the-top-20-strategies-for-successful-fb-videos-for-2024/"><u>[New] A Step-by-Step Guide to the Top 20 Strategies for Successful FB Videos for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-bring-more-life-to-your-instagram-feed-with-these-4-gif-tips-for-2024/"><u>[New] Bring More Life to Your Instagram Feed with These 4 GIF Tips for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-ae-user-guide-adding-flavor-with-typefaces/"><u>[New] In 2024, AE User Guide Adding Flavor with Typefaces</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-8-best-mirrorless-cameras-vloggers-should-know/"><u>[Updated] 2024 Approved 8 Best Mirrorless Cameras Vloggers Should Know</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-filmmaking-with-ease-decoding-common-video-editing-hurdles-in-filmora/"><u>[Updated] Filmmaking with Ease Decoding Common Video Editing Hurdles in Filmora</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-how-to-record-screen-and-video-on-android-4-methods-for-2024/"><u>[Updated] How to Record Screen and Video on Android? [4 Methods] for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-turning-live-radio-into-a-personal-archive-step-by-step-instructions/"><u>2024 Approved Turning Live Radio Into a Personal Archive Step-by-Step Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-browser-practices-optimal-memorycpu-use-on-three-platforms/"><u>Best Browser Practices: Optimal Memory/CPU Use on Three Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/guide-overcoming-banned-program-error-message-in-pc/"><u>Guide: Overcoming Banned Program Error Message in PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dns-configuration-in-windows-11-for-efficiency/"><u>Mastering DNS Configuration in Windows 11 for Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-homescreen-access/"><u>Mastering Windows 11 Homescreen Access</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-rectifying-loaderror-87-in-windows-applications/"><u>Methods for Rectifying LoadError 87 in WIndows Applications</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-samsung-galaxy-a25-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Samsung Galaxy A25 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-deactivated-volume-copies-error/"><u>Resolving Deactivated Volume Copies Error</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-the-deadly-js-error-a-comprehensive-guide-for-win-11-users/"><u>Resolving the Deadly JS Error: A Comprehensive Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-shutdown-issues-caused-by-suspicious-apps/"><u>Solving Windows Shutdown Issues Caused by Suspicious Apps</u></a></li>
<li><a href="https://win11.techidaily.com/win-screensaver-woes-heres-how-to-reset-them/"><u>Win Screensaver Woes? Here's How to Reset Them</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    