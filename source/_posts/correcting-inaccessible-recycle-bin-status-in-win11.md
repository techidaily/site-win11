---
title: Correcting Inaccessible Recycle Bin Status in Win11
date: 2024-08-16T00:48:49.809Z
updated: 2024-08-17T00:48:49.809Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Inaccessible Recycle Bin Status in Win11
excerpt: This Article Describes Correcting Inaccessible Recycle Bin Status in Win11
keywords: Win11 Fix Recycle Issues,Access Win11 Trash,Enhance Win11 Bin,Resolve Win11 Waste Error,Windows Bin Status Correct,Fix Win11 Bin Not Shown,Improve Win11 Garbage Icon
thumbnail: https://thmb.techidaily.com/b41dfc1747c954c2591d35270b4a20079e5707f867334ccdc51bba558ecb898b.jpg
---

## Correcting Inaccessible Recycle Bin Status in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-capture-and-share-best-social-media-tools-of-the-year/"><u>[New] 2024 Approved  Capture and Share  Best Social Media Tools of the Year</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-skype-recording-procedures-streamlined-techniques-for-windows-and-os-x/"><u>[New] 2024 Approved  Skype Recording Procedures - Streamlined Techniques for Windows & OS X</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-decoding-inverse-visual-queries-on-facebook-platforms/"><u>[New] In 2024, Decoding Inverse Visual Queries on Facebook Platforms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-smooth-path-from-instagram-visuals-to-mp3-sound/"><u>[New] Smooth Path  From Instagram Visuals to Mp3 Sound</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-understanding-and-meeting-aspect-ratios-on-twitter-for-2024/"><u>[New] Understanding and Meeting Aspect Ratios on Twitter for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-selecting-sacred-sounds-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Selecting Sacred Sounds  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-androidios-users-guide-to-facebook-live-broadcasting-for-2024/"><u>[Updated] Android/iOS Users' Guide to Facebook Live Broadcasting for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-optimize-your-video-written-by-your-name/"><u>[Updated] In 2024, Optimize Your Video' Written By  [Your Name]</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-premium-cutter-writers-the-top-8-linux-software/"><u>[Updated] Premium Cutter' Writers  The Top 8 Linux Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-2023-guide-ios-device-live-recording-techniques/"><u>2024 Approved  2023 Guide  IOS Device Live Recording Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-key-concepts-in-quantum-hdr-mastery/"><u>2024 Approved  Key Concepts in Quantum HDR Mastery</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-apple-iphone-12-mini-fix-now-drfone-by-drfone-virtual-ios/"><u>3uTools Virtual Location Not Working On Apple iPhone 12 mini? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-game-changing-windows-11-additions-in-moment-22h2/"><u>7 Game-Changing Windows 11 Additions in Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-utilities-to-update-file-timestamps/"><u>7 Windows Utilities To Update File Timestamps</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-rectifying-mmc-snap-in-failures/"><u>A Guide to Rectifying MMC Snap-In Failures</u></a></li>
<li><a href="https://android-frp.techidaily.com/best-nokia-frp-bypass-guide-by-drfone-android/"><u>Best Nokia FRP Bypass Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-system-update-warnings/"><u>Disabling Windows System Update Warnings</u></a></li>
<li><a href="https://app-tips.techidaily.com/effortless-steps-to-save-whatsapp-chat-videos-across-iphone-android-devices-and-laptops/"><u>Effortless Steps to Save WhatsApp Chat Videos Across iPhone, Android Devices, and Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-disabled-status-on-windows-pcs/"><u>Fixing Grammarly Disabled Status on Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-sony-xperia-5-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/french-days-lalphabet-de-la-semaine/"><u>French Days: L’Alphabet De La Semaine</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-intel-unison-power-for-effective-pc-phone-calls/"><u>Harnessing Intel Unison Power for Effective PC Phone Calls</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-get-snapchat-on-mac-in-2024/"><u>How to Get Snapchat on Mac, In 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-elite-road-warriors-game-list/"><u>In 2024, Elite Road Warriors' Game List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-motion-clearer-captures/"><u>In 2024, Mastering Motion  Clearer Captures</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722902936905-m3-macbook-pro-unveiled-discover-pricing-details-launch-dates-and-full-tech-specs-now/"><u>M3 MacBook Pro Unveiled: Discover Pricing Details, Launch Dates & Full Tech Specs Now</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-and-search-features-in-windows-11-os/"><u>Mastering Highlight & Search Features in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-removing-false-device-notifications/"><u>Mastering the Art of Removing False Device Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-integrating-dynamic-desktop-backgrounds/"><u>Mastering Windows 11: Integrating Dynamic Desktop Backgrounds</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/navigating-the-process-of-voice-over-recording-in-media-production-for-2024/"><u>Navigating the Process of Voice-Over Recording in Media Production for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-rated-and-totally-free-the-best-online-video-editors-without-watermarks-for-2024/"><u>New Top-Rated and Totally Free The Best Online Video Editors without Watermarks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-computers-visual-experience-with-enhanced-vram/"><u>Optimize Your Computer's Visual Experience with Enhanced VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-makers-code-0x8007043c-issue/"><u>Overcoming Windows Media Maker's Code 0X8007043C Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-failures-restoring-java-on-windows-devices/"><u>Resolving Failures: Restoring Java on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-windows-11-update-combat-error-0x30017/"><u>Smoothing Windows 11 Update: Combat Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-instructions-fully-removing-wsl/"><u>Step-By-Step Instructions: Fully Removing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11-cannot-open-for-writing/"><u>Steps to Overcome Windows 11: Cannot Open For Writing</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-windows-based-counter-strike-play/"><u>Supercharge Windows-Based Counter-Strike Play</u></a></li>
<li><a href="https://win11.techidaily.com/tech-renaissance-atlasos-for-obsolete-systems/"><u>Tech Renaissance: AtlasOS for Obsolete Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-evolution-of-hand-tracking-systems-over-time-for-2024/"><u>The Evolution of Hand Tracking Systems Over Time for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-tracking-apps-to-track-apple-iphone-xr-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>Top 5 Tracking Apps to Track Apple iPhone XR without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1011s-aural-output-via-audacity/"><u>Troubleshooting Windows 10/11'S Aural Output, via Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-recommended-games-on-windows-11-screen/"><u>Turn Off Recommended Games on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unclouding-your-display-secrets-to-a-sharp-windows-11-screen/"><u>Unclouding Your Display: Secrets to a Sharp Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-assistance-best-free-tools-for-a-win11-revamp/"><u>Unmatched Assistance: Best Free Tools for a Win11 Revamp</u></a></li>
<li><a href="https://win11.techidaily.com/win1110-nat-transition-altering-type-effectively/"><u>Win11/10 NAT Transition: Altering Type Effectively</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>