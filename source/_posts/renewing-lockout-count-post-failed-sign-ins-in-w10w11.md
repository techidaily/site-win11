---
title: Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
date: 2024-06-25T10:18:20.605Z
updated: 2024-06-26T10:18:20.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
excerpt: This Article Describes Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
keywords: Failed Login Recovery,Password Reset Process,Lockout Event Management,W10/W11 Access Troubleshooting,Sign-In Failure Resolution,Post-Login Lockout Strategy,Windows 10/11 Security Keying
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Renewing Lockout Count Post-Failed Sign-Ins in W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

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

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/top-5plus-windows-1011-productivity-boosters-for-maximum-output/"><u>Top 5+ Windows 10/11 Productivity Boosters for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-why-windows-fails-to-execute-exe-files/"><u>Decoding Why Windows Fails to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-sudden-invisibility-issues-in-pc-gaming/"><u>Eradicating Sudden Invisibility Issues in PC Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-intel-network-adapters-on-pcs/"><u>Step-by-Step: Setting Up Intel Network Adapters on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-num-caps-and-scroll-lock-key-indicators-to-windows-11s-system-tray/"><u>How to Add Num, Caps, and Scroll Lock Key Indicators to Windows 11’S System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/from-easy-access-to-higher-security-transitioning-your-logon-method-on-windows-11/"><u>From Easy Access to Higher Security: Transitioning Your Logon Method on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hps-visionary-color-display-dissecting-the-z32x-monitor-for-2024/"><u>HP’s Visionary Color Display  Dissecting the Z32X Monitor for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-fcpx-skin-enhancement-a-beginners-guide-to-airbrushed-results/"><u>In 2024, FCPX Skin Enhancement A Beginners Guide to Airbrushed Results</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-boost-iphone-visual-quality-selective-photo-and-video-tools/"><u>[New] Boost iPhone Visual Quality  Selective Photo and Video Tools</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-honor-90-lite-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Honor 90 Lite to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-find-out-the-best-8-youtube-engagement-tools/"><u>[New] 2024 Approved  Find Out  The Best 8 Youtube Engagement Tools</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-secrets-of-the-pros-youtube-live-mastery-techniques/"><u>2024 Approved  Secrets of the Pros  YouTube Live Mastery Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-magix-pixel-mastery-review/"><u>[New] Exploring MAGIX Pixel Mastery Review</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-samsung-galaxy-s23-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Samsung Galaxy S23</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-photos-after-huawei-nova-y91-has-been-deleted-by-fonelab-android-recover-photos/"><u>Recover your photos after Huawei Nova Y91 has been deleted.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>