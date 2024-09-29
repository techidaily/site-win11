---
title: Direct Approach to Reviving Your Windows Update Status
date: 2024-08-16T00:15:52.741Z
updated: 2024-08-17T00:15:52.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Approach to Reviving Your Windows Update Status
excerpt: This Article Describes Direct Approach to Reviving Your Windows Update Status
keywords: WinUpdate Fix Method,Direct Updater Restore,Quick Windows Status,Reboot After Update,Updating Process Start,Update Fix Guide,Reviving Windows Patches
thumbnail: https://thmb.techidaily.com/7a684ff6b3f7243ec032f5ae8a931d190264bae1e112796613965ade353d6f1f.png
---

## Direct Approach to Reviving Your Windows Update Status

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir% system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



