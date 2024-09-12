---
title: "Mastering Windows 11: Enabling Startup Services"
date: 2024-09-11T09:30:38.260Z
updated: 2024-09-12T09:30:38.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11: Enabling Startup Services"
excerpt: "This Article Describes Mastering Windows 11: Enabling Startup Services"
keywords: Win11 Startup Guide,Enable Windows 11 Boot,Startup Service Windows 11,Boot Services Windows 11,Windows 11 Services On,Configure Startup Services W11,Turn On Win11 Boot Services
thumbnail: https://thmb.techidaily.com/e7857315bad256fdc5741086fa363d0007b6f6fca6b50e61093052da5a00ac70.jpg
---

## Mastering Windows 11: Enabling Startup Services

 Leaving excess services running can drain system resources and cause your computer to appear to run slower than it actually is. Additionally, these excess resources can take up network bandwidth.

 To regain your lost speed and keep your computer running at peak shape, here's how to deactivate unnecessary startup services on Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Change Your Startup Services?

 When you install a new program on Windows it isn’t uncommon for it to set itself up as a startup service or enable other services on startup. While this might not be a bad thing, it is possible over time for a computer to become bogged down by an overabundance of services.

 If too many services are run at once, extra system resources will be taken up. This will result in slower performance that, over time, may lead to greater issues. Additionally, certain services require a constant open connection to a remote server.

 When you deactivate the services that run when your computer starts to boost your PC’s speed, you shouldn’t blindly turn them off. If you turn off a service linked to a program you commonly use it may cause the program to be slower to start, or not function at all.

 The simplest way to double-check before you shut the service off is to do a quick Google search of the service’s name when you aren’t certain. In most cases this will quickly clear up the service’s purpose, to help you determine whether it is worth it to shut it down.

## Accessing the Windows Service Manager

 The first step to deactivate any service in Windows is to access Windows Service Manager. The quickest and easiest way to do so is to use the Windows run dialog, which you can open with**Win + R** .

![The Run dialog box in Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-run-dialog.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, type in**services.msc** into the box and press**Enter** . When you do so the Windows Service Manager will immediately be pulled up. This will open a new window with every currently registered service on your computer listed.

 Alternatively, if you aren’t able to access the run dialog, you can also use the search bar in the taskbar to locate the Service Manager. Type the word**Services** into the search bar. The top result will say**Services** with an icon next to it of a pair of gears, which will open the Windows Service Manager.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Identifying the Current Startup Services

 With the service manager pulled up, you will be faced with a complete list of the services currently registered on your computer. This includes any services that the programs you use require in order to run.

![Windows Service Manager's main screen.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-service-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The list of startup services is composed of five separate columns, the service name, a description of the service, its current status, the startup type, and the user it acts as. The fourth column is the most important one for our purposes as it lists how and when the service starts.

## Changing the Status of Services

 Once you have identified one or more services that need to be deactivated, simply switch their startup type. Right-click on any service to bring up a context menu with a number of management options on it. Near the bottom, you will see an option labeled**Properties** .

![The context menu for a service in Windows Service Manager.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-service-manager-context-menu.jpg)

 Once you click it, a new window will open with the properties for the service you clicked on. Halfway down the window you will see a select box labeled**Startup Type** . This select box contains all the different startup types that a service can use.

### Service Startup Types

 There are two main types of startup types for services. Automatic indicates that the service starts up on its own when Windows starts. Manual, on the other hand, means that another program triggers this service to start. Some services, such as the[Windows Installer Service, can be enabled or disabled](https://www.makeuseof.com/enable-disable-windows-installer-service-windows/) as needed.

 Aside from Manual and Automatic, you may also see the words**Delayed Start** or**Trigger Start** in parentheses after the type. These modifiers indicate further info about the start type, however, for the purposes of deactivating startup services, they can be ignored.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Changing Startup Types

 The dropdown menu will offer several options that depend on the service selected. The three main options that will be present for all services are**Automatic** ,**Manual** , and**Disabled** .

 Set the type to**Automatic** to start the service up when Windows first boots.**Manual** will wait until an outside trigger from either a program or the user to run the service.**Disabled** will prevent the service from running. This may cause problems if the service is required by a program that you use.

 As such, don’t use**Disabled** unless you are certain that the service is unnecessary or malicious. In the event that the service will never again be needed, you can[delete the service from your Windows device](https://www.makeuseof.com/windows-11-delete-service/) altogether.

![The properties window for a service showing the service startup type dropdown.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-startup-type-dropdown.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have selected the proper startup type, click on the**Apply** button at the bottom of the screen. This saves the current setting for the service. The next time you start up your computer, the setting you have selected will be used.

### Stopping Running Services

 Once you have selected the new startup type for the service, you can determine if the service needs to be run currently. If not, you can stop the service now, without the need to restart your PC.

 Below the startup type, there is another section labeled**Service Status** . This section shows whether the service you have selected is**Running** ,**Paused** , or**Stopped** . If you want to stop the service immediately, select the button that says**Stop** in this section.

![The service status section of the properties window for a service.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-properties-status-section.jpg)

 Once the button has been pressed, Windows will attempt to gracefully shut the service down. Once terminated, it will remain deactivated until another program triggers it to run again. This is just one of the possible ways to[start or stop a service in Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/) .

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Configure Your Startup Services in Windows

 Unnecessary services that you run on your computer can drain your resources and limit network bandwidth. To keep your PC running well, periodically turn off the excess services that have been enabled by various programs.

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
<li><a href="https://youtube-data.techidaily.com/024-approved-illuminate-your-content-creation/"><u>[New] 2024 Approved Illuminate Your Content Creation</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-immediate-recording-of-facetime-conversations-made-simple/"><u>[New] 2024 Approved Immediate Recording of FaceTime Conversations Made Simple</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-the-child-prodigy-who-conquered-currency-with-content/"><u>[New] 2024 Approved The Child Prodigy Who Conquered Currency with Content</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-understanding-instagrams-video-restriction/"><u>[New] Understanding Instagram's Video Restriction</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-vocal-clarity-macs-acoustic-secrets/"><u>[New] Vocal Clarity Mac's Acoustic Secrets</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-soundscaping-stories-musical-elements-in-reels/"><u>[Updated] In 2024, Soundscaping Stories Musical Elements in Reels</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-ultimate-12-camera-guide-for-effortless-screen-swivel-use-for-2024/"><u>[Updated] The Ultimate 12 Camera Guide for Effortless Screen Swivel Use for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-screen-real-estate-win11s-best-practices/"><u>Customizing Screen Real Estate: Win11's Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-aggregatorhostexe-purpose-and-security/"><u>Demystifying Windows' AggregatorHost.exe: Purpose & Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://tech-revival.techidaily.com/expert-evaluation-of-the-plugable-usb-c-dual-hdmi-docking-hub-essential-perks-for-pc-enthusiasts/"><u>Expert Evaluation of the Plugable USB-C Dual HDMI Docking Hub: Essential Perks for PC Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-best-of-both-worlds-windows-and-games/"><u>Exploring the Best of Both Worlds: Windows & Games</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/fbx-guide-to-professional-gamers-footage-for-2024/"><u>FBX Guide to Professional Gamers' Footage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-restoring-lost-bluetooth-connectivity-in-win-11/"><u>Fix the Gap: Restoring Lost Bluetooth Connectivity in Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-xiaomi-redmi-k70-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Xiaomi Redmi K70 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-your-virtual-meetings-using-zoom-within-the-gmail-platform/"><u>In 2024, Transform Your Virtual Meetings Using Zoom Within the Gmail Platform</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-guide-to-develop-personalized-window-11-lock-patterns/"><u>In-Depth Guide to Develop Personalized Window 11 Lock Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/insights-into-microsofts-comprehensive-ai-ecosystem/"><u>Insights Into Microsoft's Comprehensive AI Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/master-naming-conventions-for-windows-files-max-156/"><u>Master Naming Conventions for Windows Files (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-protection-ranked-encryption-tools-for-windows-150-chars/"><u>Mastering Data Protection: Ranked Encryption Tools for Windows (150 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-code-fixation-in-win10win11s-shop/"><u>Mastering Error Code Fixation in Win10/Win11's Shop</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-glitches-the-top-10-tools/"><u>Mastering Windows Glitches: The Top 10 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-potential-through-efficient-use-of-law-filters/"><u>Maximizing Windows Potential Through Efficient Use of LAW Filters</u></a></li>
<li><a href="https://win11.techidaily.com/mute-to-noise-fixing-your-google-meet-mic-on-windows-pc/"><u>Mute to Noise? Fixing Your Google Meet Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winget-hurdles-on-windows-11-systems/"><u>Overcoming Winget Hurdles on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-absent-logins-in-windows-11-os/"><u>Recovering Absent Logins in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-prompt-gaps-seamless-action-integration-in-windows/"><u>Resolving Network Prompt Gaps: Seamless Action Integration in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-control-center-mastering-management-on-windows-11/"><u>Securing Your Control Center: Mastering Management on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win1011s-network-error-code-0x800704b3/"><u>Solving Win10/11's Network Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/switching-highlight-features-with-ease-in-windows-11/"><u>Switching Highlight Features with Ease in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/sync-fail-resolving-outlook-app-errors-on-pcs/"><u>Sync Fail: Resolving Outlook App Errors on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-guide-to-tackling-regular-windows-rainmeter-issues/"><u>The Insider's Guide to Tackling Regular Windows Rainmeter Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-syncing-various-bluetooth-sound-systems-with-just-one-gadget/"><u>The Ultimate Guide to Syncing Various Bluetooth Sound Systems with Just One Gadget</u></a></li>
<li><a href="https://fox-info.techidaily.com/the-ultimate-guide-to-the-best-video-speed-controller-extensions-for-2024/"><u>The Ultimate Guide to The Best Video Speed Controller Extensions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-resource-for-streamlined-navigation-windows-narrator-keybindings/"><u>The Ultimate Resource for Streamlined Navigation: Windows Narrator Keybindings</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-malfunctioning-discord-game-checker-on-windows/"><u>Tips to Rectify Malfunctioning Discord Game Checker on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-methods-to-disable-gpu-aided-prioritization-on-widno/"><u>Uncovering Methods to Disable GPU-Aided Prioritization on WIDNO</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-frozen-firewall-settings-in-windows-11/"><u>Unfreezing Frozen Firewall Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-microsoft-store-quick-sign-in-fixes/"><u>Unlocking the Microsoft Store: Quick Sign-In Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-to-flawless-steam-logins-rustwindows-edition/"><u>Unlocking the Secret to Flawless Steam Logins: Rust/Windows Edition</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-learn-video-editing-online-a-comprehensive-guide-to-downloading-and-editing/"><u>Updated In 2024, Learn Video Editing Online A Comprehensive Guide to Downloading and Editing</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tips-manage-file-explorer-folders-visibility/"><u>Windows 11 Tips: Manage File Explorer Folders Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wallpaper-guide-incorporating-spotlight-photos/"><u>Windows Wallpaper Guide: Incorporating Spotlight Photos</u></a></li>
</ul></div>

