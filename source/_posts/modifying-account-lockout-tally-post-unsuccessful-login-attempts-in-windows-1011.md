---
title: Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
date: 2024-06-25T10:08:11.147Z
updated: 2024-06-26T10:08:11.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
excerpt: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
keywords: WIN10/11 Account Lock,Unsuccessful Login Limit,Windows Lockout Settings,Preventing Bruteforce Attacks,Adjust Lockout Policy,Access Control in Win10/11,Manage Failed Logins
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
---

## Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11

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
<li><a href="https://win11.techidaily.com/stepping-past-the-steam-file-access-hurdle/"><u>Stepping Past the Steam “File Access” Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-booster-issues-windows-repair-guide/"><u>Skyrim Booster Issues: Windows Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-windows-11-cortana-commands/"><u>Overcoming Unresponsive Windows 11 Cortana Commands</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-v27-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo V27</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-of-going-unseen-during-instagram-live-events/"><u>[Updated] The Art of Going Unseen During Instagram Live Events</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-nighttime-tales-on-screen-insights-into-storytelling-videos-for-kids/"><u>[New] Nighttime Tales on Screen  Insights Into Storytelling Videos for Kids</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-realme-c67-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Realme C67 5G</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-successfully-embed-youtube-playlists-via-web-scripts/"><u>[New] 2024 Approved  How to Successfully Embed YouTube Playlists via Web Scripts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamline-your-web-experience-with-these-leading-screen-capturers/"><u>[Updated] Streamline Your Web Experience with These Leading Screen Capturers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-journey-through-podcast-land-iphoneipad-edition/"><u>[Updated] Journey Through Podcast Land  IPhone/iPad Edition</u></a></li>
<li><a href="https://extra-resources.techidaily.com/your-phones-callback-diary-iphone-future/"><u>Your Phone's Callback Diary - iPhone Future</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>