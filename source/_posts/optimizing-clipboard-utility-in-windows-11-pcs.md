---
title: Optimizing Clipboard Utility in Windows 11 PCs
date: 2024-08-23T06:10:45.856Z
updated: 2024-08-24T06:10:45.856Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Clipboard Utility in Windows 11 PCs
excerpt: This Article Describes Optimizing Clipboard Utility in Windows 11 PCs
keywords: WinClipboard Optimization,Clipboard Efficiency Windows,Enhanced Clipboard Functionality,Improve Copy/Paste in Windows,Clipboard Performance PCs,Streamlined Clipboard Use,Advanced Clipboard Tech Windows
thumbnail: https://thmb.techidaily.com/ec661044f40b96dbce0a66b5f469594edc16390627944ff76ebd8df97376a974.jpg
---

## Optimizing Clipboard Utility in Windows 11 PCs

### Quick Links

* [Clear Clipboard Data](#clear-clipboard-data)
* [Perform a Clean Boot](#perform-a-clean-boot)
* [Update Your Windows](#update-your-windows)
* [Restart File Explorer](#restart-file-explorer)
* [Run the Keyboard Troubleshooter](#run-the-keyboard-troubleshooter)
* [Reset the rdpclip.exe Process](#reset-the-rdpclip-exe-process)
* [Check Your Keyboard for Hardware Issues](#check-your-keyboard-for-hardware-issues)
* [Run the System File Checker](#run-the-system-file-checker)
* [Create a New Local User Account](#create-a-new-local-user-account)

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.


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


