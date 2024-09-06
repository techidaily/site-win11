---
title: Techniques for Efficiently Changing Directory Visibility (Windows 11)
date: 2024-09-05T08:30:05.208Z
updated: 2024-09-06T08:30:05.208Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Efficiently Changing Directory Visibility (Windows 11)
excerpt: This Article Describes Techniques for Efficiently Changing Directory Visibility (Windows 11)
keywords: Win11 DirVisibility Change,Windows 11 Visibility Tactics,Effective Windows Update,Direct Access Control Windows,Changing Dir Visibility Tech,Efficient Dir Visibility W11,Optimizing Window Directory
thumbnail: https://thmb.techidaily.com/6d6520e192a843298c5f3fb60d79f701e9d849b7c957109090842f5892749c79.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Techniques for Efficiently Changing Directory Visibility (Windows 11)

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120863/26400?prodsku=Mercury" target="_top" id="2120863">
  <img src="//a.impactradius-go.com/display-ad/26400-2120863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120863/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123475/16836" target="_top" id="2123475">
  <img src="//a.impactradius-go.com/display-ad/16836-2123475" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123475/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

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
<li><a href="https://article-posts.techidaily.com/new-easy-guide-to-see-youtube-liked-comments/"><u>[New] Easy Guide to See YouTube Liked Comments</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-pixelpilot-w11-lightweight-screenshot-and-recording-app/"><u>[New] In 2024, PixelPilot W11  Lightweight Screenshot & Recording App</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unveiling-simple-sync-obs-plus-zoom-journey-for-2024/"><u>[New] Unveiling Simple Sync  OBS + Zoom Journey for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-maximizing-your-time-online-embracing-facebook-fully/"><u>[Updated] 2024 Approved  Maximizing Your Time Online  Embracing Facebook Fully</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-windows-desktop-snappers-guide/"><u>[Updated] 2024 Approved  Windows Desktop Snappers Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-livestreaming-sovereigns-clash/"><u>[Updated] In 2024, LiveStreaming Sovereigns Clash</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/boost-your-following-with-these-top-insta-apps-for-2024/"><u>Boost Your Following with These Top Insta Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-magic-of-devhome-in-win11-landscape/"><u>Deciphering the Magic of DevHome in Win11 Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/decrypt-windows-passwords-the-ultimate-guide-to-opening-credential-manager/"><u>Decrypt Windows Passwords: The Ultimate Guide to Opening Credential Manager</u></a></li>
<li><a href="https://extra-information.techidaily.com/detailed-discussions-via-zoom-in-ms-teams/"><u>Detailed Discussions via ZOOM in MS Teams</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-rejuvenating-faulty-usb-hubs-in-windows/"><u>Diagnosing and Rejuvenating Faulty USB Hubs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-dysfunctional-utilities-of-windows-10-fixes/"><u>Elevating Dysfunctional Utilities of Windows 10 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-gaming-experience-tackle-warhammers-stutter-problems/"><u>Enhance Your Gaming Experience - Tackle Warhammer's Stutter Problems</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-start-of-programs-despite-qt-platform-missing/"><u>Ensuring Smooth Start of Programs Despite Qt Platform Missing</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-depths-of-devhome-in-win11-world/"><u>Exploring the Depths of DevHome in Win11 World</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-crashing-virtual-machines-bsod-remedy-win11/"><u>Fixes for Crashing Virtual Machines: BSOD Remedy Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/how-to-make-a-thumbnail-for-your-youtube-free-easily-in-2024/"><u>How to Make a Thumbnail for Your YouTube Free Easily, In 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-on-apple-iphone-11-pro-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account On Apple iPhone 11 Pro?</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-to-video-exporting-and-integrating-resurrected-edb-data-into-live-exchange-environments/"><u>How-To Video: Exporting and Integrating Resurrected EDB Data Into Live Exchange Environments</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-vivo-y27-4g-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Vivo Y27 4G Phone When You Forget the Password</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-from-iphone-6-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide from iPhone 6 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-windows-ui-with-supernatural-shortcuts/"><u>Infuse Windows UI with Supernatural Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-to-attach-reminders-in-win11win10/"><u>Innovative Approaches to Attach Reminders in Win11/Win10</u></a></li>
<li><a href="https://buynow-help.techidaily.com/inside-look-at-the-tp-link-av1300-range-amplifier-a-disappointment-or-a-game-changer/"><u>Inside Look at the TP-Link AV1300 Range Amplifier: A Disappointment or a Game Changer?</u></a></li>
<li><a href="https://win11.techidaily.com/instant-guide-forcibly-disable-windows-11-print-devices/"><u>Instant Guide: Forcibly Disable Windows 11 Print Devices</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-speech-to-text-using-whisper/"><u>Instantaneous Speech-to-Text Using Whisper</u></a></li>
<li><a href="https://driver-download.techidaily.com/latest-intel-chipset-drivers-for-enhanced-performance-on-windows-1011-systems/"><u>Latest Intel Chipset Drivers for Enhanced Performance on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-of-your-operating-systems-after-win-11-installation/"><u>Maximizing Efficiency of Your Operating Systems After Win 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inadequate-video-ram-issues-in-witchcraft-and-wizardry-simulation/"><u>Mending Inadequate Video RAM Issues in Witchcraft & Wizardry Simulation</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-disruptive-javascript-error-in-discord-win-oses/"><u>Methods to Rectify Disruptive JavaScript Error in Discord Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/optimized-experience-faster-teams-slimmer-memory-use/"><u>Optimized Experience: Faster Teams, Slimmer Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-endless-enter-credential-errors-in-windows/"><u>Overcoming Endless Enter Credential Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permissions-hurdle-in-windows-application-management/"><u>Overcoming Permissions Hurdle in Windows Application Management</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-blockage/"><u>Overcoming Windows EXE Opener Blockage</u></a></li>
<li><a href="https://extra-skills.techidaily.com/practical-photoshop-fixes-for-facial-pixelation-purposes-for-2024/"><u>Practical Photoshop Fixes for Facial Pixelation Purposes for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/prime-low-cost-full-hd-cameras-for-stunts/"><u>Prime Low-Cost Full HD Cameras for Stunts</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-how-to-reactivate-a-grayed-out-secure-boot-on-windows-pcs/"><u>Regaining Control: How to Reactivate a Grayed-Out Secure Boot on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-a-computer-name-mistake-on-windows-11/"><u>Reversing a Computer Name Mistake on Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/seamless-digital-presence-top-screen-share-methods-on-social-streaming-platforms-for-2024/"><u>Seamless Digital Presence  Top Screen-Share Methods on Social Streaming Platforms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/silencing-windows-graphics-enhancements-from-geforce/"><u>Silencing Windows Graphics Enhancements From GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/solving-greyed-recycle-icon-problem-in-windows/"><u>Solving Greyed Recycle Icon Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-share-failures-in-geforce-experience/"><u>Steps to Resolve Share Failures in GeForce Experience</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-immediate-accessibility-of-software-shortcuts/"><u>Stepwise Guide to Immediate Accessibility of Software Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-and-tips-to-find-missing-game-hub/"><u>Strategies and Tips to Find Missing Game Hub</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-application-launch-problems-in-windows-11/"><u>Strategies to Overcome Application Launch Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-approach-for-restarting-your-windows-update-cycle/"><u>Systematic Approach for Restarting Your Windows Update Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/the-experts-playbook-unearthing-mac-identifiers-in-windows-11/"><u>The Expert's Playbook: Unearthing MAC Identifiers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-quick-fix-handbook-unraveling-11-windows-quirks/"><u>The Quick-Fix Handbook: Unraveling 11 Windows Quirks</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-auto-detection-failure-for-windows-network-proxies/"><u>Troubleshooting Auto Detection Failure for Windows Network Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-ps4-remote-control-re-establish-connection-issues-on-pc/"><u>Troubleshooting PS4 Remote Control: Re-Establish Connection Issues on PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ultimate-top-5-list-ps3-games-on-windows-platforms/"><u>Ultimate Top 5 List  PS3 Games on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-win11s-network-insight-through-netstat-applications/"><u>Understanding Win11's Network Insight Through Netstat Applications</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-user-profile-optimization-via-command-line/"><u>Unlocking User Profile Optimization via Command Line</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-free-flv-video-editing-solutions-top-5-recommendations/"><u>Updated 2024 Approved Free FLV Video Editing Solutions Top 5 Recommendations</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Infinix Smart 7? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/why-missing-drive-letters-happen-in-windows-solutions-explored/"><u>Why Missing Drive Letters Happen in Windows - Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pc-energy-consumption-understanding-usage-patterns/"><u>Windows PC Energy Consumption: Understanding Usage Patterns</u></a></li>
</ul></div>
