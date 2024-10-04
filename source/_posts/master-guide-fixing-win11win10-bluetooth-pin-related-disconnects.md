---
title: "Master Guide: Fixing Win11/Win10 Bluetooth PIN-Related Disconnects"
date: 2024-09-30T17:14:49.495Z
updated: 2024-10-04T04:13:53.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master Guide: Fixing Win11/Win10 Bluetooth PIN-Related Disconnects"
excerpt: "This Article Describes Master Guide: Fixing Win11/Win10 Bluetooth PIN-Related Disconnects"
keywords: Win11 Bluetooth PIN Fixed Guide,Win10 Bluetooth Connectivity Repair,Bluetooth PIN Fix in Windows 11/10,Troubleshoot Windows Bluetooth Disconnects,Secure Bluetooth PIN in W11/W10,Fixing Bluetooth PIN Failures on Win11/Win10,Steps to Resolve Win11/Win10 Bluetooth PIN Issue
thumbnail: https://thmb.techidaily.com/4622c737506cba1a23868ce6098299cf82c4724d17bc893106f7883eb3c1b7e3.jpg
---

## Master Guide: Fixing Win11/Win10 Bluetooth PIN-Related Disconnects

 The “Check the PIN” error occurs for some users when they try pairing Bluetooth devices with their Windows 11/10 PCs. When users try connecting peripherals via Settings, the Add a device window shows this message, “Check the PIN and try connecting again.” Users say that issue typically occurs when they try to re-pair devices after unpairing them.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Troubleshooter for Bluetooth

 Windows has a Bluetooth troubleshooter that can fix Bluetooth connectivity errors such as the “Check the PIN” Bluetooth error.

 You can find it listed among other troubleshooters within the Settings app. This [how-to-run Windows troubleshooters guide](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) includes instructions for opening troubleshooting tools via Settings.

![The Devices and Printers Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-a-device-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Utilize the Add a Device Wizard

 The Add a device wizard provides another way to pair Bluetooth devices with your Windows PC. Some users have said they got around the “Check the PIN” error by pairing their Bluetooth devices with that wizard. This is how you can utilize the Add a device wizard in Windows 11/10:

1. Press **Windows** key + **S**, input **Control Panel**, and click the search result that matches the keyword entered.
2. Click **Large icons** on the Control Panel’s **View by** drop-down menu.  
![The Control Panel's large icon view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-control-panel.jpg)
3. Then click **Devices and Printers** to view that applet.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Press the **Add a device** button.  
![The Devices and Printers Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-a-device-option.jpg)
5. Select your Bluetooth peripheral within the Add a device window. If you cannot see your Bluetooth device listed there, make sure it’s turned on and close enough to your PC to be discoverable.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Add a device wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-add-a-device-wizard.jpg)
6. Click **Next** to proceed with Bluetooth device pairing.
7. If prompted to input a WPS PIN, input the required device code in the text box.
8. Select **Next** to pair the Bluetooth device.

## 3\. Edit the Addrs Registry Key

 There’s also a confirmed registry tweak solution for the “Check the PIN error.” This tweak involves deleting a numeric subkey within the **Addrs** registry key. We advise you to back up the registry before attempting to apply possible fixes that involve deleting keys.

 Follow the below steps to edit the **Addrs** registry key:

1. To [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/), find that app by activating the Windows search box and inputting a **regedit** keyword. Then you can select **Registry Editor** in the search results.
2. Next, click inside the registry address box to clear the path there.
3. Input this **Addrs** registry key path in the address box:  
`HKEY_USERS\.DEFAULT\Software\Microsoft\Windows\CurrentVersion\Bluetooth\ExceptionDB\Addrs`
4. Double-click the **Addrs** key to expand it. If the **ExceptionDB** key doesn’t include an **Addrs** key in your registry, you can’t apply this potential solution.
5. Then right-click a numeric subkey within the **Addrs** key and select **Delete**. That subkey’s title will include random numbers and maybe letters also.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-registry-key-option.jpg)
6. Click **Yes** when prompted to confirm the deletion.  

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Yes confirmation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-yes-option.jpg)

## 4\. Update the Bluetooth Driver on Your PC

 Another possibility is that an old or faulty Bluetooth driver on your PC is causing the “Check the PIN” error. So, try updating your PC’s Bluetooth driver to see if that makes any difference. You can do that with the methods covered in this [guide to finding and replacing outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/).

 The most straightforward way to apply this resolution is to utilize a driver updater utility, such as Driver Booster 8\. That will show if the Bluetooth driver on your PC is outdated and provide you with an option to download and install a new one. We recommend utilizing one of the software packages from the [best free driver updaters for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/).

![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/driver-booster-software.jpg)

## Utilize Your Bluetooth Peripheral With Windows PC

 There aren’t lots of confirmed potential fixes for the “Check the PIN” error. However, the potential fixes outlined in this guide are widely confirmed to work by users who’ve needed to fix the “Check for PIN” error.

 So, maybe one might also get that error sorted on your PC, enabling you to pair and utilize your Bluetooth device again.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-skills.techidaily.com/new-the-complete-rundown-on-dji-inspire-2/"><u>[New] The Complete Rundown on DJI Inspire 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-workflow-speed-with-effective-fixes-for-excel-on-windows/"><u>Boost Workflow Speed with Effective Fixes for Excel on Windows</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-cumuluspro-standing-desk-mat-assessment-your-perfect-ergonomic-solution/"><u>Comprehensive CumulusPRO Standing Desk Mat Assessment: Your Perfect Ergonomic Solution</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-cpu-crunches-how-to-manage-windows-resource-monitor/"><u>Confronting CPU Crunches: How to Manage Windows Resource Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-update-error-0xc1900101-0x30017-in-windows-11-and-11/"><u>How to Fix the Update Error 0xC1900101 – 0X30017 in Windows 11 & 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-premiere-scenarios-in-eight-movie-types/"><u>In 2024, Premiere Scenarios in Eight Movie Types</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-crypto-conversations-with-chatgpt-10-expert-approved-prompts/"><u>Mastering Crypto Conversations with ChatGPT: 10 Expert-Approved Prompts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/redefine-viewing-premium-platforms-for-videos/"><u>Redefine Viewing Premium Platforms for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-resource-overload-how-to-cut-down-dropboxs-power-use-on-windows/"><u>Reducing Resource Overload: How to Cut Down Dropbox's Power Use on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-functionality-of-your-windows-headset-mic/"><u>Regaining Functionality of Your Windows Headset Mic</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-samsung-galaxy-m54-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Samsung Galaxy M54 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-shutdownrestart-malfunction-due-to-mischievous-windows-programs/"><u>Remedying Shutdown/Restart Malfunction Due to Mischievous Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-notifications-omission-in-windows/"><u>Resolving Notifications Omission in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-w11-app-management-a-complete-wingetuser-journey/"><u>Revolutionize Your W11 App Management: A Complete WingetUser Journey</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-unsuccessful-installation-of-v22h2-win11-update/"><u>Solutions to Unsuccessful Installation of V22H2 Win11 Update</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ng-into-youtubes-earnings-how-much-do-you-make-from-adsense-per-kv/"><u>Tapping Into Youtube's Earnings How Much Do You Make From AdSense Per KV?</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-mastering-backdrop-blur-on-w11-photo-interface/"><u>The Complete Guide to Mastering Backdrop Blur on W11 Photo Interface</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-picks-for-online-classical-tone-downloads/"><u>Top Picks for Online Classical Tone Downloads</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    