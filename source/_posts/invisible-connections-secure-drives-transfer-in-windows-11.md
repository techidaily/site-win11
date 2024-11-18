---
title: "Invisible Connections: Secure Drives Transfer in Windows 11"
date: 2024-11-15T00:18:11.227Z
updated: 2024-11-18T00:41:22.846Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on[how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-switch-strike-force-your-top-10-game-lineup/"><u>[New] 2024 Approved Switch Strike Force Your Top 10 Game Lineup</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-social-media-to-monetary-success-the-roadmap-for-instagram-sponsorship-for-2024/"><u>[Updated] From Social Media to Monetary Success The Roadmap for Instagram Sponsorship for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-master-class-selecting-the-top-10-4k-shoulder-rigs-for-2024/"><u>[Updated] Master Class Selecting the Top 10 4K Shoulder Rigs for 2024</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/10-en-un-disco-duro-exterior-metodos-faciles/"><u>10 en Un Disco Duro Exterior - Métodos Fáciles</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-os-repair-procedures-chkdsk-sfc-dism-insights/"><u>Deciphering OS Repair Procedures: CHKDSK, SFC, DISM Insights</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-updated-amd-rx-6800-xt-drivers-for-optimal-performance-on-windows-pcs-windows-111087/"><u>Download Updated AMD RX 6800 XT Drivers for Optimal Performance on Windows PCs (Windows 11/10/8/7)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/from-standard-to-spectacomed-adding-fonts-to-after-effects-workflow/"><u>From Standard to Spectacomed Adding Fonts to After Effects Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-directx-download-issues-in-os/"><u>How to Rectify DirectX Download Issues in OS</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-god-mode-in-windows-11-a-compreranble-approach/"><u>Mastering God Mode in Windows 11: A Compreranble Approach</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-null-sound-driver-error-on-windows-pc/"><u>Resolving Null Sound Driver Error on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-dreaded-wacatacbml-trojan-identification-and-removal-strategies/"><u>The Dreaded Wacatac.B!ml Trojan - Identification and Removal Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-improving-laptop-performance-with-external-monitors/"><u>Tips for Improving Laptop Performance with External Monitors</u></a></li>
</ul></div>

