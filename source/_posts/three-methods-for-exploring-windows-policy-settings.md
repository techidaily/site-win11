---
title: Three Methods for Exploring Windows Policy Settings
date: 2024-06-25T11:27:47.294Z
updated: 2024-06-26T11:27:47.294Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/overcoming-system-problem-zerosevennine/"><u>Overcoming System Problem ZeroSevenNine</u></a></li>
<li><a href="https://win11.techidaily.com/time-travel-in-tech-flipping-old-games-with-dosbox-x/"><u>Time Travel in Tech: Flipping Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-ad-ds-strategies-for-printer-troubleshooting/"><u>Win11 & AD DS: Strategies for Printer Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-11-experience-introducing-an-augmented-run-feature/"><u>Master Your Windows 11 Experience: Introducing an Augmented Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-github-desktop-adoption-in-windows-11/"><u>Best Practices for GitHub Desktop Adoption in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/purify-your-pc-go-bare-with-tiny11/"><u>Purify Your PC: Go Bare with Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-novice-cinematographers-initial-work-analysis-and-replacements/"><u>In 2024, Novice Cinematographer's Initial Work Analysis & Replacements</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-10-best-discord-plugins-to-improve-using-experience/"><u>[Updated] 2024 Approved  10 Best Discord Plugins to Improve Using Experience</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-selecting-an-ideal-mac-music-file-identifier-tool/"><u>In 2024, Selecting an Ideal Mac Music File Identifier Tool</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hyperfast-picture-explorer-on-windows-11/"><u>2024 Approved  Hyperfast Picture Explorer on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-xr-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone XR With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-y02t-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Y02T</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premier-windows-8-audio-shows/"><u>2024 Approved  Premier Windows 8 Audio Shows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/sound-fidelity-at-home-mastering-quality-recordings-for-2024/"><u>Sound Fidelity at Home  Mastering Quality Recordings for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-ranking-the-ultimate-vr-fun-on-mobile-devices/"><u>[Updated] Ranking the Ultimate VR Fun on Mobile Devices</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Apple iPhone 7 Plus | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>