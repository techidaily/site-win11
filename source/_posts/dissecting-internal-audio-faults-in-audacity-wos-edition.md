---
title: Dissecting Internal Audio Faults in Audacity, WOS Edition
date: 2024-07-13T10:43:25.710Z
updated: 2024-07-14T10:43:25.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dissecting Internal Audio Faults in Audacity, WOS Edition
excerpt: This Article Describes Dissecting Internal Audio Faults in Audacity, WOS Edition
keywords: Audacity Analysis,Sound Error Diagnosis,Audacity Fault Fixing,Audacity WOS,Audio Debugging Tools,Internal Audio Issues,Recording Software Troubleshooting
thumbnail: https://thmb.techidaily.com/da3401fb2ac78eb6ea2665b0f0063719a28f111af87b9a39c4fbeb83cdcf06b8.jpg
---

## Dissecting Internal Audio Faults in Audacity, WOS Edition

 Audacity is great music editing and recording software when it works. However, some users can’t utilize Audacity because of an Internal PortAudio error that occurs when they launch the software. Instead of launching, Audacity throws up this message: “Could not find any audio devices… Internal PortAudio error.”

 Although the Audacity window opens, users can’t play or record anything with that software when the Internal PortAudio error occurs. Does the same thing happen when you run Audacity? If it does, this is how you can fix the Internal PortAudio error in Windows 11 and 10.

## 1\. Run the Playing Audio Troubleshooter

 Windows has a "Playing Audio" troubleshooter to help users resolve audio playback issues. As the Internal PortAudio error breaks sound playback in Audacity, that troubleshooter could be useful for fixing this issue. You can access the Playing Audio troubleshooter in Windows 10 and 11 via the Control Panel like this:

1. Click a search box or magnifying glass icon on the Windows 11/10 taskbar.
2. Then type in**Control Panel** within the search utility.
3. Select**Control Panel** to open that app’s window.
4. If Control Panel opens in its category view, click**Large icons** on the**View by** menu.
5. Select**Troubleshooting** to access that applet.  
![The Control Panel applets window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-control-panel-items.jpg)

1. Next, select the**View all** navigation link on the left of the Control Panel window.  
![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-applet.jpg)
2. Click Playing Audio to launch that troubleshooter.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-list.jpg)
3. Select the troubleshooter’s**Next** option to continue.
4. Then select one of the sound output device options to troubleshoot and click**Next** .
5. Apply the resolutions suggested within the Playing Audio troubleshooter.

## 2\. Enable the Windows Audio and Endpoint Builder Services

 Many Audacity users have confirmed enabling and running disabled Windows Audio and Endpoint Builder services can fix the Internal PortAudio error. So, this troubleshooting method will likely work if one of those services is disabled on your PC. This is how you can check and enable those services in Windows 11/10:

1. First, bring up the Windows search box and search for Services. You can also use one of the other [ways to open Services on Windows](https://www.makeuseof.com/windows-11-open-services-app/) .
2. Next, double-click**Windows Audio** to bring up further options for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service.jpg)
3. If the service is disabled, select an**Automatic** startup option on the drop-down menu.  
![The Automatic service option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/automatic-service.jpg)
4. Then select the properties window’s**Start** option to run the service.
5. Click**Apply** and**OK** to save the options and exit the Audio Properties window.
6. Repeat steps four to eight for the Windows Audio Endpoint Builder service.

 If you find the above services to be enabled and running, restarting them could also feasibly fix the issue. To do that, click Stop in their properties windows and select**Yes** to confirm. Then click their**Start** options to restart them.

## 3\. Manually Enable all Playback and Recording Devices

 It could be the case that a disabled audio playback or recording device is causing the PortAudio error to arise. For that reason, it’s recommended to enable all disabled playback and recording devices you can find in the Sound window. You can do that with the following steps:

1. To access the Run dialog, press**Win + R** .
2. Type**mmsys.cpl** in Run’s command box.
3. Click**OK** to bring up the Sound window.
4. Then click the**Playback** tab if necessary.
5. Right-click any disabled playback device and select**Enable** . Repeat this step for all disabled devices listed.  
![The Enable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-option.jpg)
6. Then select the**Recording** tab to view more devices.  
![The Recording tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/recording-tab.jpg)
7. Click disabled recording devices with the mouse’s right button to select their**Enable** options. Enable all disabled devices listed there.
8. Select the Sound window’s**Apply** option to save settings.
9. Click**OK** on the Sound window to exit, and then restart your Windows 11/10 desktop or laptop.

## 4\. Select the Rescan Audio Devices

 If you’ve made some recent audio device changes on your PC, Audacity might not have detected them. Selecting Audacity’s**Rescan Audio Device** option can feasibly resolve the PortAudio error in such a scenario. This is how you can select that option:

1. Open the Audacity window.
2. Click**Transport** on Audacity’s menu bar.
3. Select the**Rescan Audio Devices** option.  
![The Rescan Audio Devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/rescan-audio-devices-option.jpg)
4. Wait for the rescan to finish, and then restart**Audacity** .

## 5\. Reinstall Audio Device Drivers

 The Internal PortAudio can also occur because of a sound device driver issue. In this case, reinstalling the drivers for all audio devices can fix this issue for some users. Trying reinstalling your PC’s audio device drivers as follows:

1. To open the Power User menu, right-click the Windows 11/10**Start** button.
2. Select**Device Manager** to bring up the window for that tool.
3. Click the arrow beside the**Audio inputs and outputs** category.  
![The Audio inputs and outputs category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/audio-inputs-and-outputs.jpg)
4. Right-click your speaker’s audio device and select**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device.jpg)
5. Select**Uninstall** on the small window that opens.  
![The Uninstall button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-button.jpg)
6. Repeat the last two steps for all sound devices in the**Audio inputs and outputs** category.
7. If you utilize any sound devices with USB ports, double-click the**Universal Serial Bus** category and select to uninstall all host controllers listed there. Users who don’t have sound devices connected via USB can skip this step.
8. Restart your PC for automatic driver reinstallation. If some drivers aren’t reinstalled after the restart, select the**Action** \>**Scan for hardware** changes options in Device Manager.

## 6\. Update the Realtek Audio Codec Driver

 Does your PC have a Realtek audio codec driver? If so, it’s recommended to update that driver for the sake of fixing the Internal PortAudio error. Update that Realtek driver as follows:

1. [Open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/) to access that uninstaller tool.
2. Select Realtek High Definition Audio Driver or Realtek HD Manager.
3. Click**Uninstall** to remove the driver.  
![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/programs-and-features.jpg)
4. Then bring up the [Realtek audio driver](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software) page.
5. Click the**Download** button for the latest compatible Realtek driver for your PC.
6. Open the folder containing the downloaded Realtek driver package.
7. Double-click the Realtek package to install the latest driver.

## 7\. Reinstall Audacity

 A corrupted Audacity installation is another potential reason for the Internal PortAudio error occurring. Reinstalling the sound editor will likely resolve Audacity installation issues. You can remove Audacity with one of the methods included in our [ways to uninstall Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) post.

 To reinstall the software, open the [Audacity](https://www.audacityteam.org/download/) download page. Click the**Download for Windows** link there to save the setup wizard. Then navigate to the directory your browser downloads to and double-click the**audacity-win-.3.2.5 x64.exe** file to reinstall Audacity.

![The download Audacity option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/download-audacity-options.jpg)

 Some users have said that reinstalling older, not newer, versions of Audacity resolved the Internal PortAudio error on their PCs. Although it’s recommended to install the latest version first, reinstalling an older version is another troubleshooting option worth considering. This [uptodown archives page](https://audacity.en.uptodown.com/windows/versions) includes a good library of older Audacity versions for download.

## Get the Internal PortAudio Error Sorted on Audacity for Windows

 Although there are plenty of audio editor alternatives to Audacity, few others match its sound recording and editing features. However, you probably won’t need to switch to an alternative music editor because of the Internal PortAudio error after applying the potential fixes above. They’re widely cited solutions that have resolved the PortAudio error for many Audacity users.

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
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 6s Plus?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/step-wise-process-of-integrating-voice-over-into-videos/"><u>Step-Wise Process of Integrating Voice Over Into Videos</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-xcover-6-pro-tactical-editionwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy XCover 6 Pro Tactical Editionwith/without a PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-excessive-tiktok-drafts-simplify-with-smart-editing-techniques/"><u>In 2024, Excessive TikTok Drafts? Simplify with Smart Editing Techniques</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-15-apps-to-hack-wifi-password-on-vivo-s17t-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Vivo S17t</u></a></li>
<li><a href="https://win11.techidaily.com/scrutinizing-password-ingress-windows-pass-and-no-pass-outcomes/"><u>Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-seamless-video-watch-removing-youtube-barriers/"><u>2024 Approved  Seamless Video Watch  Removing YouTube Barriers</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-voice-transformation-powerhouses-a-deep-dive-into-25-leading-apps-and-their-capabilities/"><u>2024 Approved Voice Transformation Powerhouses A Deep Dive Into 25 Leading Apps and Their Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-paste-issues-across-popular-browsers/"><u>How to Rectify Paste Issues Across Popular Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-group-policy-intricacies-through-gpresult/"><u>Deciphering Group Policy Intricacies Through GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mend-media-player-server-faults/"><u>Steps to Mend Media Player Server Faults</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-sony-vegas-for-the-aspiring-youtube-editor-a-comprehensive-overview/"><u>[New] Sony Vegas for the Aspiring YouTube Editor  A Comprehensive Overview</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-bluetooth-headphones-playing-sound-without-volume-control/"><u>Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-a-step-by-step-manual-on-repetitive-watch-experiences-in-yt/"><u>[New] 2024 Approved  A Step-by-Step Manual on Repetitive Watch Experiences in YT</u></a></li>
<li><a href="https://win11.techidaily.com/file-compression-excellence-utilizing-cli-commands-in-windows/"><u>File Compression Excellence: Utilizing CLI Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-vanishing-steam-game-images/"><u>How to Revive Vanishing Steam Game Images</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-top-strategies-for-dominating-the-tiktok-marketing-arena/"><u>[Updated] Top Strategies for Dominating the TikTok Marketing Arena</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-xiaomi-redmi-a2plus-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Xiaomi Redmi A2+</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pcs-powertoys-10-essential-tips/"><u>Mastering Windows PCs: PowerToys' 10 Essential Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-admins-rights-issue-in-win-os/"><u>Bypassing Admins Rights Issue in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-unresponsive-voice-commands/"><u>Troubleshooting Windows 11: Unresponsive Voice Commands</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-non-ad-focused-start-menu-win-11/"><u>Exclusive, Non-Ad Focused Start Menu Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-bluetooth-attempt-error-in-windows/"><u>Mastering the Fix: Bluetooth Attempt Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-new-windows-11-taskbar-features/"><u>Mastering the New Windows 11 Taskbar Features</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-10-and-11s-0x0000011b-faults/"><u>Addressing Windows 10 & 11'S 0X0000011B Faults</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-windows-steam-speed-eliminating-zero-downloads/"><u>Elevate Windows Steam Speed: Eliminating Zero-Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-unveiled-a-deep-dive-into-w11s-core/"><u>DevHome Unveiled: A Deep Dive Into W11's Core</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-6-plus-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 6 Plus to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-the-veiled-query-power-in-windows-11/"><u>Awakening the Veiled Query Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-walkthrough-for-transferring-old-games-to-windows-gallery/"><u>A Walkthrough for Transferring Old Games to Windows Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-importance-in-preserving-win-11-notifications/"><u>Unveiling the Importance in Preserving Win 11 Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-bt-folder-functionality/"><u>Understanding Windows ~BT Folder Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-admin-control-in-windows-os-security/"><u>Redefining Admin Control in Windows OS Security</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-level-mic-tips-for-youtube-voice-talents-for-2024/"><u>Entry-Level Mic Tips for YouTube Voice Talents for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-techniques-for-effortless-facebook-video-posting-pcandroid/"><u>In 2024, Techniques for Effortless Facebook Video Posting, PC/Android</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-issue-code-0x80071a90/"><u>Decoding Windows Issue: Code 0X80071a90</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-energy-visibility-personalized-notifications-for-fully-charged-batteries-on-win11/"><u>Enhanced Energy Visibility: Personalized Notifications for Fully Charged Batteries on Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-honor-x50i-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Honor X50i to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-windows-pin-entry/"><u>Troubleshooting Non-Responsive Windows PIN Entry</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-stepwise-guide-to-optimizing-youtube-tagging-techniques/"><u>In 2024, Stepwise Guide to Optimizing YouTube Tagging Techniques</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selecting-the-top-infinite-storage-providers-for-2024/"><u>Selecting the Top Infinite Storage Providers for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-vivo-y77t-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Vivo Y77t</u></a></li>
<li><a href="https://win11.techidaily.com/nullify-non-compliance-notifications-in-win11/"><u>Nullify Non-Compliance Notifications in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/yourdevice-link-assessing-risks-and-benefits-in-w10-systems/"><u>YourDevice Link - Assessing Risks and Benefits in W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-the-win-network-access-issue/"><u>How to Mend the WIN Network Access Issue</u></a></li>
<li><a href="https://win11.techidaily.com/top-desk-features-add-your-favorite-apps-to-the-taskbar/"><u>Top Desk Features: Add Your Favorite Apps to the Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-mail-service-halt-fixing-0x800713f-in-win11/"><u>Overcoming Mail Service Halt: Fixing 0X800713F in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-tackling-windows-security-anomalies/"><u>Strategies for Tackling Windows Security Anomalies</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-heic-pictures-to-jpeg-in-w10w11/"><u>Transitioning HEIC Pictures to JPEG in W10/W11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-aspect-ratio-options-on-prime-video/"><u>New Aspect Ratio Options on Prime Video</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/offline-process-for-extra-users-in-windows-11/"><u>Offline Process for Extra Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-gpos-ensuring-compliance-on-modern-windows/"><u>Revitalizing GPOs: Ensuring Compliance on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-microsoft-ai-hub-features/"><u>Exploring Microsoft AI Hub Features</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-set-default-touch-input-placement/"><u>Win 11: Set Default Touch Input Placement</u></a></li>
</ul></div>
