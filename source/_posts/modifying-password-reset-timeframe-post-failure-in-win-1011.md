---
title: Modifying Password Reset Timeframe Post-Failure in Win 10/11
date: 2024-12-03T07:42:40.274Z
updated: 2024-12-07T01:18:04.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Password Reset Timeframe Post-Failure in Win 10/11
excerpt: This Article Describes Modifying Password Reset Timeframe Post-Failure in Win 10/11
keywords: Windows Password Reset,Delayed PassReset Time,PC Security Change,OS Update Failure Fix,Windows Login Adjustment,System Access Retry Period,Secure Credential Modification
thumbnail: https://thmb.techidaily.com/50a0e21454dc02c593e958f3f8488f7e3d42941b95d888cc2e5f79586c9b13d4.jpg
---

## Modifying Password Reset Timeframe Post-Failure in Win 10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/ed-crafting-success-with-these-15-youtube-introduction-plans-for-2024/"><u>[Updated] Crafting Success with These 15 YouTube Introduction Plans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effortlessly-update-surface-pcs-internal-settings/"><u>How-To: Effortlessly Update Surface PC's Internal Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-infinix-smart-7-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Infinix Smart 7 Device</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-top-online-tips-creating-title-magic/"><u>In 2024, Top Online Tips Creating Title Magic</u></a></li>
<li><a href="https://some-skills.techidaily.com/lightning-fast-retrieval-of-vanished-reddit-discussions-for-2024/"><u>Lightning-Fast Retrieval of Vanished Reddit Discussions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-release-a-locked-app-on-windows-pc/"><u>Methods to Release a Locked App on Windows PC</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/review-of-the-newly-launched-google-tv-enabled-chromecast-rethinking-home-entertainment/"><u>Review of the Newly Launched Google TV-Enabled Chromecast: Rethinking Home Entertainment</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-0x800713f-email-issue-on-windows-11/"><u>Troubleshooting 0X800713F Email Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-full-ram-capacity-on-windows-systems/"><u>Unleashing Full RAM Capacity on Windows Systems</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/various-methods-to-transfer-pictures-from-apple-iphone-6s-plus-to-pc-drfone-by-drfone-transfer-from-ios/"><u>Various Methods to Transfer Pictures from Apple iPhone 6s Plus to PC | Dr.fone</u></a></li>
</ul></div>

