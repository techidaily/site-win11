---
title: Simplified Procedure for Restoring Original Windows 11 Search Settings
date: 2024-06-25T10:11:39.045Z
updated: 2024-06-26T10:11:39.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplified Procedure for Restoring Original Windows 11 Search Settings
excerpt: This Article Describes Simplified Procedure for Restoring Original Windows 11 Search Settings
keywords: Win11 Setup Revival,Original Windows 11 Search,Reinstate Win11 Search,Reset Windows 11 Settings,Windows 11 Restore Search,Fixing Win11 Search Issues,Retrieve Win11 Default Search
thumbnail: https://thmb.techidaily.com/b9c87935bcb636b8006c11267defd1b13d4f0a5467f4617c51e1bd762f7f5db4.png
---

## Simplified Procedure for Restoring Original Windows 11 Search Settings

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://win11.techidaily.com/navigating-the-underrated-realm-of-windows-monitoring-systems/"><u>Navigating the Underrated Realm of Windows Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc00d36b4-in-windows-11/"><u>Troubleshooting Error Code 0xC00D36B4 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/stealthy-controls-for-displaying-windows-clock/"><u>Stealthy Controls for Displaying Windows Clock</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-on-space-spotlight-on-large-files-in-windows/"><u>Cutting Down on Space: Spotlight on Large Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-pin-verification-errors-on-w11w10-systems/"><u>Solutions for Fixing PIN Verification Errors on W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-reading-qr-codes-on-windows-devices/"><u>Essential Tips for Reading QR Codes on Windows Devices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-simple-video-editing-for-windows-get-started-with-microsoft-video-editor/"><u>New 2024 Approved Simple Video Editing for Windows Get Started with Microsoft Video Editor</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-for-smartphone-cinematography-enhancements/"><u>2024 Approved  The Ultimate Guide for Smartphone Cinematography Enhancements</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/1714192451401-new-want-to-learn-how-to-convert-facebook-posts-into-mp3-read-this-article-to-find-out-how-and-be-introduced-to-some-of-the-best-facebook-mp3-converters-ava/"><u>New Want to Learn How to Convert Facebook Posts Into MP3? Read This Article to Find Out How and Be Introduced to some of the Best Facebook MP3 Converters Available for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-expert-edits-at-a-click-2-ways-to-rule-the-world-of-tiktok-reactions-with-filmora/"><u>2024 Approved  Expert Edits at a Click – 2 Ways to Rule the World of TikTok Reactions with Filmora</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963576144-new-if-you-are-a-marketer-who-want-to-create-facebook-ads-to-boost-your-business-you-are-coming-to-the-right-place-well-share-you-some-useful-tips-to-start-/"><u>New If You Are a Marketer Who Want to Create Facebook Ads to Boost Your Business, You Are Coming to the Right Place. Well Share You some Useful Tips to Start Your First FB Ads Campaign for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/dos-and-donts-the-ultimate-fb-cover-video-tutorial-for-2024/"><u>Dos & Don'ts  The Ultimate FB Cover Video Tutorial for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-leading-10-innovative-tiktok-filters-for-creators-for-2024/"><u>[New] Leading 10 Innovative TikTok Filters For Creators for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-secret-tactics-for-elevating-your-instagram-presence/"><u>[New] Top-Secret Tactics for Elevating Your Instagram Presence</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-immersive-worlds-unveiled-delving-into-mr-ar-and-vrs-distinctions/"><u>[New] Immersive Worlds Unveiled  Delving Into MR, AR, and VR's Distinctions</u></a></li>
</ul></div>
