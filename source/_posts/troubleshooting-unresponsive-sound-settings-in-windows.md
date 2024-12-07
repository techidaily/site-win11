---
title: Troubleshooting Unresponsive Sound Settings in Windows
date: 2024-12-06T08:29:43.317Z
updated: 2024-12-07T04:12:34.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Unresponsive Sound Settings in Windows
excerpt: This Article Describes Troubleshooting Unresponsive Sound Settings in Windows
keywords: Fix Windows Audio Issues,Responsive Windows Speakers,Windows Sound Errors,Restore Default Sounds,Correct Unheard Windows Volume,Recover Noisy PC Settings,Enable System Audio Playback
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## Troubleshooting Unresponsive Sound Settings in Windows

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Restart your PC after this and check if the issue is still there.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on[how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the[best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on[how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-download-premium-video-covers-free-fast-and-easy/"><u>[New] In 2024, Download Premium Video Covers - Free, Fast & Easy</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-journey-through-lut-based-color-enhancement-methods/"><u>[Updated] 2024 Approved Journey Through LUT-Based Color Enhancement Methods</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-elite-laughter-photo-composer-tool/"><u>[Updated] Elite Laughter Photo Composer Tool</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-social-snapshot-post-photosvideos-without-a-twit-for-2024/"><u>[Updated] Social Snapshot Post Photos/Videos without a Twit for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-future-without-vlc-media-player-insights/"><u>[Updated] The Future Without VLC - Media Player Insights</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-concealed-chronicles-your-ultimate-guide-to-secret-stories/"><u>2024 Approved Concealed Chronicles Your Ultimate Guide to Secret Stories</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-logitech-mx-g920-drivers-compatible-with-windows-11-10-8-and-7/"><u>Download Logitech MX G920 Drivers – Compatible with Windows 11, 10, 8 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/efficiency-at-its-peak-streamlined-grouped-software-installs-with-winstall-on-windows-11/"><u>Efficiency at Its Peak: Streamlined Grouped Software Installs with Winstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/examining-energy-demand-in-your-windows-based-computer/"><u>Examining Energy Demand in Your Windows-Based Computer</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-educational-flair-into-your-win-11-display/"><u>Infuse Educational Flair Into Your Win 11 Display</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-gadgets-insightful-tips-from-the-experts-at-toms-hardware/"><u>Mastering Gadgets: Insightful Tips From the Experts at Tom's Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-file-safety-wins-delete-settings-guide/"><u>Optimize File Safety: Win's Delete Settings Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-feed-rates-on-task-monitor-win-11/"><u>Optimize Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/pixelpunmatic-device/"><u>PixelPunmatic Device</u></a></li>
<li><a href="https://win11.techidaily.com/rehabilitate-your-windows-service-management-tool-with-these-7-tactics/"><u>Rehabilitate Your Windows Service Management Tool With These 7 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-teammers-screens-not-showing/"><u>Tackle Teammers' Screens Not Showing</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-worst-js-error-on-discord-specifically-for-windows-users/"><u>Tackling the Worst JS Error on Discord, Specifically for Windows Users</u></a></li>
</ul></div>

