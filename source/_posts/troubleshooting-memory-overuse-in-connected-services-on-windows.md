---
title: Troubleshooting Memory Overuse in Connected Services on Windows
date: 2024-09-20T07:38:50.810Z
updated: 2024-09-22T04:44:01.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Memory Overuse in Connected Services on Windows
excerpt: This Article Describes Troubleshooting Memory Overuse in Connected Services on Windows
keywords: Memory Woes,Service Overload Fix,Windows Memory Issue,Optimize Windows Usage,Reduce PC Memory Waste,Clear Windows Glitches,Enhance Connected Services
thumbnail: https://thmb.techidaily.com/965071db1f866296dbd6b7c6cdfb4395621995dd58483ee49e8397ad83cab217.jpg
---

## Troubleshooting Memory Overuse in Connected Services on Windows

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/remium-7-video-gear-ideas-for-captivating-vloggers/"><u>[New] Premium 7 Video Gear Ideas for Captivating Vloggers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-powerpoint-to-video-best-practices-with-webcams-now-for-2024/"><u>[Updated] PowerPoint to Video Best Practices with Webcams, Now for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44ot44oq44ot44oq44gl44kj6ksh5pww5yuv55s744gu6zug5lit44oa44km44oz44ot44o844oj5oml6acg44cn/"><u>「ビリビリから複数動画の集中ダウンロード手順」</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-best-8-linux-platforms-for-video-mastery/"><u>2024 Approved Best 8 Linux Platforms for Video Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/2024-youtube/"><u>2024年用: YouTubeコンテンツをメモリースティックにバックアップする専門的な方法</u></a></li>
<li><a href="https://win11.techidaily.com/5l255so44gx44gm44ge44kl6zplusz5aow44ov44kp44o844oe44od44oi44gu56k66kqn5pa55rov44co6zplusz5aow56ym5yplus35yyw44k544kt44o844og44ob44kn44od44kv44cp/"><u>使用している音声フォーマットの確認方法『音声符号化スキームチェック』</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-walkthrough-setting-up-and-enjoying-houseparty-on-your-pc/"><u>A Complete Walkthrough: Setting Up and Enjoying Houseparty on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/access-amazon-prime-video-content-for-free-on-any-device-with-a-secure-authorized-solution-using-kodi-no-need-for-premium-subscription/"><u>Access Amazon Prime Video Content for Free on Any Device with a Secure, Authorized Solution Using Kodi - No Need for Premium Subscription</u></a></li>
<li><a href="https://win11.techidaily.com/androidmkv/"><u>AndroidスマホでMKV再生設定・視聴障害の解消手順</u></a></li>
<li><a href="https://youtube-data.techidaily.com/al-dollars-kings-and-queens-youtube-edition-for-2024/"><u>Digital Dollars Kings & Queens YouTube Edition for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/foremost-dialogue-maker-hub/"><u>Foremost Dialogue Maker Hub</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-breakthrough-tactics-for-capturing-virtual-conferences/"><u>In 2024, Breakthrough Tactics for Capturing Virtual Conferences</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-charting-the-financial-landscape-of-youtube-marketing/"><u>In 2024, Charting the Financial Landscape of YouTube Marketing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-frame-your-story-a-guide-to-insta-video-bordering/"><u>In 2024, Frame Your Story A Guide to Insta Video Bordering</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-full-exploration-new-features-in-videoshow-app-24/"><u>In 2024, Full Exploration New Features in VideoShow App '24</u></a></li>
</ul></div>

