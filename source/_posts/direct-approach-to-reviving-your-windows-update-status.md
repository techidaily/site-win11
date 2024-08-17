---
title: Direct Approach to Reviving Your Windows Update Status
date: 2024-08-16T00:15:52.741Z
updated: 2024-08-17T00:15:52.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Approach to Reviving Your Windows Update Status
excerpt: This Article Describes Direct Approach to Reviving Your Windows Update Status
keywords: WinUpdate Fix Method,Direct Updater Restore,Quick Windows Status,Reboot After Update,Updating Process Start,Update Fix Guide,Reviving Windows Patches
thumbnail: https://thmb.techidaily.com/7a684ff6b3f7243ec032f5ae8a931d190264bae1e112796613965ade353d6f1f.png
---

## Direct Approach to Reviving Your Windows Update Status

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir% system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-advanced-tips-for-accurate-and-smooth-hp-laptop-screen-capture/"><u>[New] 2024 Approved  Advanced Tips for Accurate and Smooth HP Laptop Screen Capture</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-a-filmmakers-essential-guide-to-free-royalty-free-audiosites-for-2024/"><u>[New] A Filmmaker's Essential Guide to Free Royalty-Free Audiosites for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-videos-youtube-trailers-through-filmora/"><u>[New] In 2024, Elevate Your Videos  YouTube Trailers Through Filmora</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-top-picks-excellent-4k-displays-for-playing-games-for-2024/"><u>[New] Top Picks  Excellent 4K Displays for Playing Games for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-unconfident-to-impactful-embracing-youtube-blogging/"><u>[Updated] 2024 Approved  From Unconfident to Impactful  Embracing YouTube Blogging</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-primary-footage-document-critique-with-asides/"><u>[Updated] 2024 Approved  Primary Footage Document Critique with Asides</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-creating-a-unique-online-presence-using-obs-youtube-and-twitch/"><u>[Updated] In 2024, Creating a Unique Online Presence  Using OBS, YouTube & Twitch</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-enhancing-team-call-aesthetics-before-and-after/"><u>[Updated] In 2024, Enhancing Team Call Aesthetics  Before & After</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-journey-into-tech-mastery-essential-tips-for-screen-recording-your-mac/"><u>[Updated] In 2024, Journey Into Tech Mastery  Essential Tips for Screen Recording Your Mac</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-unmatched-3d-viewing-excellence-with-elite-decks-reviewed/"><u>[Updated] Unmatched 3D Viewing Excellence with Elite Decks Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://win-answers.techidaily.com/addressed-problem-restoring-audio-during-your-twitch-live-session/"><u>Addressed Problem: Restoring Audio During Your Twitch Live Session</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clumped-up-windows-11-icon-grouping/"><u>Adjusting Clumped-Up Windows 11 Icon Grouping</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://win-answers.techidaily.com/breaking-down-cod-warzones-devilish-error-6328-top-strategies-to-succeed/"><u>Breaking Down Cod Warzone's Devilish Error 6328 - Top Strategies to Succeed</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-bricked-windows-update-fix/"><u>Bypassing a Bricked Windows Update Fix</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-and-ram-usage-tackling-unrealcefsubprocess-issues/"><u>Decreasing CPU and RAM Usage: Tackling UnrealCEFSubprocess Issues</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevate-designs-essential-secrets-for-canva-mastery/"><u>Elevate Designs  Essential Secrets for Canva Mastery</u></a></li>
<li><a href="https://fox-http.techidaily.com/elevating-your-video-posts-with-properly-uploaded-srt-files/"><u>Elevating Your Video Posts with Properly Uploaded SRT Files</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-photo-backup-networks/"><u>Elite Photo Backup Networks</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-effective-batch-conversion-of-heic-to-jpeg-in-windows/"><u>Expert Tips for Effective Batch Conversion of HEIC to JPEG in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/film-techniques-free-ecological-templates/"><u>Film Techniques  Free Ecological Templates</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-identifiable-usb-port-error-on-windows-11/"><u>Fixing Non-Identifiable USB Port Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-open-issues-windows-11s-mail-and-calendar-hiccup/"><u>Fixing Open Issues: Windows 11'S Mail & Calendar Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-video-buffer-issues-streamlined-vlc-on-pc/"><u>Fixing Video Buffer Issues: Streamlined VLC on PC</u></a></li>
<li><a href="https://win11.techidaily.com/forward-into-futures-ai-driven-windows-transformation/"><u>Forward Into Futures: AI-Driven Windows Transformation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/getting-your-xbox-series-xs-headset-working-again-a-comprehensive-fix-guide/"><u>Getting Your Xbox Series X/S Headset Working Again: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-sony-xperia-5-v-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Sony Xperia 5 V Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-11-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reestablish-network-connection-after-failure-in-windows-11/"><u>How to Reestablish Network Connection After Failure in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-samsung-galaxy-a14-5g-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Samsung Galaxy A14 5G</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-fresh-topics-to-cover-in-your-vlogs/"><u>In 2024, Fresh Topics to Cover in Your Vlogs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-final-cut-pro-with-ease-an-insiders-guide/"><u>In 2024, Navigating Final Cut Pro with Ease  An Insider's Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-peek-into-personality-traits-top-6-quizzes-to-determine-youtuber-preferences/"><u>In 2024, Peek Into Personality Traits  Top 6 Quizzes to Determine YouTuber Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-fixes-in-windows-10-and-11/"><u>Mastering DirectDraw Fixes in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-for-a-macos-feel-in-windows/"><u>Mastering Window Customization for a macOS Feel in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-realme-c51-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Realme C51? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-previous-windows-configurations/"><u>Quick Guide to Restoring Previous Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tutorial-opening-the-windows-info-panel/"><u>Quick Tutorial: Opening the Windows Info Panel</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-over-silent-slack-alerts-in-win-11/"><u>Regain Control Over Silent Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-no-connection-found-on-win-810/"><u>Remedying No Connection Found on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vmware-freeze-up-in-windows-11/"><u>Resolving VMware Freeze-Up in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-microsofts-speech-recognition-in-windows-11/"><u>Restoring Microsoft's Speech Recognition in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-snaps-windows-strategies-for-sticky-notes/"><u>Secure Your Snaps: Windows Strategies for Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-stop-laptops-internal-keystrokes/"><u>Step-by-Step: Stop Laptop's Internal Keystrokes</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-home-admin-with-ease-of-use/"><u>Streamline Windows Home Admin with Ease of Use</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-faulty-microsoft-store-eradicate-0x80072efd/"><u>Tackling Faulty Microsoft Store: Eradicate 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-overcoming-failed-rpc-in-windows/"><u>The Ultimate Guide to Overcoming Failed RPC in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-pre-buying-your-ideal-win-pc/"><u>The Ultimate Guide to Pre-Buying Your Ideal Win PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unlock-15-simple-vlog-inspirations-today/"><u>Unlock 15 Simple Vlog Inspirations Today</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-from-digital-to-physical-burning-videos-to-dvds-on-windows-and-mac/"><u>Updated 2024 Approved From Digital to Physical Burning Videos to DVDs on Windows and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-shouldnt-use-ai-chatbots-to-generate-windows-11-keys/"><u>Why You Shouldn’t Use AI Chatbots to Generate Windows 11 Keys</u></a></li>
</ul></div>
