---
title: "Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
date: 2024-08-15T23:54:18.209Z
updated: 2024-08-16T23:54:18.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
excerpt: "This Article Describes Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
keywords: DropOneDriveIcon,DeleteDriveSymbol,RemoveDriveInExplorer,EliminateOneDriveEye,ClearOneDriveFromIE,EradicateDriveIExplore,DitchDriveSymbolIcon
thumbnail: https://thmb.techidaily.com/8b86753cae048297a750321083f2087f1622c0cfcb3cab69136de042dba1a8be.jpg
---

## Confronting Clutter: Eliminate OneDrive Symbol From Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://tiktok-clips.techidaily.com/new-giggle-gallery-a-collection-of-the-funniest-tiktok-videos-and-jokes/"><u>[New] Giggle Gallery  A Collection of the Funniest TikTok Videos and Jokes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-deciphering-the-platforms-a-side-by-side-analysis-of-triller-and-tiktok-max-156-chars/"><u>[New] In 2024, Deciphering the Platforms  A Side-by-Side Analysis of Triller and TikTok (Max 156 Chars)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-compreenasive-breakdown-how-to-use-microsofts-movie-maker-on-w11/"><u>[New] The Compreenasive Breakdown  How to Use Microsoft's Movie Maker on W11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-transforming-your-profile-into-a-showstopper-for-2024/"><u>[New] Transforming Your Profile Into a Showstopper for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-optimize-video-quality-on-youtube-with-size-settings-for-2024/"><u>[Updated] How to Optimize Video Quality on YouTube with Size Settings for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-visual-vocabulary-complimentary-youtube-art-tools/"><u>[Updated] Visual Vocabulary  Complimentary YouTube Art Tools</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-render-images-with-radial-light-diffusion-technique/"><u>2024 Approved  Render Images with Radial Light Diffusion Technique</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-oculus-setup-fails-windows-1110-strategies/"><u>Addressing Oculus Setup Fails: Windows 11/10 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-antivirus-overkill-in-your-windows-os/"><u>Avoiding Antivirus Overkill in Your Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-computer-writes-on-new-program-placement/"><u>Deciphering Your Computer' Writes on New Program Placement</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-stranded-status-error-on-xbox-app-for-pcs/"><u>Eliminating Stranded Status Error on Xbox App for PCs</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-constant-crash-of-microsoft-teams-assistant-on-windows/"><u>Fixing the Constant Crash of Microsoft Teams Assistant on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-windows-media-failures/"><u>How to Correct Windows Media Failures</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-metaverse-maps-drawn-understanding-through-6-vivid-scenarios/"><u>In 2024, Metaverse Maps Drawn  Understanding Through 6 Vivid Scenarios</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-systems-to-win11-upgrade-essentials/"><u>Legacy Systems to Win11 Upgrade Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-tiworkerexe-cpu-consumption-windows-wise/"><u>Lowering TiWorker.exe CPU Consumption Windows-Wise</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-visibility-learn-to-trace-shared-social-media-footprints-in-facebook/"><u>Mastering Visibility: Learn to Trace Shared Social Media Footprints in Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-pc-load-tips-for-managing-multimedia-tasks-on-windows/"><u>Minimize PC Load: Tips for Managing Multimedia Tasks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-settings-for-better-device-control/"><u>Navigating Windows 11 Settings for Better Device Control</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-and-remedying-code-error-0x80072f8f/"><u>Preventing and Remedying Code Error 0X80072f8f</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-remote-work-fast-and-memory-friendly/"><u>Revitalizing Remote Work: Fast and Memory-Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-data-effective-use-of-powertoys-lockmaster/"><u>Securing Your Data: Effective Use of PowerToys Lockmaster</u></a></li>
<li><a href="https://win11.techidaily.com/set-windows-clock-without-automatic-regional-switching/"><u>Set Windows Clock Without Automatic Regional Switching</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-incorporating-copy-and-move-commands-in-win-11/"><u>Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-windows-update-defeat-error-0x800736cc/"><u>Swiftly Resolving Windows Update: Defeat Error 0X800736CC</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-mystery-of-the-non-launching-app-ascent-a-resolved-issue/"><u>The Mystery of the Non-Launching App 'Ascent': A Resolved Issue</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-setting-up-permanent-delete-on-your-windows-11-and-11-pcs/"><u>The Ultimate Guide to Setting up Permanent Delete on Your Windows 11 & 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-start-experience-no-more-ads-in-w11/"><u>The Ultimate Start Experience: No More Ads in W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-linux-use-without-wsl/"><u>Uncomplicated Linux Use Without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-win11-powertoys-experience/"><u>Unveiling the Win11 PowerToys Experience</u></a></li>
</ul></div>
