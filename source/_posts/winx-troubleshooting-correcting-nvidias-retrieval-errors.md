---
title: "WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors"
date: 2024-07-13T10:52:02.195Z
updated: 2024-07-14T10:52:02.195Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors"
excerpt: "This Article Describes WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors"
keywords: Fix Nvidia WinX Errors,Resolve WinX Graphics Issues,Overcome WinX GPU Problems,Troubleshoot WinX Display Errors,Correct Nvidia Driver Failures,Solve WinX System Crashes,Address WinX Freezing Glitches
thumbnail: https://thmb.techidaily.com/98061f90f0702266772c41039bf7505ea26afb88709675b4845f86d9c07123c1.jpg
---

## WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.
4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-gif-size-barrier-on-discord-for-win11-users/"><u>Breaking Down the GIF Size Barrier on Discord for Win11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/explore-the-best-podcast-platforms-for-your-mac/"><u>Explore the Best Podcast Platforms for Your Mac</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win11s-notepad-with-virtuoso-helper/"><u>Accelerate Win11's Notepad with Virtuoso Helper</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-free-fb-video-creators-20-top-tools-for-engaging-ads/"><u>[Updated] Free FB Video Creators  20 Top Tools for Engaging Ads</u></a></li>
<li><a href="https://win11.techidaily.com/windows-auto-update-shutdown-guide/"><u>Windows Auto-Update Shutdown Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-calendar-a-step-by-step-guide/"><u>Mastering Windows 11 Calendar: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-connection-issue-on-windows-os/"><u>Fixing No Connection Issue on Windows OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-capturing-victories-effective-strategies-with-w11-for-2024/"><u>[Updated] Capturing Victories  Effective Strategies with W11 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-a-comparative-journey-through-the-top-10-tv-streamers/"><u>2024 Approved  A Comparative Journey Through the Top 10 TV Streamers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fall-guys-network-woes-on-windows-systems/"><u>Mastering Fall Guys Network Woes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-hdr-visualization-with-windows-11/"><u>Dive Deep Into HDR Visualization with Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-tips-zooming-in-on-videoleap-videos-for-2024/"><u>Expert Tips  Zooming In on Videoleap Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-s18-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-unlocked-effective-tpm-deactivation/"><u>Windows 11 Unlocked: Effective TPM Deactivation</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-fatal-glitches-fixing-xbox-game-pass-error-0x00000001-in-windows-11/"><u>How to Eliminate Fatal Glitches: Fixing Xbox Game Pass Error 0X00000001 in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-elevating-discord-dynamics-a-curated-list-of-bots/"><u>2024 Approved  Elevating Discord Dynamics  A Curated List of Bots</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-5-innovative-vr-drones-collaborations/"><u>[New] Top 5 Innovative VR Drones Collaborations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-personalize-wins-standard-cli-application/"><u>How To Personalize Win’s Standard CLI Application</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-animate-like-a-pro-the-best-free-and-paid-3d-software-for-beginners-and-experts/"><u>Updated In 2024, Animate Like a Pro The Best Free and Paid 3D Software for Beginners and Experts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-usage-of-computational-resources-by-unrealcefsubprocess/"><u>Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-networking-with-python-servers-on-windows-os/"><u>Advanced Networking with Python Servers on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-unleashing-potential-strategic-hashtags-for-video-success/"><u>[Updated] 2024 Approved  Unleashing Potential  Strategic Hashtags for Video Success</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-frozen-windows-volume-backup-service/"><u>Fixes for Frozen Windows Volume Backup Service</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-breaking-free-from-the-old-a-complete-step-by-step-guide-to-updating-your-tiktok-avatar-for-2024/"><u>[New] Breaking Free From the Old  A Complete, Step-By-Step Guide to Updating Your TikTok Avatar for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-how-to-change-your-status-on-discord-in-2024/"><u>[Updated] How to Change Your Status on Discord, In 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-directly-engage-with-facebooks-video-offerings-via-your-apple-device/"><u>In 2024, Directly Engage with Facebook's Video Offerings via Your Apple Device</u></a></li>
<li><a href="https://win11.techidaily.com/is-obs-studio-unable-to-record-audio-on-windows-11-try-these-fixes/"><u>Is OBS Studio Unable to Record Audio on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-mac-users-manual-recording-high-quality-audio-with-audacity/"><u>[Updated] Mac Users' Manual  Recording High-Quality Audio with Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-t2x-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo T2x 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-infinix-note-30-5g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Infinix Note 30 5G Phone?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/essential-note-taking-software-the-winning-seven/"><u>Essential Note-Taking Software: The Winning Seven</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-uniting-your-feeds-posting-videos-from-twitter-on-snapchat/"><u>[New] 2024 Approved  Uniting Your Feeds  Posting Videos From Twitter on Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-motorola-moto-g23-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Motorola Moto G23 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/installation-triumph-fixed-mspm-in-windows-10/"><u>Installation Triumph: Fixed MSPM in Windows 10</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-quintessential-10-fight-royale-games/"><u>[New] 2024 Approved  Quintessential 10 Fight Royale Games</u></a></li>
<li><a href="https://win11.techidaily.com/burying-your-data-secretive-drive-practices/"><u>Burying Your Data: Secretive Drive Practices</u></a></li>
</ul></div>
