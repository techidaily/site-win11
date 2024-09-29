---
title: Ceasing Auto-Opens on Microsoft's Marketplace App
date: 2024-08-16T00:12:42.369Z
updated: 2024-08-17T00:12:42.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ceasing Auto-Opens on Microsoft's Marketplace App
excerpt: This Article Describes Ceasing Auto-Opens on Microsoft's Marketplace App
keywords: Stop Autopop,End Auto-Open MSM,Cease MS Marketplace Opens,Disable Auto-Launch MS,Halt Autosaves in MS Apps,Prevent MSA Openings,Block Automatic Opens MS
thumbnail: https://thmb.techidaily.com/7f563c6cc49d9e48b9aa551214712c5134f2db5185be39a48c0e895d012e0af9.jpg
---

## Ceasing Auto-Opens on Microsoft's Marketplace App

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out [how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out [how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.


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






