---
title: How to Show or Hide Folders in This PC on Windows 11
date: 2024-08-16T00:46:06.673Z
updated: 2024-08-17T00:46:06.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Show or Hide Folders in This PC on Windows 11
excerpt: This Article Describes How to Show or Hide Folders in This PC on Windows 11
keywords: Win11 Folder Visibility Control,Change Folder Display Option,Hide/Show PC Folders,Folder Display Settings Windows,Manage Folder Visibility,Adjust File Explorer Views,Configure Windows 11 Folder Showing
thumbnail: https://thmb.techidaily.com/fe5fb2202d31ead27c9d026582d857fbe91d9882cc06bf2431577eb2dc90df03.jpg
---

## How to Show or Hide Folders in This PC on Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://youtube-videos.techidaily.com/new-customizing-your-channel-icon-banner-and-thumbnail-ideas/"><u>[New] Customizing Your Channel  Icon, Banner & Thumbnail Ideas</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-break-through-the-crowd-key-youtube-seo-strategies-to-rank-high/"><u>[New] In 2024, Break Through the Crowd  Key YouTube SEO Strategies to Rank High</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-maximizing-money-smart-tactics-for-video-monetization/"><u>[New] Maximizing Money  Smart Tactics for Video Monetization</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-ace-your-content-strategies-to-skyrocket-video-popularity/"><u>[Updated] Ace Your Content  Strategies to Skyrocket Video Popularity</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-asmr-viewers-essentials-explained-for-2024/"><u>[Updated] ASMR Viewers' Essentials Explained for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-crafting-compelling-freefire-vids-with-strategy-guide-for-2024/"><u>[Updated] Crafting Compelling FreeFire Vids with Strategy Guide for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-leading-tips-for-mute-video-capture-for-2024/"><u>[Updated] Leading Tips for Mute Video Capture for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-solo-strategies-making-your-podcast-sensational/"><u>2024 Approved  Solo Strategies  Making Your Podcast Sensational</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comparative-review-apple-watch-series-9-versus-fitbit-charge-6/"><u>Comparative Review: Apple Watch Series 9 Versus Fitbit Charge 6</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-measures-for-disk-read-failure-windows/"><u>Corrective Measures for Disk Read Failure Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-taskmanager-stays-top-focused/"><u>Ensuring TaskManager Stays Top-Focused</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disjointed-sticky-note-behavior-on-w11-system/"><u>Fixing Disjointed Sticky Note Behavior on W11 System</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-manipulate-cover-page-editor-in-win11/"><u>How to Access and Manipulate Cover Page Editor in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-implement-windows-rollback-mechanism-via-system-restore/"><u>How to Effectively Implement Windows' Rollback Mechanism via System Restore</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-outlook-failed-error-in-windows/"><u>How to Rectify the 'Outlook Failed' Error in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-honor-magic-6-lite-lock-screen-password-by-drfone-android/"><u>How to Reset your Honor Magic 6 Lite Lock Screen Password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-safely-and-quickly-upgrade-your-surface-computers-software/"><u>How to Safely and Quickly Upgrade Your Surface Computers' Software</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xr-to-other-iphone-12-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XR To Other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-your-apple-iphone-14-plus-passcode-4-easy-methods-with-or-without-itunes-drfone-by-drfone-ios/"><u>How to Unlock Your Apple iPhone 14 Plus Passcode 4 Easy Methods (With or Without iTunes) | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-becoming-an-expert-at-using-zoom-for-your-windows-pc-win10/"><u>In 2024, Becoming an Expert at Using Zoom for Your Windows PC (Win10)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-proper-techniques-for-easy-iphone-screen-recording/"><u>In 2024, Proper Techniques for Easy iPhone Screen Recording</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastery-guide-to-flawless-srt-file-construction/"><u>Mastery Guide to Flawless SRT File Construction</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-pitfalls-how-to-tell-if-a-friend-request-is-real-or-fake/"><u>Navigating the Pitfalls: How to Tell if a Friend Request Is Real or Fake</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-issues-with-5ghz-wireless-networks/"><u>Navigating Windows 11 Issues with 5GHz Wireless Networks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-flip-your-tiktok-videos-a-comprehensive-guide-to-reversing-clips/"><u>New In 2024, Flip Your TikTok Videos A Comprehensive Guide to Reversing Clips</u></a></li>
<li><a href="https://win11.techidaily.com/onedrives-new-home-a-guide-for-windows-11-users/"><u>OneDrive's New Home: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-copypaste-failures-in-windows-11/"><u>Preventing Copy/Paste Failures in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proposing-a-new-vision-for-windows-11s-taskbar-functionality/"><u>Proposing a New Vision for Windows 11'S Taskbar Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solutions-for-common-cc-problems-on-win11/"><u>Quick Solutions for Common CC Problems on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-windows-1011s-faulty-recycle-bin-error/"><u>Rejuvenating Windows 10/11'S Faulty Recycle Bin Error</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-affordable-windows-10-a-comprehensible-guide/"><u>Secrets to Affordable Windows 10: A Comprehensible Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-healing-defective-windows-registry-entries/"><u>Step-by-Step: Healing Defective Windows Registry Entries</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-programs-with-context-menu-additions/"><u>Streamlining Programs with Context Menu Additions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-tecno-camon-20-pro-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Tecno Camon 20 Pro 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-artistic-potential-of-windows-11-comics/"><u>Unlock the Artistic Potential of Windows 11 Comics</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11s-hidden-treasures-with-our-6-secrets-to-success/"><u>Unlock Windows 11'S Hidden Treasures with Our 6 Secrets to Success</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-translate-audiovideo-content-from-spanish-to-english-and-vice-versa/"><u>Updated 2024 Approved Translate Audio/Video Content From Spanish to English and Vice Versa</u></a></li>
<li><a href="https://win11.techidaily.com/which-out-of-intel-unison-or-phone-link-is-superior/"><u>Which Out of Intel Unison or Phone Link Is Superior?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-evolution-retro-revamped-to-the-era-of-98/"><u>Windows Evolution Retro-Revamped: To the Era of 98</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-cpu-state-showcase-at-peak-levels/"><u>Windows Guide: CPU State Showcase at Peak Levels</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-warhammer-40k-boltgun-fix-pc-stutter-issues/"><u>Winning at Warhammer 40K Boltgun: Fix PC Stutter Issues</u></a></li>
</ul></div>
