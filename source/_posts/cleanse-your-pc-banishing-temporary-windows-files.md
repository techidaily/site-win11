---
title: "Cleanse Your PC: Banishing Temporary Windows Files"
date: 2025-02-14T23:32:32.565Z
updated: 2025-02-16T03:40:34.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cleanse Your PC: Banishing Temporary Windows Files"
excerpt: "This Article Describes Cleanse Your PC: Banishing Temporary Windows Files"
keywords: PC Cleanup Guide,Remove Temp Files,Optimize Windows,Delete Windows Junk,Speed Up PC,Clear Temporary Data,Free Disk Space
thumbnail: https://thmb.techidaily.com/280632bcded78a124b04e053c7d047b36940366fb100b93a3444f92f9f5d3614.jpg
---

## Cleanse Your PC: Banishing Temporary Windows Files

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-evaluating-professional-filmmaking-tools-filmora-and-democreator-for-2024/"><u>[New] Evaluating Professional Filmmaking Tools Filmora & Democreator for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-cutting-edge-cameras-for-extreme-enthusiasts/"><u>[Updated] 2024 Approved Cutting-Edge Cameras for Extreme Enthusiasts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-choosing-the-best-mac-mkv-players-guide-for-2024/"><u>[Updated] Choosing the Best Mac MKV Players Guide for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-vivid-imagery-with-nikon-j5s-4k-capability-revealed/"><u>2024 Approved Vivid Imagery with Nikon J5's 4K Capability Revealed</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-realme-c55-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Realme C55? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/digital-artistry-in-depth-on-ps-distortion-techniques/"><u>Digital Artistry In-Depth on PS Distortion Techniques</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-review-of-the-asus-proart-pa32ucxr-the-epitome-of-precision-in-workstation-displays/"><u>Expert Review of the Asus ProArt PA32UCXR: The Epitome of Precision in Workstation Displays</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-your-files-optimizing-deletion-dialogues-in-windows/"><u>Fine-Tuning Your Files: Optimizing Deletion Dialogues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-zip-or-unzip-files-using-the-command-prompt-and-windows-powershell/"><u>How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-non-recoverable-trash-into-your-windows-workspace/"><u>Integrating Non-Recoverable Trash Into Your Windows Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-avoiding-disk-read-errors/"><u>Mastering Windows: Avoiding Disk Read Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-errors-in-windows-11-for-seamless-internet-access/"><u>Overcoming Network Errors in Windows 11 for Seamless Internet Access</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-poco-x6-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Poco X6</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-dll-failure-in-steam-interface/"><u>Steps to Correct DLL Failure in Steam Interface</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-utilizing-windows-11-mixer-menu/"><u>Understanding and Utilizing Windows 11 Mixer Menu</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-microsofts-phone-link-application-functionality/"><u>Understanding Microsoft's Phone Link Application Functionality</u></a></li>
</ul></div>

