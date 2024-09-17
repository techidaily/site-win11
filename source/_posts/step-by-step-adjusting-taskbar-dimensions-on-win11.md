---
title: "Step by Step: Adjusting Taskbar Dimensions on Win11"
date: 2024-09-10T21:12:06.974Z
updated: 2024-09-16T19:07:59.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step by Step: Adjusting Taskbar Dimensions on Win11"
excerpt: "This Article Describes Step by Step: Adjusting Taskbar Dimensions on Win11"
keywords: Windows 11 Taskbar Size,Tweak Taskbar Width,Resize Window Bar,Win11 Screen Setup,Adjusting Desktop Edge,TaskBar Dimension Control,Maximize Taskbar Space
thumbnail: https://thmb.techidaily.com/9cb9221a42cf990d1ead5f7525c2a2084bd45082f379d43f5b1579226c750ee8.jpg
---

## Step by Step: Adjusting Taskbar Dimensions on Win11

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
<li><a href="https://vp-tips.techidaily.com/2024-approved-examining-benq-sw320-the-4k-visionary/"><u>2024 Approved Examining BenQ SW320 The 4K Visionary</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-tiktok-video-amplification/"><u>2024 Approved The Ultimate Guide to TikTok Video Amplification</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-to-getting-1000-subscribers-for-your-youtube-channel/"><u>Guide to Getting 1000 Subscribers for Your YouTube Channel</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-zte-axon-40-lite-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On ZTE Axon 40 Lite For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-analyzing-the-impact-of-burst-on-live-action-shoots/"><u>In 2024, Analyzing the Impact of Burst on Live-Action Shoots</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastery-of-instagram-video-marketing-the-ultimate-plan-crafted-here/"><u>In 2024, Mastery of Instagram Video Marketing The Ultimate Plan Crafted Here</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-infinix-smart-7-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Infinix Smart 7 Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-six-leading-compact-video-editor-tools-for-seamless-editing-on-the-go/"><u>The Six Leading Compact Video Editor Tools for Seamless Editing on the Go</u></a></li>
<li><a href="https://win11.techidaily.com/top-ts-encoder-swift-and-simple-video-conversion-fromto-ts-format/"><u>Top TS Encoder: Swift & Simple Video Conversion From/To TS Format</u></a></li>
<li><a href="https://win11.techidaily.com/turn-your-music-collection-into-ogg-format-at-no-cost-a-simple-guide-on-mp3-to-ogg-transformation/"><u>Turn Your Music Collection Into Ogg Format at No Cost: A Simple Guide on MP3-to-Ogg Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-8-screen-recorder-apps-compatible-with-mac-and-windows-pc-top-picks-for-easy-recording/"><u>Ultimate 8 Screen Recorder Apps Compatible with Mac & Windows PC: Top Picks for Easy Recording</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-top-7-excellent-choices-instead-of-kodi/"><u>Ultimate Guide: Top 7 Excellent Choices Instead of Kodi</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-top-dvd-ripper-tools-for-seamless-plex-media-server-integration/"><u>Ultimate Guide: Top DVD Ripper Tools for Seamless Plex Media Server Integration</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-for-implementing-the-black-lightning-extension-in-kodi-versions-19-and-18/"><u>Ultimate Tutorial for Implementing the Black Lightning Extension in Kodi Versions 19 & 18</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

