---
title: "ViVeTool Breakdown: How to Pre-Emptive Access Updates"
date: 2024-08-16T00:55:36.242Z
updated: 2024-08-17T00:55:36.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes ViVeTool Breakdown: How to Pre-Emptive Access Updates"
excerpt: "This Article Describes ViVeTool Breakdown: How to Pre-Emptive Access Updates"
keywords: ViVeTool Update Guide,Preemptive Update Tools,Access Update Preparation,Videotool User Tips,Proactive Software Updates,Upgrade Management Basics,Streamline Software Updates
thumbnail: https://thmb.techidaily.com/5c068034f0080166994d164493cb808318b6f6a0f4d45de0f56404a9b7904a53.jpg
---

## ViVeTool Breakdown: How to Pre-Emptive Access Updates

 ViVeTool is an open-source command-line tool to enable experimental but hidden features on your Windows computer. It is also available in a GUI version, which makes it much easier to enable or disable certain features on Windows.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

## What Is ViVeTool, and How Does It Work?

 ViVeTool is a third-party open-source C# library and console app to enable unreleased features on your Windows computer. You can also use it to restore or disable certain features.

 ViVeTool uses feature IDs, part of Windows Feature Management, a software-development practice, to identify the available features. You can then use the feature IDs to enable or disable certain features on your Windows computer by using the ViVeTool command-line or GUI utility.

 For example, if you want to remove the new search box and replace it with the classic search icon, you’ll need to run the **ViVetool /disable /id:39263329** command using the ViVeTool command-line utility.

 The **feature ID id:39263329** in the above command tells the ViVeTool and the subsequent API request which feature to toggle on your Windows computer.

 You can source the feature ID from the internet or by using the ViVeTool GUI version. That said, the feature ID description in the GUI version is mostly cryptic, so tread carefully. Once you have the feature ID, you can use the ViVeTool command-line or GUI version to enable or disable features on your Windows computer.

## Is ViVeTool Safe to Use?

 ViVeTool doesn’t add new features on its own. It simply toggles the existing features to enable or disable them for your Windows system. However, since these features are experimental by nature, activating them may sometimes cause some issues.

 If you want to use ViVeTool on your daily driver, go through the [Windows data backup and recovery options](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) and proceed with the steps below. Ideally, use a virtual machine to test new features, and if found to be stable, apply them to your daily driver.

## How to Download and Install the ViVeTool GUI Version

 ViVeTool GUI is the forked version of the ViVeTool command-line utility. It is less complicated to use and removes the hassle of executing commands or remembering them in the first place. The GUI version is available as an executable installer or portable version. Here’s how to install and use ViVeTool GUI on Windows.

 To download the ViVeTool GUI version:

1. Go to the [ViVeTool GUI page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub.  
![download vivetool gui zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-gui-zip.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
2. Download the latest version of the **Setup.exe file** available. You can also download a portable version if you prefer.
3. Run the setup file and keep the default settings. Follow the on-screen instructions to install the app.

## How to Install Unreleased Features Using ViVeTool on Windows

 Now that the app is installed, you can use it to find and install unreleased features on your Windows computer. Here’s how to do it:

1. Launch the ViVeTool using a desktop shortcut or from the **Start** menu.  
![vivetool gui select build](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-gui-select-build.jpg)
2. Click the **Select Build** drop-down in the top-left corner and select your **Windows build.** You can [check Windows 11 build and version](https://www.makeuseof.com/check-build-and-version-windows-11/) using the **Settings app**. ViVeTool GUI will now start looking for all the available features for the selected build. This may take a few minutes, so wait till the list is populated.
3. ViVeTool GUI categorizes the available features into different categories, including **Always Disabled**, **Always Enabled**, **Disabled by Default**, **Enabled by Default**, and **Modifiable**. You can expand the category and select the feature to install.
4. Next, select the feature you want to enable or disable. Alternatively, type the feature name in the search bar to find a specific feature.  
![activate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/activate-feature-vivetool-gui.jpg)
5. Click the **Perform Action** drop-down select **Activate** to enable the feature. Wait for the success message and click **Close**.  
![revert to default values feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/revert-to-default-values-feature-vivetool-gui.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
6. If the changes are not immediately visible, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) to apply the changes. In some instances, you may need to restart your PC to make the changes.

 To revert the changes or disable a feature, you can use the Deactivate Feature option available in ViVeTool. Here's how to disable a feature using ViVeTool:

![deactivate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/deactivate-feature-vivetool-gui.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

1. Launch **ViVeTool GUI.**
2. Search and select the feature you want to disable.
3. Click the **Perform Action** drop-down in the top-right corner.
4. Select **Deactivate Feature** and click **OK**.

 Alternatively, you can also revert the feature to its default state. To do this, select the modified feature, click on **Perform Action,** and select **Revert Feature to Default Values.** The changes will take effect when you restart your computer next time.

 Here are a few new and lesser-known Windows features that you can enable using ViVeTool before anyone else:

* [Enable Windows Copilot Using ViVeTool](https://www.makeuseof.com/enable-windows-copilot-vivetool/)
* [Enable the Home Section in the Settings App in Windows 11](https://www.makeuseof.com/enable-home-section-settings-app-windows-11/)
* [Enable Instant Search Results in File Explorer in Windows 11](https://www.makeuseof.com/instant-search-results-file-explorer-windows-11/)
* [Enable the Enhanced Taskbar in Windows 11](https://www.makeuseof.com/enhanced-taskbar-settings-windows-11/)
* [Enable the Volume Mixer in the Action Center in Windows 11](https://www.makeuseof.com/volume-mixer-action-center-windows/)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## How to Use the ViVeTool Command-Line Version

 The original version of ViVeTool is a command-line utility. While it offers similar functionality as the GUI version, it is an efficient way to enable and disable Windows features quickly. Here’s how to do it:

1. Go to the [ViVeTool page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub. This lists all the releases of ViVeTools since its inception.  
![download vivetool command line zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-command-line-zip.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Locate the latest version of ViVeTools. As of writing this, **Version 1.6.2** is the latest stable release available, and version 1.7 is available as a pre-release.
3. Click on **Assets** to view the download options.
4. Next, click the **ViVeTool.GUI.1.6.2.0.Portable.zip** file (version may change with the new releases) to download the latest version to your local drive.  
![vivetool zip extract folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-zip-extract-folder.jpg)
5. Right-click on the **Zip** file and select **Extract** **all**. Select a destination and click **Extract**. Take note of the extraction folder.

1. Next, press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![command prompt vivetool change directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-change-directory.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
3. In the Command Prompt, change the directory to ViVeTool extracted folder. So, type the following command and press **Enter** to change the directory:  
`cd /d [ViVeToolFolderPath]`
4. For example, if I have the ViVeTool folder saved in C:\\Users\\username\\Downloads\\ViVeTool-v0.3.2, then the full command will look this:  
`cd /d C:\Users\username\Downloads\ViVeTool-v0.3.2`
5. Next, to enable a feature, use the following command and press Enter:  
`ViVeTool.exe /enable /id:featureID`

1. In the above command, replace featureID with the feature ID you want to enable.  
![command prompt vivetool enable feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-enable-feature.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. For example, to enable the tab feature in File Explorer, the feature ID is id:37634385\. So, the full command will look like this:  
`ViVeTool.exe /enable /id:37634385`
3. If you want to disable a feature, then the command will look something like this:  
`ViVeTool.exe /disable /id:featureID`
4. Once the command is executed, type exit and press Enter to close the Command Prompt.
5. Restart your PC to apply the changes. After the PC restarts, the changes should be visible.

## Why Does Enabling a Feature in ViVeTool Not Do Anything?

 You may not be able to enable all the features present in ViVeTool. Almost all the hidden features are OS build-dependent. This means if you enable a feature using ViVeTool, but the changes don’t take effect, it is likely because the feature is not supported by the Windows OS build version you are running.

 In other instances, it may be due to the feature state being set to **Always Disabled** or **Enabled** during compilation. In this instance, even if ViVeTool successfully processes your request, you are unlikely to see any real changes, as the feature is hard-coded to remain on or off.

## ViVeTool's Supported Commands

 Apart from the /enable and /disable command, ViVeTools support a bunch of other commands to reset the custom configuration for specific or all features, update ViVeTool, and export and import custom feature configuration.

| ViVeTool Command | Action                                                       |
| ---------------- | ------------------------------------------------------------ |
| /enable          | Enable a feature                                             |
| /disable         | Disable a feature                                            |
| /query           | Find a list of all the existing features configuration       |
| /reset           | To reset a custom configuration for a specific feature       |
| /resetall        | To reset a custom configuration for all the features         |
| /addsubs         | To add a feature usage subscription                          |
| /delsub          | To remove a feature usage subscription                       |
| /export          | To export custom feature configuration                       |
| /import          | To import custom feature configuration                       |
| /fixlkg          | Fix the current ‘Last Known Good’ rollback system corruption |
| /appupdate       | Look for new ViVeTool updates                                |
| /notifyusage     | Shows a feature notification                                 |

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## ViVeTool Brings Hidden Windows Experimental Features to Everyone

 ViVeTool makes it easy to find and test new experimental features before they are released to the public. Whether you use the GUI or command-line version, it lets you easily enable and disable some exciting and annoying features.

 That said, many of these hidden features may be buggy and cause system malfunction. So, keep your system backup handy before you tinker with ViVeTool.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/updated-professional-portrait-maker-for-passports-desktop-and-online-access-only/"><u>[Updated] Professional Portrait Maker for Passports – Desktop & Online Access Only</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-shining-scenes-quick-tips-to-transform-your-iphone-video-brilliance/"><u>2024 Approved  Shining Scenes  Quick Tips to Transform Your iPhone Video Brilliance</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-crashes-sonic-frontiers-full-screen-fixes/"><u>Conquering Crashes: Sonic Frontiers Full-Screen Fixes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-ai-the-possible-threats-in-the-digital-age/"><u>Decoding AI: The Possible Threats in the Digital Age</u></a></li>
<li><a href="https://win11.techidaily.com/directly-to-dialer-windows-11-tutorial/"><u>Directly to Dialer: Windows 11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-finest-zero-cost-windows-media-devices/"><u>Discover the Finest Zero-Cost Windows Media Devices</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-hp-officejet-5740-driver-instantly/"><u>Download & Install HP OfficeJet #5740 Driver Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-1110s-required-privilege-error-code-0x80070522/"><u>Eradicating Windows 11/10'S “Required Privilege” Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insights-into-os-upgrade-schedules-and-methods/"><u>Essential Insights Into OS Upgrade Schedules & Methods</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-mitigate-local-security-offline-issue/"><u>Essential Steps to Mitigate Local Security Offline Issue</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-m-audio-m-track-2x2-driver-issue-easily-and-quickly/"><u>Fix M-Audio M-Track 2X2 Driver Issue Easily & Quickly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/get-top-quality-gifs-on-your-mac-instantly/"><u>Get Top-Quality GIFs on Your Mac Instantly</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/how-to-use-iphone-note-recovery-apps-for-missing-memos-and-texts/"><u>How to Use iPhone Note Recovery Apps for Missing Memos and Texts</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-delete-icloud-account-with-or-without-password-from-your-iphone-sewindowsmac-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account with or without Password from your iPhone SE/Windows/Mac</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-infinix-hot-40-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-pathway-to-profit-enabling-youtuber-earnings-via-mobile-devices/"><u>In 2024, The Pathway to Profit  Enabling YouTuber Earnings via Mobile Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/innovating-mukbang-content-with-fresh-creative-ideas/"><u>Innovating Mukbang Content with Fresh, Creative Ideas</u></a></li>
<li><a href="https://facebook.techidaily.com/keep-your-social-safe-a-quick-checklist-for-9-warning-signs/"><u>Keep Your Social Safe: A Quick Checklist for 9 Warning Signs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-screen-capture-tool-in-windows-11-swiftly/"><u>Navigate to Screen Capture Tool in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-exe-file-opener-failures-in-windows/"><u>Overcoming .exe File Opener Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-rectifying-epic-games-logins/"><u>Quick Guide to Rectifying Epic Games Logins</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-handling-the-lack-of-msvcr120dll-in-windows/"><u>Quick Tips for Handling the Lack of MSVCR120.DLL in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-icon-placement/"><u>Regaining Control Over Icon Placement</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-hidden-or-unresponsive-comments-on-your-youtube-videos/"><u>Resolving Hidden or Unresponsive Comments on Your YouTube Videos</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-paste-functionality-across-chromeedgefirefox-windows/"><u>Reviving Paste Functionality Across Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-update-experience-with-easy-fixes-here/"><u>Seamless Windows Update Experience With Easy Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-offline-mode-in-microsoft-onedrive/"><u>Setting Up Offline Mode in Microsoft OneDrive</u></a></li>
<li><a href="https://extra-skills.techidaily.com/setting-up-windows-11-for-automatic-hdr-activation-for-2024/"><u>Setting Up Windows 11 for Automatic HDR Activation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/shadowing-shutdown-hide-win11s-power-icon-strategically/"><u>Shadowing Shutdown: Hide Win11's Power Icon Strategically</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-update-error-0x8024800c/"><u>Solutions for Windows Update Error 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-task-juggling-skills-a-guide-to-mastering-windows-11-multitasking/"><u>Step Up Your Task Juggling Skills: A Guide to Mastering Windows 11 Multitasking</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-end-task-feature-in-windows-11-ui/"><u>Steps to Turn On End Task Feature in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-dormant-pane-windows-6-tips-for-win11-users/"><u>Triggering Dormant Pane Windows: 6 Tips for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-cab-files-explanations-and-steps-for-installation/"><u>Understanding Windows Cab Files: Explanations & Steps for Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-potential-your-custom-hotkey-journey/"><u>Unlocking Windows Potential: Your Custom Hotkey Journey</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-mysteries-a-guide-to-finding-and-fixing-error-messages-using-commands/"><u>Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-missing-tab-button-on-your-machine/"><u>Unveiling the Missing Tab Button on Your Machine</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-display-selecting-premium-timers-and-savers/"><u>Upgrade Your Display: Selecting Premium Timers & Savers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>