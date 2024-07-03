---
title: Mastering Windows 11 Taskbar Size Tweaks
date: 2024-06-25T11:25:29.788Z
updated: 2024-06-26T11:25:29.788Z
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
<li><a href="https://win11.techidaily.com/how-to-change-windows-11-search-icon-from-a-text-bar/"><u>How to Change Windows 11 Search Icon From a Text Bar</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-upgrades-techniques-for-ensuring-optional-components-on-windows-os/"><u>Optimal Upgrades: Techniques for Ensuring Optional Components on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-operational-breakdowns-of-your-windows-stylus/"><u>Understanding and Resolving Operational Breakdowns of Your Windows Stylus</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/neutralizing-windows-update-triggers/"><u>Neutralizing Windows Update Triggers</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-display-management-in-windows-11/"><u>Understanding Display Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-compression-via-cli/"><u>The Essential Guide to File Compression via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-seamless-slide-showouts-top-tips-for-powerpoint-printing-on-windows/"><u>The Key to Seamless Slide Showouts: Top Tips for PowerPoint Printing on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/1714067835129-updated-10-best-free-video-editing-apps-for-android-without-watermark/"><u>Updated 10 Best Free Video Editing Apps for Android without Watermark</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-playbook-for-procuring-partners-on-youtube/"><u>The Ultimate Playbook for Procuring Partners on YouTube</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/free-mkv-trimmer-software-top-picks-for-2024/"><u>Free MKV Trimmer Software Top Picks for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-culinary-waves-tiktoks-most-shared-meals/"><u>[New] In 2024, Culinary Waves  TikTok's Most Shared Meals</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-best-of-the-best-lego-stop-motion-creators/"><u>In 2024, The Best of the Best Lego Stop Motion Creators</u></a></li>
<li><a href="https://extra-tips.techidaily.com/10-open-source-video-player-for-linux-windows-and-mac-for-2024/"><u>10 Open Source Video Player for Linux, Windows and Mac for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/iconic-imagery-stories-a-peek-inside-for-2024/"><u>Iconic Imagery Stories  A Peek Inside for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-free-3d-animation-software-is-not-easy-to-find-some-makers-are-even-free-and-simple-if-you-want-to-know-which-are-the-8-best-3d-animat/"><u>Updated 2024 Approved Free 3D Animation Software Is Not Easy to Find. Some Makers Are Even Free and Simple. If You Want to Know Which Are the 8 Best 3D Animation Software, Check It Out</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlimited-hd-videostreaming-on-your-device-for-2024/"><u>Unlimited HD Videostreaming on Your Device for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-apple-iphone-6-without-itunes-drfone-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked Apple iPhone 6 Without iTunes | Dr.fone</u></a></li>
</ul></div>
