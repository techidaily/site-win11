---
title: Guide to Window 11 Custom Taskbar Sizing
date: 2024-06-25T09:57:30.619Z
updated: 2024-06-26T09:57:30.619Z
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
<li><a href="https://win11.techidaily.com/troubleshooting-dll-file-disappearance-on-windows/"><u>Troubleshooting DLL File Disappearance on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-games-on-windows-avoid-common-setup-pitfalls/"><u>Xbox Games on Windows: Avoid Common Setup Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-strategies-with-a-focus-on-windows-diskusage/"><u>Streamlining Storage Strategies with a Focus on Windows' DiskUsage</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/dont-overlook-the-side-effects-of-bargain-windows-keys/"><u>Don't Overlook: The Side Effects of Bargain Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-apples-messaging-on-your-windows-machine/"><u>Embracing Apple's Messaging on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-tecno-spark-10-pro-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Tecno Spark 10 Pro Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-beginners-guide-to-video-editing-top-software-picks/"><u>In 2024, Beginners Guide to Video Editing Top Software Picks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-secrets-of-profitable-youtube-videos-necessary-views-explained/"><u>In 2024, Secrets of Profitable YouTube Videos  Necessary Views Explained</u></a></li>
<li><a href="https://extra-hints.techidaily.com/your-step-by-step-apk-to-funimate-play/"><u>Your Step-by-Step APK to Funimate Play</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-infinix-note-30-vip-racing-edition-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Infinix Note 30 VIP Racing Edition Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Tecno Pop 8? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-facebook-videos-stop-buffering-and-glitches-on-devices/"><u>[New] Facebook Videos  Stop Buffering & Glitches on Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximizing-profits-the-ultimate-guide-to-youtube-revenue/"><u>Maximizing Profits   The Ultimate Guide to YouTube Revenue</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-optimizing-vertical-video-tips-for-smartphone-creators/"><u>In 2024, Optimizing Vertical Video Tips for Smartphone Creators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-leveraging-likes-and-shares-top-30-facebook-marketing-steps/"><u>In 2024, Leveraging Likes and Shares  Top 30 Facebook Marketing Steps</u></a></li>
</ul></div>
