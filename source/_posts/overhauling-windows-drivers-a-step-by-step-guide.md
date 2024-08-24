---
title: "Overhauling Windows Drivers: A Step-by-Step Guide"
date: 2024-08-23T06:06:56.569Z
updated: 2024-08-24T06:06:56.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overhauling Windows Drivers: A Step-by-Step Guide"
excerpt: "This Article Describes Overhauling Windows Drivers: A Step-by-Step Guide"
keywords: Driver Update Guide,Windows Driver Fixing,PC Driver Repair,System Driver Overhaul,Windows Upgrade,Drivers Troubleshooting,Optimize Windows Drivers
thumbnail: https://thmb.techidaily.com/6e2f3010b64553c858c441b2aa0463f3e8a124b61c9d02d5a4f78ba177103c47.png
---

## Overhauling Windows Drivers: A Step-by-Step Guide

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

## How to Check Your Installed Drivers

 You will have drivers on your system, even if you didn't manually install them, but you may not know what they are or what version you have. There are various ways to check this.

 When you come across a date associated with a driver, this usually refers to when the driver was published, not necessarily when you installed it.

### 1\. Use Device Manager

 A user-friendly way to check drivers is through Device Manager. There are plenty of [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/); a simple method is to press **Windows key + X** and select **Device Manager**.

 This shows all your devices split by category (like **Disk drives**, **Monitors**, and **Printers**). To see a device's driver details:

1. **Double-click** a category to expand it and see the devices within.
2. **Right-click** a device and click **Properties**.
3. Click the **Driver** tab.
4. If you need more information and want to view the installed driver files, click **Driver Details**.

![device manager driver details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/device-manager-driver-details.jpg)

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Use the Manufacturer's Website

 You can also download drivers yourself through the hardware manufacturer's website. To ensure the driver is safe and the latest version, don't use any unofficial websites.

 Use one of the methods provided earlier to find out what drivers you have and which company produces them. Head to the manufacturer's website and look for the driver section (perhaps under "Downloads" or "Support"). Some providers, like AMD and NVIDIA, have tools that scan your system and detect what driver you need if you're unsure. Some also have proprietary software that keeps the driver updated and provides other functionality.

 Most drivers come as executables that update what's necessary when run. If not, use Device Manager to install them:

1. Press **Windows key + X** and select **Device Manager**.
2. **Double-click** a category to expand it and see the devices within.
3. **Right-click** a device and click **Update driver**.
4. Click **Browse my computer for drivers**.
5. Click **Browse** and navigate to the folder where you downloaded the driver.
6. Click **OK**.
7. Click **Next** and follow the wizard to completion.

![windows 10 browse for drivers on your computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-10-browse-for-drivers-on-your-computer.jpg)

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-inexpensive-pc-playback-devices-for-2024/"><u>[New] Inexpensive PC Playback Devices for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-reaction-gurus-playbook-crafting-unforgettable-videos-in-under-5-minutes-each/"><u>[New] The Reaction Guru's Playbook  Crafting Unforgettable Videos in Under 5 Minutes Each</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-celebrating-top-10-moba-play-android-edition/"><u>[Updated] 2024 Approved  Celebrating Top 10 MOBA Play  Android Edition</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-correcting-audio-absence-in-obs-recordings-quickly/"><u>[Updated] Correcting Audio Absence in OBS Recordings Quickly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-curated-list-dj-video-sources-at-your-fingertips/"><u>[Updated] In 2024, Curated List  DJ Video Sources at Your Fingertips</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-professional-gimbals-and-tripods-for-youtube-starters/"><u>[Updated] Professional Gimbals & Tripods for YouTube Starters</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-screen-snapping-on-a-mac-explained/"><u>2024 Approved  Screen Snapping on a Mac Explained</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-xc0351000-finding-the-absent-hypervisor/"><u>Correcting XC0351000: Finding the Absent Hypervisor</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-batch-execution-with-task-scheduler/"><u>Effortless Batch Execution with Task Scheduler</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/elevate-your-stream-game-mastering-onestream-platforms-for-2024/"><u>Elevate Your Stream Game  Mastering OneStream Platforms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-iis-manager-entry/"><u>Essential Tips for IIS Manager Entry</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-lowering-wlanext-cpu-usage/"><u>Essential Tips for Lowering WLANEXT CPU Usage</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-skyrocketing-your-cs-gameplay/"><u>Expert Advice on Skyrocketing Your CS Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/from-apple-to-microsoft-transition-guide-for-windows-11-via-parallels/"><u>From Apple to Microsoft: Transition Guide for Windows 11 via Parallels</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/from-ideas-to-influence-an-insider-look-at-strategic-instagram-videos-for-2024/"><u>From Ideas to Influence  An Insider Look at Strategic Instagram Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-old-extensions-to-new-ones-the-windows-way/"><u>From Old Extensions to New Ones: The Windows Way</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-eliminate-slow-boot-up-delays-in-fallout-4-top-tips-and-tricks/"><u>How to Eliminate Slow Boot-Up Delays in Fallout 4 - Top Tips & Tricks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-realme-11-proplus-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Realme 11 Pro+ Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-apple-iphone-14-how-to-unlock-a-disabled-apple-iphone-14-by-drfone-ios/"><u>In 2024, Disabled Apple iPhone 14 How to Unlock a Disabled Apple iPhone 14?</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-input-concealing-commands-in-windows-11-ui/"><u>Invisible Input: Concealing Commands in Windows 11 UI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/kinemaster-android-an-in-depth-gaming-guide-review/"><u>KineMaster Android  An In-Depth Gaming Guide Review</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-issues-for-spotify-on-windows-11/"><u>Mastering Connectivity Issues for Spotify on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-pc-control-of-your-google-home-a-comprehensive-guide/"><u>Mastering PC Control of Your Google Home: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-creation-of-targeted-user-archetypes-in-chatgpt/"><u>Mastering the Creation of Targeted User Archetypes in ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-win11s-cursor-anomalies-a-decades-insight/"><u>Mastering Win11's Cursor Anomalies: A Decade's Insight</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-uninstall-win11-microsoft-store/"><u>Methods to Uninstall Win11 Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-without-automation-time-zone-fixes-for-windows/"><u>Navigate Without Automation: Time Zone Fixes for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-file-selection-activating-filters-with-box-on-win11/"><u>Optimal File Selection: Activating Filters with Box on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-screen-darkness-problem/"><u>Overcoming Chrome's Screen Darkness Problem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-windows-11-manager-access-restoration-techniques/"><u>Overcoming Obstacles: Windows 11 Manager Access Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-stuck-at-error-e8024002e/"><u>Quick Fixes for Windows Stuck at Error E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-non-functional-windows-11-search-box-in-the-ui/"><u>Reactivating a Non-Functional Windows 11 Search Box in the UI</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-your-desktop-with-dynamic-backgrounds/"><u>Redefining Your Desktop with Dynamic Backgrounds</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-honor-x7b-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Honor X7b Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-steam-games-images-in-windows/"><u>Restoring Lost Steam Games Images in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-standard-plans-for-windows-11-battery-use/"><u>Restoring Standard Plans for Windows 11 Battery Use</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-turn-onoff-handwriting-on-windows-pcs/"><u>Step-by-Step Guide: Turn On/Off Handwriting on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-pathway-creating-personalized-pin-patterns-on-windows/"><u>The Insider's Pathway: Creating Personalized Pin Patterns on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-sticking-notebooks-front-and-center/"><u>Tips for Sticking Notebooks Front and Center</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-over-obstacles-disable-windows-11-tpm-swiftly/"><u>Triumph Over Obstacles: Disable Windows 11 TPM Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-enterprise-controlled-chromeedge-browsers-on-pcs/"><u>Troubleshooting Enterprise-Controlled Chrome/Edge Browsers on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-text-display-error-in-windows-11-resource/"><u>Troubleshooting Text Display Error in Windows 11 Resource</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-262-robloxs-solution-path/"><u>Unraveling Error 262: Roblox's Solution Path</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-online-how-to-mend-fall-guys-connection-glitches-on-pc/"><u>Winning Back Online: How to Mend Fall Guys Connection Glitches on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>