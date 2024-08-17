---
title: "Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
date: 2024-08-16T00:11:44.505Z
updated: 2024-08-17T00:11:44.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
excerpt: "This Article Describes Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
keywords: WinDiskSpaceAnalysis,DrivespaceManagement,DiskUsageStrategies,EffectiveStorageUse,WindowsResourceTracking,SpaceOptimizationTips,DriveCapacityInsight
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-10-passport-photo-generator-download-print-for-free/"><u>[New] 10 Passport Photo Generator  Download, Print for Free</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-a-step-by-step-breakdown-creating-your-best-yt-shorts/"><u>[New] 2024 Approved  A Step-by-Step Breakdown  Creating Your Best YT Shorts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-precise-posting-schedules-a-guide-to-youtube-excellence/"><u>[New] 2024 Approved  Precise Posting Schedules  A Guide to YouTube Excellence</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-obscurity-to-star-in-3-simple-steps/"><u>[New] From Obscurity to Star in 3 Simple Steps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-how-to-create-animated-facebook-ads-with-high-roi-for-2024/"><u>[New] How to Create Animated Facebook Ads With High ROI for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-the-virtual-landscape-an-overview/"><u>[New] Navigating the Virtual Landscape  An Overview</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-top-5-methods-capturing-facebook-stories-on-devices/"><u>[Updated] 2024 Approved  Top 5 Methods  Capturing Facebook Stories on Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capture-stunning-imagesfilms-using-easy-shifts/"><u>[Updated] Capture Stunning Images/Films Using Easy Shifts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expert-endorsed-asmr-microphones-unveiled-for-2024/"><u>[Updated] Expert-Endorsed ASMR Microphones Unveiled for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-meditative-tunes-compilation-top-10-legal-streams/"><u>[Updated] Meditative Tunes Compilation - Top 10 Legal Streams</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-top-picks-free-fb-to-mp4-file-transformers/"><u>2024 Approved  Top Picks  Free FB to MP4 File Transformers</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-no-click-spaces-within-windows-11-interface/"><u>Combatting No-Click Spaces Within Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/concealed-commands-disguise-power-settings-in-start-screen/"><u>Concealed Commands: Disguise Power Settings in Start Screen</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-what-users-find-flawed-in-windows-11/"><u>Deciphering What Users Find Flawed in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elite-live-audience-connect/"><u>Elite Live Audience Connect</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-context-menu-choices-with-automatic-patch-information/"><u>Enriching Context Menu Choices with Automatic Patch Information</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-unravelled-enabling-windows-update/"><u>Error 2E Unravelled: Enabling Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-for-managing-users-in-command-prompt/"><u>Essential Tools for Managing Users in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-path-not-found-on-pc-systems/"><u>Fixing Path Not Found on PC Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-hp-deskjet-3520-software-and-drivers-free-download-now/"><u>Get Your HP Deskjet 3520 Software & Drivers – Free Download Now</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-xbox-games-access-error-in-windows-pcs/"><u>Guide to Correct Xbox Games Access Error in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-looks-like-youre-stranded-on-xbox-error/"><u>Guide to Overcoming 'Looks Like You're Stranded' On Xbox Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-google-chrome-from-creating-random-tabs/"><u>How To Prevent Google Chrome From Creating Random Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-motorola-moto-g-stylus-5g-2023-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Motorola Moto G Stylus 5G (2023) to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-samsung-galaxy-m34-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Samsung Galaxy M34 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-closer-look-at-the-m1-pro-versus-m1-max-in-apple-devices/"><u>In 2024, A Closer Look at the M1 Pro Versus M1 Max in Apple Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-ace-picks-top-ranked-gaming-screens-in-4k/"><u>In 2024, Ace Picks  Top-Ranked Gaming Screens in 4K</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-soundtrack-your-youtube-videos-7-free-audio-selections/"><u>In 2024, Soundtrack Your YouTube Videos  7 Free Audio Selections</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-top-mp4-tools-for-mac-users-maximizing-youtube-productions/"><u>In 2024, Top MP4 Tools For Mac Users  Maximizing YouTube Productions</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-github-desktop-on-windows-11-a-complete-guide/"><u>Mastering GitHub Desktop on Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-and-search-features-in-windows-11-os/"><u>Mastering Highlight & Search Features in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-writable-registry-for-hidden-themes/"><u>Mastering Windows 11' Writable Registry for Hidden Themes</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondlys-unique-language-learning-approach-my-experience-top-10-highlights/"><u>Mondly's Unique Language Learning Approach: My Experience (Top 10 Highlights)</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-guide-to-upgraded-audio-drivers-for-win1111/"><u>Quick Guide to Upgraded Audio Drivers for Win11/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-forcing-printer-deletion-in-win-1011/"><u>Quick Guide: Forcing Printer Deletion in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-google-nearby-sharing-service-in-windows/"><u>Re-Establishing Google Nearby Sharing Service in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/saved-the-day-downloading-youtube-playlists-made-easy-for-2024/"><u>Saved the Day! Downloading YouTube Playlists Made Easy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-discovery-of-software-installs-for-windows-users/"><u>Seamless Discovery of Software Installs for Windows Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/selecting-your-streaming-choice-podcast-or-video-platform-for-2024/"><u>Selecting Your Streaming Choice  Podcast or Video Platform for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-disk-differentiation-hdd-and-ssd-recognition-on-pcs/"><u>Simplifying Disk Differentiation: HDD & SSD Recognition on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-rectifying-file-history-missteps-in-windows-os/"><u>Steps for Rectifying File History Missteps in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-eliminating-restricted-admin-windows-alert/"><u>Strategies for Eliminating Restricted Admin Windows Alert</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-permission-on-windows-file-viewing/"><u>Strategies to Avoid 'No Permission' On Windows File Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/subnet-adjustment-for-win11-users/"><u>Subnet Adjustment for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-snap-open-apps-in-windows-11/"><u>Swiftly Snap Open Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-pc-performance-deficiencies-amidst-intel-errors/"><u>Tackling PC Performance Deficiencies Amidst Intel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-problem-code-0x800f0922/"><u>Tackling Windows Update Problem - Code 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-of-control-for-winapps-and-browsers/"><u>The Blueprint of Control for WinApps & Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-3gp-video-cutter-tutorial-2023-edition/"><u>The Ultimate 3GP Video Cutter Tutorial 2023 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-to-remove-microsoft-store-from-pcs/"><u>Three Methods to Remove Microsoft Store From PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-oppo-a2-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Oppo A2 Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-fixes-for-a-smoother-cs2-experience-tackling-lag-and-high-ping-issues-in-counter-strike-2/"><u>Ultimate Fixes for a Smoother CS2 Experience: Tackling Lag and High Ping Issues in Counter-Strike 2</u></a></li>
<li><a href="https://win11.techidaily.com/uninstall-simplified-top-methods-for-windows-11-users-111-chars/"><u>Uninstall Simplified: Top Methods for Windows 11 Users (111 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Vivo Y28 5G? | Dr.fone</u></a></li>
</ul></div>
