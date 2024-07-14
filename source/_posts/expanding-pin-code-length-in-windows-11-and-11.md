---
title: Expanding Pin Code Length in Windows 11 and 11
date: 2024-07-13T09:44:09.445Z
updated: 2024-07-14T09:44:09.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expanding Pin Code Length in Windows 11 and 11
excerpt: This Article Describes Expanding Pin Code Length in Windows 11 and 11
keywords: Windows 11 Pin Code Update,Longer Windows 11 PIN,Increase Windows 11 PIN Size,Pin Code Expansion in Windows 11,Enhance Windows 11 Security,Upgraded PIN Length Windows 11,Widening PIN Code Windows 11
thumbnail: https://thmb.techidaily.com/e5791482249db05b2c83cd0dadb655c84a6fd60d498599c2c81d00c0991581e6.jpg
---

## Expanding Pin Code Length in Windows 11 and 11

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/leveraging-advanced-tools-for-improved-admin-workflows-in-windows/"><u>Leveraging Advanced Tools for Improved Admin Workflows in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/excellence-in-audio-on-windows-best-8-podcast-apps-compiled-for-2024/"><u>Excellence in Audio on Windows  Best 8 Podcast Apps Compiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-crack-the-code-of-imagerys-roots-with-our-reverse-analysis-tools-for-instagram/"><u>2024 Approved  Crack the Code of Imagery's Roots with Our Reverse Analysis Tools for Instagram</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/proven-7-audio-processors-to-peacefully-remove-populated-sounds-from-media/"><u>Proven 7 Audio Processors to Peacefully Remove Populated Sounds From Media</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-how-to-manage-and-disable-recommended-podcast-episodes-in-spotify/"><u>[Updated] In 2024, How to Manage and Disable Recommended Podcast Episodes in Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/access-and-conquer-mastering-windows-11-printer-control-max-50-chars/"><u>Access and Conquer: Mastering Windows 11 Printer Control (Max 50 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-transfer-in-google-chrome-now-easier-on-windows/"><u>Mastering File Transfer in Google Chrome, Now Easier on Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-how-to-integrate-siri-on-tiktok-a-comprehensive-guidebook/"><u>[Updated] 2024 Approved  How to Integrate Siri on TikTok - A Comprehensive Guidebook</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/secure-total-visual-display-for-2024/"><u>Secure Total Visual Display for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-look-at-sonys-x1000v-hd-recorder/"><u>[New] In-Depth Look at Sony's X1000V HD Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-engage-audiences-skywards-drone-filming-and-facebook-live/"><u>[Updated] 2024 Approved  Engage Audiences Skywards  Drone Filming and Facebook Live</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://audio-editing.techidaily.com/choruscraft-the-premier-digital-voice-transformer-for-singers/"><u>ChorusCraft The Premier Digital Voice Transformer for Singers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/exclusive-voip-services-designed-for-the-modern-game-player/"><u>Exclusive VoIP Services Designed for the Modern Game Player</u></a></li>
<li><a href="https://win11.techidaily.com/direct-pc-access-through-smb-protocols-mobile/"><u>Direct PC Access Through SMB Protocols (Mobile)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-leveraging-colored-backdrops-for-seamless-edits-for-2024/"><u>[Updated] Leveraging Colored Backdrops for Seamless Edits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/get-across-taskbar-and-tile-adjustments-fast/"><u>Get Across Taskbar & Tile Adjustments Fast</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-nullifying-windows-tracking-mechanism/"><u>Techniques for Nullifying Windows' Tracking Mechanism</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-mac-video-production-powerhouse-adobe-premiere-pro-for-2024/"><u>New Mac Video Production Powerhouse Adobe Premiere Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-file-lifecycle-in-windows-11-set-up-autodelete-protocols/"><u>Efficient File Lifecycle in Windows 11: Set Up Autodelete Protocols</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-smooth-video-transfer-facebook-integration-with-whatsapp/"><u>[New] 2024 Approved  Smooth Video Transfer  Facebook Integration with WhatsApp</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-unleash-your-creativity-20-best-adobe-premiere-title-templates-free-download/"><u>New In 2024, Unleash Your Creativity 20 Best Adobe Premiere Title Templates Free Download</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-funny-photo-tinkering-tool-for-2024/"><u>Ultimate Funny Photo Tinkering Tool for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-tips-for-perfected-framing-implementing-letterboxing-on-social-media/"><u>[Updated] Tips for Perfected Framing  Implementing Letterboxing on Social Media</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-audio-liberation-the-ultimate-guide-to-pazeras-extraction-tools/"><u>In 2024, Audio Liberation  The Ultimate Guide to Pazera's Extraction Tools</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-dxgidll-quick-fixes-for-the-missing-file/"><u>Win11 & Dxgi.dll: Quick Fixes for the Missing File</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-navigating-the-world-of-youtubers-and-gaming-sessions/"><u>In 2024, Navigating the World of YouTubers and Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-additional-av-software-on-windows/"><u>Techniques for Enabling Additional AV Software on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-creativity-discovering-the-latest-in-microsoft-paint/"><u>Elevate Creativity: Discovering the Latest in Microsoft Paint</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wsreset-troubleshooting-in-windows-environments/"><u>Mastering WSReset Troubleshooting in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-pc-finder-power-with-everythingapp/"><u>Supercharge PC Finder Power with EverythingApp</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-prevent-dynamic-volume-reduction-by-apps-on-iphone/"><u>2024 Approved Prevent Dynamic Volume Reduction by Apps on iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-search-failures-immediately/"><u>Addressing Windows 11 Search Failures Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-from-apple-iphone-14-pro-max-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication From Apple iPhone 14 Pro Max? 5 Tips You Must Know</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-rhythm-and-resolution-leading-applications-for-seamless-beat-integration-into-videos-2023-edition-for-2024/"><u>New Rhythm & Resolution Leading Applications for Seamless Beat Integration Into Videos, 2023 Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/instant-spooler-restart-methods-for-windows/"><u>Instant Spooler Restart Methods for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-effective-app-packages-control-using-winget-on-win11/"><u>Top Tips for Effective App Packages Control Using Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-code-0x80d03801-in-microsoft-store-on-windows-pc/"><u>How to Fix Error Code 0X80d03801 in Microsoft Store on Windows PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-xiaomi-redmi-13c-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Xiaomi Redmi 13C Devices</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-open-exes-without-issues/"><u>Troubleshooting Windows: Open EXEs Without Issues</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-core-concepts-of-story-making/"><u>[New] Core Concepts of Story Making</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-updated-blueprint-for-incorporating-decay-effects-into-digital-soundtracks/"><u>Updated The Updated Blueprint for Incorporating Decay Effects Into Digital Soundtracks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-most-massive-lifting-machines-in-the-sky-for-2024/"><u>The Most Massive Lifting Machines in the Sky for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-a-new-pdf-reader-standard-on-os/"><u>Instituting a New PDF Reader Standard on OS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/begin-with-class-in-every-screen-best-intro-editor-app/"><u>Begin with Class in Every Screen  Best Intro Editor App</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/maneuvering-through-typical-anydesk-frustrations-on-windows/"><u>Maneuvering Through Typical AnyDesk Frustrations on Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-immortalize-gameplay-glories-with-samsung-devices/"><u>[New] 2024 Approved  Immortalize Gameplay Glories with Samsung Devices</u></a></li>
</ul></div>
