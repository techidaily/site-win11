---
title: How to Restore Run Command's Past Actions
date: 2024-10-14T19:31:08.715Z
updated: 2024-10-15T17:17:05.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Restore Run Command's Past Actions
excerpt: This Article Describes How to Restore Run Command's Past Actions
keywords: Revive Command History,Run Commands Action Recovery,Retrieve Run Command Deletions,Undo Run History Erase,Restore Run Commands Past Actions,Recover Lost Run Executions,Reinstate Deleted Command Logs
thumbnail: https://thmb.techidaily.com/8eb0a52f331cadec1455be55279efe68c9588c11451977d41c23dfeca435c0f3.jpg
---

## How to Restore Run Command's Past Actions

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-cut-the-clutter-in-your-tiktok-archive-learn-to-edit-wisely/"><u>[Updated] In 2024, Cut the Clutter in Your TikTok Archive Learn to Edit Wisely</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-pixeled-play-log-audit/"><u>[Updated] In 2024, Pixeled Play Log Audit</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-skald-rage-new-age-of-might/"><u>[Updated] Skald Rage New Age of Might</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-what-everyone-must-know-about-creating-short-form-videos/"><u>[Updated] What Everyone Must Know About Creating Short-Form Videos</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-masterclass-creating-alluring-vlogging-storylines/"><u>2024 Approved Masterclass Creating Alluring Vlogging Storylines</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-step-by-step-guide-to-viewing-vr-films-and-games-on-ios/"><u>2024 Approved Step-by-Step Guide to Viewing VR Films & Games on IOS</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-find-my-app-troubleshooting-no-location-found-vs-location-not-available-and-how-to-fix-them-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, Find My App Troubleshooting No Location Found vs. Location Not Available & How to Fix Them On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/itunesaac/"><u>ITunes上でAACファイルを正常に読み込む方法：解決策集</u></a></li>
<li><a href="https://win11.techidaily.com/leading-iso-tool-for-quick-dvd-to-iso-and-multi-format-file-transformations/"><u>Leading ISO Tool for Quick DVD-to-ISO and Multi-Format File Transformations</u></a></li>
<li><a href="https://win11.techidaily.com/mbs/"><u>MBS動画イズム動画ダウンロード・セキュリティ対策ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-simple-guide-converting-opus-files-to-wma-format/"><u>Quick and Simple Guide: Converting Opus Files to WMA Format</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-integrating-audio-tracks-with-avi-files-seamlessly/"><u>Quick Guide: Integrating Audio Tracks with AVI Files Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-transforming-avi-videos-into-gifs-with-speed/"><u>Quick Guide: Transforming AVI Videos Into GIFs with Speed</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-on-effortlessly-transforming-snd-tracks-into-mp3-files/"><u>Quick Tips on Effortlessly Transforming SND Tracks Into MP3 Files</u></a></li>
<li><a href="https://vp-tips.techidaily.com/seamless-verzameling-van-webm-naar-mp4-met-een-virtueel-online-convertereigenaar/"><u>Seamless Verzameling Van WebM Naar MP4 Met Een Virtueel Online-Convertereigenaar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-x100-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo X100 Location | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    