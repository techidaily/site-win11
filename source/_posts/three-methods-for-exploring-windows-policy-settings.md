---
title: Three Methods for Exploring Windows Policy Settings
date: 2024-07-13T10:04:12.542Z
updated: 2024-07-14T10:04:12.542Z
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

## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

## 3\. How to View Applied Group Policies With PowerShell

 Another method for determining which policies are applied to a Windows user or computer involves using PowerShell. If you are someone who prefers using command-line tools to interact or make changes to your computer, this method can come in handy.

 To view applied group policies using PowerShell, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the PowerShell window and press **Enter**:  
`gpresult /Scope User /v`  
![See Applied Policies for a User on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/see-applied-policies-for-a-user-on-windows.jpg)

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

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
<li><a href="https://extra-skills.techidaily.com/screen-selection-simplified-ultrawide-versus-uhd-4k-demystified-for-2024/"><u>Screen Selection Simplified  UltraWide Versus UHD 4K Demystified for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/modernized-guide-of-queries-for-engaging-podcast-discussions-for-2024/"><u>Modernized Guide of Queries for Engaging Podcast Discussions for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-essential-tools-for-motion-artwork/"><u>2024 Approved  Essential Tools for Motion Artwork</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-complete-guide-to-change-video-resolution-in-filmora/"><u>New 2024 Approved Complete Guide to Change Video Resolution in Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-rapid-rise-of-tweets-top-hotties-on-twitterscape/"><u>In 2024, Rapid Rise of Tweets  Top Hotties on Twitterscape</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-se-2020-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From Apple iPhone SE (2020) If Youve Tried Everything</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-typing-prowess-changing-and-adding-keyboards-for-win-11/"><u>Boost Typing Prowess: Changing and Adding Keyboards for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-10-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-final-countdown-for-windows-xp-7-and-81-lifeline-on-microsoft/"><u>The Final Countdown for Windows XP, 7 & 8.1 Lifeline on Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-innovation-vr-controllers-reviewed/"><u>[New] Leading Innovation  VR Controllers Reviewed</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-art-of-accompanying-visual-content-with-music/"><u>2024 Approved  The Art of Accompanying Visual Content with Music</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-bandicam-unveiled-a-thorough-examination-of-its-recording-capabilities-for-2024/"><u>[Updated] Bandicam Unveiled  A Thorough Examination of Its Recording Capabilities for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-repairing-your-windows-headsets-microphone/"><u>Addressing and Repairing Your Windows Headset's Microphone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-most-popular-tweet-chronicles-2023-edition-for-2024/"><u>[Updated] Most Popular Tweet Chronicles - 2023 Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Oppo A79 5G | Dr.fone</u></a></li>
</ul></div>
