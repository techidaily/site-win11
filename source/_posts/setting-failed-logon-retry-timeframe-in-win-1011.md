---
title: Setting Failed Logon Retry Timeframe in Win 10/11
date: 2024-06-25T11:22:05.263Z
updated: 2024-06-26T11:22:05.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
excerpt: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
keywords: Win 10 Login Recovery,Windows 10 Reset Attempts,Manage Logon Retries,Reconfigure Login Delays (Win10/11),Windows Timeout for Failed Logins,Setting Login Retry Interval (Win10),Adjusting Login Retries (Windows 10)
thumbnail: https://thmb.techidaily.com/128652f3635b5c02571aebd32ea42bdf5de3d8228fe08a4a4993ce8bcc5b8b84.png
---

## Setting Failed Logon Retry Timeframe in Win 10/11

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
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-overcoming-the-msvcr120dll-deficiency-issue/"><u>Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-pristine-windows-image-display/"><u>Mastering the Art of Pristine Windows Image Display</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-use-windows-11s-home-space/"><u>How to Access and Use Windows 11'S Home Space</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pcs-powertoys-10-essential-tips/"><u>Mastering Windows PCs: PowerToys' 10 Essential Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-immersive-surround-sound-incorporating-atmos-into-win-1011/"><u>Achieve Immersive Surround Sound: Incorporating Atmos Into Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-losses-commit-to-daily-windows-data-archiving/"><u>Avoid Losses: Commit to Daily Windows Data Archiving</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-comprehensive-guide-to-mastering-ipogo-for-pokemon-go-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, A Comprehensive Guide to Mastering iPogo for Pokémon GO On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-exclusive-list-of-top-digital-tutorial-providers-sans-udemy/"><u>[New] Exclusive List of Top Digital Tutorial Providers Sans Udemy</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-supercharge-your-games-premium-top-10-drives/"><u>[New] Supercharge Your Games  Premium Top 10 Drives</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-is-your-apple-iphone-se-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone SE in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-perfect-shadows-and-highlights-with-iphone-lighting-tips/"><u>[Updated] 2024 Approved  Perfect Shadows & Highlights with IPhone Lighting Tips</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-networking-on-linkedin/"><u>Navigating Networking on LinkedIn</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-infinix-note-30-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Infinix Note 30 5G Activity | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-infinix-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Infinix</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-around-the-clock-vision-versus-multiplanar-exposures/"><u>In 2024, Around-the-Clock Vision Versus Multiplanar Exposures</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-beyond-ustream-an-examination-of-video-streaming/"><u>[Updated] In 2024, Beyond Ustream  An Examination of Video Streaming</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>