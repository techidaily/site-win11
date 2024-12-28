---
title: Expert Advice on Navigating Folder Tabs with Windows 11
date: 2024-12-23T03:31:30.229Z
updated: 2024-12-27T17:13:00.384Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Advice on Navigating Folder Tabs with Windows 11
excerpt: This Article Describes Expert Advice on Navigating Folder Tabs with Windows 11
keywords: Windows 11 Navigation,Folder Tabs Guide,Expert Folder Tips,Tab Management W11,Navigate Folders Easily,Mastering Win11 Tabs,Optimize Tab Usage
thumbnail: https://thmb.techidaily.com/f60b5cb5d31f0db6c00b1faa5bbb82ce655e5c5fa0350104266b8258e603ad98.png
---

## Expert Advice on Navigating Folder Tabs with Windows 11

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and[check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily[download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Enable the Feature Using ViveTool

 Now, you have the Insider build running on your system. You will have to use the ViveTool to enable the hidden experimental feature to drag tabs out of the File Explorer. But first,[download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) and install the ViveTool on your system. After that, repeat the following steps:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) on your system.
2. Type**cmd** in the text input area and then press**Ctrl + Shift + Enter** key to launch the command prompt with admin privileges.
3. Now, locate the ViveTool directory using the**cd** command. We placed the ViveTool in a folder named Vive on C drive, So the command to change to that directory will be**cd\\** .
4. Once you are in the C directory, type**cd Vive** and press the**Enter** key.
5. After that, type**vivetool /enable /id:39661369** command and press the**Enter** key.  
![Enabling Tabs Dragging Feature In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-tabs-dragging-feature-in-file-explorer.jpg)
6. **Exit** the command prompt window after the ViveTool command executes successfully.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can You Restore the Tab to the File Explorer Window?

 Yes, you can indeed restore the dragged tab back to a File Explorer window. But the process is very clunky. You have to drag and hold the tab onto another open tab in a different File Explorer window.

 If you aren’t able to accurately position the tab, it will not merge with the File Explorer tab bar. In Chrome browser, dragging out and restoring them to the same window is pretty easy. You can even hover the tab and position it between two open tabs.

## Drag Tabs Out Like a Pro in File Explorer

 Microsoft is trying to make File Explorer more useful. But we cannot expect File Explorer to exactly work like a browser. After, it happens to be a means to access different types of files and open them with a compatible app or program in a new window. Still, dragging tabs out is a slick feature, and we hope Microsoft fixes the kinks and adds it in future updates.

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
<li><a href="https://extra-approaches.techidaily.com/new-musical-alchemy-transforming-previews-into-memories/"><u>[New] Musical Alchemy Transforming Previews Into Memories</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-best-practices-choosing-the-top-ios-video-downloaders-on-fb/"><u>[Updated] In 2024, Best Practices Choosing the Top iOS Video Downloaders on FB</u></a></li>
<li><a href="https://fox-web3.techidaily.com/accelerate-your-pcs-speed-with-yl-software-solutions-and-essential-optimization-strategies/"><u>Accelerate Your PC's Speed with YL Software Solutions and Essential Optimization Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/launching-windows-media-player-for-quick-access/"><u>Launching Windows Media Player for Quick Access</u></a></li>
<li><a href="https://win11.techidaily.com/mending-badge-icons-disappearance/"><u>Mending Badge Icons Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/reinforcing-windows-safety-expanding-context-menu-with-firewall-filters/"><u>Reinforcing Windows Safety: Expanding Context Menu with Firewall Filters</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-drivers-not-loading-issue/"><u>Resolving Windows 11: Drivers Not Loading Issue</u></a></li>
<li><a href="https://win11.techidaily.com/securing-vpn-connectivity-after-disconnection-issues/"><u>Securing VPN Connectivity After Disconnection Issues</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-mathematics-behind-making-money-from-snippets-for-2024/"><u>The Mathematics Behind Making Money From Snippets for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-xiaomi-14-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Xiaomi 14</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-when-your-windows-11-icons-go-missing-restore-them-now/"><u>The Ultimate Fix for When Your Windows 11 Icons Go Missing - Restore Them Now!</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-computers-clock-view-with-these-top-5-dynamic-screen-saver-apps/"><u>Transform Your Computer's Clock View with These Top 5 Dynamic Screen Saver Apps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-apple-iphone-6s-plus-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your Apple iPhone 6s Plus has bad ESN or blacklisted IMEI?</u></a></li>
</ul></div>

