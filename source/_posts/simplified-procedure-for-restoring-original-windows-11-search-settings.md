---
title: Simplified Procedure for Restoring Original Windows 11 Search Settings
date: 2024-06-25T11:31:41.572Z
updated: 2024-06-26T11:31:41.572Z
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
<li><a href="https://win11.techidaily.com/seamless-setup-for-icloud-users-with-windows-pcs/"><u>Seamless Setup for iCloud Users with Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/disable-dim-display-feature-via-control-panel-quick-guide/"><u>Disable Dim Display Feature via Control Panel Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-11-wait-longer-when-shutting-down-if-you-have-running-tasks/"><u>How to Make Windows 11 Wait Longer When Shutting Down if You Have Running Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719249883200-revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued!</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-new-folders-into-explorers-interface/"><u>Incorporating New Folders Into Explorer's Interface</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-open-issues-windows-11s-mail-and-calendar-hiccup/"><u>Fixing Open Issues: Windows 11'S Mail & Calendar Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-menu-items-on-windows/"><u>Steps to Reactivate Deactivated Menu Items on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/game-resurrection-applying-retroarchs-shaders-to-vintage-games/"><u>Game Resurrection: Applying RetroArch's Shaders to Vintage Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-mastering-tunes-in-fb-video-posts-your-step-by-step-manual/"><u>[Updated] 2024 Approved  Mastering Tunes in FB Video Posts  Your Step-by-Step Manual</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oppo-a1x-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Oppo A1x 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-poco-c50-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Poco C50 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-mastering-the-art-of-tiktok-intros-on-mac-devices/"><u>[Updated] Mastering the Art of TikTok Intros on Mac Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-can-i-recover-corrupted-excel-file-2007-stellar-by-stellar-guide/"><u>How Can I Recover Corrupted Excel File 2007 | Stellar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-finding-your-perfect-tone-strategies-for-personalized-vocal-change/"><u>Updated 2024 Approved Finding Your Perfect Tone Strategies for Personalized Vocal Change</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-behance-portfolio-image-constraints/"><u>[New] Behance Portfolio Image Constraints</u></a></li>
</ul></div>
