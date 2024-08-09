---
title: Activate/Deactivate Window 11 Search Lights
date: 2024-08-08T13:12:17.741Z
updated: 2024-08-09T13:12:17.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate/Deactivate Window 11 Search Lights
excerpt: This Article Describes Activate/Deactivate Window 11 Search Lights
keywords: Windows 11 Light Switch On/Off,Activate Window L11 Search Beam,Deactivate Windows L11 Scope,Enable/Disable Win11 Scope Light,Manage Windows 11 Search Illumination,Toggle Windows 11 Search Radiance,Control Win11 L11 Search Glow
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## Activate/Deactivate Window 11 Search Lights

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-2023s-largest-threaded-video-compilation/"><u>[New] In 2024, 2023'S Largest Threaded Video Compilation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-visionsnap-tech-your-guide-to-the-best-of-2023-for-2024/"><u>[New] VisionSnap Tech – Your Guide to the Best of 2023 for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-fbx-filming-made-simple-a-step-by-step-approach/"><u>[Updated] 2024 Approved  FBX Filming Made Simple  A Step-by-Step Approach</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-easily-connect-to-the-cloud-and-post-from-your-camera-roll/"><u>[Updated] Easily Connect to the Cloud and Post From Your Camera Roll</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-iciness-to-comfort-five-warm-backdrops-ideas-for-2024/"><u>[Updated] From Iciness to Comfort  Five Warm Backdrops Ideas for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-sizing-up-best-practices-for-instagram-videos-in-2eary-2023/"><u>[Updated] In 2024, Sizing Up  Best Practices for Instagram Videos in 2Eary 2023</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-unraveling-the-secrets-to-captivating-asmr-scenarios-and-effects/"><u>2024 Approved  Unraveling the Secrets to Captivating ASMR Scenarios and Effects</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-microsoft-powerpoint-not-printing-correctly-on-windows/"><u>9 Ways to Fix Microsoft PowerPoint Not Printing Correctly on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-windows-11-performance-with-these-adjustments/"><u>Achieve Peak Windows 11 Performance with These Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-to-remove-restrictions-on-blocked-windows-files/"><u>Advanced Methods to Remove Restrictions on Blocked Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-distractions-mastering-wins-on-windows-11/"><u>Avoiding Distractions: Mastering Wins on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-performance-with-vm-cache-clear/"><u>Boost PC Performance with VM Cache Clear</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-customization-what-are-the-risks/"><u>ChatGPT Customization: What Are the Risks?</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-lifelong-deletion-functions-on-windows-1011-desktop/"><u>Configuring Lifelong Deletion Functions on Windows 10/11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-file-management-altering-timestamps-in-windows/"><u>Cutting-Edge File Management: Altering Timestamps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-productivity-top-30-mouse-control-wizards/"><u>Elevate Productivity: Top 30 Mouse Control Wizards</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/first-film-recording-analysis-and-comparisons/"><u>First Film Recording Analysis & Comparisons</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-honor-100-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Honor 100 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-link-ups-phones-and-windows-11-synergy/"><u>Innovative Link-Ups: Phones and Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-system-top-tips-for-black-screen-on-win11/"><u>Jumpstart Your System: Top Tips for Black Screen on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-live-speech-to-text-whisper-desktop-tips/"><u>Mastering Live Speech-to-Text: Whisper Desktop Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-and-fixing-windows-update-issues/"><u>Mastering the Art of Finding and Fixing Windows Update Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-setting-updeactivating-metric-tracker-in-win11/"><u>Mastery: Setting Up/Deactivating Metric Tracker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-touchscreen-experience-on-a-windows-11-machine/"><u>Maximize Your Touchscreen Experience on a Windows 11 Machine</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mobile-audio-speed-the-fastest-app-list-for-2024/"><u>Mobile Audio Speed  The Fastest App List for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/monitor-not-recognizing-fullscreen-windows-on-win10/"><u>Monitor Not Recognizing Fullscreen Windows on Win10</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-underrated-realm-of-windows-monitoring-systems/"><u>Navigating the Underrated Realm of Windows Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-nonexistent-devices-in-os-windows-1011/"><u>Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-avoiding-endless-xbox-app-cycle/"><u>Quick Cure: Avoiding Endless Xbox App Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedy-restore-registry-management-functions/"><u>Quick Remedy: Restore Registry Management Functions</u></a></li>
<li><a href="https://win11.techidaily.com/relish-in-unmatched-windows-software-sweepstakes/"><u>Relish In Unmatched Windows Software Sweepstakes</u></a></li>
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/small-shop-success-through-social-video-content-for-2024/"><u>Small Shop Success Through Social Video Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-unlock-windows-defense-against-admins-choice/"><u>Techniques to Unlock Windows Defense Against Admins' Choice</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-reviving-your-windows-system/"><u>The Blueprint for Reviving Your Windows System</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unable-to-access-your-windows-start-icon/"><u>Troubleshooting: Unable to Access Your Windows Start Icon</u></a></li>
<li><a href="https://win11.techidaily.com/turning-oculus-quest-into-a-windows-based-vr-device/"><u>Turning Oculus Quest Into a Windows-Based VR Device</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-ceasing-wired-pc-keyboard-on-windows/"><u>Tutorial: Ceasing Wired PC Keyboard on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-high-performance-navigate-valorant-lag-reduction/"><u>Unlock High Performance: Navigate Valorant Lag Reduction</u></a></li>
</ul></div>
