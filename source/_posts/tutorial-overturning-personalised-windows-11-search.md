---
title: "Tutorial: Overturning Personalised Windows 11 Search"
date: 2024-10-19T22:51:28.732Z
updated: 2024-10-26T16:31:10.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Overturning Personalised Windows 11 Search"
excerpt: "This Article Describes Tutorial: Overturning Personalised Windows 11 Search"
keywords: Windows 11 Tutorial,Disabling Personalized Search,Opt Out Win 11,Customize Win 11 Search,Personalised Search Removal,Unfiltered Windows 11,Bypassing Windows 11 Filters
thumbnail: https://thmb.techidaily.com/f6689b1ce3b098830c1181e612252ff5b928460b4d7d4122dbd300e015bd5d6c.jpg
---

## Tutorial: Overturning Personalised Windows 11 Search

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-engineering-a-touching-tiktok-conclusion/"><u>[New] 2024 Approved Engineering a Touching TikTok Conclusion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-dell-p2715q-4k-monitor-review/"><u>[Updated] 2024 Approved Dell P2715Q 4K Monitor Review</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-no-price-point-digital-video-recorder/"><u>[Updated] 2024 Approved No-Price Point Digital Video Recorder</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-honor-90-lite-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Honor 90 Lite Phone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/crea-animaciones-gif-gratuitas-desde-archivos-webm-con-la-herramienta-online-de-conversion-en-linea-de-movavi/"><u>Crea Animaciones GIF Gratuitas Desde Archivos WebM Con La Herramienta Online De Conversión en Línea De Movavi</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/deep-dive-into-design-chatgpts-role-in-user-persona-crafting/"><u>Deep Dive Into Design: ChatGPT's Role in User Persona Crafting</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-swagtron-swagboard-t1-a-balance-between-maneuverability-and-price/"><u>In-Depth Analysis of the Swagtron Swagboard T1 - A Balance Between Maneuverability and Price</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-steams-storage-troubles-on-your-computer/"><u>Navigating Steam's Storage Troubles on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-your-efficiency-using-flow-launcher-tool/"><u>Skyrocket Your Efficiency Using Flow Launcher Tool</u></a></li>
<li><a href="https://win11.techidaily.com/solving-geforce-now-error-code-xc0f1103f-on-pcs/"><u>Solving GeForce Now Error Code XC0F1103F on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-system-microsoft-works-for-windows-latest/"><u>Streamline Your System: Microsoft Works for Windows Latest</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-the-solution-to-camera-error-a00f425d-on-windows-11/"><u>Unwrapping the Solution to Camera Error A00F425D on Windows 11</u></a></li>
</ul></div>

