---
title: Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs
date: 2024-08-23T06:07:43.848Z
updated: 2024-08-24T06:07:43.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs
excerpt: This Article Describes Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs
keywords: DLL Troubleshoot Guide,ArcExtract Fault Fix,ISDone.dll Errors,PC ISDone.dll Issue,ISArcFix Implementation,Extract Dll Troubleshoot,ISDone.dll System Fix
thumbnail: https://thmb.techidaily.com/90e284fb29c37a4c0c2a2e6970ee3fa6b56745fa434982e234c62e6bb83237e0.jpg
---

## Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs

 Some players have reported an ISDone.dll installation error for Windows games. That issue can arise when players try to install certain games with setup wizards. The message in the ISDone.dll error window says, “It is not found any file specified for ISAarcExtract.”

 Users can’t install games on Windows 10 or 11 when the ISDone.dll error appears. Is the same error stopping you from installing a PC game? If it is, this is how you can fix the ISDone.dll installation issue in Windows 11 and 10.

## 1\. Run the Game’s Installer With Admin Rights

 First, run the game’s setup file with elevated rights to ensure admin restrictions can’t cause the issue. As you’ll only need to install the game once, it’s not necessary to set the installer to[always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) . Open the folder that includes the game’s setup.exe. Right-click the game’s installer (setup) file and select its**Run as administrator** context menu option.

![The Run as administrator context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-as-administrator-context-menu-option.jpg)

## 2\. Run the Game’s Installer in Compatibility Mode

 Some players have confirmed they’ve fixed the ISDone.dll error by setting the setup wizards for their games to run in compatibility mode. That potential resolution is more likely to work for older games released before Windows 10's own. You can set a setup file to run in compatibility mode like this:

1. First, press Explorer’s**Win + E** key combination to open the File Manager.
2. Navigate to the directory that includes the game setup wizard for which you need to fix the ISDone.dll error.
3. Right-click the setup.exe file for the game and select**Properties** .
4. Select**Compatibility** along the top of the properties window.
5. Next, select the**Run this program in compatibility** mode box.
6. Select the**Windows 7** platform option on the drop-down menu. If your game predates that platform, you can also try selecting Vista or XP.  
![The Run this program in compatibility mode for option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-this-program-in-compatibility-mode-setting.jpg)
7. Click**Apply** to save the compatibility settings.
8. Select**OK** to close the setup properties window.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## 3\. Set the Game’s Setup Wizard at High Priority

 Increasing the priority for a game’s setup wizard will raise the system resources allocated to its process. Our article about[setting a priority level for a program](https://www.makeuseof.com/windows-11-set-program-priority/) includes step-by-step instructions for how to apply this potential fix. Open the game’s setup wizard and set its priority level to High in Task Manager as outlined within that guide.

![The Set priority option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-set-priority-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run System File and Image Scans

 System file corruption is another potential cause for the ISDone.dll error in Windows 11/10\. So, we recommend users run a System File Checker scan to address that possible cause. Check out our[guide about running the SFC tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) for further details about how to apply this solution.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-sfc-command.jpg)

 In addition, you can also run a Deployment Image Servicing Management scan on top. That scan can resolve issues with the system image. You can run that utility in the Command Prompt by executing this command:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Increase Virtual Memory Allocation

 As the ISDone.dll error sometimes arises due to insufficient system memory, increasing virtual memory allocation can be a viable solution. Virtual memory is extra memory reallocated from hard drive storage when your PC’s RAM utilization is at maximum. Expanding the paging file will increase the virtual memory.

 You can apply this solution by following the steps in our[how to increase virtual memory](https://www.makeuseof.com/how-increase-virtual-memory-windows-11/) guide. Enter custom megabyte values in the**Initial** and**Maximum size** boxes on the Virtual Memory window. It’s recommended to enter an initial value 1.5 times higher than your PC’s total RAM amount in megabytes. Input a maximum value three times higher than the total RAM on your PC.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/custom-radio-button.jpg)

 For example, a PC with four GB RAM would have 4096 megabytes of memory. Then you would need to multiply 1.5 by 4096 to input a value of 6144 in the**Initial** box. Three times 4096 amounts to 12288, which would be the value to enter the**Maximum size** box.

## 6\. Install Any Missing Visual C++ Redistributables

 The ISDone.dll error could be occurring because some required Visual C++ Redistributable runtimes are missing on your PC. The solution in such a scenario is to install the required C++ runtime libraries that are missing. You can install missing Visual C++ runtimes in the following steps:

1. Open Microsoft’s download page for[Visual C++ Redistributable packs](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) in your browser.
2. Then click the X64 link for the Visual Studio 2015-2022 package.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-download-link-for-visual-c.jpg)
3. Double-click the**VC\_redist.x64.exe** file to open an installer window.
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
4. Select the checkbox for agreeing to the license terms.  
![The Microsoft Visual C++ 2015-2022 runtime installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-visual-c-installer-window.jpg)
5. Click the Visual C++**Install** option.

 If the ISDone.dll installation issue arises for an old game, you might need to install missing Visual C++ runtimes that predate 2015\. In this case, you’ll need to repeat the above steps for older Visual C++ packs. Try downloading the 64-bit Visual Studio 2013 and 2012 packs from the same Microsoft page to install older missing runtime libraries.

## 7\. Re-Register the Referenced ISDone DLL File

 The ISDone.dll error references an ISDone DLL file, which might not be correctly registered. Reregistering that file could resolve the issue for some users. This is how to register the ISDone DLL file:

1. Press**Win + S** to open Windows Search
2. Type in**Command Prompt** to find that app.
3. Click**Run as administrator** for the Command Prompt app within the search results.
4. Input this command for reregistering ISDone.dll and hit**Enter** :  
`regsvr32 isdone.dll`  
![The regsvr32 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-regsvr-command.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## 8\. Temporarily Switch Off Your PC’s Antivirus Shield

 It’s not entirely unusual for antivirus apps to cause installation issues like the ISDone.dll error. You can ensure your antivirus tool isn’t interfering with the installation process by temporarily disabling its shield before attempting to install the game. Our[guide to disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) explains how to turn off the antivirus shield for the default Windows Security app.

![The Real-time protection option in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-option.jpg)

 Users who’ve installed alternative security software packages on PCs will need to disable the third-party antivirus shields. To do that, click a system tray icon for an antivirus app to bring up its context menu. Then, select an option for turning off (or disabling) the antivirus shield.

 However, don’t leave your antivirus software disabled. Instead, turn it off and then try to install whatever game the ISDone.dll error occurs for. Then make sure you re-enable the antivirus shield afterward.

## 9\. Clean Boot the Windows PC

 To minimize potential conflicting processes, try clean booting your PC. Setting a clean boot involves disabling all third-party startup apps and services. That will reduce the number of background services and apps that start with Windows, which could eliminate a process causing the ISDone.dll error.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-services-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Our guide to[configuring a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to disable third-party startup apps and services with Task Manager and MSConfig. When you’ve set the clean boot and restarted Windows, try installing the game the ISDone.dll error occurs for. Then you can restore the original boot configuration afterward.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## Enjoy Your Windows Games Again

 Players have widely confirmed those resolutions fix the ISDone.dll error. So, applying the potential ISDone.dll error resolutions above will probably resolve that game installation issue in most cases. Yet, they might not work for everyone, and you can contact support services for affected game titles if further potential fixes are needed.

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


