---
title: How to Reset Your Touch Keys' Initial Setup in Win 11
date: 2024-09-01T04:39:55.251Z
updated: 2024-09-02T04:39:55.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset Your Touch Keys' Initial Setup in Win 11
excerpt: This Article Describes How to Reset Your Touch Keys' Initial Setup in Win 11
keywords: Win 11 Keyboard Reset,11X Reset TK,Initial Keysetup Windows,Win11 TouchKeyreset,Reboot Keyboard Win11,Setup TK Reset Guide,Win11 TouchReset Steps
thumbnail: https://thmb.techidaily.com/1dd490a8bd0fd9490b2a1a7e2f3e07f4fe288167493a224a8c1401933c662484.jpeg
---

## How to Reset Your Touch Keys' Initial Setup in Win 11

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-revenue-rationale-calculating-your-average-earning-from-adsense-per-k-views/"><u>[New] 2024 Approved  Revenue Rationale  Calculating Your Average Earning From AdSense per K Views</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/irect-entry-into-your-channel-simplifying-the-follow-button-creation/"><u>[New] Direct Entry Into Your Channel  Simplifying the Follow Button Creation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-phasecope-pro-top-lightroom-replacements-unveiled/"><u>[New] PhaseCope Pro  Top Lightroom Replacements Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-introducing-your-podcast/"><u>[New] The Art of Introducing Your Podcast</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nleash-pure-content-how-to-block-youtube-ads-effectively-for-2024/"><u>[New] Unleash Pure Content  How to Block YouTube Ads Effectively for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-the-secret-of-hashtags-for-six-figures/"><u>[New] Unlocking the Secret of #Hashtags for Six Figures</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-hidden-melodic-markers-ios-and-android-recording-app-overview/"><u>[Updated] 2024 Approved  Hidden Melodic Markers  IOS & Android Recording App Overview</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-explore-top-rated-windows-10-video-capture-software/"><u>[Updated] Explore Top-Rated Windows 10 Video Capture Software</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-genres-to-gems-building-a-personalized-youtube-music-mix-onlinemobile-for-2024/"><u>[Updated] From Genres to Gems  Building a Personalized YouTube Music Mix Online/Mobile for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-transforming-tweetstream-into-hd-visionary-content-for-2024/"><u>[Updated] Transforming Tweetstream Into HD Visionary Content for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-excellent-e-recorders-for-voices/"><u>2024 Approved  Excellent E-Recorders for Voices</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-personalized-melodies-made-easy-building-a-youtube-music-collection-on-webmobile/"><u>2024 Approved  Personalized Melodies Made Easy  Building a YouTube Music Collection on Web/Mobile</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-setting-up-pip-mode-on-ios-youtubes-picture-in-picture/"><u>2024 Approved  Setting up PIP Mode on iOS  YouTube's Picture-in-Picture</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ais-interactive-voice-turning-prompts-into-meaningful-exchanges/"><u>AI's Interactive Voice: Turning Prompts Into Meaningful Exchanges</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/combatting-fraudgpt-essential-self-defense-tips/"><u>Combatting FraudGPT: Essential Self-Defense Tips</u></a></li>
<li><a href="https://fox-info.techidaily.com/complete-insight-visionpro-x-review-the-2023-edition-explored/"><u>Complete Insight  VisionPro X Review – The 2023 Edition Explored</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-compatibility-androidpc-connectivity-guide/"><u>Cross-Platform Compatibility: Android/PC Connectivity Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-wu-and-orchestrator-integration/"><u>Deciphering WU & Orchestrator Integration</u></a></li>
<li><a href="https://extra-information.techidaily.com/diy-tips-for-crafting-your-own-iphone-tones/"><u>DIY Tips for Crafting Your Own iPhone Tones</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-netgear-a6100-drivers-on-windows-latest-updates/"><u>Download and Install Netgear A6100 Drivers on Windows - Latest Updates</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-download-official-zexmte-usb-bluetooth-drivers-for-windows-operating-systems/"><u>Easy Download: Official Zexmte USB Bluetooth Drivers for Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-display-visibility-quick-fix-guide/"><u>Enhance Windows 11 Display Visibility: Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visibility-a-cursor-guide-for-win10-and-11/"><u>Enhancing Visibility: A Cursor Guide for Win10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-keeping-df-game-from-locking-up-windows/"><u>Essential Tips for Keeping DF Game From Locking Up Windows</u></a></li>
<li><a href="https://win11.techidaily.com/excel-data-consolidation-essentials-uniting-various-tables-with-ease/"><u>Excel Data Consolidation Essentials: Uniting Various Tables with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tips-how-to-embed-current-page-number-and-total-pages-into-document-headers/"><u>Excel Tips: How To Embed Current Page Number and Total Pages Into Document Headers</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-advice-on-correcting-pets-eye-issues-in-photographs/"><u>Expert Advice on Correcting Pets' Eye Issues in Photographs</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-on-handling-gtfo-program-interruptions/"><u>Expert Advice on Handling GTFO Program Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/expert-shortcuts-swiftly-sculpting-windows-11-directories/"><u>Expert Shortcuts: Swiftly Sculpting Windows 11 Directories</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-internet-connection-on-windows-systems/"><u>Fixing No Internet Connection on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-control-win11-rgb-settings/"><u>How to Control Win11 RGB Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eradicate-the-error-xc0f1103f-from-your-win11-and-geforce/"><u>How to Eradicate the Error Xc0f1103f From Your Win11 & GeForce</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-find-elite-instagram-tones-and-craft-unique-alarm-sounds/"><u>How to Find Elite Instagram Tones and Craft Unique Alarm Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-user-on-this-device-uses-this-microsoft-account-error-on-windows/"><u>How to Fix the Another User on This Device Uses This Microsoft Account Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-blackout-phenomenon-while-winning-games/"><u>How to Prevent Blackout Phenomenon While Winning Games</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-12-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 12 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-honor-90-lite-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Honor 90 Lite FRP Bypass Instantly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-samsung-galaxy-a14-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Samsung Galaxy A14 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-spark-10-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Tecno Spark 10 5G Phone without PIN</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-vivo-y78-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Vivo Y78 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-11-update-problems-non-existent/"><u>Making Windows 11 Update Problems Non-Existent</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-resolutions-in-modern-windows-versions/"><u>Mastering DirectDraw Resolutions in Modern Windows Versions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-media-importer-strategies-in-windows-10-for-2024/"><u>Mastering Media Importer Strategies in Windows 10 for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-the-art-of-continuous-snapstreak-success-for-2024/"><u>Mastering the Art of Continuous Snapstreak Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/modify-monitor-angle-using-windows-tools/"><u>Modify Monitor Angle Using Windows Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/outriders-launching-issues-successful-strategies-and-tips-to-play-without-glitches/"><u>Outriders Launching Issues? Successful Strategies and Tips to Play Without Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-installer-needs-more-access-rights-in-windows/"><u>Overcoming Installer Needs More Access Rights in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/prose-perfection-mastering-the-novel-craft-with-chatgpt/"><u>Prose Perfection: Mastering the Novel Craft with ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/refresh-virtual-memory-on-new-windows-11/"><u>Refresh Virtual Memory on New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-failed-screensaver-on-windows-4-strategies/"><u>Resetting Failed Screensaver On Windows: 4 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-windows-11-without-admin-authorization/"><u>Resetting Windows 11 Without Admin Authorization</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lack-of-system-temperature-regulation/"><u>Restoring Lack of System Temperature Regulation</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-folders-not-open-glitch-in-windows-outlook/"><u>Steps to Overcome 'Folders Not Open' Glitch in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-tactics-for-shifting-between-windows-terminals-zones-of-attention-and-rest/"><u>Streamlined Tactics for Shifting Between Windows Terminal’s Zones of Attention and Rest</u></a></li>
<li><a href="https://win11.techidaily.com/switchingnotepadvisualswin-darkmode/"><u>SwitchingNotepadVisuals:Win-DarkMode</u></a></li>
<li><a href="https://win11.techidaily.com/the-underrated-world-of-windows-11-what-youre-missing-out-on/"><u>The Underrated World of Windows 11 - What You're Missing Out On</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-iscsi-initiator-an-overview-for-network-enthusiasts/"><u>The Windows iSCSI Initiator: An Overview for Network Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/tracking-credential-success-in-windows-computers-securely/"><u>Tracking Credential Success in Windows Computers Securely</u></a></li>
<li><a href="https://win11.techidaily.com/tuning-irqs-to-perfect-your-sound-card-experience/"><u>Tuning IRQs to Perfect Your Sound Card Experience</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-disk-read-issues/"><u>Understanding and Rectifying Disk Read Issues</u></a></li>
<li><a href="https://win11.techidaily.com/windows-identity-compromised-trust-in-your-biometrics-questioned/"><u>Windows Identity Compromised: Trust in Your Biometrics Questioned</u></a></li>
<li><a href="https://win11.techidaily.com/windows-locks-halted-master-autolock-settings/"><u>Windows Locks Halted: Master Autolock Settings</u></a></li>
<li><a href="https://win11.techidaily.com/your-guide-to-safest-free-software-for-windows-devices/"><u>Your Guide to Safest Free Software for Windows Devices</u></a></li>
</ul></div>
