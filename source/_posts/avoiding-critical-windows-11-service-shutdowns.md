---
title: Avoiding Critical Windows 11 Service Shutdowns
date: 2024-07-13T11:21:37.806Z
updated: 2024-07-14T11:21:37.806Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Critical Windows 11 Service Shutdowns
excerpt: This Article Describes Avoiding Critical Windows 11 Service Shutdowns
keywords: No W11 Crashes,Safe W11 Updates,Avoid W11 Outage,Secure W11 Patching,Prevent W11 Shutdowns,Stable Windows 11,Reliable W11 Service
thumbnail: https://thmb.techidaily.com/7c8eb4a6751ebbb720d8baa15eb6264cc6e760acb0b1ed4fef37387dcca189b5.jpg
---

## Avoiding Critical Windows 11 Service Shutdowns

 Windows 11 is notably superior to Windows 10\. From the modern start menu to widgets and icons, everything enhances your Windows experience. However, you may encounter performance issues at times.

 One of the main reasons might be the plethora of unnecessary Windows services running constantly. To fix this, you need to disable some unnecessary Windows services.

 In this article, we'll look over all those Windows 11 services that may contribute to slow performance and how you can disable them.

## How to Disable a Windows Service

 Certain Windows services often consume a severe amount of system resources. They operate continuously in the background, causing stutters and lags. But how can you find out which Windows 11 services to disable? And, before that, how to disable a Windows service?

 We advise creating a restore point before modifying any service settings. For the steps, refer to our guide on [how to use a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/).

 Below are the steps to disable a Windows 11 service:

1. [Open the Services app](https://www.makeuseof.com/windows-11-open-services-app/) and right-click on the service name you wish to disable.
2. From the context menu, select the **Properties** option.  
![Windows Services Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-services-context-menu.jpg)
3. Find the **Startup type** dropdown menu, and select **Disabled**.  
![Windows Services Startup Type Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-services-startup-type-option.jpg)

 Now that you understand how to disable a service, the main question is, which Windows 11 services are safe to disable?

 For that, we've listed all the services below in alphabetical order. Make sure to read about each service before disabling it! If you mistakenly disable a service, you can re-enable it from the same **Properties** window.

## 1\. AllJoyn Router Service

 The AllJoyn Router service enables you to connect your [IoT devices](https://www.makeuseof.com/tag/what-is-internet-of-things/) to your computer.

 If you don't prefer using or connecting smart devices like digital home security solutions, smart lights, or smart TVs with your Windows, there's no reason to keep this service enabled.

## 2\. AssignedAccessManager Service

 You might not be aware, but Windows has a feature called [Kiosk mode](https://www.makeuseof.com/windows-11-kiosk-mode/). This feature allows you to place restrictions on your computer. More specifically, it empowers you to force all users to access only a single app on your PC.

 The AssignedAccessManager service helps in setting up the kiosk mode. You may never need the kiosk mode if you don't use a public-facing computer. So, disable it using the steps outlined in the previous section.

## 3\. BitLocker Drive Encryption Service

 BitLocker is beneficial for encrypting your hard drive. However, you might not use it regularly due to its low popularity among Windows users. If so, you can safely disable the BitLocker Drive Encryption service.

 Remember, disabling this service will prevent you from using BitLocker and any other related functionality!

## 4\. Bluetooth services

 Bluetooth devices are on trend; ranging from earbuds and headphones to gaming controllers, wireless mice, and keyboards–all such devices make our work easier.

 However, if you prefer the old USB days, there's nothing wrong with that. If you have never used or don't plan to use any bluetooth device in the future, disable these services:

* **Bluetooth Audio Gateway Service**
* **Bluetooth Support Service**
* **Bluetooth User Support Service**

![All Windows Bluetooth Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-bluetooth-services.jpg)

## 5\. Connected User Experiences and Telemetry

 The Connected User Experiences and Telemetry service is responsible for sending your usage and diagnostic data to Microsoft servers. So, if this service is enabled on your computer, Microsoft may easily track the apps you use, the searches you make on the search bar, and more.

 Overall, no one enjoys being tracked, especially those who value privacy. Therefore, disable this service now to stop Microsoft from handling your user data.

## 6\. Delivery Optimization

 Windows updates, especially major ones, take a considerable time to download. The slow download speed may be due to your internet connection or other factors.

 The Delivery Optimization service does precisely what its name suggests: it improves the download speed of Windows updates and Microsoft apps by sharing bandwidth with your nearby devices.

 Don't be too excited, as it only works in the case of a local network or deployment setup! If you're not part of any local network, disable the Delivery Optimization service.

## 7\. Diagnostic Services

 Whenever something goes wrong on Windows, the first step the internet suggests is to [use Windows troubleshooters](https://www.makeuseof.com/windows-11-troubleshooters/). But, if you never bother to use any of them and fix the issues on your own, there are several diagnostic services that you can disable.

 Here are the services to disable if you don't prefer running any Windows troubleshooter:

* **Diagnostic Execution Service**
* **Diagnostic Policy Service**
* **Diagnostic Service Host**
* **Diagnostic System Host**

![All Windows Diagnostic Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-diagnostic-services.jpg)

## 8\. Geolocation Service

 As its name suggests, this service provides location-related data to Windows apps when needed. You can disable your location data if you don't want to share it due to privacy concerns.

 Once the Geolocation service is disabled, you won't be able to share your location using any Windows app or web browser.

## 9\. Netlogon

 The Netlogon service is only for domain networks. It means this service is only helpful in authenticating users within a domain environment. However, if your computer isn't part of such a network (as in the case of personal computers), disabling this service is a better option.

## 10\. Optimize Drives

 If you have ever defragmented your hard drive, you may be aware of its scheduled defragmentation feature. Simply put, this service handles routine defragmentation and optimization of your drives.

 So, if you like to [defrag your hard drive manually](https://www.makeuseof.com/defrag-hard-disk-drive-windows-11/) or if your system comes equipped with an SSD (which doesn't benefit from defragmentation), you might consider turning it off.

## 11\. Parental Controls

 This service is only helpful if you are a parent. With Parental Controls enabled, you can [restrict your children's computer use](https://www.makeuseof.com/windows-11-parental-controls-guide/). It mainly manages restrictive controls, including website and app restrictions.

 Now that you understand its usage, you can decide whether to disable the Parental Controls service.

## 12\. Phone Service

 The Phone Service handles connections between your computer and mobile devices. If you disable it, you may lose some mobile device syncing capabilities.

## 13\. Print Spooler

 The Print Spooler service is of great importance for printer users. It's the core service that allows you to print anything from your computer. If this service stops or gets disabled inadvertently, your printer-related tasks will not function.

 Therefore, proceed with caution if you plan to disable it! Remember, disabling this service will prevent you from using printers connected to your computer.

## 14\. Remote Desktop services

 Windows 11 includes a helpful feature called [Remote Desktop Connection](https://www.makeuseof.com/how-to-set-up-microsofts-remote-desktop-connection/). By using it, you can connect to any remote computer on the same network. And the Remote Desktop services handle the backend when you try to establish a connection.

 If you don't connect to remote desktop sessions, you can disable all its related services, which are:

* **Remote Desktop Configuration**
* **Remote Desktop Services**
* **Remote Desktop Services UserMode Port Redirector**

![All Windows Remote Desktop Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-remote-desktop-services.jpg)

## 15\. Sensor Service

 The Sensor service manages integration with sensors like GPS and ambient light sensors. If your device doesn't come equipped with such sensors or if you don't use applications that need sensor data, disabling this service is a good decision.

## 16\. Smart Card services

 Smart Cards are mainly for corporate users who sometimes need them for authentication on Windows devices. However, if you're a typical Windows user who prefers using a keyboard for login, you can disable the following smart card services:

* **Smart Card**
* **Smart Card Device Enumeration Service**
* **Smart Card Removal Policy**

![All Windows Smart Card Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-smart-card-services.jpg)

## 17\. Windows Biometric Service

 The Windows Biometric service is only helpful if you are using a laptop. It just enables the fingerprint to unlock functionality on laptops. Other than that, there is no use for this service. So, if you're using a PC or don't prefer using biometric unlock, you can disable it safely.

## 18\. Windows Error Reporting Service

 Just like other operating systems, Windows is not perfect. You may encounter an error or two after a Windows update.

 The Windows Error Reporting service automatically captures the event whenever you face an error on Windows. It then generates information about the error and sends it to Microsoft for further diagnosis.

 Disabling it is entirely safe, so feel free to turn it off from the Services app.

## 19\. Work Folders

 Work Folders are generally used in large organizations where people can store their local work-related files on a centralized server. They can then sync such files between work and personal computers. In short, Work Folders are an alternative to other file-syncing solutions.

 So, if your organization doesn't use this feature, the Work Folders service is safe to disable on Windows.

## 20\. Xbox Services

 Xbox services together offer the best possible experience when using an Xbox gaming console. These services handle Xbox Live features like saved game files, multiplayer access, and achievements, to name a few.

 If you don't use an Xbox or need any such feature in games, you can safely disable all the following services:

* **Xbox Accessory Management Service**
* **Xbox Live Auth Manager**
* **Xbox Live Game Save**
* **Xbox Live Networking Service**

![All Windows Xbox Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-xbox-services.jpg)

## Get Rid of Unwanted Windows 11 Services

 All the services we've mentioned above are safe to disable. However, always remember to create a restore point before making any changes, and be cautious when disabling services that might have specific use cases. For example, don't disable Bluetooth services if you prefer using a Bluetooth device. Similarly, if you use the fingerprint unlock on your laptop, don't modify the Windows Biometric service.

 One of the main reasons might be the plethora of unnecessary Windows services running constantly. To fix this, you need to disable some unnecessary Windows services.

 In this article, we'll look over all those Windows 11 services that may contribute to slow performance and how you can disable them.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/in-2024-hidden-gems-on-youtube-understanding-unlisted-videos/"><u>In 2024, Hidden Gems on YouTube  Understanding 'Unlisted' Videos</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-ms-teams-hurdle-error-80080300-in-win11/"><u>Overcoming MS Teams Hurdle Error 80080300 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-virtual-machine-performance-with-six-windows-tricks/"><u>Jumpstart Your Virtual Machine Performance with Six Windows Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-windows-build-numbers/"><u>Interpreting Windows Build Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/examining-the-role-and-relevance-of-wasd-in-windows/"><u>Examining the Role and Relevance of WASD in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-xiaomi-redmi-12-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Xiaomi Redmi 12 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/one-os-multiple-worlds-windows-across-mobile-tablet-mac-and-desktop-realized/"><u>One OS, Multiple Worlds: Windows Across Mobile, Tablet, Mac & Desktop Realized</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-the-blocked-fixing-windows-access-issues/"><u>Unblocking the Blocked: Fixing Windows Access Issues</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-inside-look-at-youtubes-creator-studio-interface/"><u>[Updated] Inside Look at YouTube's Creator Studio Interface</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-your-first-impression-matters-8-must-try-youtube-tools-for-thumbnails/"><u>[New] 2024 Approved  Your First Impression Matters  8 Must-Try YouTube Tools for Thumbnails</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sailing-the-skies-easily-how-to-pair-drones-and-propellers/"><u>In 2024, Sailing the Skies Easily  How to Pair Drones and Propellers</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-regain-basic-windows-settings-after-restart/"><u>Guide to Regain Basic Windows Settings After Restart</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-microsoft-outlook-problems-effectively/"><u>How to Repair Microsoft Outlook Problems Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-approaches-to-cure-the-ailing-windows-service-control-panel/"><u>7 Key Approaches to Cure the Ailing Windows Service Control Panel</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-samsung-gear-360-alternatives-updated-list-2023/"><u>[Updated] Samsung Gear 360 Alternatives  Updated List 2023</u></a></li>
<li><a href="https://win11.techidaily.com/unzipping-complex-archives-a-windows-cli-experts-manual/"><u>Unzipping Complex Archives: A Windows CLI Expert's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-moving-programs-from-older-win-pcs-to-windows-11/"><u>Essential Steps for Moving Programs From Older Win PCs to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-accessing-your-iis-management-center/"><u>Quick Fixes for Accessing Your IIS Management Center</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://win11.techidaily.com/w11s-moment-update-a-glimpse-at-the-next-gen-features/"><u>W11's Moment Update: A Glimpse at the Next-Gen Features</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/elite-6-ad-free-android-screen-captures-for-2024/"><u>Elite 6 AD-Free Android Screen Captures for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-score-high-in-video-conferencing-top-screen-recorders-reviewed-for-2024/"><u>[Updated] Score High in Video Conferencing  Top Screen Recorders Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mending-usb30-device-failure-in-windows-1011-systems/"><u>Mending USB3.0 Device Failure in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-visual-harmony-with-windows-desktop-wallpapers/"><u>Perfecting Visual Harmony with Windows Desktop Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-lighting-top-brightness-managers-for-windows-monitors/"><u>Optimal Lighting: Top Brightness Managers for Windows Monitors</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-ultimate-list-8-exceptional-movie-creators-for-mac-users/"><u>New In 2024, The Ultimate List 8 Exceptional Movie Creators for Mac Users</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-vn-editor-a-prominent-option-for-adding-luts-for-video-editing/"><u>Updated 2024 Approved VN Editor A Prominent Option for Adding Luts for Video Editing</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-superior-mac-gif-saving-the-ultimate-guide/"><u>[New] 2024 Approved  Superior Mac GIF Saving  The Ultimate Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-on-iphone-15-plus-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out On iPhone 15 Plus How to Bypass?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pixelshalfed-dissection/"><u>2024 Approved  PixelsHalfed Dissection</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-1011s-share-issue-with-nvidia/"><u>Addressing Windows 10/11'S Share Issue with NVIDIA</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/no-snip-from-prtscan-how-to-prevent-launch-of-snipping-tool-in-windows-11/"><u>No Snip From PrtScan: How to Prevent Launch of Snipping Tool in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-drivers-issue-22-resolved/"><u>GPU Drivers: Issue #22 Resolved</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-grasping-virtual-realitys-revolutionary-gear/"><u>[New] Grasping Virtual Reality's Revolutionary Gear</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-clearing-out-microsoft-edge/"><u>Easy Guide: Clearing Out Microsoft Edge</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/discover-the-top-4-audio-editing-programs-specifically-designed-for-mac-for-2024/"><u>Discover the Top 4 Audio Editing Programs Specifically Designed for Mac for 2024</u></a></li>
</ul></div>
