---
title: Integrating Printer Support Into Application Guard
date: 2024-08-28T00:53:30.035Z
updated: 2024-08-29T00:53:30.035Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Printer Support Into Application Guard
excerpt: This Article Describes Integrating Printer Support Into Application Guard
keywords: Guard Printer Integration,AppGuard Print Support,Security Print Feature,Secure Printer Gateway,Print Guard Connectivity,Application Printer Shield,Enhanced Print Protection
thumbnail: https://thmb.techidaily.com/ff0b61be790a55820d60db4c7ad60b6e5b6b95574b036e27c98e637af2bd24e8.jpg
---

## Integrating Printer Support Into Application Guard

 Application Guard is a security feature introduced in Microsoft Edge. It allows you to isolate potentially malicious websites and documents in a virtualized environment.

 While this feature provides an extra layer of protection, it also restricts some functionalities, such as printing. This guide explains how to enable printing in Application Guard for Edge on Windows devices.

## 1\. How to Enable Printing via Windows Settings

 To enable printing in Application Guard for Edge, follow the steps below:

1. Press**Win + I** on your keyboard to open the Settings menu. For more information, see[how to open Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, click**Privacy & security** .
3. Then select**Windows Security** on the right.
4. On the next page, select**App & browser control** .  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
5. Scroll down to Isolated browsing, then click the**Change Applications Guard settings** link.
6. Under Application Guard settings, turn on the toggle for**Print files** .  
![Allow Printing From Application Gurard For Microsoft Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allow-printing-from-application-gurard-for-microsoft-edge.jpg)
7. If UAC prompts appear on the screen, click**Yes** to continue.

 After following the above instructions, you must restart your computer to make the changes take effect. Now you can print files from isolated browsing in Edge.

 If you ever need to disable this feature, simply follow the same steps and toggle off Print files. This will disable printing in Application Guard for Edge on your device.

## 2\. How to Enable Printing via Registry Editor

 If you prefer using the Registry Editor to enable printing in Application Guard for Edge, follow the steps below:

1. Open the Registry Editor (see[how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for more instructions).
2. When UAC appears on the screen, click**Yes** to continue.
3. In the Registry Editor window, go to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
4. Next, go to the right pane and double-click on**EnablePrinters** .  
![Enable Print from Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-print-from-application-guard-for-edge.jpg)
5. Set Value data**1** and click**OK** to save the changes.

 Once you have completed the above steps, close the Registry window and restart your computer.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Now the Application Guard for Edge Supports Printing

 It is quite easy to enable printing in Application Guard for Edge on a Windows computer. Now you know two quick and easy ways to get it working.


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


