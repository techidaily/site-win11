---
title: "Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users"
date: 2024-08-08T13:14:29.985Z
updated: 2024-08-09T13:14:29.985Z
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-download-harmony-free-music-from-fb-for-2024/"><u>[New] Download Harmony  Free Music From FB for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-boost-your-brand-twitter-ads-guide/"><u>[New] In 2024, Boost Your Brand  Twitter Ads Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-harmony-haven-our-selection-of-the-top-20-musical-channels-on-youtube/"><u>[New] In 2024, Harmony Haven  Our Selection of the Top 20 Musical Channels on YouTube</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-unveiling-5-excellent-mac-livestream-software/"><u>[New] In 2024, Unveiling 5 Excellent Mac Livestream Software</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-blocking-facebooks-advertising-overload-in-real-time-for-2024/"><u>[Updated] Blocking Facebook's Advertising Overload in Real Time for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-essential-screen-recording-tools-a-comprehensive-educators-guide/"><u>[Updated] In 2024, Essential Screen Recording Tools  A Comprehensive Educator's Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-quicktweet-clip-swiftly-gather-social-media-vids/"><u>[Updated] QuickTweet Clip  Swiftly Gather Social Media Vids</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-scribes-summit-selection-top-8/"><u>[Updated] Scribe's Summit Selection - Top 8</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-guide-to-automated-mac-lecture-recording-for-2024/"><u>[Updated] The Ultimate Guide to Automated Mac Lecture Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-urban-ecosystem-fostering-resilience-through-green-policies/"><u>2024 Approved  The Urban Ecosystem  Fostering Resilience Through Green Policies</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-honor-90-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Honor 90 without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722892228339-discover-these-6-exceptional-no-cost-photo-manipulation-tools/"><u>Discover These 6 Exceptional No-Cost Photo Manipulation Tools</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-pioneer-dj-ddj-sx2-drivers-in-minutes-step-by-step-tutorial/"><u>Download and Install Pioneer DJ DDJ-SX2 Drivers in Minutes - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-reverting-customized-windows-configurations/"><u>Effective Methods: Reverting Customized Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-user-experience-tailoring-windows-via-alomware-applications/"><u>Elevate User Experience: Tailoring Windows via AlomWare Applications</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-in-windows-11-os/"><u>Ensuring a Valid Temp Directory in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-sudden-invisibility-issues-in-pc-gaming/"><u>Eradicating Sudden Invisibility Issues in PC Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-lsa-error-on-windows-systems/"><u>Fixing LSA Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/graphics-correction-step-by-step-windows-11/"><u>Graphics Correction: Step-by-Step Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/harmonics-high-flyers-top-5-programs-for-surpassing-windows-maxed-sound-level/"><u>Harmonics High-Flyers: Top 5 Programs for Surpassing Windows' Maxed Sound Level</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-connect-remote-desktop-without-a-password-in-windows-11/"><u>How to Connect Remote Desktop Without a Password in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-high-definition-zoom-features/"><u>In 2024, Navigating High-Definition Zoom Features</u></a></li>
<li><a href="https://extra-information.techidaily.com/jokesonscreen-pro/"><u>JokesOnScreen Pro</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-guide-skipping-pin-on-windows-win11-cast/"><u>Mastery Guide: Skipping PIN on Window's Win11 Cast</u></a></li>
<li><a href="https://win11.techidaily.com/missing-dxgidll-in-win11-heres-an-action-plan/"><u>Missing Dxgi.dll in Win11? Here's an Action Plan</u></a></li>
<li><a href="https://win11.techidaily.com/organize-like-a-pro-5-must-try-windows-folder-tricks/"><u>Organize Like a Pro: 5 Must-Try Windows Folder Tricks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/organize-soundtracks-on-youtube-the-playlist-guide-for-2024/"><u>Organize Soundtracks on Youtube  The Playlist Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-freeze-issues-photoshopping-onoff-windows-11-versions-2023/"><u>Overcoming Freeze Issues: Photoshopping On/Off Windows 11, Versions 2023</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-windows-11s-potential-for-phone-synergy/"><u>Probing Into Windows 11’S Potential for Phone Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/propel-power-5-best-windows-optimization-strategies/"><u>Propel Power: 5 Best Windows Optimization Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-ram-overcoming-obstacles-in-windows/"><u>Reigniting RAM: Overcoming Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/removing-the-0x800704cf-hurdle-in-windows-store-experience/"><u>Removing the 0X800704CF Hurdle in Windows Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sudden-freeze-and-blackout-with-steam/"><u>Resolving Sudden Freeze & Blackout with Steam</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/revolutionizing-tv-broadcasts-with-fb-live-streaming/"><u>Revolutionizing TV Broadcasts with FB Live Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-account-transitioning-from-pin-to-password-in-windows-11/"><u>Secure Your Account: Transitioning From PIN to Password in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-type-mistakes-in-windows-11-zerox-error/"><u>Solutions for Correcting Type Mistakes in Windows 11 Zerox Error</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-out-with-yt-shorts-essential-guidelines-to-follow/"><u>Stand Out with YT Shorts  Essential Guidelines to Follow</u></a></li>
<li><a href="https://win11.techidaily.com/the-importance-of-consistent-windows-data-saves/"><u>The Importance of Consistent Windows Data Saves</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peace-sleep-mode-strategies/"><u>The Path to Peace: Sleep Mode Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-printer-commands-using-windows-11-edge-shield-mode/"><u>Triggering Printer Commands Using Windows 11 Edge Shield Mode</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-values-on-windows-devices/"><u>Troubleshooting Missing Values on Windows Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-infinix-note-30-by-drfone-android/"><u>Universal Unlock Pattern for Infinix Note 30</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-more-disk-room-with-this-roundup-of-cheap-volume-enhancers/"><u>Unlock More Disk Room with This Roundup of Cheap Volume Enhancers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-ftdibussys-and-windows-memory-standards/"><u>Unlocking the Secrets of ftdibus.sys & Windows Memory Standards</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-behind-error-0x80370102-in-wsl-distribution/"><u>Unraveling the Cause Behind Error 0X80370102 in WSL Distribution</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/winrars-file-consistency-fixing-summation-discrepancies/"><u>WinRAR's File Consistency: Fixing Summation Discrepancies</u></a></li>
</ul></div>
