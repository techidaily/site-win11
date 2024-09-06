---
title: Crafting Personalized Inactivity Timer in Windows
date: 2024-09-05T08:40:23.632Z
updated: 2024-09-06T08:40:23.632Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting Personalized Inactivity Timer in Windows
excerpt: This Article Describes Crafting Personalized Inactivity Timer in Windows
keywords: WinTimerPersonalization,CustomInactiveBreak,ActivityPauseWMScreen,IndividualRestTimers,PersonalizedScreenTime,WindowsActivityTracker,TailoredInactivityCountdown
thumbnail: https://thmb.techidaily.com/ce2c767b4ea66790422350863194f4cca1e1e1f1b31e78a51ee237f509439d21.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Crafting Personalized Inactivity Timer in Windows

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-fb-live-streaming-to-perfect-mp3-format-2023-converter/"><u>[New] 2024 Approved  FB Live Streaming to Perfect MP3 Format - 2023 Converter</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-6-ingenious-sites-brimming-with-customizable-youtube-themes/"><u>[Updated] 2024 Approved  6 Ingenious Sites Brimming With Customizable YouTube Themes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-charting-financial-horizons-the-threefold-technique-for-analyzing-youtube-earning-data/"><u>[Updated] 2024 Approved  Charting Financial Horizons  The Threefold Technique for Analyzing YouTube Earning Data</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-mastering-fb-video-quick-subtitle-and-caption-creation-guide/"><u>[Updated] 2024 Approved  Mastering FB Video  Quick Subtitle & Caption Creation Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-the-insiders-guide-to-elevating-conference-calls-with-effects-and-masks/"><u>[Updated] In 2024, The Insider's Guide to Elevating Conference Calls with Effects and Masks</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-xiaomi-13t-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Xiaomi 13T Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/a-comprehensive-breakdown-is-hero7-black-the-best/"><u>A Comprehensive Breakdown: Is HERO7 Black the Best?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/artistic-anomaly-top-10-unique-affordable-mac-drawers-free-for-2024/"><u>Artistic Anomaly  Top 10 Unique, Affordable Mac Drawers (Free) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-compatibility-androidpc-connectivity-guide/"><u>Cross-Platform Compatibility: Android/PC Connectivity Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-wu-and-orchestrator-integration/"><u>Deciphering WU & Orchestrator Integration</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/effortless-video-and-image-backup-from-instagram/"><u>Effortless Video & Image Backup From Instagram</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-your-streaming-experience-switching-between-spotify-and-youtube-music/"><u>Elevating Your Streaming Experience  Switching Between Spotify & YouTube Music</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-display-visibility-quick-fix-guide/"><u>Enhance Windows 11 Display Visibility: Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visibility-a-cursor-guide-for-win10-and-11/"><u>Enhancing Visibility: A Cursor Guide for Win10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-keeping-df-game-from-locking-up-windows/"><u>Essential Tips for Keeping DF Game From Locking Up Windows</u></a></li>
<li><a href="https://win11.techidaily.com/expert-shortcuts-swiftly-sculpting-windows-11-directories/"><u>Expert Shortcuts: Swiftly Sculpting Windows 11 Directories</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-browser-blues-a-comprehensive-guide-to-solving-google-chromes-dark-screen-error/"><u>Fix Your Browser Blues: A Comprehensive Guide to Solving Google Chrome's Dark Screen Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-control-win11-rgb-settings/"><u>How to Control Win11 RGB Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eradicate-the-error-xc0f1103f-from-your-win11-and-geforce/"><u>How to Eradicate the Error Xc0f1103f From Your Win11 & GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-user-on-this-device-uses-this-microsoft-account-error-on-windows/"><u>How to Fix the Another User on This Device Uses This Microsoft Account Error on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-choosing-your-videos-ultimate-shape/"><u>In 2024, Choosing Your Video's Ultimate Shape</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-experts-guide-to-effortless-video-submissions-on-igtv/"><u>In 2024, The Expert's Guide to Effortless Video Submissions on IGTV</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-11-update-problems-non-existent/"><u>Making Windows 11 Update Problems Non-Existent</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-resolutions-in-modern-windows-versions/"><u>Mastering DirectDraw Resolutions in Modern Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/modify-monitor-angle-using-windows-tools/"><u>Modify Monitor Angle Using Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-installer-needs-more-access-rights-in-windows/"><u>Overcoming Installer Needs More Access Rights in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-vivo-v30-lite-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Vivo V30 Lite 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-failed-screensaver-on-windows-4-strategies/"><u>Resetting Failed Screensaver On Windows: 4 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-folders-not-open-glitch-in-windows-outlook/"><u>Steps to Overcome 'Folders Not Open' Glitch in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-tactics-for-shifting-between-windows-terminals-zones-of-attention-and-rest/"><u>Streamlined Tactics for Shifting Between Windows Terminal’s Zones of Attention and Rest</u></a></li>
<li><a href="https://win11.techidaily.com/switchingnotepadvisualswin-darkmode/"><u>SwitchingNotepadVisuals:Win-DarkMode</u></a></li>
<li><a href="https://win11.techidaily.com/the-underrated-world-of-windows-11-what-youre-missing-out-on/"><u>The Underrated World of Windows 11 - What You're Missing Out On</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-iscsi-initiator-an-overview-for-network-enthusiasts/"><u>The Windows iSCSI Initiator: An Overview for Network Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/tracking-credential-success-in-windows-computers-securely/"><u>Tracking Credential Success in Windows Computers Securely</u></a></li>
<li><a href="https://win11.techidaily.com/tuning-irqs-to-perfect-your-sound-card-experience/"><u>Tuning IRQs to Perfect Your Sound Card Experience</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-nokia-c110-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Nokia C110 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-disk-read-issues/"><u>Understanding and Rectifying Disk Read Issues</u></a></li>
<li><a href="https://win11.techidaily.com/windows-identity-compromised-trust-in-your-biometrics-questioned/"><u>Windows Identity Compromised: Trust in Your Biometrics Questioned</u></a></li>
<li><a href="https://win11.techidaily.com/windows-locks-halted-master-autolock-settings/"><u>Windows Locks Halted: Master Autolock Settings</u></a></li>
<li><a href="https://win11.techidaily.com/your-guide-to-safest-free-software-for-windows-devices/"><u>Your Guide to Safest Free Software for Windows Devices</u></a></li>
</ul></div>
