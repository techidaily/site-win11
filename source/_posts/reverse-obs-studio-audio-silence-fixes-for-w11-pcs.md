---
title: "Reverse OBS Studio Audio Silence: Fixes for W11 PCs"
date: 2024-06-25T11:24:19.772Z
updated: 2024-06-26T11:24:19.772Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reverse OBS Studio Audio Silence: Fixes for W11 PCs"
excerpt: "This Article Describes Reverse OBS Studio Audio Silence: Fixes for W11 PCs"
keywords: Reverse OBS Silence,Audio Fix W11,PC Silence Issue,OBS Studio Troubleshoot,W11 Noise Reduction,Audio Silence Solutions,OBS Silent Mode
thumbnail: https://thmb.techidaily.com/a6232b975632e43de71e5ab6217eebf552fc531569d56d79c1b10e2acedb4321.png
---

## Reverse OBS Studio Audio Silence: Fixes for W11 PCs

 OBS Studio is a free-to-use app that allows you to record gameplay and stream online. However, like any other application, it has its own share of flaws. Many users have reported that OBS Studio fails to record audio on their Windows 11 PC.

 Luckily, it's a very common issue and can quickly be resolved. Here are all the working solutions that will help you fix OBS Studio if it is unable to record audio.

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
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-e8024002e-for-updates/"><u>Bypassing Windows Error E:8024002E for Updates</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-digital-persona-username-overhaul-guide/"><u>Upgrading Your Digital Persona: UserName Overhaul Guide</u></a></li>
<li><a href="https://win11.techidaily.com/type-smartly-and-fast-typingaid-secrets/"><u>Type Smartly and Fast - TypingAid Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/the-overlooked-duo-of-windows-monitoring-metrics/"><u>The Overlooked Duo of Windows Monitoring Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-user-authentication-management-for-domains-in-w11/"><u>Perfecting User Authentication Management for Domains in W11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clumped-up-windows-11-icon-grouping/"><u>Adjusting Clumped-Up Windows 11 Icon Grouping</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-syncs-a-guide-to-onedrive-operations-on-windows/"><u>Fixing Failed Syncs: A Guide to OneDrive Operations on Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-some-leading-ai-tools-to-replace-sky-backgrounds/"><u>Updated 2024 Approved Some Leading AI Tools to Replace Sky Backgrounds</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-6-unique-sources-for-premium-youtube-imagery/"><u>[New] Top 6 Unique Sources for Premium YouTube Imagery</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-top-10-insta-management-gadgets-for-boosting-engagement/"><u>In 2024, Top 10 Insta Management Gadgets for Boosting Engagement</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-top-tier-emulators-for-gba-games-on-android/"><u>[Updated] 2024 Approved  Top-Tier Emulators for GBA Games on Android</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-vivo-y36-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Vivo Y36 Phone Hassle-Free</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-looms-lens-sharpen-your-recording-skills-for-2024/"><u>[Updated] Loom's Lens  Sharpen Your Recording Skills for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-innovative-igtv-thumbnail-upgrades-guide/"><u>[New] In 2024, Innovative IGTV Thumbnail Upgrades Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-compreenas-guide-to-choosing-ideal-lenses-for-filmmaking/"><u>A Compreenas Guide to Choosing Ideal Lenses for Filmmaking</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-boosting-your-channel-a-guide-to-amassing-viewers/"><u>[Updated] Boosting Your Channel  A Guide to Amassing Viewers</u></a></li>
</ul></div>
