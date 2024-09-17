---
title: "Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
date: 2024-09-11T05:47:41.047Z
updated: 2024-09-16T22:13:23.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
excerpt: "This Article Describes Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
keywords: Lockout Management Guide,Failed Login Triggers Changes,Access Denied Resolution Steps,Unauthorized Sign-Out Adjustments,Post-Lockout System Tweaks,Security Protocols After Failures,Lockout Alterations Guidebook
thumbnail: https://thmb.techidaily.com/72178c55a17f02b5af426d7fce9f5984667c0f559291ba6b4b11d31fc14a8936.jpg
---

## Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<li><a href="https://video-screen-grab.techidaily.com/new-elite-fighting-top-10-royale-action-experiences-for-2024/"><u>[New] Elite Fighting Top 10 Royale Action Experiences for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/xclusive-access-prime-video-downloader-picks/"><u>[New] Exclusive Access Prime Video Downloader Picks</u></a></li>
<li><a href="https://win11.techidaily.com/44cm5yuv55s75zyn57iu44go44oa44km44oz44ot44o844oj44ks44kk44oj44cn/"><u>「動画圧縮とダウンロードガイド」</u></a></li>
<li><a href="https://win11.techidaily.com/5yuv55s757eo6zug5ywl6zaaic0g5yid5bplusd6icf44gn44kc5qw944gx44gp5a2m44g544kl5pa55rov/"><u>動画編集入門 - 初心者でも楽しく学べる方法</u></a></li>
<li><a href="https://win11.techidaily.com/adobe-premiere-proelephant/"><u>Adobe Premiere ProとElephantによるステップバイステップガイド: 写真をビデオに変換する方法</u></a></li>
<li><a href="https://win11.techidaily.com/best-free-online-tools-convert-av1-videos-to-mp4-format/"><u>Best Free Online Tools: Convert AV1 Videos to MP4 Format</u></a></li>
<li><a href="https://win11.techidaily.com/convert-vob-videos-into-mov-format-step-by-step-guide/"><u>Convert VOB Videos Into MOV Format Step-by-Step Guide</u></a></li>
<li><a href="https://discover-best.techidaily.com/fixing-handbrake-errors-successful-dvd-conversion-tips/"><u>Fixing Handbrake Errors: Successful DVD Conversion Tips</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-effortless-audio-capture-techniques-for-new-windows-11-users/"><u>In 2024, Effortless Audio Capture Techniques for New Windows 11 Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-lava-yuva-2-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Lava Yuva 2</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-picture-in-picture-mode-with-ease-in-microsoft-edge/"><u>Navigating Picture-In-Picture Mode with Ease in Microsoft Edge</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/push-boundaries-with-unique-split-screen-videos-for-youtube-for-2024/"><u>Push Boundaries with Unique Split-Screen Videos for YouTube for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/smooth-out-gameplay-overcoming-delays-in-anthem/"><u>Smooth Out Gameplay: Overcoming Delays in Anthem</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-the-constant-bugs-in-thunders-top-tier-level-a-users-manual/"><u>Solving the Constant Bugs in Thunder's Top-Tier Level - A User's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/anddvdmov/"><u>スピーディ&シンプルなDVDからMOVへの直接変換ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/bandicam/"><u>どうすればBandicamで記録できない状況を克服できるか？</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128843/7443" target="_top" id="2128843">
  <img src="//a.impactradius-go.com/display-ad/7443-2128843" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128843/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

