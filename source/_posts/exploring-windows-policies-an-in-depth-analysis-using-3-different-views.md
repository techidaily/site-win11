---
title: "Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views"
date: 2024-06-25T09:44:37.385Z
updated: 2024-06-26T09:44:37.385Z
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
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-clicks-avoid-accelerated-movement-in-win-1011/"><u>Stabilizing Clicks: Avoid Accelerated Movement in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-invisible-images-with-encrypted-zips-win/"><u>Mastering the Art of Invisible Images with Encrypted Zips (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-on-mac-via-parallels/"><u>Mastering Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/correct-misplaced-second-display-on-windows-11/"><u>Correct Misplaced Second Display on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11-drag-and-drop-failures-now/"><u>Fix Windows 11 Drag-and-Drop Failures Now</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-driver-verifier-on-windows-11-pc/"><u>Triggering Driver Verifier on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/fan-the-fire-essential-tips-for-cooler-gameplay-on-overheated-windows-laptops/"><u>Fan the Fire: Essential Tips for Cooler Gameplay on Overheated Windows Laptops</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-how-to-use-gimp-green-screen/"><u>In 2024, How to Use GIMP GREEN SCREEN</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-strategies-for-expanding-your-tiktok-influence-via-hashtags/"><u>In 2024, Strategies for Expanding Your TikTok Influence via Hashtags</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-lava-blaze-2-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Lava Blaze 2 5G FRP</u></a></li>
<li><a href="https://extra-tips.techidaily.com/real-time-broadcast-at-your-fingertips-12-channels/"><u>Real-Time Broadcast at Your Fingertips - 12 Channels</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-oppo-find-x7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-honor-magic-6-lite-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Honor Magic 6 Lite Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-the-new-powerdirector-a-2024-blueprint/"><u>[New] Navigating the New PowerDirector  A 2024 Blueprint</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-capturing-attention-sharing-tweets-as-snaps-for-2024/"><u>[Updated] Capturing Attention  Sharing Tweets as Snaps for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-enhance-your-tiktok-viewing-experience-for-2024/"><u>[New] Enhance Your TikTok Viewing Experience for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-signature-to-a-pdf-v12-document-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to add signature to a PDF v1.2 document</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>