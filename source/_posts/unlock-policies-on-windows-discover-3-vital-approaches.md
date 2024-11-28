---
title: "Unlock Policies on Windows: Discover 3 Vital Approaches"
date: 2024-11-24T04:09:36.117Z
updated: 2024-11-28T01:15:53.298Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Policies on Windows: Discover 3 Vital Approaches"
excerpt: "This Article Describes Unlock Policies on Windows: Discover 3 Vital Approaches"
keywords: Windows Policy Unlocking,Essential Windows Tweaks,Critical Policy Management,Key Windows Access Tips,Secure Windows Policies,Streamline Windows Settings,Optimize Windows Controls
thumbnail: https://thmb.techidaily.com/8b36213cf3c4388b8515bed526f0d42f540b1ba9bd34731fb80416cf28c2a508.jpg
---

## Unlock Policies on Windows: Discover 3 Vital Approaches

 The Local Group Policy is a tool that allows you to easily manage a wide range of system settings, from the appearance of the desktop to the security of the operating system. At times, you may need to review the policies applied to your Windows computer, either for troubleshooting purposes or to ensure that your system is configured correctly.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.

## 1\. How to View Applied Group Policies Using the Sort or Filter Options in Local Group Policy Editor

 The Local Group Policy Editor on Windows allows you to organize policies by their current state, so you can quickly see which ones are enabled or disabled.

 Use one of the [many ways to open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your PC. Then, use the left pane to head to **Computer Configuration > Administrative Templates > All Settings**. On your right, you will see a list of policies. Click the **State** column to sort policies based on their current status.

![Sort Group Policies on Windows by Their State](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sort-group-policies-on-windows-by-their-state.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the Group Policy Editor sorts all the policies, you can review or modify them as you see fit.

 Another way to see applied policies based on specific criteria is to use the filter option in the Local Group Policy Editor. This can be useful if you want to see all the applied policies in a particular area or folder.

 Simply right-click on a folder in the Local Group Policy Editor and select **Filter Options**. In the following window, select **Yes** in the **Configured** drop-down menu and click **OK**. After that, the Group Policy Editor will only show the folders and policies you have applied.

![Filter Group Policies on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/filter-group-policies-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-best-practices-in-yt-thumbnail-sizing/"><u>[New] 2024 Approved Best Practices in YT Thumbnail Sizing</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unleashing-creativity-a-tiktok-video-guide-for-devices/"><u>[Updated] In 2024, Unleashing Creativity A TikTok Video Guide for Devices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-your-first-step-on-twitter-creating-an-account/"><u>[Updated] In 2024, Your First Step on Twitter Creating an Account</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-key-videographers-in-asmr-landscape/"><u>[Updated] Key Videographers in ASMR Landscape</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-y78t-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo Y78t without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-mystery-of-blank-logins-on-windows-devices/"><u>Deciphering the Mystery of Blank Logins on Windows Devices</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-logitech-driver-upgrade-process/"><u>Direct Logitech Driver Upgrade Process</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-index-tuning-on-windows-os/"><u>Exploring Index Tuning on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-faulty-lock-screen-timeout-in-windows-1011/"><u>Fixing Faulty Lock Screen Timeout in Windows 10/11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-find-and-install-updated-drivers-for-hp-deskjet-3700-step-by-step-guide-and-links/"><u>How to Find and Install Updated Drivers for HP Deskjet 3700: Step-by-Step Guide & Links</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-file-alignment-errors-on-windows-drives/"><u>Repairing File Alignment Errors on Windows Drives</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-icons-in-windows-without-dismantling-system-files/"><u>Resetting Icons in Windows Without Dismantling System Files</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlocking-the-secrets-of-reversed-visual-exploration-online-facebook-for-2024/"><u>Unlocking the Secrets of Reversed Visual Exploration Online (Facebook) for 2024</u></a></li>
</ul></div>

