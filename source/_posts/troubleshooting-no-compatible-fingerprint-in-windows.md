---
title: Troubleshooting No Compatible Fingerprint in Windows
date: 2024-07-13T10:13:40.075Z
updated: 2024-07-14T10:13:40.075Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting No Compatible Fingerprint in Windows
excerpt: This Article Describes Troubleshooting No Compatible Fingerprint in Windows
keywords: WinFingerprintError,UnsupportedWindowsID,IDNotFoundIssue,IncompatibleFingerID,FixFingerprintFail,ResolveNoMatchWin,RemoveInvalidFingerID
thumbnail: https://thmb.techidaily.com/893ed101846c23a15225b4055236cf141325f0b733704c87b6bafd0385f7132f.jpg
---

## Troubleshooting No Compatible Fingerprint in Windows

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on [how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to [uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a [Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on [enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on [fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://win11.techidaily.com/advanced-tactics-in-managing-windows-startup-procedures/"><u>Advanced Tactics in Managing Windows Startup Procedures</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-essential-techniques-for-saving-roblox-playback-on-mac/"><u>[New] 2024 Approved  Essential Techniques for Saving Roblox Playback on Mac</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-mouse-dynamics-for-a-more-natural-response-in-win-1011/"><u>Adjusting Mouse Dynamics for a More Natural Response in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-dark-theme-for-windows-calc/"><u>Activate Dark Theme for Windows Calc</u></a></li>
<li><a href="https://win11.techidaily.com/altwindirstat-reigniting-your-file-systems-potential-on-windows/"><u>AltWinDirStat: Reigniting Your File System's Potential on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-poco-c50-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Poco C50 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-your-window-to-wins-cli-default-actions/"><u>Adjust Your Window to Win's CLI: Default Actions</u></a></li>
<li><a href="https://win11.techidaily.com/android-transition-post-subsystem-discontinuation-whats-next/"><u>Android Transition Post-Subsystem Discontinuation: What's Next?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-pro-tips-for-re-sharing-on-instagram/"><u>[Updated] Pro Tips for Re-Sharing on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-for-windowsapps-acquisition/"><u>Advanced Methods for WindowsApps Acquisition</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-elevated-viewing-larger-youtube-images/"><u>[New] 2024 Approved  Elevated Viewing  Larger YouTube Images</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-unlock-professional-filmmaking-skills-within-xp/"><u>[Updated] In 2024, Unlock Professional Filmmaking Skills Within XP</u></a></li>
<li><a href="https://ai-topics.techidaily.com/how-to-create-funny-talking-avatars-using-oddcast-text-to-speech-tech-for-2024/"><u>How to Create Funny Talking Avatars Using Oddcast Text to Speech Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inkpad-functionality-woes/"><u>Addressing Windows Inkpad Functionality Woes</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-terminal-for-quake-interface/"><u>Activating Windows Terminal for Quake Interface</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-oled-bape-edition-review-stealthy-stylish-and-practical/"><u>ASUS Vivobook S 15 OLED BAPE Edition Review: Stealthy, Stylish, and Practical</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-from-video-to-mp3-maintaining-audio-fidelity-made-easy/"><u>In 2024, From Video to MP3 Maintaining Audio Fidelity Made Easy</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-diving-deep-into-instagrams-new-features/"><u>[New] In 2024, Diving Deep Into Instagram's New Features</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-improve-obs-rendering-speed-and-quality/"><u>2024 Approved  Improve OBS Rendering Speed and Quality</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-itel-s23-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Itel S23 Device</u></a></li>
<li><a href="https://win11.techidaily.com/activation-verification-methods-for-windows-11/"><u>Activation Verification Methods for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-error-unauthorized-file-reading-in-win11/"><u>Addressing Steam Error: Unauthorized File Reading in Win11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/diy-ig-videos-tips-and-template-inspirations-for-2024/"><u>DIY IG Videos  Tips & Template Inspirations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/fiendish-funny-factory/"><u>Fiendish Funny Factory</u></a></li>
<li><a href="https://win11.techidaily.com/access-from-afar-zero-password-connectivity-on-win-11/"><u>Access From Afar: Zero-Password Connectivity on Win 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-your-iphone-se-passcode-4-easy-methods-with-or-without-itunes-drfone-by-drfone-ios/"><u>How to Unlock Your iPhone SE Passcode 4 Easy Methods (With or Without iTunes) | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-new-to-video-editing-here-are-the-best-free-tools-desktoponlinemobile/"><u>Updated New to Video Editing? Here Are the Best Free Tools Desktop/Online/Mobile</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-comprehensive-guide-to-the-top-10-cost-free-picture-archives/"><u>In 2024, Comprehensive Guide to the Top 10 Cost-Free Picture Archives</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-mac-users-guide-to-stellar-tiktok-beginnings/"><u>2024 Approved  Mac Users' Guide to Stellar TikTok Beginnings</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-uncovered-top-mac-speech-to-text-apps-you-never-knew-existed-free-and-no-installation/"><u>2024 Approved Uncovered Top Mac Speech-to-Text Apps You Never Knew Existed Free & No Installation</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-chaos-tidy-up-your-icons/"><u>Avoid Visual Chaos: Tidy Up Your Icons</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-system-settings-for-outdated-app-packages/"><u>Adjusting System Settings for Outdated App Packages</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-in-the-ms-store-a-step-by-step-guide/"><u>Accelerating Downloads in the MS Store - A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-engaging-audiences-crafting-youtube-trailers-via-filmora/"><u>[Updated] 2024 Approved  Engaging Audiences  Crafting YouTube Trailers via Filmora</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-list-of-cutting-edge-anime-vocal-adaptors-and-alterers-for-pcs-and-phones/"><u>Updated The Ultimate List of Cutting-Edge Anime Vocal Adaptors and Alterers for PCs & Phones</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-multi-archive-handling-in-windows-os/"><u>Advanced Multi-Archive Handling in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-pc-energy-utilization-efficiency/"><u>Assessing Windows PC Energy Utilization Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/app-and-browser-domination-on-windows-os/"><u>App & Browser Domination on Windows OS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-file-download-voice-track-analysis/"><u>2024 Approved  File Download  Voice Track Analysis</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/enhancing-visuals-tips-for-recording-ppt-effectively/"><u>Enhancing Visuals  Tips for Recording PPT Effectively</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-splitcam-examination-camera-quality-showdown-for-2024/"><u>[New] SplitCam Examination - Camera Quality Showdown for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-htc-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change HTC Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-failure-notifications-in-w10w11-pcs/"><u>Addressing 'Device Failure' Notifications in W10/W11 PCs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-inshot-vs-competitors-a-detailed-video-app-review/"><u>2024 Approved  InShot vs Competitors  A Detailed Video App Review</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-headphone-and-speaker-non-detection-in-windows-os/"><u>Addressing Headphone & Speaker Non-Detection in WINDOWS OS</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-revolutionize-unboxing-on-instagram-a-guide-to-popularity/"><u>[Updated] 2024 Approved  Revolutionize Unboxing on Instagram  A Guide to Popularity</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mirthful-milestones-an-examination-of-goofy-odyssey/"><u>In 2024, 'Mirthful Milestones'  An Examination of 'Goofy Odyssey'</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-systemsettings-issue-on-windows-11/"><u>Addressing SystemSettings Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-monitor-settings-quickly/"><u>Adjusting Monitor Settings Quickly</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-3-ways-of-how-to-get-someones-apple-id-off-iphone-se-2020-without-password-by-drfone-ios/"><u>In 2024, 3 Ways of How to Get Someones Apple ID Off iPhone SE (2020) without Password</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamlining-time-lapse-photography-with-gopro-software/"><u>[New] Streamlining Time-Lapse Photography with GoPro Software</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-infinix-note-30i-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Infinix Note 30i</u></a></li>
<li><a href="https://network-issues.techidaily.com/remedying-screen-malfunctions-in-laptops/"><u>Remedying Screen Malfunctions in Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-to-new-horizons-migrating-apps-for-a-windows-11-laptop/"><u>Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/g-the-green-glow-youtubes-mac-solution-manual-for-2024/"><u>Nixing the Green Glow  YouTube's Mac Solution Manual for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/unveiling-an-assortment-of-authentic-dog-noise-recordings/"><u>Unveiling an Assortment of Authentic Dog Noise Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitter-mastery-adding-visuals-to-your-tweet/"><u>[New] 2024 Approved  Twitter Mastery  Adding Visuals to Your Tweet</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-get-more-engagement-the-simplest-way-to-resize-vertical-videos-for-social-media/"><u>Updated 2024 Approved Get More Engagement The Simplest Way to Resize Vertical Videos for Social Media</u></a></li>
</ul></div>
