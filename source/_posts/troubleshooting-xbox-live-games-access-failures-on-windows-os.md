---
title: "Troubleshooting: Xbox Live Games Access Failures on Windows OS"
date: 2024-08-15T23:55:06.121Z
updated: 2024-08-16T23:55:06.121Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Xbox Live Games Access Failures on Windows OS"
excerpt: "This Article Describes Troubleshooting: Xbox Live Games Access Failures on Windows OS"
keywords: Xbox Live Fix Guide,Xbox Error Resolution,Win OS Gaming Issues,PlayStation Network Troubleshoot,Online Games Access Fail,Windows Media Streaming Game,Console Game Connectivity
thumbnail: https://thmb.techidaily.com/a270605ef2ab426a6767629ae263537bc25fdbd249dd83c4ff219886bfce5bc1.jpg
---

## Troubleshooting: Xbox Live Games Access Failures on Windows OS

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

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
## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-enhancing-visuals-the-role-of-a-tripod-in-video-content-for-2024/"><u>[New] Enhancing Visuals  The Role of a Tripod in Video Content for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-prime-5-hd-webcams-for-seamless-video-conferencing-for-2024/"><u>[New] Prime 5 HD Webcams For Seamless Video Conferencing for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-the-ultimate-guide-to-digital-audio-streaming-and-recording/"><u>[New] The Ultimate Guide to Digital Audio Streaming & Recording</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-effortless-strategies-for-facebook-stories-seamless-uploads/"><u>[Updated] In 2024, Effortless Strategies for Facebook Stories' Seamless Uploads</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-maximizing-visual-variety-with-b-roll-elements/"><u>[Updated] Maximizing Visual Variety with B Roll Elements</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-iphone-exposed-the-art-of-prolonged-photography/"><u>2024 Approved  IPhone Exposed  The Art of Prolonged Photography</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/s-exclusive-stock-images-through-vital-4-youtube-sources-for-2024/"><u>Access Exclusive Stock Images Through Vital 4 YouTube Sources for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-cmd-skills-with-these-20-must-learn-commands/"><u>Boost Your CMD Skills with These 20 Must-Learn Commands</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-pc-hardware-mismatch-in-windows-captures/"><u>Correcting PC Hardware Mismatch in Windows Captures</u></a></li>
<li><a href="https://win11.techidaily.com/dual-display-designs-crafting-individual-monitor-ambiance-in-win-1011/"><u>Dual Display Designs: Crafting Individual Monitor Ambiance in WIN 10/11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-step-by-step-guide-for-updating-intels-graphic-drivers-in-windows/"><u>Effortless Step-by-Step Guide for Updating Intel's Graphic Drivers in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-developer-setup-5-core-wsl-2-best-practices/"><u>Elevate Your Developer Setup: 5 Core WSL 2 Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/error-handling-strategies/"><u>Error Handling Strategies:</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-comic-archives-with-windows-11-interface/"><u>Exploring Comic Archives with Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-reset-account-lockout-counter-after-failed-logins-win-11-edition/"><u>Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/from-iso-to-reality-how-to-install-windows-11-arm/"><u>From ISO to Reality - How to Install Windows 11 ARM</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-unlock-your-iphone-11-learn-all-4-methods-by-drfone-ios/"><u>How Do You Unlock your iPhone 11? Learn All 4 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bridge-the-disconnect-gap-windows-11-and-printers/"><u>How to Bridge the Disconnect Gap: Windows 11 & Printers</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-the-ideal-taskbar-for-your-windows-11-tablet/"><u>Implementing the Ideal Taskbar for Your Windows 11 Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/improve-cs-global-offensive-speed-and-precision/"><u>Improve CS Global Offensive Speed and Precision</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-xiaomi-redmi-a2-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Xiaomi Redmi A2? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-windows-11-admin-interface/"><u>In-Depth Look at Windows 11 Admin Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-service-failures-fixing-steam-errors-on-windows-11/"><u>Mastery Over Service Failures: Fixing Steam Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-windows-potential-with-new-widgets/"><u>Maximize Your Window's Potential with New Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-web-with-ease-using-ms-edge-gestures-windows-11/"><u>Navigate the Web with Ease Using MS Edge Gestures (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-photo-workflow-with-keys/"><u>Optimizing Your Windows Photo Workflow with Keys</u></a></li>
<li><a href="https://win11.techidaily.com/raising-volume-on-disconnected-bt-headphonesspeakers/"><u>Raising Volume on Disconnected BT Headphones/Speakers</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-missing-phone-link-notifications-on-pc/"><u>Restoring Functionality to Missing Phone Link Notifications on PC</u></a></li>
<li><a href="https://win11.techidaily.com/solving-chrome-troubleshooting-failed-virus-alert/"><u>Solving Chrome: Troubleshooting Failed Virus Alert</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-limit-microsoft-edge-processes/"><u>Strategies to Limit Microsoft Edge Processes</u></a></li>
<li><a href="https://win11.techidaily.com/tech-convergence-ios-ipados-mac-and-windows-operating-systems-tie/"><u>Tech Convergence: IOS, iPadOS, Mac & Windows Operating Systems Tie</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-emails-adding-gmail-accounts-to-outlook-windows-style/"><u>Uniting Emails: Adding Gmail Accounts to Outlook, Windows Style</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-it-means-when-you-see-a-red-x-next-to-wi-fi-in-system-tray-icons/"><u>What It Means When You See a Red X Next to Wi-Fi in System Tray Icons</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tablets-enhancing-user-experience-with-a-taskbar/"><u>Windows 11 Tablets: Enhancing User Experience with a Taskbar</u></a></li>
</ul></div>
