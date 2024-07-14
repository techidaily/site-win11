---
title: "Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
date: 2024-07-13T10:04:15.856Z
updated: 2024-07-14T10:04:15.856Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
excerpt: "This Article Describes Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
keywords: Win XP Fix Guide,WIN11 Patch Steps,Win10 Update Tips,LostWindows Support,Windows Patch Hacks,System Recovery Tools,OS Repaired Tutorials
thumbnail: https://thmb.techidaily.com/6ea42b82e55f6c668ff7a393a7539803912a1c23ef44a3dc870ec2d24d91150f.jpg
---

## Unlock the Code: Navigating Through Lost Windows 11/10 Patches

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell

![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  
![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-top-15-ff-extensions-for-easy-fb-video-download/"><u>2024 Approved  Top 15 FF Extensions For Easy FB Video Download</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcome-ppt-save-blunders-6-quick-fixes-windows-users-need/"><u>Swiftly Overcome PPT Save Blunders: 6 Quick Fixes Windows Users Need</u></a></li>
<li><a href="https://win11.techidaily.com/windows-auto-update-shutdown-guide/"><u>Windows Auto-Update Shutdown Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-flushed-to-functional-8-steps-for-desktop-color-correction/"><u>From Flushed to Functional: 8 Steps for Desktop Color Correction</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-secure-entry-into-windows-admin-console/"><u>Steps for Secure Entry Into Windows' Admin Console</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-note-taking-software-the-winning-seven/"><u>Essential Note-Taking Software: The Winning Seven</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-hidden-insta-story-accessibility-step-by-step-for-tech-savvy/"><u>[New] 2024 Approved  Hidden Insta Story Accessibility - Step-by-Step for Tech Savvy</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-capturing-and-saving-instagrams-transient-media-for-2024/"><u>How-To  Capturing and Saving Instagram's Transient Media for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-mastering-igtv-sharing-via-insta-stories/"><u>In 2024, Mastering IGTV Sharing via Insta Stories</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h-265-on-samsung-galaxy-a15-4g-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Samsung Galaxy A15 4G, is it possible?</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-master-fast-sharing-youtube-playlists-made-simple/"><u>2024 Approved  Master Fast Sharing  YouTube Playlists Made Simple</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-razr-40-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Razr 40</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-hdr-visualization-with-windows-11/"><u>Dive Deep Into HDR Visualization with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win11s-notepad-with-virtuoso-helper/"><u>Accelerate Win11's Notepad with Virtuoso Helper</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-oppo-find-x6-pro-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Oppo Find X6 Pro Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-usage-of-computational-resources-by-unrealcefsubprocess/"><u>Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-gif-size-barrier-on-discord-for-win11-users/"><u>Breaking Down the GIF Size Barrier on Discord for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-essential-tips-for-perfect-webinar-saves/"><u>[New] In 2024, Essential Tips for Perfect Webinar Saves</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-clip-curator-platform/"><u>[New] Clip Curator Platform</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-gastronomic-gala-top-food-videos-sweeping-social-media-for-2024/"><u>[Updated] Gastronomic Gala  Top Food Videos Sweeping Social Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://extra-hints.techidaily.com/inside-look-expert-techniques-with-vlc-playback/"><u>Inside Look  Expert Techniques with VLC Playback</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-time-lapse-video-editing-made-easy-top-software-freeandpaid/"><u>New In 2024, Time-Lapse Video Editing Made Easy Top Software Free&Paid</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-nubia-red-magic-9-pro-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-zooming-into-success-a-complete-guide-to-podcast-audio-capture-for-2024/"><u>[Updated] Zooming Into Success  A Complete Guide to Podcast Audio Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/basic-tips-how-to-record-and-save-google-voice-calls/"><u>Basic Tips  How to Record and Save Google Voice Calls</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-free-video-editing-apps-for-android-no-watermark-no-hassle/"><u>Updated 2024 Approved Free Video Editing Apps for Android No Watermark, No Hassle</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-y200-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo Y200</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/burying-your-data-secretive-drive-practices/"><u>Burying Your Data: Secretive Drive Practices</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-networking-with-python-servers-on-windows-os/"><u>Advanced Networking with Python Servers on Windows OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-tecno-spark-20-by-drfone-android/"><u>How to Bypass FRP from Tecno Spark 20?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-unlocked-effective-tpm-deactivation/"><u>Windows 11 Unlocked: Effective TPM Deactivation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-expert-recommendations-for-efficient-gif-makers/"><u>[New] 2024 Approved  Expert Recommendations for Efficient GIF Makers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-unleash-nostalgia-easy-vhs-effects-in-final-cut-pro/"><u>In 2024, Unleash Nostalgia Easy VHS Effects in Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-iphone-se-without-backup-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Restore iPhone SE without Backup | Stellar</u></a></li>
</ul></div>
