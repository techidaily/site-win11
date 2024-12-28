---
title: "Efficient Use of RAM in Cross-Device Service Platforms: Windows Tips"
date: 2024-12-22T01:07:37.862Z
updated: 2024-12-28T00:09:34.030Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient Use of RAM in Cross-Device Service Platforms: Windows Tips"
excerpt: "This Article Describes Efficient Use of RAM in Cross-Device Service Platforms: Windows Tips"
keywords: RAM Efficiency Tricks,RAM Usage Guide,Optimize RAM Windows,Device RAM Management,Cross-Platform RAM Tips,Service Platforms RAM Saving,Window RAM Utilization
thumbnail: https://thmb.techidaily.com/3e134df3d1e30ff21305cf90a72d9a508b70a320e15fdc18733cb673b02e8a47.jpg
---

## Efficient Use of RAM in Cross-Device Service Platforms: Windows Tips

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-add-music-in-premiere-pro/"><u>[New] 2024 Approved Add Music In Premiere Pro</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-swift-video-editing-made-easy-with-top-iosdesktop-apps-8/"><u>[New] Swift Video Editing Made Easy with Top iOS/Desktop Apps #8</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ideal-selections-the-best-9-mobile-video-meeting-solutions-reviewed-for-2024/"><u>[Updated] Ideal Selections The Best 9 Mobile Video Meeting Solutions Reviewed for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-ultimate-guide-to-effective-reddit-sharing/"><u>[Updated] The Ultimate Guide to Effective Reddit Sharing</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>3 Things You Must Know about Fake Snapchat Location On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-0x800713f-halt-in-windows-11-mail/"><u>Eliminating 0X800713F Halt in Windows 11 Mail</u></a></li>
<li><a href="https://win11.techidaily.com/executing-system-file-checker-with-ease-in-windows/"><u>Executing System File Checker with Ease in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nokia-c22-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nokia C22 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-momentum-masters-youtubes-freshly-watched-hits/"><u>In 2024, Momentum Masters Youtube’s Freshly Watched Hits</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-malware-control-strategies-to-tackle-unavailable-defender-engine/"><u>Mastering Malware Control: Strategies To Tackle Unavailable Defender Engine</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-your-windows-11-experience-with-forgotten-features/"><u>Maximizing Your Windows 11 Experience with Forgotten Features</u></a></li>
<li><a href="https://win11.techidaily.com/mending-winget-glitches-on-modern-windows/"><u>Mending Winget Glitches on Modern Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-5-best-free-video-rotation-apps-for-iphone-users/"><u>New 5 Best Free Video Rotation Apps for iPhone Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-obs-recording-glitch-on-windows/"><u>Steps to Overcome OBS Recording Glitch on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-smart-shift-ais-role-in-windows-software-evolution/"><u>The Smart Shift: AI's Role in Windows Software Evolution</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11s-help-app-malfunction/"><u>Troubleshooting Windows 11'S Help App Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/typing-titanics-crafting-custom-hotkeys-to-snap-and-snag-predefined-text/"><u>Typing Titanics: Crafting Custom Hotkeys to Snap and Snag Predefined Text</u></a></li>
</ul></div>

