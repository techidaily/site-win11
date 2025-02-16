---
title: Changing Lockout Duration for Unsuccessful Login Events
date: 2025-02-15T00:32:13.866Z
updated: 2025-02-15T23:19:26.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Lockout Duration for Unsuccessful Login Events
excerpt: This Article Describes Changing Lockout Duration for Unsuccessful Login Events
keywords: Shorten Lockout Times,Reduce Lockouts,Login Failure Policy,Extend Access Delay,Modify Lockout Periods,Adjust Login Cooldown,Change Unsuccessful Logins
thumbnail: https://thmb.techidaily.com/b97d0ebad54511b61b45570cc2aa70ceb4b57e4382ef455cbbee6f6a39f5f377.jpg
---

## Changing Lockout Duration for Unsuccessful Login Events

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-earnings-enigma-the-revenue-of-a-youtuber/"><u>[New] 2024 Approved Earnings Enigma The Revenue of a YouTuber</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-expert-guide-implementing-time-loops-in-obs-for-2024/"><u>[New] Expert Guide Implementing Time Loops in OBS for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-five-expert-tools-for-extracting-fb-content-for-2024/"><u>[Updated] Five Expert Tools for Extracting FB Content for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ghostly-movie-editing-hacks/"><u>[Updated] Ghostly Movie Editing Hacks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-how-to-screen-record-on-lenovo-laptop/"><u>[Updated] In 2024, How to Screen Record on Lenovo Laptop</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-navigating-video-streaming-tools-a-focus-on-zoom-with-youtube/"><u>[Updated] Navigating Video Streaming Tools A Focus on Zoom with YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/escape-the-blues-effective-ways-to-reactivate-an-ailing-keys/"><u>Escape the Blues: Effective Ways to Reactivate an Ailing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-to-windows-11-desktop-widget-integration/"><u>Essential Guide to Windows 11 Desktop Widget Integration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-error-finding-lost-ubisoft-launcher/"><u>Fixing the Error: Finding Lost Ubisoft Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/hyper-v-workflow-building-a-linux-vm-in-windows-os/"><u>Hyper-V Workflow: Building a Linux VM in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-desktop-with-w11-taskbar-tweaks/"><u>Reimagine Your Desktop with W11 Taskbar Tweaks</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-selection-leading-usb-thumb-drives/"><u>Ultimate Selection: Leading USB Thumb Drives</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-handbrake-windows-glitches-quickly/"><u>Unravel HandBrake Windows Glitches Quickly</u></a></li>
</ul></div>

