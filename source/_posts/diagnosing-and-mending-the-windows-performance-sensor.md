---
title: Diagnosing and Mending the Windows Performance Sensor
date: 2024-08-08T13:22:45.966Z
updated: 2024-08-09T13:22:45.966Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diagnosing and Mending the Windows Performance Sensor
excerpt: This Article Describes Diagnosing and Mending the Windows Performance Sensor
keywords: Windows Performance Checkup,Speed Sensor Diag,System Performance Fix,Optimize Windows Sys,PC Speed Boosting,Boosting Windows Sys,Repair Win Speed Sensor
thumbnail: https://thmb.techidaily.com/bc72bcdc29440f3559a7ac3b3d313c8c685d10379af7ea84f2fb960950ffa85c.jpg
---

## Diagnosing and Mending the Windows Performance Sensor

 Performance Monitor is a system monitoring tool on Windows that you can use to view real-time statistics about the applications you are running. But sometimes this tool fails to work correctly. If you're facing such a problem on your computer, here are a few fixes you can try to solve it.

## 1\. Reboot your Computer

 Whether you're experiencing performance issues such as slow startup times, or if Performance Monitor isn't working on your system, a simple reboot might do the trick.

 Rebooting Windows clears out any conflicting programs or services that may be causing PerfMon to not work properly. It removes any unnecessary data stored in memory that might be responsible for the issue.

To restart your computer, follow these steps:

1. Open the**Start** menu.
2. Click on the Power button, then select**Restart** .

 Once the computer has restarted, open Performance Monitor and check if the issue has been resolved.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 2\. Restart the Performance Logs and Alerts service

 If rebooting your computer doesn't fix the problem, you can try restarting the Performance Logs and Alerts service. This service is responsible for monitoring system performance settings and generating alert messages when something is wrong.

To restart this service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run command
2. Type**services.msc** in the dialog box and press**Enter** .
3. In the Services window, scroll down to**Performance Logs & Alerts** service.
4. Right-click on the service and select the**Restart** option.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Restart Performance service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-performance-service.jpg)

 After you follow the above steps, check if Performance Monitor is working correctly.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the System File Checker

 The System File Checker is a handy Windows tool that can scan for and fix corrupted system files. It is useful when the Performance Monitor isn't working due to a corrupt system file.

To run the System File Checker, follow these steps:

1. Click on the Start menu.
2. Type**cmd** in the search bar, then press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. If UAC appears on the screen, click**Yes** to grant access. You can learn more about this handy tool with our[beginner's guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In the Command Prompt, type the following command and press**Enter** :  
sfc /scannow
5. The scan will check for any corrupted system files and repair them.

 After the scan is complete, restart your computer and check if Performance Monitor is working properly.

## 4\. Check for a Windows Update

 In some cases, outdated versions of Windows can cause Performance Monitor problems. To ensure your system is running the latest version of Windows, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings. We also have an in-depth tutorial on[accessing the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click**Windows Update** in the left pane.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)
3. Then click the**Check for updates** button.

 If any available updates are found, Windows will download and install them automatically. After the updates have been installed, restart your computer and check if Performance Monitor is now working correctly.

## 5\. Perform a System Restore

 In case you have run out of options, you may want to try a system restore. This way, your computer will be restored to the state it was in before the program stopped working.

To perform a system restore, follow these steps:

1. Press**Win + Q** on your keyboard.
2. Type**System Restore** in the search bar and click on**Create a restore point** .
3. In the System Properties window, click the**System Restore** button.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![Run System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-system-restore.jpg)
4. Choose a restore point, then click**Next** .
5. Follow the on-screen instructions to perform a system restore.

 Upon completion of the restoration process, make sure Performance Monitor is working properly.

## Get Hassle Free Performance and Health Monitoring

 Like any other program, Performance Monitor can have glitches and other issues that prevent it from working correctly. The steps in this article will help you fix these issues and get Performance Monitor up and running again.


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


