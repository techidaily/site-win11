---
title: Guide to Window 11 Custom Taskbar Sizing
date: 2024-06-25T11:27:10.719Z
updated: 2024-06-26T11:27:10.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Window 11 Custom Taskbar Sizing
excerpt: This Article Describes Guide to Window 11 Custom Taskbar Sizing
keywords: Windows 11 Bar Size Guide,Adjust Taskbar Dimensions W11,Taskbar Resize Tutorial W11,Custom Taskbar Setting Window11,W11 Taskbar Sizing Configuration,Mastering Taskbar Space in Windows 11,Personalize W11 Taskbar Size
thumbnail: https://thmb.techidaily.com/da3a565149456b725f254b5d80c3b1f1c06d74a5fc993d32dbb395957f6fba49.jpg
---

## Guide to Window 11 Custom Taskbar Sizing

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
<li><a href="https://win11.techidaily.com/1719290483430-quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC</u></a></li>
<li><a href="https://win11.techidaily.com/immersive-education-experience-windows-11-tutorials/"><u>Immersive Education Experience: Windows 11 Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://win11.techidaily.com/pixelated-paths-walking-through-oldschool-pc-world-in-dosbox-x/"><u>Pixelated Paths: Walking Through Oldschool PC World in DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-maze-quickly-entering-windows-support-space/"><u>Avoiding the Maze: Quickly Entering Windows' Support Space</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-unidentified-usb-port-problems/"><u>Overcoming Windows 11'S Unidentified USB Port Problems</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-professional-pc-sound-recording-options-unveiling-the-top-10/"><u>Updated In 2024, Professional PC Sound Recording Options Unveiling the Top 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dealing-with-a-solitary-speaker/"><u>Dealing with a Solitary Speaker</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-itunes-masterclass-maximizing-video-outputs/"><u>[Updated] In 2024, ITunes Masterclass  Maximizing Video Outputs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-charting-the-trends-popular-tiktok-reaction-videos/"><u>[New] In 2024, Charting the Trends  Popular TikTok Reaction Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-discovering-top-foodie-influencers-on-tiktok/"><u>[New] Discovering Top Foodie Influencers on TikTok</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-joint-filmmaking-and-gaining-followers-quickly/"><u>In 2024, Joint Filmmaking & Gaining Followers Quickly</u></a></li>
<li><a href="https://video-capture.techidaily.com/quick-screen-grabs-for-win-11-users-for-2024/"><u>Quick Screen Grabs for Win 11 Users for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/pioneering-techniques-for-popularizing-youtube-videos-for-2024/"><u>Pioneering Techniques for Popularizing YouTube Videos for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-maximize-monetization-the-step-by-step-for-youtube-profiles/"><u>In 2024, Maximize Monetization  The Step-by-Step for YouTube Profiles</u></a></li>
</ul></div>
