---
title: "Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
date: 2024-09-11T09:44:25.281Z
updated: 2024-09-12T09:44:25.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
excerpt: "This Article Describes Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
keywords: Defying Standards,Camera Microphone Limits,Edge Device Control,Audio Tech Constraints,Non-Conforming Devices,Restrictive Hardware Use,Innovative Recording Boundaries
thumbnail: https://thmb.techidaily.com/59a195ec28420319fea5f3f07d0383273230910a4a9660ef6c59333c64bce5cd.jpg
---

## Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-active-screen-capture-pro-does-it-reign-supreme/"><u>[New] Active Screen Capture Pro Does It Reign Supreme?</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-10-budget-friendly-platforms-for-youtube-branding-mastery-for-2024/"><u>[Updated] 10 Budget-Friendly Platforms for YouTube Branding Mastery for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-standout-youtube-thumbnails-with-ease/"><u>[Updated] 2024 Approved Crafting Standout YouTube Thumbnails with Ease</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-raw-to-masterpiece-the-premier-free-mobile-editors-for-android/"><u>[Updated] 2024 Approved From Raw to Masterpiece The Premier Free Mobile Editors for Android</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-easy-steps-to-extract-instagram-video-files-from-pcmac/"><u>[Updated] Easy Steps to Extract Instagram Video Files From PC/Mac</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-cutting-edge-tips-for-capturing-movies-on-everyday-tech/"><u>[Updated] In 2024, Cutting-Edge Tips for Capturing Movies on Everyday Tech</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-masterclass-flawless-powerpoint-screen-recordings-for-2024/"><u>[Updated] Masterclass Flawless PowerPoint Screen Recordings for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-color-command-center-expert-transformation-techniques/"><u>2024 Approved Color Command Center Expert Transformation Techniques</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-mastering-cc-license-application-a-comprehensive-guide/"><u>2024 Approved Mastering CC License Application A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-insufficient-privilege-error-during-windows-setup/"><u>Combatting Insufficient Privilege Error During Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/concurrent-close-down-on-pc-multi-app-mastery/"><u>Concurrent Close-Down on PC: Multi-App Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-no-available-projectors-windows-alert/"><u>Correcting the 'No Available Projectors' Windows Alert</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unable-to-open-issue-on-ges-sharing-feature/"><u>Correcting Unable to Open Issue on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/deferring-windows-edge-tabs-on-windows-11/"><u>Deferring Windows Edge Tabs on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ease-of-access-tools-in-windows-right-click-options/"><u>Ease of Access Tools in Windows' Right-Click Options</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-to-fix-non-working-utorrent-installers-on-windows/"><u>Effective Methods to Fix Non-Working uTorrent Installers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-systemsettingsexe-problem-in-win11/"><u>Eliminating SystemSettings.exe Problem in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-efficiency-with-near-power-button-shortcuts-on-windows-11/"><u>Enhance Efficiency with Near-Power Button Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-must-have-components-warning-on-windows-1011/"><u>Eradicating Must-Have Components Warning on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/error-x-demystified-correcting-the-0x80072746-mail-flaw/"><u>Error X Demystified: Correcting the 0X80072746 Mail Flaw</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-for-resolving-check-pin-error-in-windows-1110/"><u>Essential Techniques for Resolving Check Pin Error in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-os-maintenance-the-unique-traits-of-chkdsk-scan-disk-vs-dissect/"><u>Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect</u></a></li>
<li><a href="https://screen-recording.techidaily.com/free-and-easy-best-mac-screen-recorder-software-of-2023/"><u>Free and Easy Best Mac Screen Recorder Software of 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/full-unveiling-of-picsart-complete-users-guide/"><u>Full Unveiling of PicsArt Complete User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-installation-error-secure-oculus-app-on-ws11wc10-windows/"><u>How to Fix Installation Error: Secure Oculus App on WS11/WC10 Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-shutdown-hindered-error-from-peculiar-windows-programs/"><u>How to Resolve Shutdown Hindered Error From Peculiar Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-an-automatic-update-reminder-toolbar-on-windows-11/"><u>Implementing an Automatic Update Reminder Toolbar on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-chromebooks-voice-alteration-guide-the-leading-online-text-to-speech-apps/"><u>In 2024, Chromebook's Voice Alteration Guide The Leading Online Text-to-Speech Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-sony-xperia-5-v-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Sony Xperia 5 V Device</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-analysis-of-windows-system-boot-configurations/"><u>In-Depth Analysis of Windows System Boot Configurations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-depth-evaluation-of-the-newest-slomo-video-software/"><u>In-Depth Evaluation of the Newest SloMo Video Software</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-insight-how-meditation-shapes-the-mental-landscape/"><u>Integrating Insight: How Meditation Shapes the Mental Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-user-preferences-with-powertoys-across-devices/"><u>Keeping User Preferences with PowerToys Across Devices</u></a></li>
<li><a href="https://win-answers.techidaily.com/league-of-legends-woes-top-strategies-for-fixing-black-screens-edition/"><u>League of Legends Woes? Top Strategies for Fixing Black Screens Edition</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-aoemi-for-efficient-windows-file-syncing/"><u>Leveraging AOEMi for Efficient Windows File Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/master-class-adjusting-system-index-settings/"><u>Master Class: Adjusting System Index Settings</u></a></li>
<li><a href="https://win11.techidaily.com/monitors-unleashed-personalized-themes-for-multitaskers-on-win-1011/"><u>Monitors Unleashed: Personalized Themes for Multitaskers on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-glitch-maze-fixing-microsoft-store-errors-on-1011/"><u>Navigating the Glitch Maze: Fixing Microsoft Store Errors on 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steamuidll-not-found-complication/"><u>Overcoming Steamui.dll Not Found Complication</u></a></li>
<li><a href="https://win11.techidaily.com/premier-predictions-winning-weather-apps-on-pc/"><u>Premier Predictions: Winning Weather Apps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/printer-spool-reinitiation-tips/"><u>Printer Spool Reinitiation Tips</u></a></li>
<li><a href="https://win11.techidaily.com/proven-techniques-for-effortless-docx-to-pdf-transfers-in-windows-11/"><u>Proven Techniques for Effortless Docx-to-PDF Transfers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/recover-unseen-window-extra-monitor/"><u>Recover Unseen Window Extra Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-access-denial-during-os-installer-processes/"><u>Resolving Access Denial During OS Installer Processes</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-issues-in-win-10/"><u>Resolving Steam Cloud Issues in Win 10</u></a></li>
<li><a href="https://buynow-help.techidaily.com/review-of-the-totobay-wake-up-light-second-generation-top-affordable-option/"><u>Review of the Totobay Wake-Up Light, Second Generation - Top Affordable Option</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unsuccessful-message-display-on-discord-system/"><u>Solving Unsuccessful Message Display on Discord System</u></a></li>
<li><a href="https://extra-support.techidaily.com/steady-visual-commencement-for-2024/"><u>Steady Visual Commencement for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/steelseries-gaming-mouse-driver-download-compatible-drivers-now-available/"><u>SteelSeries Gaming Mouse Driver Download - Compatible Drivers Now Available!</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-tips-to-fix-frame-drops-and-raise-fps-for-seamless-the-ascent-gameplay/"><u>Step-by-Step Tips to Fix Frame Drops and Raise FPS for Seamless 'The Ascent' Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-context-menu-on-windows-11-to-show-only-essentials/"><u>Tailor Context Menu on Windows 11 to Show Only Essentials</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/top-igtv-gurus-you-cant-miss-for-2024/"><u>Top IGTV Gurus You Can't Miss for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-discord-resolving-unresizeable-gif-issues-in-win11/"><u>Troubleshooting Discord: Resolving Unresizeable GIF Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-flickering-screens-on-windows-11/"><u>Troubleshooting Flickering Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-frozen-epic-game-launcher-instances/"><u>Troubleshooting Frozen Epic Game Launcher Instances</u></a></li>
<li><a href="https://win11.techidaily.com/turning-on-print-via-application-guard-in-windows-11-edge/"><u>Turning On Print via Application Guard in Windows 11 Edge</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/your-pathway-to-mastering-windows-boot-selection-process/"><u>Your Pathway to Mastering Windows Boot Selection Process</u></a></li>
</ul></div>

