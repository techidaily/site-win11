---
title: "Troubleshooting: Win PC's Issue with Non-Opening Battle.net"
date: 2024-10-24T18:15:38.121Z
updated: 2024-10-27T08:32:34.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Win PC's Issue with Non-Opening Battle.net"
excerpt: "This Article Describes Troubleshooting: Win PC's Issue with Non-Opening Battle.net"
keywords: Battle.net Login Fix,Opening Game Notebook,PC Battlenet Trouble,NetPlay Start Issues,Win Accessory Error,Networked Game Failure,Laptop Can't Connect Net
thumbnail: https://thmb.techidaily.com/c11b89b923631ed5d512ccc32ee592a5fb46939b31266627ae16098d24a9cb49.jpg
---

## Troubleshooting: Win PC's Issue with Non-Opening Battle.net

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Battle.net to Run With Admin Rights

 This is a simple potential fix for Battle.net not opening that some users have confirmed works. Setting Battle.net to run as administrator will give that software elevated system access, which can resolve permission issues. You can configure Battle.net to always run with administrative rights like this:

1. Open Battle.net’s installation directory (folder) within File Explorer.
2. Next, click the**Battle.net Launcher.exe** file with your right mouse button and select**Properties** .
3. Click**Compatibility** on the Battle.net Launcher.exe Properties window.
4. Select**Run this program as administrator** if that checkbox isn’t selected.  
![The Run this program as an administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/run-this-program-as-administrator-option.jpg)
5. Press the Properties window’s**Apply** button.

 In addition, running the software in compatibility mode might help some users fix Battle.net not opening. You can do that by selecting the**Run this program in compatibility mode** option on the same**Compatibility** tab. Choose Windows 8 on the drop-down menu.

## 2\. Delete the Battle.net and Blizzard Entertainment Data Folders

 Battle.net and Blizzard Entertainment are two cache folders for Blizzard’s game launcher software. The Battle.net software often doesn’t start right when those folders contain corrupted data. Deleting those directories will clear Battle.net’s cache.

This is how you can erase those folders in Windows 11/10:

1. First, make sure there aren’t any Battle.net background processes running by[opening Task Manager’s Process tab](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) . Disable any Battle.net processes you see there by selecting them and clicking**End task** .
2. Hold the**Windows** keyboard key and press**E** to view the Explorer file and folder manager.
3. Clear Explorer’s folder path bar, and input this directory location there: C:\\ProgramData  
![The Blizzard Entertainment folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/blizzard-entertainment-folder.jpg)
4. Right-click the Battle.net directory and select the**Delete** context menu option.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-delete-button.jpg)
5. Next, erase the Blizzard Entertainment folder.

6. Try opening Battle.net again.

 This should hopefully clear any cache issues and Battle.net should open correctly.

## 3\. Check the Secondary Logon Service Is Enabled

 The Secondary Logon service enables the starting of processes with alternative types of user credentials. That’s a required prerequisite service for Battle.net’s Blizzard agent. So, check Secondary Login is enabled and running like this:

1. To open Services, click the search box or magnifying glass on your Windows 11/10 taskbar. Type**services.msc** in the search box, and select the Services app.
2. Double-click**Secondary Logon** to view the properties window for that service.  
![The Secondary Logon service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/secondary-logon-service.jpg)
3. Set the**Startup type** option to**Automatic** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
5. Remember to select**Apply** to save the setting.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Select**OK** to exit the Secondary Logon Properties window.
7. Click**Restart** on the Start menu in Windows 11/10.

 If you find Secondary Logon is already enabled, restart the service instead. Right-click Secondary Logon on the Services window to select**Restart** . Or you can click**Stop** and**Start** in the service’s properties window.

## 4\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall will block Battle.net from connecting with Blizzard services if that software isn’t permitted through it. To test if that firewall is blocking the Battle.net client, temporarily disable it in the following steps:

1. First, open WDF in the Control Panel with a method in our guide for opening the Windows Defender Firewall applet.
2. Select the**Turn Windows Defender Firewall on or off** navigation option on the left of the applet.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-defender-control-panel-applet.jpg)
3. Click the**Turn off Windows Defender Firewall** options for both the public and private network settings.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
4. Select**OK** to save the new WDF options.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about[allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Third-Party Antivirus and Firewall Software

 Some third-party antivirus and firewall software can also block Battle.net from running. Antivirus utilities sometimes wrongly identify legitimate programs to be malware. So, temporarily disable third-party antivirus tools or firewalls before selecting to launch Battle.net if you don’t want to uninstall anything.

 You can usually find options for disabling third-party antivirus software on their context menus. So, right-click an antivirus icon in the system tray and look for an option to disable or turn off its shield on the menu that opens. If that works, you’ll know what’s causing the issue. Whitelist Battle.net in your antivirus tool’s exclusion settings.

## 6\. Disable the Proxy Server

 Proxy servers conflict with Battle.net’s login module, which can prevent the software from launching. Even if you can’t recall enabling a proxy server yourself, double-check the proxy server setting isn’t selected in Windows. You can disable the proxy server as follows:

1. Bring up the file and app search box in Windows.
2. Enter**inetcpl.cpl** in the Type here to search text box.
3. Select**inetcpl.cpl** to view Internet Properties.
4. Click**Connections** to access network options.
5. Next, click**LAN settings** to view a Local Area Network (LAN) window.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/LAN-settings-button.jpg)
6. Uncheck (deselect) the**Use a proxy server** option if its checkbox is selected.  
![The Use a proxy server checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-use-a-proxy-server-checkbox.jpg)
7. Press the**OK > Apply** buttons.

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our[Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our[guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After setting a clean boot, restart your PC and try launching Battle.net. Did that potential resolution work? If it did, clean booting likely eliminated a program or service conflicting with Battle.net. Then you can keep the boot configuration as it is or attempt to figure out what software or service caused the issue.

## 8\. Reinstall the Battle.net Software

 Finally, reinstall Battle.net Launcher if all else fails. Reinstalling that software will replace its files and ensure you’re utilizing the latest version. That won’t uninstall games installed with Battle.net.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-programs-and-features-applet.jpg)

 You can remove Battle.net in Control Panel’s Programs and Features applet, as outlined in our[guide for uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After uninstalling the game launcher, open the[Battle.net desktop app](https://www.blizzard.com/en-us/apps/battle.net/desktop) download page; click**Download for Windows** on that page. Then double-click the**Battle.net-Setup.exe** file in whatever folder it downloaded to, and go through the setup wizard to install.

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
<li><a href="https://extra-skills.techidaily.com/new-money-smart-aerial-explorers-5-best-drones-for-less-than-100/"><u>[New] Money-Smart Aerial Explorers 5 Best Drones for Less Than $100</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-shooting-the-best-sports-moments-iphone-burst-mode-for-2024/"><u>[New] Shooting the Best Sports Moments IPhone Burst Mode for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elite-channel-analyzer-top-youtube-positioning-tool/"><u>[Updated] In 2024, Elite Channel Analyzer Top YouTube Positioning Tool</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-incandescent-ideas-innovations-for-stellar-cinematography/"><u>2024 Approved Incandescent Ideas Innovations for Stellar Cinematography</u></a></li>
<li><a href="https://win11.techidaily.com/easy-strategies-for-correctly-opening-packages-on-ws11ws10/"><u>Easy Strategies for Correctly Opening Packages on WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-multi-monitor-use-with-these-windows-11-tips/"><u>Effortless Multi-Monitor Use with These Windows 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-for-repairing-system-files-in-win11/"><u>Essential Techniques for Repairing System Files in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/finding-where-your-windows-theme-is-saved/"><u>Finding Where Your Window's Theme Is Saved</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-problem-of-an-unsuccessful-discord-update-on-pcs/"><u>Fixing the Problem of an Unsuccessful Discord Update on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-hyper-v-error-0x8009030e-in-windows/"><u>How to Fix the Hyper-V Error 0X8009030E in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/is-fake-gps-location-spoofer-a-good-choice-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>Is Fake GPS Location Spoofer a Good Choice On Vivo V30 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-laptop-battery-with-simple-onoff-tweaks/"><u>Maximize Laptop Battery with Simple On/Off Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-modify-program-size-on-windows-11/"><u>Simplified Techniques to Modify Program Size on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-problem-of-inconsistent-audio-playback-in-windows-11-a-guide/"><u>Solving the Problem of Inconsistent Audio Playback in Windows 11: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/space-optimization-for-local-drives-in-windows-11-no-file-deletion-max-156-chars/"><u>Space Optimization for Local Drives in Windows 11 (No File Deletion) (Max 156 Chars)</u></a></li>
<li><a href="https://some-tips.techidaily.com/streamline-your-workflow-with-leading-tts-apps-for-mac-users-for-2024/"><u>Streamline Your Workflow with Leading TTS Apps for Mac Users for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-essence-of-sound-diminishment-a-lumafusion-insight/"><u>The Essence of Sound Diminishment A Lumafusion Insight</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-the-missing-d3d9dll-error-on-your-pc-easily/"><u>Troubleshooting the 'Missing d3d9.dll' Error on Your PC Easily</u></a></li>
</ul></div>

