---
title: How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
date: 2024-08-15T23:39:59.284Z
updated: 2024-08-16T23:39:59.284Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
excerpt: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
keywords: Wi-Fi Metrics Tuning,Win11 Wifi Tracker Settings,Wi-Fi Performance Optimization,Windows Network Adjustments,Gain Wi-Fi Data Insights,Wi-Fi Metrics Control,Wifi Settings Enhancement
thumbnail: https://thmb.techidaily.com/8605278b5d648a8e727674b42f156215fdccc4c56056b931eaef077a91501e84.jpg
---

## How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11

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
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
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
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/new-how-to-effortlessly-connect-zoom-with-gmail/"><u>[New] How to Effortlessly Connect Zoom with Gmail</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-streamlined-approaches-to-documenting-whatsapp-discussions/"><u>[New] Streamlined Approaches to Documenting WhatsApp Discussions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-no-cost-android-facetime-replacements-ranked/"><u>[Updated] 2024 Approved  No-Cost Android FaceTime Replacements Ranked</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-learn-photoshops-core-techniques-for-shade-adjustment/"><u>[Updated] In 2024, Learn Photoshop's Core Techniques for Shade Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-clear-the-wallpaper-history-on-windows/"><u>3 Ways to Clear the Wallpaper History on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-ingenious-cmd-puzzles-to-perplex-and-pleasure/"><u>5 Ingenious CMD Puzzles to Perplex and Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-printer-administration-interface/"><u>A Comprehensive Look at Windows Printer Administration Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-and-upgrade-top-5-essentials-to-enhance-win-pcs/"><u>Accelerate and Upgrade: Top 5 Essentials to Enhance Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connectivity-issues-fix-iphone-images-not-uploading-in-windows/"><u>Addressing Connectivity Issues: Fix iPhone Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-dll-issue-in-windows-810/"><u>Addressing Missing DLL Issue in Windows 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-security-strategies-in-powertoys/"><u>Advanced File Security Strategies in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-tray-graphics-windows-resource-indicators-displayed/"><u>Amplify Tray Graphics: Windows Resource Indicators Displayed</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-black-screen-in-windows-quick-fix-guide/"><u>Banish Black Screen in Windows - Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-explore-4-innovative-microsoft-paint-additions/"><u>Breaking Boundaries: Explore 4 Innovative Microsoft Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-tips-to-prevent-and-fix-horizon-forbidden-west-ultimate-collectors-set-from-crashing-on-windows-pc/"><u>Expert Tips to Prevent and Fix 'Horizon Forbidden West Ultimate Collector's Set' From Crashing on Windows PC</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-zte-nubia-flip-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-maximizing-your-youtube-videos-viewer-count/"><u>In 2024, Maximizing Your YouTube Video's Viewer Count</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-streamlined-teaching-mastering-lecture-capture-on-mac-systems/"><u>In 2024, Streamlined Teaching  Mastering Lecture Capture on Mac Systems</u></a></li>
<li><a href="https://win11.techidaily.com/1719380925919-keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719254765561-solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-3-step-structure-for-successful-subscriber-profit-analysis-a-guide-from-google/"><u>The 3-Step Structure for Successful Subscriber Profit Analysis  A Guide From Google</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-zte-nubia-flip-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About ZTE Nubia Flip 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723009959364-troubleshoot-and-resolve-control-application-errors-swiftly-and-effectively/"><u>Troubleshoot & Resolve Control Application Errors Swiftly & Effectively</u></a></li>
</ul></div>
