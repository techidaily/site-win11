---
title: Navigating Common Outlook Issues in Windows
date: 2024-12-04T12:17:04.259Z
updated: 2024-12-07T02:21:55.415Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Common Outlook Issues in Windows
excerpt: This Article Describes Navigating Common Outlook Issues in Windows
keywords: Fixing Outlook Troubles,Windows Email Errors,Resolve Outlook Glitches,Outlook Windows Help,Overcoming Outlook Issues,Mend Mail App Problems,Outlook on Windows Tips
thumbnail: https://thmb.techidaily.com/c381619f8aafcfb0f80b6508563d2271437d8649f2f0442bcc2c7a6fb3d30ee1.jpg
---

## Navigating Common Outlook Issues in Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-capturing-your-desktop-in-winoses-effortlessly/"><u>[New] In 2024, Capturing Your Desktop in WinOSes Effortlessly</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-fraud-busters-efficient-and-economical-methods/"><u>[Updated] Instagram Fraud Busters Efficient & Economical Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-meme-formula-combining-humor-trendiness-and-viral-video-potential/"><u>[Updated] The Meme Formula Combining Humor, Trendiness & Viral Video Potential</u></a></li>
<li><a href="https://fox-useful.techidaily.com/1-effortless-ringtone-movement-transferring-your-favorite-tones-from-iphone-to-ipad-or-iphone/"><u>1. Effortless Ringtone Movement: Transferring Your Favorite Tones From iPhone to iPad or iPhone</u></a></li>
<li><a href="https://solve-latest.techidaily.com/efficient-hevc-h265-video-decode-accelerator-top-performer-in-minimal-resource-consumption/"><u>Efficient HEVC H.265 Video Decode Accelerator: Top Performer in Minimal Resource Consumption</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-manage-windows-11-security/"><u>Essential Steps to Manage Windows 11 Security</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-xltm-files-free-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How do i sign a .xltm files free</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-vivo-y55s-5g-2023-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Vivo Y55s 5G (2023) Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-appeal-enabling-emoji-15-in-win11/"><u>Maximize Visual Appeal: Enabling Emoji 15 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-problems-with-downloading-data-on-windows/"><u>Navigating Through Problems with Downloading Data on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-windows-tracked-app-usage/"><u>Quiet Windows' Tracked App Usage</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-google-chrome-error-on-microsoft-os/"><u>Resolving Google Chrome Error on Microsoft OS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solution-guide-overcoming-the-800-error-in-vpn-setup-for-clients-and-servers/"><u>Solution Guide: Overcoming the 800 Error in VPN Setup for Clients and Servers</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-pcs-persistent-pink-flashes/"><u>Swift Remedies for PC's Persistent Pink Flashes</u></a></li>
<li><a href="https://win11.techidaily.com/the-ideal-windows-10-artistic-software-lineup-of-7/"><u>The Ideal Windows 10 Artistic Software Lineup of 7</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-power-the-ultimate-guide-to-windows-performance/"><u>Unleash Power: The Ultimate Guide to Windows Performance</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-vivo-v29-pro-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Vivo V29 Pro Phone Network-Ready</u></a></li>
<li><a href="https://win11.techidaily.com/your-guide-to-win11s-versatility-homes-vs-professional-suites/"><u>Your Guide to Win11's Versatility: Homes Vs. Professional Suites</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    