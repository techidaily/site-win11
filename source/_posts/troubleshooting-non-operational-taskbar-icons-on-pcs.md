---
title: Troubleshooting Non-Operational Taskbar Icons on PCs
date: 2024-11-06T17:17:02.518Z
updated: 2024-11-07T17:37:14.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational Taskbar Icons on PCs
excerpt: This Article Describes Troubleshooting Non-Operational Taskbar Icons on PCs
keywords: Fix Taskbar Icons,Non-Working Bar Icons,Operational Bar Fix,Restart Icon Issue,Taskbar Icon Reset,Icon Display Troubleshoot,Enable Taskbar Items
thumbnail: https://thmb.techidaily.com/482035835ea328d1609501451811446cad884a7a61227ca3ca092b735291d94d.jpg
---

## Troubleshooting Non-Operational Taskbar Icons on PCs

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-enhancing-profiles-first-impression/"><u>[New] 2024 Approved Enhancing Profile's First Impression</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-6-engagement-realms-critical-for-corporate-networks/"><u>[New] Prime 6 Engagement Realms Critical for Corporate Networks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-streamline-your-workflow-with-the-top-5-pc-screen-grabbers/"><u>[New] Streamline Your Workflow with the Top 5 Pc Screen Grabbers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-ultimate-list-11-premium-sound-recording-tools-for-2024/"><u>[New] The Ultimate List 11 Premium Sound Recording Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1-effortless-conversion-turning-m4a-files-into-mp3-formats-using-free-online-tools/"><u>1. Effortless Conversion: Turning M4A Files Into MP3 Formats Using Free Online Tools</u></a></li>
<li><a href="https://win11.techidaily.com/1-mastering-the-process-step-by-step-guide-to-converting-beatstars-tracks-into-mp3-format/"><u>1. Mastering the Process: Step-by-Step Guide to Converting BeatStars Tracks Into MP3 Format</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtubes-high-stakes-hardware-showdown/"><u>2024 Approved YouTube’s High-Stakes Hardware Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/1726028392485-mp3/"><u>無響拡張子MP3でピークレス部分をクリアする手引き</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/free-windows-11-media-viewer-compatible-with-multiple-file-types/"><u>Free Windows 11 Media Viewer: Compatible with Multiple File Types</u></a></li>
<li><a href="https://win11.techidaily.com/1726027925580-huawei/"><u>Huawei端末における音楽再生の不具合解消ガイド</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-are-video-reviews-of-goods-paid-for-by-creators/"><u>In 2024, Are Video Reviews of Goods Paid For by Creators?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-from-your-apple-iphone-14-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card from Your Apple iPhone 14 Apple ID and Apple Pay</u></a></li>
<li><a href="https://win11.techidaily.com/itunes-mp3wav/"><u>ITunes MP3ファイルからWAV形式への変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/mp3-audible-aax/"><u>MP3への変換 - Audible AAX音声ファイルをどうやって変更するか</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-realme-gt-5-pro-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Realme GT 5 Pro Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-free-dvd-player-applications-compatible-with-windows-11-watch-movies-at-no-charge/"><u>Top 7 Free DVD Player Applications Compatible with Windows 11: Watch Movies at No Charge</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/1728473421813-windows-11qnap-nas/"><u>Windows 11とQNAP NAS間で安全なデータバックアップ方法:最新戦略</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfox-solves-missing-page-issue-error-code-404-no-more/"><u>WonderFox Solves Missing Page Issue - Error Code 404 No More</u></a></li>
<li><a href="https://win11.techidaily.com/avisynth/"><u>ビデオ再生中の音量設定 - AviSynthを使って</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    