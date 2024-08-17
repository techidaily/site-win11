---
title: Navigating Highlight Settings in Windows 11
date: 2024-08-16T00:09:04.623Z
updated: 2024-08-17T00:09:04.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Highlight Settings in Windows 11
excerpt: This Article Describes Navigating Highlight Settings in Windows 11
keywords: Win11 Highlight Controls,Windows 11 Theme Editing,Adjusting Windows Colors,Changing Display Features,Windows Color Settings Guide,Master Window's Appearance,Tailor Windows UI Brightness
thumbnail: https://thmb.techidaily.com/095ce3d3eacef166f46f59459d5ef71a92a706285f3160a9b70eb170ae6406f1.jpg
---

## Navigating Highlight Settings in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-comprehensive-guide-to-whatsapp-vocal-exchange/"><u>[New] 2024 Approved  Comprehensive Guide to WhatsApp Vocal Exchange</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-bridging-gaps-transforming-trend-data-into-video-concepts/"><u>[New] In 2024, Bridging Gaps  Transforming Trend Data Into Video Concepts</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-streamlining-your-tweets-with-video-upload-rules/"><u>[New] In 2024, Streamlining Your Tweets with Video Upload Rules</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-deep-dive-into-selecting-tiktok-screenshots/"><u>[Updated] A Deep Dive Into Selecting TikTok Screenshots</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-is-integrating-itop-into-your-toolkit-advisable-for-2024/"><u>[Updated] Is Integrating ITop Into Your Toolkit Advisable for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-leading-locales-for-immersive-content/"><u>[Updated] Leading Locales for Immersive Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-step-by-step-youtube-image-enlargement-technique/"><u>[Updated] Step-by-Step Youtube Image Enlargement Technique</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-oppo-find-n3-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Oppo Find N3 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-streamline-your-workflow-learn-to-record-macs-screen-with-shortcuts/"><u>2024 Approved  Streamline Your Workflow  Learn to Record Mac's Screen with Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/ditch-the-focus-spotlight-icon-on-win11-desktop/"><u>Ditch the Focus: Spotlight Icon on Win11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-setup-failures-windows-10-and-11-edition/"><u>Fixing Windows Setup Failures: Windows 10 & 11 Edition</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722964171534-get-the-newest-canon-color-laserjet-mg490-windows-driver-software-here/"><u>Get the Newest Canon Color LaserJet MG490 Windows Driver Software Here</u></a></li>
<li><a href="https://tech-hub.techidaily.com/gpt-3-vs-translate-best-at-language-conversion/"><u>GPT-3 Vs. Translate: Best at Language Conversion?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-streamlined-scheduling-making-the-most-of-zoom-calls/"><u>In 2024, Streamlined Scheduling  Making the Most of Zoom Calls</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-guide-to-setting-up-windows-11-calendar/"><u>In-Depth Guide to Setting Up Windows 11 Calendar</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/instantly-engage-in-video-talks-using-whatsapp-web-from-your-laptop-for-2024/"><u>Instantly Engage in Video Talks Using WhatsApp Web From Your Laptop for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-artistic-creation-with-windows-11-make-amazing-ai-images-using-paint-tool-sai/"><u>Master Artistic Creation with Windows 11: Make Amazing AI Images Using Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-window-settings-for-optimal-space-in-win11/"><u>Master the Window Settings for Optimal Space in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-the-exception-has-been-reached-on-pcs/"><u>Mastering Fixes for The Exception Has Been Reached on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-managerial-maze-free-old-championship-soccer-management-guide/"><u>Navigate the Managerial Maze: Free Old Championship Soccer Management Guide</u></a></li>
<li><a href="https://win11.techidaily.com/nexus-controller-down-regain-control-with-these-fixes/"><u>Nexus Controller Down? Regain Control with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-speed-5-expertly-engineered-pc-enhancements/"><u>Pinnacle Speed: 5 Expertly Engineered PC Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unpreviewed-documents-error-in-office-outlook/"><u>Quick Fixes for Unpreviewed Documents Error in Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-usability-ai-transformations-in-windows/"><u>Redefining Usability: AI Transformations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-directories-not-empty-error-on-win11-with-0x80070091/"><u>Remedying Directories Not Empty Error on Win11 with #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cloud-sync-failures-windows-10-and-11/"><u>Resolving Cloud Sync Failures: Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-tab-key-for-seamless-typing/"><u>Reviving a Dormant Tab Key for Seamless Typing</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gameplay-mastery-fixing-frames-drops-in-valorant/"><u>Seamless Gameplay Mastery: Fixing Frames Drops in Valorant</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/seamless-shoot-and-stream-perfecting-dslr-broadcasts-from-home-pcsmacs-for-2024/"><u>Seamless Shoot & Stream  Perfecting DSLR Broadcasts From Home PCs/Macs for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-save-netflix-videos-onto-your-laptop/"><u>Step-by-Step: Save Netflix Videos Onto Your Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-interface-with-alignment/"><u>Streamline Windows Interface with Alignment</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-corrupted-recycle-bin-on-win-11/"><u>Tackling Corrupted Recycle Bin on Win 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tech-picks-leading-drone-gimbals-for-2024/"><u>Tech Picks  Leading Drone Gimbals for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-lava-blaze-2-pro-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Lava Blaze 2 Pro</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-nokia-g310-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Nokia G310 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-not-found-in-windows-environments/"><u>Unraveling 'Not Found' In Windows Environments</u></a></li>
<li><a href="https://fox-that.techidaily.com/unsticking-stubborn-iphone-alarms-that-just-wont-go-off/"><u>Unsticking Stubborn iPhone Alarms That Just Won't Go Off</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-approach-to-turn-off-gpgpu-prioritization-on-winos/"><u>Unveiling the Approach to Turn Off GPGPU Prioritization on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-virtualbox-to-70-in-win11-a-comprehensive-tutorial/"><u>Upgrading VirtualBox to 7.0 in Win11: A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-computer-embracing-the-power-of-16gb/"><u>Upgrading Your Computer: Embracing the Power of 16GB</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-win11-control-panel-settings-locate-missing-keys/"><u>Where Are Win11 Control Panel Settings? Locate Missing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips</u></a></li>
</ul></div>
