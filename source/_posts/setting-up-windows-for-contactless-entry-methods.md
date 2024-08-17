---
title: Setting Up Windows For Contactless Entry Methods
date: 2024-08-15T23:46:11.332Z
updated: 2024-08-16T23:46:11.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Up Windows For Contactless Entry Methods
excerpt: This Article Describes Setting Up Windows For Contactless Entry Methods
keywords: TouchEntryWindowsSetup,ContactlessWindowsTech,WindowsCtAccessMethod,EnableTouchWindows,CtEntryWindowsConfig,WindowsContactlessMode,ConfigWindowsForCtEntry
thumbnail: https://thmb.techidaily.com/74113c2d83645a48c9d2ad195371cc6a07bee43db8bd23e967a3613c122b6663.jpg
---

## Setting Up Windows For Contactless Entry Methods

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagram-savvy-top-5-methods-for-building-a-thriving-influencer-profile/"><u>[New] 2024 Approved  Instagram Savvy  Top 5 Methods for Building a Thriving Influencer Profile</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-6-effortless-steps-to-add-social-media-live-content-online/"><u>[New] 6 Effortless Steps to Add Social Media Live Content Online</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-elevate-your-instagram-feed-vertical-video-edits-in-fcpx-for-2024/"><u>[New] Elevate Your Instagram Feed  Vertical Video Edits in FCPX for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-lowering-volume-steps-in-logic-pro-audio-editing/"><u>[New] Lowering Volume Steps in Logic Pro Audio Editing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-zoom-in-on-success-screenshots-made-simple-by-ezvide-tech-for-2024/"><u>[New] Zoom In on Success  Screenshots Made Simple by EZvide Tech for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-peak-computing-powerhouses-the-best-on-the-market/"><u>[Updated] Peak Computing Powerhouses - The Best On the Market</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-say-goodbye-to-vertical-and-horizontal-bars-in-youtube-movies-for-2024/"><u>[Updated] Say Goodbye to Vertical and Horizontal Bars in YouTube Movies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-sky-surfing-in-hd-with-the-yuneec-drone-review/"><u>[Updated] Sky Surfing in HD with the Yuneec Drone Review</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-future-is-in-your-cloud-price-rankings-and-bargains-2024/"><u>[Updated] The Future Is in Your Cloud  Price Rankings & Bargains 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-unlock-creative-potential-with-10-best-backdrop-modification-software-for-2024/"><u>[Updated] Unlock Creative Potential with 10 Best Backdrop Modification Software for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-music-video-shoot-estimated-financial-outlay/"><u>2024 Approved  Music Video Shoot - Estimated Financial Outlay</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-science-behind-auto-hdr-and-cameras-ai-powered-shooting-modes/"><u>2024 Approved  The Science Behind Auto HDR and Camera's AI-Powered Shooting Modes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-unblemished-visuals-buying-high-quality-images/"><u>2024 Approved  Unblemished Visuals  Buying High-Quality Images</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-take-notes-on-windows-11-without-downloading-software/"><u>5 Ways to Take Notes on Windows 11 Without Downloading Software</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/achieve-optimal-wellbeing-formulating-and-pursuing-personal-health-ambitions-using-chatgpt/"><u>Achieve Optimal Wellbeing: Formulating and Pursuing Personal Health Ambitions Using ChatGPT</u></a></li>
<li><a href="https://extra-information.techidaily.com/boost-your-capacity-20-premier-gratis-cloud-storage-options/"><u>Boost Your Capacity  20 Premier Gratis Cloud Storage Options</u></a></li>
<li><a href="https://win11.techidaily.com/close-all-easy-as-1-2-3-windows-multi-app-command/"><u>Close All, Easy as 1-2-3: Windows Multi-App Command</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-eliminating-wsl-from-win-11-pcs/"><u>Comprehensive Guide: Eliminating WSL From Win 11 PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/convert-any-instagram-video-in-minutes-best-free-tools-windowsmac-for-2024/"><u>Convert Any Instagram Video in Minutes  Best Free Tools (Windows/Mac) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-gaps-in-file-explorer-indexing/"><u>Correcting Gaps in File Explorer Indexing</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-install-access-denied-windows-setup-issue/"><u>Correcting Install Access Denied Windows Setup Issue</u></a></li>
<li><a href="https://win11.techidaily.com/demonstrating-the-power-of-powershell-removing-restrictions-on-windows/"><u>Demonstrating the Power of PowerShell: Removing Restrictions on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/digital-detox-how-to-turn-off-youtube-on-computers-and-phones/"><u>Digital Detox  How to Turn Off Youtube on Computers and Phones</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-window-11s-secure-browsing-graphically/"><u>Enhancing Window 11'S Secure Browsing Graphically</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-for-captivating-images-and-memorable-slideshows-in-win11s-photography-platform/"><u>Expert Insights for Captivating Images and Memorable Slideshows in Win11's Photography Platform</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-system-audio-windows-11-mixer-configuration-steps/"><u>Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-xiaomi-14-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-error-0x7e1-on-win1011/"><u>How to Reverse Error 0X7E1 on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-file-fixation-powerpoint-saves-crisis-solutions-win11/"><u>Immediate File Fixation: PowerPoint Saves Crisis, Solutions WIN11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-gecata-game-recorder-review/"><u>In 2024, Gecata Game Recorder Review</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-win11s-ultimate-screen-recording-kit/"><u>In 2024, Win11's Ultimate Screen Recording Kit</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/must-have-server-enclosures-and-racks-industry-experts-choice/"><u>Must-Have Server Enclosures & Racks - Industry Experts' Choice</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-essential-steps-for-using-dev-drive/"><u>Navigating Windows 11: Essential Steps for Using Dev Drive</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-how-to-translate-video-from-japanese-to-english-online-in-2024/"><u>New How To Translate Video From Japanese to English Online, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-credential-vault-access-blocks/"><u>Overcome Credential Vault Access Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/phoenix-rise-revive-gaming-pcs-with-atlasos/"><u>Phoenix Rise: Revive Gaming PCs with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-hacked-no-more-winning-encryption-tools-ranked-149-chars/"><u>Privacy Hacked No More: Winning Encryption Tools Ranked (149 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-the-heart-of-windows-11-system32/"><u>Probing Into the Heart of Windows 11: System32</u></a></li>
<li><a href="https://win11.techidaily.com/recording-games-simply-mastering-screen-captures-with-intel-tools/"><u>Recording Games Simply: Mastering Screen Captures with Intel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hibernation-a-windows-users-guide/"><u>Resurrecting Hibernation: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pc-display-interactive-and-lively-windows-11-walls/"><u>Revitalize Your PC Display: Interactive and Lively Windows 11 Walls</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-operation-warhammer-40k-boltgun-windows-stutter-fixes/"><u>Smooth Operation Warhammer 40K Boltgun: Windows Stutter Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-trembling-cursor-a-guide-to-windows/"><u>Stop the Trembling Cursor: A Guide to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-experience-microsoft-store-file-types-msixbundle/"><u>Streamline Your Experience: Microsoft Store File Types (MSixBundle)</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-increase-win11-icons-size/"><u>Techniques to Increase Win11 Icons Size</u></a></li>
<li><a href="https://facebook.techidaily.com/the-art-of-unseen-discussions-on-social-platforms/"><u>The Art of Unseen Discussions on Social Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-windows-photo-management-tools-an-essential-guide/"><u>Top 7 Windows Photo Management Tools: An Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-glitches-solutions-guide/"><u>Unraveling WINDOWS 11 Glitches: Solutions Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unveiling-the-secrets-to-youtube-success-titles-and-tags/"><u>Unveiling the Secrets to Youtube Success  Titles & Tags</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-powerpoint-wont-record-audio-while-recording-the-screen-on-windows/"><u>What to Do if PowerPoint Won’t Record Audio While Recording the Screen on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/win-10s-best-recording-software-10-picks-for-2024/"><u>Win 10'S Best Recording Software - 10 Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-deactivating-nvidias-visual-effects/"><u>Windows Guide: Deactivating NVIDIA's Visual Effects</u></a></li>
</ul></div>
