---
title: Fixing Unresponsive Battle.net Application on Windows PC
date: 2024-12-23T17:55:25.851Z
updated: 2024-12-28T03:01:11.064Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unresponsive Battle.net Application on Windows PC
excerpt: This Article Describes Fixing Unresponsive Battle.net Application on Windows PC
keywords: Responsive Battle.net Fix,Battle.net App Sync,Win App Connectivity,BattNet Trouble Solve,Unblock Game Link,PC NetApp Issue Remediation,Windows Game Application Reconnect
thumbnail: https://thmb.techidaily.com/4820926913a4a1263a46714c8a07c6721c528103224c7dceab692252cbf067a0.jpg
---

## Fixing Unresponsive Battle.net Application on Windows PC

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
4. Select**OK** to save the new WDF options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about[allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our[Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our[guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-in-depth-study-of-video-tech-outside-manycam/"><u>[New] In 2024, In-Depth Study of Video Tech Outside ManyCam</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-easy-methods-for-downloading-vimeo-clips/"><u>[Updated] 2024 Approved Easy Methods for Downloading Vimeo Clips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-mobile-youtube-watching-iphone-and-android-edition/"><u>[Updated] Mobile YouTube Watching IPhone & Android Edition</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-secure-and-compelling-social-media-presentations-through-subtitle-sharing/"><u>[Updated] Secure and Compelling Social Media Presentations Through Subtitle Sharing</u></a></li>
<li><a href="https://blog-min.techidaily.com/1-fixing-the-issue-how-to-overcome-video-unplayable-error-224003/"><u>1. Fixing the Issue: How to Overcome 'Video Unplayable - Error 224003'</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-conversational-slides-with-powerpoints-speech-features/"><u>Crafting Conversational Slides with PowerPoint's Speech Features</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/does-your-pc-need-a-refresh-the-impact-of-updates-on-system-speed-by-yl-digital-solutions/"><u>Does Your PC Need a Refresh?: The Impact of Updates on System Speed by YL Digital Solutions</u></a></li>
<li><a href="https://program-issues.techidaily.com/god-of-war-action-packed-first-person-shooter-launches-for-pc-gamers/"><u>God of War Action-Packed First-Person Shooter Launches for PC Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activatedisable-internet-safety-filter-in-win-11/"><u>How to Activate/Disable Internet Safety Filter in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-powershell-as-admin-in-windows-11-operating-system/"><u>Initiating PowerShell as Admin in Windows 11 Operating System</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-leading-text-tracking-solutions-for-animators/"><u>New 2024 Approved Leading Text Tracking Solutions for Animators</u></a></li>
<li><a href="https://win11.techidaily.com/opt-for-windows-10-why-it-still-wins-over-win11/"><u>Opt for Windows 10: Why It Still Wins Over Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reestablish-xbox-mic-connection-on-windows-11/"><u>Steps to Reestablish Xbox Mic Connection on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-manage-non-microsoft-app-verification-in-windows/"><u>Strategies to Manage Non-Microsoft App Verification in Windows</u></a></li>
</ul></div>

