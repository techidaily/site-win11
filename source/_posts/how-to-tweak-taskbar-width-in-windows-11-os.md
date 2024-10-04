---
title: How to Tweak Taskbar Width in Windows 11 OS
date: 2024-09-27T07:11:35.632Z
updated: 2024-10-03T23:38:44.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Tweak Taskbar Width in Windows 11 OS
excerpt: This Article Describes How to Tweak Taskbar Width in Windows 11 OS
keywords: Windows Taskbar Adjustment,Change Taskbar Size W11,Taskbar Resize Guide Windows,Windows 11 Bar Dimension,Optimizing Taskbar Width,Taskbar Settings Edit W11,Altering Windows Taskbar Thickness
thumbnail: https://thmb.techidaily.com/cb670c879e89656e881160d22473efee38dda114df0401fe96c31b4cf2882857.jpg
---

## How to Tweak Taskbar Width in Windows 11 OS

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049391/7443" target="_top" id="2049391">
  <img src="//a.impactradius-go.com/display-ad/7443-2049391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049391/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/updated-comprehensive-report-on-djis-inspire-1/"><u>[Updated] Comprehensive Report on DJI's Inspire 1</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-transform-meetings-with-easy-to-follow-zoom-sharing-tips/"><u>[Updated] Transform Meetings with Easy-to-Follow Zoom Sharing Tips</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-pc-innovations-at-toms-hardware-hub/"><u>Exploring PC Innovations at Tom's Hardware Hub</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-display-glitches-in-windows-11-os/"><u>Fix Window's Display Glitches in Windows 11 OS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-you-cast-your-apple-iphone-12-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>In 2024, How Can You Cast Your Apple iPhone 12 to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/nine-cool-additions-to-windows-11-feb23/"><u>Nine Cool Additions to Windows 11 FEB23</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-the-perfect-win-tracker-from-these-6-titles/"><u>Pinpoint the Perfect Win Tracker From These 6 Titles</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/quick-guide-converting-mkv-to-avi-format-using-vlc-player-no-hidden-marks/"><u>Quick Guide: Converting MKV to AVI Format Using VLC Player - No Hidden Marks</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-honor-x9b-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Honor X9b</u></a></li>
<li><a href="https://win11.techidaily.com/spruce-up-your-window-mail-and-events-with-images/"><u>Spruce Up Your Window Mail and Events With Images</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-solutions-to-overcome-discord-not-opening-issues/"><u>Step-by-Step Solutions to Overcome Discord Not Opening Issues</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-computing-experience-with-windows-new-standard-ram/"><u>Transforming Computing Experience with Windows' New Standard RAM</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-photos-efficiency-through-shortcuts/"><u>Unlocking Windows Photos Efficiency Through Shortcuts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-poco-x5-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Poco X5? | Dr.fone</u></a></li>
</ul></div>

