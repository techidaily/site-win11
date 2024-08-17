---
title: 4 Ways to Temporarily Disable Windows Security in Windows 11
date: 2024-08-15T23:26:06.409Z
updated: 2024-08-16T23:26:06.409Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Temporarily Disable Windows Security in Windows 11
excerpt: This Article Describes 4 Ways to Temporarily Disable Windows Security in Windows 11
keywords: Disable Windows 11 Secure,Bypass Windows Security,Windows Safeguard Offset,Turnoff WinSys Protection,Temporary Security Suspend,Pause Windows Defender,Halt UWP Feature Lock
thumbnail: https://thmb.techidaily.com/a6fbcf7b87c69b74abd8f2d894637274c942b2c57ba584189354e0290ce20d66.jpg
---

## 4 Ways to Temporarily Disable Windows Security in Windows 11

 Windows Security is the built-in security app for Windows 11\. You should always keep it enabled as it protects your computer from online and offline threats. However, you may come across situations where you might need to disable it.

 Whether you want to disable it for personal preference or install an app that's facing interference by it, here's how to temporarily disable Windows Security in Windows 11.

## 1\. Temporarily Disable Windows Security Using the Settings App

 The Settings app is the central hub of Windows OS, from where you can manage important system settings. You can use it to personalize your computer, change privacy settings, update Windows, and do much more. It's also one of the places to disable Windows Security on your computer. Here's how:

1. Press the**Win + I** hotkeys to open the**Settings** app.
2. Choose**Privacy & security** from the left sidebar.
3. Click the**Open Windows** **Security** button on the right pane.  
![Open Windows Security option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/open-windows-security.jpg)
4. In the Windows Security app, choose the**Virus & threats protection** option from the left sidebar.
5. Click**Manage settings** under the Virus & threats protection section.
6. Disable the toggle under the**Real-time protection** option.  
![Disabling Real-time protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/real-time-protection.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Temporarily Disable Windows Security Using the Registry Editor

 Windows Registry is a massive database of important settings and software installed on your computer. You can access and edit that database using a built-in tool called the Registry Editor.

 The Registry Editor can also come in handy in temporarily disabling Windows Security. Here's how to do that:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Windows Security** and press Enter.
3. Select**Virus & threat protection** from the left sidebar.
4. Turn off the toggle under the**Tamper protection** option.  
![Disabling Tamper Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tamper-protection.jpg)
5. Click**Yes** to the UAC that crops up.

 Now it's time to open the Registry Editor. Check out [how to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) for steps on how to do this.

1. When the Registry Editor opens, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender`
2. Right-click on**Windows Defender** in the left sidebar and choose**Permissions.**  
![Permissions option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/permissions.jpg)
3. Click the**Advanced** options.  
![Advanced option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced.jpg)
4. Click**Change** next to the**Owner** option.
5. In the**Select User or Group window** , click the**Advanced** button.  
![Advanced option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-option.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->

1. Click the**Find Now** button and then select the admin account.  
![Find Now option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/find-now.jpg)
2. Click**OK** \>**OK** to save the changes.
3. Check the **Replace all child object permission entries with inheritable permission entries from this object** box.  
![Replace all child object permission entries with inheritable permission entries from this object box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-all-child-object-permission-entries-with-inheritable-permission-entries-from-this-object.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
4. Click**Apply** \>**OK.**
5. Next, head towards the**Permission for Windows Defender** window, and check the box next to**Full control.**  
![Full control box in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-control-box.jpg)
6. Click**Apply** \>**OK.**
7. Right-click on the blank space in the right pane, and create three**DWORD (32-bit) Value** with the following names:  
`DisableAntiVirus  

DisableAntiSpyware  

ServiceStartStates`
8. Double-click on each value, type**1** in**Value data,** and click**OK.**

Restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Temporarily Disable Windows Security Using the Local Group Policy Editor

 Another quick way to temporarily turn off Windows Security is through the Local Group Policy Editor. Here's what you need to do:

1. Open the Run dialog box, type**gpedit.msc** , and click**OK.**
2. In the Local Group Policy Editor, navigate to**Computer Configuration** \>**Administrative Templates** \>**Windows Components** \>**Microsoft Defender Antivirus** .
3. Double-click on the**Turn off Microsoft Defender Antivirus** policy.  
![Microsoft Defender Antivirus policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-defender-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
4. Click**Enabled** .  
![Enabled option in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabled-option.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click**Apply** \>**OK.**

 Once your work is done, you can enable Windows Security by choosing**Disabled** for the Turn off Microsoft Defender Antivirus policy.

## 4\. Temporarily Disable Windows Security Using Autoruns

 Autoruns is a Windows utility using which you can turn off the service responsible for starting Windows Security at startup. Before you use Autoruns, disable Tamper Protection by following the steps in method 2.

 Follow the below instructions to disable Windows Security using Autoruns:

1. To begin with,[download Autoruns](https://download.sysinternals.com/files/Autoruns.zip) on your computer.
2. Extract the downloaded file on your computer.
3. Next, boot your computer in safe mode (see [how to boot in safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) ) and then open the extracted Autoruns folder.
4. Double-click on the**Autoruns64** file and then choose**Run** from the prompt that crops up.  
![Run option for Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-option.jpg)
5. Click**Agree** in the**Autoruns Licence Agreement window** .
6. In the Autoruns window, click**Options** and uncheck**Hide Windows Entries.**  
![Hide Microsoft Entries option in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/hide-microsoft-enteries.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
7. Click**Services.**
8. Uncheck the**WinDefend** box and then close the Autoruns window.  
![Disabling WinDefend in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windefend.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

 Now, to boot in normal mode, open the**System Configuration** window, select**Normal startup,** and then**OK.**

## Stop Windows Security for a Little While on Windows 11

 The new Window Security app ensures you don't have to install a dedicated antivirus program to safeguard your computer. However, the strict policy of Windows Security can sometimes block the installation of third-party apps on your computer. Fortunately, you can disable Windows Security by following the above methods.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-simplified-approach-to-overhauling-facebook-photo-background/"><u>[New] 2024 Approved  Simplified Approach to Overhauling Facebook Photo Background</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-church-live-streaming-services-uncovered/"><u>[New] Best Church Live Streaming Services Uncovered</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-principles-of-paradoxical-intervention/"><u>[New] Principles of Paradoxical Intervention</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-seo-revolution-transforming-your-content-visibility/"><u>[Updated] 2024 Approved  SEO Revolution  Transforming Your Content Visibility</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-top-stabilizers-choosing-the-best-for-high-res-cameras/"><u>[Updated] 2024 Approved  Top Stabilizers  Choosing the Best for High-Res Cameras</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-youtube-entrepreneurship-building-a-recognizable-brand/"><u>[Updated] In 2024, YouTube Entrepreneurship  Building a Recognizable Brand</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-the-editorial-maze-answers-for-filmora-users/"><u>[Updated] Navigating the Editorial Maze  Answers for Filmora Users</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-top-10-high-quality-photography-lenses/"><u>2024 Approved  Top 10 High-Quality Photography Lenses</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-google-pixel-7a-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Google Pixel 7a PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-connectivity-the-5g-challenge/"><u>Addressing Windows 11 Connectivity: The 5G Challenge</u></a></li>
<li><a href="https://win11.techidaily.com/alert-systems-top-7-windows-processes-for-infection-scrutiny/"><u>Alert Systems: Top 7 Windows Processes for Infection Scrutiny</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-a-list-of-quick-access-techniques-for-credentials-in-win11/"><u>Break the Code: A List of Quick Access Techniques for Credentials in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-on-windows-folders-amidst-issues/"><u>Bypassing Read-Only on Windows Folders Amidst Issues</u></a></li>
<li><a href="https://youtube-web.techidaily.com/led-insights-into-youtubes-perfected-aspect-ratios/"><u>Detailed Insights Into YouTube's Perfected Aspect Ratios</u></a></li>
<li><a href="https://win-solutions.techidaily.com/diy-keyboard-troubleshooting-making-your-pathfinder-game-controls-work-again/"><u>DIY Keyboard Troubleshooting: Making Your Pathfinder Game Controls Work Again</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-tech-line-up-cards-for-4k-videography/"><u>Elite Tech Line-Up  Cards for 4K Videography</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/explainer-video-software-review-the-top-contenders-for-2024/"><u>Explainer Video Software Review The Top Contenders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/from-sealed-boxes-to-digital-realm-unlocking-windows-11-with-a-window-7-key/"><u>From Sealed Boxes to Digital Realm: Unlocking Windows 11 With a Window 7 Key</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/grasping-group-policies-in-windows-environments/"><u>Grasping Group Policies in Windows Environments</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-edgeplus-2023-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Edge+ (2023) without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ignite-your-pc-bypassing-windows-11-lag-and-latency/"><u>Ignite Your PC: Bypassing Windows 11 Lag & Latency</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-iphone-7-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass iPhone 7 Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-vivo-s18-pro-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Vivo S18 Pro Phone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-into-the-depths-mastering-gopros-time-lapse-techniques/"><u>In 2024, Into the Depths  Mastering GoPro's Time-Lapse Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/in-place-upgrade-mastery-simplify-your-transition-to-windows-11/"><u>In-Place Upgrade Mastery: Simplify Your Transition to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-guide-winning-strategies-for-selecting-best-windows-emulators/"><u>Master Guide: Winning Strategies for Selecting Best Windows Emulators</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/maximize-engagement-with-effective-scheduling-of-your-xtwitter-content-calendar/"><u>Maximize Engagement with Effective Scheduling of Your X/Twitter Content Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-non-changeable-energy-modes-in-windows-11/"><u>Navigating Non-Changeable Energy Modes in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-rated-free-mod-video-editors-the-best-for-2024/"><u>New Top-Rated Free MOD Video Editors The Best for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-experience-the-power-of-winstall-for-app-groups/"><u>Optimizing Your Windows Experience: The Power of Winstall for App Groups</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-flawed-game-detection-feature-in-discord-windows/"><u>Repairing Flawed Game Detection Feature in Discord (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-shrinking-windows-11-icons-quickly/"><u>Resolve Shrinking Windows 11 Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-the-core-of-windows-11s-problem-solving-tools/"><u>Resurrecting the Core of Windows 11'S Problem-Solving Tools</u></a></li>
<li><a href="https://win11.techidaily.com/secret-start-screen-tactics-vanish-power-buttons-from-windows-11/"><u>Secret Start Screen Tactics: Vanish Power Buttons From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-reinstate-lunar-client-after-launch-failed/"><u>Strategies to Reinstate Lunar Client After Launch Failed</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-linux-vm-setup-with-windows-and-hyper-v-integration/"><u>Streamlining Linux VM Setup with Windows and Hyper-V Integration</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-process-to-configure-pc-manager/"><u>The Complete Process to Configure PC Manager</u></a></li>
<li><a href="https://win11.techidaily.com/the-hidden-art-of-photo-transformation-in-windows/"><u>The Hidden Art of Photo Transformation in Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-search-is-over-best-sony-vegas-alternatives-for-windows-video-editors-for-2024/"><u>The Search Is Over Best Sony Vegas Alternatives for Windows Video Editors for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-ultimate-guide-to-adding-audio-content-in-fb-timeline-for-2024/"><u>The Ultimate Guide to Adding Audio Content in FB Timeline for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-text-into-talk-a-windows-11-guide/"><u>Transforming Text Into Talk: A Windows 11 Guide</u></a></li>
</ul></div>
