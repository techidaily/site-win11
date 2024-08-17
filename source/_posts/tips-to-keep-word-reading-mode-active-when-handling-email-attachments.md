---
title: Tips to Keep Word Reading Mode Active When Handling Email Attachments
date: 2024-08-16T00:11:24.349Z
updated: 2024-08-17T00:11:24.349Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Keep Word Reading Mode Active When Handling Email Attachments
excerpt: This Article Describes Tips to Keep Word Reading Mode Active When Handling Email Attachments
keywords: Active Email Reading,Word Optimize View,Handling Attachments Tips,Maintain Readability,Email Alert Mode,Attachment Management,Enhance Word Display
thumbnail: https://thmb.techidaily.com/dbe86ec4eee57de28307f7a87e5d2dc26b222d4d704a45568094d723e05d6df4.jpg
---

## Tips to Keep Word Reading Mode Active When Handling Email Attachments

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-access-exclusive-video-artwork-free-flawless-and-fast-for-2024/"><u>[New] Access Exclusive Video Artwork – Free, Flawless, and Fast for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-beauty-vlogs-from-basics-to-brilliance-launching-a-youtube-channel/"><u>[Updated] In 2024, Beauty Vlogs From Basics to Brilliance  Launching a YouTube Channel</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-quick-start-5-simple-ways-to-document-your-minecraft-journey-on-a-mac/"><u>[Updated] In 2024, Quick Start  5 Simple Ways to Document Your Minecraft Journey on a Mac</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-instant-annotation-text-overlaying-on-images-and-videos-using-windows-photos/"><u>[Updated] Instant Annotation  Text Overlaying on Images & Videos Using Windows Photos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-exclusive-no-fee-fb-visual-content-craftsman/"><u>2024 Approved  Exclusive No-Fee FB Visual Content Craftsman</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-no-cost-premiere-pro-resource-pack/"><u>2024 Approved  Exclusive, No-Cost Premiere Pro Resource Pack</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-harmonic-hits-on-snapchat-videos/"><u>2024 Approved  Harmonic Hits on Snapchat Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-speedy-resizing-your-youtube-videos-for-mac-view/"><u>2024 Approved  Speedy Resizing  Your Youtube Videos for Mac View</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-tecno-pova-5-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Tecno Pova 5 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-zipping-with-command-prompt-step-by-step/"><u>Advanced Zipping with Command Prompt, Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-browser-speed-discrepancy-across-devices/"><u>Bridging Browser Speed Discrepancy Across Devices</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-nokia-c12-plus-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Nokia C12 Plus Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhance-your-xiaomi-experience-with-easy-record-screens/"><u>Enhance Your Xiaomi Experience with Easy Record Screens</u></a></li>
<li><a href="https://win11.techidaily.com/essential-methods-unlocking-computer-management-on-windows-11/"><u>Essential Methods: Unlocking Computer Management on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-on-capturing-windows-calls-effectively/"><u>Essential Tips on Capturing Windows Calls Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-lava-yuva-3-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Lava Yuva 3 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-xiaomi-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Xiaomi Unlock Without Password</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-xiaomi-14-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Xiaomi 14 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-asus-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Asus Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-instantaneous-duo-recording-cam-plus-screen/"><u>In 2024, Instantaneous Duo Recording  Cam + Screen</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-11-pro-max-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-explorer-filters-as-an-alternative-to-ls/"><u>Mastery of Windows Explorer Filters as an Alternative to LS</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-surface-studio-2-almost-perfect-creators-choice/"><u>Microsoft Surface Studio 2 - Almost Perfect Creator's Choice</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-public-ip-using-windows-command-window/"><u>Navigate to Public IP Using Windows Command Window</u></a></li>
<li><a href="https://vp-tips.techidaily.com/navigating-high-definition-zoom-features-for-2024/"><u>Navigating High-Definition Zoom Features for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-maintenance-tips-for-setting-active-windows-11-times/"><u>Navigating System Maintenance: Tips for Setting Active Windows 11 Times</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pro-video-and-photography-harnessing-the-power-of-hero5-black/"><u>Pro Video & Photography  Harnessing the Power of Hero5 Black</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-shield-5-key-fixes-for-windows-family-protection/"><u>Revive the Shield: 5 Key Fixes for Windows Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-quiet-slack-signals-on-windows-11-pcs/"><u>Reviving Quiet Slack Signals on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-seamlessly-engagedisengage-windows-terminal-focus/"><u>Secrets to Seamlessly Engage/Disengage Windows Terminal Focus</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-non-responsive-lenovo-mouse-pads-on-pc-tips-for-windows-1187-users/"><u>Solving Non-Responsive Lenovo Mouse Pads on PC: Tips for Windows 11/8/7 Users</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-visual-studio-code-on-windows-11/"><u>Stabilizing Visual Studio Code on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-wallpapers-for-each-windows-11-workspace-element/"><u>Step-by-Step Wallpapers for Each Windows 11 Workspace Element</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamline-your-workflow-learn-to-record-macs-screen-with-shortcuts/"><u>Streamline Your Workflow  Learn to Record Mac's Screen with Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-value-apple-watch-se-assessment-smartwatch-savings-without-compromise/"><u>The Value Apple Watch SE Assessment: Smartwatch Savings Without Compromise</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-t2-pro-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo T2 Pro 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://fox-glue.techidaily.com/transforming-ordinary-interviews-into-impactful-experiences/"><u>Transforming Ordinary Interviews Into Impactful Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-disabled-microsoft-outlook-push-notifications/"><u>Troubleshooting Disabled Microsoft Outlook Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-virtual-disk-service-failure-in-windows/"><u>Troubleshooting: Resolving Virtual Disk Service Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-smooth-spotify-link-functionality-in-windows-11/"><u>Unlocking Smooth Spotify Link Functionality in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-rapid-system-restart-windows-11-edition/"><u>Unlocking the Secrets of Rapid System Restart: Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-auditory-interference-mystery/"><u>Unraveling Windows' Auditory Interference Mystery</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
</ul></div>
