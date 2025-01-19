---
title: "Securing Your Login: Adjusting the Reset Lockout Frequency Post-Attempts, Win 11 Edition"
date: 2025-01-16T20:18:30.292Z
updated: 2025-01-18T20:24:18.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Securing Your Login: Adjusting the Reset Lockout Frequency Post-Attempts, Win 11 Edition"
excerpt: "This Article Describes Securing Your Login: Adjusting the Reset Lockout Frequency Post-Attempts, Win 11 Edition"
keywords: Win 11 Login Security,Password Reset Limit,Account Lockout Adjustment,Safe Login Frequency,Secure Login Settings,Prevent Brute Force,Post-Attempts Safeguard
thumbnail: https://thmb.techidaily.com/3fc14c15f73df5f4c8b19f8291c51668294576df82a5964da7eda1f1831694f2.jpg
---

## Securing Your Login: Adjusting the Reset Lockout Frequency Post-Attempts, Win 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-vivo-v30-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-browsing-on-new-systems/"><u>Essential Steps for Browsing on New Systems</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-laptops-for-tech-enthusiasts/"><u>Essential Windows Laptops for Tech Enthusiasts</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-vivo-v30-pro-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Vivo V30 Pro Without PUK Codes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-samsung-galaxy-a25-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Samsung Galaxy A25 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pinnacle-of-performance-new-samsung-bdplus-review/"><u>In 2024, Pinnacle of Performance - New Samsung BD+ Review</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-which-is-the-best-fake-gps-joystick-app-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, Which is the Best Fake GPS Joystick App On Samsung Galaxy S24+? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/iwara/"><u>Iwaraコンテンツをダウンロード保存するための詳細な手順: 最強の方法</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-correction-guide-for-windows-error-x800704cf/"><u>Microsoft Store Correction Guide for Windows Error X800704CF</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/next-level-interaction-how-apples-cutting-edge-artificial-intelligence-can-decipher-your-desktop-and-empower-siri-for-superior-assistance/"><u>Next Level Interaction: How Apple's Cutting-Edge Artificial Intelligence Can Decipher Your Desktop and Empower Siri for Superior Assistance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-printer-driver-not-found-error-in-windows-computers-a-step-by-step-guide/"><u>Resolving 'Printer Driver Not Found' Error in Windows Computers - A Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-error-code-0x80070091-directories-not-empty-issue-on-windows-11/"><u>Unblocking Error Code: 0X80070091 Directories Not Empty Issue on Windows 11</u></a></li>
</ul></div>

