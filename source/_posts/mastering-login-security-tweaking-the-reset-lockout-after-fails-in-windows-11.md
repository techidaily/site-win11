---
title: "Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11"
date: 2024-11-10T20:13:52.553Z
updated: 2024-11-18T02:26:35.850Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-cutting-through-the-noise-top-15-non-gopro-cameras-for-2024/"><u>[New] Cutting Through the Noise Top 15 Non-GoPro Cameras for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-unleash-creativity-with-top-9-free-tools-to-craft-your-brand/"><u>[New] In 2024, Unleash Creativity with Top 9 Free Tools to Craft Your Brand</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-the-pros-guide-to-conquering-photovideo-importers-in-win11/"><u>[New] The Pro's Guide to Conquering Photo/Video Importers in Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-discover-8-trusted-online-content-marketing-tools-for-2024/"><u>[Updated] Discover 8 Trusted Online Content Marketing Tools for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-tips-for-stellar-video-conclusions/"><u>[Updated] In 2024, Tips for Stellar Video Conclusions</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-ceased-windows-security-activities/"><u>Counteracting Ceased Windows Security Activities</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-redefine-administrative-role-guide-for-windows-11-users/"><u>Efficiently Redefine Administrative Role: Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-configure-startup-services-in-windows-11/"><u>How to Configure Startup Services in Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-realme-11-proplus-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-keyboard-configuration-on-windows-11/"><u>Mastering Keyboard Configuration on Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-the-factory-reset-process-for-iphones-and-ipads-step-by-step-tips/"><u>Mastering the Factory Reset Process for iPhones and iPads – Step-by-Step Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/playstation-funding-guide-adding-and-shopping/"><u>PlayStation Funding Guide: Adding and Shopping</u></a></li>
<li><a href="https://win11.techidaily.com/seeking-windows-screen-saver-spot/"><u>Seeking Windows Screen Saver Spot</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-diagnostic-failures-on-computer-systems/"><u>Solutions for Diagnostic Failures on Computer Systems</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-guide-swift-and-effective-mkv-to-webm-file-transformation-techniques/"><u>Step-by-Step Guide: Swift and Effective MKV to WebM File Transformation Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-epic-games-access-on-your-system/"><u>Steps to Regain Epic Games Access on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-xbox-audio-settings-in-windows-11-os/"><u>Streamlining Xbox Audio Settings in Windows 11 OS</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208863446-thyroid-lymphoma-while-uncommon-can-be-more-prevalent-in-individuals-with-a-history-of-autoimmune-thyroiditis-like-hashimotos-disease/"><u>Thyroid Lymphoma, While Uncommon, Can Be More Prevalent in Individuals with a History of Autoimmune Thyroiditis Like Hashimoto's Disease.</u></a></li>
<li><a href="https://win11.techidaily.com/windows-keys-locked-here-are-quick-fixes-to-regain-accessibility-of-your-shortcut-commands/"><u>Windows Keys Locked? Here Are Quick Fixes to Regain Accessibility of Your Shortcut Commands</u></a></li>
</ul></div>

