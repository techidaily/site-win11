---
title: Fixing Saving Failures in Windows 10 & 11
date: 2024-09-11T18:28:42.688Z
updated: 2024-09-16T19:23:40.541Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Saving Failures in Windows 10 & 11
excerpt: This Article Describes Fixing Saving Failures in Windows 10 & 11
keywords: Windows Save Errors Fix,10/11 Savings Hacks,Win10 Saving Shortcuts,Repairing Saves in W11,Win10 Data Backup Tips,Avoiding Save Failures,Safekeep Your Windows Files
thumbnail: https://thmb.techidaily.com/891c1ef62d1f0cae8f261e14a3ae4e9d18efe066afd0af7e2373c813aa6b6f85.jpg
---

## Fixing Saving Failures in Windows 10 & 11

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-step-up-your-instagram-game-with-these-highest-rated-grid-makers/"><u>[New] 2024 Approved Step Up Your Instagram Game with These Highest-Rated Grid Makers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-elevating-video-discoverability-with-strategic-tagging-on-youtube/"><u>[New] In 2024, Elevating Video Discoverability with Strategic Tagging on Youtube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-premier-moba-experiences-on-your-android-device/"><u>[New] In 2024, Premier MOBA Experiences on Your Android Device</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-streamlining-script-conversion-from-text-formats-to-engaging-srt/"><u>[New] Streamlining Script Conversion From Text Formats to Engaging SRT</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-top-10-filmora-editing-traits-for-fan-loyalty/"><u>[New] Top 10 Filmora Editing Traits for Fan Loyalty</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-artisans-guide-to-chromatic-mastery/"><u>[Updated] The Artisan's Guide to Chromatic Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-issues-with-googles-nearby-sharing-on-windows/"><u>Fixing Issues with Google's Nearby Sharing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-power-saver-modes-in-windows-os/"><u>Mastering Power Saver Modes in Windows OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/normalizing-opposite-orientation-screens-windows-11/"><u>Normalizing Opposite Orientation Screens, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perpetual-disposal-setting-up-unchangeable-deletion-bin-on-pc/"><u>Perpetual Disposal: Setting up Unchangeable Deletion Bin on PC</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-11-sign-in-your-guide-to-success/"><u>Seamless Windows 11 Sign-In: Your Guide to Success</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-usage-error-in-windows-11-os/"><u>Troubleshooting Usage Error in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unresponsive-click-problems-guide-for-win11-users/"><u>Unresponsive Click Problems: Guide for Win11 Users</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-realme-v30-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Realme V30? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    