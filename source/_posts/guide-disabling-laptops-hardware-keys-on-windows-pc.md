---
title: "Guide: Disabling Laptop's Hardware Keys on Windows PC"
date: 2024-07-13T10:39:24.168Z
updated: 2024-07-14T10:39:24.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Disabling Laptop's Hardware Keys on Windows PC"
excerpt: "This Article Describes Guide: Disabling Laptop's Hardware Keys on Windows PC"
keywords: Hardware Key Disable,Wi-Fi Key Off,BIOS Security Lock,Laptop Secure PC,Windows Input Halt,Hardware Keypad Turnoff,Device Safety Setup,PC Security Guide,Hardware Lock Windows,Laptop Controls Halt,Keyboard Disable Procedures
thumbnail: https://thmb.techidaily.com/017337439b4f792b0246468061b8e1aa8f8f36d01cdf2619fb3c06685fc0972f.jpg
---

## Guide: Disabling Laptop's Hardware Keys on Windows PC

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/recovering-hidden-notifications-on-desktops/"><u>Recovering Hidden Notifications on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-speedy-utorrent-in-windows/"><u>Winning Strategies: Speedy uTorrent in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/expert-windows-11-weather-app-reviews/"><u>Expert Windows 11 Weather App Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-device-integration-using-googles-nearby/"><u>Seamless Device Integration Using Google's Nearby</u></a></li>
<li><a href="https://win11.techidaily.com/greatest-non-microsoft-options-easy-screen-captures-without-windows/"><u>Greatest Non-Microsoft Options: Easy Screen Captures Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-eliminate-auto-change-backgrounds/"><u>Windows 11: Eliminate Auto-Change Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-undetermined-status-messages-on-windows/"><u>Remedying 'Undetermined' Status Messages on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-internal-sound-malfunctions-in-winaudacity-interface/"><u>Pinpointing Internal Sound Malfunctions in WinAudacity Interface</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-unlinking-saved-wi-fi/"><u>Win 11: Unlinking Saved Wi-Fi</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-spirit-of-victory-a-steam-achievements-reset/"><u>Reviving the Spirit of Victory: A Steam Achievements Reset</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mastering-mac-cam-high-quality-captures-in-minutes/"><u>[Updated] Mastering Mac Cam  High-Quality Captures in Minutes</u></a></li>
<li><a href="https://win11.techidaily.com/fix-static-speakers-after-disabling-default-sounds/"><u>Fix Static Speakers After Disabling Default Sounds</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-video-channels-face-off-the-monetization-tale-of-two-titles/"><u>2024 Approved  Video Channels Face-Off  The Monetization Tale of Two Titles</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-poco-x6-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Poco X6 Pro</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-streamlining-post-production-with-luts-in-ae/"><u>2024 Approved  Streamlining Post-Production with LUTs in AE</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-full-featured-sierra-drives-files-and-more/"><u>2024 Approved  Full-Featured Sierra  Drives, Files, and More</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-step-by-step-guide-to-professional-instagram-live-conversations/"><u>In 2024, Step-by-Step Guide to Professional Instagram Live Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-tips-for-discovering-computer-gpu-make/"><u>Fast-Track Tips for Discovering Computer GPU Make</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-boost-creativity-with-free-audio-effects-online/"><u>[Updated] In 2024, Boost Creativity with Free Audio Effects Online</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-9-indisputable-reasons-to-choose-a-pc-over-a-mac/"><u>Unveiling 9 Indisputable Reasons to Choose a PC Over a Mac</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-dive-into-360-videos-iphone-edition-for-facebook-posts/"><u>[New] 2024 Approved  Dive Into 360 Videos  IPhone Edition for Facebook Posts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-best-practices-for-documenting-youtube-live-videos/"><u>[New] 2024 Approved  Best Practices for Documenting Youtube LIVE Videos</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-immediate-failure-how-to-successfully-add-a-folder-in-onedrive-on-pc/"><u>Tackling Immediate Failure: How to Successfully Add a Folder in OneDrive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-of-windows-11-is-ai-whether-you-like-it-or-not/"><u>The Future of Windows 11 Is AI, Whether You Like It or Not</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-mastering-gesture-control-a-comprehensive-overview/"><u>[New] Mastering Gesture Control  A Comprehensive Overview</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-interactions-between-devices-and-windows-snooze/"><u>Fine-Tuning Interactions Between Devices and Windows Snooze</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-supercharge-video-memory-on-windows-devices/"><u>Tips to Supercharge Video Memory on Windows Devices</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Realme 10T 5G? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-honor-magic-6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/explore-5-innovative-windows-folder-strategies/"><u>Explore 5 Innovative Windows Folder Strategies</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-v27e-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/pioneering-popularity-with-powerful-instagram-videos/"><u>Pioneering Popularity with Powerful Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/unite-with-your-absent-astra-pilot-on-windows-11/"><u>Unite With Your Absent Astra Pilot On Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713964617797-new-read-and-learn-how-to-convert-a-slow-motion-video-to-normal-in-this-guide-besides-find-the-best-desktop-solution-to-adjust-video-speed-quickly-and-easil/"><u>New Read and Learn How to Convert a Slow-Motion Video to Normal in This Guide. Besides, Find the Best Desktop Solution to Adjust Video Speed Quickly and Easily for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-make-a-slow-motion-video-in-wondershare-filmora/"><u>Updated In 2024, How to Make a Slow Motion Video in Wondershare Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-windows-11-cortana-commands/"><u>Overcoming Unresponsive Windows 11 Cortana Commands</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-11-best-streaming-audio-recorders-for-2024/"><u>Top 11 Best Streaming Audio Recorders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-revitalize-retro-computers/"><u>AtlasOS Resurgence: Revitalize Retro Computers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revealed-the-best-10-in-4k-no-hassle/"><u>2024 Approved  Revealed  The Best 10 in 4K, No Hassle</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-direct-transfer-techniques-camera-roll-images-to-snapchat/"><u>[Updated] 2024 Approved  Direct Transfer Techniques  Camera Roll Images to Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-status-check-top-three-techniques/"><u>Windows 11 Status Check: Top Three Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/setting-specific-windows-lockdown-period/"><u>Setting Specific Windows Lockdown Period</u></a></li>
<li><a href="https://win11.techidaily.com/curing-a-non-operational-windows-control-panel/"><u>Curing a Non-Operational Windows Control Panel</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-weekly-must-see-elite-igtv-talents/"><u>[Updated] 2024 Approved  Weekly Must-See  Elite IGTV Talents</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE To Other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-a-journey-with-the-taskbar-through-time/"><u>Windows UI: A Journey with the Taskbar Through Time</u></a></li>
<li><a href="https://win11.techidaily.com/silent-storage-strategies-for-stealthy-windows-users/"><u>Silent Storage Strategies for Stealthy Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-troubleshooting-xbox-audio-failures-in-pcs/"><u>Steps for Troubleshooting Xbox Audio Failures in PCs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-tiktok-gaming-top-10-gaming-tiktokers/"><u>[New] Tiktok Gaming | Top 10 Gaming Tiktokers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-can-i-share-youtube-videos-on-facebook-in-2024/"><u>How Can I Share YouTube Videos on Facebook, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/separate-onedrive-and-microsoft-accounts-on-desktop-windows/"><u>Separate OneDrive & Microsoft Accounts on Desktop Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-unveiling-the-nuances-of-anime-dubbing-methodology-examples-and-best-practices/"><u>2024 Approved Unveiling the Nuances of Anime Dubbing Methodology, Examples, & Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-analysis-underutilized-windows-system-health-metrics/"><u>A Dual Analysis: Underutilized Windows System Health Metrics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-realme-12-proplus-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Realme 12 Pro+ 5G for Streaming | Dr.fone</u></a></li>
</ul></div>
