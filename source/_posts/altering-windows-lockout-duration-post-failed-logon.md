---
title: Altering Windows Lockout Duration Post-Failed Logon
date: 2024-06-25T11:42:31.313Z
updated: 2024-06-26T11:42:31.313Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Lockout Duration Post-Failed Logon
excerpt: This Article Describes Altering Windows Lockout Duration Post-Failed Logon
keywords: Windows Login Delay,Account Unlock Time,Failed Logon Limit,Password Reset Period,Security Lockout Fix,Access Control Adjustment,Lockout Duration Change
thumbnail: https://thmb.techidaily.com/bcbbbb17c516407e41023c9df84564d9e208249f4419e84badf29d91094b0794.jpg
---

## Altering Windows Lockout Duration Post-Failed Logon

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

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

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-windows-11-performance-with-these-adjustments/"><u>Achieve Peak Windows 11 Performance with These Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/cease-alerts-for-unrequested-system-recommendations/"><u>Cease Alerts for Unrequested System Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-cryptographic-solutions-ranked-148-chars/"><u>Window's Best Cryptographic Solutions Ranked (148 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-chatgpt-is-at-capacity-right-now-error-on-windows/"><u>How to Fix the ChatGPT Is at Capacity Right Now Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-convert-facebook-videos-to-mp3-top-online-converters-for-2024/"><u>New Convert Facebook Videos to MP3 Top Online Converters for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-discover-the-best-4k-capture-software-for-live-recording-for-2024/"><u>[New] Discover the Best 4K Capture Software for Live Recording for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-festive-soundtrack-mix-for-a-special-commemorative-film/"><u>New In 2024, Festive Soundtrack Mix for a Special Commemorative Film</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-a05-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy A05 Phone Hassle-Free</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-checklist-for-post-editing-and-uploading-your-360-vids-on-youtube/"><u>2024 Approved  The Ultimate Checklist for Post-Editing & Uploading Your 360 Vids on YouTube</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-silent-the-screen-how-to-strip-audio-from-your-movies-in-imovie/"><u>Updated 2024 Approved Silent the Screen How to Strip Audio From Your Movies in iMovie</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-samsung-galaxy-m54-5g-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Samsung Galaxy M54 5G Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On OnePlus Nord N30 5G? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>