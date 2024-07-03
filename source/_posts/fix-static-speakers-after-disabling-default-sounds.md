---
title: Fix Static Speakers After Disabling Default Sounds
date: 2024-06-25T11:36:14.116Z
updated: 2024-06-26T11:36:14.116Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-through-system-failsafe-files-after-blue-screen/"><u>Traversing Through System Failsafe Files After Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-bricked-windows-update-fix/"><u>Bypassing a Bricked Windows Update Fix</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/unwavering-erasure-made-simple-configuring-windows-trash-for-permanent-deletion/"><u>Unwavering Erasure Made Simple: Configuring Windows Trash for Permanent Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-counter-after-incorrect-password-entry-windows-11-edition/"><u>Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/dont-double-dip-the-case-against-two-antiviruses/"><u>Don't Double Dip: The Case Against Two Antiviruses</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/top-30-inspirational-ideas-fusing-animated-themes-and-social-media/"><u>Top 30 Inspirational Ideas Fusing Animated Themes and Social Media</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-from-apple-iphone-xr-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server From Apple iPhone XR</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-what-makes-this-mp3-converter-for-windows-article-a-must-read/"><u>New 2024 Approved What Makes This Mp3 Converter for Windows Article a Must-Read?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-xiaomi-redmi-k70e-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Xiaomi Redmi K70E</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-breaking-down-the-barriers-to-knowing-your-fans/"><u>[New] In 2024, Breaking Down the Barriers to Knowing Your Fans</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-8-subtitle-transformers-seamless-switch-from-sub-to-srtr-in-seconds-on-windowsmacos/"><u>[Updated] Best 8 Subtitle Transformers  Seamless Switch From SUB to SRTR in Seconds on Windows/MacOS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-oneplus-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-boosting-watch-time-and-reducing-churn-on-youtube-the-ultimate-list-of-methods/"><u>[New] In 2024, Boosting Watch Time and Reducing Churn on YouTube  The Ultimate List of Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-sony-xperia-5-v-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Sony Xperia 5 V to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-master-the-art-of-sharing-funny-gifs-instagrams-latest-trend-explained-in-4-steps/"><u>[New] In 2024, Master the Art of Sharing Funny GIFs  Instagram's Latest Trend Explained in 4 Steps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>