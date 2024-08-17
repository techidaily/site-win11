---
title: Cutting Ties with Windows 11 Store
date: 2024-08-15T23:53:14.400Z
updated: 2024-08-16T23:53:14.400Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting Ties with Windows 11 Store
excerpt: This Article Describes Cutting Ties with Windows 11 Store
keywords: Forego Windows Shop,Ditch WinStore,Reject Microsoft Apps,Escape WinShop,Bypass Windows Updates,Liberate From WinOS,Break Free From Store
thumbnail: https://thmb.techidaily.com/bbf8b4ac709b45ef5944f09a459d244c293de523e01954b86b12ee5efc9e9834.jpg
---

## Cutting Ties with Windows 11 Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-boosting-channel-profitability-famebit-powered-sponsorship-tactics/"><u>[New] 2024 Approved  Boosting Channel Profitability  FameBit-Powered Sponsorship Tactics</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-fine-tuning-your-videos-for-viral-instagram-moments/"><u>[New] 2024 Approved  Fine-Tuning Your Videos for Viral Instagram Moments</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-seamless-strategies-to-record-and-archive-gotomeetings/"><u>[New] 2024 Approved  Seamless Strategies to Record and Archive GoToMeetings</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-viewer-recognition-the-play-button-reward-ribbon/"><u>[New] 2024 Approved  Viewer Recognition  The Play Button Reward Ribbon</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-behind-the-scenes-mastering-screen-recordings-in-games/"><u>[New] Behind the Scenes  Mastering Screen Recordings in Games</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-gain-massive-viewership-with-a-small-financial-investment/"><u>[New] Gain Massive Viewership with a Small Financial Investment</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-get-superior-visuals-from-youtube-downloading-thumbnails-free-for-2024/"><u>[New] Get Superior Visuals From YouTube - Downloading Thumbnails Free for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-flickr-profile-picture-breakdown-area-codec-timeframe/"><u>[New] In 2024, Flickr Profile Picture Breakdown  Area, Codec, Timeframe</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-skyrocket-your-brands-impact-top-ten-seo-tips-for-facebook-marketers/"><u>[New] In 2024, Skyrocket Your Brand's Impact  Top Ten SEO Tips for Facebook Marketers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-strategies-to-continue-live-video-on-facebook/"><u>[New] In 2024, Strategies to Continue Live Video on Facebook</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-time-lapse-android-tips-and-tricks/"><u>[New] Mastering Time-Lapse  Android Tips & Tricks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-full-inspection-gopro-silver-hero4-detailed-review/"><u>[Updated] 2024 Approved  Full Inspection  GoPro Silver Hero4 Detailed Review</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-effectively-reduce-your-youtube-video-lengths/"><u>[Updated] How To Effectively Reduce Your YouTube Video Lengths</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-go-live-on-instagram/"><u>[Updated] How to Go Live on Instagram</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-y28-5g-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo Y28 5G</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-content-creators-guide-to-thriving-in-a-digital-economy-on-vimeo/"><u>2024 Approved  Content Creators' Guide to Thriving in a Digital Economy on Vimeo</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-express-faster-window-photo-sorter/"><u>2024 Approved  Express Faster Window Photo Sorter</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-pristine-windows-display-perfection/"><u>Crafting Pristine Windows Display Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-heart-of-windows-11-registry-explained/"><u>Delving Into the Heart of Windows 11: Registry Explained</u></a></li>
<li><a href="https://win11.techidaily.com/digital-detox-for-pcs-a-collection-of-13-revival-methods/"><u>Digital Detox for PCs: A Collection of 13 Revival Methods</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-challenge-write-permissions-for-steam-folders/"><u>Easing the Challenge: Write Permissions for Steam Folders</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-linux-capabilities-through-windows-software/"><u>Elevating Linux Capabilities Through Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-false-negatives-restoring-accurate-game-status-in-discord-windows/"><u>Eliminating False Negatives: Restoring Accurate Game Status in Discord (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-package-registration-problems-on-windows-devices/"><u>Eliminating Package Registration Problems on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-trustworthiness-in-ai-does-chatgpt-speak-truthfully/"><u>Evaluating Trustworthiness in AI: Does ChatGPT Speak Truthfully?</u></a></li>
<li><a href="https://win11.techidaily.com/eye-catching-laptops-exhibited-at-ifa-2023/"><u>Eye-Catching Laptops Exhibited at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-self-triggered-command-prompt-issues/"><u>Fixing Self-Triggered Command Prompt Issues</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-country-on-app-store-for-iphone-x-with-7-methods-by-drfone-ios/"><u>How To Change Country on App Store for iPhone X With 7 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-non-recognized-ports-and-devices-on-windows-11/"><u>How to Fix Non-Recognized Ports and Devices on Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-xiaomi-redmi-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-unresponsive-mail-alerts-on-windows-11/"><u>How to Overcome Unresponsive Mail Alerts on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-put-multiple-pictures-on-insta-story-a-simple-guide-for-2024/"><u>How to Put Multiple Pictures on Insta Story - a Simple Guide for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-from-apple-iphone-14-pro-max-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons From Apple iPhone 14 Pro Max? Find the Best Solution Here</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-audiophiles-guide-to-superior-9-online-mic-tools/"><u>In 2024, Audiophile's Guide to Superior 9 Online Mic Tools</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-samsung-galaxy-a15-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Samsung Galaxy A15 5G Is Unlocked</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-learn-to-edit-films-youtube-tutorials-plus-others/"><u>In 2024, Learn to Edit Films  YouTube Tutorials + Others</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-snapedit-essentials-for-beginners-a-visual-journey/"><u>In 2024, Snapedit Essentials for Beginners  A Visual Journey</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-samsung-galaxy-z-fold-7-anticipated-features-launch-timeline-cost-estimates-and-latest-leaks/"><u>Inside Samsung Galaxy Z Fold 7: Anticipated Features, Launch Timeline, Cost Estimates & Latest Leaks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/meringue-movie-magic-step-by-step-guide-to-ice-cream-capture/"><u>Meringue Movie Magic  Step-by-Step Guide to Ice Cream Capture</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/navigating-animated-ads-to-skyrocket-facebook-roi/"><u>Navigating Animated Ads to Skyrocket Facebook ROI</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-seamless-program-deployment/"><u>Navigating Windows 11'S Seamless Program Deployment</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-booting-procedures-complete-guide/"><u>Navigating Windows' Booting Procedures Complete Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-ultimate-primer-on-the-wave-editor-pivotal-components-audit-reports-and-tutorials/"><u>New In 2024, The Ultimate Primer on the Wave Editor Pivotal Components, Audit Reports, and Tutorials</u></a></li>
<li><a href="https://hardware-help.techidaily.com/newly-updated-nvidia-geforce-ve-gpu-drivers-for-enhanced-performance-on-windows-11/"><u>Newly Updated Nvidia GeForce Ve GPU Drivers for Enhanced Performance on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/opera-on-windows-thwarting-the-downloading-dilemma/"><u>Opera on Windows: Thwarting the Downloading Dilemma</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-memory-and-cpu-for-streamers-on-w11/"><u>Optimizing Memory & CPU for Streamers on W11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-camera-app-error-0xa00f425d-in-windows-11/"><u>Overcoming Camera App Error 0xA00F425D in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-get-assistance-problems/"><u>Overcoming Windows 11 'Get Assistance' Problems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-error-nvidia-geforce-x0001/"><u>Overcoming Windows 11 Error: Nvidia GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1110-app-installation-obstacles-in-oculus/"><u>Overcoming Windows 11/10 App Installation Obstacles in Oculus</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-local-devices-avoid-in-use-names-errors/"><u>Overcoming Windows' Local Devices: Avoid In-Use Names Errors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photography-and-captioning-a-guide-to-dynamic-text/"><u>Photography & Captioning  A Guide to Dynamic Text</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unbidden-command-window-activations/"><u>Preventing Unbidden Command Window Activations</u></a></li>
<li><a href="https://win11.techidaily.com/quantify-windows-computer-power-usage-for-optimization/"><u>Quantify Windows Computer Power Usage for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-speaker-recognition-errors/"><u>Rectifying Windows Speaker Recognition Errors</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/security-straightforward-quick-ways-to-suspend-user-accounts-in-win11/"><u>Security Straightforward: Quick Ways to Suspend User Accounts in Win11</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723007714139-skip-the-struggle-speed-up-shader-optimization-for-a-better-run-of-battlefront-ii/"><u>Skip the Struggle: Speed Up Shader Optimization for a Better Run of Battlefront II!</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-into-speed-creating-collage-posts-in-a-flash-for-2024/"><u>Step Into Speed  Creating Collage Posts in a Flash for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-mastering-file-deletion-using-the-windows-11-command-prompt/"><u>Step-by-Step Guide: Mastering File Deletion Using the Windows 11 Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-of-an-era-microsofts-abandonment-of-windows-7-and-81/"><u>The End of an Era: Microsoft's Abandonment of Windows 7 and 8.1</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-way-to-self-empty-the-recycle-bin-on-windows/"><u>The Simple Way to Self-Empty the Recycle Bin on Windows</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-6-essential-ios-applications-for-effortlessly-retrieving-lost-iphone-contact-details/"><u>Top 6 Essential iOS Applications for Effortlessly Retrieving Lost iPhone Contact Details</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-steam-disconnect-in-windows-os/"><u>Troubleshoot Steam Disconnect in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-your-pcs-usb-troubleshooting-guide-for-windows-users/"><u>Unblock Your PC's USB: Troubleshooting Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-a-stuck-windows-11-settings-bar-the-search-solution/"><u>Unclogging a Stuck Windows 11 Settings Bar - The Search Solution</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-discover-the-leading-online-havens-for-free-premium-hd-video-backdrops-for-2024/"><u>Updated Discover the Leading Online Havens for Free, Premium HD Video Backdrops for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-icon-recovery-step-by-step-guide/"><u>Windows 11 Icon Recovery: Step-by-Step Guide</u></a></li>
</ul></div>
