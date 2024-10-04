---
title: Steps to Correct Win XP/10 Extraction Issue 1152
date: 2024-10-03T02:31:34.455Z
updated: 2024-10-04T04:23:10.116Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Correct Win XP/10 Extraction Issue 1152
excerpt: This Article Describes Steps to Correct Win XP/10 Extraction Issue 1152
keywords: Win XP Fix Guide,Windows XP Extract Issue,XP Error 1152 Resolution,Extracting XP Installation,XP/10 BSOD Correction,XP Boot Failure Solution,XP Install Troubleshooting
thumbnail: https://thmb.techidaily.com/5d3200ea7acc8a267e33f7e3f6be29344352dcba610c7cb281d20c740b294fae.jpg
---

## Steps to Correct Win XP/10 Extraction Issue 1152

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

## Install the Windows Software You Need Again

 There aren’t that many confirmed resolutions for error 1152\. However, the ones covered here have worked for many users who’ve needed to fix that Windows software installation issue.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-advice-for-staying-copyright-compliant-online/"><u>[Updated] Expert Advice for Staying Copyright Compliant Online</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-tiktok-glitches-troubleshooting-iosandroid-issues-for-2024/"><u>[Updated] TikTok Glitches Troubleshooting iOS/Android Issues for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1-quick-and-simple-guide-downloading-and-setting-up-showbox-on-your-computer/"><u>1. Quick & Simple Guide: Downloading & Setting Up ShowBox on Your Computer</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-elevate-your-gaming-with-fbx-capture-pro/"><u>2024 Approved Elevate Your Gaming with FBX Capture Pro</u></a></li>
<li><a href="https://win11.techidaily.com/1726028090190-20248/"><u>2024年度人気動画編集ツールベスト8！無料でダウンロード可能</u></a></li>
<li><a href="https://extra-information.techidaily.com/beyond-reality-mastering-the-subtleties-of-ps-distortions-for-2024/"><u>Beyond Reality Mastering the Subtleties of PS Distortions for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-evaluation-why-nest-audio-is-a-must-have-for-every-music-enthusiast/"><u>Comprehensive Evaluation: Why Nest Audio Is a Must-Have for Every Music Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/handling-runtime-failure-tips-for-correcting-malwarebytes-execution-errors-on-win10win11/"><u>Handling Runtime Failure: Tips for Correcting Malwarebytes' Execution Errors on Win10/Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-iphone-6s-plus-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your iPhone 6s Plus in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-unveiling-the-leading-free-stock-video-and-image-archives/"><u>In 2024, Unveiling the Leading Free Stock Video and Image Archives</u></a></li>
<li><a href="https://win11.techidaily.com/intel-unison-not-working-try-this-fix-guide-on-windows-11/"><u>Intel Unison Not Working? Try This Fix Guide on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-notes-at-the-forefront-on-win-oses/"><u>Keep Your Notes at the Forefront on Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-search-troubleshooting-steps/"><u>Navigating Through Windows Search Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-win11-vagrant-start-issues-with-7-effective-approaches/"><u>Resolve Win11 Vagrant Start Issues with 7 Effective Approaches</u></a></li>
<li><a href="https://buynow-info.techidaily.com/retrospective-review-exploring-the-new-dimensions-in-ratchet-and-clank-classic/"><u>Retrospective Review: Exploring the New Dimensions in Ratchet & Clank Classic</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-getting-started-with-outlook-preview-on-windows-11/"><u>Seamless Transition: Getting Started with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1726027263067-step-by-step-guide-video-editing-in-windows-10-updated/"><u>Step-by-Step Guide: Video Editing in Windows 10 (Updated)</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-tech-truth-about-texting-with-snapchat-and-gpt/"><u>The Tech Truth About Texting with Snapchat & GPT</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    