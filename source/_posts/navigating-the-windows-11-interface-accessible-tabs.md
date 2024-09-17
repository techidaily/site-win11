---
title: "Navigating the Windows 11 Interface: Accessible Tabs"
date: 2024-09-14T06:15:47.288Z
updated: 2024-09-17T06:34:22.275Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating the Windows 11 Interface: Accessible Tabs"
excerpt: "This Article Describes Navigating the Windows 11 Interface: Accessible Tabs"
keywords: Win11TabsAccessibility,Windows11TabInterface,NewWinNavGuide,EasyWindowsNavigation,TabSwitchingWindows,Windows11EaseOfUse,IntuitiveWin11UX
thumbnail: https://thmb.techidaily.com/99663f80a681577ef6d172804500e3555c286bc17d7a19ae0d763067c374fc29.jpg
---

## Navigating the Windows 11 Interface: Accessible Tabs

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and[check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily[download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-top-5-free-screen-recorder-extensions-for-chromebooks/"><u>[New] 2024 Approved TOP 5 Free Screen Recorder Extensions for Chromebooks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-guide-to-producing-effective-youtube-promo-videos/"><u>[Updated] 2024 Approved Guide to Producing Effective YouTube Promo Videos</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723862740728-710-deal-on-core-i5-12450h-alienexchange-swap-keyboard-for-spectacular-16-inch-dual-displays/"><u>$710 Deal on Core I5-12450H AlienExchange - Swap Keyboard for Spectacular 16-Inch Dual Displays!</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-tailoring-your-podcast-content-with-seo-in-mind/"><u>2024 Approved Tailoring Your Podcast Content with SEO in Mind</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-eradicating-a-drives-partition-on-pc/"><u>Essential Steps for Eradicating a Drives Partition on PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-iphone-11-pro-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For iPhone 11 Pro?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-infinix-hot-40-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Infinix Hot 40 using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-to-vector-art-dive-into-basics-forms-and-software/"><u>New to Vector Art? Dive Into Basics, Forms, and Software</u></a></li>
<li><a href="https://data-wizards.techidaily.com/perfect-pixels-curing-video-with-interlace-issues/"><u>Perfect Pixels: Curing Video with Interlace Issues</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-couldnt-access-page-issue-with-ms-store/"><u>Remedying 'Couldn't Access' Page Issue with MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sound-on-windows-mastering-the-art-of-driver-update/"><u>Streamlined Sound on Windows: Mastering the Art of Driver Update</u></a></li>
<li><a href="https://win11.techidaily.com/the-case-for-continuing-with-classic-windows-10-compelling-reasons/"><u>The Case for Continuing with Classic Windows 10: Compelling Reasons</u></a></li>
</ul></div>

