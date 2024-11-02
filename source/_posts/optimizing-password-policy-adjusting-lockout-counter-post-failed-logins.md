---
title: "Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
date: 2024-10-27T23:42:54.314Z
updated: 2024-11-01T21:10:19.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
excerpt: "This Article Describes Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
keywords: Password Strength Guidelines,Login Failure Responses,Account Lockout Protocols,Secure Authentication Methods,User Access Management,Enhancing Security Postures,Preventing Brute Force Attacks
thumbnail: https://thmb.techidaily.com/2b0be1d254da9a28eb7fb0462b3c66de235332cf8b2fab4ba3941b84a9d75cac.jpg
---

## Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins

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
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-video-editing-software-showdown-bandicam-vs-camtasia/"><u>[New] In 2024, Video Editing Software Showdown Bandicam vs Camtasia</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-step-by-step-for-apple-podcast-integration/"><u>[Updated] In 2024, Step-by-Step for Apple Podcast Integration</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/a-deep-dive-into-the-amazing-features-of-dells-xps-13-7390-2-in-1-ultrabook-unveiled/"><u>A Deep Dive Into the Amazing Features of Dell's XPS 13 (7390): 2-In-1 Ultrabook Unveiled</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/eliminating-latency-in-chromecast-audio-streams-a-step-by-step-guide/"><u>Eliminating Latency in Chromecast Audio Streams - A Step-by-Step Guide</u></a></li>
<li><a href="https://ai-topics.techidaily.com/how-to-create-funny-talking-avatars-using-oddcast-text-to-speech/"><u>How to Create Funny Talking Avatars Using Oddcast Text to Speech</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-sign-in-snag-onedrive-0x8004dec5-fix-guide-for-windows/"><u>Overcoming the Sign-In Snag: ONEDRIVE 0X8004DEC5 Fix Guide for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/timeliness-triumphant-fixing-chromes-time-on-windows/"><u>Timeliness Triumphant: Fixing Chrome's Time on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-package-registrations-in-windows-os/"><u>Troubleshooting Failed Package Registrations in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-list-of-video-cutting-apps-on-windows-11/"><u>Ultimate List of Video Cutting Apps on Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-fcpx-compression-crash-course-from-basics-to-advanced-for-2024/"><u>Updated FCPX Compression Crash Course From Basics to Advanced for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-store-troubleshooting-tips-for-error-x800704cf/"><u>Windows Store Troubleshooting Tips for Error X800704CF</u></a></li>
</ul></div>

