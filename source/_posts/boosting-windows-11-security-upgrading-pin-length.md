---
title: "Boosting Windows 11 Security: Upgrading PIN Length"
date: 2024-07-13T11:23:51.890Z
updated: 2024-07-14T11:23:51.890Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Windows 11 Security: Upgrading PIN Length"
excerpt: "This Article Describes Boosting Windows 11 Security: Upgrading PIN Length"
keywords: Win11 Security Boost,Increase Pin Security,Longer PIN Advantage,Enhance Window 11 Safety,Windows Upgrade Tips,Stronger User Lock,Secure Windows Update
thumbnail: https://thmb.techidaily.com/0464d20c8383250ad5eec7dae311ce3366a21c1ceecc558739dbb36535dbfcf9.jpg
---

## Boosting Windows 11 Security: Upgrading PIN Length

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-xiaomi-14-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-honor-70-lite-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Honor 70 Lite 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/enhancing-your-playtime-non-gamebar-video-recording-options/"><u>Enhancing Your Playtime  Non-GameBar Video Recording Options</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-fixing-windows-scheduler-failures/"><u>Beat the Bug: Fixing Windows Scheduler Failures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-how-to-secretly-browse-instagram-stories-on-desktop-and-mobile-devices-for-free/"><u>[Updated] 2024 Approved  How to Secretly Browse Instagram Stories on Desktop and Mobile Devices (For Free)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-elevating-listener-experience-through-powerful-podcast-covers-the-latest-design-dos-and-donts/"><u>Updated In 2024, Elevating Listener Experience Through Powerful Podcast Covers (The Latest Design Dos and Donts)</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/break-through-windows-barriers-be-an-admin-now/"><u>Break Through Windows Barriers - Be an Admin Now</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-ordinary-displays-elevate-your-screen-with-customized-themes-on-win11/"><u>Beyond Ordinary Displays: Elevate Your Screen with Customized Themes on Win11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-become-a-master-at-kinemaster-strategies-features-and-top-online-gaming-rivals/"><u>2024 Approved  Become a Master at KineMaster  Strategies, Features, and Top Online Gaming Rivals</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-windows-journey-with-a-voice-guide/"><u>Begin Your Windows Journey with a Voice Guide</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-overcome-steam-sync-error-on-windows/"><u>Best Practices to Overcome Steam Sync Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-monitors-brightness-with-top-software-select/"><u>Boosting Windows Monitors' Brightness with Top Software Select</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/0-scholarly-channels-on-youtube-for-history-aficionados-for-2024/"><u>Top 10 Scholarly Channels on Youtube for History Aficionados for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-1011-how-to-bypass-pin-locks/"><u>Breaking Down Windows 10/11: How to Bypass PIN Locks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-photoflex-max-best-windowsmac-picture-editors/"><u>2024 Approved  PhotoFlex Max  Best Windows/Mac Picture Editors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-top-7-tips-for-mastering-windows-11-49/"><u>Boosting Productivity: Top 7 Tips for Mastering Windows 11 (49)</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-corrupt-files-error-code-0x80070570-solutions-for-windows-11/"><u>Beating Back Corrupt Files Error Code 0X80070570: Solutions for Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-economical-growth-methodology-subscribe-now/"><u>[New] 2024 Approved  Economical Growth Methodology - Subscribe Now</u></a></li>
<li><a href="https://win11.techidaily.com/best-ways-to-restore-default-window-options-on-system-startup/"><u>Best Ways to Restore Default Window Options on System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-performance-and-functionality-via-improved-run-toolset/"><u>Boost Windows Performance and Functionality via Improved Run Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-conflict-over-shared-device-camera-error-0xa00f4243/"><u>Avoiding Conflict Over Shared Device (Camera, Error 0xA00F4243)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-cash-on-reddit-here-are-13-ways-for-new-users-for-2024/"><u>Quick Cash on Reddit? Here Are 13 Ways for New Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breakdown-of-windows-error-message-30005s-complexity/"><u>Breakdown of Windows Error Message 30005'S Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-key-steps-to-tackle-windows-blue-screen/"><u>Breaking Down Key Steps to Tackle Windows Blue Screen</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-best-5-quandale-dingle-voice-generators/"><u>New 2024 Approved Best 5 Quandale Dingle Voice Generators</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-an-admin-in-windows-control-settings/"><u>Becoming an Admin in Windows Control Settings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-pinnacle-of-immersion-highest-rated-oculus-headsets-for-2024/"><u>[New] The Pinnacle of Immersion  Highest-Rated Oculus Headsets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-art-of-cross-platform-content-sharing-for-2024/"><u>[Updated] The Art of Cross-Platform Content Sharing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://facebook.techidaily.com/metaverse-truths-and-misconceptions-a-reality-check/"><u>Metaverse Truths & Misconceptions – A Reality Check</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-display-with-w11s-auto-hdr-feature/"><u>Boost Your Display with W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/black-and-white-brilliance-a-guide-for-the-shadows/"><u>Black & White Brilliance: A Guide for the Shadows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-ide-performance-android-studio-tips/"><u>Accelerating IDE Performance: Android Studio Tips</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-realme-12plus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-galaxy-xcover-6-pro-tactical-edition-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Galaxy XCover 6 Pro Tactical Edition.</u></a></li>
<li><a href="https://win11.techidaily.com/automating-printer-removal-on-win11-devices/"><u>Automating Printer Removal on Win11 Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfect-iphone-silhouette-captures-101/"><u>In 2024, Perfect iPhone Silhouette Captures 101</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-intensive-investigation-the-gecata-game-logger/"><u>2024 Approved  Intensive Investigation  The Gecata Game Logger</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-mp60-mini-pc-expandable-storage-but-unremarkable-performance/"><u>Blackview MP60 Mini PC: Expandable Storage but Unremarkable Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-gameplay-seamlessly-adding-achievements-using-retroarch/"><u>Boosting Classic Gameplay - Seamlessly Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-streamlining-the-process-of-making-smaller-images-tips-and-tricks/"><u>[Updated] Streamlining the Process of Making Smaller Images  Tips & Tricks</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-do-you-want-to-professionally-blur-the-background-in-your-video-read-this-article-to-find-out-the-easiest-way-to-blur-the-background-in-videos-using-ado/"><u>New Do You Want to Professionally Blur the Background in Your Video? Read This Article to Find Out the Easiest Way to Blur the Background in Videos Using Adobe After Effects</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-vivo-y78t-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Vivo Y78t</u></a></li>
<li><a href="https://extra-hints.techidaily.com/extract-srt-from-zip-simple-subtitle-file-creation-tips/"><u>Extract SRT From ZIP  Simple Subtitle File Creation Tips</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-speed-implementing-a-smart-enhanced-run-feature/"><u>Boosting System Speed: Implementing a Smart Enhanced Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pc-wins-best-performance-fixes-ranked/"><u>Boost Your PC: Win's Best Performance Fixes Ranked</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-reduce-video-size-for-free-10-best-online-compressors/"><u>New Reduce Video Size for Free 10 Best Online Compressors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expressive-emojis-and-images-kinemaster-tips/"><u>In 2024, Expressive Emojis & Images  KineMaster Tips</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-a-look-at-four-game-changing-paint-additions/"><u>Breaking Barriers: A Look at Four Game-Changing Paint Additions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-save-webcam-videos-using-vlc-software/"><u>[Updated] In 2024, Save Webcam Videos Using VLC Software</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/how-to-watch-nba-in-real-time-15-effective-strategies-for-2024/"><u>How to Watch NBA in Real Time  15 Effective Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-audio-5-ways-for-above-100-output-on-pcs/"><u>Boosting Audio: 5 Ways for Above-100%% Output on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-novelties-the-next-gen-of-windows-11/"><u>Beyond Novelties: The Next Gen of Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-mastering-time-in-fcpx-freeze-frames-slow-mo-and-more/"><u>In 2024, Mastering Time in FCPX Freeze Frames, Slow-Mo, and More</u></a></li>
<li><a href="https://video-capture.techidaily.com/google-meetings-mastered-best-practices-4/"><u>Google Meetings Mastered  Best Practices #4</u></a></li>
<li><a href="https://extra-hints.techidaily.com/deciding-on-showcasing-your-off-facebook-journey/"><u>Deciding on Showcasing Your Off-Facebook Journey</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-essential-lenovo-display-recording-hacks/"><u>[New] In 2024, The Essential Lenovo Display Recording Hacks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>