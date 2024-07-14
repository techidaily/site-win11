---
title: "Reverse OBS Studio Audio Silence: Fixes for W11 PCs"
date: 2024-07-13T09:51:29.390Z
updated: 2024-07-14T09:51:29.390Z
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

 Before getting into advanced troubleshooting, consider restarting OBS Studio. The best way is to [launch the Task Manager](https://www.makeuseof.com/windows-open-device-manager/) and close all the OBS Studio-related processes.

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

1. Open the**Settings** app (see how to [launch the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar.
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

 A corrupt or outdated audio driver can also be a prime reason why OBS Studio is unable to record audio. To fix this, you will have to [update the audio driver on Windows](https://www.makeuseof.com/how-to-update-audio-drivers-windows-11/) .

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
<li><a href="https://win11.techidaily.com/discover-file-systems-better-with-diskspace-added-to-windows-menu/"><u>Discover File Systems Better with Diskspace Added to Windows Menu</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-comprehensive-list-top-rated-srt-translation-services/"><u>[Updated] A Comprehensive List  Top-Rated SRT Translation Services</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-enhance-your-watch-experience-with-faster-instagram-videos/"><u>[New] 2024 Approved  Enhance Your Watch Experience with Faster Instagram Videos</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fcpx-audio-editing-essentials-l-cuts-j-cuts-and-more/"><u>FCPX Audio Editing Essentials L-Cuts, J-Cuts, and More</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-instagram-video-dimensions-what-you-need-to-know-for-maximum-engagement/"><u>2024 Approved Instagram Video Dimensions What You Need to Know for Maximum Engagement</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-strategies-for-enhancing-clarity-eliminating-unwanted-noise-from-internet-streamed-music-and-voices/"><u>New 2024 Approved Strategies for Enhancing Clarity Eliminating Unwanted Noise From Internet-Streamed Music and Voices</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-nubia-red-magic-9-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Nubia Red Magic 9 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-get-your-fb-message-videos-flowing-again-on-mobile-devices/"><u>[Updated] In 2024, How to Get Your FB Message Videos Flowing Again on Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-long-start-ups-in-windows-11-easily-and-swiftly/"><u>Conquering Long Start-Ups in Windows 11 Easily and Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-visual-upgrades-with-themes-from-microsoft-store/"><u>Harnessing Visual Upgrades with Themes From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-cant-connect-nvidia-error-on-win-11-devices/"><u>Bypassing the Can't Connect Nvidia Error on Win 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-iphone-x-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For iPhone X</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-files-vanish-permanently-in-your-desktop-trash-bin-windows-11/"><u>How to Make Files Vanish Permanently in Your Desktop Trash Bin (Windows 11)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-olympic-ice-showdown-highlights-of-speed-skating-short-track/"><u>[New] Olympic Ice Showdown  Highlights of Speed Skating Short Track</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-and-changing-login-credentials-in-win-11/"><u>Guide to Resetting and Changing Login Credentials in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-10-best-hashtag-tracker-for-facebook-twitter-and-instagram/"><u>[New] 2024 Approved  10 Best Hashtag Tracker for Facebook, Twitter and Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-make-a-private-story-on-snapchat-a-complete-guide/"><u>In 2024, How to Make a Private Story on Snapchat  A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://extra-information.techidaily.com/champions-of-cutting-edge-vr-creation/"><u>Champions of Cutting-Edge VR Creation</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-os-alerts-utilizing-command-prompt-to-identify-and-resolve-windows-issues/"><u>Interpreting OS Alerts: Utilizing Command Prompt to Identify and Resolve Windows Issues</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-your-interview-role-a-comprehensive-guide/"><u>Perfecting Your Interview Role  A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x80780119-on-system-image/"><u>Addressing Windows Error 0X80780119 on System Image</u></a></li>
<li><a href="https://win11.techidaily.com/which-window-suits-you-best-home-versus-pro-in-windows-11/"><u>Which Window Suits You Best? Home Versus Pro in Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/safety-vs-entertainment-balancing-risks-with-quizzes/"><u>Safety Vs. Entertainment: Balancing Risks with Quizzes</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-audio-fade-ins-and-outs-made-easy-2-final-cut-pro-techniques-for-2024/"><u>Updated Audio Fade Ins and Outs Made Easy 2 Final Cut Pro Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ms-store-downloads-techniques-and-tips/"><u>Boosting MS Store Downloads: Techniques and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/instagrammable-pcs-how-to-add-your-chosen-weather-image-in-windows-11-status-bar/"><u>Instagrammable PCs: How to Add Your Chosen Weather Image in Windows 11 Status Bar</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-mini-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 mini to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://win11.techidaily.com/from-problem-to-perfection-tactics-to-install-missing-features-in-windows-11-and-11-pro/"><u>From Problem to Perfection: Tactics to Install Missing Features in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-manage-files-and-tabs-windows-11/"><u>Expert Strategies to Manage Files and Tabs (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-private-character-editor-in-windows/"><u>How to Open the Private Character Editor in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fog-no-more-secrets-for-crisp-clean-filming-for-2024/"><u>Fog No More  Secrets for Crisp, Clean Filming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unrequested-file-explorer-startups/"><u>Addressing Unrequested File Explorer Startups</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-iphone-13-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-artisans-of-cinematic-magic-unveiling-every-roles-importance-in-movie-creation/"><u>New The Artisans of Cinematic Magic Unveiling Every Roles Importance in Movie Creation</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-chromiums-network-access-via-windows-settings-blockers/"><u>Unshackle Chromium's Network Access via Windows Settings Blockers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximizing-your-story-potential-with-instagram-highlights-for-2024/"><u>Maximizing Your Story Potential with Instagram Highlights for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-imessage-for-windows-expert-techniques-revealed/"><u>Leveraging iMessage for Windows: Expert Techniques Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-on-computing-power-spent-by-malware-scanners/"><u>Cut Down on Computing Power Spent by Malware Scanners</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-by-step-blueprint-for-successful-reddit-contributions/"><u>Step-by-Step Blueprint for Successful Reddit Contributions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-avoid-last-minute-fb-stress-with-these-free-tools/"><u>In 2024, Avoid Last-Minute FB Stress with These Free Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-discover-the-hottest-tiktok-products-at-amazon/"><u>In 2024, Discover the Hottest TikTok Products at Amazon</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-windows-programming-file-layout-pe/"><u>Deciphering the Windows Programming File Layout (PE)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-uncharted-territories-discovering-hidden-vlc-capabilities/"><u>[New] Uncharted Territories  Discovering Hidden VLC Capabilities</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-what-make-aesthetic-cartoon-drawing-more-understandable/"><u>New 2024 Approved What Make Aesthetic Cartoon Drawing More Understandable</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-internet-connections-a-guide-for-steam-on-windows/"><u>Fixing Internet Connections: A Guide for Steam on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
</ul></div>
