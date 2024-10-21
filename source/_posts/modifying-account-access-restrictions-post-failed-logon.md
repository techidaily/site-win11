---
title: Modifying Account Access Restrictions Post-Failed Logon
date: 2024-10-15T16:45:33.339Z
updated: 2024-10-21T05:06:45.909Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Access Restrictions Post-Failed Logon
excerpt: This Article Describes Modifying Account Access Restrictions Post-Failed Logon
keywords: Login Failure Limits,Account Lockout Policy,Unauthorized Access Control,Revise Login Rejections,Manage Failed Login Attempts,Enhance Security Restrictions,Adjust Access Denial Settings
thumbnail: https://thmb.techidaily.com/4c8d9f631d7921c719a1941a590fa8e1cb22a0616837cda48eb590a45fbdddeb.png
---

## Modifying Account Access Restrictions Post-Failed Logon

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-easy-process-how-to-save-twitter-videos-on-an-android-device-for-2024/"><u>[New] Easy Process How to Save Twitter Videos on an Android Device for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-revamping-online-speech-chromebooks-top-5-voice-alteration-tools-revealed/"><u>[New] In 2024, Revamping Online Speech Chromebook's Top 5 Voice Alteration Tools Revealed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-directing-content-flow-uploading-imovie-films-to-youtube/"><u>[Updated] 2024 Approved Directing Content Flow Uploading IMovie Films to YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-1110-nvidia-cp-error-with-ease/"><u>Fixing Windows 11/10 NVIDIA CP Error with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-support-for-emoji-15-on-windows-11/"><u>How to Enable Support for Emoji 15 on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-oppo-reno-11f-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Oppo Reno 11F 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instagrams-best-grids-built-by-the-top-tools-compiled-here/"><u>In 2024, Instagram's Best Grids Built by the Top Tools Compiled Here</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-aggregatorhostexe-purpose-usefulness-and-safety/"><u>Insight Into Windows AggregatorHost.exe: Purpose, Usefulness, and Safety</u></a></li>
<li><a href="https://win11.techidaily.com/installing-virtualbox-on-windows-set-up-the-dependencies-first-for-error-free-installation/"><u>Installing VirtualBox on Windows? Set Up the Dependencies First for Error-Free Installation</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-to-rectify-managed-chromium-and-microsoft-edge-configurations/"><u>Methodology to Rectify Managed Chromium & Microsoft Edge Configurations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-soundtrack-selection-in-unboxing-filmmaking/"><u>Navigating Soundtrack Selection in Unboxing Filmmaking</u></a></li>
<li><a href="https://win11.techidaily.com/switch-to-shadows-making-paint-dark/"><u>Switch to Shadows: Making Paint Dark</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-infinix-note-30-pro-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Infinix Note 30 Pro Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-windows-timer-apps-perfecting-pomodoros/"><u>Top 8 Windows Timer Apps: Perfecting Pomodoros</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-htc-u23-pro-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of HTC U23 Pro on Windows?</u></a></li>
</ul></div>

