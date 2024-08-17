---
title: Finding the Absent Hypervisor - Fix for XC0351000 Error
date: 2024-08-15T23:48:34.242Z
updated: 2024-08-16T23:48:34.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Finding the Absent Hypervisor - Fix for XC0351000 Error
excerpt: This Article Describes Finding the Absent Hypervisor - Fix for XC0351000 Error
keywords: Hybrid Virtualization XC0351000 Issue,Resolving Hypervisor Disappearance,XC0351000 Fix Steps Guide,XenServer Error Handling,Diagnosing XenDesktop Glitches,Solve XC0351000 Crash,Troubleshoot Hyper-V Absence
thumbnail: https://thmb.techidaily.com/056b5dc5bf38553fc5e62980ac558058cdfef6fae043dca04e140a16eeec969f.jpg
---

## Finding the Absent Hypervisor - Fix for XC0351000 Error

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

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
## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-android-and-ios-leading-titles-mimicking-playstation-games-for-2024/"><u>[New] Android & iOS  Leading Titles Mimicking PlayStation Games for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamers-guide-to-choosing-a-video-player-vlc-vs-mpc/"><u>[New] Streamer's Guide to Choosing a Video Player  VLC Vs. MPC</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/he-complete-youtube-traffic-and-monetization-guidebook/"><u>[New] The Complete Youtube Traffic & Monetization Guidebook</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-collaborative-video-creation-and-growth-tips/"><u>[Updated] Collaborative Video Creation & Growth Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-discover-7-unforgettable-marriage-videos-on-vimeo-for-2024/"><u>[Updated] Discover 7 Unforgettable Marriage Videos on Vimeo for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-mindfulness-melodies/"><u>[Updated] Free Mindfulness Melodies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-boost-engagement-the-art-of-adding-borders-on-insta/"><u>2024 Approved  Boost Engagement  The Art of Adding Borders on Insta</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-shutterbug-secrets-iphone-night-photography/"><u>2024 Approved  Shutterbug Secrets  IPhone Night Photography</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723013104182-bypassing-launch-errors-in-borderlands-3-effective-strategies-you-can-apply-now/"><u>Bypassing Launch Errors in Borderlands 3: Effective Strategies You Can Apply Now!</u></a></li>
<li><a href="https://win11.techidaily.com/comeback-king-windows-guide-essential-13-restoration-steps/"><u>Comeback King Windows Guide: Essential 13 Restoration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-lack-of-access-for-windows-app-removal/"><u>Correcting Lack of Access for Windows App Removal</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-digital-menace-tackling-wacatacbml-in-windows-networks/"><u>Deciphering the Digital Menace: Tackling Wacatac.B!ml in Windows Networks</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-resource-consumption-handling-unrealcefsubprocess-in-windows/"><u>Decreasing Resource Consumption: Handling UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-disk-identities-c-vs-d-a-review/"><u>Demystifying Disk Identities (C vs D): A Review</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-personalized-game-recommendations-on-w11/"><u>Disabling Personalized Game Recommendations on W11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/engaging-eyesight-navigating-high-definition-tweets/"><u>Engaging Eyesight  Navigating High-Definition Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/escape-key-troubles-discover-immediate-remedies-for-your-pc/"><u>Escape Key Troubles? Discover Immediate Remedies for Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/expert-commands-locating-and-correcting-windows-errors-via-the-command-line/"><u>Expert Commands: Locating & Correcting Windows Errors via the Command Line</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-realme-v30t-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Realme V30T Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-taskbar-for-tablets-on-windows-11/"><u>How to Get the Taskbar for Tablets on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-error-code-0xc0000005-a-techs-approach/"><u>How to Overcome Error Code 0XC0000005: A Tech's Approach</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-retrieve-icon-positions/"><u>How to Swiftly Retrieve Icon Positions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-iphone-13-mini-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your iPhone 13 mini in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-store-themes-setup-and-utilization-guide/"><u>Mastering MS Store Themes: Setup & Utilization Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/maximize-wi-fi-efficiency-on-your-iphone-with-these-8-techniques/"><u>Maximize Wi-Fi Efficiency on Your iPhone with These 8 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-printer-service-not-running-issue-in-win/"><u>Overcoming Printer Service Not Running Issue in Win</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wi-fi-prompt-shortcomings-completing-missing-steps-in-windows/"><u>Overcoming Wi-Fi Prompt Shortcomings: Completing Missing Steps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-image-failure-error-0x80780119/"><u>Overcoming Windows' Image Failure: Error 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-lost-widgets-and-symbols-on-win-11-system/"><u>Reinstate Lost Widgets and Symbols on Win 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-update-a-comprehensive-guide/"><u>Reviving Windows Update: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-office-365-issue-code-30015-26/"><u>Steps to Rectify Office 365 Issue Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinstate-the-mia-dxgidll-in-windows-11/"><u>Steps to Reinstate the MIA Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-error-steams-verified-games-issue/"><u>Strategies to Address Windows Error: Steam’s Verified Games Issue</u></a></li>
<li><a href="https://win11.techidaily.com/taming-false-antivirus-alarms-a-windows-chrome-fix/"><u>Taming False Antivirus Alarms: A Windows Chrome Fix</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-affordable-solutions-for-maximizing-windows-storage-space/"><u>The Top 7 Affordable Solutions for Maximizing Windows Storage Space</u></a></li>
<li><a href="https://win11.techidaily.com/top-solutions-when-your-windows-security-is-down/"><u>Top Solutions When Your Windows Security Is Down</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-store-apps-in-windows-11/"><u>Troubleshooting Non-Functional Store Apps in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-pc-issues-resolve-constant-minecraft-dungeon-crashes/"><u>Troubleshooting PC Issues: Resolve Constant Minecraft Dungeon Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicate-your-computing-win11s-directories-guide/"><u>Uncomplicate Your Computing: Win11's Directories Guide</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-how-runtime-broker-boosts-computing-efficiency/"><u>Understanding How Runtime Broker Boosts Computing Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-local-file-transmission-google-versus-windows-strategies/"><u>Understanding Local File Transmission: Google Versus Windows Strategies</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-samsung-galaxy-s23-tactical-edition-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Samsung Galaxy S23 Tactical Edition Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-hidden-features-of-system-restore-in-win11/"><u>Unlocking the Hidden Features of System Restore in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-to-a-functional-enter-key-in-windows/"><u>Unveiling the Secrets to a Functional 'Enter' Key in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-centric-tips-for-switching-mkv-format-to-mp4/"><u>Win-Centric Tips for Switching MKV Format to MP4</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-six-routes-to-property-insight/"><u>Windows Wizardry: Six Routes to Property Insight</u></a></li>
<li><a href="https://win11.techidaily.com/write-with-confidence-using-these-win-friendly-apps/"><u>Write with Confidence Using These Win-Friendly Apps</u></a></li>
</ul></div>
