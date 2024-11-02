---
title: Correcting Disk Access Failure in Microsoft's OS
date: 2024-10-27T16:31:14.367Z
updated: 2024-11-01T20:15:59.981Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Disk Access Failure in Microsoft's OS
excerpt: This Article Describes Correcting Disk Access Failure in Microsoft's OS
keywords: Fix Disk Error MSOS,Solve IO Ops Failures,Stop Disk Access Crash,Rectify Disk Issues MSOS,Resolve IO Bugs Windows,Correct OS Disk Access,Microsoft OS Disk Repair
thumbnail: https://thmb.techidaily.com/a362218194355c666b0860326aa79761dfe27d2518f12f424f4610cd1ffe517b.jpg
---

## Correcting Disk Access Failure in Microsoft's OS

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Compress the Files You’re Trying to Copy Into a ZIP Folder

 Some users have been able to fix the “Cannot read from the source file or disk” error by compressing the files they need to copy into ZIP archives. Doing so will reduce the overall size of one or more files to copy. You can set up a ZIP archive before copy files onto a drive by following the instructions in our article about [creating ZIP files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/).

![The Send to option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-send-to-option.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Check the Permissions for the Affected Files

 You might need to fix the “Cannot read from the source file or disk” because one of the files you’re trying to copy doesn’t have full control permissions set. You can check and fix permissions for affected files as follows:

1. First, bring up Explorer (press**Win + E**) and navigate to the folder that includes the files you need to copy.
2. Right-click a file you need to copy and select **Properties**.
3. Then select **Edit** on the **Security** tab.  
![The Edit button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-edit-button.jpg)
4. Next, select the checkbox labeled **Full control** with the **Allow** column.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-full-control-checkbox.jpg)
5. Press **Apply** to save the file’s permission settings.

6. Click **OK** to exit.

 If you can’t see your account username within the Group box, you’ll need to add it. To do so, click **Add** on the **Security** tab to bring up a Select Users or Group window; then click **Advanced** \> **Find now** to select your user account. Click **OK** to add the selected account.

![The Find now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-find-now-option.jpg)

## How to Access Files on Mac-Formatted Drives With Third-Party Software

 The “Can’t read from the source file” error can also occur because of file system incompatibility on source drives. For example, Mac-formatted HFS or APFS drives aren’t compatible with Windows PCs.

 You can check the file system of any connected drive by right-clicking it in File Explorer and selecting **Properties**. Then check the File system detail on the General tab. NTFS and FAT32 file systems are fine for Windows, but HFS and APFS aren’t.

![The File system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-file-system-detail.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you’re trying to copy files from Mac-formatted drives, you can access them with third-party software. Software packages like MacDrive, UFS Explorer, and Paragon HFS+ enable users to access files on Mac-formatted drives on Windows PCs. Our article about [reading Mac-formatted drives on Windows](https://www.makeuseof.com/tag/4-ways-read-mac-formatted-drive-windows/) provides details on how to apply this potential resolution.

## Copy Files Between Drives on Your Windows PC Again

 Applying those solutions will usually resolve the “Cannot read from the source file” error on Windows. Then you can copy all the files you need between your Windows PC and external drives.

 One other resolution for this error recommended by some users is to utilize data recovery software. Such software provides another way to copy or transfer files from one drive to another. Stellar Data Recovery, Recuva, MiniTool Data Recovery, and Disk Drill are among the best data recovery software to utilize for that purpose.

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-how-long-does-a-20mb-video-last-for-2024/"><u>[New] How Long Does a 20MB Video Last for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-simple-steps-to-coordinate-consistent-productive-google-collaboration-times/"><u>[Updated] In 2024, Simple Steps to Coordinate Consistent, Productive Google Collaboration Times</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-infusing-youtube-soundtracks-within-multimedia/"><u>[Updated] Infusing YouTube Soundtracks Within Multimedia</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-source-material-how-it-formulates-answers-without-stealing-ideas/"><u>ChatGPT's Source Material: How It Formulates Answers Without Stealing Ideas</u></a></li>
<li><a href="https://extra-resources.techidaily.com/diving-deep-into-the-features-of-the-dell-p2715q-monitor/"><u>Diving Deep Into the Features of the Dell P2715Q Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/effective-windows-spooler-revival/"><u>Effective Windows Spooler Revival</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-unstable-cursor-on-windows-systems/"><u>Fixing an Unstable Cursor on Windows Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-lava-agni-2-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Lava Agni 2 5G Phone Without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-method-to-install-windows-11-on-elderly-pcs-with-to-go-and-rufus/"><u>Masterful Method to Install Windows 11 on Elderly PCs with To Go and Rufus</u></a></li>
<li><a href="https://fox-direct.techidaily.com/sync-your-storytelling-iphone-captures-words-and-pictures-for-2024/"><u>Sync Your Storytelling IPhone Captures Words and Pictures for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-graphics-ram-on-modern-windows-devices/"><u>Upgrading Graphics RAM on Modern Windows Devices</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/what-language-is-spoken-in-israel/"><u>What Language Is Spoken in Israel?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-discontinued-adapting-to-new-android-setup/"><u>Windows Subsystem Discontinued: Adapting to New Android Setup</u></a></li>
</ul></div>

