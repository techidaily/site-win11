---
title: Overcoming Unresponsive Shadow Copies Issue
date: 2024-12-04T03:05:51.342Z
updated: 2024-12-07T00:57:20.776Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Unresponsive Shadow Copies Issue
excerpt: This Article Describes Overcoming Unresponsive Shadow Copies Issue
keywords: Fixing Shadow Copy Errors,Resolve SharePoint Backups,Repair Drive Sync Issues,Correct Copy Archive Failures,Eliminate VHD Problems,Mend Disk Mirroring Fails,Solve Shadowspace Malfunction
thumbnail: https://thmb.techidaily.com/2ceae87a9b9364e8de7f8199f6943542799e9e444d1e94cece6744b91d0b78e1.jpg
---

## Overcoming Unresponsive Shadow Copies Issue

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-one-frame-at-a-time-how-to-extract-images-from-windows-10-movie-files/"><u>[New] 2024 Approved One Frame at a Time How To Extract Images From Windows 10 Movie Files</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-origami-and-samurai-inspirations-for-minecraft-homes/"><u>[New] 2024 Approved Origami & Samurai Inspirations for Minecraft Homes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-experts-choice-best-practices-for-vimeo-video-download/"><u>[New] Expert's Choice Best Practices for Vimeo Video Download</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-mastering-soft-melodies-pcos-guide/"><u>[New] Mastering Soft Melodies PC/OS Guide</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-speedy-image-viewer-powered-by-windows-11-for-2024/"><u>[New] Speedy Image Viewer Powered by Windows 11 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-seamless-dolby-atmos-setup-in-your-pc/"><u>Expert Tips for Seamless Dolby Atmos Setup in Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-wallpaper-image-storage-on-windows-11/"><u>Exploring Wallpaper Image Storage on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/funny-robots-unveiling-pc-history-and-virtual-network-protection/"><u>Funny Robots: Unveiling PC History and Virtual Network Protection</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>How to Address Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-infinix-note-30-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Infinix Note 30 5G FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/increase-productivity-hotkey-hacks-on-your-mouse/"><u>Increase Productivity: Hotkey Hacks on Your Mouse</u></a></li>
<li><a href="https://win11.techidaily.com/master-github-desktop-usage-for-effective-windows-devops/"><u>Master GitHub Desktop Usage for Effective Windows DevOps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-use-of-microsofts-security-tool-canary/"><u>Mastering the Use of Microsoft's Security Tool Canary</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-final-cut-pro-x-jump-cuts-take-your-editing-to-the-next-level-for-2024/"><u>New Final Cut Pro X Jump Cuts Take Your Editing to the Next Level for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/new-to-windows-learn-basic-accessibility-tools/"><u>New to Windows? Learn Basic Accessibility Tools</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-excel-opening-issue-with-notepad-windows/"><u>Troubleshoot: Excel Opening Issue with Notepad Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-netgear-secrets-the-ultimate-default-password-directory-for-july-2024/"><u>Unlocking Netgear Secrets: The Ultimate Default Password Directory for July 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1126171-9781609254605-what-is-occultism/"><u>What Is Occultism? | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-mastering-the-removal-of-error-3-from-nvidia-opengl/"><u>Win10/11: Mastering the Removal of Error 3 From Nvidia OpenGL</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    