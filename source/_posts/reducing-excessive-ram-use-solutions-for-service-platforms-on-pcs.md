---
title: "Reducing Excessive RAM Use: Solutions for Service Platforms on PCs"
date: 2025-01-31T22:49:11.338Z
updated: 2025-02-04T05:52:19.902Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reducing Excessive RAM Use: Solutions for Service Platforms on PCs"
excerpt: "This Article Describes Reducing Excessive RAM Use: Solutions for Service Platforms on PCs"
keywords: RAM Efficiency Tips,Minimize RAM Usage,Optimal RAM Settings,Reduce RAM Consumption,Service Platform RAM Saving,PC RAM Management,Limit Excessive RAM
thumbnail: https://thmb.techidaily.com/4f0baa4676690f713a7c64c49fa175c4aff67762b3efda1ae17d3bfe6d387995.jpg
---

## Reducing Excessive RAM Use: Solutions for Service Platforms on PCs

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-televisual-enhancements-through-engaging-fb-livestreams-for-2024/"><u>[New] Televisual Enhancements Through Engaging FB Livestreams for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/wist-your-way-through-youtube-mastering-rotation-techniques-for-2024/"><u>[New] Twist Your Way Through YouTube Mastering Rotation Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-the-beginner-pro-marketing-playbook-secrets-of-facebook-success-for-2024/"><u>[Updated] The Beginner-Pro Marketing Playbook Secrets of Facebook Success for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209838180-9780991345748-a-journey-of-possibilities/"><u>A Journey of Possibilities | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/de-jam-your-devices-top-9-solutions-for-unstuck-windows-setup/"><u>De-Jam Your Devices: Top 9 Solutions for Unstuck Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-steam-authentication-errors-a-rust-powered-windows-approach/"><u>Dealing with Steam Authentication Errors: A Rust-Powered Windows Approach</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-update-intel-hd-graphics-5500-drivers-find-download-and-install/"><u>Easy Update: Intel HD Graphics 5500 Drivers - Find, Download and Install</u></a></li>
<li><a href="https://win11.techidaily.com/ensure-your-windows-screenscape-remains-same/"><u>Ensure Your Windows Screenscape Remains Same</u></a></li>
<li><a href="https://win11.techidaily.com/evade-windows-sign-in-sequence-with-short-term-profiles/"><u>Evade Windows Sign-In Sequence with Short-Term Profiles</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-xbox-controller-for-pc/"><u>Fixing a Non-Functional Xbox Controller for PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-intellij-unison-back-up-and-running-on-win11/"><u>How to Get IntelliJ Unison Back Up & Running on Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-14-pro-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on Apple iPhone 14 Pro</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-15-pro-max-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Pro Max Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/quickly-enhance-graphics-performance-with-a-simple-intel-hd-update-on-w10/"><u>Quickly Enhance Graphics Performance with a Simple Intel HD Update on W10.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/recognizing-pretend-predictions-a-guide-to-authentic-vs-fake-ai-analysis/"><u>Recognizing Pretend Predictions: A Guide to Authentic Vs. Fake AI Analysis</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-problems-making-your-airpods-mic-work-again-on-windows-11/"><u>Solving Audio Problems: Making Your AirPods Mic Work Again on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-correct-opengl-error-3-in-nvidia-gpus-win1011/"><u>Strategies to Correct OpenGL Error 3 in Nvidia GPUs (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/swift-system-solutions-the-essential-10-tools/"><u>Swift System Solutions: The Essential 10 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/windows-teammers-your-screens-puzzle/"><u>Windows Teammers, Your Screen's Puzzle</u></a></li>
</ul></div>

