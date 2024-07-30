---
title: Bypassing 'Service Failed' Errors on Disk Management
date: 2024-07-29T15:55:12.257Z
updated: 2024-07-30T15:55:12.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing 'Service Failed' Errors on Disk Management
excerpt: This Article Describes Bypassing 'Service Failed' Errors on Disk Management
keywords: Disable Service Fails,Disk Error Bypass,Fix Service Fail,Manage Disk No Error,Override Service Fail,Remove Disk Errors,Eliminate System Break,Service Fail Resolve,Disk Error Fixing,No-Error Management,Bypass System Fails,Avoiding Disk Disruption,Stop Service Interruptions,Remove System Crashes
thumbnail: https://thmb.techidaily.com/a08727f11a7832f787474e1a64a135e87ab43cd2d3040a1084f509333c65c397.jpg
---

## Bypassing 'Service Failed' Errors on Disk Management

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
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
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/frolic-fables-a-vhs-review-of-the-comical-epic/"><u>'Frolic Fables' - A VHS Review of The Comical Epic</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-finding-non-inshot-video-software-for-pcs/"><u>[New] Finding Non-Inshot Video Software for PCs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-easily-record-lenovo-laptop-screen-activity/"><u>[Updated] Easily Record Lenovo Laptop Screen Activity</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-efficient-viewing-strategies-for-instagram-content/"><u>[Updated] Efficient Viewing Strategies for Instagram Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-ordinary-to-outstanding-mastering-instagram-editing-skills-for-2024/"><u>[Updated] From Ordinary to Outstanding  Mastering Instagram Editing Skills for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/10-premium-text-tricks-for-videos/"><u>10 Premium Text Tricks for Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-haul-vids-creation-and-editing-basics/"><u>2024 Approved  Mastering Haul Vids  Creation & Editing Basics</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-tips-for-crafting-an-engaging-fb-timeline-memory/"><u>2024 Approved  Tips for Crafting an Engaging FB Timeline Memory</u></a></li>
<li><a href="https://win11.techidaily.com/9-pros-of-modernizing-to-windows-revamped-outlook/"><u>9 Pros of Modernizing to Windows' Revamped Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-calculator-on-windows-11-effortlessly/"><u>Accessing the Calculator on Windows 11 Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-out-of-space-issue-in-windows-oses/"><u>Addressing Out-of-Space Issue in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-package-malfunctions-in-windows-updates/"><u>Addressing Package Malfunctions in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-install-net-application-complaint/"><u>Addressing the Install .NET Application Complaint</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-failed-logon-wait-duration-settings/"><u>Adjusting Failed Logon Wait Duration Settings</u></a></li>
<li><a href="https://win11.techidaily.com/adopt-wsl-the-easy-way-to-run-linux-commands/"><u>Adopt WSL: The Easy Way to Run Linux Commands</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-for-windowsapps-acquisition/"><u>Advanced Methods for WindowsApps Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/altering-account-access-in-windows-11-easily/"><u>Altering Account Access in Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-creativity-best-writing-software-for-windows/"><u>Amplify Creativity: Best Writing Software For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/are-some-of-your-keyboard-keys-not-working-heres-how-to-fix-them-on-windows/"><u>Are Some of Your Keyboard Keys Not Working? Here's How to Fix Them on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-wait-winning-strategies-to-fasten-upstart-in-win11/"><u>Beat The Wait: Winning Strategies to Fasten Upstart in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/big-hard-drive-in-minipcs-but-below-average-brawn/"><u>Big Hard Drive in Minipcs, But Below Average Brawn</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-app-opening-top-techniques-for-windows-11/"><u>Boosted App Opening: Top Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-app-aesthetics-with-win11s-automatic-tuning/"><u>Boosting App Aesthetics with Win11's Automatic Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-directx-titles-with-dxvk-on-windows/"><u>Boosting Classic DirectX Titles with DXVK on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-memory-usage-in-windows-without-complications/"><u>Boosting Memory Usage in Windows Without Complications</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-utility-of-windows-11s-initial-interface/"><u>Boosting the Utility of Windows 11'S Initial Interface</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-samsung-galaxy-f04-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortlessly-enhance-your-systems-graphics-speed-upgrade-intel-drivers-in-windows/"><u>Effortlessly Enhance Your System's Graphics Speed, Upgrade Intel Drivers in WIndows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/essential-guide-to-enhancing-video-content-on-instagram/"><u>Essential Guide to Enhancing Video Content on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/1719209276170-essential-windows-store-top-10-crucial-apps/"><u>Essential Windows Store: Top 10 Crucial Apps!</u></a></li>
<li><a href="https://extra-hints.techidaily.com/exclude-automatic-recommended-podcasts-in-spotify-feed/"><u>Exclude Automatic Recommended Podcasts in Spotify Feed</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-htc-u23-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For HTC U23? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-samsung-galaxy-m34-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Samsung Galaxy M34 Activity | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-downloading-fb-video-files-in-a-flash-as-mp4/"><u>In 2024, Downloading FB Video Files in a Flash as MP4</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-apple-iphone-15-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-smart-8-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Infinix Smart 8 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leading-funny-image-editor-hub/"><u>In 2024, Leading Funny Image Editor Hub</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719356384376-mastery-over-mute-shift-key-trouble/"><u>Mastery Over Mute Shift Key Trouble</u></a></li>
<li><a href="https://extra-information.techidaily.com/revolutionize-your-gameplay-with-this-gratuitous-voice-alterer/"><u>Revolutionize Your Gameplay with This Gratuitous Voice Alterer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tips-for-skewing-photo-captions/"><u>Tips for Skewing Photo Captions</u></a></li>
<li><a href="https://win11.techidaily.com/1719245846865-windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>