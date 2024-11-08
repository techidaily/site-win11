---
title: How To Reverse Color Mismatch in Microsoft Store
date: 2024-11-03T22:59:53.325Z
updated: 2024-11-07T16:58:11.678Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Reverse Color Mismatch in Microsoft Store
excerpt: This Article Describes How To Reverse Color Mismatch in Microsoft Store
keywords: Fixing Color Issues MS,MS Store Color Fix,Reverse Color Mismatch MS,Correct Colour MS St,Mismatched Colors MS,Microsoft Store Color Fixed,Hack Color Mismatch MS
thumbnail: https://thmb.techidaily.com/0f9975c7424be8ab80f0e3edfa04cf204d756fbbde35db8886dbe8cbc049b368.jpg
---

## How To Reverse Color Mismatch in Microsoft Store

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these[reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re[dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

 Also, you can[manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to[how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to[factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Microsoft Store Working Again

 It can be frustrating when you need to install a new app, but Microsoft Store isn’t working. Instead of looking for the same app on not-so-trustworthy websites, you can use the above solutions to fix Microsoft Store.

 But if you can’t find a specific app, there are several websites where you can download apps without compromising your system security.

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-essential-list-top-10-free-copyright-safe-chants-for-calm/"><u>[New] 2024 Approved Essential List Top 10 Free, Copyright-Safe Chants for Calm</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-top-8-android-visionaries-for-speedy-videos-for-2024/"><u>[New] Top 8 Android Visionaries for Speedy Videos for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-stepwise-strategies-building-a-playlist-on-youtube/"><u>2024 Approved Stepwise Strategies Building a Playlist on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/curating-a-list-of-top-windows-11-sketch-apps/"><u>Curating a List of Top Windows 11 Sketch Apps</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95782445-9781591437796-delusions-in-science-and-spirituality/"><u>Delusions in Science and Spirituality | Free Book</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s24plus-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S24+ Phone without Google Account?</u></a></li>
<li><a href="https://win11.techidaily.com/innovating-windows-11-6-changes-that-could-revolutionize-the-taskbar/"><u>Innovating Windows 11: 6 Changes that Could Revolutionize the Taskbar</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/movavionline-aacogg/"><u>Movaviで簡単な無料Online AACファイルを直接OGG形式に変換可能</u></a></li>
<li><a href="https://win11.techidaily.com/solving-slowness-issues-with-windows-monitor-app/"><u>Solving Slowness Issues with Windows Monitor App</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-installing-arduino-drivers-in-windows/"><u>Step-by-Step Guide: Installing Arduino Drivers in Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/swift-remedies-for-chatgpt-log-in-errors/"><u>Swift Remedies for ChatGPT Log-In Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-overcoming-common-windows-update-configuration-errors/"><u>Troubleshooting Tips: Overcoming Common Windows Update Configuration Errors</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-interrupt-at-breakpoint-in-debugging/"><u>Understanding and Solving 'Interrupt at Breakpoint' In Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/work-smart-not-harder-top-time-management-windows-apps/"><u>Work Smart, Not Harder: Top Time Management Windows Apps</u></a></li>
</ul></div>

