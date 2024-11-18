---
title: Strategizing Account Lockout Count Modification Post Multiple Failed Attempts, Win 11
date: 2024-11-14T03:35:31.231Z
updated: 2024-11-17T21:59:51.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategizing Account Lockout Count Modification Post Multiple Failed Attempts, Win 11
excerpt: This Article Describes Strategizing Account Lockout Count Modification Post Multiple Failed Attempts, Win 11
keywords: Account Lockout Strategy,Modify Lockout Limit,Failure Attempt Management,Secure Win11 Settings,Preventing Unauthorized Access,Safe Login Retries Control,Enhance Win 11 Security
thumbnail: https://thmb.techidaily.com/d62120d0f92dda8643d1fb18ba050a4238aed422d93382b937c3fa171ed251d1.jpg
---

## Strategizing Account Lockout Count Modification Post Multiple Failed Attempts, Win 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934254/19272" target="_top" id="1934254">
  <img src="//a.impactradius-go.com/display-ad/19272-1934254" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934254/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/n-2024-best-youtube-thumbnail-size-you-should-knowthe-ultimate-guide/"><u>[New] In 2024, Best YouTube Thumbnail Size You Should Know[The Ultimate Guide]</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-ultimate-collection-no-cost-ae-template-gold/"><u>[New] In 2024, Ultimate Collection No-Cost AE Template Gold</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-streamlining-production-processes-a-magix-video-pro-x-perspective/"><u>[New] Streamlining Production Processes A Magix Video Pro X Perspective</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-art-of-swapping-gender-representation-in-snapchatfacebook-photos/"><u>[Updated] Mastering the Art of Swapping Gender Representation in Snapchat/Facebook Photos</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-adventure-awaits-in-these-top-5-samsung-gear-vr-titles/"><u>2024 Approved Adventure Awaits in These Top 5 Samsung Gear VR Titles</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-quick-recording-techniques-for-firaxis-age-of-empires-ii/"><u>2024 Approved Quick Recording Techniques for Firaxis' Age of Empires II</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-accounts-after-fails/"><u>Bypassing Disabled Windows Accounts After Fails</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-access-the-key-to-your-windows-11-folder/"><u>Conquering Access: The Key to Your Windows 11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/from-concept-to-reality-paving-new-ways-in-windows-11-widgets/"><u>From Concept to Reality: Paving New Ways in Windows 11 Widgets</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/no-window-no-problem-master-the-art-of-reviving-hidden-apps-on-win-1011-with-6-tactics/"><u>No Window, No Problem! Master the Art of Reviving Hidden Apps on Win 10/11 with 6 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-embedding-app-shortcuts-in-windows-11/"><u>Step-by-Step Guide to Embedding App Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-remove-programs-without-permission-in-windows/"><u>Steps to Remove Programs Without Permission in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/swiftly-recommissioning-steam-service/"><u>Swiftly Recommissioning Steam Service</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    