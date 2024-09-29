---
title: "Windows 11'S Highlighted Icons: A How-To Guide"
date: 2024-08-08T13:21:50.770Z
updated: 2024-08-09T13:21:50.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11'S Highlighted Icons: A How-To Guide"
excerpt: "This Article Describes Windows 11'S Highlighted Icons: A How-To Guide"
keywords: Windows 11 Icons Guide,Highlighted Icon Tips,Icon Customization Windows 11,Windows 11 UI Enhancement,Personalizing Win11 Icons,How to Change Win11 Icons,Win11 Icon Setup Tutorial
thumbnail: https://thmb.techidaily.com/6391f80929a44e71d1cec19d1806bcb918554d022df1dd84ca222ff30839f7f0.jpg
---

## Windows 11'S Highlighted Icons: A How-To Guide

 Spotlight is a feature that adds different Bing images to Windows 11’s desktop background when enabled. That feature also adds a "Learn about this picture" icon to the desktop you can double-click to bring up image info. Right-clicking that icon brings up a context menu that includes a **Switch to next picture** option.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## How to Remove the Spotlight Desktop Icon With a Manual Registry Tweak

 A relatively simple registry tweak is required to remove the "Learn about this picture" icon from the Windows Spotlight wallpaper. These are the steps for removing the Spotlight desktop icon by manually tweaking the registry:

1. Launch Run by right-clicking **Start** (the taskbar icon) and selecting **Run**.
2. Enter **regedit** inside Run’s **Open** command box and select **OK** to [access the Registry Editor app](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Next, go to this **NewStartPanel** key by inputting its path in the registry address bar:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel`
4. Right-click **NewStartPanel** and select **New** to view a submenu with options for adding new registry entries.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The New DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-new-dword-option.jpg)
5. Click **DWORD (32-bit) Value** on the submenu.

1. Copy **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** to your clipboard by selecting the text and pressing **Ctrl** \+ **C**. Then press **Ctrl** \+ **V** to paste that into the DWORD’s name text box.
2. Double-click the **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you just added.
3. Delete **0** in the **Value data** box.
4. Input **1** in the **Value data** box and click **OK**.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![The NewStartPanel key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-window.jpg)
5. Click Registry Editor’s **X** window button.
6. Right-click any empty part of the desktop and select **Refresh**. The "Learn about this picture icon" will no longer be on the desktop.

 If you ever want to restore that Spotlight icon, you can do so by changing the value of the {**2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you added to the registry. Double-click **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** in the **NewStartPanel** key to input **0** in that DWORD’s **Value data** box. Refreshing the desktop will then restore the "Learn about this picture" icon.

![The Learn about this picture desktop icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-learn-about-this-picture-icon.jpg)

## How to Remove the Spotlight Desktop Icon With Winaero Tweaker

 The manual registry tweaking required for removing the "Learn about this picture" icon is relatively straightforward. However, you can remove the Spotlight desktop icon with Winaero Tweaker if you still prefer not to fiddle with the registry.

 At any rate, Winaero Tweaker is a fantastic piece of Windows customization software that’s worth installing. You can remove the Spotlight desktop icon with Winaero Tweaker like this:

1. Go to this [Winaero Tweaker download page](https://winaero.com/download-winaero-tweaker/) and click the download link there.
2. Extract the Winaero Tweaker ZIP and install the software with its setup file. Our guide to [customizing Windows with Winaero Tweaker](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes step-by-step installation instructions for that software.
3. Next, double-click the **Windows 11** category within Winaero Tweaker’s sidebar.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Windows 11 category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-11-category.jpg)
4. Click **Remove Windows Spotlight** icon from the desktop.
5. Select the **Remove Windows Spotlight icon from Desktop** checkbox.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![The Remove Windows Spotlight Icon from Desktop option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-remove-windows-spotlight-icon.jpg)

 Now the "Learn about this picture" icon will no longer be there. It’s easy to restore that icon with Winaero Tweaker if you ever want to utilize its Spotlight options again. Uncheck the **Remove Windows Spotlight icon from Desktop** checkbox in Winaero Tweaker to bring it back.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of the "Learn About This Picture" Icon on Windows 11

 The "Learn about this picture" icon only adds extra Windows 11 desktop clutter for users who never utilize its options. If you don’t want that additional Spotlight icon on your Windows 11 desktop, it’s straightforward to remove it with a manual registry tweak or Winaero Tweaker.

 The ExplorerPatcher software also includes an option for disabling that icon, along with other settings for making Windows 11 look like Windows 10\.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>