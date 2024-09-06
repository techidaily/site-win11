---
title: Deferring Windows Edge Tabs on Windows 11
date: 2024-09-05T08:30:35.727Z
updated: 2024-09-06T08:30:35.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deferring Windows Edge Tabs on Windows 11
excerpt: This Article Describes Deferring Windows Edge Tabs on Windows 11
keywords: Defer Edge Tabs,Windows 11 Delaying Tabs,Postpone Windows Tab Activation,Windows Edge Tabs Pause,Tabs Onset Deferral Win11,Windows 11 Tab Stagger,Hold Off Windows Tab Start
thumbnail: https://thmb.techidaily.com/8e847bcd25e1bb956f9c0d5ed5c3e1ee40f922a7b0a9cd027835fb97af58ec95.jpg
---

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123482/16836" target="_top" id="2123482">
  <img src="//a.impactradius-go.com/display-ad/16836-2123482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123482/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Deferring Windows Edge Tabs on Windows 11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. **Restart** your PC to apply the changes made to the registry.

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-essential-youtube-end-screen-templates-for-content-makers-for-2024/"><u>[New] Essential YouTube End Screen Templates for Content Makers for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-engaging-viewers-a-guide-to-interactive-livestreams/"><u>[New] In 2024, Engaging Viewers  A Guide to Interactive Livestreams</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-hidden-facets-of-instagram-story-consumption/"><u>[New] The Hidden Facets of Instagram Story Consumption</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-explore-the-world-of-frames-5-free-youtube-tips-for-you/"><u>[Updated] In 2024, Explore the World of Frames  5 Free YouTube Tips for You</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-chromebooks-free-screen-capture-leaders-reviewed/"><u>2024 Approved  Chromebook's Free Screen Capture Leaders Reviewed</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-what-is-the-difference-between-youtube-and-dailymotion/"><u>2024 Approved  What Is the Difference Between YouTube and Dailymotion</u></a></li>
<li><a href="https://win-answers.techidaily.com/addressing-civilization-xvi-launch-issues-under-windows-11-steps-for-a-smooth-start/"><u>Addressing Civilization XVI Launch Issues Under Windows 11 - Steps for a Smooth Start</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-magic-of-devhome-in-win11-landscape/"><u>Deciphering the Magic of DevHome in Win11 Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/decrypt-windows-passwords-the-ultimate-guide-to-opening-credential-manager/"><u>Decrypt Windows Passwords: The Ultimate Guide to Opening Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-rejuvenating-faulty-usb-hubs-in-windows/"><u>Diagnosing and Rejuvenating Faulty USB Hubs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-dysfunctional-utilities-of-windows-10-fixes/"><u>Elevating Dysfunctional Utilities of Windows 10 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-start-of-programs-despite-qt-platform-missing/"><u>Ensuring Smooth Start of Programs Despite Qt Platform Missing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/essential-10-royale-confrontations-for-2024/"><u>Essential 10 Royale Confrontations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-depths-of-devhome-in-win11-world/"><u>Exploring the Depths of DevHome in Win11 World</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-crashing-virtual-machines-bsod-remedy-win11/"><u>Fixes for Crashing Virtual Machines: BSOD Remedy Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-common-steam-errors-blocking-game-launch-on-win-11/"><u>How To Solve Common Steam Errors Blocking Game Launch on Win 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-vivo-g2-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Vivo G2 for Free? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-access-your-iphone-14-plus-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 14 Plus When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-iphone-close-up-techniques-for-photo-excellence/"><u>In 2024, Innovative iPhone Close-Up Techniques for Photo Excellence</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/incorrect-display-11-windows-should-be-full-screen/"><u>Incorrect Display: 11 Windows Should Be Full-Screen</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-speech-to-text-using-whisper/"><u>Instantaneous Speech-to-Text Using Whisper</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-ai-the-new-stand-up-artist-discovering-chatgpts-humorous-side/"><u>Is AI the New Stand-Up Artist? Discovering ChatGPT's Humorous Side</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-w11s-startup-process-for-csgo/"><u>Mastering W11's Startup Process for CS:GO</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-of-your-operating-systems-after-win-11-installation/"><u>Maximizing Efficiency of Your Operating Systems After Win 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inadequate-video-ram-issues-in-witchcraft-and-wizardry-simulation/"><u>Mending Inadequate Video RAM Issues in Witchcraft & Wizardry Simulation</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-disruptive-javascript-error-in-discord-win-oses/"><u>Methods to Rectify Disruptive JavaScript Error in Discord Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/optimized-experience-faster-teams-slimmer-memory-use/"><u>Optimized Experience: Faster Teams, Slimmer Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-endless-enter-credential-errors-in-windows/"><u>Overcoming Endless Enter Credential Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permissions-hurdle-in-windows-application-management/"><u>Overcoming Permissions Hurdle in Windows Application Management</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-huawei-nova-y91-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Huawei Nova Y91 Black and White | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-microphone-problems-for-smooth-gaming/"><u>Resolving Microphone Problems for Smooth Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11-for-a-retro-windows-98-aesthetic/"><u>Reviving Windows 11 for a Retro Windows 98 Aesthetic</u></a></li>
<li><a href="https://win11.techidaily.com/silencing-windows-graphics-enhancements-from-geforce/"><u>Silencing Windows Graphics Enhancements From GeForce</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-y02t-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo Y02T Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/sizzling-stories-whos-cooking-up-the-trends-in-2024/"><u>Sizzling Stories  Who's Cooking Up the Trends, In 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/snapdragon-x-shows-its-a-strong-contender-against-apple-silicon-qualcomms-triumph/"><u>Snapdragon X Shows It's a Strong Contender Against Apple Silicon: Qualcomm's Triumph</u></a></li>
<li><a href="https://win11.techidaily.com/solving-greyed-recycle-icon-problem-in-windows/"><u>Solving Greyed Recycle Icon Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-share-failures-in-geforce-experience/"><u>Steps to Resolve Share Failures in GeForce Experience</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-and-tips-to-find-missing-game-hub/"><u>Strategies and Tips to Find Missing Game Hub</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-application-launch-problems-in-windows-11/"><u>Strategies to Overcome Application Launch Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-experts-playbook-unearthing-mac-identifiers-in-windows-11/"><u>The Expert's Playbook: Unearthing MAC Identifiers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-quick-fix-handbook-unraveling-11-windows-quirks/"><u>The Quick-Fix Handbook: Unraveling 11 Windows Quirks</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-auto-detection-failure-for-windows-network-proxies/"><u>Troubleshooting Auto Detection Failure for Windows Network Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-ps4-remote-control-re-establish-connection-issues-on-pc/"><u>Troubleshooting PS4 Remote Control: Re-Establish Connection Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-win11s-network-insight-through-netstat-applications/"><u>Understanding Win11's Network Insight Through Netstat Applications</u></a></li>
<li><a href="https://win11.techidaily.com/why-missing-drive-letters-happen-in-windows-solutions-explored/"><u>Why Missing Drive Letters Happen in Windows - Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pc-energy-consumption-understanding-usage-patterns/"><u>Windows PC Energy Consumption: Understanding Usage Patterns</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>