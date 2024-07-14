---
title: "Improving Performance: Managing Memory Usage for Connected Services"
date: 2024-07-13T09:53:25.738Z
updated: 2024-07-14T09:53:25.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Improving Performance: Managing Memory Usage for Connected Services"
excerpt: "This Article Describes Improving Performance: Managing Memory Usage for Connected Services"
keywords: Memory Management,Service Efficiency,Performance Optimization,Data Usage Control,Connectivity Enhancement,Resource Allocation,Streamlining Services
thumbnail: https://thmb.techidaily.com/b38051c9d12a2b8d1315fdc2f1d84dde69fd749e096f758fd9b3624bcd8211ec.jpg
---

## Improving Performance: Managing Memory Usage for Connected Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/24-charting-your-course-in-the-realm-of-youtube-shorts/"><u>In 2024, Charting Your Course in the Realm of YouTube Shorts</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-banter-bonanza-the-funniest-content-on-the-internet-for-2024/"><u>[Updated] Banter Bonanza  The Funniest Content on the Internet for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-methods-of-exporting-audio-from-audacity-in-mp3-format/"><u>In 2024, Methods of Exporting Audio From Audacity in MP3 Format</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-diagnostic-criteria-for-fetal-alcohol-syndrome/"><u>In 2024, Diagnostic Criteria for Fetal Alcohol Syndrome</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-os-security-patches/"><u>Navigating Windows OS Security Patches</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-en-2022-puede-editar-todos-los-videos-inmediatamente-despues-de-capturarlos-pero-primero-debe-descubrir-una-aplicacion-de-edicion-de-vlogs/"><u>New 2024 Approved En 2022, Puede Editar Todos Los Videos Inmediatamente Después De Capturarlos, Pero Primero Debe Descubrir Una Aplicación De Edición De Vlogs Que Realmente Le Guste Usar</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-using-lesser-known-windows-11-assets-efficiently/"><u>Pro-Tips for Using Lesser Known Windows 11 Assets Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-boot-and-tpm-activationdeactivation-in-vbox-70/"><u>Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-tecno-pova-5-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Tecno Pova 5 Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-not-enough-privileges-error-during-installation-on-windows/"><u>Eliminating Not Enough Privileges Error During Installation on Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/audience-accessibility-enhancement-adding-subtitles-and-closed-captions-on-youtube-for-2024/"><u>Audience Accessibility Enhancement  Adding Subtitles and Closed Captions on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-perfecting-sims-4-live-action-for-videographers/"><u>[Updated] 2024 Approved  Perfecting Sims 4 Live Action for Videographers</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-concealing-content-securing-video-data-ethics-for-2024/"><u>[New] Concealing Content  Securing Video Data Ethics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-win11s-network-settings/"><u>Guiding Through Win11's Network Settings</u></a></li>
<li><a href="https://win11.techidaily.com/instant-connectivity-breakthroughs-win-11s-unauthorized-access-guide/"><u>Instant Connectivity Breakthroughs: Win 11'S Unauthorized Access Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhancing-viewability-of-fb-videos-hv-debate-for-2024/"><u>Enhancing Viewability of FB Videos – H/V Debate for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-voice-cloning-simplified-two-approaches-to-achieve-consistent-ai-voices/"><u>2024 Approved Voice Cloning Simplified Two Approaches to Achieve Consistent AI Voices</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-unlocking-content-discovery-with-instagram-hashtags/"><u>2024 Approved  Unlocking Content Discovery with Instagram Hashtags</u></a></li>
<li><a href="https://win11.techidaily.com/operating-unity-windows-rolls-out-across-apple-pc-mac-android-world/"><u>Operating Unity: Windows Rolls Out Across Apple, PC, Mac, Android World</u></a></li>
<li><a href="https://article-posts.techidaily.com/become-a-successful-smm-in-10-steps/"><u>Become a Successful SMM in 10 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-connection-issues-malwarebytes-service-errors-in-win-1011/"><u>Fixing Connection Issues: Malwarebytes' Service Errors in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-installing-new-drivers-in-windows-11/"><u>Mastering the Art of Installing New Drivers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maxing-out-melodies-best-5-apps-for-boosting-windows-audio-by-100plus/"><u>Maxing Out Melodies: Best 5 Apps for Boosting Windows' Audio By 100%%+</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-ignite-curiosity-with-a-personal-touch-anime-subscribe-buttons-for-filmmakers-filmora/"><u>[New] Ignite Curiosity with a Personal Touch - Anime Subscribe Buttons for Filmmakers (Filmora)</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-samsung-galaxy-a34-5g-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Samsung Galaxy A34 5G Wont Charge | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-protecting-ideas-avoidance-of-rash-removals/"><u>[Updated] In 2024, Protecting Ideas  Avoidance of Rash Removals</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tips-for-speeding-up-your-tiktok-videos-for-2024/"><u>Tips for Speeding Up Your TikTok Videos for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ize-your-money-with-these-top-10-simple-and-strategic-youtube-biz-channels-for-2024/"><u>Maximize Your Money with These Top 10 Simple and Strategic YouTube Biz Channels for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-best-of-both-worlds-free-and-paid-3d-video-creation-software-for-2024/"><u>Updated Best of Both Worlds Free and Paid 3D Video Creation Software for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-11-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-track-windows-10-and-11-note-hacks/"><u>Keeping Track: Windows 10 & 11 Note Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microphone-settings-in-w11-systems/"><u>Mastering Microphone Settings in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-modify-calculators-color-scheme-dark/"><u>How To Modify Calculator's Color Scheme (Dark)</u></a></li>
<li><a href="https://win11.techidaily.com/ethernet-efficiency-top-tips-to-test-your-networks-pace-on-windows/"><u>Ethernet Efficiency: Top Tips to Test Your Network's Pace on Windows</u></a></li>
</ul></div>
