---
title: "Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
date: 2024-10-20T01:31:04.576Z
updated: 2024-10-21T00:08:36.831Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016134/19272" target="_top" id="2016134">
  <img src="//a.impactradius-go.com/display-ad/19272-2016134" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016134/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-downloading-insta-videos-in-two-simple-ways-for-2024/"><u>[New] Downloading Insta Videos in Two Simple Ways for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-dynamic-subtitle-artisan/"><u>[Updated] In 2024, Dynamic Subtitle Artisan</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-maximize-your-google-meet-experience-with-effective-use-of-digital-boards-on-any-os/"><u>[Updated] Maximize Your Google Meet Experience with Effective Use of Digital Boards on Any OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-cutting-edge-review-superior-text-plugins-for-adobe-ae/"><u>2024 Approved Cutting-Edge Review Superior Text Plugins for Adobe AE</u></a></li>
<li><a href="https://win-amazing.techidaily.com/connect-your-samsung-to-pc-with-new-windows-11-usb-driver-downloads/"><u>Connect Your Samsung to PC with New Windows 11 USB Driver Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/enliven-your-windows-11-desktop-live-wallpaper-tutorial/"><u>Enliven Your Windows 11 Desktop: Live Wallpaper Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-windows-11-unwritable-files-issue/"><u>Methods to Rectify Windows 11: Unwritable Files Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/passo-a-passo-simples-para-recuperacao-de-fotos-antigas-tecnicas-eficazes-do-movavi/"><u>Passo a Passo Simples Para Recuperação De Fotos Antigas - Técnicas Eficazes Do Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/protective-measures-against-unauthorized-insiders/"><u>Protective Measures Against Unauthorized Insiders</u></a></li>
<li><a href="https://win11.techidaily.com/swift-transitioning-techniques-in-and-out-of-window-terminals-attention-spotlight/"><u>Swift Transitioning Techniques: In & Out of Window Terminal's Attention Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-gameplay-8-steps-to-better-frames/"><u>Upgrade Your Gameplay: 8 Steps to Better Frames</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
</ul></div>

