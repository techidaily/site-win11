---
title: Fix Static Speakers After Disabling Default Sounds
date: 2024-07-13T10:33:57.368Z
updated: 2024-07-14T10:33:57.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Static Speakers After Disabling Default Sounds
excerpt: This Article Describes Fix Static Speakers After Disabling Default Sounds
keywords: Fixing Static Sound Issues,Remove Speaker Noise Post-Disable,Cleaning Audio Outputs,Deactivate Sound Effects Remedy,Silence Disabled Sounds Solution,Eradicate Static Speaker Sound,Address Speaker Disturbance After Disabling
thumbnail: https://thmb.techidaily.com/f99b0547d8a95f637159e251c131a6578ae71b255445af767dc74d5fd38281e0.jpg
---

## Fix Static Speakers After Disabling Default Sounds

 So you've tested your sound drivers and found that the test tone isn't playing on Windows. This problem occurs with an error message such as "Failed to play test tone" or something similar.

 Dealing with audio problems on Windows is sometimes frustrating, but there are simple solutions available. This guide shows you how to troubleshoot the issue and get your speakers working again.

## 1\. Restart Your Computer

 If the test tone isn't playing, restart your computer first. This often refreshes the system and solves small glitches that may have developed. It's a simple workaround but sometimes effective.

![A Windows PC Getting Started](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restarting-a-windows-pc.jpg)

 To restart your computer, close any running applications. After that, press **Alt + F4**, or right-click the **Start** menu and select **Shut down or sign out** \> **Shut down**.

## 2\. Run the Audio Troubleshooter

 Windows comes with a built-in troubleshooter for minor audio problems. It diagnoses and fixes issues related to audio hardware, settings, and driver configuration. Here's how to use this tool.

1. Press **Win + I** on your keyboard to open the Settings app.
2. In the Settings menu, navigate to **System** \> **Troubleshoot**.
3. Click **Other troubleshooters** on the next page.
4. Next to the **Playing Audio** troubleshooter, click the **Run** button.  
![Run the Audio Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-audio-troubleshooter.jpg)

 Wait for a while until Windows scans and fixes the issue. After this, see if the test tone is working.

## 3\. Restart the Windows Audio Service

 The Windows Audio service is responsible for controlling the sound on your computer. It's possible that this service stopped running and caused the test tone to fail. In this case, you must restart the Windows Audio service to get your sound back. Here's how.

1. Click on Start, type **services.msc**, and press **Enter**.
2. In the Services window, scroll down to find the **Windows Audio** service.  
![Open Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-windows-audio-service.jpg)
3. Once found, double-click it to open its Properties window.
4. In the General tab, click on the **Start type** drop down menu and select **Automatic**.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-windows-audio-service.jpg)
5. Now go to the **Service status** section and click on **Stop**.
6. Wait for a few moments, then press **Start** to restart the service.
7. Click **Apply** \> **OK** to save the changes.

 After doing this, close the Services window and open any audio application to check if the test tone is playing.

## 4\. Turn Off Audio Enhancements

 The audio enhancement feature on Windows enhances audio quality and adds additional effects to audio playback. However, it sometimes leads to audio problems and glitches. Disabling this feature may fix any sound issues you have.

 To disable audio enhancement, do the following:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type "Control Panel" in the search field and hit Enter.
3. Click **Hardware and Sound** in the Control Panel.
4. On the right side of the window, click **Sound**.
5. In the Sound window, select the **Playback** tab.
6. Right-click any device with a green check mark and select **Properties**.
7. On the **Advanced** tab, uncheck the box for **Enable audio enhancements**.  
![Disable Audo Enhancements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-audo-enhancements.jpg)
8. Now click **Apply > OK** to save the changes.

 Audio enhancements should now be disabled, and you may find your sound issues resolved. If you have multiple audio devices, repeat the process for each device. Once you have completed these steps, restart your computer and check if your audio issues have been resolved.

## 5\. Update the Audio Driver

 Outdated or corrupted audio drivers may lead to the test tone not working. You will need to update them to get your sound back on Windows.

 To update the audio driver:

1. Press **Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **devmgmt.msc** in the dialog box and press Enter.
3. In the Device Manager window, expand the **Audio inputs and outputs** section.  
![Update Audio driver Via Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/update-audio-driver-via-device-manager.jpg)
4. Find your audio device. Note the manufacturer and model name.
5. Search online for drivers for your device. Usually, these will be on the manufacturer's website.

 These drivers usually install with a double-click, but if it doesn't, go back to Device Manager and do this:

1. Right-click your audio device and select **Update driver**.
2. On the next page, select **Search automatically for drivers**. If it doesn't find anything, select **Browse my computer for drivers** and select it manually.  
![Search automatically for drivers-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-automatically-for-drivers-1.jpg)

 Wait until Windows downloads and installs the latest driver version. Once done, restart your device and check if the test tone is now playing.

## 6\. Reinstall the Audio Drivers

 If you're still having the same issue, then your audio drivers might be corrupted. So uninstall and reinstall them and check if it works. This process completely removes and reinstalls the driver package on your computer.

 It's a bit more time-consuming but worth trying if the above solutions fail. Here's how to do it:

1. Right-click on the Start menu and select **Device Manager**.
2. Expand the **Audio inputs and outputs** section.
3. Right-click your audio device and select **Uninstall device**.  
![Uninstall Audio driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-audio-driver.jpg)
4. If a warning pops up, click **Uninstall** to continue.
5. Now follow the on-screen instructions to uninstall the audio driver.

 After this, close the window and restart your computer. Once your system is up, Windows will automatically detect the audio device and install its driver. This will fix the issue if the driver was corrupted.

## 7\. Try Different Audio Formats

 Sample rate and a bit depth are two important settings that affect the sound quality on your computer. If these settings are not configured correctly, audio glitches may occur, causing the test tone to fail. Based on your device specs, you can change the sample rate and see if it helps.

 To change these settings, do the following:

1. Open the Control Panel and view it as the Category.
2. Click **Hardware and Sound** in the Control Panel, then select **Sound**.
3. On the **Playback** tab, right-click on your audio device and select **Properties**.
4. Next switch to the **Advanced** tab and check the box next to **Allow applications to take exclusive control of this device**.
5. Under **Default format**, select your desired sample rate from the drop-down menu.  
![Try Different Audio Formats](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/try-different-audio-formats.jpg)
6. Now try playing a test tone and see if it works.

 If this solution works, you should leave the settings at their current values. If it doesn't work, go back and select a different sample rate. Once you find the correct settings, click **Apply** \> **OK** to save the changes.

## 8\. Perform a Few General Fixes

 Besides the methods mentioned above, you can try a few general fixes that may help you get the test tone working.

* Disconnecting & reconnecting the audio device. Sometimes, this is all you need to do to fix it.
* [Updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/).
* You can also [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). It disables unnecessary third-party software running in the background, which may cause the issue. I
* If the problem persists, [use the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This utility scans all protected system files and replaces them if they are corrupted.

## Playing the Test Tone Again on Windows

 It appears that you are having problems with your sound card and the Windows test tone is not playing. Hopefully, one of these tips worked for you, and your speakers are now working.

 Dealing with audio problems on Windows is sometimes frustrating, but there are simple solutions available. This guide shows you how to troubleshoot the issue and get your speakers working again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/a-comprerante-tale-to-transform-your-windows-11-desk/"><u>A Comprerante Tale to Transform Your Windows 11 Desk</u></a></li>
<li><a href="https://win11.techidaily.com/5-top-win-drawing-apps-that-challenge-procreates-edge/"><u>5 Top Win Drawing Apps That Challenge Procreate's Edge</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-unveiling-the-art-of-reshaping-your-tiktok-avatar/"><u>2024 Approved  Unveiling the Art of Reshaping Your TikTok Avatar</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-approach-to-managing-settings-in-win11-ui/"><u>A Fresh Approach to Managing Settings in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-handy-manual-assessing-and-annulling-window-history-data/"><u>A Handy Manual: Assessing & Annulling Window History Data</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-upgrading-virtualbox-v70-in-win11/"><u>A Beginner's Guide to Upgrading VirtualBox v7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-the-windows-startup-settings/"><u>A Complete Guide to the Windows Startup Settings</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-for-restoring-windows-hello-fingerprint-functionality/"><u>7 Key Steps for Restoring Windows Hello Fingerprint Functionality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-compiling-the-top-10-affordable-video-conferencing-for-phones/"><u>[Updated] Compiling the Top 10 Affordable Video Conferencing for Phones</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-navigating-through-numbers-a-full-guide-for-measuring-youtube-success/"><u>[New] Navigating Through Numbers  A Full Guide for Measuring YouTube Success</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nlock-the-power-of-persuasion-perfecting-your-shorts-visual-hook-for-2024/"><u>[New] Unlock the Power of Persuasion  Perfecting Your Shorts' Visual Hook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-11-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 11 & 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-excellent-facial-editors-for-smartphones-for-2024/"><u>10 Excellent Facial Editors for Smartphones for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-2023-facebook-live-video-downloaders/"><u>In 2024, 2023 Facebook Live Video Downloaders</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://some-tips.techidaily.com/strengthening-your-presence-networking-techniques-for-youtubers-for-2024/"><u>Strengthening Your Presence  Networking Techniques for YouTubers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-expert-moves-for-restoring-the-functionality-of-windows-services-control-panel/"><u>7 Expert Moves for Restoring the Functionality of Windows Services Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-derek-walsh-phd-dr-jeffrey-l-gardiner-phd-and-david-c-muller-phd-from-their-book-understanding-the-psychology-of-religion-exploring-god-33/"><u>A Compre Written by Derek Walsh, PhD; Dr. Jeffrey L. Gardiner, PhD; and David C. Muller, PhD; From Their Book Understanding the Psychology of Religion: Exploring God Wise</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-best-in-class-textify-your-vlogs/"><u>[Updated] In 2024, Best in Class  Textify Your Vlogs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-poco-c65-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Poco C65</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-universal-companion-windows-now-app-for-iosmac-and-windows-devices/"><u>A Universal Companion: Windows Now App for iOS/Mac and Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-vivo-s18e-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Vivo S18e</u></a></li>
<li><a href="https://win11.techidaily.com/8-apps-for-changing-the-createdmodified-date-on-a-file-on-windows/"><u>8 Apps for Changing the Created/Modified Date on a File on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-setup-must-have-windows-store-essentials/"><u>Accelerate Setup: Must-Have Windows Store Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/a-scholarly-approach-to-embracing-hdr-in-windows-11-workflows/"><u>A Scholarly Approach to Embracing HDR in Windows 11 Workflows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-lens-legends-a-deep-dive-into-snapchats-transformative-tools/"><u>2024 Approved  Lens Legends  A Deep Dive Into Snapchat's Transformative Tools</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
</ul></div>
