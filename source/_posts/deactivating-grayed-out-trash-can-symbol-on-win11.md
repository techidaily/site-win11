---
title: Deactivating Grayed Out Trash Can Symbol on Win11
date: 2024-10-05T22:36:16.651Z
updated: 2024-10-09T04:25:56.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deactivating Grayed Out Trash Can Symbol on Win11
excerpt: This Article Describes Deactivating Grayed Out Trash Can Symbol on Win11
keywords: Windows 11 Trash Fix,Remove Grayed Out Icon,Fix Win11 Symbol,Clear Can Waste Image,Deactivate Bin Marking,Trash Can Reset Win11,Symbol Deactivation Win11
thumbnail: https://thmb.techidaily.com/344ccd42970473c822ce3d8647d1f132f07ed11b189d66bfa12739452e5e4fb4.jpg
---

## Deactivating Grayed Out Trash Can Symbol on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
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
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-reassessing-manycam-search-for-a-top-contender/"><u>[New] In 2024, Reassessing ManyCam Search for a Top Contender</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-expert-tutorial-on-utilizing-googles-automatic-speech-transcription/"><u>[Updated] 2024 Approved Expert Tutorial on Utilizing Google's Automatic Speech Transcription</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-nextgen-fidelity-upgrade-your-viewing-experience/"><u>[Updated] 2024 Approved NextGen Fidelity Upgrade Your Viewing Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-guide-to-sns-hdr-pro-and-similar-software/"><u>[Updated] Comprehensive Guide to SNS HDR Pro and Similar Software</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-elite-streaming-sensations-worlds-most-popular-video-content-makers-for-2024/"><u>[Updated] Elite Streaming Sensations World's Most Popular Video Content Makers for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-zero-to-viral-video-top-10-user-friendly-youtube-concepts/"><u>[Updated] From Zero to Viral Video Top 10 User-Friendly YouTube Concepts</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-top-strategies-for-changing-song-pace-on-spotify-app-for-2024/"><u>[Updated] Top Strategies for Changing Song Pace on Spotify App for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-early-edge-tab-launches-on-windows-11/"><u>Prevent Early Edge Tab Launches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-integrating-songs-in-microsofts-presentation-maker/"><u>Step-by-Step Integrating Songs in Microsoft's Presentation Maker</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-rectifying-windows-error-code-0x80040610/"><u>Swift Solutions for Rectifying Windows Error Code 0X80040610</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-tips-for-keeping-your-iphones-memories-in-order-and-backed-up-on-icloud-for-2024/"><u>Top Tips for Keeping Your iPhone's Memories in Order and Backed Up on iCloud for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-secrets-the-working-principle-behind-chatgpt-shared-links/"><u>Unveiling the Secrets: The Working Principle Behind ChatGPT Shared Links</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
</ul></div>

