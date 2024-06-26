---
title: Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
date: 2024-06-25T10:11:06.438Z
updated: 2024-06-26T10:11:06.438Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
excerpt: This Article Describes Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
keywords: WinResetLimitUpdate,AuthFailWindowsUpdate,WindowsAuthenticationLimit,UpdateLoginLimitError,ResetLimitUnAuthW10x11,AuthenticationResetLimit,UnsuccessfulWinResetUpd
thumbnail: https://thmb.techidaily.com/9c54005e696cd2ed7b70760eb63ef402583a5567abcd354a24f074d4d0059be5.jpg
---

## Updating Reset Limit After Unsuccessful Authentication in Windows 10/11

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
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-local-devices-avoid-in-use-names-errors/"><u>Overcoming Windows' Local Devices: Avoid In-Use Names Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-end-task-control-panel-in-windows-11-ui/"><u>Mastering the End Task Control Panel in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps</u></a></li>
<li><a href="https://win11.techidaily.com/get-rid-of-unwanted-files-setting-up-scheduled-deletions-on-win11/"><u>Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-failed-0x0000011b-in-windows/"><u>Overcoming Operation Failed 0X0000011B in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-social-media-showdown-2021-tiktok-vs-snapchat-whos-winning/"><u>[Updated] 2024 Approved  Social Media Showdown 2021  TikTok vs Snapchat - Who’s Winning?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-from-novice-to-pro-16-easy-to-use-free-video-editors-for-all-skill-levels/"><u>New 2024 Approved From Novice to Pro 16 Easy-to-Use Free Video Editors for All Skill Levels</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-first-use-to-expertise-a-comprehensive-fcp-guidebook/"><u>[New] From First Use to Expertise  A Comprehensive FCP Guidebook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-words-to-wax-mastering-voice-note-techniques-for-2024/"><u>From Words to Wax  Mastering Voice Note Techniques for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-elevate-your-online-presence-discord-picture-perfection/"><u>[New] 2024 Approved  Elevate Your Online Presence  Discord Picture Perfection</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-experience-retro-gaming-glory-with-best-pc-ps1-emulation-software/"><u>2024 Approved  Experience Retro Gaming Glory with Best PC PS1 Emulation Software</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-honor-100-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Honor 100?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-beyond-one-viewpoint-the-ultimate-review-of-best-11-bridge-cams/"><u>[New] Beyond One Viewpoint  The Ultimate Review of Best 11 Bridge Cams</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-6-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 6 with a Mask On</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>