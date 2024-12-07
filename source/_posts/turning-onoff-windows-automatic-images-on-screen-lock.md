---
title: Turning On/Off Windows' Automatic Images on Screen Lock
date: 2024-12-03T18:18:39.607Z
updated: 2024-12-06T16:37:13.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turning On/Off Windows' Automatic Images on Screen Lock
excerpt: This Article Describes Turning On/Off Windows' Automatic Images on Screen Lock
keywords: Screen Image Auto Lock,Turn Off Auto Photos,Disable Window Photo,Stop Windows Screenshot,Halt Auto Screen Capture,Inhibit Picture Auto-Display,Deactivate Locked Image
thumbnail: https://thmb.techidaily.com/8d1de21c666386207e0a2c0896dc0647ebc82a413cfdd6aa282a235213b145ee.jpg
---

## Turning On/Off Windows' Automatic Images on Screen Lock

 With the Windows Spotlight feature enabled, your lock screen gets updated every day with spectacular images from Bing. That said, not everyone may like seeing a different lock screen background daily.

 In any case, it’s fairly simple to enable or disable spotlight images on your Windows lock screen. Here's how you can go about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable or Disable Windows Spotlight Images Using the Settings App

 The Settings app in Windows gives you several options for[customizing the lock screen](https://www.makeuseof.com/windows-11-customize-lock-screen/) , including the ability to enable or disable spotlight images. It is also the quickest method for turning spotlight images on or off on Windows. Here are the steps you can follow.

1. Right-click on the**Start icon** and select**Settings** from the list.
2. Select**Personalization** from the left pane.
3. Click on**Lock screen** .
4. Click the drop-down menu next to**Personalize your lock screen** and select**Windows spotlight** to enable the feature. If you want to disable spotlight images, select**Picture** or**Slideshow** instead.  
![Enable or Disable Spotlight Images on Lock Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-spotlight-images-on-lock-screen-using-settings-app.jpg)

## 2\. How to Enable or Disable Windows Spotlight Images via the Group Policy Editor

 The Group Policy Editor is a useful tool for implementing system-level changes on Windows. If you have the Education, Enterprise, or Professional edition of Windows, you can enable or disable spotlight images on the lock screen via the Group Policy Editor. If you use Windows Home, however, check our guide on[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 To enable or disable Windows spotlight images on your lock screen, use these steps:

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Cloud Content** .
4. Double-click the**Turn off all Windows spotlight features** policy in the right pane.
5. Select**Enabled** to get spotlight images on the lock screen. If you want to turn them off, select**Not Configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
![Enable or Disable Spotlight Images on Lock Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-spotlight-images-on-lock-screen-using-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Enable or Disable Windows Spotlight Images With the Registry Editor

 Registry Editor in Windows provides yet another way to enable or disable spotlight images on the lock screen. However, this method may not be suitable for everyone, especially those who are not familiar with the Registry Editor.

 If you decide to use this method, make sure you[back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or[create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding. Once you’ve done that, use the following steps to enable or disable spotlight images via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows > CloudContent** .
5. Right-click on the**CloudContent** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DisableWindowsSpotlightFeatures** .
6. Double-click on the newly created DWORD to edit it.
7. Enter**1** in the Value data field to disable spotlight images. If you want to enable them, enter**0** instead.
8. Click**OK** .  
![Enable or Disable Spotlight Images on Lock Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-spotlight-images-on-lock-screen-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Exit the Registry Editor and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get a New View Every Day With Windows Spotlight

 As we just saw, you can enable or disable Windows spotlight images on the lock screen via the Settings app, Group Policy Editor, or Registry Editor. No matter which method you opt for, turning Windows spotlight images on or off should not take long.

 Since Windows stores all the spotlight images locally on your computer, you can even save them and use them as your desktop wallpaper if you want.

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
<li><a href="https://twitter-videos.techidaily.com/new-how-to-share-a-tiktok-video-on-twitter-in-2024/"><u>[New] How to Share A Tiktok Video on Twitter, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-on-clearing-windows-arp-caches/"><u>Comprehensive Guide on Clearing Windows ARP Caches</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-mechanics-of-mouseclicklock-in-windows-systems/"><u>Deciphering the Mechanics of MouseClickLock in Windows Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-adobe-media-encoder-version-2402-freeware/"><u>Download Adobe Media Encoder Version 24.0.2 - Freeware</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016310671-fix-the-silent-problem-in-jabra-g435-wireless-earbuds-comprehensive-fixes-here/"><u>Fix the Silent Problem in Jabra G435 Wireless Earbuds – Comprehensive Fixes Here!</u></a></li>
<li><a href="https://win11.techidaily.com/fix-visual-issues-windows-11-drivers-guide/"><u>Fix Visual Issues: Windows 11 Drivers Guide</u></a></li>
<li><a href="https://win11.techidaily.com/free-windows-game-successful-ocm-team-management/"><u>Free Windows Game: Successful OCM Team Management</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/getting-latest-drivers-for-hps-z440-professional-desktop-system/"><u>Getting Latest Drivers for HP's Z440 Professional Desktop System</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-and-install-the-official-epson-v500-scanner-drivers/"><u>How to Obtain and Install the Official Epson V500 Scanner Drivers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-s23plus-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy S23+ Lock Screen Password?</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/maitrisez-votre-recepitule-video-avec-handbrake-guide-etape-par-etape-pour-desactiver-lautoresizing-et-recadrer-en-mode-manuel/"><u>Maîtrisez Votre Récépitulé Vidéo Avec HandBrake : Guide Étape Par Étape Pour Désactiver L'autoresizing Et Recadrer en Mode Manuel</u></a></li>
<li><a href="https://win11.techidaily.com/meeting-mastery-how-to-ensure-your-techs-performance-windows/"><u>Meeting Mastery: How to Ensure Your Tech's Performance (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-how-to-boot-your-windows-11-pc-into-safe-mode/"><u>Quick Fixes: How to Boot Your Windows 11 PC Into Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-default-functionality-to-windows-11-search/"><u>Restoring Default Functionality to Windows 11 Search</u></a></li>
</ul></div>

