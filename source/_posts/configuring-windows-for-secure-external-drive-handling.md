---
title: Configuring Windows for Secure External Drive Handling
date: 2024-07-13T10:30:50.057Z
updated: 2024-07-14T10:30:50.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Windows for Secure External Drive Handling
excerpt: This Article Describes Configuring Windows for Secure External Drive Handling
keywords: Secure Drive Configuration,External Drive Security,Safe Data Transfer Windows,Protecting External Storage,Secured Drives in Windows,Enhanced Drive Safety Windows,Encrypted Disk Handling
thumbnail: https://thmb.techidaily.com/b9b05a126aedfd2f1ee9a14603409ac5ab4c281ddb514708f183215c5384ae47.jpg
---

## Configuring Windows for Secure External Drive Handling

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-decoding-vsdcs-technology-against-top-screen-recorder-competitors/"><u>[Updated] In 2024, Decoding VSDC's Technology Against Top Screen Recorder Competitors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-elevate-your-brand-10-best-intro-builder-websites/"><u>In 2024, Elevate Your Brand 10 Best Intro Builder Websites</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premiere-pros-picks-professional-camera-stabilizers-reviewed/"><u>2024 Approved  Premiere Pros' Picks  Professional Camera Stabilizers Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/android-as-a-w11-secondary-display-step-by-step-guide/"><u>Android as a W11 Secondary Display: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-your-download-experience-with-epic-launcher/"><u>Accelerating Your Download Experience with Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/aspire-to-win-11s-trials-joining-the-insider-brigade/"><u>Aspire to Win 11'S Trials: Joining the Insider Brigade</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/adopt-wsl-the-easy-way-to-run-linux-commands/"><u>Adopt WSL: The Easy Way to Run Linux Commands</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-call-failed-problems-in-windows-devices/"><u>Addressing 'Call Failed' Problems in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://facebook.techidaily.com/6-unexpected-ways-facebook-enhances-your-daily-life/"><u>6 Unexpected Ways Facebook Enhances Your Daily Life</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/beat-infused-videos-a-step-by-step-guide-to-adding-tunes-to-fb-for-2024/"><u>Beat-Infused Videos  A Step-by-Step Guide to Adding Tunes to FB for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-online-vertical-video-editing-made-easy-top-picks/"><u>Updated Online Vertical Video Editing Made Easy Top Picks</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-nix-the-sneaky-youtube-quick-playback-feature/"><u>[Updated] Nix the Sneaky YouTube Quick Playback Feature</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-the-art-of-editing-powerdirector-complete-guide-and-tutorials-2024/"><u>[New] Master the Art of Editing  PowerDirector Complete Guide & Tutorials 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-discreprancies-in-power-usage-display-for-win-11-systems/"><u>Addressing Discreprancies in Power Usage Display for Win 11 Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-cost-monitor-functionality-of-your-wifi-network/"><u>Adjusting the Cost Monitor Functionality of Your Wifi Network</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-memory-shortage-in-the-magical-school-of-hogwarts-game/"><u>Addressing Memory Shortage in The Magical School of Hogwarts Game</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unifying-your-musical-journey-converting-spotify-plays-into-youtube-music-lists/"><u>Unifying Your Musical Journey  Converting Spotify Plays Into YouTube Music Lists</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-flat-screens-to-spatial-storytelling-understanding-vr/"><u>2024 Approved  From Flat Screens to Spatial Storytelling  Understanding VR</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-engaging-enthusiasts-top-biographical-approaches-for-growing-followers-inspired-by-filmora-for-2024/"><u>[New] Engaging Enthusiasts  Top Biographical Approaches for Growing Followers, Inspired by Filmora for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-efficiency-strategies-for-effective-multitasking-with-windows-11/"><u>Amplify Efficiency: Strategies for Effective Multitasking with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/age-friendly-features-in-pre-windows-10-systems/"><u>Age-Friendly Features in Pre-Windows 10 Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mobile-editing-hacks-writing-on-photos/"><u>[New] Mobile Editing Hacks  Writing on Photos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-streaming-success-stories-of-gaming-geeks/"><u>[New] 2024 Approved  Streaming Success Stories of Gaming Geeks</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-unsupported-drive-issue-in-windows/"><u>Unraveling the 'Unsupported Drive' Issue in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-calculating-riches-a-look-at-mr-beasts-wallet/"><u>2024 Approved  Calculating Riches  A Look at Mr. Beast's Wallet</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ultimate-lens-selection-tips-for-vloggers-and-editors/"><u>2024 Approved  Ultimate Lens Selection Tips for Vloggers & Editors</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-sound-controls-in-windows-os/"><u>Addressing Faulty Sound Controls in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-management-application-hiccups/"><u>Avoid Windows Management Application Hiccups</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-oppo-reno-8t-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Oppo Reno 8T to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlock-video-mastery-with-these-quick-trimming-tips-for-windows-10/"><u>Unlock Video Mastery with These Quick Trimming Tips for Windows 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-creating-a-captivating-instagram-cover-for-your-topics-highlight/"><u>[Updated] 2024 Approved  Creating a Captivating Instagram Cover for Your Topics Highlight</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-loading-lag-quick-fix-for-lol-on-win/"><u>Avoid Loading Lag: Quick Fix for LOL on Win</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unleash-your-dj-iq-with-free-luts-for-djis-minis-and-air-series/"><u>In 2024, Unleash Your DJ IQ with FREE LUTs for DJI's Minis & Air Series</u></a></li>
</ul></div>
