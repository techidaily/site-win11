---
title: Reinstating Windows 11 Default Search Options
date: 2025-01-18T00:57:18.792Z
updated: 2025-01-19T01:14:10.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Windows 11 Default Search Options
excerpt: This Article Describes Reinstating Windows 11 Default Search Options
keywords: Restore Win11 SearCH,Win11 SEARCH RESET,Enable Win11 Default SERCH,Set Win11 as DEFAULT SEARCH,Windows 11 SETTINGS RESTORE,Win11 INITIAL SEARCH RECUP,Win11 Search RETURN TO STD
thumbnail: https://thmb.techidaily.com/e0a34c7a81fb8279e0e4f8e61ff399b11932a0b059873f4809f00d7b660fc375.jpg
---

## Reinstating Windows 11 Default Search Options

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-sky-sprints-guide-to-excellence-plus-ultimate-fpv-drones-for-speed-for-2024/"><u>[New] Sky Sprints Guide to Excellence + Ultimate FPV Drones for Speed for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-unveiling-youtubes-mechanism-post-upload/"><u>[Updated] 2024 Approved Unveiling YouTube's Mechanism Post-Upload</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-amplify-content-with-free-audio-samples/"><u>[Updated] In 2024, Amplify Content with Free Audio Samples!</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-login-attempt-wait-duration-on-failure/"><u>Customizing Login Attempt Wait Duration on Failure</u></a></li>
<li><a href="https://win-able.techidaily.com/1723005983936-football-manager-2020-stops-responding-heres-how-you-can-unfreeze-it/"><u>Football Manager 2020 Stops Responding? Here's How You Can Unfreeze It!</u></a></li>
<li><a href="https://win11.techidaily.com/gaming-legends-redirected-your-pcs-my-pictures-gallery/"><u>Gaming Legends Redirected: Your PC's My Pictures Gallery</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/handbrake-now-supports-64-bit-overcoming-vlc-not-64-bit-issue/"><u>Handbrake Now Supports 64-Bit: Overcoming 'VLC Not 64-Bit' Issue</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-iphone-7-plus-complete-guide-by-drfone-ios/"><u>In 2024, How To Remove Passcode From iPhone 7 Plus? Complete Guide</u></a></li>
<li><a href="https://win-data.techidaily.com/mac-keyboard-customization-tips-how-to-adjust-the-command-key-settings/"><u>Mac Keyboard Customization Tips: How To Adjust The Command Key Settings</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-navigating-win-repairs-creating-efficient-hotkey-links/"><u>Swiftly Navigating Win Repairs: Creating Efficient Hotkey Links</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/uncovering-the-best-kept-secret-in-robot-vacuums-a-stunning-find-from-a-newcomer-to-market-zdnet-exclusive-review/"><u>Uncovering the Best Kept Secret in Robot Vacuums: A Stunning Find From a Newcomer to Market | ZDNET Exclusive Review</u></a></li>
<li><a href="https://win11.techidaily.com/undercover-archive-strategies-for-win11-photos/"><u>Undercover Archive Strategies for Win11 Photos</u></a></li>
</ul></div>

