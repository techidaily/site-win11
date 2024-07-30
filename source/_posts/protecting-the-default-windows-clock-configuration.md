---
title: Protecting the Default Windows Clock Configuration
date: 2024-07-29T15:45:35.462Z
updated: 2024-07-30T15:45:35.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Protecting the Default Windows Clock Configuration
excerpt: This Article Describes Protecting the Default Windows Clock Configuration
keywords: Win Clock Security,Safe Time Settings,Default Time Protection,OS Clock Safeguard,Preventing Time Changes,Secure Windows Time,Preserve Windows Hours
thumbnail: https://thmb.techidaily.com/48b583faa31b393aa904516c2278bd0e1546bcda1fa4122648e108e1ee1f91de.jpg
---

## Protecting the Default Windows Clock Configuration

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-cut-expenses-create-wow-download-high-quality-templates-for-videos/"><u>[New] 2024 Approved  Cut Expenses, Create Wow - Download High-Quality Templates for Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-channel-prodigy-skyrocketing-with-content-innovation/"><u>[New] Channel Prodigy  Skyrocketing with Content Innovation</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-experience-the-old-school-games-anywhere-with-best-in-class-pc-gb-emulators/"><u>[New] In 2024, Experience the Old School Games Anywhere with Best-in-Class PC GB Emulators</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-iphone-screen-sharing-made-simple-for-2024/"><u>[New] IPhone Screen Sharing Made Simple for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-step-by-step-guide-to-revamping-youtube-inspired-thumbnails-on-twitter-for-2024/"><u>[New] Step-by-Step Guide to Revamping YouTube-Inspired Thumbnails on Twitter for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-snapshot-sentence-maker/"><u>[Updated] 2024 Approved  Snapshot Sentence Maker</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-effortless-webcam-recordings-on-hp-systems-for-2024/"><u>[Updated] Effortless Webcam Recordings on HP Systems for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-excellence-in-social-media-video-playback-tools-2023-edition-for-2024/"><u>[Updated] Excellence in Social Media Video Playback Tools, 2023 Edition for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-learning-the-art-of-softly-amplifying-audio-tracks/"><u>[Updated] Learning the Art of Softly Amplifying Audio Tracks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-quick-start-to-clear-background-filming/"><u>[Updated] Quick Start to Clear Background Filming</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-smooth-art-of-mov-saving-a-win10-insight-for-2024/"><u>[Updated] The Smooth Art of MOV Saving  A Win10 Insight for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-roadmap-to-unearth-gorgeous-pexel-pictures/"><u>[Updated] The Ultimate Roadmap to Unearth Gorgeous Pexel Pictures</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-master-9-fixes-for-youtube-buffering-woes/"><u>2024 Approved  Master 9 Fixes for YouTube Buffering Woes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/ad-profits-unveiled-how-much-do-creators-make-on-youtube-for-2024/"><u>Ad Profits Unveiled  How Much Do Creators Make on Youtube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-and-resolve-windows-error-code-0xc00000f-quickly/"><u>Avoid and Resolve Windows Error Code: 0Xc00000f Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-uninstalling-apps-on-windows-11/"><u>Efficiently Uninstalling Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-soundscape-windows-11-spatial-tips/"><u>Elevate Your Soundscape: Windows 11 Spatial Tips</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-list-of-windows-most-reliable-usage-monitors/"><u>Exclusive List of Windows' Most Reliable Usage Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-the-feel-personalizing-touchpad-settings-in-windows-11/"><u>Fine-Tune the Feel: Personalizing Touchpad Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/harnessing-altitude-live-streaming-with-dji-drones/"><u>Harnessing Altitude  Live-Streaming with DJI Drones</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-asus-rog-phone-8-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Asus ROG Phone 8 FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-gain-entry-windowsstore-apps-explorer/"><u>How To Gain Entry: WindowsStore Apps Explorer</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-xiaomi-13t-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Xiaomi 13T.</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-honor-magic-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6s-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6s To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-13t-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi 13T Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-a-comprehensive-guide-to-monetize-your-facebook-page-tips-and-tricks/"><u>In 2024, A Comprehensive Guide to Monetize Your Facebook Page  Tips and Tricks</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-devhome-navigating-windows-11-with-ease/"><u>Introducing DevHome: Navigating Windows 11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-microsoft-store-sign-in-blocks/"><u>Navigate Through Microsoft Store Sign-In Blocks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-free-mkv-video-editing-software-top-cutting-tools/"><u>New 2024 Approved Free MKV Video Editing Software Top Cutting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/old-wallpapers-no-more-discover-three-solutions/"><u>Old Wallpapers No More! Discover Three Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-windows-event-logger/"><u>Overcoming Errors with Windows Event Logger</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-task-manager-unresponsiveness/"><u>Overcoming Windows Task Manager Unresponsiveness</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://win11.techidaily.com/procedure-opening-driver-verifier-for-fault-analysis/"><u>Procedure: Opening Driver Verifier for Fault Analysis</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-oppo-f25-pro-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Oppo F25 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inability-to-install-windows-store-apps/"><u>Resolving Inability to Install Windows Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/revel-in-rich-software-diversity-on-windows/"><u>Revel in Rich Software Diversity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-data-update-windows-11-user-passwords/"><u>Safeguarding Data: Update Windows 11 User Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-photoshop-wont-launch-in-windows-1011/"><u>Troubleshooting PhotoShop Won't Launch in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-username-modification-in-windows-11/"><u>Unlocking the Secrets of UserName Modification in Windows 11</u></a></li>
</ul></div>
