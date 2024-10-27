---
title: Regaining Control Over PUBG's Save Functionality (Windows)
date: 2024-10-20T04:44:03.485Z
updated: 2024-10-27T07:09:11.494Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Control Over PUBG's Save Functionality (Windows)
excerpt: This Article Describes Regaining Control Over PUBG's Save Functionality (Windows)
keywords: PUBG Save Fix,WinSaveControl,Windows SavePause,PUBGCtrlRestore,PUBGSaveRevise,GameSaveWindows,PUBGSaveOverride
thumbnail: https://thmb.techidaily.com/d885990175ebfd301b45bcb64f4157ae788a5f9cafe52f432572d6e312400466.jpg
---

## Regaining Control Over PUBG's Save Functionality (Windows)

 Many players adjust graphical, audio, and control settings in PUBG: Battlegrounds to match their preferences. However, some players have reported they can’t change settings in PUBG: Battlegrounds because it doesn’t save them. PUBG’s settings reset for those players every time they restart the game.

 This is an annoying issue. Players can still play PUBG but can’t change in-game settings when they aren’t saving. Is PUBG: Battlegrounds not saving settings for you? If so, here are five fixes you can try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Delete the GameUserSettings File

 One of the most widely confirmed solutions for PUBG not saving game settings is to delete its GameUserSettings.ini file. Deleting that configuration file will reset it, which often fixes PUBG not saving settings. Applying this potential resolution has worked for lots of players, and it could be the same for you. This is how you can delete that GameUserSettings.ini file:

1. Bring up the Run command app, which you can quickly access with the Windows logo key + R hotkey.
2. Type**%appdata%** inside Run and press**Enter** to[open Windows File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) in the AppData folder.
3. Click AppData in Explorer’s address bar to view that directory.  
![The AppData folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/appdata-folder.jpg)
4. Open the**Local** subfolder within the**AppData** directory.
5. Click the**TslGame** folder to view and open it.
6. Then open the**Saved > Config > WindowsNoEditor** folders from there.  
![The GameUserSettings.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/gameusersettings-ini-file.jpg)
7. Right-click the**GameUserSettings.ini** file and select**Delete** .
8. Launch PUBG and try changing the game settings again.

 Some PlayerUnknown’s Battleground players have also said that deselecting the Read-only option for the GameUserSettings.ini file can fix PUBG not saving. You can do that by right-clicking the GameUserSettings file and selecting**Properties** . Deselect (uncheck) the**Read-only** checkbox if it’s selected. Click**Apply > OK** to save the file’s attribute option.

## 2\. Verify the Integrity of PUBG’s Files

 Verifying game files can resolve a wide variety of gaming issues. In this case, PUBG is playable but isn’t working right because it’s not saving settings. Thus, that could be a bug verifying PUBG’s files might resolve.

![The Verify Files option in Epic Games](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/verify-files-option.jpg)

 Both Steam and the Epic Games Launcher client software with which players install PUBG include options for verifying games. Those troubleshooting options scan and repair game files. Our[guide to repairing game files](https://www.makeuseof.com/how-to-verify-game-file-integrity-different-launchers/) tells you how to verify PUBG's files in Steam and Epic Games Launcher.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable Controlled Folder Access

 Controlled folder access blocks ransomware, and other malware, from modifying files in folders. However, that feature can also stop games from saving progress and settings when it restricts their folder access. Make sure that feature isn’t causing issues for PUBG saving settings on your PC by checking and disabling its setting like this:

1. Double-click**Windows Security** (the shield icon) inside the system tray.
2. Click the**Virus & threat protection** navigation option within the Home tab.
3. Scroll down and click the**Manage ransomware protection** navigation option.  
![The Manage ransomware protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-protection-option.jpg)
4. If**Controlled folder access** is enabled, click that setting to turn it off.  
![The Controlled folder access setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access2.jpg)

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

 Now try changing the game settings in PUBG again with controlled folder access disabled. If that fix works, but you prefer controlled folder access kept on, try adding PUBG to the exclusion list.

 You can do that by clicking the**Allowed an app through Controlled folder access** option below the turned-on**Controlled folder access** setting. Click**Add an allowed app** to select the PUBG EXE file for exclusion.

## 4\. Disable Third-Party Antivirus Software

 Some third-party antivirus apps might also include a similar controlled folder access feature to the one in Windows Security. So, it’s recommended users with third-party antivirus utilities select to disable them via their system tray context menus.

 Or look through your antivirus software’s settings tabs to see if one includes a comparable controlled folder setting that restricts app access to directories and files and turn it off if it does.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall PUBG

 Reinstalling PUBG is the last resort potential fix for settings not saving if nothing else works. As PUBG is a 30-40 gigabyte game, it’s not ideal to download and reinstall it again. However, this potential resolution could fix PUBG not saving setting if caused by corrupted or missing game files. If you’re an Epic Games user, you’ll need to reinstall PUBG as follows:

1. Open Epic Games Launcher, and click its**Library** tab.
2. Click the**…** (ellipses) menu button under PUBG in your library.
3. Select the**Uninstall** menu option.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-option3.jpg)
4. Click**Uninstall** when asked to confirm.
5. After uninstalling, click**PUBG** in the**Library** tab and select**Install** to reinstall.  
![The Install option in Epic Games](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/choose-install-location.jpg)

 Steam users can select to uninstall PUBG via the Control Panel, as covered in our guide for[uninstalling software in Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After removing PUBG, select that game within Steam’s**Library** tab and click**Install** .

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528681/16446" target="_top" id="1528681">
  <img src="//a.impactradius-go.com/display-ad/16446-1528681" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528681/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Tweak PUBG’s Game Settings Again

 Applying those potential resolutions will likely fix PUBG: Battlegrounds not saving settings for most players. However, we can never promise 100 percent guaranteed solutions for everybody.

 You can submit a support request via the PUBG: Battlegrounds website if more troubleshooting guidance for fixing PUBG not saving settings is required.

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
<li><a href="https://extra-approaches.techidaily.com/new-round-table-of-angles-samsung-vs-lg-camera-debate/"><u>[New] Round Table of Angles Samsung vs LG Camera Debate</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-how-to-easily-disableremove-youtube-shorts-permanently/"><u>[Updated] 2024 Approved How to Easily Disable/Remove YouTube Shorts Permanently?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-ultimate-blueprint-for-perfecting-zooms-screen-cast/"><u>[Updated] In 2024, The Ultimate Blueprint for Perfecting Zoom's Screen Cast</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-enhancing-gamers-experience-recording-console-titles-for-pc/"><u>2024 Approved Enhancing Gamers' Experience Recording Console Titles for PC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-future-of-airflow-thermaltakes-new-120mm-and-140mm-flippable-coolers-with-superior-magnetic-force-and-a-minimalist-aesthetic-no-rgb/"><u>Discover the Future of Airflow: Thermaltake's New 120Mm & 140Mm Flippable Coolers with Superior Magnetic Force and a Minimalist Aesthetic (No RGB)</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-substitute-methods-for-the-ls-command-in-windows/"><u>Discovering Substitute Methods for the LS Command in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-enable-and-disable-iphone-recovery-mode-easily/"><u>How to Enable and Disable iPhone Recovery Mode Easily</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-bluetooth-speaker-volume-control-not-working-in-windows-11/"><u>How to Fix the Bluetooth Speaker Volume Control Not Working in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-8-plus-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 8 Plus using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://extra-resources.techidaily.com/making-avatar-creation-a-breeze-in-the-digital-realm/"><u>Making Avatar Creation a Breeze in the Digital Realm</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-update-issue-code-0x800f0845/"><u>Overcoming Update Issue: Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-no-sound-issues-with-usb-headphones-on-a-windows-7-system-guide/"><u>Resolving No-Sound Issues with USB Headphones on a Windows 7 System [Guide]</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-deletions-with-customized-context-menus-in-windows/"><u>Speed up Deletions with Customized Context Menus in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-dism-failure-0x800f082f-with-ease/"><u>Tackling Windows' DISM Failure 0X800F082F with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/why-isolating-audio-devices-may-be-a-windows-feature/"><u>Why Isolating Audio Devices May Be a Windows Feature?</u></a></li>
</ul></div>

