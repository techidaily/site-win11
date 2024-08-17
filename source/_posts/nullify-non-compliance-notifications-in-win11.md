---
title: Nullify Non-Compliance Notifications in Win11
date: 2024-08-15T23:44:58.123Z
updated: 2024-08-16T23:44:58.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Nullify Non-Compliance Notifications in Win11
excerpt: This Article Describes Nullify Non-Compliance Notifications in Win11
keywords: Nullify Penalties,Compliance Removal,NoNoncomplianceWin11,Disable WarningsWin11,Erase ViolationsWin11,Eliminate Notifications,Ban Non-ComplianceNotes
thumbnail: https://thmb.techidaily.com/656378bfa436826a8517a6c678576be78969ead53968b002df8bcb5d506324cf.jpg
---

## Nullify Non-Compliance Notifications in Win11

### Key Takeaways

* Windows 11 has stricter hardware requirements, resulting in a "System requirements not met" watermark for unsupported hardware.
* You can remove the watermark by modifying the Registry Editor or using the Group Policy Editor.
* New updates may cause the watermark to reappear, requiring you to repeat the removal steps.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.


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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-complete-guide-to-crafting-impressive-timelapse-films-on-ipad/"><u>[New] 2024 Approved  The Complete Guide to Crafting Impressive Timelapse Films on iPad</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-dissecting-the-technology-behind-frapss-screenshot-pro/"><u>[New] In 2024, Dissecting the Technology Behind Fraps's Screenshot Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-transforming-old-images-into-snaps-on-snapchat/"><u>[New] Transforming Old Images Into Snaps on Snapchat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-effortless-recording-of-android-devices-for-all/"><u>[Updated] Effortless Recording of Android Devices for All</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-fb-video-aspect-ratio-varieties-for-2024/"><u>[Updated] FB Video Aspect Ratio Varieties for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-path-to-cross-media-popularity-via-television-and-fb-live/"><u>[Updated] The Path to Cross-Media Popularity via Television and FB Live</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/converging-zoom-and-fb-live-for-professional-broadcasts-for-2024/"><u>Converging ZOOM and FB Live for Professional Broadcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-pristine-windows-display-perfection/"><u>Crafting Pristine Windows Display Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/digital-detox-for-pcs-a-collection-of-13-revival-methods/"><u>Digital Detox for PCs: A Collection of 13 Revival Methods</u></a></li>
<li><a href="https://extra-hints.techidaily.com/e-world-punchline-maker/"><u>E-World Punchline Maker</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-challenge-write-permissions-for-steam-folders/"><u>Easing the Challenge: Write Permissions for Steam Folders</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-realme-gt-3-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Realme GT 3</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-linux-capabilities-through-windows-software/"><u>Elevating Linux Capabilities Through Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-package-registration-problems-on-windows-devices/"><u>Eliminating Package Registration Problems on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://some-techniques.techidaily.com/full-review-of-lg-bp350-from-screen-brightness-to-audio-output-for-2024/"><u>Full Review of LG BP350 - From Screen Brightness to Audio Output for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-non-recognized-ports-and-devices-on-windows-11/"><u>How to Fix Non-Recognized Ports and Devices on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-unresponsive-mail-alerts-on-windows-11/"><u>How to Overcome Unresponsive Mail Alerts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-seamless-program-deployment/"><u>Navigating Windows 11'S Seamless Program Deployment</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-booting-procedures-complete-guide/"><u>Navigating Windows' Booting Procedures Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/opera-on-windows-thwarting-the-downloading-dilemma/"><u>Opera on Windows: Thwarting the Downloading Dilemma</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-camera-app-error-0xa00f425d-in-windows-11/"><u>Overcoming Camera App Error 0xA00F425D in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-get-assistance-problems/"><u>Overcoming Windows 11 'Get Assistance' Problems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-error-nvidia-geforce-x0001/"><u>Overcoming Windows 11 Error: Nvidia GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1110-app-installation-obstacles-in-oculus/"><u>Overcoming Windows 11/10 App Installation Obstacles in Oculus</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unbidden-command-window-activations/"><u>Preventing Unbidden Command Window Activations</u></a></li>
<li><a href="https://win11.techidaily.com/quantify-windows-computer-power-usage-for-optimization/"><u>Quantify Windows Computer Power Usage for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsofts-activation-error-code-0x8007251d/"><u>Tackling Microsoft's Activation Error Code 0X8007251d</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-of-an-era-microsofts-abandonment-of-windows-7-and-81/"><u>The End of an Era: Microsoft's Abandonment of Windows 7 and 8.1</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-way-to-self-empty-the-recycle-bin-on-windows/"><u>The Simple Way to Self-Empty the Recycle Bin on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-steam-disconnect-in-windows-os/"><u>Troubleshoot Steam Disconnect in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-your-pcs-usb-troubleshooting-guide-for-windows-users/"><u>Unblock Your PC's USB: Troubleshooting Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-a-stuck-windows-11-settings-bar-the-search-solution/"><u>Unclogging a Stuck Windows 11 Settings Bar - The Search Solution</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-icon-recovery-step-by-step-guide/"><u>Windows 11 Icon Recovery: Step-by-Step Guide</u></a></li>
</ul></div>
