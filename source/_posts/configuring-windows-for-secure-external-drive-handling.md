---
title: Configuring Windows for Secure External Drive Handling
date: 2024-08-16T00:03:39.562Z
updated: 2024-08-17T00:03:39.562Z
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

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-premier-camera-drones-10-filmmakers-dream-fleet/"><u>[New] 2024 Approved  Premier Camera Drones #10  Filmmakers' Dream Fleet</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-ultimate-ranking-of-8-swift-recorders/"><u>[New] 2024 Approved  Ultimate Ranking of 8 Swift Recorders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-shades-insights-from-the-best-11-color-guides/"><u>[New] Exploring Shades  Insights From the Best 11 Color Guides</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-ajeys-youtube-profit-milestones/"><u>[New] In 2024, Ajey's YouTube Profit Milestones</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-live-broadcasting-on-fb-tips-for-success/"><u>[New] In 2024, Live Broadcasting on FB  Tips for Success</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-innovative-methods-to-archive-lol-dueling/"><u>[New] Innovative Methods to Archive LOL Dueling</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-of-the-rest-cutting-edge-vr-games-for-google-cardboard/"><u>[Updated] Best of the Rest  Cutting-Edge VR Games for Google Cardboard</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-hottest-twitters-the-viral-video-countdown-for-2024/"><u>[Updated] Hottest Twitters  The Viral Video Countdown for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-premier-high-definition-recording-discs/"><u>[Updated] In 2024, Premier High Definition Recording Discs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-selecting-peak-frame-rate-for-exceptional-slow-motion-video/"><u>[Updated] In 2024, Selecting Peak Frame Rate for Exceptional Slow Motion Video</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-itops-expert-selection-best-windows-screencasters/"><u>[Updated] ITop's Expert Selection  Best Windows Screencasters</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-mkv-player-for-pc-and-mobile/"><u>2024 Approved  Best Mkv Player for PC and Mobile</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-copyright-on-youtube-and-cc/"><u>2024 Approved  Navigating Copyright on YouTube & CC</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-oneplus-ace-3-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from OnePlus Ace 3 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-from-iphone-12-mini-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock From iPhone 12 mini Online</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-samsung-galaxy-f14-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-optimize-windows-powershell-script-policies/"><u>Activate and Optimize Windows PowerShell Script Policies</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-windows-lockscreen-for-user-preferences/"><u>Adapting Windows Lockscreen for User Preferences</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/beat-the-blues-fixing-football-manager-2021s-crashing-woes-on-your-desktop-computer/"><u>Beat the Blues: Fixing Football Manager 2021'S Crashing Woes on Your Desktop Computer</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-process-termination-errors-effortlessly/"><u>Bypassing Process Termination Errors Effortlessly</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/channel-marketing-making-a-trailer-that-sells-more-for-2024/"><u>Channel Marketing  Making a Trailer that Sells More for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unexpected-reference-to-token-in-win10win11/"><u>Correcting Unexpected Reference to Token in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-cloud-file-retrieval-methods/"><u>Cross-Platform Cloud File Retrieval Methods</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-canon-mx280-printer-drivers-compatible-with-windows-11-8-and-7/"><u>Download Canon MX280 Printer Drivers - Compatible with Windows 11, 8 & 7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-oppo-reno-10-5g-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Oppo Reno 10 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/1719347376759-efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7.</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://win11.techidaily.com/freezing-wi-fi-mouse-how-to-reset-and-restore-functionality-in-windows/"><u>Freezing Wi-Fi Mouse? How to Reset and Restore Functionality in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-tecno-spark-10-4g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Tecno Spark 10 4G to Roku | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-capturing-tiktok-videos-saving-on-modern-smartphones/"><u>In 2024, Capturing TikTok Videos  Saving on Modern Smartphones</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-a15-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy A15 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovating-with-numbers-tips-for-tiktok-video-enhancements/"><u>In 2024, Innovating with Numbers  Tips for TikTok Video Enhancements</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-locked-out-of-apple-iphone-12-pro-5-ways-to-get-into-a-locked-apple-iphone-12-pro-by-drfone-ios/"><u>In 2024, Locked Out of Apple iPhone 12 Pro? 5 Ways to get into a Locked Apple iPhone 12 Pro</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-art-of-search-engine-optimization-for-podcasts/"><u>In 2024, Mastering the Art of Search Engine Optimization for Podcasts</u></a></li>
<li><a href="https://win11.techidaily.com/in-a-nutshell-how-to-spot-your-pcs-ram-quickly/"><u>In a Nutshell: How to Spot Your PC's RAM Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/initial-guide-to-zoom-room-segregation-for-2024/"><u>Initial Guide to Zoom Room Segregation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users.</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-polishing-your-projects-soundtrack-effective-methods-for-removing-unwanted-audio-noise-in-videoworks-pro/"><u>New Polishing Your Projects Soundtrack Effective Methods for Removing Unwanted Audio Noise in VideoWorks Pro</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-devices-aesthetics-using-microsoft-store-themes/"><u>Optimizing Your Device's Aesthetics Using Microsoft Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-failure-codes/"><u>Overcoming Windows 10/11 Failure Codes</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pc-revival-unearthing-windows-best-eight-methods/"><u>Quick PC Revival: Unearthing Windows' Best Eight Methods</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise:</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-11-from-self-restarting-frequently/"><u>Stop Windows 11 From Self-Restarting Frequently</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-repeated-edge-desktop-additions/"><u>Stopping Repeated Edge Desktop Additions</u></a></li>
<li><a href="https://network-issues.techidaily.com/strategies-to-stop-lenovo-screenshaking/"><u>Strategies to Stop Lenovo Screenshaking</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-revive-windows-11s-essential-directories/"><u>Tailored Guide to Revive Windows 11'S Essential Directories</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-editors-toolkit-elevating-your-video-with-inshot-transitions-for-2024/"><u>The Editor's Toolkit  Elevating Your Video with Inshot Transitions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-for-fixing-failed-to-startup-battleye-service-with-error-1450/"><u>Troubleshooting Steps for Fixing 'Failed to Startup BattlEye Service' With Error 1450</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-chrome-profile-errors-for-windows-users/"><u>Unraveling Chrome Profile Errors for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-a-runtime-broker-unpacking-its-importance-for-pcs/"><u>What Is a Runtime Broker? Unpacking Its Importance for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
</ul></div>
