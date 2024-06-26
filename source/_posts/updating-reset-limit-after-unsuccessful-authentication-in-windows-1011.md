---
title: Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
date: 2024-06-25T11:31:25.360Z
updated: 2024-06-26T11:31:25.360Z
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
<li><a href="https://win11.techidaily.com/the-forgotten-windows-11-theme-archive/"><u>The Forgotten Windows 11 Theme Archive</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-non-functionality-in-windows-10/"><u>Fixing Grammarly Non-Functionality in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-android-studio-efficiency-on-windows-dev-environment/"><u>Maximize Android Studio Efficiency on Windows Dev Environment</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-art-with-top-win-11-sketch-tools/"><u>Elevate Your Art with Top Win 11 Sketch Tools</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-transferable-operation-relocating-your-torrent-software/"><u>Enabling Transferable Operation: Relocating Your Torrent Software</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-potential-your-custom-hotkey-journey/"><u>Unlocking Windows Potential: Your Custom Hotkey Journey</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-effective-methods-to-document-facetime-calls/"><u>In 2024, Effective Methods to Document FaceTime Calls</u></a></li>
<li><a href="https://extra-information.techidaily.com/spiritual-soundtracks-finding-and-tuning-for-ringtones/"><u>Spiritual Soundtracks  Finding & Tuning for Ringtones</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-nokia-g42-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Nokia G42 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-free-and-fabulous-the-best-4k-video-editors-for-2024/"><u>New Free and Fabulous The Best 4K Video Editors for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/screen-capture-tips-for-ios-devices-2023-update/"><u>Screen Capture Tips for iOS Devices - 2023 Update</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevate-your-content-in-depth-guide-to-youtube-video-edits/"><u>[Updated] In 2024, Elevate Your Content  In-Depth Guide to YouTube Video Edits</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-2023-guide-selecting-no-charge-fb-video-and-photo-artists/"><u>[New] 2024 Approved  2023 Guide  Selecting No-Charge FB Video & Photo Artists</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-dissecting-digital-communication-discord-versus-skype/"><u>[New] 2024 Approved  Dissecting Digital Communication  Discord Versus Skype</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>