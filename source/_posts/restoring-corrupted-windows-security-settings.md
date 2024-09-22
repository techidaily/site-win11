---
title: Restoring Corrupted Windows Security Settings
date: 2024-09-16T22:52:41.058Z
updated: 2024-09-21T16:15:54.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Corrupted Windows Security Settings
excerpt: This Article Describes Restoring Corrupted Windows Security Settings
keywords: Fixing Windows Secure Issues,Resetting Windows Safety,Recovering System Security,Reviving PC Protection,Restore Windows Lockdown,Repairing OS Security,Reinstating Security Settings
thumbnail: https://thmb.techidaily.com/22dc377b14c8750c75c360ab6d9b7d702e69a18c8a5a08c607e9cd26432f995f.jpg
---

## Restoring Corrupted Windows Security Settings

 Your computer has what's known as an Access Control List (ACL). Its job is to tell Windows the resources, such as files and folders, users can access on your computer. If something corrupts the ACL, you can run into the “access control entry is corrupt” error when trying to access certain resources on Windows.

 We're going to show you how to get rid of the “access control entry is corrupt” error on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Perform an SFC or CHKDSK Scan

 Running an SFC scan can fix the error by fixing any corrupt system files associated with the proper functioning of the ACL. If the files are missing, a DISM scan will replace them using a cached Windows system image file. If these two scans don't work, the problem could be related to hard disk errors, which you can fix with a CHKDSK scan.

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The above-mentioned tools are [built into Windows to help repair corrupt or damaged files](https://www.makeuseof.com/windows-built-in-repair-tools), and you should familiarize yourself with how and when to use them.

## 2\. Close All Universal Windows Platform (UWP) Apps

 Sometimes, UWP apps can lock resources when they're running in their sand-boxed environment. They're not supposed to, but when they do, you can get the “access control entry is corrupt” error message. To fix this, close the UWP app you suspect is the culprit and then update or reinstall it.

## 3\. Change Ownership of the Affected File or Folder

 Taking ownership of a file or folder can sometimes resolve the “access control entry is corrupt” error. To do that, follow the steps below:

1. Right-click the file or folder and select **Properties**.  
![the context menu in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-context-menu-in-windows-11.jpg)
2. Select the **Security** tab and then click on **Advanced** at the bottom to open the **Advanced Securities** window for the file.  
![the Security tab of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-security-tab-of-a-file-on-windows.jpg)
3. Next to the **Owner**, check to see if your username is listed as the owner of the file or folder. If it isn't, that may be the problem. So, click on the **Change** link next to it to open the Select User or Group window.  
![the Advanced Settings window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-settings-window-of-a-file-on-windows.jpg)
4. Click **Advanced** to open the **Select User or Group (Advanced)** window.  
![the Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-select-user-or-group-window-of-a-file-on-windows.jpg)
5. Click **Find Now** to search for the available users on your Windows computer.  
![the advanced Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-on-windows.jpg)
6. In the search results at the bottom, select your username and click **OK**.  
![the advanced Select User or Group window of a file on Windows with a list user on the PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-with-a-list-of-users-on-windows.jpg)
7. Back in the **Select User or Group** window, click **OK**.
8. In the **Advanced Securities** window, click **Apply** and then **OK**.

 Now that you've changed ownership, try accessing the file or folder again and see if the error still shows up.

## 4\. Try Accessing the File or Folder From a Different User Account

 Sometimes, the error pops up because your user account is corrupt, meaning that all the fixes above will most likely fail. What you can do is [create another user account on Windows for troubleshooting purposes](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

 Try to access the file or folder (provided it is in a publicly available directory), and if the error doesn't pop up, you can migrate the necessary files from the old account to the new one.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Restore the Access Control List

 If none of the solutions above have worked, then it might be time to restore the ACL itself. To do that, first, [back up your Windows 10 computer](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) or [back up your Windows 11 computer](https://www.makeuseof.com/windows-11-create-complete-backup/).

 Then, [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/), and that should get rid of the “access control entry is corrupt” error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Access Every Resource on Your Windows Computer

 The “access control entry is corrupt” error is frustrating since it locks you out of the resources you need at the time on your Windows computer. Hopefully, the first four fixes will help before you have to do something drastic like resetting your PC. Either way, it's good to know you're not stuck with the error indefinitely.

 We're going to show you how to get rid of the “access control entry is corrupt” error on your Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tech-haven.techidaily.com/chatgpt-on-iphone-not-responding-apply-any-of-our-9-proven-strategies/"><u>ChatGPT on iPhone Not Responding? Apply Any of Our 9 Proven Strategies!</u></a></li>
<li><a href="https://win11.techidaily.com/hotkeys-and-habits-integrating-quick-paste-features-in-windows-11-edition/"><u>Hotkeys & Habits: Integrating Quick-Paste Features in Windows 11 Edition</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-apple-iphone-11-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and Apple iPhone 11 The Right Way</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-effortlessly-correct-the-0x800f0831-glitch-using-windows-updates/"><u>How to Effortlessly Correct the 0X800F0831 Glitch Using Windows Updates</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-make-slow-motion-video-with-photos-app-and-online/"><u>How to Make Slow Motion Video with Photos App and Online</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-lenovo-phone-without-google-account-by-drfone-android/"><u>How to Unlock Lenovo Phone without Google Account?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-infinix-zero-30-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Infinix Zero 30 5G FRP?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c300-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Nokia C300 Phone without Google Account?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-incorporating-keywords-for-seo/"><u>In 2024, Incorporating Keywords for SEO</u></a></li>
<li><a href="https://win11.techidaily.com/intruder-alert-hiding-windows-wi-fi-ssid/"><u>Intruder Alert! Hiding Windows Wi-Fi SSID</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-error-80080300-fixing-ms-teams-win11-glitches/"><u>Overcoming Error 80080300: Fixing MS Teams Win11 Glitches</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo Reno 11F 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    