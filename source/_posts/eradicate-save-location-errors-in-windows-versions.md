---
title: Eradicate Save Location Errors in Windows Versions
date: 2024-09-27T02:12:31.475Z
updated: 2024-10-03T23:47:12.424Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicate Save Location Errors in Windows Versions
excerpt: This Article Describes Eradicate Save Location Errors in Windows Versions
keywords: Eradicate Location Errors,Fix Win Error Locations,Resolve Windows LocError,Remove Windows ErrLoc,Clear OS Location Errors,Stop Win LocErrors,Eliminate Windows LocErr
thumbnail: https://thmb.techidaily.com/f0f1add4f06bedd9b4441c0d9e38e221d87204ef26ea2cde0e10ae3ca9b9c9f6.jpg
---

## Eradicate Save Location Errors in Windows Versions

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148644/16836" target="_top" id="2148644">
  <img src="//a.impactradius-go.com/display-ad/16836-2148644" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148644/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-social-stardom-awaits-add-1k-to-your-insta-profile-each-month-for-2024/"><u>[New] Social Stardom Awaits Add 1K to Your Insta Profile Each Month for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-image-quality-a-newbies-comprehensible-guide/"><u>[Updated] Unveiling Image Quality A Newbie's Comprehensible Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-audacity-for-professional-sound-capture/"><u>2024 Approved Mastering Audacity for Professional Sound Capture</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-poco-f5-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-meizu-21-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Meizu 21 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/elevate-gaming-and-design-how-to-successfully-replace-a-video-card/"><u>Elevate Gaming & Design: How to Successfully Replace a Video Card</u></a></li>
<li><a href="https://fox-blue.techidaily.com/exclusive-selections-free-vs-paid-hd-playback-software/"><u>Exclusive Selections Free vs Paid HD Playback Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vac-was-unable-to-verify-your-game-session-error-on-steam-for-windows/"><u>How to Fix the “VAC Was Unable to Verify Your Game Session” Error on Steam for Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevating-creative-content-vimeo-vs-youtubes-approach/"><u>In 2024, Elevating Creative Content Vimeo vs YouTube's Approach</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-essential-guide-unobtrusive-android-video-capture/"><u>In 2024, Essential Guide Unobtrusive Android Video Capture</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-without-microsofts-core-tools-for-win-11/"><u>Mastery Without Microsoft's Core Tools for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-settings-hyper-v-onoff-tutorial/"><u>Navigating Windows 11'S Settings: Hyper-V On/Off Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-windows-11-defender-trail-easy-steps-to-take/"><u>Revamp Your Windows 11 Defender Trail: Easy Steps to Take</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-microsoft-meeting-screen/"><u>Reviving Your Microsoft Meeting Screen</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-win11-screensaver-exceptions-easily/"><u>Sidestep WIN11 Screensaver Exceptions Easily</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-lost-network-access-on-windows-pc/"><u>Steps to Regain Lost Network Access on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-re-associate-file-applications-in-win108/"><u>Strategies to Re-Associate File Applications in Win10/8</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/toms-tech-hub-exploring-latest-computer-hardware-trends/"><u>Tom's Tech Hub: Exploring Latest Computer Hardware Trends</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-security-tool-canary-channel/"><u>Unveiling Windows' Security Tool: Canary Channel</u></a></li>
</ul></div>

