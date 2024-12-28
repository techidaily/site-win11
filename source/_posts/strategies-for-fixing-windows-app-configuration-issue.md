---
title: Strategies for Fixing Windows App Configuration Issue
date: 2024-12-23T16:23:18.749Z
updated: 2024-12-28T04:18:12.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Fixing Windows App Configuration Issue
excerpt: This Article Describes Strategies for Fixing Windows App Configuration Issue
keywords: Windows App Config Repair,App Setting Error Fixed,Resolve WinApp Issues,Debugging WinApps Quickly,Windows App Setup Fix,Correcting WinConfig Problems,Streamline Windows App Setup
thumbnail: https://thmb.techidaily.com/1acb8c811dd75a749590a9459a8ce73dd17ec95c9b2687aeea798f4dbe27d8a4.jpg
---

## Strategies for Fixing Windows App Configuration Issue

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Open up your web browser and head over to the[Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see[how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the[best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-how-to-downloadsave-instagram-reels-video-in-2-ways/"><u>[New] 2024 Approved How to Download/Save Instagram Reels Video in 2 Ways</u></a></li>
<li><a href="https://article-files.techidaily.com/new-adding-flair-to-your-online-gatherings-an-in-depth-zoom-filter-guide-for-2024/"><u>[New] Adding Flair to Your Online Gatherings An In-Depth Zoom Filter Guide for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-ultimate-guide-to-non-vimeo-editing-software/"><u>[New] The Ultimate Guide to Non-Vimeo Editing Software</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-best-practices-for-youtube-to-igtv-transformation/"><u>[Updated] In 2024, Best Practices for YouTube to IGTV Transformation</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-live-links-debate-is-software-superior-to-gear-for-2024/"><u>[Updated] Live Links Debate Is Software Superior to Gear for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-premium-downloader-suite-for-vimeo-content/"><u>2024 Approved Premium Downloader Suite for Vimeo Content</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ease-of-disk-management-access-on-win-1011/"><u>Discover the Ease of Disk Management Access on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-accelerated-gpu-task-order-in-windows/"><u>Eliminating Accelerated GPU Task Order in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adjust-administrative-controlled-options-in-windows-11-os/"><u>How to Adjust Administrative Controlled Options in Windows 11 OS</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Vivo V30? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-facebook-messages-overcoming-window-snags/"><u>Mastering Facebook Messages: Overcoming Window Snags</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-windows-pin-issues/"><u>Mastering the Art of Fixed Windows PIN Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-tool-accessibility-settings/"><u>Mastering Windows 11'S Tool Accessibility Settings</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pathways-to-windows-performance-reports/"><u>Quick Pathways to Windows Performance Reports</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-restoring-corrupt-system-files-in-windows-10-and-11/"><u>Step-by-Step Tutorial: Restoring Corrupt System Files in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/thaw-frozen-handbrake-on-windows/"><u>Thaw Frozen HandBrake on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-artist-creating-captivating-ai-visuals-with-paint-cocreator-and-windows-11/"><u>Unleash Your Inner Artist: Creating Captivating AI Visuals with Paint Cocreator & Windows 11</u></a></li>
<li><a href="https://techidaily.com/vivo-y78-5g-music-recovery-recover-deleted-music-from-vivo-y78-5g-by-fonelab-android-recover-music/"><u>Vivo Y78 5G Music Recovery - Recover Deleted Music from Vivo Y78 5G</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721467435745-why-wont-my-iphone-back-up-to-icloud-here-are-9-fixes-that-work/"><u>Why Won’t My iPhone Back Up to iCloud? Here Are 9 Fixes That Work</u></a></li>
</ul></div>

