---
title: Strategies to Reactivate Non-Operational Buttons
date: 2024-09-11T09:30:07.701Z
updated: 2024-09-12T09:30:07.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Reactivate Non-Operational Buttons
excerpt: This Article Describes Strategies to Reactivate Non-Operational Buttons
keywords: Button Reactivation Tips,Operational Buttons Strategy,Resurrecting Inactive UI Elements,Reviving Unused Interface Controls,Non-Functional Button Fixes,UI Button Rejuvenation Steps,Reactivating Dormant Interaction Tools
thumbnail: https://thmb.techidaily.com/99ddeff4dd981a34b1bf66d98e84fae1038add51e63fa5e698f7136621990952.jpg
---

## Strategies to Reactivate Non-Operational Buttons

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.

<!-- affiliate ads begin -->
<span id="1304648">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304648%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304648/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135476/26400" target="_top" id="2135476">
  <img src="//a.impactradius-go.com/display-ad/26400-2135476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135476/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cut-costs-enhance-visuals-free-banners-for-video-makers/"><u>[New] In 2024, Cut Costs, Enhance Visuals – Free Banners for Video Makers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-mastering-the-art-of-zoom-filters-for-premium-sessions-for-2024/"><u>[New] Mastering the Art of Zoom Filters for Premium Sessions for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-streamline-social-tweet-to-fb-guide/"><u>[New] Streamline Social  Tweet to FB Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-cameras-for-quality-youtube-content-for-2024/"><u>[Updated] Best Cameras for Quality YouTube Content for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-zooms-finest-audio-to-text-solutions-complimentary-and-subscriptions/"><u>[Updated] In 2024, Zoom's Finest Audio-to-Text Solutions  Complimentary & Subscriptions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-art-of-capture-and-storage-managing-snapshots-like-a-pro/"><u>2024 Approved  The Art of Capture and Storage  Managing Snapshots Like a Pro</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-huawei-nova-y91-frp-bypass-by-drfone-android/"><u>About Huawei Nova Y91 FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-0x80073cf3-in-win10win11s-marketplace/"><u>Correcting Error 0X80073CF3 in Win10/Win11's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-onedrives-reparse-point-tag-misstep-on-windows/"><u>Correcting OneDrive's Reparse Point Tag Misstep on Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/discreetly-streaming-top-8-video-tools-of-the-year-2023-for-2024/"><u>Discreetly Streaming  Top 8 Video Tools of the Year, 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gameplay-ps1-mastery-on-pc-with-duckstations-aid/"><u>Elevate Your Gameplay: PS1 Mastery on PC with Duckstation's Aid</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-desktops-on-win-11-the-drawing-guide/"><u>Enhancing Desktops on Win 11 - The Drawing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-resolving-win-os-audacity-error-code-9999/"><u>Expert Guide to Resolving Win OS Audacity Error Code: 9999</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/from-editing-to-sharing-youtube-mastery-with-adobe-premiere/"><u>From Editing to Sharing  YouTube Mastery with Adobe Premiere</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-lava-blaze-2-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Lava Blaze 2 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-a-black-background-in-wincalc/"><u>How To Activate a Black Background in WinCalc</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-samsung-galaxy-a54-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Samsung Galaxy A54 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-instantly-enabledisable-bings-assistive-chat/"><u>How to Instantly Enable/Disable Bing's Assistive Chat</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-incorrectly-identified-games-by-discord-in-windows/"><u>How to Rectify Incorrectly Identified Games by Discord in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/improving-sound-quality-for-bluetooth-headphonesspeakers/"><u>Improving Sound Quality for Bluetooth Headphones/Speakers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-step-into-the-world-of-modified-snapchat-speeches-two-simple-steps/"><u>In 2024, Step Into the World of Modified Snapchat Speeches  Two Simple Steps</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/learn-to-screen-capture-flawlessly-on-mac-using-just-keys-for-2024/"><u>Learn to Screen Capture Flawlessly on Mac Using Just Keys for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-mode-microsoft-paint-guide/"><u>Mastering Dark Mode: Microsoft Paint Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-installation-techniques-for-win11-and-workstation-17/"><u>Mastering Installation Techniques for Win11 and Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-quick-repairs-for-windows-software-glitches/"><u>Mastering Troubleshooting: Quick Repairs for Windows Software Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/mute-windows-update-announcements/"><u>Mute Windows Update Announcements</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-network-growth-strategies-for-instagram-success-for-2024/"><u>Navigating Network Growth  Strategies for Instagram Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-internet-protection-add-secure-sites-for-windows-11-users/"><u>Optimizing Internet Protection: Add Secure Sites for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-not-a-valid-user-errors-in-win1011/"><u>Overcoming 'Not a Valid User' Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sleep-suspend-with-windows-11-devices/"><u>Overcoming Sleep Suspend with Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-taskbar-buttons-display-problems/"><u>Overcoming Taskbar Buttons Display Problems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xc0000142-crash-in-win11-and-win10/"><u>Overcoming XC0000142 Crash in WIN11 & Win10</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-your-vintage-video-gaming-passion-add-achievements-via-retroarch/"><u>Reignite Your Vintage Video Gaming Passion - Add Achievements via Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-heat-flow-management-in-pcs/"><u>Restoring Missing Heat Flow Management in PCs</u></a></li>
<li><a href="https://win11.techidaily.com/spot-real-vs-ruse-unveiling-authentic-windows-apps/"><u>Spot Real Vs. Ruse: Unveiling Authentic Windows Apps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-to-downloading-the-latest-logitech-g920-drivers-for-all-windows-versions/"><u>Step-by-Step Guide to Downloading the Latest Logitech G920 Drivers for All Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-restoring-windows-11-help-functionality/"><u>Steps for Restoring Windows 11 Help Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/stop-diminished-size-of-your-windows-11-desktop-icons/"><u>Stop Diminished Size of Your Windows 11 Desktop Icons</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-voice-transmission-via-windows/"><u>Streamlining Voice Transmission via Windows</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-go-3-update-enhanced-cpu-persistent-issues/"><u>Surface Laptop Go 3 Update: Enhanced CPU, Persistent Issues</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-guide-to-youtube-seo-techniques-for-2024/"><u>The Ultimate Guide to YouTube SEO Techniques for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-limitations-why-chatgpt-falls-short-in-analyzing-cryptocurrencies/"><u>Top 5 Limitations: Why ChatGPT Falls Short in Analyzing Cryptocurrencies</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/understanding-the-value-whats-your-data-worth-the-lifespan-of-1gb/"><u>Understanding the Value: What's Your Data Worth? The Lifespan of 1GB</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-desktops-drag-dilemma-on-win11/"><u>Unlock Your Desktop's Drag Dilemma on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-full-potential-of-windows-filing-system-max-156/"><u>Unlocking the Full Potential of Window's Filing System (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/unsung-storage-issues-reviving-your-c-drives-lifespan/"><u>Unsung Storage Issues: Reviving Your C: Drive's Lifespan</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-nikon-video-workflow-efficient-editing-for-stunning-results-for-2024/"><u>Updated Nikon Video Workflow Efficient Editing for Stunning Results for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>