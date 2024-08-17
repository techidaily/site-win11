---
title: Navigating to Silent Tab Disabling in Windows 11
date: 2024-08-15T23:41:04.130Z
updated: 2024-08-16T23:41:04.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Silent Tab Disabling in Windows 11
excerpt: This Article Describes Navigating to Silent Tab Disabling in Windows 11
keywords: Windows 11 Tabs Mute,Tab Silence Mode,11 PC Quiet Switch,Windows 11 No Sound Tabs,Disable Tabs Sound,Windows 11 Silent Tabs,Mute Windows 11 Apps
thumbnail: https://thmb.techidaily.com/5e4f2e08bc06e83ddb45587d928cf61d9245bd50e484b6c6cc6059c7ac856aae.jpg
---

## Navigating to Silent Tab Disabling in Windows 11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-how-to-sprinkle-new-colors-into-your-past-media-with-instagram/"><u>[New] 2024 Approved  How to Sprinkle New Colors Into Your Past Media with Instagram</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-science-spheres-finest-15-youtube-picks/"><u>[New] 2024 Approved  Science Sphere's Finest 15 YouTube Picks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-design-best-practices-for-engaging-youtube-thumbnails-for-2024/"><u>[New] Design Best Practices for Engaging YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-noir-nights-transitioning-with-pro-for-2024/"><u>[New] Noir Nights - Transitioning with Pro for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-obs-and-streamlabs-showdown-best-livestream-tool-compared/"><u>[New] OBS and Streamlabs Showdown – Best Livestream Tool Compared</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-accessing-your-twitter-history-for-2024/"><u>[Updated] Accessing Your Twitter History for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-convenient-methods-for-macbook-pros-video-recording-for-2024/"><u>[Updated] Convenient Methods for MacBook Pro's Video Recording for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-find-youtube-sponsorships-by-using-famebit/"><u>[Updated] How to Find YouTube Sponsorships by Using FameBit</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-ultimate-mobile-and-desktop-sound-pace-alteration-compendium/"><u>[Updated] In 2024, Ultimate Mobile & Desktop Sound Pace Alteration Compendium</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streamline-your-yt-content-with-background-softening-tricks/"><u>[Updated] Streamline Your YT Content with Background Softening Tricks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2023-how-to-autoplay-facebook-videos/"><u>2023 | How to Autoplay Facebook Videos?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-the-secrets-of-profitability-in-youtube-shorts/"><u>2024 Approved  Unlocking the Secrets of Profitability in YouTube Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/ace-file-moves-with-advanced-auto-transfer-techniques-on-win-11/"><u>Ace File Moves with Advanced Auto-Transfer Techniques on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/become-an-instagram-broadcast-pro-learning-through-obs/"><u>Become an Instagram Broadcast Pro  Learning Through OBS</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/chronology-clash-wintime-harmony-guide/"><u>Chronology Clash? WinTime Harmony Guide</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-google-pixel-7a-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Google Pixel 7a Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-revamped-widget-picker-in-win11/"><u>Configuring Revamped Widget Picker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-solid-state-drive-speed-on-windows-via-ssd-fresh/"><u>Elevate Solid State Drive Speed on Windows via SSD Fresh</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-hello-login-fingerprint-failure/"><u>Eliminating Windows Hello Login Fingerprint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ensuring-every-detail-is-visible-during-google-meets/"><u>Ensuring Every Detail Is Visible During Google Meets</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-microcomputers-reviewed/"><u>Essential Windows Microcomputers Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-past-security-checks-on-your-wins-system/"><u>How to Clear Past Security Checks on Your Wins System</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-of-apple-iphone-8-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-accelerate-your-adrenaline-the-ultimate-5-racing-game-list/"><u>In 2024, Accelerate Your Adrenaline  The Ultimate 5 Racing Game List</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Xiaomi Redmi Note 13 Pro 5G?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-oppo-reno-11-pro-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Oppo Reno 11 Pro 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-itel-p55-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Itel P55 Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-a18-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo A18 to New Android? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/insta-chat-101-an-introduction-to-online-video-talks-for-2024/"><u>Insta Chat 101  An Introduction to Online Video Talks for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-video-preservation-straightforward-techniques-unpacked/"><u>Instagram Video Preservation  Straightforward Techniques Unpacked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/mastering-three-techniques-to-preserve-discord-live-streams-for-2024/"><u>Mastering Three Techniques to Preserve Discord Live Streams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-endless-scrolls-on-large-datasheets-windows/"><u>Overcome Endless Scrolls on Large Datasheets, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-charmap-incompatibility-challenges/"><u>Overcoming Windows CharMap Incompatibility Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-microsoft-store-crash-error-0x800704cf-in-windows/"><u>Quick Fix for Microsoft Store Crash: Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-access-denied-on-nvidia-panel/"><u>Quick-Fix Tips for Access Denied on NVIDIA Panel</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-windows-11-bsod-the-clock-watchdog-timout-dilemma/"><u>Resolving Windows 11 BSoD: The 'Clock Watchdog Timout' Dilemma</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/social-scrutiny-who-felt-the-glance-on-your-insta-image-in-2024/"><u>Social Scrutiny  Who Felt the Glance on Your Insta Image, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-savers-a-guide-to-win11/"><u>Tailoring Screen Savers: A Guide to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-producing-attention-grabbing-podcast-openers-for-2024/"><u>The Art of Producing Attention-Grabbing Podcast Openers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-oneplus-ace-2v-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 OnePlus Ace 2V Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-resolve-world-of-warcraft-slowdowns/"><u>Troubleshooting Steps to Resolve World of Warcraft Slowdowns</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/winfixer-rectifying-the-network-not-reachable-error-in-windows-11/"><u>Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11</u></a></li>
</ul></div>
