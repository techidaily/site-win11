---
title: Strategies to Avoid 'No Permission' On Windows File Viewing
date: 2024-08-15T23:38:25.196Z
updated: 2024-08-16T23:38:25.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Avoid 'No Permission' On Windows File Viewing
excerpt: This Article Describes Strategies to Avoid 'No Permission' On Windows File Viewing
keywords: Avoiding NoPermViewError,WindowsFileAccessDeny,SafeFileshareTechniques,PermissionsControlWindows,AccessDeniedWindowsStrategy,FilePermissionAvoidance,SecureFilesystemWindows
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## Strategies to Avoid 'No Permission' On Windows File Viewing

 Did you encounter an error message when opening photos on an external hard drive? The message says "It looks like you don't have permission to view this file. Check the permissions and try again." The error implies that Windows Photos or File Explorer is not authorized to access this file.

 In this article, we explain how to fix this error, so you can view your photos again.

## Why Can't You View the File?

 You may encounter this error if your external hard drive is connected to a device without the right permissions settings. Other possible causes include user account control settings which restrict access to external drives, or a corrupted Windows Photos app.

 Now you know what causes this error, let's explore the solution.

## 1\. Grant Full Control Permissions

 It looks like the main issue causing this error is that Windows doesn’t have sufficient permissions to access the file. To fix this, you must grant full control permissions to the account or user accessing the file. Here are the steps to follow:

1. Right-click on the folder and choose **Properties**.
2. In the Properties window, go to the **Security** tab.
3. Select the user account or group from the list and click **Edit**.
4. Under the **Permissions** section, check the box next to **Full Control**.  
![Grant Full Control Permissions to an user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/grant-full-control-permissions-to-an-user-account.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
5. Click **Apply** and **OK** to save the changes.

 After making these changes, try viewing the photos again and checking if the error has been resolved.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Take Ownership of the Folder

 If granting full control permissions does not work, take ownership of the folder to get more control. Taking ownership means you can manage, access, and delete files within it. Here's how to do it:

1. Right-click on the folder and select **Properties** from the context menu.
2. Switch to the **Security** tab, then click **Advanced** at the bottom.
3. In the Advanced Security Settings window, make sure you're on the **Permissions** tab.
4. Click on **Change** next to **Owner** in the top section.  
![Advanced Security Settings for Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-security-settings-for-folders.jpg)
5. In the dialog box, type **Everyone** and click **Check Names**.  
![Enter the object name to select user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enter-the-object-name-to-select-user.jpg)

1. If it seems correct, click **OK**.
2. Check the box next to **Replace owner on subcontainers and objects**.  
![Take Ownership of the Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/take-ownership-of-the-folder.jpg)
3. Now click Apply. A pop-up appears and asks you to confirm the ownership change.
4. Click **Yes** and wait for the process to finish.
5. Once done, click **OK** and close the window.

 After that, restart your computer and try accessing the folder.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the Photos App

 Another way to fix this error is to reset the Photos app. Resetting the app will delete all settings and cached data and restore it to its default state. Here’s how to reset the Photos app:

1. Press **Win + I** to open the Settings menu.
2. From the left pane, click **Apps** \> **Installed apps**.
3. Scroll down to find the **Microsoft Photos** app. You can also use the search bar to find it.  
![Microsoft Photos App in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-photos-app-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the three dots and select **Advanced options**.
5. Under the **Reset** section, click the **Reset** button.  
![Reset Microsoft Photos App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-microsoft-photos-app.jpg)
6. If a pop-up appears, click **Reset** again to confirm your action.

 After that, try to open photos on your external hard drive.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 4\. Disable UAC Temporarily

 You may often find that you don’t have enough permissions to perform specific tasks. In such cases, [disabling UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) may do the trick. So, disable it temporarily and see if it works.

## 5\. Run the Program Compatibility Troubleshooter

 If you're still encountering the error, try [running the Program Compatibility Troubleshooter](http://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/). This tool scans for compatibility issues with installed programs and solves them automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Open Files Without a Problem Again on Windows

 If you have the proper permissions, you should not encounter the "you don’t have permission to view this file” message. However, if you run into this issue, read this guide to resolve it quickly. Make sure you grant all permissions and take ownership of the folder.

 In this article, we explain how to fix this error, so you can view your photos again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



