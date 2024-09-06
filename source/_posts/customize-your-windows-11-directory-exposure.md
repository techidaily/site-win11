---
title: Customize Your Window's 11 Directory Exposure
date: 2024-09-05T08:43:39.639Z
updated: 2024-09-06T08:43:39.639Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Your Window's 11 Directory Exposure
excerpt: This Article Describes Customize Your Window's 11 Directory Exposure
keywords: Custom Window Display Adjustment,DirExpo Customization Guide,Windows View Settings,Personalized Directory View,Optimize Window Pane,Fixed Window Positioning,Tailored Screen Layout
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Customize Your Window's 11 Directory Exposure

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://youtube-lab.techidaily.com/024-approved-perfect-harmony-strategies-for-top-tier-audio-recording/"><u>[New] 2024 Approved  Perfect Harmony  Strategies for Top-Tier Audio Recording</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-unveiling-techniques-for-targeted-youtube-video-download/"><u>[New] 2024 Approved  Unveiling Techniques for Targeted YouTube Video Download</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-12-tactics-to-reveal-facebook-videos-not-displaying-2023-edition/"><u>[Updated] 12 Tactics to Reveal Facebook Videos Not Displaying, 2023 Edition</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-filter-fiesta-the-ultimate-guide-to-transformative-snaps-for-2024/"><u>[Updated] Filter Fiesta  The Ultimate Guide to Transformative Snaps for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-live-sound-perfection-our-selections-of-the-top-6-stream-friendly-mics/"><u>[Updated] Live Sound Perfection  Our Selections of the Top 6 Stream-Friendly Mics</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-youtube-video-dimension-standards/"><u>[Updated] YouTube Video Dimension Standards</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-altering-game-console-speech-ps5ps4-upgrades/"><u>2024 Approved  Altering Game Console Speech  PS5/PS4 Upgrades</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-inside-look-at-youtubes-creator-studio-interface/"><u>2024 Approved  Inside Look at YouTube's Creator Studio Interface</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-filter-kids-web-activity/"><u>Configuring Windows 11 to Filter Kids' Web Activity</u></a></li>
<li><a href="https://win11.techidaily.com/cure-voice-command-issues-reactivation-techniques-for-win11/"><u>Cure Voice Command Issues: Reactivation Techniques for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-path-to-exceptional-windows-wallpapers/"><u>Decoding the Path to Exceptional Windows Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/fast-focus-furious-fighting-efficient-gameplay-fixes-for-bf2/"><u>Fast Focus, Furious Fighting: Efficient Gameplay Fixes for BF2</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/filmora-watermark-how-to-bypass-or-remove-it-permanently-for-2024/"><u>Filmora Watermark How to Bypass or Remove It Permanently for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-your-windows-sleep-timer/"><u>Fine-Tune Your Window's Sleep Timer</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-external-monitor-not-detected-issue-in-windows/"><u>Fixing External Monitor Not Detected Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/future-on-display-the-premium-laptops-at-ifa-2023/"><u>Future on Display: The Premium Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/hands-on-steps-for-buying-adobe-reader-in-microsoft-store/"><u>Hands-On Steps for Buying Adobe Reader in Microsoft Store</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-tecno-pop-8-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Tecno Pop 8</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-here-are-different-ways-to-find-pokemon-go-trainer-codes-to-add-to-your-account-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, Here are Different Ways to Find Pokemon Go Trainer Codes to Add to Your Account On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-from-iphone-11-pro-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently From iPhone 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-or-minimize-windows-11-taskbar/"><u>Maximize or Minimize Windows 11 Taskbar</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/navigating-through-vlcs-recording-options-for-2024/"><u>Navigating Through VLC's Recording Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/old-meets-new-again-seven-core-windows-characteristics-evolving/"><u>Old Meets New Again: Seven Core Windows Characteristics Evolving</u></a></li>
<li><a href="https://fox-http.techidaily.com/one-device-two-os-file-migration-tactics/"><u>One Device, Two OS File Migration Tactics</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-microphone-challenges-in-counter-strike-global-offensive/"><u>Overcoming Microphone Challenges in Counter-Strike Global Offensive</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-stay-connected-eight-ways-to-enhance-win11-point/"><u>Reconnect and Stay Connected: Eight Ways to Enhance Win11' Point</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-alerts-on-desktop-applets/"><u>Restoring Alerts on Desktop Applets</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-installation-blockers-for-effective-win-11-uninstalls/"><u>Sidestep Installation Blockers for Effective Win 11 Uninstalls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frustrating-asana-issues-with-a-step-by-step-guide/"><u>Solving Frustrating Asana Issues with a Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stop-chromes-spontaneous-tab-triggers-on-windows-desktop/"><u>Stop Chrome's Spontaneous Tab Triggers on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-decrease-cpu-strain-from-tiworkerexe-processes/"><u>Strategies to Decrease CPU Strain From TiWorker.exe Processes</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-honor-magic5-ultimate-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Honor Magic5 Ultimate Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rotating-images-on-win11/"><u>The Ultimate Guide to Rotating Images on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-reactivating-lost-pin-access-in-windows-11/"><u>Troubleshooting: Reactivating Lost Pin Access in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-set-of-free-photo-screen-shifts/"><u>Ultimate Set of Free Photo Screen Shifts</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-efficient-directory-creation-with-newest-windows-oses/"><u>Unleash the Power of Efficient Directory Creation with Newest Windows OSes</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-g24-power-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on G24 Power ?</u></a></li>
<li><a href="https://win11.techidaily.com/win-wise-utorrent-speeding-up-downloads-made-simple/"><u>Win-Wise uTorrent: Speeding Up Downloads Made Simple</u></a></li>
</ul></div>
