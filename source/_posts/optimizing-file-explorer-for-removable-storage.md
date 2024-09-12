---
title: Optimizing File Explorer for Removable Storage
date: 2024-09-11T09:34:51.171Z
updated: 2024-09-12T09:34:51.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing File Explorer for Removable Storage
excerpt: This Article Describes Optimizing File Explorer for Removable Storage
keywords: Optimize Finder,Media Access Speed,Removable Drive Efficiency,Quick Search Functionality,Extra Space Utilization,Streamlined File Handling,Secure Storage Management
thumbnail: https://thmb.techidaily.com/3e64ab7fbedf01adf094c0f7a07b62ec8466f937073c7188969d1624a01e5f53.jpg
---

## Optimizing File Explorer for Removable Storage

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-livestream-titans-clash/"><u>[New] In 2024, LiveStream Titans Clash</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-vision-with-the-best-4k-monitors-1-10/"><u>[New] Optimal Vision with the Best 4K Monitors, #1-10</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-strategies-for-efficiently-configuring-facebooks-instream-ads/"><u>[New] Strategies for Efficiently Configuring Facebook's Instream Ads</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-stabilizing-aerial-cameras-choosing-a-drone-gimbal/"><u>[New] The Art of Stabilizing Aerial Cameras Choosing a Drone Gimbal</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unlimited-christmas-classics-9-films-available-for-no-charge/"><u>[New] Unlimited Christmas Classics 9 Films Available for No Charge</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-apex-of-hd-technology-leading-recorder-brands-decoded-for-2024/"><u>[Updated] Apex of HD Technology Leading Recorder Brands Decoded for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-choosing-your-best-gif-creator-a-comparative-analysis-for-2024/"><u>[Updated] Choosing Your Best GIF Creator A Comparative Analysis for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-starting-a-new-chapter-establishing-an-enterprise-ig-page/"><u>[Updated] In 2024, Starting a New Chapter Establishing an Enterprise IG Page</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-10-virtual-photo-backdrop-modifiers/"><u>2024 Approved Ideal 10 Virtual Photo Backdrop Modifiers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-m1-pro-to-m1-max-assessing-the-leap-in-apples-chip-design/"><u>2024 Approved M1 Pro to M1 Max Assessing the Leap in Apple's Chip Design</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-superior-selection-of-free-high-definition-software-for-both-oss/"><u>2024 Approved Superior Selection of Free, High-Definition Software for Both OS's</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-sony-xperia-1-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/comment-reussir-la-mise-a-jour-de-fichiers-dvd-au-format-mp3-gratuit-methode-ultime-2020/"><u>Comment Réussir La Mise À Jour De Fichiers DVD Au Format MP3 Gratuit - Méthode Ultime 2020</u></a></li>
<li><a href="https://win11.techidaily.com/discover-pro-level-video-trimming-on-your-windows-device/"><u>Discover Pro-Level Video Trimming on Your Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-hidden-treasures-of-group-policy-settings/"><u>Discover the Hidden Treasures of Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-power-down-for-idle-pcs-in-w10w11/"><u>Effortless Power-Down for Idle PCs in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-security-top-7-windows-defense-methods/"><u>Enhancing Security: Top 7 Windows Defense Methods</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-the-latest-samsung-galaxy-s21-model-less-is-more-approach-by-samsung/"><u>Evaluating the Latest Samsung Galaxy S21 Model: Less Is More Approach by Samsung</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-counteract-uninstallation-restrictions-in-windows-11/"><u>How to Counteract Uninstallation Restrictions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-0x800700e1-in-windows-11-and-11/"><u>How to Fix Error 0X800700E1 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-failed-system-call-in-windows-os/"><u>How to Overcome 'Failed System Call' In Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-notorious-office-error-0x80041015/"><u>How to Resolve the Notorious Office Error 0X80041015</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-titles-google-cardboards-most-immersive-vr-games/"><u>In 2024, Best Titles Google Cardboard's Most Immersive VR Games</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-boxing-battlegrounds-live-vs-virtual-warriors/"><u>In 2024, Boxing Battlegrounds Live VS Virtual Warriors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instant-storage-inspection-in-windows-10-and-11-through-context-menus/"><u>Instant Storage Inspection in Windows 10 & 11 Through Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-restoring-router-access/"><u>Mastering the Art of Restoring Router Access</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-how-to-add-and-custom-slack-emoji-wondershare-filmora/"><u>New 2024 Approved How to Add and Custom Slack Emoji-Wondershare Filmora</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/next-level-broadcast-software-showdown-with-obs-for-2024/"><u>Next-Level Broadcast Software Showdown with OBS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-deactivated-cooling-protocol-in-winos/"><u>Overhauling Deactivated Cooling Protocol in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-11-search-the-ultimate-guide-to-11-solutions/"><u>Overhauling Windows 11 Search: The Ultimate Guide to 11 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-alignment-on-your-monitor-overcoming-overscan/"><u>Perfect Alignment on Your Monitor: Overcoming Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/prepare-for-win11-offline-installation-guide/"><u>Prepare for Win11: Offline Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-crowded-taskbar-icons-collapse/"><u>Preventing Crowded Taskbar Icons Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unresponsive-nvidia-cp-windows-11/"><u>Quick Fixes for Unresponsive Nvidia CP, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/redefine-winterminals-background-design/"><u>Redefine WinTerminal’s Background Design</u></a></li>
<li><a href="https://win11.techidaily.com/reestablishing-sound-channels-for-xbox-microphone-in-windows-11/"><u>Reestablishing Sound Channels for Xbox Microphone in Windows 11</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/revolutionizing-paperwork-the-dawn-of-smart-document-handling/"><u>Revolutionizing Paperwork: The Dawn of Smart Document Handling</u></a></li>
<li><a href="https://win11.techidaily.com/siri-or-chatgpt-discover-what-sets-them-apart/"><u>Siri or ChatGPT? Discover What Sets Them Apart</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722998000841-star-citizen-windows-compatibility-improved-crashes-now-fixed/"><u>Star Citizen Windows Compatibility Improved, Crashes Now Fixed!</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-for-the-slow-gpsvc-loop/"><u>Step-by-Step Fix for the Slow GPSVC Loop</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-loadlibrary-failure-code-87/"><u>Steps to Correct LoadLibrary Failure Code 87</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-notes-decoded-entering-the-world-of-windows-11/"><u>Sticky Notes Decoded: Entering the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-parseerror-fixes-for-winoss/"><u>Streamlining ParseError Fixes for WinOSs</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-technicolor-turnover-desktop-color-fix-tips-for-windows/"><u>Taming the Technicolor Turnover: Desktop Color Fix Tips for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-fundamentals-of-data-protection-in-windows-notes/"><u>The Fundamentals of Data Protection in Windows Notes</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-steps-to-stop-your-flickering-mouse-pointer/"><u>The Simple Steps to Stop Your Flickering Mouse Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steams-file-permission-issue-in-win11/"><u>Troubleshooting Steam's File Permission Issue in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-potential-mastery-of-taskbar-attachments-w11/"><u>Unlock Potential: Mastery of Taskbar Attachments (W11)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-9-critical-differences-that-favor-pcs-to-macs/"><u>Unveiling 9 Critical Differences That Favor PCs to Macs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-ideal-frames-per-second-for-excellent-slow-mo-videos/"><u>Unveiling Ideal Frames Per Second For Excellent Slow-Mo Videos</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-process-for-ms-office-on-windows-1011/"><u>Unveiling the Process for MS Office on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/windows-fatal-exception-fix-code-0x8007045d/"><u>Windows Fatal Exception Fix: Code 0X8007045D</u></a></li>
<li><a href="https://win11.techidaily.com/windows-lacks-drive-letters-why-and-how-to-rectify-this-issue/"><u>Windows Lacks Drive Letters: Why and How to Rectify This Issue.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    