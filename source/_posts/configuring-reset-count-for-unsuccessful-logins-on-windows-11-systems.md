---
title: Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
date: 2024-11-23T22:31:15.538Z
updated: 2024-11-28T01:21:28.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
excerpt: This Article Describes Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
keywords: Windows 11 Login Resets,Win11 Unauthorized Access,Increment Failed Login Counts,Enhancing Login Security,Password Lockout Mechanism,Preventing Brute Force Attacks,Managing Failed Logins Windows
thumbnail: https://thmb.techidaily.com/897a54d20c0fe274d0937962de97f84511515ba57539d3344fb75e1f209995c6.png
---

## Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/updated-in-2024-mastering-camtasia-ken-burns-technique-unveiled/"><u>[Updated] In 2024, Mastering Camtasia Ken Burns Technique Unveiled</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-photobooth-playback-hang-up-seeking-solutions/"><u>[Updated] In 2024, Photobooth Playback Hang-Up - Seeking Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-secure-restricted-realm-of-windows-11/"><u>Delving Into the Secure, Restricted Realm of Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-self-assurance-against-virtual-hostility-for-2024/"><u>Fostering Self-Assurance Against Virtual Hostility for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-vivo-v27-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Vivo V27 for Free? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-windows-files-stop-read-only-barrier/"><u>How to Unlock Windows Files: Stop Read-Only Barrier</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-correcting-unsteady-flight-footage-artifacts/"><u>In 2024, Correcting Unsteady Flight Footage Artifacts</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-take-control-of-time-top-10-free-video-speed-manipulation-apps-for-mobile/"><u>New Take Control of Time Top 10 Free Video Speed Manipulation Apps for Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installation-failure-error-0xc004f050/"><u>Overcoming Windows Installation Failure: Error 0XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/transformative-interface-step-by-step-installation-of-themes-from-ms-store/"><u>Transformative Interface: Step-by-Step Installation of Themes From MS Store</u></a></li>
</ul></div>

