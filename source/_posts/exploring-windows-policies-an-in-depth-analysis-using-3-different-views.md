---
title: "Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views"
date: 2024-06-25T11:23:05.581Z
updated: 2024-06-26T11:23:05.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views"
excerpt: "This Article Describes Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views"
keywords: Windows Policy Deep Insight,Policy Management Guide,Policy View Explained,Security Policy Analysis,Policies in Windows Explored,Access Control Settings,User Rights Configuration
thumbnail: https://thmb.techidaily.com/b744c16caf8d91ab5e04778eef04ae38bd5e09c87e85e6ab4edefd7b2e2e0090.jpg
---

## Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-windows-11-zoom-failure-1132/"><u>Unblocking Windows 11 Zoom Failure #1132</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-malfunctioning-windows-snippers/"><u>Regaining Control Over Malfunctioning Windows Snippers</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reverse-color-issue-with-windows-marketplace/"><u>Techniques to Reverse Color Issue with Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-strategies-for-finding-a-misplaced-pin/"><u>Unlock Windows 11 - Strategies for Finding a Misplaced PIN</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-mobile-video-mastery-top-split-screen-apps-for-iphone-and-android/"><u>New Mobile Video Mastery Top Split Screen Apps for iPhone and Android</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-14-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone 14 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-offline-replay-select-playlist-extractors-reviewed/"><u>[Updated] Offline Replay  Select Playlist Extractors Reviewed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/step-by-step-guide-to-premium-mac-video-capture/"><u>Step-by-Step Guide to Premium Mac Video Capture</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-design-and-graphics-free-and-affordable-sources/"><u>[New] Innovative Design and Graphics  Free & Affordable Sources</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-drone-editors-toolkit-techniques-for-visual-excellence/"><u>2024 Approved  The Drone Editor's Toolkit  Techniques for Visual Excellence</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/boosting-brand-presence-with-innovative-snapads/"><u>Boosting Brand Presence with Innovative SnapAds</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-creating-ai-videos-with-templates/"><u>In 2024, Creating AI Videos With Templates</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-samsung-galaxy-s23-ultra-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Samsung Galaxy S23 Ultra to New Phone | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>