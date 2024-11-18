---
title: "Win 11: Tips for Modifying Login Lockout Count Post-Failures"
date: 2024-11-13T21:07:30.012Z
updated: 2024-11-18T07:51:52.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Tips for Modifying Login Lockout Count Post-Failures"
excerpt: "This Article Describes Win 11: Tips for Modifying Login Lockout Count Post-Failures"
keywords: Win11LockoutTips,ChangeLoginLockoutCount,Windows11FailureMods,AdjustLockoutAfterFail,Win11Post-FailureSettings,ModifyWindows11LockTime,LockoutCountAdjustmentWin
thumbnail: https://thmb.techidaily.com/92e9b29713cc88b11300b903399854331375d2de8a951965b47ae1bc4c0fa3c6.jpg
---

## Win 11: Tips for Modifying Login Lockout Count Post-Failures

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-explore-advanced-multi-screen-browsing-in-chrome/"><u>[New] Explore Advanced Multi-Screen Browsing in Chrome</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-leaders-shaping-the-marvel-online-experience/"><u>[Updated] In 2024, Leaders Shaping the Marvel Online Experience</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-the-ultimate-guide-to-establishing-a-twitter-presence/"><u>[Updated] In 2024, The Ultimate Guide to Establishing a Twitter Presence</u></a></li>
<li><a href="https://fox-helps.techidaily.com/cutting-edge-gaming-setup-unpacking-samsungs-ue590-panel-for-2024/"><u>Cutting Edge Gaming Setup Unpacking Samsung's UE590 Panel for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-battery-alerts-windows-insider-guide/"><u>Enhancing Battery Alerts: Windows Insider Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-setting-up-your-apple-homepod-with-your-television-easily/"><u>Expert Advice: Setting Up Your Apple HomePod with Your Television Easily</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-prime-selection-of-affordable-cams-for-action-sports/"><u>In 2024, Prime Selection of Affordable Cams for Action Sports</u></a></li>
<li><a href="https://win11.techidaily.com/make-every-device-mobile-ready-with-easy-apk-installs-on-w11/"><u>Make Every Device Mobile-Ready with Easy APK Installs on W11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-persistent-windows-update-problems/"><u>Solving the Persistent Windows Update Problems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-rated-mp3-players-the-ultimate-guide/"><u>Top Rated MP3 Players : The Ultimate Guide</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-absence-of-network-router-access/"><u>Troubleshooting Absence of Network Router Access</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ng-youtube-music-into-mp3-files-with-macos-for-2024/"><u>Turning YouTube Music Into MP3 Files with MacOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-potential-with-our-recommended-8-timer-apps-for-windows/"><u>Unleash Your Potential With Our Recommended 8 Timer Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-steams-session-verification-failed-woes/"><u>Unraveling Steam's Session Verification Failed Woes</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-sound-leveraging-the-volume-mixer-in-action-center/"><u>Windows 11 Sound: Leveraging the Volume Mixer in Action Center</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    