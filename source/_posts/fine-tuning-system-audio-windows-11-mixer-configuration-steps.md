---
title: "Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps"
date: 2024-08-16T00:06:50.704Z
updated: 2024-08-17T00:06:50.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps"
excerpt: "This Article Describes Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps"
keywords: Windows Audio Tuning,Set W11 Sound,Mixer Config Steps,System Audio Optimize,Win11 Sound Settings,Fine-Tune Windows Sounds,Adjust W11 Audio Levels
thumbnail: https://thmb.techidaily.com/f65801f01aff4d3373b4cf2db5d1bc7ed704b50a070459838ec79267fdebcd19.jpg
---

## Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.


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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-navigating-the-landscape-of-facebook-ad-effectiveness/"><u>[Updated] In 2024, Navigating the Landscape of Facebook Ad Effectiveness</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-essential-ps-know-how-color-enhancement-basics/"><u>2024 Approved  Essential PS Know-How  Color Enhancement Basics</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-leading-tech-essential-video-recorders-of-the-net/"><u>2024 Approved  Leading Tech  Essential Video Recorders of the Net</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-error-0x80070194-with-onedrive/"><u>Addressing the Error 0X80070194 with OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-save-configuration-errors-in-pubg/"><u>Correcting Save Configuration Errors in PUBG</u></a></li>
<li><a href="https://extra-resources.techidaily.com/deciphering-concealed-views-on-video-content/"><u>Deciphering Concealed Views on Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-geforce-error-x0001-on-windows-pcs/"><u>Fixing Common GeForce Error X0001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-xiaomi-redmi-note-13-proplus-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Xiaomi Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-infinix-smart-8-plus-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Infinix Smart 8 Plus PC | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Additional Tips About Sinnoh Stone For Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-efficient-tagging-techniques-to-boost-your-youtube-traffic/"><u>In 2024, Efficient Tagging Techniques to Boost Your Youtube Traffic</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-make-a-creative-split-screen-video-for-youtube/"><u>In 2024, How to Make a Creative Split-Screen Video for YouTube?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-unlocking-full-potential-with-facebook-interaction/"><u>In 2024, Unlocking Full Potential with Facebook Interaction</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-techniques-for-overcoming-media-app-issues-in-win11/"><u>Methodical Techniques for Overcoming Media App Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-it-all-the-top-7-ways-to-use-windows-11-effectively/"><u>Optimize It All: The Top 7 Ways to Use Windows 11 Effectively</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-deleted-iphone-se-2020-whatsapp-attachments-on-mac-and-windows-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Recover Deleted iPhone SE (2020) WhatsApp Attachments on Mac and Windows | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-desktop-experience-with-winbubbles-best-practices/"><u>Tailor Your Desktop Experience with WinBubble's Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/troubleshoot-facebook-live-pause-strategies-for-smooth-broadcasts/"><u>Troubleshoot Facebook Live Pause  Strategies for Smooth Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/winxpxo11-how-to-prevent-closed-folders-double-clicked/"><u>WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked</u></a></li>
</ul></div>
