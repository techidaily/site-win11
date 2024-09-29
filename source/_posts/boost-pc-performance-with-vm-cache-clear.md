---
title: Boost PC Performance with VM Cache Clear
date: 2024-08-15T23:55:22.310Z
updated: 2024-08-16T23:55:22.310Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost PC Performance with VM Cache Clear
excerpt: This Article Describes Boost PC Performance with VM Cache Clear
keywords: Boost PC Speed,Enhance Computer PERF,Optimize System BOOST,Increase PC EFFICIENCY,Accelerate PC SPEED,Improve System PERFORMANCE,Enhance CPU Performance
thumbnail: https://thmb.techidaily.com/a8a2eae7840110809ce01981ae6ddd7381e7680b0d93e29805eecd4b92108f79.jpg
---

## Boost PC Performance with VM Cache Clear

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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






