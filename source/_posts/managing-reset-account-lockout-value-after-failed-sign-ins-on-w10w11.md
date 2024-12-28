---
title: Managing Reset Account Lockout Value After Failed Sign-Ins on W10/W11
date: 2024-12-22T06:58:02.190Z
updated: 2024-12-28T05:48:25.694Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

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
<li><a href="https://article-helps.techidaily.com/new-in-2024-accelerate-access-funimates-download-demystified/"><u>[New] In 2024, Accelerate Access Funimate's Download Demystified</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-elevate-your-youtube-presence-with-masterful-editing-skills/"><u>[Updated] 2024 Approved Elevate Your YouTube Presence with Masterful Editing Skills</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-prime-selections-of-maximum-digital-safekeeping/"><u>[Updated] Prime Selections of Maximum Digital Safekeeping</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-cortana-in-windows-with-vivetool/"><u>Empowering Cortana in Windows with ViveTool</u></a></li>
<li><a href="https://win11.techidaily.com/identify-screenshot-storage-in-windows/"><u>Identify Screenshot Storage in Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/maximizing-performance-with-akasa-gecko-heatsink-expert-analysis-and-reviews-for-ssd-airflow-optimization/"><u>Maximizing Performance with Akasa Gecko Heatsink - Expert Analysis and Reviews for SSD Airflow Optimization</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/um-film-experiences-yts-best-of-lists/"><u>Premium Film Experiences YT's Best Of Lists</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-keyboard-errors-windows-11s-function-keys/"><u>Rectify: Keyboard Errors - Windows 11'S Function Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-bargain-alert-lifetime-win10-starting-at-612/"><u>Top Bargain Alert: Lifetime Win10, Starting at $6.12</u></a></li>
</ul></div>

