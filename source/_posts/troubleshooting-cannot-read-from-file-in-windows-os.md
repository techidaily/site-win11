---
title: Troubleshooting “Cannot Read From File” In Windows OS
date: 2024-10-02T18:15:52.463Z
updated: 2024-10-03T21:16:49.328Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting “Cannot Read From File” In Windows OS
excerpt: This Article Describes Troubleshooting “Cannot Read From File” In Windows OS
keywords: FileReadError_Windows,WindowsFileAccessFailure,WindowsIOOperationProblems,TroubleshootFileIssuesWinOS,ReadFileErrorSolutionsWin,FixCannotReadWinFile,ResolveWindowsFileReadFail
thumbnail: https://thmb.techidaily.com/815fea7976911214190dec2e4ce8ef31c5b56fc35aca9555d7d0112a6571e067.jpg
---

## Troubleshooting “Cannot Read From File” In Windows OS

 Users often need to copy (or transfer) files to or from external drives connected to Windows PCs. However, some users can’t do so because of an error that says, “Can’t read from the source file or disk.”

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check if the File Names Include Unsupported Characters

 Unsupported file name characters can cause the “Cannot read from the source file” error. Mac computers enable users to save files with characters like ?, <, >, :, \*, /, \\, |, and “. However, Windows 11 and 10 don’t support any of those characters for file names. Thus, users can’t copy files from external drives that include those characters onto a Windows PC.

 So, check if any files you’re trying to copy from an external drive include those characters. If you find any that do, right-click the files and select **Rename**. Then delete all unsupported characters from their file names. Or remove all kinds of special characters.

![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-option-1.jpg)

## 2\. Run a Check Disk Scan

 Running a Check Disk scan is a widely confirmed fix for the “Cannot read from the source file” error. That highlights this error is often caused by bad disk sectors on drives. Running a Check Disk scan via the Command Prompt for the drive that includes the files will usually remedy such a cause. Our [how to run a CHKDSK scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,to%20get%20stuck%20on%20occasion.) article tells you how to apply this potential fix.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-chkdsk-command2.jpg)

## 3\. Try a Different USB Cable or Port for External Drives

 Another possible cause for the “Cannot read from the source file or disk” error is that there’s an issue with your USB cable or a port on your PC. So, connect your external drive to a different USB port to see if that makes a difference. If you have an alternative USB cable available, try connecting the drive to your PC with it.

## 4\. Compress the Files You’re Trying to Copy Into a ZIP Folder

 Some users have been able to fix the “Cannot read from the source file or disk” error by compressing the files they need to copy into ZIP archives. Doing so will reduce the overall size of one or more files to copy. You can set up a ZIP archive before copy files onto a drive by following the instructions in our article about [creating ZIP files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/).

![The Send to option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-send-to-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Check the Permissions for the Affected Files

 You might need to fix the “Cannot read from the source file or disk” because one of the files you’re trying to copy doesn’t have full control permissions set. You can check and fix permissions for affected files as follows:

1. First, bring up Explorer (press**Win + E**) and navigate to the folder that includes the files you need to copy.
2. Right-click a file you need to copy and select **Properties**.
3. Then select **Edit** on the **Security** tab.  
![The Edit button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-edit-button.jpg)
4. Next, select the checkbox labeled **Full control** with the **Allow** column.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-full-control-checkbox.jpg)
5. Press **Apply** to save the file’s permission settings.
6. Click **OK** to exit.

 If you can’t see your account username within the Group box, you’ll need to add it. To do so, click **Add** on the **Security** tab to bring up a Select Users or Group window; then click **Advanced** \> **Find now** to select your user account. Click **OK** to add the selected account.

![The Find now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-find-now-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Access Files on Mac-Formatted Drives With Third-Party Software

 The “Can’t read from the source file” error can also occur because of file system incompatibility on source drives. For example, Mac-formatted HFS or APFS drives aren’t compatible with Windows PCs.

 You can check the file system of any connected drive by right-clicking it in File Explorer and selecting **Properties**. Then check the File system detail on the General tab. NTFS and FAT32 file systems are fine for Windows, but HFS and APFS aren’t.

![The File system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-file-system-detail.jpg)

 If you’re trying to copy files from Mac-formatted drives, you can access them with third-party software. Software packages like MacDrive, UFS Explorer, and Paragon HFS+ enable users to access files on Mac-formatted drives on Windows PCs. Our article about [reading Mac-formatted drives on Windows](https://www.makeuseof.com/tag/4-ways-read-mac-formatted-drive-windows/) provides details on how to apply this potential resolution.

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Copy Files Between Drives on Your Windows PC Again

 Applying those solutions will usually resolve the “Cannot read from the source file” error on Windows. Then you can copy all the files you need between your Windows PC and external drives.

 One other resolution for this error recommended by some users is to utilize data recovery software. Such software provides another way to copy or transfer files from one drive to another. Stellar Data Recovery, Recuva, MiniTool Data Recovery, and Disk Drill are among the best data recovery software to utilize for that purpose.

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-premium-list-top-8-android-calls-with-multiple-users/"><u>[New] 2024 Approved Premium List Top 8 Android Calls with Multiple Users</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-mastering-brand-collaboration-on-youtube/"><u>[Updated] 2024 Approved Mastering Brand Collaboration on YouTube</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-excellence-in-resolution-macs-favorite-4k-screens-for-2024/"><u>[Updated] Excellence in Resolution Mac's Favorite 4K Screens for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-plating-perfection-30-unique-and-appealing-recipe-channels/"><u>[Updated] Plating Perfection 30 Unique and Appealing Recipe Channels</u></a></li>
<li><a href="https://win-answers.techidaily.com/44cm56m25qw144gu44ky44o844of44oz44kw6yyy55s744k944ov44oi44ks6kal44gk44gr44ki44gg77yb6kmz44gx44gp6kej6kqs5luy44gn44ob44ol44o844oi44oq44ki44or44cn/"><u>「究極のゲーミング録画ソフトを見つけよう！詳しく解説付きチュートリアル」</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-masterclass-syncing-your-social-media-with-urls/"><u>2024 Approved Masterclass Syncing Your Social Media with URLs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/anthem-latency-solutions/"><u>Anthem Latency Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-performance-erase-sluggish-windows-11-frustration/"><u>Elevate Performance: Erase Sluggish Windows 11 Frustration</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-resolve-improper-token-usage-problems/"><u>Guidance to Resolve Improper Token Usage Problems</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-7-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 7 Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-windows-power-consumption-statistics/"><u>Identifying Windows Power Consumption Statistics</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-meizu-21-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Meizu 21 Phone FRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-languages-swiftly-on-windows-with-key-combinations/"><u>Navigate Through Languages Swiftly on Windows With Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solutions-to-common-fall-guys-connectivity-issues-in-windows/"><u>Quick Solutions to Common Fall Guys Connectivity Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-cameras-capability-to-record/"><u>Restoring Windows Camera's Capability to Record</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-turn-your-pc-into-a-transcoding-network-with-tdarr/"><u>Unleash Potential: Turn Your PC Into a Transcoding Network with Tdarr</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    