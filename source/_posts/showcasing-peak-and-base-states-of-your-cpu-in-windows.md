---
title: Showcasing Peak and Base States of Your CPU in Windows
date: 2024-09-11T09:46:14.886Z
updated: 2024-09-12T09:46:14.886Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Showcasing Peak and Base States of Your CPU in Windows
excerpt: This Article Describes Showcasing Peak and Base States of Your CPU in Windows
keywords: PeakCPUStateWindows,BaseCPUStatesPC,WindowsCPUPeakView,BaseStateCPUWin,HighPerformanceCPU,CPUHeatMapWin,TemperatureBaseState
thumbnail: https://thmb.techidaily.com/b5066dad0b601fca3256158753d40238cd5a1c7754394d186d31755e512b1e70.jpg
---

## Showcasing Peak and Base States of Your CPU in Windows

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-cheap-not-bad-chromebooks-top-recording-tools/"><u>[New] Cheap Not Bad – Chromebook's Top Recording Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-a-beginners-pathway-to-iphone-audio-memos/"><u>[New] In 2024, A Beginner's Pathway to iPhone Audio Memos</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-live-tv-streaming-guide-the-best-ten-and-their-comparison/"><u>[New] In 2024, Live TV Streaming Guide The Best Ten and Their Comparison</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-striking-visuals-for-success-a-deep-dive-into-youtube-live-imagery/"><u>[New] Striking Visuals for Success A Deep Dive Into YouTube Live Imagery</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-tame-fast-paced-vids-a-slowdown-strategy-for-snapchat/"><u>[Updated] 2024 Approved Tame Fast-Paced Vids A Slowdown Strategy for Snapchat</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-learning-photography-on-the-go-the-lunapic-approach/"><u>[Updated] Learning Photography on the Go The LunaPic Approach</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-itel-a05s-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Itel A05s | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-pioneering-photography-with-quantum-hdr-tech/"><u>2024 Approved Pioneering Photography with Quantum HDR Tech</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-xiaomi-redmi-k70-pro-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-windows-versioning-insight/"><u>Cracking the Code: Windows Versioning Insight</u></a></li>
<li><a href="https://win11.techidaily.com/electrical-use-analysis-for-windows-computers-unveiled/"><u>Electrical Use Analysis for Windows Computers Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-search-icon-techniques-for-windows-11/"><u>Elusive Search Icon Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-windows-1111-ui-for-auto-check-updates/"><u>Enabling Windows 11/11 UI for Auto-Check Updates</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-steps-into-filmmaking-the-ultimate-guide-for-making-your-first-10-youtube-videos-for-2024/"><u>First Steps Into Filmmaking The Ultimate Guide for Making Your First 10 YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/harness-powertoys-for-rapid-file-naming-tasks/"><u>Harness PowerToys for Rapid File Naming Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-best-linux-features-with-windows-apps/"><u>How to Get the Best Linux Features With Windows Apps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-realme-11-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Realme 11 5G Phones</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/inside-the-world-of-toolwiz-an-in-depth-software-review-for-2024/"><u>Inside the World of Toolwiz An In-Depth Software Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-implementation-microsoft-works-for-windows-10plus/"><u>Instantaneous Implementation: Microsoft Works for Windows 10+</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-accessibility-must-know-tips/"><u>Intro to Windows Accessibility: Must-Know Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-xbox-mic-troubleshooting-in-windows-11-platforms/"><u>Mastering Xbox Mic Troubleshooting in Windows 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-functional-adjustments-windows-1011-edition/"><u>Navigating Functional Adjustments: Windows 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-navigation-for-the-elusive-mac-on-windows-11/"><u>Navigating Network Navigation for the Elusive MAC on WIndows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-10-essential-animated-text-makers-for-unbeatable-engagement/"><u>New 10 Essential Animated Text Makers for Unbeatable Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-unrealcefsubprocess-for-lower-cpu-and-memory-usage/"><u>Optimizing UnrealCEFSubprocess for Lower CPU and Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-dilemmrances/"><u>Overcoming Windows Exe Opener Dilemmrances</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-ui-fidelity-on-newest-windows-release/"><u>Perfecting UI Fidelity on Newest Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pandemonium-a-guide-to-regaining-your-pcs-true-colors/"><u>Purple Pandemonium? A Guide to Regaining Your PC's True Colors</u></a></li>
<li><a href="https://win11.techidaily.com/quickly-link-tofrom-bing-chat-in-windows-11-search-field/"><u>Quickly Link To/From Bing Chat in Windows 11 Search Field</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-incomplete-network-prompt-guidance-on-windows/"><u>Resolving Incomplete Network Prompt Guidance on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-visual-placement-on-windows-devices/"><u>Reversing Visual Placement on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-custom-sort-and-group-order-of-files/"><u>Reverting Custom Sort and Group Order of Files</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/sharing-videos-tweet-tumble-route-for-2024/"><u>Sharing Videos Tweet-Tumble Route for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-game-with-expert-multitasking-techniques-for-windows-11/"><u>Step Up Your Game with Expert Multitasking Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-error-e8024002e/"><u>Steps to Overcome Windows Error E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spotify-on-windows-startup-by-default/"><u>Stop Spotify on Windows Startup by Default</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-technique-to-design-personalized-lock-patterns-on-windows-11/"><u>The Complete Technique to Design Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-guide-to-disbanding-disk-divisions-in-win-os/"><u>The Comprehensive Guide to Disbanding Disk Divisions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-picks-of-drawing-apps-for-windows-11-enthusiasts/"><u>The Top 7 Picks of Drawing Apps for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/time-tracker-tweaks-top-apps-to-modify-file-timestamps-on-pc/"><u>Time Tracker Tweaks: Top Apps to Modify File Timestamps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/top-six-strategies-to-scale-your-photos-on-windows-11-effectively/"><u>Top Six Strategies to Scale Your Photos on Windows 11 Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-into-a-personalized-oasis-8-winbubble-upgrades/"><u>Transform Windows Into a Personalized Oasis: 8 WinBubble Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-digital-music-library-a-comprehensive-guide-on-mp3-to-cd-conversion-with-imgburn-windows/"><u>Transforming Your Digital Music Library: A Comprehensive Guide on Mp3 to CD Conversion with ImgBurn (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/turning-phones-into-windows-audio-input/"><u>Turning Phones Into Windows Audio Input</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-audacitys-windows-compatibility-issue-9999/"><u>Unlocking Audacity's Windows Compatibility Issue #9999</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-blue-screen-mysteries-where-are-the-logs/"><u>Unlocking Blue Screen Mysteries: Where Are the Logs?</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-fixing-windows-remote-desktop-errors/"><u>Unlocking Secrets: Fixing Windows Remote Desktop Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-speech-technology-navigating-shortcuts-on-win-11/"><u>Unlocking Speech Technology: Navigating Shortcuts on Win 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/updated-drivers-for-your-sound-blaster-z-download-and-compatibility-with-windows-11/"><u>Updated Drivers for Your Sound Blaster Z - Download & Compatibility with Windows 11</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-in-2024-best-live-streaming-platforms-to-engage-audiences-and-increase-viewership/"><u>Updated In 2024, Best Live Streaming Platforms To Engage Audiences and Increase Viewership</u></a></li>
<li><a href="https://win11.techidaily.com/win-pc-download-speedups-navigate-the-net-faster/"><u>Win-PC Download Speedups: Navigate the Net Faster</u></a></li>
<li><a href="https://win11.techidaily.com/winning-torrent-clients-the-best-of-windows-list/"><u>Winning Torrent Clients: The Best of Windows List</u></a></li>
</ul></div>

