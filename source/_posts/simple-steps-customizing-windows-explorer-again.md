---
title: "Simple Steps: Customizing Windows Explorer Again"
date: 2024-08-23T06:07:07.357Z
updated: 2024-08-24T06:07:07.357Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simple Steps: Customizing Windows Explorer Again"
excerpt: "This Article Describes Simple Steps: Customizing Windows Explorer Again"
keywords: Customize WinExplorer,Personalize File Explorer,Windows Explorer Tips,Explore Windows Settings,Optimize File Explorer,Adjust WinExplorer Views,Enhance File Explorer UI
thumbnail: https://thmb.techidaily.com/720039bdcfeba97eefefa9824f21f9715183b78c763bbf782b71c474fcdd45b6.jpg
---

## Simple Steps: Customizing Windows Explorer Again

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-mastering-the-art-of-attracting-more-youtube-admirers/"><u>[New] 2024 Approved  Mastering the Art of Attracting More YouTube Admirers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-creating-a-backup-securing-your-fb-messenger-records-for-2024/"><u>[New] Creating a Backup  Securing Your FB Messenger Records for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-power-of-words-in-viral-videos-top-20-tiktok-caption-picks/"><u>[New] In 2024, The Power of Words in Viral Videos  Top 20 TikTok Caption Picks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovating-with-iphone-for-complete-360-video-capture/"><u>[New] Innovating with iPhone for Complete 360 Video Capture</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-unleash-vrecorder-download-steps/"><u>[Updated] In 2024, Unleash VRecorder  Download Steps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-insiders-guide-to-recording-slideshows/"><u>[Updated] The Insider's Guide to Recording Slideshows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-unlocking-youtube-success-with-the-right-networking-choice/"><u>[Updated] Unlocking YouTube Success with the Right Networking Choice</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-ultimate-guide-for-ps3-playback-recording/"><u>2024 Approved  The Ultimate Guide for PS3 Playback Recording</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-optical-character-recognition-ocr-understanding-image-based-text-capture-with-copernic-software/"><u>A Deep Dive Into Optical Character Recognition (OCR): Understanding Image-Based Text Capture with Copernic Software</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-unwanted-edge-shortcut-popups/"><u>Conquering Unwanted Edge Shortcut Popups</u></a></li>
<li><a href="https://tech-hub.techidaily.com/create-professional-slideshows-effortlessly-using-the-best-ai-presentation-generators/"><u>Create Professional Slideshows Effortlessly Using the Best AI Presentation Generators</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-leverage-copernic-for-efficient-cloud-storage-searches/"><u>Discover How to Leverage Copernic for Efficient Cloud Storage Searches</u></a></li>
<li><a href="https://win11.techidaily.com/easily-activate-snipping-tool-in-modern-windows-os/"><u>Easily Activate Snipping Tool in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connection-integrate-your-pc-and-phone-through-flow/"><u>Effortless Connection - Integrate Your PC & Phone Through Flow</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-lsassexe-identification-failure-on-pcs/"><u>Eliminating lsass.exe Identification Failure on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-comprehensibility-with-obsidians-artistic-note-taking/"><u>Enhancing Comprehensibility with Obsidian's Artistic Note-Taking</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-performance-for-faster-steam-content-loading/"><u>Enhancing PC Performance for Faster Steam Content Loading</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-fixing-two-users-ms-login-conflicts/"><u>Expert Tips: Fixing Two Users' MS Login Conflicts</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-biggest-networking-sites-facebook-twitter-instagram-and-youtube/"><u>Exploring the Biggest Networking Sites: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/1723809008305-find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search!</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-zerox-error-code-0x80049dd3-and-enhance-typing/"><u>Fix Windows 11'S Zerox Error (Code: 0X80049DD3) and Enhance Typing</u></a></li>
<li><a href="https://win11.techidaily.com/four-hacks-stopping-automatic-windows-and-office-updates/"><u>Four Hacks: Stopping Automatic Windows & Office Updates</u></a></li>
<li><a href="https://win11.techidaily.com/go-direct-to-linux-with-no-wsl/"><u>Go Direct to Linux with No WSL</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-you-are-not-connected-to-any-networks-on-windows/"><u>How to Fix You Are Not Connected to Any Networks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-wsl-error-4294967295-on-windows/"><u>How to Resolve the WSL Error 4294967295 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-switch-windows-11-search-from-a-text-box-back/"><u>How to Switch Windows 11 Search From a Text Box Back</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-headset-havens-weighing-google-cardboard-against-samsung-gear/"><u>In 2024, Headset Havens  Weighing Google Cardboard Against Samsung Gear</u></a></li>
<li><a href="https://win11.techidaily.com/learn-your-computers-identity-a-quick-guide-with-6-methods/"><u>Learn Your Computer’s Identity: A Quick Guide with 6 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-email-management-9-key-upgrades-in-windows-outlook/"><u>Mastering Email Management: 9 Key Upgrades in Windows' Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/1723809006534-mastering-social-media-growth-with-seamless-menu-expand-functions-on-fb-li-yt-top-level-navigation-essentials/"><u>Mastering Social Media Growth with Seamless Menu Expand Functions on FB, LI, YT - Top-Level Navigation Essentials!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-1011-gpu-drivers-with-precision/"><u>Navigating Windows 10/11 GPU Drivers with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-system-streamlined-windows-autoupdate-and-driver-change/"><u>Optimize System: Streamlined Windows Autoupdate & Driver Change</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/precision-voice-transformation-through-morphvox/"><u>Precision Voice Transformation Through MorphVOX</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-world-effortless-windows-factory-techniques/"><u>Reboot Your World: Effortless Windows Factory Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-cut-and-paste-in-windows-11/"><u>Repairing Non-Functional Cut & Paste in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/savings-saved-the-hidden-dangers-in-cheap-windows-activation-codes/"><u>Savings, Saved? The Hidden Dangers in Cheap Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-workflow-windows-custom-key-combinations/"><u>Speed Up Workflow: Windows Custom Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-document-discovery-using-copernics-expert-text-search-features-for-professionals/"><u>Streamline Document Discovery Using Copernic's Expert Text Search Features for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflow-with-outlook-preview-on-windows-11/"><u>Streamlining Workflow with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-comedy-codex-a-practical-tutorial-for-gif-creation-for-2024/"><u>The Comedy Codex  A Practical Tutorial for GIF Creation for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/top-techniques-and-gadgets-for-homely-french-learning/"><u>Top Techniques & Gadgets for Homely French Learning</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-to-virtualbox-70-on-windows-11-your-ultimate-walkthrough/"><u>Transitioning to VirtualBox 7.0 on Windows 11 – Your Ultimate Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/win-fixes-overcoming-firefox-page-load-issues-in-windows/"><u>Win Fixes: Overcoming Firefox Page Load Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-strategies-accelerating-valorants-sluggish-downloads/"><u>Win Strategies: Accelerating Valorant's Sluggish Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/windows-print-admin-a-user-friendly-approach/"><u>Windows Print Admin: A User-Friendly Approach</u></a></li>
</ul></div>
