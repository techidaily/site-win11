---
title: Changing the Time Before Next Login Attempt on Failure
date: 2025-02-08T17:33:01.364Z
updated: 2025-02-15T20:07:07.978Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing the Time Before Next Login Attempt on Failure
excerpt: This Article Describes Changing the Time Before Next Login Attempt on Failure
keywords: Login Time Change On Fail,Adjusting Login Delay,Prevent Repeated Logins,Login Retry Timer Modify,Post-Login Attempt Time,Alter Next Login Time,Increase Login Try Period
thumbnail: https://thmb.techidaily.com/f09a424aa99c62f7b51db30e0d97dc33c8611de88afaf819d747680f631cd289.jpg
---

## Changing the Time Before Next Login Attempt on Failure

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/new-key-strategies-for-navigating-complex-youtube-discussions-for-2024/"><u>[New] Key Strategies for Navigating Complex YouTube Discussions for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-ig-tunes-crafting-perfect-music-posts/"><u>[Updated] In 2024, IG Tunes Crafting Perfect Music Posts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-tech-driven-pleasure-exploring-vr-in-media/"><u>[Updated] In 2024, Tech-Driven Pleasure Exploring VR in Media</u></a></li>
<li><a href="https://win11.techidaily.com/command-your-files-mastering-autohandling-on-w11/"><u>Command Your Files: Mastering Autohandling on W11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-themes-in-windows-terminal/"><u>Crafting Unique Themes in Windows Terminal</u></a></li>
<li><a href="https://buynow-help.techidaily.com/critical-assessment-unveiling-the-strengths-and-weaknesses-of-pioneer-bdr-xd05b-blu-ray-burner-design/"><u>Critical Assessment: Unveiling the Strengths & Weaknesses of Pioneer BDR-XD05B Blu-Ray Burner Design</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/film-lovers-ultimate-selection-of-stop-motion-works-for-2024/"><u>Film Lovers' Ultimate Selection of Stop-Motion Works for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-simple-guide-to-hosting-efficient-zoom-chats/"><u>In 2024, The Simple Guide to Hosting Efficient Zoom Chats</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-who-wins-samsung-or-lgs-ultra-wide-cams/"><u>In 2024, Who Wins? Samsung or LG's Ultra-Wide Cams</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-audio-in-windows-os/"><u>Overcoming Unresponsive Audio in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-generating-windows-11-shortcuts-for-microsoft-store-apps/"><u>Quick Guide: Generating Windows 11 Shortcuts for Microsoft Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-systems-highlighting-7-essential-windows-processes/"><u>Safeguarding Systems: Highlighting 7 Essential Windows Processes</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-time-management-on-pc-choose-from-these-best-apps-to-create-dynamic-clock-screensavers/"><u>Streamline Time Management on PC: Choose From These Best Apps to Create Dynamic Clock Screensavers</u></a></li>
</ul></div>

