---
title: Dissecting Internal Audio Faults in Audacity, WOS Edition
date: 2024-06-25T11:38:53.492Z
updated: 2024-06-26T11:38:53.492Z
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

1. First, bring up the Windows search box and search for Services. You can also use one of the other[ways to open Services on Windows](https://www.makeuseof.com/windows-11-open-services-app/) .
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
4. Then bring up the[Realtek audio driver](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software) page.
5. Click the**Download** button for the latest compatible Realtek driver for your PC.
6. Open the folder containing the downloaded Realtek driver package.
7. Double-click the Realtek package to install the latest driver.

## 7\. Reinstall Audacity

 A corrupted Audacity installation is another potential reason for the Internal PortAudio error occurring. Reinstalling the sound editor will likely resolve Audacity installation issues. You can remove Audacity with one of the methods included in our[ways to uninstall Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) post.

 To reinstall the software, open the[Audacity](https://www.audacityteam.org/download/) download page. Click the**Download for Windows** link there to save the setup wizard. Then navigate to the directory your browser downloads to and double-click the**audacity-win-.3.2.5 x64.exe** file to reinstall Audacity.

![The download Audacity option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/download-audacity-options.jpg)

 Some users have said that reinstalling older, not newer, versions of Audacity resolved the Internal PortAudio error on their PCs. Although it’s recommended to install the latest version first, reinstalling an older version is another troubleshooting option worth considering. This[uptodown archives page](https://audacity.en.uptodown.com/windows/versions) includes a good library of older Audacity versions for download.

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
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/7-solutions-for-resolving-windows-11-naming-issues-in-directories/"><u>7 Solutions for Resolving Windows 11 Naming Issues in Directories</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-bluetooth-pairing-fail-in-windows-devices/"><u>Steps to Tackle Bluetooth Pairing Fail in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-1011-installing-a-unique-lock-pattern/"><u>Guide to Windows 10/11: Installing a Unique Lock Pattern</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-add-on-of-portable-software-to-windows-oses/"><u>Seamless Add-On of Portable Software to Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bridge-the-disconnect-gap-windows-11-and-printers/"><u>How to Bridge the Disconnect Gap: Windows 11 & Printers</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-a2-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo A2 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/cutting-edge-tips-for-game-capture-in-obs/"><u>Cutting-Edge Tips for Game Capture in OBS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-ultimate-guide-top-10-high-quality-no-cost-recording-tools/"><u>[New] In 2024, Ultimate Guide  Top 10 High-Quality, No-Cost Recording Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-how-to-find-facebook-recently-watched-videos-in-2024/"><u>[New] How to Find Facebook Recently Watched Videos, In 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-be-a-good-podcast-host-2024-updated/"><u>New How to Be a Good Podcast Host (2024 Updated)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-t-mobile-iphone-12-pro-online-without-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock T-Mobile iPhone 12 Pro online without SIM Card?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-digital-identity-building-crafting-perfect-channel-images/"><u>2024 Approved  Digital Identity Building  Crafting Perfect Channel Images</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-free-video-steadycam-software-for-windows-and-mac-compare-and-choose/"><u>New In 2024, Free Video Steadycam Software for Windows and Mac Compare and Choose</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-maximize-your-snapchat-impact-with-mac-footage-for-2024/"><u>[Updated] Maximize Your Snapchat Impact with Mac Footage for 2024</u></a></li>
</ul></div>
