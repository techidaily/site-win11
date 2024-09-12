---
title: Mastering Dimming Features in Windows Power Settings
date: 2024-09-11T09:33:51.265Z
updated: 2024-09-12T09:33:51.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Dimming Features in Windows Power Settings
excerpt: This Article Describes Mastering Dimming Features in Windows Power Settings
keywords: Power Control Mastery,Windows Power Dimming,Optimize Power Settings,Energy-Saving Techniques,Windows Efficiency Tips,Adjusting Power Sliders,Save Energy with PCs
thumbnail: https://thmb.techidaily.com/e1c4df4174fbb7e774640c12444893c833b651d1c12bd8c02f2b01f747786c25.jpg
---

## Mastering Dimming Features in Windows Power Settings

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://instagram-video-files.techidaily.com/new-harmonizing-content-and-sound-in-instagram-reels/"><u>[New] Harmonizing Content & Sound in Instagram Reels</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-leveraging-facebook-slides-a-beginners-handbook-for-visual-storytelling/"><u>[New] Leveraging Facebook Slides A Beginner's Handbook for Visual Storytelling</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-5-free-online-gif-to-video-tools-no-downloads-needed/"><u>[New] Top 5 Free Online GIF-to-Video Tools (No Downloads Needed)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-8-endorsed-methods-for-video-marketing-success/"><u>[New] Top 8 Endorsed Methods for Video Marketing Success</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transforming-windows-photos-viewer-with-creative-filter-settings-and-soundscape/"><u>[New] Transforming Windows Photos Viewer with Creative Filter Settings & Soundscape</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-from-stream-to-file-vimeo-hd-to-mp4-methods/"><u>[Updated] 2024 Approved From Stream to File Vimeo HD to MP4 Methods</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-discovering-8-honestly-endorsed-promotional-strategies/"><u>[Updated] In 2024, Discovering 8 Honestly-Endorsed Promotional Strategies</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-the-ultimate-30-list-of-no-cost-high-quality-online-film-effects-tools-for-2024/"><u>[Updated] The Ultimate 30 List of No-Cost, High-Quality Online Film Effects Tools for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-virtual-venue-video-verifier/"><u>[Updated] Virtual Venue Video Verifier</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-discover-top-affordable-video-editors-of-2023-today/"><u>2024 Approved Discover Top Affordable Video Editors of 2023 Today</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-pinpointing-factors-that-influence-igtv-video-performance/"><u>2024 Approved Pinpointing Factors that Influence IGTV Video Performance</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-asus-rog-phone-7-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Asus ROG Phone 7 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-nokia-g310-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Nokia G310 FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/connoisseurs-tips-for-immaculate-w11-window-backgrounds/"><u>Connoisseur’s Tips for Immaculate W11 Window Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-personalized-inactivity-timer-in-windows/"><u>Crafting Personalized Inactivity Timer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dazzling-display-holiday-themed-window-wonders/"><u>Dazzling Display: Holiday Themed Window Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/designing-keybindings-for-windows-applications/"><u>Designing Keybindings for Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/dial-down-devices-the-fast-route-to-silence-windows-11/"><u>Dial Down Devices: The Fast Route to Silence Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-commands-open-screenshots-utility-in-win-11/"><u>Efficient Commands: Open Screenshots Utility in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-hibernate-for-idle-windows-1011-users/"><u>Effortless Hibernate for Idle Windows 10/11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-w11s-notepad-through-intelligent-assistance/"><u>Elevate W11's Notepad Through Intelligent Assistance</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-to-show-disk-space/"><u>Enhancing Windows Explorer to Show Disk Space</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enthusiastic-exchanges-chatting-with-your-subscribers/"><u>Enthusiastic Exchanges Chatting With Your Subscribers</u></a></li>
<li><a href="https://win-able.techidaily.com/get-unstuck-solutions-for-when-madden-22-hangs-on-the-startup-screen/"><u>Get Unstuck! Solutions for When Madden 22 Hangs on the Startup Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-tecno-pop-8-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Tecno Pop 8 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-remove-your-apple-id-permanently-on-apple-iphone-12-pro-max-by-drfone-ios/"><u>How To Delete iCloud Account Remove Your Apple ID Permanently On Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-pin-almost-anything-to-the-windows-11-taskbar/"><u>How to Pin Almost Anything to the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-stop-automatic-windows-updates/"><u>How to Temporarily Stop Automatic Windows Updates</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-6s-plus-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 6s Plus without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-xiaomi-redmi-note-12t-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Xiaomi Redmi Note 12T Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-connections-with-spotify/"><u>Mastering Windows 11 Connections with Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/nine-essential-tips-for-new-windows-11-users-avoid-these-errors/"><u>Nine Essential Tips for New Windows 11 Users - Avoid These Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-store-failure-error-0x80073d26/"><u>Overcoming Windows Store Failure: Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/premium-weather-tech-for-windows-users/"><u>Premium Weather Tech for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/relaunching-file-explorer-a-step-bystep-guide/"><u>Relaunching File Explorer: A Step-Bystep Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reworking-windows-11-to-utilize-traditional-search-icon/"><u>Reworking Windows 11 to Utilize Traditional Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-your-type-speed-with-windows-tools/"><u>Skyrocket Your Type-Speed with Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solution-matching-internet-on-mobile-and-desktop/"><u>Speedy Solution: Matching Internet on Mobile & Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-address-windows-save-permission-mishaps/"><u>Steps to Address Windows Save Permission Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/subtle-system-tweaks-windows-toolbars-unseen/"><u>Subtle System Tweaks: Windows Toolbars Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-signature-compliant-update-files-on-windows/"><u>Tackling Non-Signature Compliant Update Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-edge-settings-to-reduce-processes/"><u>Tailoring Edge Settings to Reduce Processes</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-disable-repetitive-sign-in-requests-in-teams/"><u>Techniques to Disable Repetitive Sign-In Requests in Teams</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-to-resolve-skies-sse-woes/"><u>The Quest to Resolve Skies' SSE Woes</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-checklist-for-clean-windows-installations/"><u>The Ultimate Checklist for Clean Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/tiny-tech-giants-running-microsoft-os/"><u>Tiny Tech Giants Running Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-failed-ms-store-app-downloads/"><u>Tips for Dealing with Failed MS Store App Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-win-error-31-in-network-connections/"><u>Troubleshooting WIN Error 31 in Network Connections</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-performance-with-these-5-powerful-windows-apps/"><u>Unleash Peak Performance with These 5 Powerful Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-help-application-issues/"><u>Unlocking Windows 11 Help Application Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-strategies-to-exit-s-mode/"><u>Unlocking Your PC: Strategies to Exit S Mode</u></a></li>
</ul></div>

