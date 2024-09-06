---
title: Fix Uninstall Issues with Epic Games Hub on Windows 11
date: 2024-09-05T08:44:25.657Z
updated: 2024-09-06T08:44:25.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Uninstall Issues with Epic Games Hub on Windows 11
excerpt: This Article Describes Fix Uninstall Issues with Epic Games Hub on Windows 11
keywords: Fixing Epic Uninstall,Epic Uninstall Errors,Windows 11 Gameroom,Epic Game Studio,Repair Hub Installation,Troubleshoot Epic Games,Epic Uninstalls Issue
thumbnail: https://thmb.techidaily.com/b97d0ebad54511b61b45570cc2aa70ceb4b57e4382ef455cbbee6f6a39f5f377.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix Uninstall Issues with Epic Games Hub on Windows 11

 Are you struggling to uninstall Epic Games Launcher on Windows 11? Most of the time, there’s a background process still running so the fix should be quick and easy. However, this isn’t always the case so the classical way of uninstalling software isn’t enough to fix the problem.

 If you're facing the same issue, you don't have to worry. We’ll take a look at five methods that are worth a try when you can’t uninstall the Epic Games Launcher app.

## 1\. Close Epic Games Background Processes

 If you try to uninstall Epic Games Launcher, but Windows shows you the “Epic Games Launcher is currently running” message, there’s a background process stopping you. Even if you haven’t launched the app, its process might already run if it’s set to launch at system startup.

 However, you can easily stop the app from running in the background.

1. Right-click the **Start** button and select **Task Manager**.
2. Open the **Processes** tab.
3. Right-click **EpicGamesLauncher** and select **End Task**.  
![End Epic Game background processes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/epic-game-process-1.jpg)

 If you still can’t uninstall Epic Games Launcher, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Install and Uninstall Troubleshooter

 Windows it’s trying its best to give you the necessary troubleshooting tools for every problem you might encounter. While there’s no built-in troubleshooter to help you uninstall stubborn software, you can use [Microsoft’s Install and Uninstall Troubleshooter](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d). Here’s how you can use it after you’ve downloaded it:

1. Launch the Install and Uninstall Troubleshooter and click **Yes** in the UAC window.
2. Click **Next** **\> Uninstalling**.  
![Run the install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooter-1.jpg)
3. Choose **Epic Games Launcher** from the list of programs and click **Next**.
4. Select **Yes, try uninstall**.  
![Uninstall Epic Games using a troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooter-2.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Uninstall Epic Games Using Command Prompt

 There are [different ways to uninstall software in Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/), and most people use Control Panel to remove software. However, it might not be the best choice especially when it comes to problematic apps. So, if the classical method didn’t work, it’s time to give Command Prompt a try.

1. [Launch Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the **wmic** and press **Enter**.
3. Copy and run the **product where name="Epic Games Launcher" call uninstall** command line.
4. Confirm the action by typing **Y** and pressing **Enter**.  
![Uninstall Epic Games Launcher with Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-command-1.jpg)

 Wait for Command Prompt to uninstall the app. If it displays the **Method executions successful** message, Epic Games Launcher is now uninstalled.

## 4\. Delete Epic Games From Registry

 If the Command Prompt method didn’t work, you should delete the Epic Games Launcher entries in the Registry Editor.

1. Launching Registry Editor with administrative rights.
2. In the Registry window, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Uninstall**. Windows shows installed programs using a combination of letters and numbers, so it might be difficult to identify which one corresponds to Epic Games Launcher.
3. Click each key one at a time and check the value displayed next to **Display Name**.
4. Once you find the right key, double-click **UninstallString** from the right pane and copy the **Value data** information.
5. To uninstall Epic Games Launcher, press **Windows key + R** to bring up a Run dialog. There, paste the Registry value and click **OK**.  
![Use the Registry Editor to uninstall Epic Games Launcher](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-registry-1.jpg)

 Before editing the Registry, you should [manually create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) in case something goes wrong.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall Epic Games in Safe Mode

 If Epic Games Launcher is still doing its best to stop you from uninstalling it, there’s a chance a background process is still interfering. In this case, you should [start Windows in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). By doing so, your system will start without any additional drivers and apps that might lead to conflict.

## 6\. Use a Third-Party App

 Instead of editing the Registry or running command lines, you can have a third-party app do the job for you. If you haven’t used a similar app before, check out our guide on [the best uninstallers to remove stubborn apps in Windows](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/).

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easily Uninstall Epic Games Launcher on Windows

 Hopefully, the above tips helped you uninstall Epic Games Launcher on your computer. When Windows built-in tools are not enough to fix the problem, you could use the Install and Uninstall Troubleshooter or switch to a third-party app.

 But if you haven’t had any luck and Epic Games Launcher isn’t the only program that you can’t uninstall, it might be time to reset Windows 11\.

 If you're facing the same issue, you don't have to worry. We’ll take a look at five methods that are worth a try when you can’t uninstall the Epic Games Launcher app.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-bridging-gap-integrating-zoom-into-your-gmail-setup/"><u>[New] 2024 Approved  Bridging Gap  Integrating Zoom Into Your Gmail Setup</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-complete-checklist-for-internet-broadcast-preservation/"><u>[New] The Complete Checklist for Internet Broadcast Preservation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-heart-of-video-magic-10-key-edits-in-filmora/"><u>[New] The Heart of Video Magic  10 Key Edits in Filmora</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/hat-is-mukbang-and-how-to-make-mukbang-videos-for-2024/"><u>[New] What Is Mukbang and How to Make Mukbang Videos for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-beyond-the-basics-streamlabs-competitors-analyzed/"><u>[Updated] 2024 Approved  Beyond the Basics  Streamlabs Competitors Analyzed</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-examining-video-sharing-platforms-the-vimeo-and-youtube-divide/"><u>[Updated] 2024 Approved  Examining Video Sharing Platforms  The Vimeo & YouTube Divide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-hidden-gems-premium-mac-speech-to-text-tools/"><u>[Updated] In 2024, Hidden Gems  Premium Mac Speech-to-Text Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perplexing-perspective-shifts-in-instagram-video-feeds/"><u>[Updated] Perplexing Perspective Shifts in Instagram Video Feeds</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-follow-the-flow-of-forum-fancies/"><u>2024 Approved  Follow the Flow of Forum Fancies</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-recording-skype-meetings-on-modern-operating-systems/"><u>2024 Approved  Recording Skype Meetings on Modern Operating Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-soundscapes-startups-the-best-10-music-pieces-for-podcast-intros/"><u>2024 Approved  Soundscapes Startups  The Best 10 Music Pieces for Podcast Intros</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-to-avi-tutorial-plus-8-best-youtube-to-avi-converters/"><u>2024 Approved  YouTube to AVI  Tutorial + 8 Best YouTube to AVI Converters</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-zoom-for-the-first-timer-easy-to-follow-guidelines/"><u>2024 Approved  Zoom for the First Timer  Easy-to-Follow Guidelines</u></a></li>
<li><a href="https://win-blog.techidaily.com/6-steps-to-bypass-palworlds-eos-login-hurdle-quick-fix-techniques-revealed/"><u>6 Steps to Bypass PalWorld's EOS Login Hurdle: Quick Fix Techniques Revealed</u></a></li>
<li><a href="https://games-able.techidaily.com/6-ways-to-use-chatgpt-as-a-video-game-scriptwriter/"><u>6 Ways to Use ChatGPT as a Video Game Scriptwriter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-drones-leap-into-clarity-q500-reviewed/"><u>A Drone's Leap Into Clarity - Q500 Reviewed</u></a></li>
<li><a href="https://article-files.techidaily.com/bringing-out-the-best-advanced-color-correction-in-gopro-for-2024/"><u>Bringing Out the Best  Advanced Color Correction in GoPro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/does-pressing-prtscr-start-snipping-tool-on-win-11-trick-to-block-it/"><u>Does Pressing PrtScr Start Snipping Tool on Win 11? Trick to Block It</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-for-documenting-user-account-control-messages/"><u>Easy Steps for Documenting User Account Control Messages</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-ide-speed-and-productivity-for-developers-on-windows/"><u>Enhancing IDE Speed & Productivity for Developers on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-overcoming-in-game-lags-in-world-of-warcraft/"><u>Expert Tips for Overcoming In-Game Lags in World of Warcraft</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-top-8-win11-choices-for-professional-videoscripting/"><u>Explore the Top 8 Win11 Choices for Professional Videoscripting</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/finns-fortune-flux-earnings-examination/"><u>Finn's Fortune Flux  Earnings Examination</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zero-x-error-in-windows-11s-mail-application/"><u>Fixing Zero X Error in Windows 11'S Mail Application</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-logitech-k400-plus-driver-updates-instantly-no-cost/"><u>Get the Latest Logitech K400 Plus Driver Updates Instantly – No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-successful-or-failed-login-attempts-on-your-windows-computer/"><u>How to Check Successful or Failed Login Attempts on Your Windows Computer</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/how-to-do-screen-recording-on-iphone-easily-for-2024/"><u>How to Do Screen Recording on Iphone Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-discords-cannot-resize-gif-error-on-windows-11/"><u>How to Fix Discord's Cannot Resize GIF Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-merge-adjacent-and-non-adjacent-partitions-in-windows/"><u>How to Merge Adjacent and Non-Adjacent Partitions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reconnect-disconnected-file-apps-in-windows/"><u>How to Reconnect Disconnected File Apps in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-15-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone 15 Lock Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-recurring-restart-problems-in-windows-11-effortlessly/"><u>How to Resolve Recurring Restart Problems in Windows 11 Effortlessly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-realme-c55-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Realme C55 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-lava-blaze-2-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Lava Blaze 2 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-full-guide-to-facebook-algorithm-change-are-you-ready/"><u>In 2024, Full Guide to Facebook Algorithm Change   Are You Ready？</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-hire-harmony-a-collection-of-inspirational-clips/"><u>In 2024, Hire Harmony  A Collection of Inspirational Clips</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-visual-storytelling-of-pc-playtime-top-6-screenshot-secrets/"><u>In 2024, Visual Storytelling of PC Playtime - Top 6 Screenshot Secrets</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-geforce-rtx-3070-drivers-for-windows-11-and-windows-10-get-your-download-now/"><u>Latest GeForce RTX 3070 Drivers for Windows 11 and Windows 10 – Get Your Download Now!</u></a></li>
<li><a href="https://win11.techidaily.com/low-ram-and-cpu-consumption-choosing-the-best-browser-across-operating-systems/"><u>Low RAM & CPU Consumption: Choosing the Best Browser Across Operating Systems</u></a></li>
<li><a href="https://extra-information.techidaily.com/master-videoleap-to-capture-up-close-footage/"><u>Master Videoleap to Capture Up-Close Footage</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-bloatware-removal-in-windows-11/"><u>Mastering Bloatware Removal in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-microsofts-phone-link-app-explained/"><u>Mastering Connectivity: Microsoft’s Phone Link App Explained</u></a></li>
<li><a href="https://fox-helps.techidaily.com/mastering-live-undo-on-twitch-essential-tips-and-strategies-for-2024/"><u>Mastering Live Undo on Twitch  Essential Tips and Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-transparency-on-windows-11-machines/"><u>Maximizing Window Transparency on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-game-pass-issues-on-windows-os/"><u>Methods to Rectify Game Pass Issues on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-modifying-network-address-translation-in-wins-oses/"><u>Navigating and Modifying Network Address Translation in Wins OSes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-restore-on-windows-for-past-fixes/"><u>Navigating System Restore on Windows for Past Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-flawed-menu-navigation-in-windows-desktops/"><u>Overcoming Flawed Menu Navigation in Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-overcoming-xbox-game-pass-warzones-directx-issues/"><u>Quick Fixes for Overcoming Xbox Game Pass Warzone's DirectX Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solution-conquer-camera-fails-in-windows-os/"><u>Quick Solution: Conquer Camera Fails in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-reconnecting-distant-devices-in-windows/"><u>Regaining Control: Reconnecting Distant Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-cyber-travel-mastering-connections-on-windows-pc/"><u>Seamless Cyber Travel: Mastering Connections on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/six-proven-techniques-for-pinpointing-your-pcs-brand-and-version/"><u>Six Proven Techniques for Pinpointing Your PC's Brand & Version</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-performance-with-expert-tips-on-wintoys-usage/"><u>Skyrocket Performance with Expert Tips on Wintoys Usage</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-unexpected-command-prompt-displays/"><u>Stopping Unexpected Command Prompt Displays</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-digital-life-using-windows-11s-taskbar-search/"><u>Streamline Your Digital Life: Using Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-11-logon-from-pin-to-password-a-step-by-step-guide/"><u>Switching Windows 11 Logon From PIN to Password: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-operation-failed-problem-on-pcs/"><u>Tackling the Operation Failed Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-functionalities-of-fn-keys-on-windows-11-devices/"><u>Tailoring Functionalities of FN Keys on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-integrity-in-the-windows-registry/"><u>The Ultimate Guide to Restoring Integrity in the Windows Registry</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-over-win11-blue-screen-with-these-top-11-strategies/"><u>Triumph Over Win11 Blue Screen with These Top 11 Strategies</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-top-10-free-music-production-tools-expert-reviews/"><u>Updated In 2024, Top 10 Free Music Production Tools Expert Reviews</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-unveiling-the-facts-dispelling-common-misconceptions-about-daw-software/"><u>Updated Unveiling the Facts Dispelling Common Misconceptions About DAW Software</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-breakdown-how-to-pre-emptive-access-updates/"><u>ViVeTool Breakdown: How to Pre-Emptive Access Updates</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-comprehensive-navshortcut-compendium/"><u>Win11's Comprehensive NavShortcut Compendium</u></a></li>
<li><a href="https://win11.techidaily.com/windows-as-the-base-crafting-a-linux-vm-environment-via-hyper-v/"><u>Windows as the Base: Crafting a Linux VM Environment via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-diverse-monitor-decorations-1011-edition/"><u>Windows Wonders: Diverse Monitor Decorations, 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-adoption-and-linux-market-dynamics/"><u>WSL Adoption and Linux Market Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/zero-internet-window-upgrades-strategy/"><u>Zero Internet Window Upgrades Strategy</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>