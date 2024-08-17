---
title: "Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
date: 2024-08-16T00:41:46.642Z
updated: 2024-08-17T00:41:46.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
excerpt: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
keywords: AVOID Device Error Windows,Overcome In-Use Name Issue,Resolve Local Devices Error,Stop Windows In-Use Error,Fix In-Used Names on PC,Avoid Local Devices Errors,Correct Windows Usage Error
thumbnail: https://thmb.techidaily.com/57a07625ab9c873f1b8816cfe4ef02cf1a6f9bda4b7acdd0899c793b0d810b70.jpg
---

## Overcoming Windows' Local Devices: Avoid In-Use Names Errors

 The Local device name is already in use error is not particularly unusual. If you work with any type of network, even a local network, you are quite likely to encounter it at some point. Luckily, it is also usually easy to resolve.

 Here are the most common causes of this error, along with the most likely solutions.

## What Causes the Local Device Name Error?

 There can be a couple of possible causes of this error, but pinpointing the exact cause can be difficult. The most common are unassigned drive letters and incorrect file and printer sharing settings.

 It is also possible that a lack of space on the network server can result in this error appearing. You should check this possibility first. If lack of storage is the cause, none of the following solutions will make a difference.

 If the network server has ample space, you can move on to trying the methods below to solve the problem on your local device.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1 Enable File and Printer Sharing

[You should always keep your firewall enabled](https://www.makeuseof.com/tag/5-reasons-use-firewall/) , but it can sometimes interfere with file and printer sharing. This can lead to seeing the Local device name is already in use error. Luckily you can enable file and printer sharing easily in the firewall settings.

 If you're using a third-party firewall, refer to the documentation to find the setting. Here's how to enable file and printer sharing in the Microsoft Firewall.

1. Search for Control Panel using Windows Search, and click the search result to open it.
2. Click**System and Security > Windows Defender Firewall** to see the firewall settings.
3. In the left menu, click**Allow an app or feature through the firewall** and then click the**Change settings** button.  
![Windows firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-printer-sharing.jpg)
4. Scroll down to find**File and Printer Sharing** in the list, and click the**Public** checkbox.
5. Click**Ok** and restart your computer to apply the change.

 Occasionally, the file and printer sharing settings for the firewall can get reset after a major update. Just because you know you have enabled it in the past, it is worth checking again.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2 Remap the Network Drive With Command Prompt

 Windows will automatically assign a letter to your network drive. During network mapping, the assigned letters can become mixed and even be missing altogether. Remapping the network drive can fix this and prevent the error.

1. The best way to remap the network drive is through the Command Prompt. Search for**cmd** in Windows Search and select**Run as Administrator** .
2. At the cursor, type:**net use D /delete** . Replace**D** with the drive letter you want to delete. Then press**Enter** .  
![the remap network drive command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remap-network-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
3. Now remap the drive by typing:**net use D: \\\\server\\share /user:username password** . Replace the drive letter and user and username password with the relevant details.

 If this doesn't help, you may need to try reassigning the drive letters manually. The end result is similar, but sometimes remapping won't work when manually reassigning the drive path will work.

## 3 Re-assign Drive Letters

 Another common cause of this error is an incorrectly assigned drive letter. Reassigning a drive letter is easy, as long as you don't run into the Drive letter not available error.

1. Search for**Disk Management** using Windows Search, or right-click the Start Menu and select it from the hidden menu.
2. In Disk Management, find the partition or drive you want to change and right-click on it.
3. Select**Change Drive Letter and Paths** , and then click the**Add** button.  
![reassigning drive letter in disk management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reassign-drive-letter.jpg)
4. Click**Assign the following drive letter** and use the drop-down menu to choose a new letter for the partition or drive.

 If the drive letter you require is not available, it may already be being used on another drive or partition. It could also be associated with a removable drive that is not currently connected. If the A and B drive letters are available, and they often aren't, it is best not to use them. These letters are traditionally reserved for floppy drives and for use with old OS versions.

 Learn more about [why drive letters usually start with C on Windows](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4 Reinitialize the Computer Browser

 A less likely solution to this error, but one that does sometimes help, is reinitializing the browser. Browser settings can, in some cases, interfere with network drive settings. By stopping the browser and reinitializing it, those settings should be reverted.

1. Open Windows Search and type**cmd** . In the result, select**Command Prompt** and click**Run as Administrator** .
2. At the Command Prompt cursor, type:**net stop "Computer Browser"** and then press**Enter** .  
![reinitialize the browser on command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinitialize-browser.jpg)
3. When the command finishes executing, type:**net start "Computer Browser"** and press**Enter** .
4. You can now close the Registry Editor and check to see if the error persists.

 Reinitializing the browser is different from simply closing and reopening the browser window. It is a much more forceful solution to clearing any browser settings that may be in conflict.

 Learn how to optimize and get the most from your computer with these [essential Windows performance tips](https://www.makeuseof.com/tag/windows-10-faster-performance/) .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5 Delete the MountPoints Registry Key

 If none of the above solutions have fixed the problem, you can try deleting the MountPoints registry key as a last resort. This key stores data about USB and other removable drives. Deleting the key can sometimes resolve conflicts in drive letter assignments.

1. Deleting the MountPoints key shouldn't cause problems, but it is best to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case. Do this before you continue.
2. Open the Registry Editor by searching for it in Windows Search.
3. Navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer** .  
![delete mountpoints in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-mountpoints.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Look for the**MountPoints2** key in the right-hand panel, right-click on it and select**Delete** .
5. Close the Registry Editor and restart your computer.

 The MountPoint registry key will be regenerated after deleting and restarting. You can then check to see if this fixed the Local Device name is already in use error.

## Fixing Local Device Name Errors on Windows

 The Local device name is already in use error is not uncommon, and it can be frustrating. But by working through the solutions here, you will normally be able to fix it within a few minutes. Just be sure to check the remaining storage on the network server before you start digging deeper.


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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-image-enhancement-made-simple-how-to-inject-text-into-pictures-on-windowsmacos/"><u>[New] 2024 Approved  Image Enhancement Made Simple  How to Inject Text Into Pictures on Windows/MacOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exciting-journeys-in-samsungs-virtual-reality-games/"><u>[New] Exciting Journeys in Samsung's Virtual Reality Games</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-avoiding-obscured-games-fixes-for-obs-black-screen-issues/"><u>[New] In 2024, Avoiding Obscured Games  Fixes for OBS Black Screen Issues</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-crop-companion-chronicles-ultimate-agrigames-to-bond-with-buddies/"><u>[New] In 2024, Crop Companion Chronicles  Ultimate AgriGames to Bond with Buddies</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-instagram-incorporating-music-in-videos-and-stories-for-2024/"><u>[New] Mastering Instagram  Incorporating Music in Videos & Stories for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-privacy-first-securely-document-your-fb-video-conversations/"><u>[New] Privacy First  Securely Document Your FB Video Conversations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-keep-the-click-going-tips-for-automatically-backing-up-snapshots/"><u>[Updated] Keep the Click Going  Tips for Automatically Backing Up Snapshots</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-essential-vhs-illusions-transforming-video-artistry/"><u>2024 Approved  Essential VHS Illusions  Transforming Video Artistry</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-how-to-make-thumbnails/"><u>2024 Approved  How to Make Thumbnails</u></a></li>
<li><a href="https://extra-information.techidaily.com/acquire-excellent-images-at-no-cost-essential-strategies/"><u>Acquire Excellent Images at No Cost  Essential Strategies</u></a></li>
<li><a href="https://fox-info.techidaily.com/actionable-techniques-for-efficient-media-conversion-chains/"><u>Actionable Techniques for Efficient Media Conversion Chains</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-back-into-your-computers-print-command-wwinplusp/"><u>Breathe Life Back Into Your Computer's Print Command (WWin+P).</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-gaps-windows-11-legacy-computers-to-go-and-rufus-guide/"><u>Bridging Technology Gaps: Windows 11, Legacy Computers, To Go & Rufus Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-elevating-your-windows-experience-by-reclaiming-offscreen-panes/"><u>Bridging the Gap: Elevating Your Windows Experience by Reclaiming Offscreen Panes</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-unifying-your-pcs-with-files-through-aoemi/"><u>Bridging the Gap: Unifying Your PCs With Files Through AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-your-windows-11-interface-pointer/"><u>Brighten Up Your Windows 11 Interface Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-lifelayer-trashbin-on-the-windows-1011-environment/"><u>Building a Lifelayer Trashbin on the Windows 10/11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-directory-not-empty-warnings-solutions-for-error-x80070091/"><u>Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-restricted-windows-11-themes-with-skilled-registry-editing/"><u>Bypassing Restricted Windows 11 Themes with Skilled Registry Editing</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-security-warning-glitches/"><u>Bypassing Windows 11 Security Warning Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'.</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-to-locate-windows-app-habitats/"><u>Charting a Course to Locate Windows' App Habitats</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigating-permission-fail-in-installer-errors/"><u>Circumnavigating Permission Fail in Installer Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-differences-how-exes-stack-up-against-msis/"><u>Clarifying Differences: How EXEs Stack Up Against MSIs</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-installation-package-could-not-be-opens-errors-in-w10w11/"><u>Clearing Up 'Installation Package Could Not Be Opens' Errors in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-access-issues-top-5-fixes-for-access-denied-on-windows-11/"><u>Clearing Up Access Issues: Top 5 Fixes for Access Denied on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-missing-file-alert-in-win-11/"><u>Clearing Up Missing File Alert in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-path-unavailability-issue/"><u>Clearing Up WIN Path Unavailability Issue</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-way-for-startup-icons-visibility/"><u>Clearing Way for Startup Icons' Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/clipchamp-win11-install-issues-step-by-step-remedies/"><u>ClipChamp Win11 Install Issues: Step-by-Step Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/combatant-guide-for-the-windows-updater-error-0x80070003/"><u>Combatant Guide for the Windows Updater Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/combating-darkened-windows-display-during-remote-workspace-access/"><u>Combating Darkened Windows Display During Remote Workspace Access</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/crafting-innovative-fb-videos-unique-ad-creation-techniques-for-2024/"><u>Crafting Innovative FB Videos  Unique Ad Creation Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/develop-a-custom-speech-to-text-app-for-windows-step-by-step-guide/"><u>Develop a Custom Speech-to-Text App for Windows: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-pink-screens-an-essential-skill/"><u>Disabling Windows Pink Screens: An Essential Skill</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/examining-the-financial-success-strategies-of-t-series-on-youtube/"><u>Examining the Financial Success Strategies of T-Series on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/fixed-positioning-of-windows-tasks-a-guide/"><u>Fixed Positioning of Windows Tasks: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-portaudio-problems-in-audacity-for-windows-1111-devices/"><u>Fixing PortAudio Problems in Audacity for Windows 11/11 Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-galaxy-m34-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Galaxy M34.</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mediameld-editsuite/"><u>In 2024, MediaMeld EditSuite</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-premier-solutions-highest-rated-vimeo-downloaders/"><u>In 2024, Premier Solutions  Highest Rated Vimeo Downloaders</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-10-picture-frames-and-organizers/"><u>In 2024, Top 10 Picture Frames & Organizers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-movie-storage-space-needs-over-24-hours/"><u>In 2024, Understanding Movie Storage Space Needs Over 24 Hours</u></a></li>
<li><a href="https://win11.techidaily.com/mending-forgotten-windows-key-logon-message/"><u>Mending Forgotten Windows Key Logon Message</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-online-communication-facebook-to-youtube/"><u>Navigating the Giants of Online Communication – Facebook to YouTube</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-no-copyright-worries-top-public-domain-video-download-sites-for-2024/"><u>New No Copyright Worries Top Public Domain Video Download Sites for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-problems-smooth-your-pcs-cpu-flow-with-rm/"><u>Pinpointing Problems: Smooth Your PC's CPU Flow With RM</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-write-access-blockage-in-windows-11/"><u>Remedying Write Access Blockage in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/removing-recycle-icon-inactivity-issue-in-win11/"><u>Removing Recycle Icon Inactivity Issue in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-copy-and-paste-on-edge-within-windows-11s-app-guard/"><u>Unlock Copy & Paste on Edge Within Windows 11'S App Guard</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-solutions-for-windows-color-synchronization/"><u>Unveiling Solutions for Windows Color Synchronization</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-what-are-ai-tools/"><u>Updated In 2024, What Are AI Tools?</u></a></li>
</ul></div>
