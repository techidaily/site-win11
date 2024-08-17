---
title: How to Fix the Vanishing Battery Time Indicator in Windows 11
date: 2024-08-15T23:49:31.605Z
updated: 2024-08-16T23:49:31.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
excerpt: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
keywords: Windows Battery Life,Save Power Mode,Low Battery Alerts,Battery Health Check,Optimize Battery Use,Fix Time Indicator,Manage Battery Settings
thumbnail: https://thmb.techidaily.com/4d82cc5d4830160f77be1be23b3b0d5c8cbc630ac82437e197dd592c77a4c46e.jpg
---

## How to Fix the Vanishing Battery Time Indicator in Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://extra-resources.techidaily.com/new-character-development-through-authentic-dialogue/"><u>[New] Character Development Through Authentic Dialogue</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-elevate-photos-selecting-a-robust-text-editor/"><u>[New] Elevate Photos  Selecting a Robust Text Editor</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elite-edits-the-best-video-editors-ranked-for-2024/"><u>[Updated] Elite Edits  The Best Video Editors Ranked for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-enhancing-vimeo-playback-velocity-guide/"><u>[Updated] In 2024, Enhancing Vimeo Playback Velocity Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-leading-voice-modifying-apps-magical-calls-and-more/"><u>[Updated] Leading Voice-Modifying Apps  Magical Calls & More</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-creating-a-professional-periscope-presence/"><u>2024 Approved  Creating a Professional Periscope Presence</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win11s-notepad-with-virtuoso-helper/"><u>Accelerate Win11's Notepad with Virtuoso Helper</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-usage-of-computational-resources-by-unrealcefsubprocess/"><u>Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/eliminating-crackling-noise-from-your-cyberpunk-2077-gameplay-expert-tips-and-tricks/"><u>Eliminating Crackling Noise From Your Cyberpunk 2077 Gameplay: Expert Tips and Tricks</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enhancing-video-discoverability-with-effective-titles-and-tags/"><u>Enhancing Video Discoverability with Effective Titles & Tags</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-nokia-130-music-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-frozen-windows-volume-backup-service/"><u>Fixes for Frozen Windows Volume Backup Service</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-a2-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on A2</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-fatal-glitches-fixing-xbox-game-pass-error-0x00000001-in-windows-11/"><u>How to Eliminate Fatal Glitches: Fixing Xbox Game Pass Error 0X00000001 in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-samsung-galaxy-s23-ultra-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Samsung Galaxy S23 Ultra online without jailbreak</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Life360 Learn How Everything Works On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-revolutionize-your-recording-experience-top-18-cam-tools-showcase/"><u>In 2024, Revolutionize Your Recording Experience - Top 18 Cam Tools Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fall-guys-network-woes-on-windows-systems/"><u>Mastering Fall Guys Network Woes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-calendar-a-step-by-step-guide/"><u>Mastering Windows 11 Calendar: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-logitech-g733-mic-problems-expert-fixes-and-advice/"><u>Resolve Logitech G733 Mic Problems: Expert Fixes & Advice</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/s-most-popular-video-reversal-websites-for-2024/"><u>S Most Popular Video Reversal Websites for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/smooth-sailing-ahead-eliminating-the-avatar-new-world-of-pandora-pc-game-crash-problems/"><u>Smooth Sailing Ahead! Eliminating the 'Avatar: New World of Pandora' PC Game Crash Problems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-access-to-system-fixes-windows-10-and-11-key-setups/"><u>Strategic Access to System Fixes: Windows 10 & 11 Key Setups</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-full-potential-of-windows-customizations-via-winbubble/"><u>Unleash the Full Potential of Windows Customizations via WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-rdp-access-quickly-in-the-latest-windows/"><u>Unlock RDP Access Quickly in the Latest Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-capabilities-with-easy-installation-of-msixbundle-packages/"><u>Unlock Windows Capabilities with Easy Installation of MSixBundle Packages</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-ranking-rise-must-have-youtube-seo-aids/"><u>Video Ranking Rise – Must-Have YouTube SEO Aids</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>Which Pokémon can Evolve with a Moon Stone For Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/why-are-other-processes-aligned-with-edge/"><u>Why Are Other Processes Aligned with Edge?</u></a></li>
</ul></div>
