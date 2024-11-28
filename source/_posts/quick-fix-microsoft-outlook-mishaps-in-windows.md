---
title: Quick-Fix Microsoft Outlook Mishaps in Windows
date: 2024-11-27T03:57:57.773Z
updated: 2024-11-28T03:15:57.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick-Fix Microsoft Outlook Mishaps in Windows
excerpt: This Article Describes Quick-Fix Microsoft Outlook Mishaps in Windows
keywords: Fix Outlook Errors,Outlook Troubleshooting Tips,Quick Outlook Repair Guide,Windows Outlook Fails,Microsoft Office Solution,Resolve Outlook Issues,Outlook Fix in Win XP/Vista
thumbnail: https://thmb.techidaily.com/ff8e499dfacbb3f8c53c52b2127d34f19a999ba4d08ba1beb7fd17db0047dd1a.jpg
---

## Quick-Fix Microsoft Outlook Mishaps in Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Allow Outlook to repair your profile and then restart the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-a-guide-to-effective-video-capture-methods-for-playstation-4/"><u>[New] 2024 Approved A Guide to Effective Video Capture Methods for PlayStation 4</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-the-dji-drone-visor-revolution-an-in-depth-review/"><u>[New] 2024 Approved The DJI Drone Visor Revolution An In-Depth Review</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-legacy-library-exploring-free-visual-echoes/"><u>[New] The Legacy Library Exploring Free Visual Echoes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-expert-review-dynamic-action-recording-tools-for-2024/"><u>[Updated] Expert Review Dynamic Action Recording Tools for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-from-observing-to-involved-the-tiktok-life-journey/"><u>[Updated] From Observing to Involved The TikTok Life Journey</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-ultimate-guide-to-convert-srt-to-txt-in-minutes-for-2024/"><u>[Updated] Ultimate Guide to Convert SRT to TXT in Minutes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-upgrade-opt-for-cleaner-win11/"><u>Effortless Upgrade: Opt for Cleaner Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-with-simple-key-filter-adjustments/"><u>Enhance Accessibility with Simple Key Filter Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-winerror-inaccurate-file-history-configurations/"><u>How to Rectify WinError: Inaccurate File History Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tailor-your-win11-display-with-rgb/"><u>How to Tailor Your Win11 Display with RGB</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-iphone-14-pro-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On iPhone 14 Pro Online</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-from-apple-iphone-12-pro-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication From Apple iPhone 12 Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/los-20-mejores-editores-video-ideales-para-navegacion-movil-y-ordenadores/"><u>Los 20 Mejores Editores Vídeo Ideales Para Navegación Móvil Y Ordenadores</u></a></li>
<li><a href="https://win11.techidaily.com/opening-disk-management-in-windows-1011-with-ease/"><u>Opening Disk Management in Windows 10/11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-media-player-server-fault/"><u>Solutions for Media Player Server Fault</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-resource-occupancy-issues-in-windows-1011-153-chars/"><u>Tackling Resource Occupancy Issues in Windows 10/11 (153 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-file-system-efficiency-adjusting-ntfs-compression-in-windows-11/"><u>Tailoring File System Efficiency: Adjusting NTFS Compression in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-world-of-tech-samsung-flow-for-pc-and-galaxy-link/"><u>Uniting World of Tech – Samsung Flow for PC & Galaxy Link</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-your-disabled-iphone-15-plus-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>Unlock Your Disabled iPhone 15 Plus Without iTunes in 5 Ways | Dr.fone</u></a></li>
</ul></div>

