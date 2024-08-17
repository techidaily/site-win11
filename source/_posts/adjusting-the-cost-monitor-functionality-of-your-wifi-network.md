---
title: Adjusting the Cost Monitor Functionality of Your Wifi Network
date: 2024-08-15T23:14:20.055Z
updated: 2024-08-16T23:14:20.055Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting the Cost Monitor Functionality of Your Wifi Network
excerpt: This Article Describes Adjusting the Cost Monitor Functionality of Your Wifi Network
keywords: WiFi Cost Control,Wifi Expense Management,Wireless Bill Adjustment,Network Usage Pricing,Optimize Wi-Fi Bills,Reduce Wifi Expenses,Manage Wifi Costs
thumbnail: https://thmb.techidaily.com/78f06b81f7c57e1e88ac6a7fa4601f5ae07cf7d31be3889aa12b125cc68b1e89.jpg
---

## Adjusting the Cost Monitor Functionality of Your Wifi Network

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-eliminate-camera-sway-no-tripods-allowed/"><u>[New] 2024 Approved  Eliminate Camera Sway  No Tripods, Allowed</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-step-by-step-turn-your-images-darker/"><u>[New] 2024 Approved  Step-by-Step  Turn Your Images Darker</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-time-travelers-guide-to-youtube-queue-watch-from-end-to-start/"><u>[New] A Time Traveler’s Guide to YouTube Queue  Watch From End to Start</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/est-cameras-for-quality-youtube-content-for-2024/"><u>[New] Best Cameras for Quality YouTube Content for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tiktok-triumphs-in-twitter-land-toptiktoks-revealed-for-2024/"><u>[New] TikTok Triumphs in Twitter Land  #TopTikToks Revealed for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-soundsnatcher-free-guide-and-assessment/"><u>[Updated] In 2024, SoundSnatcher Free Guide & Assessment</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-art-of-youtube-editing-a-compreenasive-guidebook/"><u>[Updated] The Art of YouTube Editing  A Compreenasive Guidebook</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-treat-tracks-review-exhaustive-guide-on-frozen-food-filming-for-2024/"><u>[Updated] Treat Tracks Review  Exhaustive Guide on Frozen Food Filming for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-ultimate-tiktok-to-mp4-recorder/"><u>2024 Approved  Ultimate TikTok to MP4 Recorder</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/affordable-excellence-on-wheels-a-closer-look-at-the-intuitive-z-edge-z3-plus-cameras/"><u>Affordable Excellence on Wheels: A Closer Look at the Intuitive Z-Edge Z3 Plus Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-steam-cloud-discrepancies-in-windows/"><u>Correcting Steam Cloud Discrepancies in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/data-resilience-on-windows-embrace-daily-savings/"><u>Data Resilience on Windows: Embrace Daily Savings</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-cpu-temperatures-on-windows-11-machines/"><u>Decreasing CPU Temperatures on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-and-repairing-win-error-31-on-your-computer/"><u>Dissecting and Repairing WIN Error 31 on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-directx-on-your-system/"><u>Efficiently Managing DirectX on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-driving-experience-the-most-effective-5-free-tools-for-pcs/"><u>Enhance Driving Experience: The Most Effective 5 Free Tools for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-system-files-top-6-access-methods/"><u>Exploring System Files: Top 6 Access Methods</u></a></li>
<li><a href="https://win11.techidaily.com/fourfold-path-to-permanently-delete-a-disk-partition-on-windows/"><u>Fourfold Path to Permanently Delete a Disk Partition on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-advanced-strategies-for-recording-and-saving-gameplay-on-ps4/"><u>In 2024, Advanced Strategies for Recording and Saving Gameplay on PS4</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harnessing-the-power-of-auto-transcribe-for-enhanced-office-productivity-in-ms-word/"><u>In 2024, Harnessing the Power of Auto-Transcribe for Enhanced Office Productivity in MS Word</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-vivo-t2-5g-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Vivo T2 5G FRP</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-package-management-in-windows-11/"><u>Leveraging the Power of Package Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-application-floods-on-windows-solving-error-0x80860010/"><u>Navigating Application Floods on Windows: Solving Error 0X80860010</u></a></li>
<li><a href="https://win11.techidaily.com/old-techs-new-lease-on-life-the-art-of-employing-windows-11-to-go-and-rufus/"><u>Old Tech's New Lease on Life: The Art of Employing Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-absent-cpu-cooling-directive-in-os/"><u>Reinstating Absent CPU Cooling Directive in OS</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-unresponsive-disk-optimization-utility/"><u>Solutions for Unresponsive Disk Optimization Utility</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-discord-javascript-dilemma-on-windows-11-pcs/"><u>Steps to Eliminate Discord Javascript Dilemma on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-file-disconnect-issue-in-windows-settings/"><u>Tackling Steam File Disconnect Issue in Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/the-gamers-manual-to-prevent-data-loss-with-epic-backup/"><u>The Gamer's Manual to Prevent Data Loss with Epic Backup</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-11-compatible-android-apps-worth-your-time/"><u>Top 6 Windows 11 Compatible Android Apps Worth Your Time</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-ancient-directx-software-using-modern-dxvk-techniques/"><u>Transforming Ancient DirectX Software Using Modern DXVK Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-vivo-x100-pro-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Vivo X100 Pro Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-wanted-learn-backup-tricks-for-notebooks/"><u>Windows Users Wanted: Learn Backup Tricks for Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-error-code-31-your-guide-to-restoring-online-access/"><u>Winning Over Error Code 31: Your Guide to Restoring Online Access</u></a></li>
</ul></div>
