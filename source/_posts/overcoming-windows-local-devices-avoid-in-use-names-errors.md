---
title: "Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
date: 2024-08-16T00:41:46.642Z
updated: 2024-08-17T00:41:46.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
excerpt: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
keywords: AVOID Device Error Windows,Overcome In-Use Name Issue,Resolve Local Devices Error,Stop Windows In-Use Error,Fix In-Used Names on PC,Avoid Local Devices Errors,Correct Windows Usage Error
thumbnail: https://thmb.techidaily.com/57a07625ab9c873f1b8816cfe4ef02cf1a6f9bda4b7acdd0899c793b0d810b70.jpg
---

## Overcoming Windows' Local Devices: Avoid In-Use Names Errors

 The Local device name is already in use error is not particularly unusual. If you work with any type of network, even a local network, you are quite likely to encounter it at some point. Luckily, it is also usually easy to resolve.

 Here are the most common causes of this error, along with the most likely solutions.

## What Causes the Local Device Name Error?

 There can be a couple of possible causes of this error, but pinpointing the exact cause can be difficult. The most common are unassigned drive letters and incorrect file and printer sharing settings.

 It is also possible that a lack of space on the network server can result in this error appearing. You should check this possibility first. If lack of storage is the cause, none of the following solutions will make a difference.

 If the network server has ample space, you can move on to trying the methods below to solve the problem on your local device.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1 Enable File and Printer Sharing

[You should always keep your firewall enabled](https://www.makeuseof.com/tag/5-reasons-use-firewall/) , but it can sometimes interfere with file and printer sharing. This can lead to seeing the Local device name is already in use error. Luckily you can enable file and printer sharing easily in the firewall settings.

 If you're using a third-party firewall, refer to the documentation to find the setting. Here's how to enable file and printer sharing in the Microsoft Firewall.

1. Search for Control Panel using Windows Search, and click the search result to open it.
2. Click**System and Security > Windows Defender Firewall** to see the firewall settings.
3. In the left menu, click**Allow an app or feature through the firewall** and then click the**Change settings** button.  
![Windows firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-printer-sharing.jpg)
4. Scroll down to find**File and Printer Sharing** in the list, and click the**Public** checkbox.
5. Click**Ok** and restart your computer to apply the change.

 Occasionally, the file and printer sharing settings for the firewall can get reset after a major update. Just because you know you have enabled it in the past, it is worth checking again.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2 Remap the Network Drive With Command Prompt

 Windows will automatically assign a letter to your network drive. During network mapping, the assigned letters can become mixed and even be missing altogether. Remapping the network drive can fix this and prevent the error.

1. The best way to remap the network drive is through the Command Prompt. Search for**cmd** in Windows Search and select**Run as Administrator** .
2. At the cursor, type:**net use D /delete** . Replace**D** with the drive letter you want to delete. Then press**Enter** .  
![the remap network drive command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remap-network-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
3. Now remap the drive by typing:**net use D: \\\\server\\share /user:username password** . Replace the drive letter and user and username password with the relevant details.

 If this doesn't help, you may need to try reassigning the drive letters manually. The end result is similar, but sometimes remapping won't work when manually reassigning the drive path will work.

## 3 Re-assign Drive Letters

 Another common cause of this error is an incorrectly assigned drive letter. Reassigning a drive letter is easy, as long as you don't run into the Drive letter not available error.

1. Search for**Disk Management** using Windows Search, or right-click the Start Menu and select it from the hidden menu.
2. In Disk Management, find the partition or drive you want to change and right-click on it.
3. Select**Change Drive Letter and Paths** , and then click the**Add** button.  
![reassigning drive letter in disk management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reassign-drive-letter.jpg)
4. Click**Assign the following drive letter** and use the drop-down menu to choose a new letter for the partition or drive.

 If the drive letter you require is not available, it may already be being used on another drive or partition. It could also be associated with a removable drive that is not currently connected. If the A and B drive letters are available, and they often aren't, it is best not to use them. These letters are traditionally reserved for floppy drives and for use with old OS versions.

 Learn more about [why drive letters usually start with C on Windows](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4 Reinitialize the Computer Browser

 A less likely solution to this error, but one that does sometimes help, is reinitializing the browser. Browser settings can, in some cases, interfere with network drive settings. By stopping the browser and reinitializing it, those settings should be reverted.

1. Open Windows Search and type**cmd** . In the result, select**Command Prompt** and click**Run as Administrator** .
2. At the Command Prompt cursor, type:**net stop "Computer Browser"** and then press**Enter** .  
![reinitialize the browser on command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinitialize-browser.jpg)
3. When the command finishes executing, type:**net start "Computer Browser"** and press**Enter** .
4. You can now close the Registry Editor and check to see if the error persists.

 Reinitializing the browser is different from simply closing and reopening the browser window. It is a much more forceful solution to clearing any browser settings that may be in conflict.

 Learn how to optimize and get the most from your computer with these [essential Windows performance tips](https://www.makeuseof.com/tag/windows-10-faster-performance/) .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5 Delete the MountPoints Registry Key

 If none of the above solutions have fixed the problem, you can try deleting the MountPoints registry key as a last resort. This key stores data about USB and other removable drives. Deleting the key can sometimes resolve conflicts in drive letter assignments.

1. Deleting the MountPoints key shouldn't cause problems, but it is best to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case. Do this before you continue.
2. Open the Registry Editor by searching for it in Windows Search.
3. Navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer** .  
![delete mountpoints in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-mountpoints.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Look for the**MountPoints2** key in the right-hand panel, right-click on it and select**Delete** .
5. Close the Registry Editor and restart your computer.

 The MountPoint registry key will be regenerated after deleting and restarting. You can then check to see if this fixed the Local Device name is already in use error.

## Fixing Local Device Name Errors on Windows

 The Local device name is already in use error is not uncommon, and it can be frustrating. But by working through the solutions here, you will normally be able to fix it within a few minutes. Just be sure to check the remaining storage on the network server before you start digging deeper.


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






