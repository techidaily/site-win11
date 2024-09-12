---
title: Simplified Steps to Reset SoftwareDistribution on Windows 11
date: 2024-09-11T09:38:39.965Z
updated: 2024-09-12T09:38:39.965Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplified Steps to Reset SoftwareDistribution on Windows 11
excerpt: This Article Describes Simplified Steps to Reset SoftwareDistribution on Windows 11
keywords: Win11 Setup Guide,SoftReset Trick,Reset W11 Distro,Simple System Fix,Easy OS Reset,Windows Restore,Tech Tips
thumbnail: https://thmb.techidaily.com/3826690fad2bdad4d7aa62bd8a31b6771b07791104399fd4c0b5ca08b831fc4c.jpg
---

## Simplified Steps to Reset SoftwareDistribution on Windows 11

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  

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

![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-video-popularity-12-key-strategies-unveiled/"><u>[New] In 2024, Elevate Video Popularity 12 Key Strategies Unveiled</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-essential-steps-to-achieve-flawless-nocturnal-photography/"><u>[New] In 2024, Essential Steps to Achieve Flawless Nocturnal Photography</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-enrich-your-knowledge-student-approved-history-youtubes-to-watch/"><u>[Updated] In 2024, Enrich Your Knowledge Student-Approved History YouTubes To Watch</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-how-to-unlock-mac-with-apple-watch-sierra/"><u>[Updated] In 2024, How to Unlock Mac with Apple Watch [Sierra]</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-lightning-leap-fame-mastering-instagram-with-these-15-essential-easy-tips-for-overnight-success/"><u>[Updated] In 2024, Lightning Leap Fame Mastering Instagram with These 15 Essential, Easy Tips for Overnight Success</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transition-tunes-mastering-crossfading-in-music/"><u>[Updated] Transition Tunes Mastering Crossfading in Music</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-top-8-zero-cost-3d-vids-plugins-for-windows-and-mac-os/"><u>2024 Approved Explore Top 8 Zero-Cost 3D Vids Plugins For Windows & Mac OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-foundational-framework-engaging-in-instagram-video-talk/"><u>2024 Approved Foundational Framework Engaging in Instagram Video Talk</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bridal-bliss-filmed-alike-high-quality-8-marriage-videos-online-for-2024/"><u>Bridal Bliss Filmed Alike High-Quality 8 Marriage Videos Online for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/champions-of-cutting-edge-vr-creation/"><u>Champions of Cutting-Edge VR Creation</u></a></li>
<li><a href="https://win-solutions.techidaily.com/comprehensive-solutions-to-address-frequent-crashes-in-nioh-2-game-full-version/"><u>Comprehensive Solutions to Address Frequent Crashes in Nioh 2 Game - Full Version</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-windows-canary-vulnerability-alerts/"><u>Demystifying the Windows Canary Vulnerability Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-winning-at-ps1-on-windows-a-detailed-guide-from-duckstation/"><u>Expertly Winning at PS1 on Windows: A Detailed Guide From Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/image-editing-excellence-cutting-out-the-unwanted/"><u>Image Editing Excellence: Cutting Out the Unwanted</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-selection-of-economical-4k-projection-screens/"><u>In 2024, Ultimate Selection of Economical 4K Projection Screens</u></a></li>
<li><a href="https://win11.techidaily.com/increase-efficiency-and-control-with-advanced-wsl-2-docker-tactics/"><u>Increase Efficiency and Control with Advanced WSL 2 Docker Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-diverse-content-in-win1011-systems/"><u>Integrating Diverse Content in WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-wi-fi-secret-with-windows-settings/"><u>Keep Your Wi-Fi Secret with Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-your-gamer-goals-intact-a-guide-to-epic-saves/"><u>Keeping Your Gamer Goals Intact: A Guide to Epic Saves</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-timely-tab-prevention-for-edge-in-w11/"><u>Mastering Timely Tab Prevention for Edge in W11</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-strategy-behind-extended-updates-for-windows-11/"><u>Microsoft's Strategy Behind Extended Updates for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/minuscule-machines-small-windows-pcs/"><u>Minuscule Machines: Small Windows PCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-the-world-of-gopro-and-time-lapse-shooting/"><u>Navigating the World of GoPro and Time-Lapse Shooting</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-ultimate-dvd-conversion-guide-from-disc-to-digital/"><u>New In 2024, The Ultimate DVD Conversion Guide From Disc to Digital</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-psx-non-starting-issues-in-newest-ws11-builds/"><u>Overcoming PSX Non-Starting Issues in Newest WS11 Builds</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unity-graphical-glitches-fixed-failure-to-initialize-solutions/"><u>Overcoming Unity Graphical Glitches - Fixed Failure to Initialize Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-abrupt-game-endings-fix-tips-for-roblox-on-pc/"><u>Preventing Abrupt Game Endings: Fix Tips for Roblox on PC</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-seamless-file-downloads-in-windows-11/"><u>Re-Establishing Seamless File Downloads in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-microsoft-store-functionality-on-windows-devices/"><u>Reclaiming Microsoft Store Functionality on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-camera-not-found-on-win11-a-step-by-step-guide/"><u>Resolving Camera Not Found on Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-renewal-why-not-go-beyond-windows/"><u>Rethink Renewal: Why Not Go Beyond Windows?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/scoperto-come-comprimere-i-tuoi-file-video-in-alta-definizione-fino-al-90-senza-perdita-di-qualita/"><u>Scoperto: Come Comprimere I Tuoi File Video in Alta Definizione Fino Al 90% Senza Perdita Di Qualità!</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-a-secure-proxy-with-windows-11/"><u>Setting Up a Secure Proxy with Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-for-classic-film-aesthetics-for-2024/"><u>Step-by-Step for Classic Film Aesthetics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-loadlibrary-failure-code-87/"><u>Steps to Correct LoadLibrary Failure Code 87</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11s-camera-app-failures-error-afc/"><u>Steps to Overcome Windows 11'S Camera App Failures: Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-commands-define-wins-cli/"><u>Streamlining Your Commands: Define Win's CLI</u></a></li>
<li><a href="https://win11.techidaily.com/sudo-power-your-guide-to-windows-command-line/"><u>Sudo Power: Your Guide to Windows Command Line</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tackling-random-choppings-in-instagrams-video-streams/"><u>Tackling Random Choppings in Instagram’s Video Streams</u></a></li>
<li><a href="https://win11.techidaily.com/taming-resource-consumption-in-windows-optimizing-pcs-for-efficient-media-handling/"><u>Taming Resource Consumption in Windows: Optimizing PCs for Efficient Media Handling</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-technicolor-turnover-desktop-color-fix-tips-for-windows/"><u>Taming the Technicolor Turnover: Desktop Color Fix Tips for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-manual-for-windows-users-using-imessage/"><u>The Ultimate Manual for Windows Users: Using iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-overcome-local-security-offline-warning/"><u>Tips to Overcome Local Security Offline Warning</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-insights-in-depth-reviews-and-buying-guides/"><u>Tom's Tech Insights: In-Depth Reviews & Buying Guides</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-honor-80-pro-straight-screen-edition-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Honor 80 Pro Straight Screen Edition to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-realme-12plus-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Realme 12+ 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-read-only-reverting-in-file-systems/"><u>Troubleshooting Read-Only Reverting in File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-policies-on-windows-discover-3-vital-approaches/"><u>Unlock Policies on Windows: Discover 3 Vital Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-odbc-an-introduction-for-users/"><u>Unlock Windows ODBC: An Introduction for Users</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-methods-to-activate-cortana-in-windows/"><u>ViveTool Methods to Activate Cortana in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-gamers-secret-7-insider-moves-to-up-your-score/"><u>Win 11 Gamers' Secret: 7 Insider Moves to Up Your Score</u></a></li>
<li><a href="https://win11.techidaily.com/win-at-excel-speed-solutions-for-windows-users/"><u>Win at Excel Speed: Solutions for Windows Users</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-vistas-top-10-inspirational-yoga-videos-for-2024/"><u>Yogic Vistas Top 10 Inspirational Yoga Videos for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    