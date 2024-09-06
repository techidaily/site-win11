---
title: Preventing Default Save Issues in Modern Windows
date: 2024-09-05T08:27:09.492Z
updated: 2024-09-06T08:27:09.492Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Default Save Issues in Modern Windows
excerpt: This Article Describes Preventing Default Save Issues in Modern Windows
keywords: WinSaveProtect,FixDefaultSaveWin,PreventWindowsSaves,StopSaveErrorWin,SecureDefaultSave,EliminateSaveFailures,WindowsSaveGuard
thumbnail: https://thmb.techidaily.com/41b376d29e85724c5481e57f7a36ad6deb299d08d21887a298dcedb2ce73aa51.jpg
---

## Preventing Default Save Issues in Modern Windows

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

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
## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-ideal-echo-chamber-recorders-for-2024/"><u>[New] Ideal Echo Chamber Recorders for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-simplifying-media-sharing-how-to-enable-autoplay-in-facebook-video-spaces-for-2024/"><u>[New] Simplifying Media Sharing  How to Enable Autoplay in Facebook Video Spaces for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-20-tiktok-captions-for-captivating-viewers-for-2024/"><u>[New] Top 20 TikTok Captions for Captivating Viewers for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-visionary-entry-critique-and-dissection-for-2024/"><u>[New] Visionary Entry Critique and Dissection for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unpacking-the-essence-of-digital-tales/"><u>[Updated] Unpacking the Essence of Digital Tales</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-netflixs-innovative-split-screen-tech/"><u>2024 Approved  Mastering Netflix's Innovative Split Screen Tech</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-tecno-pova-5-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Tecno Pova 5 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/hd4kwindowsmac/"><u>畅通HD/4K电影播放：转换Windows与Mac系统的技巧</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/audience-anticipation-crafting-captivating-video-content-on-social-media-for-2024/"><u>Audience Anticipation  Crafting Captivating Video Content on Social Media for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cognados-entre-ingles-y-espanol-50-expresiones-simples/"><u>Cognados Entre Inglés Y Español: 50 Expresiones Simples</u></a></li>
<li><a href="https://buynow-help.techidaily.com/1723088299053-comprehensive-review-of-the-razer-book-13-a-mini-beasts-bite/"><u>Comprehensive Review of the Razer Book 13 – A Mini Beast's Bite!</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-failed-sync-with-onedrive-on-windows/"><u>Correcting Failed Sync with OneDrive on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-magic-of-devhome-in-win11-landscape/"><u>Deciphering the Magic of DevHome in Win11 Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/decrypt-windows-passwords-the-ultimate-guide-to-opening-credential-manager/"><u>Decrypt Windows Passwords: The Ultimate Guide to Opening Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-rejuvenating-faulty-usb-hubs-in-windows/"><u>Diagnosing and Rejuvenating Faulty USB Hubs in Windows</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-msis-latest-innovation-the-aiplus-laptop-range-revolutionizing-gaming-and-creativity-with-up-to-542-tops/"><u>Discover MSI's Latest Innovation: The AI+ Laptop Range, Revolutionizing Gaming and Creativity with Up to 542 TOPS</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-windows-memory-dumps-an-essential-skill/"><u>Dissecting Windows Memory Dumps: An Essential Skill</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-dysfunctional-utilities-of-windows-10-fixes/"><u>Elevating Dysfunctional Utilities of Windows 10 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-gaming-experience-tackle-warhammers-stutter-problems/"><u>Enhance Your Gaming Experience - Tackle Warhammer's Stutter Problems</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-start-of-programs-despite-qt-platform-missing/"><u>Ensuring Smooth Start of Programs Despite Qt Platform Missing</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-depths-of-devhome-in-win11-world/"><u>Exploring the Depths of DevHome in Win11 World</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/eyecatcher-studio-wx-series-for-2024/"><u>EyeCatcher Studio WX Series for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/far-cry-6-no-more-blank-screens-ultimate-fix-guide/"><u>Far Cry 6 No More Blank Screens: Ultimate Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-crashing-virtual-machines-bsod-remedy-win11/"><u>Fixes for Crashing Virtual Machines: BSOD Remedy Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-tecno-pova-5-pro-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Tecno Pova 5 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-save-photo-from-video-in-windows-11-photos-app/"><u>How to Save Photo From Video in Windows 11 Photos App</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-conventional-to-cutting-edge-the-shift-from-rgb-to-srgb/"><u>In 2024, From Conventional to Cutting-Edge  The Shift From Rgb to Srgb</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-premium-designers-stellar-instagram-hlv-page-builders/"><u>In 2024, Premium Designers  Stellar Instagram HLV Page Builders</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-windows-ui-with-supernatural-shortcuts/"><u>Infuse Windows UI with Supernatural Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-to-attach-reminders-in-win11win10/"><u>Innovative Approaches to Attach Reminders in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/instant-guide-forcibly-disable-windows-11-print-devices/"><u>Instant Guide: Forcibly Disable Windows 11 Print Devices</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-speech-to-text-using-whisper/"><u>Instantaneous Speech-to-Text Using Whisper</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Vivo Y78+? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/joke-generation-made-simple-kapwing-app-guide-for-2024/"><u>Joke Generation Made Simple – Kapwing App Guide for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-data-merge-techniques-integrating-multiple-spreadsheet-sources-in-excel/"><u>Mastering Data Merge Techniques: Integrating Multiple Spreadsheet Sources in Excel</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-of-your-operating-systems-after-win-11-installation/"><u>Maximizing Efficiency of Your Operating Systems After Win 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-disruptive-javascript-error-in-discord-win-oses/"><u>Methods to Rectify Disruptive JavaScript Error in Discord Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-endless-enter-credential-errors-in-windows/"><u>Overcoming Endless Enter Credential Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permissions-hurdle-in-windows-application-management/"><u>Overcoming Permissions Hurdle in Windows Application Management</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-blockage/"><u>Overcoming Windows EXE Opener Blockage</u></a></li>
<li><a href="https://article-helps.techidaily.com/podcast-preludes-crafting-irresistible-openings-for-2024/"><u>Podcast Preludes  Crafting Irresistible Openings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-blue-screen-windows-error-code-0xc0000001/"><u>Quick Fixes for Blue Screen - Windows Error Code 0xC0000001</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/recording-power-20plus-best-practices-for-skype-chats-on-windowsmac-pcs-for-2024/"><u>Recording Power  20+ Best Practices for Skype Chats on Windows/Mac PCs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-how-to-reactivate-a-grayed-out-secure-boot-on-windows-pcs/"><u>Regaining Control: How to Reactivate a Grayed-Out Secure Boot on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-a-computer-name-mistake-on-windows-11/"><u>Reversing a Computer Name Mistake on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-share-failures-in-geforce-experience/"><u>Steps to Resolve Share Failures in GeForce Experience</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-immediate-accessibility-of-software-shortcuts/"><u>Stepwise Guide to Immediate Accessibility of Software Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-and-tips-to-find-missing-game-hub/"><u>Strategies and Tips to Find Missing Game Hub</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-application-launch-problems-in-windows-11/"><u>Strategies to Overcome Application Launch Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-approach-for-restarting-your-windows-update-cycle/"><u>Systematic Approach for Restarting Your Windows Update Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/the-experts-playbook-unearthing-mac-identifiers-in-windows-11/"><u>The Expert's Playbook: Unearthing MAC Identifiers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-quick-fix-handbook-unraveling-11-windows-quirks/"><u>The Quick-Fix Handbook: Unraveling 11 Windows Quirks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-guide-to-scaling-photos-and-vids-with-ai-discover-the-8-superior-applications/"><u>The Ultimate Guide to Scaling Photos & Vids with AI - Discover the 8 Superior Applications</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-find-x7-ultra-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Find X7 Ultra for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-auto-detection-failure-for-windows-network-proxies/"><u>Troubleshooting Auto Detection Failure for Windows Network Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-ps4-remote-control-re-establish-connection-issues-on-pc/"><u>Troubleshooting PS4 Remote Control: Re-Establish Connection Issues on PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-tips-how-to-overcome-the-challenge-of-black-screen-issues-on-facetime/"><u>Troubleshooting Tips: How To Overcome The Challenge Of Black Screen Issues On FaceTime</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-itunes-crashes-on-windows/"><u>Troubleshooting: ITunes Crashes on Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unboxing-the-lenovo-ideapad-320-a-fusion-of-style-portability-and-classic-keyboard-features-review-insights/"><u>Unboxing the Lenovo IdeaPad 320: A Fusion of Style, Portability & Classic Keyboard Features - Review Insights</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-win11s-network-insight-through-netstat-applications/"><u>Understanding Win11's Network Insight Through Netstat Applications</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-user-profile-optimization-via-command-line/"><u>Unlocking User Profile Optimization via Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/why-missing-drive-letters-happen-in-windows-solutions-explored/"><u>Why Missing Drive Letters Happen in Windows - Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pc-energy-consumption-understanding-usage-patterns/"><u>Windows PC Energy Consumption: Understanding Usage Patterns</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>