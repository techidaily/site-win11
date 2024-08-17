---
title: 3 Ways to View the Applied Group Policies on Windows
date: 2024-08-15T23:28:05.660Z
updated: 2024-08-16T23:28:05.660Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to View the Applied Group Policies on Windows
excerpt: This Article Describes 3 Ways to View the Applied Group Policies on Windows
keywords: PolicyViewWindowsApps,GroupPolicyWindowAccess,SeeGroupPoliciesWinOS,AccessGroupRulesWindows,ViewWindowsGroupPolicies,WindowsGroupPolicyInspect,InspectGroupPoliciesWinOS
thumbnail: https://thmb.techidaily.com/6fcd76fd6f172d48de92c06ef6acf9b4878b2af9216aa863bdd663f250b5d16d.jpg
---

## 3 Ways to View the Applied Group Policies on Windows

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
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-reel-in-attention-by-emulating-tiktok-stardom-on-instagram/"><u>[New] 2024 Approved  Reel In Attention by Emulating TikTok Stardom on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-guide-to-applying-luts-in-professional-production/"><u>[New] Expert Guide to Applying LUTs in Professional Production</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/achieve-social-stardom-the-ultimate-list-for-fb-fan-increase-for-2024/"><u>Achieve Social Stardom  The Ultimate List for FB Fan Increase for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-between-windows-and-wsl-with-post-update-strategies/"><u>Bridging Gaps Between Windows & WSL With Post-Update Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-combining-folders-and-files-win-1011-style/"><u>Bridging Gaps: Combining Folders & Files, Win 10/11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-to-your-my-pictures-on-w11/"><u>Bridging Generations: Old Games to Your My Pictures on W11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-local-libraries-and-online-oceans-dropbox-googledrive-on-c/"><u>Bridging Local Libraries & Online Oceans: Dropbox, GoogleDrive on C:/</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-to-recovered-network-access/"><u>Bridging the Gap to Recovered Network Access</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-back-typical-window-explorer-options/"><u>Bringing Back Typical Window Explorer Options</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-winget-back-online-window-11-edition/"><u>Bringing Winget Back Online: Window 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bsod-fix-tips-counteracting-issues-with-vmware-on-windows-11/"><u>BSOD Fix Tips: Counteracting Issues with VMware on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-connections-ps3-dualshock-on-windows/"><u>Bypass Connections: PS3-DualShock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-update-warnings-with-these-4-tips/"><u>Bypass Update Warnings with These 4 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevation-requirement-hurdle-on-winos/"><u>Bypassing Elevation Requirement Hurdle on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-geforce-experiences-error-on-windows-pcs/"><u>Bypassing GeForce Experience's Error on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-insufficient-access-on-windows-for-removal-tasks/"><u>Bypassing Insufficient Access on Windows for Removal Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-insufficient-privileges-for-app-updates-on-windows-oses/"><u>Bypassing Insufficient Privileges for App Updates on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-internal-failure-for-smooth-rd-session/"><u>Bypassing Internal Failure for Smooth RD Session</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumble-errors-on-microsoft-store-win-1011/"><u>Bypassing Server Stumble Errors on Microsoft Store, Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-alerts-fast-track/"><u>Bypassing Windows 11 Alerts Fast-Track</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fixing-outdated-windows-user-password-issue/"><u>Bypassing: Fixing Outdated Window's User Password Issue</u></a></li>
<li><a href="https://win11.techidaily.com/cease-unsolicited-search-menu-activation-win11-style/"><u>Cease Unsolicited Search Menu Activation, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/change-windows-11-taskbar-size/"><u>Change Windows 11 Taskbar Size</u></a></li>
<li><a href="https://win11.techidaily.com/changing-file-dates-in-windows-a-practical-overview/"><u>Changing File Dates in Windows: A Practical Overview</u></a></li>
<li><a href="https://win11.techidaily.com/chatgpt-deployment-for-windows-computers/"><u>ChatGPT Deployment for Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/chatgpt-lite-free-self-hosted-windows-edition-with-gpt4all/"><u>ChatGPT Lite: Free Self-Hosted Windows Edition with GPT4All.</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-stuck-unlock-windows-11s-quick-fixes-now/"><u>Chrome Stuck? Unlock Windows 11'S Quick Fixes Now</u></a></li>
<li><a href="https://win11.techidaily.com/classic-game-connector-directing-past-fun-into-the-future/"><u>Classic Game Connector: Directing Past Fun Into the Future</u></a></li>
<li><a href="https://win11.techidaily.com/clear-out-clutter-personalize-your-w11-workspace/"><u>Clear Out Clutter: Personalize Your W11 Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/clear-outdated-files-with-confidence-using-windows-1011s-feature/"><u>Clear Outdated Files with Confidence Using Windows 10/11'S Feature</u></a></li>
<li><a href="https://win11.techidaily.com/clear-screen-glitches-via-windows-11-driver-reset/"><u>Clear Screen Glitches via Windows 11 Driver Reset</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-nine-tricks-to-dodge-steady-windows-update-stalls/"><u>Clear the Path: Nine Tricks to Dodge Steady Windows Update Stalls</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-from-the-recycle-bin-in-win-11-edition/"><u>Clearing Errors From the Recycle Bin in Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusions-removing-read-only-from-folders/"><u>Clearing Up Confusions: Removing Read-Only From Folders</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-headphone-connection-errors-in-windows/"><u>Clearing Up Headphone Connection Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cleverly-camouflaged-these-programs-slow-down-windows-users/"><u>Cleverly Camouflaged, These Programs Slow Down Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/combat-plan-against-dual-programming-issues/"><u>Combat Plan Against Dual Programming Issues</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-phone-to-fame-best-vertical-video-editing-apps-for-mobile-creators/"><u>From Phone to Fame Best Vertical Video Editing Apps for Mobile Creators</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-demystifying-ez-grabber-a-beginners-guide/"><u>In 2024, Demystifying EZ Grabber  A Beginner's Guide</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-hitting-a-pixel-snag-a6400s-video-problems/"><u>In 2024, Hitting a Pixel Snag  A6400's Video Problems</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ating-facebook-sharing-of-youtube-videos-for-2024/"><u>Navigating Facebook Sharing of YouTube Videos for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-choices-the-premier-portable-devices-for-editors-for-2024/"><u>Prime Choices  The Premier Portable Devices for Editors for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/step-by-step-solution-for-overcoming-black-display-on-discords-shared-screens/"><u>Step-by-Step Solution for Overcoming Black Display on Discord's Shared Screens</u></a></li>
<li><a href="https://driver-download.techidaily.com/tp-link-ub400-free-downloads-for-your-bluetooth-usb-adapter-drivers/"><u>TP-Link UB400: Free Downloads for Your Bluetooth USB Adapter Drivers</u></a></li>
</ul></div>
