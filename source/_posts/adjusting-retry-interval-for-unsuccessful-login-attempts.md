---
title: Adjusting Retry Interval for Unsuccessful Login Attempts
date: 2024-06-25T11:24:38.139Z
updated: 2024-06-26T11:24:38.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
excerpt: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
keywords: Login Retry Adjustment,Unsuccessful Login Handling,Increase Login Retries,Manage Failed Logins,Login Attempt Limits,Optimize Login Intervals,Success Rate for Login Attempts
thumbnail: https://thmb.techidaily.com/4ac54b51c1cafa3a284440c31d27701c82afd968d6a73268fe3b019a529c7811.jpg
---

## Adjusting Retry Interval for Unsuccessful Login Attempts

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
<li><a href="https://win11.techidaily.com/elevate-editing-the-win11-list-of-premier-video-scripts/"><u>Elevate Editing: The Win11 List of Premier Video Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-invisible-images-with-encrypted-zips-win/"><u>Mastering the Art of Invisible Images with Encrypted Zips (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-google-play-on-w11-os/"><u>Guide: Setting Up Google Play on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/1719296331398-fixes-for-inadequate-screen-shots-in-windows-snip-and-sketch-app/"><u>Fixes for Inadequate Screen Shots in Windows’ Snip & Sketch App.</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ntfs-enablingdisabling-file-compression/"><u>Mastering NTFS: Enabling/Disabling File Compression</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-art-of-digital-library-step-by-step-guide-for-your-youtube-saved-playlist/"><u>[New] The Art of Digital Library  Step-by-Step Guide for Your YouTube Saved Playlist</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/invest-in-success-unveiling-the-highest-earning-posts/"><u>Invest in Success  Unveiling the Highest Earning Posts</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/spotlight-on-15-books-loved-and-shown-by-booktok-creators/"><u>Spotlight on 15 Books Loved and Shown by BookTok Creators</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-blur-your-video-for-free-no-software-required/"><u>Updated In 2024, Blur Your Video for Free No Software Required</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlock-the-power-of-speech-recognition-for-effective-office-documentation-in-microsoft-word/"><u>[Updated] Unlock the Power of Speech Recognition for Effective Office Documentation in Microsoft Word</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/converting-graphics-to-iconic-messages-a-complete-tutorial-for-chat-apps-for-2024/"><u>Converting Graphics to Iconic Messages  A Complete Tutorial for Chat Apps for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-iphone-se-2022-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your iPhone SE (2022) Apple ID and Apple Pay</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-unearthing-unique-content-for-youtubes-spotlight/"><u>[Updated] 2024 Approved  Unearthing Unique Content for Youtube's Spotlight</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>