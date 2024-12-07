---
title: Secure Optimal Performance in Win11 - Learn the Top Availability Verification Steps
date: 2024-12-05T16:01:22.512Z
updated: 2024-12-07T10:44:13.105Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure Optimal Performance in Win11 - Learn the Top Availability Verification Steps
excerpt: This Article Describes Secure Optimal Performance in Win11 - Learn the Top Availability Verification Steps
keywords: Win11 Security Boost,Secure Win11 Performance,Optimize Win11 Stability,Enhance Win11 Reliability,Verify Win11 Availability,Top Win11 Steps,Properly Test Win11
thumbnail: https://thmb.techidaily.com/33028f93fa14d69bbcfce2acf14136a66954cb281abb62aff639869e465c0177.jpg
---

## Secure Optimal Performance in Win11 - Learn the Top Availability Verification Steps

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the[many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)

## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these[best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.

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
<li><a href="https://extra-support.techidaily.com/updated-movavi-video-editors-2024-update-a-deep-dive-review/"><u>[Updated] Movavi Video Editor's 2024 Update A Deep Dive Review</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069717623-updated-utilizing-internal-screen-recording-on-huaweis-mate-1020-and-p-models-p20-p10-for-2024/"><u>[Updated] Utilizing Internal Screen Recording on Huawei's Mate 10/20 & P Models (P20, P10). For 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/blur-no-more-top-10-web-photo-sharpening-apps/"><u>Blur No More! Top 10 Web Photo Sharpening Apps</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-tackling-not-empty-directive-error-in-windows/"><u>Expert Guide to Tackling Not Empty Directive Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/faster-updates-no-frustration-9-fixes-for-verifying-installer-speed/"><u>Faster Updates, No Frustration: 9 Fixes for Verifying Installer Speed</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-iphone-se-by-drfone-ios/"><u>Guide on How To Remove Apple ID From iPhone SE</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-visual-disk-space-analyzer-tool-to-the-context-menu-in-windows-10-and-11/"><u>How to Add a Visual Disk Space Analyzer Tool to the Context Menu in Windows 10 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unsaved-sound-adjustments-in-windows/"><u>Preventing Unsaved Sound Adjustments in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-muted-microphone-recordings-with-obs-in-windows-11/"><u>Rectifying Muted Microphone Recordings with OBS in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/running-windows-11-in-mac-a-parallels-guide/"><u>Running Windows 11 in Mac: A Parallels Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/ultimate-list-best-high-definition-blu-ray-decks-for-2024/"><u>Ultimate List Best High-Definition Blu-Ray Decks for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/windows-leading-video-chat-pros-top-8-for-2024/"><u>Windows' Leading Video Chat Pros Top 8 for 2024</u></a></li>
</ul></div>

