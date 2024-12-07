---
title: How to Eliminate Error 0X80073D26 From Your Microsoft Store
date: 2024-11-30T17:49:52.868Z
updated: 2024-12-07T05:14:06.201Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Eliminate Error 0X80073D26 From Your Microsoft Store
excerpt: This Article Describes How to Eliminate Error 0X80073D26 From Your Microsoft Store
keywords: Fixing Error X73D26 MSStore,Eradicate MSStore Error 073D26,Removing OS Error 0X80073D26,Resolve Windows Store Error,Overcome Error 73D26 in Microsoft Store,Eliminate X73D26 MSStore Issue,Solve MSStore Error 73D26
thumbnail: https://thmb.techidaily.com/634ac9f760c3e79a9b2c54edc99fe994b8053a847fb1d16c5b184059bb3a3f2f.png
---

## How to Eliminate Error 0X80073D26 From Your Microsoft Store

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-digital-detailing-expert-tips-for-attaching-dates-in-photography/"><u>[New] 2024 Approved Digital Detailing Expert Tips for Attaching Dates in Photography</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-get-official-passport-photo-online-download-and-print-your-portraits-for-free/"><u>[New] 2024 Approved Get Official Passport Photo Online – Download & Print Your Portraits for FREE</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-in-depth-assessment-comprehensive-camstudio-toolkit/"><u>[New] In 2024, In-Depth Assessment Comprehensive CamStudio Toolkit</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-play-40c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor Play 40C? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/are-camera-shakes-less-troublesome-after-photostable-effects-for-2024/"><u>Are Camera Shakes Less Troublesome After PhotoStable Effects for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-restarts-for-distro-and-catroot2-in-latest-ws11-os/"><u>Efficient Restarts for Distro & Catroot2 in Latest WS11 OS</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ce-branding-the-ultimate-guide-to-custom-urls-for-youtube/"><u>Enhance Branding The Ultimate Guide to Custom URLs for YouTube</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-decoding-second-count-in-20mb-video-files/"><u>In 2024, Decoding Second Count in 20MB Video Files</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-discover-the-world-in-360-watching-vr-videos-on-iphone/"><u>In 2024, Discover the World in 360 Watching VR Videos on iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-malfunctioning-asana-applications-on-your-computer/"><u>Mastery Over Malfunctioning Asana Applications on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/nostalgic-gaming-revived-techniques-for-using-retroarchs-shaders/"><u>Nostalgic Gaming Revived: Techniques for Using RetroArch’s Shaders</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-pubgs-save-functionality-windows/"><u>Regaining Control Over PUBG's Save Functionality (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11s-calculator-opening-process/"><u>Simplifying Windows 11'S Calculator Opening Process</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-returning-windows-11-to-original-search-layout/"><u>Step-by-Step: Returning Windows 11 to Original Search Layout</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-overheating-pcs-with-windows-resource-monitor-insights/"><u>Tackling Overheating PCs with Windows Resource Monitor Insights</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-strategy-for-top-tier-youtube-titles-and-tags-for-2024/"><u>The Ultimate Strategy for Top-Tier Youtube Titles & Tags for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-hardware-in-windows/"><u>Troubleshooting Unresponsive Audio Hardware in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-virtual-capacity-with-these-6-windows-tricks/"><u>Unlock Full Virtual Capacity with These 6 Windows Tricks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    