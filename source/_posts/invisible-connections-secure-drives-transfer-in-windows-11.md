---
title: "Invisible Connections: Secure Drives Transfer in Windows 11"
date: 2024-11-02T18:37:27.644Z
updated: 2024-11-07T16:18:56.881Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Invisible Connections: Secure Drives Transfer in Windows 11"
excerpt: "This Article Describes Invisible Connections: Secure Drives Transfer in Windows 11"
keywords: Secure Drive Transfer W11,InvisiLink Windows,Data Privacy Win11,Stealthy File Sync,Windows Secure Sharing,IntSecure Drive Link,Hidden Connect Win
thumbnail: https://thmb.techidaily.com/e788f79a8684ff135a50b06576e0943a8c2779cab90284e9a264c3a4912b0271.png
---

## Invisible Connections: Secure Drives Transfer in Windows 11

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on[how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful[not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.

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
<li><a href="https://extra-approaches.techidaily.com/new-start-your-quest-for-quick-snapstreaming-today/"><u>[New] Start Your Quest for Quick Snapstreaming Today</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-optimize-tasks-the-8-superior-facebook-schedulers/"><u>2024 Approved Optimize Tasks The 8 Superior Facebook Schedulers</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-vivo-s18-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Vivo S18 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-lava-storm-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Lava Storm 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-realme-12-pro-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Realme 12 Pro 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/budget-savvy-shoppers-best-cameras-for-2024/"><u>Budget-Savvy Shoppers' Best Cameras for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-review-of-the-xp-pen-artist-16-pro-the-ultimate-drawing-tablet/"><u>Comprehensive Review of the XP-Pen Artist 16 Pro: The Ultimate Drawing Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-find-and-delete-empty-folders-on-windows/"><u>How to Find and Delete Empty Folders on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/integrating-c270-webcam-with-modern-windows-11-system/"><u>Integrating C270 Webcam with Modern Windows 11 System</u></a></li>
<li><a href="https://some-approaches.techidaily.com/soluciones-rapidas-para-quitar-ojos-rojos-en-fotografias-usando-movavis-tools/"><u>Soluciones Rápidas Para Quitar Ojos Rojos en Fotografías Usando Movavi's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-windows-1011s-unable-to-open-share-error/"><u>Steps to Solve Windows 10/11'S Unable to Open Share Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-usb30-device-malfunctions-in-windows/"><u>Steps to Tackle USB3.0 Device Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taking-back-control-with-fresh-windows-11-installation/"><u>Taking Back Control with Fresh Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-adjusting-file-deletion-warnings/"><u>Understanding & Adjusting File Deletion Warnings</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-shutdown-4-steps-for-windows-firewall/"><u>Unlocking the Shutdown: 4 Steps for Windows' Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-rapid-response-feature-windows-11s-qa-tool/"><u>Utilizing Rapid Response Feature: Windows 11'S QA Tool</u></a></li>
</ul></div>

