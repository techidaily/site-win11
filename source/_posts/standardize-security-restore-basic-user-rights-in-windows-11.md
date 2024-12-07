---
title: "Standardize Security: Restore Basic User Rights in Windows 11"
date: 2024-12-02T00:02:00.239Z
updated: 2024-12-07T05:21:11.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Standardize Security: Restore Basic User Rights in Windows 11"
excerpt: "This Article Describes Standardize Security: Restore Basic User Rights in Windows 11"
keywords: Win11 Secure Basics,UserRights Windows Update,Standardizing Windows Safety,Revive UAC Windows 11,Enhance Windows Permissions,UX Rights Restoration,Windows Security Standards
thumbnail: https://thmb.techidaily.com/8bc720ee0adbf09ae88a648a38e027832e102c5d3884a2078035ea55eb60772c.jpg
---

## Standardize Security: Restore Basic User Rights in Windows 11

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.

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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-navigating-the-seas-of-saving-facebook-gifs-on-various-tech-platforms/"><u>[New] 2024 Approved Navigating the Seas of Saving Facebook GIFs on Various Tech Platforms</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/olishing-resilience-for-online-criticism-for-2024/"><u>[New] Polishing Resilience for Online Criticism for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-symphony-of-streams-harmonizing-your-multiple-youtube-views/"><u>[Updated] 2024 Approved A Symphony of Streams Harmonizing Your Multiple YouTube Views</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-chart-topping-content-youtubes-top-5/"><u>[Updated] In 2024, Chart-Topping Content YouTube's Top 5</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-prime-collection-best-10-apps-for-extracting-high-quality-vimeo-videos/"><u>[Updated] In 2024, Prime Collection Best 10 Apps for Extracting High-Quality Vimeo Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-low-cost-pc-monitoring-solutions-reviewed-and-compared-for-2024/"><u>[Updated] Low-Cost PC Monitoring Solutions Reviewed & Compared for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-elevated-wudfhostexe-cpu-usage-on-your-windows-11-system-expert-tips-and-solutions/"><u>Dealing with Elevated WUDFHost.exe CPU Usage on Your Windows 11 System - Expert Tips & Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/hibernation-vs-standby-windows-comparisons/"><u>Hibernation Vs. Standby: Windows Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-group-policy-settings-on-individual-windows-accounts/"><u>Personalizing Group Policy Settings on Individual Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-enabling-wordpad-in-windows-environment/"><u>Quick Start: Enabling WordPad in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-audacitys-error-when-opening-sounds-on-win11/"><u>Remedying Audacity's Error When Opening Sounds on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/safe-windows-best-free-software-download-picks/"><u>Safe Windows: Best Free Software Download Picks</u></a></li>
<li><a href="https://article-tips.techidaily.com/simplifying-video-editing-with-windows-movie-maker-for-windows-8-users/"><u>Simplifying Video Editing with Windows Movie Maker for Windows 8 Users</u></a></li>
<li><a href="https://win11.techidaily.com/switching-chromes-block-webp-format-for-saved-pics-windows-based/"><u>Switching Chromes: Block WebP Format for Saved Pics, Windows-Based</u></a></li>
<li><a href="https://win-reviews.techidaily.com/tout-savoir-pour-envoyer-des-photos-diphone-vers-un-ordinateur-en-utilisant-la-technologie-bluetooth/"><u>Tout Savoir Pour Envoyer Des Photos D'iPhone Vers Un Ordinateur en Utilisant La Technologie Bluetooth</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-digital-files-onedrive-fixes-for-windows/"><u>Unlocking Your Digital Files: OneDrive Fixes for Windows</u></a></li>
</ul></div>

