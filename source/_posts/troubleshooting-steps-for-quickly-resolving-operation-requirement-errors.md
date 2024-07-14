---
title: Troubleshooting Steps for Quickly Resolving Operation Requirement Errors
date: 2024-07-13T10:00:03.592Z
updated: 2024-07-14T10:00:03.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Steps for Quickly Resolving Operation Requirement Errors
excerpt: This Article Describes Troubleshooting Steps for Quickly Resolving Operation Requirement Errors
keywords: OpReqError Fix,Error Resolution Tips,Quick OpRequirement Fixes,Resolve OpRequirements Fast,Operational Requirements Troubleshooting,Quickly Address OpErrors,Fixed Operation Error Steps
thumbnail: https://thmb.techidaily.com/f2cea06ab8ae79e3da9341215d5a2b3791081a5d0d2f702dc7f4ecb1fa023ae2.jpg
---

## Troubleshooting Steps for Quickly Resolving Operation Requirement Errors

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-ultimate-rankings-exceptional-free-auditory-slicing-applications-online/"><u>Updated 2024 Approved Ultimate Rankings Exceptional Free Auditory Slicing Applications Online</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a15-4g-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Samsung Galaxy A15 4G Phone without Any Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-dive-into-this-collection-of-14-text-animation-marvels/"><u>2024 Approved  Dive Into This Collection of 14 Text Animation Marvels</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-artistry-behind-capturing-evening-light-and-people/"><u>In 2024, The Artistry Behind Capturing Evening Light and People</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-no-cost-guide-to-harmonizing-audio-with-web-video-content/"><u>New The No-Cost Guide to Harmonizing Audio with Web Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sci-fi-virtual-horizons-a-selection-of-epic-movies-in-the-metaverse-realm/"><u>[Updated] Sci-Fi Virtual Horizons  A Selection of Epic Movies in the Metaverse Realm</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-15-funny-jokes-on-tiktok-for-giggles/"><u>[New] 15 Funny Jokes on TikTok for Giggles</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-a-beginners-guide-to-tell-you-what-3d-animation-is/"><u>Updated 2024 Approved A Beginners Guide to Tell You What 3D Animation Is</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/locate-video-game-audio-cues/"><u>Locate Video Game Audio Cues</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-playlist-passport-traveling-tunes-throughout-platforms/"><u>2024 Approved  Playlist Passport  Traveling Tunes Throughout Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-vivo-y27s-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Vivo Y27s Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-google-pixel-7a-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Google Pixel 7a to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-how-to-engage-with-snapchat-luminaries/"><u>In 2024, How to Engage with Snapchat Luminaries</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-locked-apple-iphone-6s-plus-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Forgot Locked Apple iPhone 6s Plus Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-from-apple-iphone-xs-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently From Apple iPhone XS</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-mastering-live-stream-capture-tv-show-recording-techniques/"><u>2024 Approved  Mastering Live Stream Capture  TV Show Recording Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-dive-into-design-get-a-complimentary-set-of-50-banner-pieces/"><u>[Updated] Dive Into Design  Get a Complimentary Set of 50 Banner Pieces</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-screencapture-2023-top-techs-recommendations-for-2024/"><u>[New] ScreenCapture 2023  Top Tech's Recommendations for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-strategies-for-captivating-handc-fb-campaigns-for-2024/"><u>Innovative Strategies for Captivating H&C FB Campaigns for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-beyond-default-modifying-siris-voice-across-apple-ecosystems/"><u>Updated 2024 Approved Beyond Default Modifying Siris Voice Across Apple Ecosystems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715701205047-in-device-recorder-activation-huaweis-mate-1020-and-p-series-phones-p20-p10/"><u>In-Device Recorder Activation  Huawei's Mate 10/20 & P Series Phones (P20, P10).</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-blueprint-for-crafting-an-individual-tiktok-marker/"><u>[Updated] The Blueprint for Crafting an Individual TikTok Marker</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-securing-your-snapchat-memories-mobile-recorders-guide/"><u>[Updated] 2024 Approved  Securing Your Snapchat Memories  Mobile Recorders' Guide</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-achieving-professional-audio-in-home-recording-studios/"><u>[Updated] In 2024, Achieving Professional Audio in Home Recording Studios</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-11-taskbar/"><u>Addressing Non-Operational Windows 11 Taskbar</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-update-your-brand-boost-engagement-on-tiktok/"><u>[New] Update Your Brand, Boost Engagement on TikTok</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-educational-youtube-channels/"><u>In 2024, Top 10 Educational YouTube Channels</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exceptional-facial-editing-software-iphoneandroid/"><u>[Updated] Exceptional Facial Editing Software, iPhone/Android</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-thriving-financially-with-successful-facebook-video-advertising-tactics/"><u>[New] In 2024, Thriving Financially with Successful Facebook Video Advertising Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/step-in-step-approach-hulu-recording-tutorial-for-diverse-systems-for-2024/"><u>Step-In-Step Approach  Hulu Recording Tutorial for Diverse Systems for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-ultimate-discord-screenshots-tools-online-desktop-and-mobile/"><u>In 2024, Ultimate Discord Screenshots Tools  Online, Desktop & Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
</ul></div>
