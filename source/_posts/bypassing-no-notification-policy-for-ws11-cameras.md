---
title: Bypassing No-Notification Policy for WS11 Cameras
date: 2024-08-16T00:04:34.445Z
updated: 2024-08-17T00:04:34.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing No-Notification Policy for WS11 Cameras
excerpt: This Article Describes Bypassing No-Notification Policy for WS11 Cameras
keywords: Bypass Notification,Camera Alert Skip,Disable Notify Feature,Cam Privacy Control,WS11 No-Alert,Security Camera Silence,Unnotified WS11 Cameras
thumbnail: https://thmb.techidaily.com/70cafb81e97d380bf1f55403cf595cebfeb242757ff19f24408692f694faf166.jpg
---

## Bypassing No-Notification Policy for WS11 Cameras

 Have you noticed your camera LED randomly lighting up? Are you worried that malicious software can access your camera at any time?

 By default, Windows turns on the LED next to your webcam every time your camera is accessed. But if you’re in a well-lit environment or something is covering the LED, you might miss it. Also, the LED might be broken, so there’s no way of telling if your camera is on.

 The good news is that you can have Windows 11 display a desktop notification to let you know whether your camera is turned on or off.

## How to Turn On Camera On and Off Notifications

 You need administrative rights to turn on camera notifications. So, if you’re using a local account, check out [how to switch to an account with administrative rights on Windows 11](https://www.makeuseof.com/windows-11-switch-user-accounts/) . Then, follow these steps to edit the Registry Editor:

1. Press**Winy + R** to bring up a Run dialog.
2. Type**regedit** and press**Enter** .
3. In the Registry Editor, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > OEM > Device > Capture** .
4. Locate and open**NoPhysicalCameraLED** .
5. Set**Value data** to**1** to enable the notifications.
6. Click**OK** and restart your computer.

![Enable camera notifications in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/notify-camera-1.jpg)

 If the**NoPhysicalCameraLED** value is missing, you can create it. Right-click on the empty space in the right pane, and click**New > Dword(32-bit) value** . Set its name and**Value data** to**1** . Then, save the new changes and restart your computer for the changes to take place.

 Changing the value to**1** doesn’t impact your camera LED. It will still light up every time you access the camera. If you want to revert the change, go through the above instructions again and set**Value data** to**0** .

 Once your computer boots up access the camera and test if Windows is showing the camera notification.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Check Camera History

 If you missed the notification, Windows 11 allows you to check which apps have accessed your camera. Launch Windows Settings and go to**Privacy & security > Camera** . There, check the**Recent activity** section.

 Also, it might be worth it to take a look at your Privacy settings and [check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Know When Your Camera Starts on Windows

 Now, every time an app accesses your camera, Windows 11 will let you know. But if you want to add an extra layer to your privacy, you should consider placing tape over the camera.


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






