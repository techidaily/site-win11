---
title: "Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11"
date: 2024-11-02T21:10:00.638Z
updated: 2024-11-07T23:20:48.931Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11"
excerpt: "This Article Describes Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11"
keywords: Login Secure Win11,Reset Lockout Fix,Tweak User Pass,Enhance Login Security,Bypass Lockout Proc,Safe Windows Cred,Update Account Failures
thumbnail: https://thmb.techidaily.com/13464bbf7702e727674e34228111122f1f619fb5b014ebf3cf5f5ddd4c2dec0d.jpg
---

## Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11

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
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-your-ipad-as-a-creative-tool-for-time-lapse/"><u>[New] In 2024, Your iPad as a Creative Tool for Time Lapse</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-becoming-a-savvy-vr-tour-connoisseur/"><u>[Updated] Becoming a Savvy VR Tour Connoisseur</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-how-to-fix-live-video-interrupted-on-facebook/"><u>2024 Approved How to Fix Live Video Interrupted on Facebook?</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/critically-acclaimed-top-8-oculus-rift-games/"><u>Critically Acclaimed Top 8 Oculus Rift Games</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-resolving-frozen-ctrl-issues-for-windows-11/"><u>Diagnosing and Resolving Frozen Ctrl Issues for Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-y200e-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Vivo Y200e 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-improve-performance-of-windows-download-area/"><u>How to Improve Performance of Windows Download Area</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-motorola-edge-40-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Motorola Edge 40 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/simple-solutions-eliminating-screen-phantom-images-effortlessly/"><u>Simple Solutions: Eliminating Screen Phantom Images Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-solve-error-3-in-nvidia-opengl-win1011/"><u>Strategies to Solve Error 3 in NVIDIA OpenGL (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-eliminate-pointer-shake-on-pcs/"><u>The Ultimate Guide to Eliminate Pointer Shake on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-veiled-window-of-you-uncovering-windows-private-self-profile-access/"><u>The Veiled Window of You: Uncovering Windows’ Private Self-Profile Access</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tips-to-revive-a-frozen-wi-fi-mouse-on-windows/"><u>Top 5 Tips to Revive a Frozen Wi-Fi Mouse on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    