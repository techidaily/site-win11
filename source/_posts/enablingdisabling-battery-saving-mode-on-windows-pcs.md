---
title: Enabling/Disabling Battery Saving Mode on Windows PCs
date: 2024-11-06T20:33:42.911Z
updated: 2024-11-07T22:11:18.129Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Battery Saving Mode on Windows PCs
excerpt: This Article Describes Enabling/Disabling Battery Saving Mode on Windows PCs
keywords: Battery Saver Mode Windows,Disable Windows Battery Save,Enable Windows Power Efficient,Optimize Windows Battery Life,Turn Off Battery Saving PC,Manage Windows Power Settings,Configure Windows Energy Saver
thumbnail: https://thmb.techidaily.com/0b4edc9260dee73e74c6f70d4608ea90c51d96ccbc3b5f5a0008c722859666ad.jpg
---

## Enabling/Disabling Battery Saving Mode on Windows PCs

 Your Windows laptop features a handy battery saver mode that allows you to stretch your device's battery life. Windows archives this by lowering the screen brightness, limiting background processes, and disabling certain visual effects and animations.

 Here we show you how to enable or disable battery saver mode on your Windows 10 or 11 laptop.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The[Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the[many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn[the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

## Easily Enable or Disable Battery Saver Mode on Windows

 Battery saver mode in Windows can come in handy when you're away from a power source. However, it's important to note that leaving battery saver mode on all the time can impact certain features, such as notifications and background app sync. Hence, it's best to enable battery saver mode only when necessary.

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
<li><a href="https://some-tips.techidaily.com/new-the-clear-path-a-step-by-step-approach-to-buying-an-exceptional-4k-monitor/"><u>[New] The Clear Path A Step-By-Step Approach to Buying an Exceptional 4K Monitor</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-crafting-engaging-narratives-a-compreehensive-guide-to-adding-emojis-to-instagram-stories-for-2024/"><u>[Updated] Crafting Engaging Narratives A Compreehensive Guide to Adding Emojis to Instagram Stories for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-decoding-the-metrics-for-youtube-video-hierarchy-for-2024/"><u>[Updated] Decoding the Metrics for YouTube Video Hierarchy for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-banishing-unwanted-green-in-mac-recorded-youtube-content/"><u>[Updated] In 2024, Banishing Unwanted Green in Mac-Recorded YouTube Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-growth-by-numbers-tapping-into-youtube-analytics-power/"><u>[Updated] In 2024, Growth by Numbers Tapping Into YouTube Analytics Power</u></a></li>
<li><a href="https://win11.techidaily.com/ps3/"><u>「無料・迅速：動画をPS3用に適した形式にするテクニック」</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/identifying-bluetooth-support-on-your-notebook-simple-methods-for-discovery/"><u>Identifying Bluetooth Support on Your Notebook: Simple Methods for Discovery</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-tecno-spark-20-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Tecno Spark 20 Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/open-and-repair-doesnt-work-in-ms-excel-stellar-by-stellar-guide/"><u>Open and Repair Doesnt Work in MS Excel | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/pcsoundcloudmp3/"><u>PCによるSoundCloudからのMP3曲ダウンロード手順</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-your-dvd-collection-expert-tips-on-effortlessly-switching-from-dvd-to-mp4-offline-options-included/"><u>Preserving Your DVD Collection: Expert Tips on Effortlessly Switching From DVD to MP4, Offline Options Included!</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-effective-methods-for-converting-your-wma-audio-to-wav-quality/"><u>Quick & Effective Methods for Converting Your WMA Audio to WAV Quality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-crafting-tailored-listening-sessions-with-windows-media-player/"><u>Quick Guide to Crafting Tailored Listening Sessions with Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/returning-to-basics-the-revival-of-apples-traditional-roots/"><u>Returning to Basics: The Revival of Apple's Traditional Roots</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-the-ultimate-guide-to-watching-dvds-on-an-ipad/"><u>Seamless Transition: The Ultimate Guide to Watching DVDs on an iPad</u></a></li>
</ul></div>

