---
title: Modifying Account Access Restrictions Post-Failed Logon
date: 2024-09-12T17:11:32.531Z
updated: 2024-09-16T23:46:10.426Z
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-tips.techidaily.com/updated-transcribe-speech-absolutely-gratis/"><u>[Updated] Transcribe Speech, Absolutely Gratis</u></a></li>
<li><a href="https://win11.techidaily.com/best-10-free-video-segmenters-how-to-easily-cut-and-slice-movies-without-cost/"><u>Best 10 FREE Video Segmenters: How to Easily Cut and Slice Movies Without Cost</u></a></li>
<li><a href="https://win11.techidaily.com/best-7-no-cost-audio-equalizers-and-levelers-for-windows-10-users/"><u>Best 7 No-Cost Audio Equalizers & Levelers for Windows 10 Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-engaging-youtube-videos-using-finalcut-pro-expertise-for-2024/"><u>Crafting Engaging YouTube Videos Using FinalCut Pro Expertise for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ultimate-selection-of-5-acapella-sites-for-free-tunes-perfect-for-dj-playlists/"><u>Discover the Ultimate Selection of 5 Acapella Sites for Free Tunes Perfect for DJ Playlists</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-to-setting-up-the-ultimate-loonatics/"><u>Easy Guide to Setting Up the Ultimate LooNatics</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-setting-up-your-vizio-tv-for-optimal-usb-movie-playback-performance/"><u>Easy Guide: Setting Up Your Vizio TV For Optimal USB Movie Playback Performance</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-optimize-your-pcps4-settings-stop-assassins-creed-syndicate-from-crashing/"><u>How to Optimize Your PC/PS4 Settings: Stop Assassin's Creed Syndicate From Crashing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-oneplus-ace-2-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from OnePlus Ace 2 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/secrets-to-excellent-1080p-content-on-fb-for-2024/"><u>Secrets to Excellent 1080P Content on FB for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/voyage-to-greatness-youtubes-best-travel-vids-for-2024/"><u>Voyage to Greatness YouTube's Best Travel Vids for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

