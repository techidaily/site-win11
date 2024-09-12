---
title: "Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
date: 2024-09-11T09:31:09.038Z
updated: 2024-09-12T09:31:09.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
excerpt: "This Article Describes Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins"
keywords: Password Strength Guidelines,Login Failure Responses,Account Lockout Protocols,Secure Authentication Methods,User Access Management,Enhancing Security Postures,Preventing Brute Force Attacks
thumbnail: https://thmb.techidaily.com/2b0be1d254da9a28eb7fb0462b3c66de235332cf8b2fab4ba3941b84a9d75cac.jpg
---

## Optimizing Password Policy: Adjusting Lockout Counter Post-Failed Logins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-asmrs-role-in-better-nights-expert-vocal-guides/"><u>[New] 2024 Approved ASMR's Role in Better Nights Expert Vocal Guides</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-capture-winning-with-mov-files-on-your-windows-system/"><u>[New] 2024 Approved Capture Winning with MOV Files on Your Windows System</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-gaming-for-everyone-accessible-channels/"><u>[New] 2024 Approved Gaming for Everyone Accessible Channels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-ios-excellence-leading-apps-to-unlock-youtube-videos/"><u>[New] IOS Excellence Leading Apps to Unlock YouTube Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-step-by-step-guide-for-font-integration-in-ae/"><u>[New] Step-by-Step Guide for Font Integration in AE</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-navigate-instagram-video-problems-with-ease/"><u>[Updated] 2024 Approved Navigate Instagram Video Problems with Ease</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-how-to-record-youtube-live-stream-on-any-device/"><u>[Updated] In 2024, How To Record YouTube Live Stream On Any Device?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-navigating-the-digital-maze-to-save-snaps-from-social-media/"><u>[Updated] Navigating the Digital Maze to Save Snaps From Social Media</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-our-quick-and-complete-obs-youtube-streaming-path-for-newbies/"><u>[Updated] Our Quick & Complete OBS Youtube Streaming Path for Newbies</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-steps-to-optimize-win11-network-preferences/"><u>Detailed Steps to Optimize Win11 Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-issues-with-windows-11-search-bar/"><u>Eliminate Issues with Windows 11 Search Bar</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-os-maintenance-the-unique-traits-of-chkdsk-scan-disk-vs-dissect/"><u>Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-session-invalid-error-in-steam-gaming/"><u>How To Prevent “Session Invalid” Error in Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-shutdown-hindered-error-from-peculiar-windows-programs/"><u>How to Resolve Shutdown Hindered Error From Peculiar Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-an-automatic-update-reminder-toolbar-on-windows-11/"><u>Implementing an Automatic Update Reminder Toolbar on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Vivo Y28 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-xiaomi-redmi-note-12t-pro-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Xiaomi Redmi Note 12T Pro to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-motorola-moto-e13-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Motorola Moto E13 to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-asus-rog-phone-7-ultimate-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Asus ROG Phone 7 Ultimate Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-aggregatorhostexe-functionalities-and-security/"><u>Insight Into Windows' AggregatorHost.exe: Functionalities and Security</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-insight-how-meditation-shapes-the-mental-landscape/"><u>Integrating Insight: How Meditation Shapes the Mental Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-user-preferences-with-powertoys-across-devices/"><u>Keeping User Preferences with PowerToys Across Devices</u></a></li>
<li><a href="https://win11.techidaily.com/nearby-share-guide-for-dual-os-connectivity/"><u>Nearby Share Guide for Dual OS Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-zero-a00f-camera-application-issue/"><u>Overcoming Windows 11'S Zero-A00F Camera Application Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-missing-bluetooth-on-your-windows-11-pc-with-ease/"><u>Quickly Restore Missing Bluetooth on Your Windows 11 PC with Ease!</u></a></li>
<li><a href="https://win11.techidaily.com/refine-your-tapes-best-no-cost-windows-software/"><u>Refine Your Tapes: Best No-Cost Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-windows-fbm-errors-seamless-chats-ahead/"><u>Resolve Windows FBM Errors, Seamless Chats Ahead</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-access-denial-during-os-installer-processes/"><u>Resolving Access Denial During OS Installer Processes</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-directory-fullness-errors-with-code-0x80070091-on-windows-11/"><u>Resolving Directory Fullness Errors with Code: 0X80070091 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-avoiding-password-entry-for-rdp-connections/"><u>Stealth Mode: Avoiding Password Entry for RDP Connections</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-domain-services-printer-error-on-microsofts-newest-os/"><u>Tackling Domain Services Printer Error on Microsoft's Newest OS</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-context-menu-on-windows-11-to-show-only-essentials/"><u>Tailor Context Menu on Windows 11 to Show Only Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-efficiently-changing-directory-visibility-windows-11/"><u>Techniques for Efficiently Changing Directory Visibility (Windows 11)</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-miniature-powerhouse-ourlink-u631-usb-wi-fi-adapter-for-superior-speed-and-durability/"><u>The Miniature Powerhouse: OURLINK U631 USB Wi-Fi Adapter for Superior Speed & Durability</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-discord-resolving-unresizeable-gif-issues-in-win11/"><u>Troubleshooting Discord: Resolving Unresizeable GIF Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-after-successful-login-failed/"><u>Unlocking Windows After Successful Login Failed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-motorola-edge-40-neo-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Motorola Edge 40 Neo Device</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    