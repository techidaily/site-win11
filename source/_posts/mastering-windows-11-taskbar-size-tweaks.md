---
title: Mastering Windows 11 Taskbar Size Tweaks
date: 2024-06-25T09:52:19.009Z
updated: 2024-06-26T09:52:19.009Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows 11 Taskbar Size Tweaks
excerpt: This Article Describes Mastering Windows 11 Taskbar Size Tweaks
keywords: WinTaskbarSizeAdjust,TaskbarTweakWin11,TaskbarWidthControl,OptimizeWindowsBar,SetWinBarSize,WindowsBarSizeChange,Win11TaskbarModify
thumbnail: https://thmb.techidaily.com/78fc2ce8486dc3d6564f3f5f4f837891a8fa189d01a8b699d519ecb10291bd82.jpg
---

## Mastering Windows 11 Taskbar Size Tweaks

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://win11.techidaily.com/quelling-the-0x800736cc-dilemran-in-windows-update/"><u>Quelling the 0X800736CC Dilemran in Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-eliminating-server-glitches-impacting-ms-store-on-win-1111/"><u>Quick Fix: Eliminating Server Glitches Impacting MS Store on Win 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-widget-personalization-on-windows-11-pcs/"><u>The Beginner's Guide to Widget Personalization on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-access-to-computers-heartbeat-open-mouse-prop-on-win11/"><u>Effortless Access to Computer's Heartbeat: Open Mouse Prop on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-nubia-red-magic-9-pro-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Nubia Red Magic 9 Pro? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/time-saving-strategies-mastering-video-playback-speed-for-2024/"><u>Time-Saving Strategies  Mastering Video Playback Speed for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/vpx-film-record-thorough-examination-and-reviews/"><u>VPX Film Record  Thorough Examination & Reviews</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-itel-s23-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Itel S23 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-free-yourself-from-tiktok-watermarks-best-removal-tools/"><u>Updated 2024 Approved Free Yourself From TikTok Watermarks Best Removal Tools</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-mastering-the-art-of-spotify-downloads-a-comprehensive-guide-for-music-lovers/"><u>Updated In 2024, Mastering the Art of Spotify Downloads A Comprehensive Guide for Music Lovers</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-the-complete-breakdown-of-screen-casting-on-discord/"><u>2024 Approved  The Complete Breakdown of Screen Casting on Discord</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sleepy-screenplays-for-nights-end/"><u>In 2024, Sleepy Screenplays for Night's End</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-online-broadcast-battle-fb-live-and-yt-live-vs-tweetstreams/"><u>[Updated] Online Broadcast Battle  FB LIVE & YT Live Vs. TweetStreams</u></a></li>
</ul></div>
