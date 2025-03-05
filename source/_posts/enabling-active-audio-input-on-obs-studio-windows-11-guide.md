---
title: Enabling Active Audio Input on OBS Studio - Windows 11 Guide
date: 2025-03-03T02:02:14.316Z
updated: 2025-03-05T01:37:08.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Active Audio Input on OBS Studio - Windows 11 Guide
excerpt: This Article Describes Enabling Active Audio Input on OBS Studio - Windows 11 Guide
keywords: OBS Audio Enablement,OBS Windows 11 Audio,Active Input OBS Studio,Windows 11 Audio Guide,Audio Setup in OBS,OBS Sound Activation,OBS Studio Windows Input
thumbnail: https://thmb.techidaily.com/a54e5c701c009258ccb5e3ebc68c482a0352d900bfe7620286533aaa04ebdf62.png
---

## Enabling Active Audio Input on OBS Studio - Windows 11 Guide

 OBS Studio is a free-to-use app that allows you to record gameplay and stream online. However, like any other application, it has its own share of flaws. Many users have reported that OBS Studio fails to record audio on their Windows 11 PC.

 Luckily, it's a very common issue and can quickly be resolved. Here are all the working solutions that will help you fix OBS Studio if it is unable to record audio.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart OBS Studio

 Before getting into advanced troubleshooting, consider restarting OBS Studio. The best way is to[launch the Task Manager](https://www.makeuseof.com/windows-open-device-manager/) and close all the OBS Studio-related processes.

 Next, relaunch the OBS Studio and check if it is able to record audio. If not, it's time for some more complicated fixes.

## 2\. Launch OBS Studio With Administrative Rights

 Oftentimes, issues in third-party applications occur due to a lack of administrative privileges. It can happen even when you're using an administrator account on your computer.

 The best way to resolve this problem is to configure OBS Studio to always launch as an administrator. To do that, follow the below steps:

1. Right-click on the OBS Studio icon and choose**Properties** from the context menu.
2. In the Properties window, switch to the**Compatibility** tab.
3. Check the**Run this program as an administrator** option.  
![Run as admin option for OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-as-admin-option.jpg)
4. Click**Apply** \>**OK** to save the settings.

## 3\. Unmute OBS Studio in the Settings App

 OBS Studio will fail to record audio if it is muted in the Settings app. Here's how to check and change OBS Studio sound settings in the Settings app.

1. Open the**Settings** app (see how to[launch the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar.
2. Select**Sound** from the right pane.
3. Under the**Advanced section,** choose the**Volume Mixer** option.
4. Under the**Apps section,** unmute OBS Studio if muted and adjust the slider accordingly.  
![Unmute OBS Studio in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unmute-obs-studio.jpg)
5. Also, click the drop-down icon next to OBS Studio, then choose the correct input device.  

![Choosing default audio device for OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-default-audio-device.jpg)

Restart OBS Studio and check if the problem persists.

## 4\. Use the Correct Recording Device

 Windows allows you to manually choose recording and playback devices. But if you've chosen an incorrect recording device in Settings, then you're likely to face this issue. To fix this, you will have to configure the correct device as the default recording option. Here's how to do that:

1. Open the**Settings** app, and head towards**System** \>**Sound.**
2. Choose**More sound settings** under the**Advanced section.**
3. Switch to the**Recording** tab.
4. Right-click on the correct recording device and choose the**Set as Default Device** option from the context menu.  
![Set as default option in Sound properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/set-as-default-option.jpg)
5. Click**Apply** and then**OK.**

## 5\. Allow OBS Studio to Access Microphone

[Windows 11 is big on privacy and security](https://www.makeuseof.com/windows-11-privacy-options-explained/) . The OS lets you allow or restrict apps from accessing certain services of your computer. For instance, you can restrict apps from using the microphone on your computer.

 As such, if you've mistakenly restricted OBS Studio from accessing the microphone, then you'll face audio issues. The solution here is to allow OBS Studio to access the microphone. Here's how:

1. Open the Settings app and choose**Privacy & Security** from the left sidebar.
2. Under the**App permission** section, select the**Microphone** option.
3. Enable the toggle next to the**Microphone access** option.  
![Microphone access option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/microphone-access.jpg)
4. Next, enable the toggle next to**Let desktop apps to access your microphone** option.  

![Allow desktop apps to access microphone option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-desktop-apps-to-access-microphone.jpg)

## 6\. Change the OBS Studio Settings

 OBS Studio lets you manually set audio devices and adjust their settings as per your preference. However, OBS Studio will be unable to record audio if you have chosen an incorrect audio device within its settings.

 So, head toward the OBS Studio audio settings, and choose the correct audio device to solve the issue. Here are the steps to do it:

1. Launch OBS Studio and choose**File** from the top-left corner.
2. Choose**Settings** from the context menu.
3. In the Settings window, select**Audio** from the left sidebar.
4. Under the**Global Audio Devices** section, click the drop-down icon next to**Desktop Audio** and**Desktop Audio 2** and choose**Default** in both options.
5. Next, click the drop-down icon next to**Mic/Auxiliary Audio** and**Mic/Auxiliary Audio 2** and choose**Default** in both options.  
![Audio settings of OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/audio-settings.jpg)
6. Choose**Apply** \>**OK** to save the changes.

## 7 . Adjust the Audio Mixer Settings

 The next solution on the list is to adjust the audio mixer settings of the OBS Studio. Here's how:

1. Open OBS Studio.
2. Under the**Audio Mixer** section, adjust the**Mic/Aux** slider to**\-2.1dB.**  
![Adjusting dB in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/adjusting-db.jpg)
3. Click the three dots next to Mic/Aux and choose**Properties.**

4. Click the drop-down icon next to**Device,** select your default recording device and click**OK.**  
![Choosing correct Mic in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-correct-mic.jpg)
5. Next, click the three dots next to Mic/Aux again and choose**Advanced Audio Properties.**  
![Choosing Advanced properties in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-properties.jpg)
6. Under the**Audio Monitoring** tab, choose**Monitor** **and Output** for**Desktop Audio** and**Monitor Only** **(mute output)** for**Mic/Aux.**  

![Adjusting Advanced Properties in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/adjusting-advanced-properties.jpg)

## 8\. Download the Latest Audio Driver Updates

 A corrupt or outdated audio driver can also be a prime reason why OBS Studio is unable to record audio. To fix this, you will have to[update the audio driver on Windows](https://www.makeuseof.com/how-to-update-audio-drivers-windows-11/) .

You can do that by following the below steps:

1. Press the**Win + X** hotkeys and choose**Device Manager** from the list.
2. Double-click the**Sound, video, and game controllers** node to expand it.
3. Right-click on your default recording device and select**Update driver** from the context menu.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-driver-2.jpg)
4. Choose**Search automatically for drivers** option in the window that crops up.

 Next, allow Windows to search for and download any available driver updates for your recording device.

## 9\. Reinstall OBS Studio

 Are you still facing the issue? If yes, then there's something wrong with the OBS Studio installation file that's causing the problem. The only solution, in this case, is to reinstall the OBS Studio.

## Enjoy Uninterrupted Recording Again on OBS Studio for Windows

 OBS Studio is everyone's first choice to stream online, and there's a strong reason behind it. But sometimes, misconfigured Windows or OBS Studio settings can cause the audio issue. Fortunately, you can quickly get rid of this issue by following the above fixes.

 However, if you think it's time for a change, there are a few OBS Studio alternatives that are worth a try.

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-prime-6-social-sites-boosting-biz-success/"><u>[New] 2024 Approved Prime 6 Social Sites Boosting Biz Success</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-a-wealthy-beauty-channel-host/"><u>Becoming a Wealthy Beauty Channel Host</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-the-windows-11-bar-a-comprehensive-approach/"><u>Conquer the Windows 11 Bar: A Comprehensive Approach</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/effortless-dvd-winx-dvd-copy-iso/"><u>Effortless DVD 복사기 WinX DVD Copy 활용: 원형 ISO 제작 기술에 대한 간단한 안내</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-unlock-your-pcs-credentials-with-these-11-win11-tricks/"><u>Effortlessly Unlock Your PC’s Credentials with These 11 Win11 Tricks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-insiders-guide-to-pro-windows-10-expertise/"><u>In 2024, Insider's Guide to Pro WINDOWS 10 Expertise</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-apple-iphone-15-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 5 Tracking Apps to Track Apple iPhone 15 Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-turning-vlogging-into-cash-essential-steps/"><u>In 2024, Turning Vlogging Into Cash Essential Steps</u></a></li>
<li><a href="https://win11.techidaily.com/learn-9-ways-to-navigate-through-windows-audio-settings-panel/"><u>Learn 9 Ways to Navigate Through Windows Audio Settings Panel</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-noninteractive-elements-on-windows-11/"><u>Overcoming Noninteractive Elements on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-silent-audio-issues-during-valorant-playthroughs-on-windows/"><u>Overcoming Silent Audio Issues During Valorant Playthroughs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-to-your-gaming-hardware-information-in-win11/"><u>Quick Access to Your Gaming Hardware Information in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-server-unavailable-for-ea-on-windows/"><u>Tackling Server Unavailable for EA on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-discovering-deleting-null-space-in-windows-systems/"><u>The Ultimate Guide: Discovering, Deleting Null Space in Windows Systems</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210659820-9781638740889-thoughts-from-a-mothers-love/"><u>Thoughts from a Mother's Love | Free Book</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/what-does-jailbreaking-iphone-12-pro-max-i-do-get-answers-here-by-drfone-ios/"><u>What Does Jailbreaking iPhone 12 Pro Max i Do? Get Answers here</u></a></li>
</ul></div>

