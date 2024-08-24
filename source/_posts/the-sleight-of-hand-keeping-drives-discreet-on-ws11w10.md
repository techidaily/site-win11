---
title: "The Sleight of Hand: Keeping Drives Discreet on WS11/W10"
date: 2024-08-23T06:09:18.620Z
updated: 2024-08-24T06:09:18.620Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Sleight of Hand: Keeping Drives Discreet on WS11/W10"
excerpt: "This Article Describes The Sleight of Hand: Keeping Drives Discreet on WS11/W10"
keywords: Drive Discretion (WS11),WS11 Secrecy Tips,WS11 Data Hiding,WS10 Stealth Storage,WS10 Privacy Techniques,WS10 Anonymity Strategies,Discreet Drive Management
thumbnail: https://thmb.techidaily.com/1f7a28a8bb8145eaefcf7bd927fe30950467d63b1317d80297e6274f57adb5a8.jpg
---

## The Sleight of Hand: Keeping Drives Discreet on WS11/W10

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
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
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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
<li><a href="https://youtube-video-recordings.techidaily.com/new-edit-like-a-championtop-strategies-for-beginner-youtubers/"><u>[New] Edit Like a Champion—Top Strategies for Beginner YouTubers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-gasp-and-guffaw-10-instagram-pages-where-laughter-meets-tears/"><u>[Updated] Gasp & Guffaw  10 Instagram Pages Where Laughter Meets Tears</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ideal-webcams-elevating-podcast-production/"><u>[Updated] Ideal Webcams Elevating Podcast Production</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-audiovisual-excellence-the-premier-video-formats-for-youtube/"><u>[Updated] In 2024, Audiovisual Excellence  The Premier Video Formats for YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-quick-tips-eradicate-online-ads-from-your-feed/"><u>[Updated] In 2024, Quick Tips  Eradicate Online Ads From Your Feed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-mastering-lol-recording-three-easy-techniques/"><u>[Updated] Mastering LOL Recording  Three Easy Techniques</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-circle-of-connectivity-spotlighting-instas-top-25-influencers/"><u>[Updated] The Circle of Connectivity  Spotlighting Insta's Top 25 Influencers</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-best-budget-asmr-mic-stellar-sound-value/"><u>2024 Approved  Best Budget ASMR Mic  Stellar Sound Value</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combating-the-deadly-windows-10-fatality-code-c0000022/"><u>Combating the Deadly Windows 10 Fatality Code C0000022</u></a></li>
<li><a href="https://win11.techidaily.com/create-order-in-chaos-master-these-5-advanced-window-folder-tactics/"><u>Create Order in Chaos: Master These 5 Advanced Window Folder Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/curing-windows-error-elusive-startup-items/"><u>Curing Windows Error: Elusive Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-discarding-your-windows-11-trail/"><u>Deciphering and Discarding Your Windows 11 Trail</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-the-iomap64-syscall-failure-blue-screen/"><u>Deciphering and Fixing the IOMap64 Syscall Failure Blue Screen</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-horizons-exploring-facebooks-stealthy-smartwatch-creation/"><u>Digital Horizons: Exploring Facebook's Stealthy Smartwatch Creation</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-airflow-for-windows-11-gadgets/"><u>Enhancing Airflow for Windows 11 Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-achieving-a-90-degree-display-flip/"><u>Expert Advice on Achieving a 90-Degree Display Flip</u></a></li>
<li><a href="https://win11.techidaily.com/formulating-enduring-file-disposal-strategies-on-windows-systems/"><u>Formulating Enduring File Disposal Strategies on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-vivo-x100-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Vivo X100 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-no-device-drivers-were-found-error-while-installing-windows/"><u>How to Fix the No Device Drivers Were Found Error While Installing Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-on-apple-iphone-14-plus-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud on Apple iPhone 14 Plus Safe and Legal</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-heres-everything-you-should-know-about-pokemon-stops-in-detail-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Heres Everything You Should Know About Pokemon Stops in Detail On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-master-seminar-script-synthesizer/"><u>In 2024, Master Seminar Script Synthesizer</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-tutorial-on-3d-lut-tools/"><u>In 2024, Ultimate Tutorial on 3D LUT Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-your-pathway-to-profit-the-most-straightforward-top-10-business-channels-on-youtube/"><u>In 2024, Your Pathway to Profit  The Most Straightforward Top 10 Business Channels on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagram-story-and-reels-transform-your-vocal-brand-with-these-tricks-for-2024/"><u>Instagram Story & Reels  Transform Your Vocal Brand with These Tricks for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unlocking-compressors-full-potential-in-fcpx/"><u>New 2024 Approved Unlocking Compressors Full Potential in FCPX</u></a></li>
<li><a href="https://extra-tips.techidaily.com/next-gen-photography-unveiling-auto-and-smart-hdr-features/"><u>Next-Gen Photography  Unveiling Auto and Smart HDR Features</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workflow-with-windows-and-sudo-integration/"><u>Optimize Your Workflow with Windows & Sudo Integration</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-denial-on-windows-11/"><u>Overcoming File Access Denial on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pace-up-tech-locating-gpu-specifications-on-windows-11/"><u>Pace Up Tech: Locating GPU Specifications on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-windows-11-taskbar-icons-layout/"><u>Perfecting Windows 11 Taskbar Icons Layout</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-unlocking-your-os-control-panel/"><u>Quick Access: Unlocking Your OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-seven-ways-to-bridge-obs-studios-network-gap-in-windows/"><u>Quick Guide: Seven Ways to Bridge OBS Studio's Network Gap in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-method-to-shut-off-windows-11-alerts/"><u>Quick Method to Shut Off Windows 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-methods-refreshing-windows-pc-eightfold/"><u>Reboot Methods: Refreshing Windows PC Eightfold</u></a></li>
<li><a href="https://win11.techidaily.com/remedies-for-low-memory-indicators-in-windows-based-vmware/"><u>Remedies for Low Memory Indicators in Windows-Based VmWare</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unselectable-text-in-windows-pdf-viewers/"><u>Resolve Unselectable Text in Windows' PDF Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-chrome-file-downloads-issue-in-windows/"><u>Resolving Chrome File Downloads Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/speed-difference-how-to-match-pc-and-android-connectivity/"><u>Speed Difference: How to Match PC and Android Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-no-data-usb-devices-in-microsoft-systems/"><u>Strategies for Fixing No-Data USB Devices in Microsoft Systems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-handle-source-file-error-in-windows-1110/"><u>Strategies to Handle Source File Error in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-rectify-non-previewable-documents-in-outlook/"><u>Strategies to Rectify Non-Previewable Documents In Outlook</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/streamlining-your-ps3-recorded-experiences-for-2024/"><u>Streamlining Your PS3 Recorded Experiences for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-stuck-easy-fixes-for-w11w10-users/"><u>Synapse Stuck? Easy Fixes for W11/W10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-issue-0x800704b3-in-windows/"><u>Tackling Network Issue 0X800704B3 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-xpatch-problem-error-code-0x80073712/"><u>Tackling XPatch Problem: Error Code 0X80073712</u></a></li>
<li><a href="https://fox-direct.techidaily.com/techniques-for-smoothly-fading-audio-within-lumafusion/"><u>Techniques for Smoothly Fading Audio Within Lumafusion</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peaceful-application-management-in-window-11/"><u>The Path to Peaceful Application Management in Window 11</u></a></li>
<li><a href="https://win11.techidaily.com/unite-pilot-and-ai-on-windows-11-after-disconnection/"><u>Unite Pilot & AI on Windows 11 After Disconnection</u></a></li>
<li><a href="https://win11.techidaily.com/use-accessibility-features-utilize-features-like-narrator-magnifier-and-text-size-adjustment-for-better-visibility-without-altering-display-settings-drastic29/"><u>Use Accessibility Features: Utilize Features Like Narrator, Magnifier, and Text Size Adjustment for Better Visibility without Altering Display Settings Drastically</u></a></li>
<li><a href="https://win11.techidaily.com/win11-activating-new-widget-selection-interface/"><u>Win11: Activating New Widget Selection Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-command-line-expertise-the-top-20-must-know-commands/"><u>Windows Command Line Expertise: The Top 20 Must-Know Commands</u></a></li>
<li><a href="https://win11.techidaily.com/windows-screen-grabs-snip-tool-versus-print-screen-efficacy/"><u>Windows Screen Grabs: Snip Tool Versus Print Screen Efficacy</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-influence-on-desktop-linux-landscape-shift/"><u>WSL Influence on Desktop Linux Landscape Shift</u></a></li>
</ul></div>
