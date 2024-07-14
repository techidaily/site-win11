---
title: 3 Ways to View the Applied Group Policies on Windows
date: 2024-07-13T11:07:43.342Z
updated: 2024-07-14T11:07:43.342Z
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
<li><a href="https://facebook-record-videos.techidaily.com/new-crafting-link-driven-success-a-backlink-blueprint-for-channels-for-2024/"><u>[New] Crafting Link-Driven Success  A Backlink Blueprint for Channels for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-device-sticky-note-integration-on-win11/"><u>Seamless Multi-Device Sticky Note Integration on WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fix-kit-conquering-error-code-0x80-cookies/"><u>Microsoft Store Fix Kit: Conquering Error Code 0X80 Cookies</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-unsupported-devices-warning-when-upgrading-windows/"><u>How to Handle Unsupported Devices Warning When Upgrading Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-enhancing-photos-and-videos-with-instagrams-creative-features/"><u>In 2024, Enhancing Photos and Videos with Instagram's Creative Features</u></a></li>
<li><a href="https://win11.techidaily.com/fast-tracking-yuzu-gameplay-on-windows/"><u>Fast-Tracking Yuzu Gameplay on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-top-rated-online-webm-video-minifiers/"><u>New 2024 Approved Top-Rated Online WebM Video Minifiers</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-with-linuxs-sudo-feature/"><u>Navigating Windows with Linux's Sudo Feature</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-your-pcs-ram-landscape-on-windows/"><u>Navigate Your PC's RAM Landscape on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-impact-with-auto-color-settings-in-windows-11/"><u>Maximize Visual Impact with Auto Color Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ntoskrnlexe-overload-issue/"><u>Addressing Ntoskrnl.exe Overload Issue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximizing-your-potential-is-a-joined-force-right-for-you/"><u>[Updated] Maximizing Your Potential  Is a Joined Force Right for You?</u></a></li>
<li><a href="https://win11.techidaily.com/openai-whisper-for-windows-voice-to-text-techniques-unveiled/"><u>OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-optimize-collaborative-sessions-zooming-in-on-google-meet-participants/"><u>2024 Approved  Optimize Collaborative Sessions  Zooming in on Google Meet Participants</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/compreender-expressoes-do-carinho-no-portugues/"><u>Compreender Expressões Do Carinho No Português</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-windows-11s-help-interaction/"><u>How to Revive Windows 11'S Help Interaction</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-the-redundant-or-missing-windows-tools-and-add-ons/"><u>Reinstalling the Redundant or Missing Windows Tools & Add-Ons</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-overhaul-overflow-cutting-edge-techniques-for-massive-tiktok-drafts/"><u>[Updated] Overhaul Overflow  Cutting-Edge Techniques for Massive TikTok Drafts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-vivo-s18e-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Vivo S18e Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-domain-users-biometric-use-on-w11/"><u>Strategizing Domain Users' Biometric Use on W11</u></a></li>
<li><a href="https://win11.techidaily.com/best-web-browsing-practices-minimizing-resources-across-platforms/"><u>Best Web Browsing Practices: Minimizing Resources Across Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-enable-widgets-on-windows-11-system/"><u>Harness the Power: Enable Widgets on Windows 11 System</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streamline-your-seo-strategy-with-the-leading-7-online-youtube-tags-tools-for-2024/"><u>Streamline Your SEO Strategy with the Leading 7 Online Youtube Tags Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unauthorized-access-to-secure-devices-win/"><u>Addressing Unauthorized Access to Secure Devices Win</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-purging-partitions-on-your-win-os/"><u>Mastering the Art of Purging Partitions on Your Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-smooth-directx-installation-on-pc/"><u>Step-by-Step Guide to Smooth DirectX Installation on PC</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-whats-rigging-animation-and-why-it-matters-for-2024/"><u>Updated Whats Rigging Animation and Why It Matters for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-essential-guide-to-cheap-webcam-capture-tech/"><u>[New] In 2024, Essential Guide to Cheap Webcam Capture Tech</u></a></li>
<li><a href="https://win11.techidaily.com/enable-system-sounds-despite-muted-status/"><u>Enable System Sounds Despite Muted Status</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-navigation-for-uwp-apps-with-windows-11-links/"><u>Rapid Navigation for UWP Apps with Windows 11 Links</u></a></li>
<li><a href="https://win11.techidaily.com/the-rise-of-ai-in-next-gen-windows/"><u>The Rise of AI in Next-Gen Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-selections-of-the-year-best-snowboard-and-ski-cams/"><u>[New] Selections of the Year  Best Snowboard & Ski Cams</u></a></li>
<li><a href="https://win11.techidaily.com/end-session-of-unknown-windows-users-effectively/"><u>End Session of Unknown Windows Users Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-pc-graphics-fix-in-windows-1011/"><u>Mastering PC Graphics Fix in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/bring-home-the-fun-smartphone-games-to-desktop-with-win-11-and-google-play/"><u>Bring Home the Fun: Smartphone Games to Desktop with Win 11 & Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-memory-shortage-error-in-windows-based-vms/"><u>Solutions for 'Memory Shortage' Error in Windows-Based VMs</u></a></li>
<li><a href="https://win11.techidaily.com/zip-file-disguise-for-windows-11-enthusiasts/"><u>Zip File Disguise for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/erasing-email-on-windows-sign-in-a-guide/"><u>Erasing Email on Windows Sign-In: A Guide</u></a></li>
</ul></div>
