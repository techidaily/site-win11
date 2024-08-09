---
title: Muting File Explorer Tabs in Windows 11 Guide
date: 2024-08-08T13:21:14.752Z
updated: 2024-08-09T13:21:14.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Muting File Explorer Tabs in Windows 11 Guide
excerpt: This Article Describes Muting File Explorer Tabs in Windows 11 Guide
keywords: Mute Windows Tabs,PC Tab Silence,Win11 Silent Mode,File Explore Quieting,Taskbar Hush Guide,Mutual File Explorer,Tabs Mute Tips
thumbnail: https://thmb.techidaily.com/aa427c93a364e264a275d02d7b783f7e962d85c1fac24bb52cc0d4742cbe1750.jpg
---

## Muting File Explorer Tabs in Windows 11 Guide

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://youtube-blog.techidaily.com/levate-your-video-profiles-using-smart-templates-for-2024/"><u>[New] Elevate Your Video Profiles Using Smart Templates for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-watchers-unveiling-who-sees-your-content/"><u>[New] In 2024, Instagram Watchers  Unveiling Who Sees Your Content</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-composing-engaging-podcast-thumbnails/"><u>[Updated] 2024 Approved  Composing Engaging Podcast Thumbnails</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-top-5-quick-filming-diy-hacks-to-try-at-home/"><u>[Updated] In 2024, Top 5 Quick Filming DIY Hacks to Try at Home</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-ultimate-list-of-8-gratis-corporate-video-conferencing-software/"><u>2024 Approved  The Ultimate List of 8 Gratis Corporate Video Conferencing Software</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-rewind-game-pc-redemption/"><u>AtlasOS Rewind: Game PC Redemption</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-sandbox-a-win-11-guide/"><u>Configure Your Sandbox: A Win 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-docker-setup-tips-for-optimized-wsl-2-use/"><u>Elevate Your Docker Setup: Tips for Optimized WSL 2 Use</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-camera-error-a00f4289-in-windows-environments/"><u>Eradicating Camera Error A00F4289 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-policies-an-in-depth-analysis-using-3-different-views/"><u>Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-spontaneous-search-menu-open-in-win11/"><u>Fixing Spontaneous Search Menu Open in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-tecno-spark-go-2024-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Tecno Spark Go (2024).</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-lsa-protection-error-on-windows/"><u>How to Fix the LSA Protection Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-enable-razer-recognition-by-synapse/"><u>How to Re-Enable Razer Recognition by Synapse</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-save-locations-on-windows-devices/"><u>How to Resolve Save Locations on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-microsofts-phone-link-on-mobile-devices/"><u>How to Utilize Microsoft's Phone Link on Mobile Devices</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-9-pinnacle-in-live-game-broadcasting/"><u>In 2024, 9 Pinnacle in Live Game Broadcasting</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-poco-f5-pro-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Poco F5 Pro 5G Fingerprint Lock</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-full-guide-to-unlock-iphone-6s-plus-with-itunes-drfone-by-drfone-ios/"><u>In 2024, Full Guide to Unlock iPhone 6s Plus with iTunes | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/innovative-approaches-for-bigger-character-portrayals-on-tiktok/"><u>Innovative Approaches for Bigger Character Portrayals on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-google-nearby-to-link-devices-easily/"><u>Leveraging Google Nearby to Link Devices Easily</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-for-disabling-onedrive-indicator-in-windows-11/"><u>Methodology for Disabling OneDrive Indicator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-missing-window-panes-with-win11-6-tips/"><u>Reclaiming Missing Window Panes with Win11 (6 Tips)</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-legacy-boot-configurations/"><u>Reinstating Legacy Boot Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-devices-in-sleep-mode-of-win11-pc/"><u>Resurrecting Devices in Sleep Mode of Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-windows-webcam-transition-techniques/"><u>Seamless Android-Windows Webcam Transition Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/seamlessly-post-pictures-your-youtube-visual-guide/"><u>Seamlessly Post Pictures  Your YouTube Visual Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-no-connection-found-error-in-win/"><u>Steps to Solve No Connection Found Error in WIN</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-from-iphone-se-2022-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication From iPhone SE (2022)? 5 Tips You Must Know</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
</ul></div>
