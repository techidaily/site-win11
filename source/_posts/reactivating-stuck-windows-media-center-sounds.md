---
title: Reactivating Stuck Windows Media Center Sounds
date: 2024-09-10T20:36:52.261Z
updated: 2024-09-17T01:34:05.363Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Stuck Windows Media Center Sounds
excerpt: This Article Describes Reactivating Stuck Windows Media Center Sounds
keywords: Media Center Sound Fix,WMCSound Troubleshoot,Media Player Reset,Windows Media Stop,Tweak Media Audio,Media Sound Reactivate,Windows Media Sounds Fix
thumbnail: https://thmb.techidaily.com/beb79c97cd88302125e646092101e6316bc065b6e8c0e4d468eed617783ebeeb.jpg
---

## Reactivating Stuck Windows Media Center Sounds

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Windows Audio Service

 Typically, the Windows Audio service starts automatically when your computer boots. However, if the service encounters any problems during startup, it may malfunction. If it's just a one-off glitch, restarting the Windows Audio service should fix the issue. Hence, you should start with that.

To restart the Windows Audio service:

1. Press**Win + S** to open the search menu.
2. Type**services** in the text box and press**Enter** .
3. In the Services window, scroll down to locate the**Windows Audio** service on the list. Then, right-click on it and select**Restart** .  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

## 2\. Make Sure the Supporting Audio Components Are Running

 Windows Audio service relies on several system components to function properly on your PC. If one of these components is not running, audio services may stop responding.

Here’s how to check if the required services are running.

1. Press**Win + R** to open the Run dialog box.
2. Type**services.msc** in the Open field and press**Enter** .
3. Locate the**RPC Endpoint Mapper** service on the list and double-click on it to open its properties.
4. Click the drop-down menu next to**Startup type** to select**Automatic** .
5. Click**Apply** followed by**OK** .
6. Similarly, change the startup type for**Remote Procedure Call (RPC)** and**DCOM Server Process Launcher** services as well.  
![Remote Procedure Call Service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remote-procedure-call-service-in-windows.jpg)

Restart your PC after this and check if the issue is still there.

## 3\. Add Local and Network Services Using Command Prompt

 Another thing you can do to resolve this issue is to register local and network services on Windows using Command Prompt. Here are the steps for the same.

1. Right-click on the**Start icon** or press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press**Enter** to register network services on your system.  
`net localgroup Administrators /add networkservice`
5. Now run the following command to register local services:  
`net localgroup Administrators /add localservice`
6. Exit the Command Prompt window and then restart your PC.  
![Add Local and Network Services Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-local-and-network-services-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on[how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the[best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
2. Now use one of the[many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on[how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Perform a System Restore

 System Restore is a useful feature on Windows that creates a backup of your entire system at predefined intervals. It can help you restore your system to the point before the problem occurred.

 System Restore will undo any recent changes made to your computer and resolve the issue for good. Don’t worry, this process won’t affect any of your personal data.

To perform a system restore on Windows, use these steps:

1. Right-click on the**Start** icon and select**Run** from the list.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the issue first appeared and hit**Next** .
7. Review all the details and click**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-dialog-on-windows.jpg)

 Wait for Windows to restart and revert to the specified restore point. After that, the audio services should work fine.

## Fixing Audio Services on Windows Is Easy

 It can be confusing if the audio services on Windows suddenly become unresponsive. In most cases, manually restarting the audio services should resolve the issue. If not, you may have to go through the trouble of scanning the system files or performing a system restore.

 That said, if none of the above solutions work, you can consider resetting your Windows computer or performing an in-place upgrade as a last resort.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-the-ultimate-review-gopro-hero5-adventure-footage/"><u>[New] 2024 Approved The Ultimate Review GoPro Hero5 Adventure Footage</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44ot44oq44ot44oq44gl44kj6ksh5pww5yuv55s744gu6zug5lit44oa44km44oz44ot44o844oj5oml6acg44cn/"><u>「ビリビリから複数動画の集中ダウンロード手順」</u></a></li>
<li><a href="https://win11.techidaily.com/2024-youtube/"><u>2024年用: YouTubeコンテンツをメモリースティックにバックアップする専門的な方法</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-motorola-moto-g04-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5l255so44gx44gm44ge44kl6zplusz5aow44ov44kp44o844oe44od44oi44gu56k66kqn5pa55rov44co6zplusz5aow56ym5yplus35yyw44k544kt44o844og44ob44kn44od44kv44cp/"><u>使用している音声フォーマットの確認方法『音声符号化スキームチェック』</u></a></li>
<li><a href="https://win11.techidaily.com/1726029196115-youtube/"><u>最高の解決策! YouTube動画をセキュリティ保証付きでダウンロードするためのベストソフト選び方</u></a></li>
<li><a href="https://fox-that.techidaily.com/addressing-calendar-anomalies-retrieving-lost-events-on-iphones/"><u>Addressing Calendar Anomalies: Retrieving Lost Events on iPhones</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-realme-c55-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Realme C55 Fingerprint Lock</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-poco-c50-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Poco C50 FRP In 3 Different Ways</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-windows-11s-hidden-know-how-for-media-importing/"><u>In 2024, Unveiling Windows 11'S Hidden Know-How for Media Importing</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-apple-iphone-12-pro-look-no-further-drfone-by-drfone-virtual-ios/"><u>Looking For A Location Changer On Apple iPhone 12 Pro? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1726030664644-pc8/"><u>PCに最適!人気の絶対必見ビデオ記録ソフト8本載流</u></a></li>
<li><a href="https://win11.techidaily.com/1726030030603-pcyoutube/"><u>PCを使ったYouTubeショートムービーの手順と最適アプリ選び：ステップバイステップレシピ</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-ultimate-guide-to-boosting-views-on-tiktok-unboxings/"><u>The Ultimate Guide to Boosting Views on TikTok Unboxings</u></a></li>
</ul></div>

