---
title: Mending Microsoft Outlook Glitches on Windows Devices
date: 2024-07-13T10:33:20.694Z
updated: 2024-07-14T10:33:20.694Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mending Microsoft Outlook Glitches on Windows Devices
excerpt: This Article Describes Mending Microsoft Outlook Glitches on Windows Devices
keywords: Fix Outlook Errors,Resolve Outlook Crash,Tackle Outlook Issues,Mend Outlook on PC,Rectify Microsoft Email Glitches,Overcome Windows Outlook Problems,Solve Devices Outlook Bug
thumbnail: https://thmb.techidaily.com/dc5fff1a9acb5e2e1b1bb4c72b06c12c5151a76a3bb3ac96ddd883f3e1ef8520.jpg
---

## Mending Microsoft Outlook Glitches on Windows Devices

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

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
<li><a href="https://win11.techidaily.com/4-easy-ways-to-create-a-new-folder-in-windows-11/"><u>4 Easy Ways to Create a New Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-correcting-not-working-error-in-windows/"><u>Breaking Down and Correcting 'Not Working' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-error-code-0x80070570-repair-corrupted-filesdirectories/"><u>Reversing Error Code 0X80070570: Repair Corrupted Files/Directories</u></a></li>
<li><a href="https://win11.techidaily.com/five-smart-choices-of-windows-devices/"><u>Five Smart Choices of Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-windows-11-pitfalls/"><u>Addressing Common Windows 11 Pitfalls</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-zdsofts-edge-masterful-video-capture-analysis/"><u>[New] ZDSoft's Edge  Masterful Video Capture Analysis</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-are-you-looking-for-a-filmora-discount-code-or-promo-coupon-code-here-are-5-trusted-and-genuine-solutions-to-get-a-discount-on-your-fi/"><u>Updated 2024 Approved Are You Looking for a Filmora Discount Code or Promo Coupon Code? Here Are 5 Trusted and Genuine Solutions to Get a Discount on Your Filmora Subscription</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-step-by-step-tutorial-applying-computer-vhs-filters/"><u>[Updated] 2024 Approved  Step-by-Step Tutorial  Applying Computer VHS Filters</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-notification-interface-in-win-11/"><u>Tailoring Your Notification Interface in Win 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-meizu-21-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Meizu 21?</u></a></li>
<li><a href="https://win11.techidaily.com/decrypting-wacatacbml-trojan-a-step-by-step-windows-cleanup/"><u>Decrypting Wacatac.B!ml Trojan: A Step-by-Step Windows Cleanup</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/1714952559821-new-2024-approved-top-10-audio-normalizers-for-windows-dont-miss-it/"><u>New 2024 Approved Top 10 Audio Normalizers for Windows. Dont Miss It</u></a></li>
<li><a href="https://win11.techidaily.com/risks-and-precautions-deleting-windows-bt-folder/"><u>Risks & Precautions: Deleting Windows ~BT Folder</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/detailed-guide-to-capturing-minecraft-gameplay-events-for-2024/"><u>Detailed Guide to Capturing Minecraft Gameplay Events for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-tech-appbrowser-rule/"><u>Understanding Windows Tech: App/Browser Rule</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-infinix-zero-30-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Infinix Zero 30 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-expert-picks-5-superior-video-call-recording-tools/"><u>[New] Expert Picks  5 Superior Video Call Recording Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-moto-g24-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola Moto G24</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-webclipper-facebook-videos/"><u>[Updated] WebClipper - Facebook Videos</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-upscale-your-old-videos-with-madvr-for-windows/"><u>How to Upscale Your Old Videos With MadVR for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unable-to-open-error-in-geforce-experience-windows/"><u>Resolving Unable to Open Error in GeForce Experience Windows</u></a></li>
<li><a href="https://win11.techidaily.com/crack-the-ms-pc-manager-install-issue-on-windows-xp/"><u>Crack the MS PC Manager Install Issue on Windows XP</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/igrating-spotify-written-content-for-a-streamlined-youtube-music-experience-for-2024/"><u>[New] Migrating Spotify' Written Content for a Streamlined YouTube Music Experience for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-s-best-free-video-compression-solutions-for-windows-10-users/"><u>Updated In 2024, S Best Free Video Compression Solutions for Windows 10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/restarting-routine-efficiently-installing-windows-11/"><u>Restarting Routine: Efficiently Installing Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-w11s-0x8004def5-onedrive-malfunction/"><u>Unraveling the Mystery of W11's 0X8004def5 OneDrive Malfunction</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-file-format-alterations-on-your-pc/"><u>Streamline File Format Alterations on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-deletion-with-windows-context-add-ons/"><u>Streamlining Deletion with Windows Context Add-Ons</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-comprehensive-guide-to-precision-screen-capture-for-2024/"><u>[New] The Comprehensive Guide to Precision Screen Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-display-panel-configurations/"><u>Rearranging Display Panel Configurations</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tips-for-truly-tuning-into-your-iphone-podcasts/"><u>In 2024, Tips for Truly Tuning Into Your iPhone Podcasts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-exploring-media-magic-an-in-depth-analysis-of-magix-vpx/"><u>2024 Approved  Exploring Media Magic  An In-Depth Analysis of Magix VPX</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17e-by-drfone-android/"><u>In 2024, How to Bypass FRP from Vivo S17e?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/conserve-space-not-time-youtube-video-length-adjustment/"><u>Conserve Space, Not Time  YouTube Video Length Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-difference-between-chkdsk-sfc-and-dism-in-windows/"><u>What Is the Difference Between CHKDSK, SFC, and DISM in Windows?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-streamlining-the-capture-of-podcast-archives-for-computer-devices/"><u>2024 Approved Streamlining the Capture of Podcast Archives for Computer Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumbled-glitches-win-1111-store-correction-guide/"><u>Bypassing 'Server Stumbled' Glitches: Win 11/11 Store Correction Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-onedrive-and-microsoft-id-for-pc-users/"><u>Bridging the Gap: OneDrive & Microsoft ID for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/silence-non-pertinent-windows-advisory-messages/"><u>Silence Non-Pertinent Windows Advisory Messages</u></a></li>
<li><a href="https://win11.techidaily.com/essential-reasons-why-pcs-outshine-macs-9/"><u>Essential Reasons Why PCs Outshine Macs (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-settings-managing-device-permissions/"><u>Navigating Windows Settings: Managing Device Permissions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-a-volume-on-windows-without-erasing-personal-data/"><u>How to Extend a Volume on Windows Without Erasing Personal Data</u></a></li>
</ul></div>
