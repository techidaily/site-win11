---
title: Securely Clear Unwanted Saved Wi-Fi in Win 11
date: 2024-10-13T22:41:14.357Z
updated: 2024-10-20T23:29:53.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Clear Unwanted Saved Wi-Fi in Win 11
excerpt: This Article Describes Securely Clear Unwanted Saved Wi-Fi in Win 11
keywords: Wi-Fi Security Win11,Remove Saved Networks Win11,Secure Wi-Fi Removal Windows,Wi-Fi Erase Procedure Win11,Clear Unwanted Wi-Fi Windows 11,Safe Disconnect Saves Win11,Forget Wi-Fi Passwords Win11
thumbnail: https://thmb.techidaily.com/0be5a94dd3d4589909d5a9db46fde9f5e7dc17aa86b034cba9990542387160cd.jpg
---

## Securely Clear Unwanted Saved Wi-Fi in Win 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.

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
<li><a href="https://vp-tips.techidaily.com/new-embrace-the-brilliance-stream-create-and-revel-in-pcs-hd-video-splendor/"><u>[New] Embrace the Brilliance Stream, Create, and Revel in PC's HD Video Splendor</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-techniques-for-downloading-vimeo-media-as-mp3/"><u>[New] In 2024, Techniques for Downloading Vimeo Media as MP3</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-reduce-share-and-enjoy-top-5-shortened-urls-for-youtube/"><u>[Updated] Reduce, Share and Enjoy Top 5 Shortened URLs for YouTube</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722998260664-discord-webcam-trouble-here-are-five-ways-to-get-it-working-again/"><u>Discord Webcam Trouble? Here Are Five Ways to Get It Working Again!</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-ancient-gaming-enhancing-titles-with-retroarchs-artistry/"><u>Echoes of Ancient Gaming: Enhancing Titles with RetroArch's Artistry</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-systray-ui-adding-key-indicators-on-win11/"><u>Enhancing SysTray UI: Adding Key Indicators on Win11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-your-logitech-g90-mic-comprehensive-solutions-for-optimal-performance/"><u>Fixing Your Logitech G90 Mic: Comprehensive Solutions for Optimal Performance</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-mac-to-apple-iphone-x-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share Mac to Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-from-your-iphone-xr-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled From your iPhone XR? How to Fix</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-way-to-responsive-menu-bar-navigation/"><u>Mending Your Way to Responsive Menu Bar Navigation</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-to-resolving-problems-with-onlinevideoconvertercom-accessibility/"><u>Step-by-Step Guide to Resolving Problems with OnlineVideoConverter.com Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-tasks-on-windows-integrating-an-advanced-run-command-utility/"><u>Streamlining Tasks on Windows: Integrating an Advanced Run Command Utility</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-failure-0xa00f425d-error/"><u>Tackling Windows Camera Failure: 0XA00F425D Error</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-linux-on-windows-10-enabling-wsl/"><u>The Pathway to Linux on Windows 10: Enabling WSL</u></a></li>
<li><a href="https://win11.techidaily.com/the-voice-commander-keyboard-tricks-for-windows-11-narrator/"><u>The Voice Commander: Keyboard Tricks for Windows 11 Narrator</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-sierra-icloud-drive-integrations-and-usage-for-2024/"><u>Unlocking Sierra iCloud Drive Integrations & Usage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-the-art-of-scheduling-updates-and-downtime/"><u>Windows 11: The Art of Scheduling Updates and Downtime</u></a></li>
</ul></div>

