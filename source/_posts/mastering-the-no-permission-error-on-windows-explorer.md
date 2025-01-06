---
title: Mastering the 'No Permission' Error on Windows Explorer
date: 2025-01-03T16:57:36.054Z
updated: 2025-01-06T16:47:02.954Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the 'No Permission' Error on Windows Explorer
excerpt: This Article Describes Mastering the 'No Permission' Error on Windows Explorer
keywords: No PermError WinExplorer Mastery,Handling NoPerm in Explorer,Fix NoPerm Windows Explorer,No Perm Essentials,Overcoming 'No Perm' On Explorer,NoPermit Error Solutions Explorer,Navigate NoPermission Explorer
thumbnail: https://thmb.techidaily.com/6d09665be2a2fe83c31f111bbc0153ce5984e036a76c36457898ede132e8d028.jpg
---

## Mastering the 'No Permission' Error on Windows Explorer

 Did you encounter an error message when opening photos on an external hard drive? The message says "It looks like you don't have permission to view this file. Check the permissions and try again." The error implies that Windows Photos or File Explorer is not authorized to access this file.

 In this article, we explain how to fix this error, so you can view your photos again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Can't You View the File?

 You may encounter this error if your external hard drive is connected to a device without the right permissions settings. Other possible causes include user account control settings which restrict access to external drives, or a corrupted Windows Photos app.

 Now you know what causes this error, let's explore the solution.

## 1\. Grant Full Control Permissions

 It looks like the main issue causing this error is that Windows doesn’t have sufficient permissions to access the file. To fix this, you must grant full control permissions to the account or user accessing the file. Here are the steps to follow:

1. Right-click on the folder and choose **Properties**.
2. In the Properties window, go to the **Security** tab.
3. Select the user account or group from the list and click **Edit**.
4. Under the **Permissions** section, check the box next to **Full Control**.  
![Grant Full Control Permissions to an user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/grant-full-control-permissions-to-an-user-account.jpg)
5. Click **Apply** and **OK** to save the changes.

 After making these changes, try viewing the photos again and checking if the error has been resolved.

## 2\. Take Ownership of the Folder

 If granting full control permissions does not work, take ownership of the folder to get more control. Taking ownership means you can manage, access, and delete files within it. Here's how to do it:

1. Right-click on the folder and select **Properties** from the context menu.
2. Switch to the **Security** tab, then click **Advanced** at the bottom.
3. In the Advanced Security Settings window, make sure you're on the **Permissions** tab.
4. Click on **Change** next to **Owner** in the top section.  
![Advanced Security Settings for Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-security-settings-for-folders.jpg)
5. In the dialog box, type **Everyone** and click **Check Names**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enter the object name to select user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enter-the-object-name-to-select-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. If it seems correct, click **OK**.
2. Check the box next to **Replace owner on subcontainers and objects**.  
![Take Ownership of the Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/take-ownership-of-the-folder.jpg)
3. Now click Apply. A pop-up appears and asks you to confirm the ownership change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click **Yes** and wait for the process to finish.
5. Once done, click **OK** and close the window.

 After that, restart your computer and try accessing the folder.

## 3\. Reset the Photos App

 Another way to fix this error is to reset the Photos app. Resetting the app will delete all settings and cached data and restore it to its default state. Here’s how to reset the Photos app:

1. Press **Win + I** to open the Settings menu.
2. From the left pane, click **Apps** \> **Installed apps**.
3. Scroll down to find the **Microsoft Photos** app. You can also use the search bar to find it.  
![Microsoft Photos App in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-photos-app-in-settings.jpg)
4. Click on the three dots and select **Advanced options**.
5. Under the **Reset** section, click the **Reset** button.  
![Reset Microsoft Photos App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-microsoft-photos-app.jpg)
6. If a pop-up appears, click **Reset** again to confirm your action.

 After that, try to open photos on your external hard drive.

## 4\. Disable UAC Temporarily

 You may often find that you don’t have enough permissions to perform specific tasks. In such cases, [disabling UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) may do the trick. So, disable it temporarily and see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Run the Program Compatibility Troubleshooter

 If you're still encountering the error, try [running the Program Compatibility Troubleshooter](http://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/). This tool scans for compatibility issues with installed programs and solves them automatically.

## Open Files Without a Problem Again on Windows

 If you have the proper permissions, you should not encounter the "you don’t have permission to view this file” message. However, if you run into this issue, read this guide to resolve it quickly. Make sure you grant all permissions and take ownership of the folder.

 In this article, we explain how to fix this error, so you can view your photos again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/2024-approved-audiovisual-format-fusion-srt-to-ttml-and-ssa-mastery/"><u>2024 Approved Audiovisual Format Fusion SRT to TTML & SSA Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-identify-and-delete-null-space-in-your-windows-drives/"><u>Discover How to Identify and Delete Null Space in Your Windows Drives</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnected-servers-restoring-access-to-ms-sql-and-malwarebytes/"><u>Fixing Disconnected Servers: Restoring Access to MS SQL & Malwarebytes</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-find-and-update-your-asus-laptops-software-drivers/"><u>How to Find and Update Your ASUS Laptop's Software Drivers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-samsung-galaxy-m14-4g-lock-screen-password-by-drfone-android/"><u>How to Reset your Samsung Galaxy M14 4G Lock Screen Password</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-honor-70-lite-5g-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Honor 70 Lite 5G FRP</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-peek-at-sonys-high-end-smartphone-the-xperia-xz-4k-reveal/"><u>In 2024, Peek at Sony's High-End Smartphone - The Xperia XZ 4K Reveal</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-winx-error-0x80246007-fix/"><u>Step-by-Step Guide to WinX Error 0X80246007 Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-broken-keys-on-modern-microsoft-operating-systems/"><u>Step-by-Step Guide: Restoring Broken Keys on Modern Microsoft Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-resolving-winerror-709/"><u>Steps for Resolving WinError 709</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/transforme-gratuitement-votre-fichier-wmv-en-format-mp4-avec-videosan/"><u>Transforme Gratuitement Votre Fichier WMV en Format MP4 Avec Vidéosan</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-installers-on-windows-os/"><u>Troubleshooting Failed Installers on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-windows-ui-with-customizable-portable-tools/"><u>Upgrade Windows UI with Customizable Portable Tools</u></a></li>
</ul></div>

