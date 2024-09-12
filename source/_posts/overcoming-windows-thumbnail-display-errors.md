---
title: Overcoming Windows Thumbnail Display Errors
date: 2024-09-11T09:42:28.985Z
updated: 2024-09-12T09:42:28.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Thumbnail Display Errors
excerpt: This Article Describes Overcoming Windows Thumbnail Display Errors
keywords: Fixing Win ThumbError,Resolve ThumbnailsWin,Erase ThumbnailFixWin,Eliminate Win ThumbError,Rectify ThumbnailWinIssue,Remove Windows ThumbError,Correct Win ThumbnailProblem
thumbnail: https://thmb.techidaily.com/4d4519b2feefb328b63c1d94cdbcefc1487c835a8052a017be6091c495520e05.jpg
---

## Overcoming Windows Thumbnail Display Errors

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
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
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-enable-quiet-youtube-bgplay-for-iphone-and-android/"><u>[New] 2024 Approved Enable Quiet YouTube BGPlay for iPhone & Android</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-beginning-the-live-journey-on-instagram/"><u>[New] Beginning the Live Journey on Instagram</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-simple-images-to-creative-stickers-complete-tutorial-for-chat-app-enthusiasts/"><u>[New] From Simple Images to Creative Stickers Complete Tutorial for Chat App Enthusiasts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-twisting-tales-in-photography-the-ultimate-guide-to-angled-spins-on-digital-platforms/"><u>[Updated] 2024 Approved Twisting Tales in Photography The Ultimate Guide to Angled Spins on Digital Platforms</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-dealing-with-mistakes-self-representation-during-online-chats-for-2024/"><u>[Updated] Dealing with Mistakes Self-Representation During Online Chats for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-mastering-instagram-filters-applying-them-to-old-memories-for-2024/"><u>[Updated] Mastering Instagram Filters Applying Them to Old Memories for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-navigating-the-convergence-of-obs-and-zoom-for-enhanced-streaming/"><u>2024 Approved Navigating the Convergence of OBS & Zoom for Enhanced Streaming</u></a></li>
<li><a href="https://tech-haven.techidaily.com/accessing-microsoft-bings-free-dall-e-3-features-a-comprehensive-guide/"><u>Accessing Microsoft Bing's Free DALL-E 3 Features: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatbot-evolution-premium-plan-with-chatgpt-at-20-limited-to-us/"><u>ChatBot Evolution: Premium Plan with ChatGPT at $20, Limited to US</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-11-directory-exposure/"><u>Customize Your Window's 11 Directory Exposure</u></a></li>
<li><a href="https://win11.techidaily.com/deconstructing-the-keygen-virus-symptoms-damage-and-how-to-eradicate-it-on-windows/"><u>Deconstructing the Keygen Virus: Symptoms, Damage, and How to Eradicate It on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-and-efficiency-using-a-90-degree-display-shift/"><u>Enhance Visibility & Efficiency Using a 90-Degree Display Shift</u></a></li>
<li><a href="https://win11.techidaily.com/excellence-in-organizing-top-windows-to-dos-revealed/"><u>Excellence in Organizing: Top Windows To-Dos Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-mastering-your-workflow-with-mspcm-on-w11/"><u>Expert Techniques: Mastering Your Workflow with MSPCM on W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-iphone-images-not-working-with-windows-systems/"><u>Fixes for iPhone Images Not Working with Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/free-windows-chatbot-embrace-gpt-liberation/"><u>Free Windows ChatBot: Embrace GPT Liberation</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-updated-network-adapter-drivers-tp-link-support-for-win-10-8-and-7/"><u>Get Updated Network Adapter Drivers | TP-Link Support for Win 10, 8 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/getting-rid-of-windows-11s-official-store/"><u>Getting Rid of Windows 11'S Official Store</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-a-smooth-installation-amd-installer-success/"><u>Guaranteeing a Smooth Installation: AMD Installer Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-overcome-halo-4s-ue4-catastrophic-crash-issue-update/"><u>Guide to Overcome Halo 4'S UE4 Catastrophic Crash Issue Update</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-oneplus-12r-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on OnePlus 12R? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-around-regedit-is-not-found/"><u>How to Get Around Regedit Is Not Found</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-preserve-your-custom-audio-settings-on-windows/"><u>How to Preserve Your Custom Audio Settings on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-realme-c67-5g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Realme C67 5G</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-oppo-k11-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Oppo K11 5G</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-powertoys-to-speed-up-rename-tasks/"><u>Leverage PowerToys to Speed Up Rename Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-restore-google-drive-sync-on-your-desktop/"><u>Master Plan: Restore Google Drive Sync on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-memory-metrics-for-windows-users/"><u>Mastery over Memory Metrics for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-common-rainmeter-challenges-on-pcs/"><u>Navigating the Maze of Common Rainmeter Challenges on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-barriers-for-unauthorized-software/"><u>Overcoming Windows Barriers for Unauthorized Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/professional-insights-into-androids-recording-features/"><u>Professional Insights Into Android's Recording Features</u></a></li>
<li><a href="https://win11.techidaily.com/recognize-invisible-drives-and-fix-windows-errors/"><u>Recognize Invisible Drives & Fix Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-group-policies-a-proactive-compliance-strategy/"><u>Refreshing Group Policies: A Proactive Compliance Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-windows-11-triggering-start-with-a-windows-7-code/"><u>Reigniting Windows 11: Triggering Start with a Windows 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-no-saving-problem-with-photoapp/"><u>Remedy for 'No Saving' Problem with PhotoApp</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-operational-capacity-in-flawed-usb-serial-cables-windows/"><u>Restore Operational Capacity in Flawed USB-Serial Cables, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/retro-to-revitalized-atlasos-for-old-pcs/"><u>Retro to Revitalized: AtlasOS for Old PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-crashing-resource-monitor-app-in-win11/"><u>Reviving Your Crashing Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/screenshots-secure-stow-in-windows/"><u>Screenshots' Secure Stow in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-of-vbox-in-your-windows-environment/"><u>Seamless Integration of VBox in Your Windows Environment</u></a></li>
<li><a href="https://facebook.techidaily.com/spotting-hidden-activity-on-your-pcemails/"><u>Spotting Hidden Activity on Your PC/Emails</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-alleviate-wlanextexes-power-drain/"><u>Steps to Alleviate WLANEXT.EXE's Power Drain</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-virtualbox-efail-0x80004005-glitch/"><u>Steps to Fix Windows Virtualbox E_FAIL (0X80004005) Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-avoiding-random-keypress-responses/"><u>Strategies for Avoiding Random Keypress Responses</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-development-github-desktop-and-windows-11-synergy/"><u>Streamlining Development: GitHub Desktop & Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/the-basics-of-managing-windows-11-volume-levels/"><u>The Basics of Managing Windows 11 Volume Levels</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-windows-pin-modification/"><u>The Ultimate Guide to Windows PIN Modification</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-windows-to-dos-compilation/"><u>The Ultimate Windows To-Dos Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-upgrade-top-5-tools-to-supercharge-your-pc/"><u>Turbo Upgrade: Top 5 Tools to Supercharge Your PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unlocking-mov-capture-potential-on-windows-10-for-2024/"><u>Unlocking MOV Capture Potential on Windows 10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-peak-performance-windows-11s-best-productivity-widgets/"><u>Unlocking Peak Performance: Windows 11'S Best Productivity Widgets</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-true-cost-is-riding-with-uber-cheaper-than-taking-a-cab/"><u>Unveiling the True Cost: Is Riding with Uber Cheaper than Taking a Cab?</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-microsoft-store-wont-install-an-app/"><u>What to Do If the Microsoft Store Won't Install an App</u></a></li>
<li><a href="https://win11.techidaily.com/win11-designing-hotkeys-for-audio-level-management/"><u>Win11: Designing Hotkeys for Audio Level Management</u></a></li>
<li><a href="https://win11.techidaily.com/windows-security-reboot-a-guide-to-altering-rules/"><u>Windows Security Reboot: A Guide to Altering Rules</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    