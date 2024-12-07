---
title: Understanding LSA Failure Causes, Fixes for Windows
date: 2024-12-04T23:22:39.907Z
updated: 2024-12-06T19:51:34.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding LSA Failure Causes, Fixes for Windows
excerpt: This Article Describes Understanding LSA Failure Causes, Fixes for Windows
keywords: LSA Failures,Windows SysFix,Win LSA Troubleshoot,Fix LSA Issues,Resolve Win LSA,LSA Errors in Win OS,SysLSA Windows Repair
thumbnail: https://thmb.techidaily.com/6ed52b8d826a5b6701c9229d81239cb21a1a6ea95480871656b8b252c90f9890.jpeg
---

## Understanding LSA Failure Causes, Fixes for Windows

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.

7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-efficient-techniques-for-capturing-google-voice-calls-for-2024/"><u>[New] Efficient Techniques for Capturing Google Voice Calls for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-skyrocketing-youtube-views-strategies-to-dodge-bots/"><u>[Updated] In 2024, Skyrocketing YouTube Views Strategies to Dodge Bots</u></a></li>
<li><a href="https://blog-min.techidaily.com/1-ultimate-guide-how-to-combine-mp3s-efficiently-on-windows-11/"><u>1. Ultimate Guide: How to Combine MP3s Efficiently on Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-achieve-seamless-video-playback-by-removing-bars-in-youtube/"><u>2024 Approved Achieve Seamless Video Playback by Removing Bars in YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-ai-potential-for-ultimate-user-experience-at-ms-store/"><u>Harnessing AI Potential for Ultimate User Experience at MS Store</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-best-practice-manual-for-text-on-picture-edits/"><u>In 2024, The Best Practice Manual for Text-on-Picture Edits</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-printer-access-within-application-guards-secure-environment/"><u>Initiating Printer Access Within Application Guard's Secure Environment</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-realme-12-proplus-5g-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-best-of-the-best-top-rated-2d-animation-software-free-trials-and-paid-plans/"><u>New 2024 Approved The Best of the Best Top-Rated 2D Animation Software Free Trials & Paid Plans</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recovery-from-crushing-windows-c0000022-error/"><u>Steps to Recovery From Crushing Window's C0000022 Error</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1125700-9781609256432-the-everyday-psychic/"><u>The Everyday Psychic | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-grouping-files-into-windows-11-directories/"><u>The Ultimate Guide to Grouping Files Into Windows 11 Directories</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-unblocking-screen-settings-on-pcs/"><u>The Ultimate Guide to Unblocking Screen Settings on PCs</u></a></li>
<li><a href="https://fox-access.techidaily.com/troubleshooting-tips-for-a-stable-windows-11-photo-experience/"><u>Troubleshooting Tips for a Stable Windows 11 Photo Experience</u></a></li>
</ul></div>

