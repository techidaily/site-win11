---
title: Reclaiming Default Heat Reduction Rules in WinOS
date: 2024-08-15T23:44:03.855Z
updated: 2024-08-16T23:44:03.855Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
excerpt: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
keywords: Windows Heat Rule Reclamation,Optimize OS WinTemp,WinOS Coolness Controls,Default Temp Fixes Win,Reduce WinHeat Effectively,Thermal Settings Adjust Win,Manage WinTemperature Norm
thumbnail: https://thmb.techidaily.com/6462de374e4f489455f584c5102443a7cb28c7609933729fa2bbdde0fb2df507.jpg
---

## Reclaiming Default Heat Reduction Rules in WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://youtube-web.techidaily.com/024-approved-core-asmr-platforms-explored/"><u>[New] 2024 Approved  Core ASMR Platforms Explored</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unrestricted-story-preservation-free/"><u>[New] 2024 Approved  Unrestricted Story Preservation, FREE</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-unveiling-rokus-potential-engaging-with-facebook-live/"><u>[New] 2024 Approved  Unveiling Roku's Potential  Engaging with Facebook Live</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fix-how-to-solve-your-slow-nvidia-games-expert-tips-inside/"><u>[Quick Fix] How to Solve Your Slow Nvidia Games – Expert Tips Inside</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-htc-vive-redefining-virtual-playtime-with-unmatched-immersion/"><u>[Updated] HTC Vive  Redefining Virtual Playtime with Unmatched Immersion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-cost-effective-cumulus-vault-for-colossal-archives/"><u>[Updated] In 2024, Cost-Effective Cumulus Vault for Colossal Archives</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-mastering-igtv-hash-tagging-boosting-your-fan-base/"><u>[Updated] In 2024, Mastering IGTV Hash Tagging  Boosting Your Fan Base</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-screen-record-wizard-for-win11-enthusiasts/"><u>[Updated] In 2024, Screen Record Wizard for Win11 Enthusiasts</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-technical-treasure-trove-mastering-the-art-of-capturing-roblox-adventures-on-apple-devices/"><u>[Updated] Technical Treasure Trove  Mastering the Art of Capturing Roblox Adventures on Apple Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/10-best-classic-family-vacation-movie-for-this-summer-for-2024/"><u>10 Best Classic Family Vacation Movie for This Summer for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-filmmakers-companion-quickly-convert-any-avi-file-into-a-trendy-gif-using-filmora/"><u>2024 Approved  Filmmakers' Companion  Quickly Convert Any AVI File Into a Trendy GIF Using Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-clear-the-wallpaper-history-on-windows/"><u>3 Ways to Clear the Wallpaper History on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-windows-spotlight-images-on-the-lock-screen/"><u>3 Ways to Enable or Disable the Windows Spotlight Images on the Lock Screen</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-poco-x6-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Poco X6 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-tips-for-opening-windows-help-and-support-promptly/"><u>5 Tips for Opening Windows Help and Support Promptly</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-windows-processes-that-could-be-hiding-a-virus/"><u>7 Essential Windows Processes That Could Be Hiding a Virus</u></a></li>
<li><a href="https://win11.techidaily.com/7-exciting-additions-on-the-horizon-for-windows-11s-moment-22h2/"><u>7 Exciting Additions on the Horizon for Windows 11'S Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-google-drive-not-syncing-on-windows/"><u>7 Ways to Fix Google Drive Not Syncing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-intel-wi-fi-6-ax201-160-mhz-driver-is-not-working-error-on-windows/"><u>8 Ways to Fix “The Intel Wi-Fi 6 AX201 160 MHz Driver Is Not Working” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-vmwares-failed-to-start-the-virtual-machine-error-in-windows-11/"><u>9 Ways to Fix VMware's Failed to Start the Virtual Machine Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-chronological-study-of-the-windows-taskbar/"><u>A Chronological Study of the Windows Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-printer-administration-interface/"><u>A Comprehensive Look at Windows Printer Administration Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-judicious-use-of-ping-in-windows-operations/"><u>A Guide to Judicious Use of Ping in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/a-simple-yet-effective-guide-for-starting-a-skype-group-discussion-across-different-os-platforms/"><u>A Simple yet Effective Guide for Starting a Skype Group Discussion Across Different OS Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-and-upgrade-top-5-essentials-to-enhance-win-pcs/"><u>Accelerate and Upgrade: Top 5 Essentials to Enhance Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-outlook-performance-in-windows/"><u>Accelerate Outlook Performance in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connectivity-issues-fix-iphone-images-not-uploading-in-windows/"><u>Addressing Connectivity Issues: Fix iPhone Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-dll-issue-in-windows-810/"><u>Addressing Missing DLL Issue in Windows 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-laptop-touchpad-sensitivity-guide/"><u>Adjusting Windows 11 Laptop Touchpad Sensitivity Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-tray-graphics-windows-resource-indicators-displayed/"><u>Amplify Tray Graphics: Windows Resource Indicators Displayed</u></a></li>
<li><a href="https://win11.techidaily.com/assess-if-your-system-qualifies-for-new-windows-11/"><u>Assess if Your System Qualifies for New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-black-screen-in-windows-quick-fix-guide/"><u>Banish Black Screen in Windows - Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-error-xc0f1103f-in-windows-11-nvidias-geforce-now/"><u>Banishing Error Xc0f1103f in Windows 11, NVIDIA's GeForce Now</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-explore-4-innovative-microsoft-paint-additions/"><u>Breaking Boundaries: Explore 4 Innovative Microsoft Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/clandestine-call-collectors-discreet-voice-capture-tools-list/"><u>Clandestine Call Collectors  Discreet Voice Capture Tools List</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-samsung-device-sim-by-drfone-android/"><u>Easily Unlock Your Samsung Device SIM</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722975507764-enhancing-your-brother-device-functionality-windows-compatible-driver-upgrades-available-now/"><u>Enhancing Your Brother Device Functionality: Windows-Compatible Driver Upgrades Available Now</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-14-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone 14 Space | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-facebook-content-at-your-fingertips-best-downloader-apps-for-ios/"><u>In 2024, Facebook Content at Your Fingertips  Best Downloader Apps for iOS</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-latest-lg-360-camera-features-and-review/"><u>In 2024, Latest LG 360 Camera Features and Review</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-meme-magic-iphone-edition/"><u>In 2024, Meme Magic  IPhone Edition</u></a></li>
<li><a href="https://win11.techidaily.com/1719380925919-keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719254765561-solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-into-the-future-of-entertainment-tcls-q-and-s-class-expands-now-featuring-19-cutting-edge-models/"><u>Step Into the Future of Entertainment – TCL's Q and S Class Expands, Now Featuring 19 Cutting-Edge Models</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-compass-for-content-creators-steering-towards-viral-instagram-success-for-2024/"><u>The Compass for Content Creators  Steering Towards Viral Instagram Success for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-y77t-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo Y77t Phones</u></a></li>
<li><a href="https://common-error.techidaily.com/triumph-over-windows-11s-troublesome-error-code-0x80070541-with-our-step-by-step-solutions/"><u>Triumph Over Windows 11'S Troublesome Error Code 0X80070541 with Our Step-by-Step Solutions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-morphvox-alteration-guidebook/"><u>Ultimate MorphVOX Alteration Guidebook</u></a></li>
<li><a href="https://techidaily.com/xiaomi-mix-fold-3-can-t-play-avchd-mts-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Xiaomi Mix Fold 3 can’t play AVCHD .mts video</u></a></li>
</ul></div>
