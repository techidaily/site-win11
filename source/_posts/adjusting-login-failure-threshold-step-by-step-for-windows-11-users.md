---
title: "Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users"
date: 2025-03-01T00:29:07.406Z
updated: 2025-03-05T01:33:22.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users"
excerpt: "This Article Describes Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users"
keywords: Win11 Login Adjustments,Failure Thresh Hold Config,Login Error Management,User Access Restrictions,Security Windows Login,Optimize Login Rules,Increase Login Success
thumbnail: https://thmb.techidaily.com/45bc41dfd22bb4252a227dcc20488f6faf42f4a30eaffbfeaeadce5abdbcdc1d.png
---

## Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-decoding-the-earning-dynamics-for-podcasters-for-2024/"><u>[New] Decoding the Earning Dynamics for Podcasters for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-greatest-7-web-based-recording-tools-2023/"><u>[New] Greatest 7 Web-Based Recording Tools 2023</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-alert-tones-superior-download-sites-list/"><u>[New] Top Alert Tones Superior Download Sites List</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-virtual-voyages-unveiled-the-ultimate-gaming-odyssey-top-10/"><u>[New] Virtual Voyages Unveiled The Ultimate Gaming Odyssey (Top 10)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-auto-color-management-for-apps-in-windows-11/"><u>How to Enable Auto Color Management for Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-c-drive-from-being-overfilled/"><u>How to Prevent C: Drive From Being Overfilled</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/proven-ways-to-convert-mkv-files-to-mp4-in-windows/"><u>Proven Ways to Convert MKV Files to MP4 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-windows-11s-languishing-5g-connection/"><u>Reviving Your Windows 11'S Languishing 5G Connection</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-beginners-tutorial-on-clearing-the-cmos-for-effective-bios-management/"><u>The Beginner’s Tutorial on Clearing the CMOS for Effective BIOS Management</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-how-to-overcome-the-red-dead-redemption-loading-screen-glitch/"><u>Troubleshooting: How to Overcome the Red Dead Redemption ^Loading Screen Glitch</u></a></li>
</ul></div>

