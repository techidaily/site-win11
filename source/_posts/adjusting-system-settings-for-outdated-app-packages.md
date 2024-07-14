---
title: Adjusting System Settings for Outdated App Packages
date: 2024-07-13T11:20:15.047Z
updated: 2024-07-14T11:20:15.047Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting System Settings for Outdated App Packages
excerpt: This Article Describes Adjusting System Settings for Outdated App Packages
keywords: Update App Configs,Old Package Adjustments,Revise Application Settings,Upgrade App Packages,Tweak Outdated Software,Modify Obsolete Apps,Fix Deprecated Profiles
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Adjusting System Settings for Outdated App Packages

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

 You can use [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the [App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.


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
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/free-custom-minecraft-gif-templates/"><u>Free Custom Minecraft GIF Templates</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-clone-without-third-party-reliance-in-windows/"><u>Crafting Clone Without Third-Party Reliance in Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-10-key-devices-for-effective-zoom-sessions/"><u>[Updated] 2024 Approved  10 Key Devices for Effective Zoom Sessions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-vision-to-execution-the-full-spectrum-of-personal-branding-on-youtube/"><u>In 2024, From Vision to Execution  The Full Spectrum of Personal Branding on YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-detailed-tips-for-adequate-lighting-in-youtube-video-production/"><u>[Updated] 2024 Approved  Detailed Tips for Adequate Lighting in YouTube Video Production</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-efficient-windows-11-shortcuts-for-uwp-apps/"><u>Crafting Efficient Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-honor-by-drfone-android/"><u>How to Bypass FRP on Honor?</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-windows-control-with-administrator-rights/"><u>Conquering Windows Control with Administrator Rights</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-cross-promotion-mastery-sharing-igtv-to-fb-for-2024/"><u>[New] Cross-Promotion Mastery  Sharing IGTV to FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-a-perfect-replica-of-your-drive/"><u>How to Make a Perfect Replica of Your Drive</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-password-strength-in-windows-11-with-longer-pins/"><u>Enhancing Password Strength in Windows 11 with Longer Pins</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2-easy-methods-how-to-zoom-in-on-tiktok-videos/"><u>New 2 Easy Methods | How To Zoom In On TikTok Videos?</u></a></li>
<li><a href="https://video-capture.techidaily.com/ultimate-playbook-cutting-edge-methods-for-remarkable-mobizen-recordings/"><u>Ultimate Playbook  Cutting-Edge Methods for Remarkable Mobizen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://techidaily.com/why-are-your-photos-lost-from-iphone-8-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why are your photos lost from iPhone 8? | Stellar</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-whats-the-best-alternative-to-windows-movie-maker-on-mac-our-top-picks/"><u>2024 Approved Whats the Best Alternative to Windows Movie Maker on Mac? Our Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-pre-use-disk-formatting-notice-on-windows/"><u>Eliminating Pre-Use Disk Formatting Notice on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-rapid-video-resizing-techniques-for-professionals/"><u>Updated Rapid Video Resizing Techniques for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/directives-for-disabling-errors-on-gaming-platform/"><u>Directives for Disabling Errors on Gaming Platform</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-maximizing-your-tiktok-impact-from-fans-to-followers-and-beyond/"><u>[Updated] Maximizing Your TikTok Impact  From Fans to Followers and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-error-0x80070522-enhance-client-access-control/"><u>Eliminate Window's Error 0X80070522: Enhance Client Access Control</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-guide-to-incorrantey-instagrams-music-focused-emojis-for-2024/"><u>[Updated] Guide to Incorrantey Instagram's Music-Focused Emojis for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-androids-elite-10-gb-games-simulators/"><u>[Updated] 2024 Approved  Android's Elite 10 GB Games Simulators</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-screen-recording-101-using-filmora-scrn-to-capture-your-desktop/"><u>New 2024 Approved Screen Recording 101 Using Filmora Scrn to Capture Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-shutdown-the-guide-to-auto-mode-with-windows-1011/"><u>Efficient Shutdown: The Guide to Auto Mode with Windows 10/11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-ethical-implications-recording-whatsapp-calls-responsibly/"><u>2024 Approved  Ethical Implications  Recording WhatsApp Calls Responsibly</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-youtube-copyright/"><u>[Updated] The Ultimate Guide to YouTube Copyright</u></a></li>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-elevating-social-media-interaction-via-fb-story-links/"><u>[New] Elevating Social Media Interaction via FB Story Links</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/secrets-to-efficient-itunes-video-capturing/"><u>Secrets to Efficient iTunes Video Capturing</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-image-editing-techniques-for-subject-isolation/"><u>Advanced Image Editing: Techniques for Subject Isolation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-win-compatible-free-media-devices/"><u>Essential Guide: Win-Compatible Free Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-tips-for-prolonging-gopros-energy-stamina/"><u>2024 Approved  Tips for Prolonging GoPro's Energy Stamina</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-collect-lifes-moments-tiktok-files-free-and-pure-for-2024/"><u>[Updated] Collect Life's Moments - TikTok Files, FREE & Pure for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-how-to-record-a-video-presentation-using-adobe-captivate/"><u>[Updated] In 2024, How to Record a Video Presentation Using Adobe Captivate</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-definitive-10-screenshot-boosters-with-stickers-on-iphones-and-androids-for-2024/"><u>The Definitive 10 Screenshot Boosters with Stickers on iPhones & Androids for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/copying-powertoys-preferences-to-another-pc/"><u>Copying PowerToys Preferences to Another PC</u></a></li>
</ul></div>
