---
title: Three Methods for Exploring Windows Policy Settings
date: 2024-08-16T00:30:50.811Z
updated: 2024-08-17T00:30:50.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Methods for Exploring Windows Policy Settings
excerpt: This Article Describes Three Methods for Exploring Windows Policy Settings
keywords: Windows Policy Control,Policy Settings Insight,Enhancing Windows Policies,Modify Windows Policy,Windows Security Settings,Policy Setting Navigation,Accessing Policy Configurations
thumbnail: https://thmb.techidaily.com/468b7a50fb837089e10cec38dd44fa01aaab4078b704b313fd2f69558ac117bb.png
---

## Three Methods for Exploring Windows Policy Settings

 The Local Group Policy is a tool that allows you to easily manage a wide range of system settings, from the appearance of the desktop to the security of the operating system. At times, you may need to review the policies applied to your Windows computer, either for troubleshooting purposes or to ensure that your system is configured correctly.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.

## 1\. How to View Applied Group Policies Using the Sort or Filter Options in Local Group Policy Editor

 The Local Group Policy Editor on Windows allows you to organize policies by their current state, so you can quickly see which ones are enabled or disabled.

 Use one of the [many ways to open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your PC. Then, use the left pane to head to **Computer Configuration > Administrative Templates > All Settings**. On your right, you will see a list of policies. Click the **State** column to sort policies based on their current status.

![Sort Group Policies on Windows by Their State](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sort-group-policies-on-windows-by-their-state.jpg)

 Once the Group Policy Editor sorts all the policies, you can review or modify them as you see fit.

 Another way to see applied policies based on specific criteria is to use the filter option in the Local Group Policy Editor. This can be useful if you want to see all the applied policies in a particular area or folder.

 Simply right-click on a folder in the Local Group Policy Editor and select **Filter Options**. In the following window, select **Yes** in the **Configured** drop-down menu and click **OK**. After that, the Group Policy Editor will only show the folders and policies you have applied.

![Filter Group Policies on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/filter-group-policies-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to View Applied Group Policies With PowerShell

 Another method for determining which policies are applied to a Windows user or computer involves using PowerShell. If you are someone who prefers using command-line tools to interact or make changes to your computer, this method can come in handy.

 To view applied group policies using PowerShell, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the PowerShell window and press **Enter**:  
`gpresult /Scope User /v`  
![See Applied Policies for a User on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/see-applied-policies-for-a-user-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## Checking the Applied Group Policies on Windows Is Easy

 Knowing how to check the policies applied to your Windows computer can be useful when troubleshooting issues with a program or feature, or when you have concerns about your privacy or security. Fortunately, doing so is a breeze with the methods mentioned above.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-stand-out-in-the-stream-top-name-generators-reviewed/"><u>[New] 2024 Approved  Stand Out in the Stream  Top Name Generators Reviewed</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastering-live-game-replays-with-fraps-for-2024/"><u>[New] Mastering Live Game Replays with Fraps for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-sharpen-your-streams-top-5-video-enhancers/"><u>[New] Sharpen Your Streams  Top 5 Video Enhancers</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-transforming-raw-audio-into-high-quality-youtube-videos/"><u>[Updated] In 2024, Transforming Raw Audio Into High-Quality YouTube Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-artisans-approach-integrating-typefaces-in-ae/"><u>[Updated] The Artisan's Approach  Integrating Typefaces in AE</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-top-tier-free-screen-capture-programs-2023-edition/"><u>[Updated] Top-Tier Free Screen Capture Programs – 2023 Edition</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-visual-excellence-pro-tips-for-snapchat-zoom/"><u>[Updated] Visual Excellence  Pro Tips for Snapchat Zoom</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flawless-photography-with-picarts-background-erasure-tricks/"><u>2024 Approved  Flawless Photography with PicArt’s Background Erasure Tricks</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-kinemaster-tools-for-cohesive-narrative-flow/"><u>2024 Approved  Kinemaster Tools for Cohesive Narrative Flow</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-next-gen-online-meeting-apps-azoom-no-more/"><u>2024 Approved  Next-Gen Online Meeting Apps  Azoom No More</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-snappy-and-straightforward-win11-screening/"><u>2024 Approved  Snappy & Straightforward Win11 Screening</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-samsung-galaxy-s23-fe-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-search-failures-immediately/"><u>Addressing Windows 11 Search Failures Immediately</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/advance-repair-for-bad-and-corrupt-video-files-of-vivo-s17-by-stellar-video-repair-mobile-video-repair/"><u>Advance Repair for Bad and Corrupt Video Files of Vivo S17</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-charts-with-a-click-youtube-short-tunes-made-easy/"><u>Crafting Charts with a Click  YouTube Short Tunes Made Easy</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-why-chatgpt-skyrockets-to-global-audience-favorite-in-minutes/"><u>Discover Why ChatGPT Skyrockets to Global Audience Favorite in Minutes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-file-lifecycle-in-windows-11-set-up-autodelete-protocols/"><u>Efficient File Lifecycle in Windows 11: Set Up Autodelete Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-windows-temp-file-deletion-guide/"><u>Effortless Windows Temp File Deletion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-creativity-discovering-the-latest-in-microsoft-paint/"><u>Elevate Creativity: Discovering the Latest in Microsoft Paint</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embracing-germanys-linguistic-culture-top-25-phrases/"><u>Embracing Germany's Linguistic Culture: Top 25 Phrases</u></a></li>
<li><a href="https://fox-that.techidaily.com/fix-fast-solving-the-issue-of-non-responsive-predictive-emojis-on-iphoneipad/"><u>Fix Fast: Solving the Issue of Non-Responsive Predictive Emojis on iPhone/iPad</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/fortnite-access-denied-heres-how-you-can-regain-entry-successfully/"><u>Fortnite Access Denied? Here’s How You Can Regain Entry Successfully</u></a></li>
<li><a href="https://technical-tips.techidaily.com/from-drab-to-fab-the-ultimate-guide-to-modifying-windows-11-taskbar-colors/"><u>From Drab to Fab: The Ultimate Guide to Modifying Windows 11 Taskbar Colors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-samsung-galaxy-xcover-7-frp-by-drfone-android/"><u>Full Guide to Bypass Samsung Galaxy XCover 7 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-vivo-x100-pro-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-amplify-your-photography-with-these-top-notch-pixlr-tricks/"><u>In 2024, Amplify Your Photography with These Top-Notch Pixlr Tricks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-capturing-the-moment-masterful-techniques-for-excellent-edits/"><u>In 2024, Capturing the Moment  Masterful Techniques for Excellent Edits</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-vivo-s17e-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Vivo S17e Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-itel-p55-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Itel P55? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-seamless-sharing-of-oversized-content-from-iphone-to-macos/"><u>In 2024, Seamless Sharing of Oversized Content From iPhone to macOS</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/insta-cinematography-tips-three-way-borders/"><u>Insta Cinematography Tips  Three-Way Borders</u></a></li>
<li><a href="https://win11.techidaily.com/instant-spooler-restart-methods-for-windows/"><u>Instant Spooler Restart Methods for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-advanced-tools-for-improved-admin-workflows-in-windows/"><u>Leveraging Advanced Tools for Improved Admin Workflows in Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/make-stunning-videos-in-minutes-wevideo-for-2024/"><u>Make Stunning Videos in Minutes WeVideo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wsreset-troubleshooting-in-windows-environments/"><u>Mastering WSReset Troubleshooting in Windows Environments</u></a></li>
<li><a href="https://fox-that.techidaily.com/navigating-common-iphone-13-difficulties-fixing-top-6-problems/"><u>Navigating Common iPhone 13 Difficulties – Fixing Top 6 Problems</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-stabilize-windows-configuration-app/"><u>Quick Fixes to Stabilize Windows Configuration App</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-rectifying-epic-games-logins/"><u>Quick Guide to Rectifying Epic Games Logins</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-handling-the-lack-of-msvcr120dll-in-windows/"><u>Quick Tips for Handling the Lack of MSVCR120.DLL in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-g2-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo G2 Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-icon-placement/"><u>Regaining Control Over Icon Placement</u></a></li>
<li><a href="https://win11.techidaily.com/remove-hyper-v-from-windows-11-setup/"><u>Remove Hyper-V From Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/removing-hitchhiking-devices-win-1011-printer-uninstallation/"><u>Removing Hitchhiking Devices: Win 10/11 Printer Uninstallation</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-update-experience-with-easy-fixes-here/"><u>Seamless Windows Update Experience With Easy Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-pin-verification-errors-on-w11w10-systems/"><u>Solutions for Fixing PIN Verification Errors on W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-task-juggling-skills-a-guide-to-mastering-windows-11-multitasking/"><u>Step Up Your Task Juggling Skills: A Guide to Mastering Windows 11 Multitasking</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-end-task-feature-in-windows-11-ui/"><u>Steps to Turn On End Task Feature in Windows 11 UI</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/stop-the-crash-comprehensive-steps-to-fix-the-blue-screen-with-stop-code-0x00000124-in-windows-os/"><u>Stop the Crash: Comprehensive Steps to Fix the Blue Screen with Stop Code 0X00000124 in Windows OS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-comprehensive-dictionary-for-ai-enthusiasts-grasping-29-vital-terminologies/"><u>The Comprehensive Dictionary for AI Enthusiasts: Grasping 29 Vital Terminologies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-cortana-commands-in-windows-11/"><u>Troubleshooting Non-Functional Cortana Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-computing-experience-best-windows-devices-2024/"><u>Ultimate Computing Experience - Best Windows Devices 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-silencing-windows-11-operations/"><u>Ultimate Guide: Silencing Windows 11 Operations</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-rdp-connection-issues-in-modern-oses/"><u>Unblocking RDP Connection Issues in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-cab-files-explanations-and-steps-for-installation/"><u>Understanding Windows Cab Files: Explanations & Steps for Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-mysteries-a-guide-to-finding-and-fixing-error-messages-using-commands/"><u>Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-app-migration-from-older-windows-versions/"><u>Unveiling the Art of App Migration From Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-missing-tab-button-on-your-machine/"><u>Unveiling the Missing Tab Button on Your Machine</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo S17 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-volume-adjustment-reviving-dull-edges/"><u>Win Volume Adjustment: Reviving Dull Edges</u></a></li>
</ul></div>
