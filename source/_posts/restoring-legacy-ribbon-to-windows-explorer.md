---
title: Restoring Legacy Ribbon to Windows Explorer
date: 2024-07-29T15:45:41.073Z
updated: 2024-07-30T15:45:41.073Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Legacy Ribbon to Windows Explorer
excerpt: This Article Describes Restoring Legacy Ribbon to Windows Explorer
keywords: Restore Ribbon Windows,Ribbon Explorer Update,Legacy Ribbon Fix,WinExplorer Ribbon,Renew Explorer Features,Rebuild Window Ribbon,Reinstate Explorer Bar
thumbnail: https://thmb.techidaily.com/b034e397cf58f21c63fc5dd80cb149d6528213f9e99cf7ed2375f403fbf9fc3e.jpg
---

## Restoring Legacy Ribbon to Windows Explorer

 Microsoft redesigned File Explorer’s user interface for Windows 11\. Windows 11’s File Explorer has a command bar on which you can select options. That bar replaces the tabbed ribbon interface from Windows 10’s File Explorer.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

## 1\. Press the Up Button in the Control Panel

 File Explorer is accessible from the Control Panel. Furthermore, Explorer will still have the old, ribbon interface from Windows 10 when you open it from there. You can access the classic File Explorer in Windows 11 by clicking the up button in the Control Panel as follows:

1. Press the **Windows + S** key combination to access Windows 11’s search box.
2. Input **Control Panel** and select to open the matching search result.
3. If the Control Panel opens in an icon view, click the **View by** drop-down menu and select **Category**.  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![The View by menu in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/view-by-menu.jpg)
4. Then click the **Up to “Desktop”** button (up arrow) button on the Control Panel’s navigation bar. Alternatively, press the **Alt + Up arrow key** keyboard shortcut.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
![The Up to Desktop button in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/up-button.jpg)

 Now you’ll see the classic File Explorer from Windows 10 that incorporates a tab bar. You’ll always need to open the Control Panel first to access classic File Explorer through it. So, consider [setting up a Control Panel shortcut](https://www.makeuseof.com/windows-11-set-up-control-panel-shortcuts/) in Windows 11 to give you more direct access.

## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
3. You can bring back the command bar by executing this command:  
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Restore Explorer’s Classic Ribbon UI With ExplorerPatcher

 You can still restore Explorer’s ribbon interface in Windows 11 22H2 and all other build versions with ExplorerPatcher. ExplorerPatcher is freeware software that enables you to customize Windows 11’s Start menu, taskbar, File Explorer, and system tray. It includes many options for [making Windows 11 look more like Windows 10](https://www.makeuseof.com/windows-11-look-like-windows-10-explorerpatcher/).

 This is how you can restore tabs in Windows 11’s File Explorer with ExplorerPatcher.

1. Open this [ExplorerPatcher Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Explorer-Patcher-for-Windows-11.shtml) and download the file.
2. Double-click the **ep\_setup** file to install Explorer Patcher.
3. Activate the Power User menu by right-clicking the **Start** taskbar button to select **Search**.
4. Enter **ExplorerPatcher** in the Windows 11 search box and click **Properties (ExplorerPatcher)**.
5. Click the **File Explorer** tab in ExplorerPatcher.
6. Next, click the **Control interface** option to select **Windows 10 Ribbon**.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![The Windows 10 Ribbon option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-10-ribbon.jpg)
7. Click **Restart File Explorer** on the Properties window.

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)

 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



