---
title: Troubleshooting Steps to Resolve Battle.net Login on PCs
date: 2024-08-15T23:44:18.304Z
updated: 2024-08-16T23:44:18.304Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Steps to Resolve Battle.net Login on PCs
excerpt: This Article Describes Troubleshooting Steps to Resolve Battle.net Login on PCs
keywords: Battle.Net Login Fix,PC Login Issue,NetLogin Troubleshoot,Game Sign In Error,Accessing BTN Network,Windows Login Problems,Steps for BTN Logon
thumbnail: https://thmb.techidaily.com/237f968e1f2378d2ca8f58711b34f30634497fa9b29838c074677a1e86056393.jpg
---

## Troubleshooting Steps to Resolve Battle.net Login on PCs

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

## 1\. Set Battle.net to Run With Admin Rights

 This is a simple potential fix for Battle.net not opening that some users have confirmed works. Setting Battle.net to run as administrator will give that software elevated system access, which can resolve permission issues. You can configure Battle.net to always run with administrative rights like this:

1. Open Battle.net’s installation directory (folder) within File Explorer.
2. Next, click the**Battle.net Launcher.exe** file with your right mouse button and select**Properties** .
3. Click**Compatibility** on the Battle.net Launcher.exe Properties window.
4. Select**Run this program as administrator** if that checkbox isn’t selected.  
![The Run this program as an administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/run-this-program-as-administrator-option.jpg)
5. Press the Properties window’s**Apply** button.

 In addition, running the software in compatibility mode might help some users fix Battle.net not opening. You can do that by selecting the**Run this program in compatibility mode** option on the same**Compatibility** tab. Choose Windows 8 on the drop-down menu.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## 2\. Delete the Battle.net and Blizzard Entertainment Data Folders

 Battle.net and Blizzard Entertainment are two cache folders for Blizzard’s game launcher software. The Battle.net software often doesn’t start right when those folders contain corrupted data. Deleting those directories will clear Battle.net’s cache.

This is how you can erase those folders in Windows 11/10:

1. First, make sure there aren’t any Battle.net background processes running by [opening Task Manager’s Process tab](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) . Disable any Battle.net processes you see there by selecting them and clicking**End task** .
2. Hold the**Windows** keyboard key and press**E** to view the Explorer file and folder manager.
3. Clear Explorer’s folder path bar, and input this directory location there: C:\\ProgramData  
![The Blizzard Entertainment folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/blizzard-entertainment-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
4. Right-click the Battle.net directory and select the**Delete** context menu option.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-delete-button.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, erase the Blizzard Entertainment folder.
6. Try opening Battle.net again.

 This should hopefully clear any cache issues and Battle.net should open correctly.

## 3\. Check the Secondary Logon Service Is Enabled

 The Secondary Logon service enables the starting of processes with alternative types of user credentials. That’s a required prerequisite service for Battle.net’s Blizzard agent. So, check Secondary Login is enabled and running like this:

1. To open Services, click the search box or magnifying glass on your Windows 11/10 taskbar. Type**services.msc** in the search box, and select the Services app.
2. Double-click**Secondary Logon** to view the properties window for that service.  
![The Secondary Logon service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/secondary-logon-service.jpg)
3. Set the**Startup type** option to**Automatic** .
4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
5. Remember to select**Apply** to save the setting.
6. Select**OK** to exit the Secondary Logon Properties window.
7. Click**Restart** on the Start menu in Windows 11/10.

 If you find Secondary Logon is already enabled, restart the service instead. Right-click Secondary Logon on the Services window to select**Restart** . Or you can click**Stop** and**Start** in the service’s properties window.

## 4\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall will block Battle.net from connecting with Blizzard services if that software isn’t permitted through it. To test if that firewall is blocking the Battle.net client, temporarily disable it in the following steps:

1. First, open WDF in the Control Panel with a method in our guide for opening the Windows Defender Firewall applet.
2. Select the**Turn Windows Defender Firewall on or off** navigation option on the left of the applet.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-defender-control-panel-applet.jpg)
3. Click the**Turn off Windows Defender Firewall** options for both the public and private network settings.  
![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
4. Select**OK** to save the new WDF options.
5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about [allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

## 5\. Disable Third-Party Antivirus and Firewall Software

 Some third-party antivirus and firewall software can also block Battle.net from running. Antivirus utilities sometimes wrongly identify legitimate programs to be malware. So, temporarily disable third-party antivirus tools or firewalls before selecting to launch Battle.net if you don’t want to uninstall anything.

 You can usually find options for disabling third-party antivirus software on their context menus. So, right-click an antivirus icon in the system tray and look for an option to disable or turn off its shield on the menu that opens. If that works, you’ll know what’s causing the issue. Whitelist Battle.net in your antivirus tool’s exclusion settings.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable the Proxy Server

 Proxy servers conflict with Battle.net’s login module, which can prevent the software from launching. Even if you can’t recall enabling a proxy server yourself, double-check the proxy server setting isn’t selected in Windows. You can disable the proxy server as follows:

1. Bring up the file and app search box in Windows.
2. Enter**inetcpl.cpl** in the Type here to search text box.
3. Select**inetcpl.cpl** to view Internet Properties.
4. Click**Connections** to access network options.
5. Next, click**LAN settings** to view a Local Area Network (LAN) window.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/LAN-settings-button.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Uncheck (deselect) the**Use a proxy server** option if its checkbox is selected.  
![The Use a proxy server checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-use-a-proxy-server-checkbox.jpg)
7. Press the**OK > Apply** buttons.

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our [Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our [guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 After setting a clean boot, restart your PC and try launching Battle.net. Did that potential resolution work? If it did, clean booting likely eliminated a program or service conflicting with Battle.net. Then you can keep the boot configuration as it is or attempt to figure out what software or service caused the issue.

## 8\. Reinstall the Battle.net Software

 Finally, reinstall Battle.net Launcher if all else fails. Reinstalling that software will replace its files and ensure you’re utilizing the latest version. That won’t uninstall games installed with Battle.net.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-programs-and-features-applet.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can remove Battle.net in Control Panel’s Programs and Features applet, as outlined in our [guide for uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After uninstalling the game launcher, open the [Battle.net desktop app](https://www.blizzard.com/en-us/apps/battle.net/desktop) download page; click**Download for Windows** on that page. Then double-click the**Battle.net-Setup.exe** file in whatever folder it downloaded to, and go through the setup wizard to install.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Enjoy Blizzard Battle.net Games Again

 When you’ve got Battle.net up and running again, you’ll be able to download, launch, and play Blizzard games. As there are many potential causes for Battle.net not starting, we can’t guarantee the solutions in this guide will resolve all startup issues for that software.

 However, those potential resolutions will address the most common causes for Battle.net not opening in Windows 11 and 10\. So, there’s a very good chance at least one will kick-start Blizzard’s gaming client on your PC.

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
<li><a href="https://vimeo-videos.techidaily.com/updated-how-to-upload-imovie-video-to-vimeo-for-2024/"><u>[Updated] How to Upload iMovie Video to Vimeo for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-funniest-memes-born-select-the-best-generators/"><u>2024 Approved  Funniest Memes Born  Select the Best Generators</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-slow-windows-excel-with-easy-fixes/"><u>Breathe Life Into Slow Windows-Excel with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-hidden-panes-6-strategies-in-win11/"><u>Breathing Life Into Hidden Panes: 6 Strategies in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-apple-maps-for-windows-operating-system/"><u>Bridging Platforms: Apple Maps for Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-for-a-non-opening-command-prompt-window/"><u>Bridging the Gap for a Non-Opening Command Prompt Window</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-integrating-gmail-with-outlook-app-for-windows/"><u>Bridging the Gap: Integrating Gmail with Outlook App for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-icons-on-windows-11-easily/"><u>Bring Back Missing Icons on Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-dormant-wastebin-icon-in-windows/"><u>Bring Back the Dormant Wastebin Icon in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forlorn-windows-apps-back-into-use/"><u>Bringing Forlorn Windows Apps Back Into Use</u></a></li>
<li><a href="https://win11.techidaily.com/building-python-applications-to-handle-file-operations-in-networks/"><u>Building Python Applications to Handle File Operations in Networks</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-non-genuine-adobe-pop-up-on-pcs/"><u>Bypass Non-Genuine Adobe Pop-Up on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-screen-locks-for-uninterrupted-presentations/"><u>Bypass Screen Locks for Uninterrupted Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-webp-conversion-modifying-images-settings-in-chrome-windows/"><u>Bypass WebP Conversion: Modifying Images Settings in Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-wi-fi-in-windows-11-a-guide-of-8-methods/"><u>Bypassing Limited Wi-Fi in Windows 11: A Guide of 8 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-zero-error-on-windows-11/"><u>Bypassing Microsoft's Zero-Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-printer-busy-on-windows-11-systems/"><u>Bypassing Printer Busy on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/can-pressing-prtscr-open-snipping-tool-how-to-block-it-on-windows-11/"><u>Can Pressing PrtScr Open Snipping Tool? How to Block It on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cease-self-scrolling-in-your-windowed-world/"><u>Cease Self-Scrolling in Your Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-windows-key-consequences-a-warning-list/"><u>Cheap Windows Key Consequences: A Warning List</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-steam-game-accomplishments/"><u>Clean Slate for Steam Game Accomplishments</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-air-solving-microphone-problems-in-microsoft-powered-meet/"><u>Clear the Air: Solving Microphone Problems in Microsoft-Powered Meet</u></a></li>
<li><a href="https://win11.techidaily.com/combat-non-mic-working-on-windows-headsets/"><u>Combat Non-Mic Working on Windows Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/combat-plan-against-windows-update-setback-code-0x800f080a/"><u>Combat Plan Against Windows Update Setback: Code 0X800f080a</u></a></li>
<li><a href="https://win11.techidaily.com/combating-app-not-uploading-issue-a-guide-to-microsofts-store/"><u>Combating App Not Uploading Issue: A Guide to Microsoft's Store</u></a></li>
<li><a href="https://extra-tips.techidaily.com/echoing-emptiness-guiding-graduated-gone-sounds-in-pp/"><u>Echoing Emptiness  Guiding Graduated Gone Sounds in PP</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-advice-how-to-easily-update-your-computers-intel-centrino-advanced-n-client-driver-6237-version/"><u>Expert Advice: How to Easily Update Your Computer's Intel Centrino Advanced-N Client Driver (6237) Version</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-with-tomtom-actioncam-new-year-for-2024/"><u>Exploring with TomTom ActionCam New Year for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-beginner-to-expert-in-using-chatgpt-best-practices-and-tips/"><u>From Beginner to Expert in Using ChatGPT: Best Practices and Tips</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-realme-c67-4g-frp-by-drfone-android/"><u>How Can We Bypass Realme C67 4G FRP?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-meizu-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Meizu</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-elite-multiplatform-recorder-for-pcs/"><u>In 2024, Elite Multiplatform Recorder for PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-vivo-y56-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Vivo Y56 5G Phone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/instagram-success-secrets-8-steps-to-becoming-a-top-poster-for-2024/"><u>Instagram Success Secrets  8 Steps to Becoming a Top Poster for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unique-hearing-solutions-from-the-forgotten-brand/"><u>Unique Hearing Solutions From the Forgotten Brand</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/your-first-steps-in-the-digital-world-course-recommendations-for-2024/"><u>Your First Steps in the Digital World  Course Recommendations for 2024</u></a></li>
</ul></div>
