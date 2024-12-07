---
title: Safe Deletion Practices for Windows ~BT Folders
date: 2024-11-30T16:53:06.370Z
updated: 2024-12-06T21:34:29.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safe Deletion Practices for Windows ~BT Folders
excerpt: This Article Describes Safe Deletion Practices for Windows ~BT Folders
keywords: Safe BT Delete,Secure Windows Erase,BT Files Cleanup,Safe File Removal,Windows Security Purge,Deletion Safety Tips,Protecting Batch Data
thumbnail: https://thmb.techidaily.com/3940086541c823408b7e3893cd4adcfe04714cf8a1d0ceb2c3d06364d867bc68.png
---

## Safe Deletion Practices for Windows ~BT Folders

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/op-10-hilarious-song-mock-ups-laughter-unleashed/"><u>[New] Top 10 Hilarious Song Mock-Ups Laughter Unleashed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-camcraze-evaluation-excellence-beyond-one-brand/"><u>[Updated] In 2024, CamCraze Evaluation Excellence Beyond One Brand</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-ps5xbox-series-x-gaming-sets-the-top-5-list/"><u>[Updated] PS5/Xbox Series X Gaming Sets The Top 5 List</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-uniting-choreography-with-crafted-audio-in-instagram/"><u>[Updated] Uniting Choreography with Crafted Audio in Instagram</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/boost-your-mobile-performance-discover-motorolas-innovative-350-device-packing-a-built-in-stylus-and-expanded-storage/"><u>Boost Your Mobile Performance: Discover Motorola's Innovative $350 Device Packing a Built-In Stylus and Expanded Storage!</u></a></li>
<li><a href="https://win11.techidaily.com/elite-selection-top-156-characters-nintendo-switch-simulators/"><u>Elite Selection: Top 156 Characters Nintendo Switch Simulators</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-storage-solutions-the-role-of-windows-iscsi-initiator/"><u>Exploring Storage Solutions: The Role of Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-windows-net-core-demand/"><u>Guide to Overcoming Windows' .NET Core Demand</u></a></li>
<li><a href="https://extra-information.techidaily.com/highlighting-heroics-at-the-x-olympics-2022/"><u>Highlighting Heroics at the X-Olympics 2022</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-oppo-a38-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-lightning-fast-windows-evaluation-path/"><u>In 2024, Lightning-Fast Windows Evaluation Path</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-top-10-titans-of-aerial-lifting-technology/"><u>In 2024, Top 10 Titans of Aerial Lifting Technology</u></a></li>
<li><a href="https://win11.techidaily.com/opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-network-setup-mastering-dns-on-windows-11/"><u>Optimal Network Setup: Mastering DNS on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-pin-inaccessibility-after-windows-11-software-errors/"><u>Restoring PIN Inaccessibility After Windows 11 Software Errors</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-self-extraction-a-win11-approach/"><u>Simplifying Self-Extraction: A Win11 Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-steam-library-accessibility-issues-on-windows-11/"><u>Streamlining Steam Library Accessibility Issues on Windows 11</u></a></li>
</ul></div>

