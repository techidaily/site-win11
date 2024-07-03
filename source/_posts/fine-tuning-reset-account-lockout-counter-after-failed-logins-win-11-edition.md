---
title: Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
date: 2024-06-25T11:39:43.650Z
updated: 2024-06-26T11:39:43.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
excerpt: This Article Describes Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
keywords: Reset Lockout Windows,Login Failures Fix,Account Unlock Procedure,Win11 Password Recovery,Security Audit for Logins,Counter Failed Attempts,Lockout Settings Win 11
thumbnail: https://thmb.techidaily.com/3854233be38a7a3b692f6b1c87d1917c44d3f0b5ad0376d97a1f07070c0cf22e.jpg
---

## Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition

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
<li><a href="https://win11.techidaily.com/tips-to-uncover-hidden-system-startups/"><u>Tips to Uncover Hidden System Startups</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-cab-files-explanations-and-steps-for-installation/"><u>Understanding Windows Cab Files: Explanations & Steps for Installation</u></a></li>
<li><a href="https://win11.techidaily.com/1719374785731-unlock-additional-space-on-your-windows-system-for-free/"><u>Unlock Additional Space on Your Windows System, For Free!</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-mixed-user-microsoft-login-issues/"><u>Dealing with Mixed-User Microsoft Login Issues</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://win11.techidaily.com/10-trusted-secure-windows-software-download-spots/"><u>10 Trusted, Secure Windows Software Download Spots</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-admin-command-center-on-windows/"><u>Navigating to Admin Command Center on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-sony-lock-screen-password-by-drfone-android/"><u>How To Change Sony Lock Screen Password?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-edit-like-a-pro-gopro-video-editing-for-mac-users-2023-update/"><u>In 2024, Edit Like a Pro GoPro Video Editing for Mac Users (2023 Update)</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-tecno-pova-5-pro-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Tecno Pova 5 Pro 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-xiaomi-redmi-note-12r-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Xiaomi Redmi Note 12R?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-scopesight-appraisal-review/"><u>[New] ScopeSight Appraisal Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-video-marketing-top-20-strategies-to-watch-for-2024/"><u>[Updated] Facebook Video Marketing  Top 20 Strategies to Watch for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-enhance-visuals-with-better-obs-settings/"><u>In 2024, Enhance Visuals with Better OBS Settings</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-nokia-c210-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-innovative-split-screen-videos-for-youtube-sharing/"><u>[Updated] 2024 Approved  Innovative Split-Screen Videos for YouTube Sharing</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-maximizing-yandex-translate-in-video-translation-and-beyond/"><u>New Maximizing Yandex Translate in Video Translation and Beyond</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>