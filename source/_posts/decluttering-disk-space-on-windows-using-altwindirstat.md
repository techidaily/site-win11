---
title: Decluttering Disk Space on Windows Using altWinDirStat
date: 2024-08-28T00:56:13.976Z
updated: 2024-08-29T00:56:13.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decluttering Disk Space on Windows Using altWinDirStat
excerpt: This Article Describes Decluttering Disk Space on Windows Using altWinDirStat
keywords: Disk Cleanup Guide,File Management Tips,Reduce Clutter,Optimize Disk Usage,AltWinDirStat Tool,Space Freedom Windows,Organize Files Efficiently
thumbnail: https://thmb.techidaily.com/8443124490dd4d26d174966fed147fd5721a9572389508714a7b16fe1b9aa1b0.jpg
---

## Decluttering Disk Space on Windows Using altWinDirStat

### Key Takeaways

* altWinDirStat is a modified version of WinDirStat that offers higher speeds and a streamlined interface for analyzing storage space. It is a useful tool for locating large files.
* To download and install altWinDirStat, visit its page on GitHub and download the version that matches your PC's architecture. Since it does not require installation, you can save it to a folder or a USB flash drive for portable use.
* altWinDirStat directly scans the storage device's Master File Table (MFT) for faster analysis. To access the MFT, you need to run altWinDirStat as administrator. The app only takes seconds to analyze storage and present results.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.


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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-perfecting-your-youtube-video-archive-setup/"><u>[New] 2024 Approved  Perfecting Your YouTube Video Archive Setup</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-oculus-odyssey-a-journey-through-best-vr-headsets/"><u>[New] Oculus Odyssey  A Journey Through Best VR Headsets</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-decoding-the-perks-of-asmr/"><u>[Updated] Decoding the Perks of ASMR</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-follower-deletion-identification/"><u>[Updated] In 2024, Instagram Follower Deletion Identification</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-nine-crucial-methods-to-log-computer-speakers-and-microphones/"><u>[Updated] In 2024, Nine Crucial Methods to Log Computer Speakers and Microphones</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-streamlining-time-lapse-photography-with-gopro-software/"><u>2024 Approved  Streamlining Time-Lapse Photography with GoPro Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleashing-audio-pleasure-your-iphones-podcast-potential/"><u>2024 Approved  Unleashing Audio Pleasure - Your iPhone’s Podcast Potential</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-unwanted-edge-shortcut-popups/"><u>Conquering Unwanted Edge Shortcut Popups</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-leverage-copernic-for-efficient-cloud-storage-searches/"><u>Discover How to Leverage Copernic for Efficient Cloud Storage Searches</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-resolving-windows-11-user-access-problems/"><u>Efficiently Resolving Windows 11 User Access Problems</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connection-integrate-your-pc-and-phone-through-flow/"><u>Effortless Connection - Integrate Your PC & Phone Through Flow</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-image-quality-mastering-windows-11s-background-blur-function-in-photos/"><u>Elevate Your Image Quality: Mastering Windows 11'S Background Blur Function in Photos</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-driver-not-working-on-your-windows-1011-pc/"><u>Eliminate Driver Not Working on Your Windows 10/11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-fixing-two-users-ms-login-conflicts/"><u>Expert Tips: Fixing Two Users' MS Login Conflicts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-ais-capacity-to-understand-emotional-nuances/"><u>Exploring AI's Capacity to Understand Emotional Nuances</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-zerox-error-code-0x80049dd3-and-enhance-typing/"><u>Fix Windows 11'S Zerox Error (Code: 0X80049DD3) and Enhance Typing</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-chromes-non-responsive-black-screen/"><u>Fixing Chrome's Non-Responsive Black Screen</u></a></li>
<li><a href="https://win11.techidaily.com/four-simple-steps-to-tell-if-factory-reset-is-right/"><u>Four Simple Steps to Tell If Factory Reset Is Right</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-wsl-error-4294967295-on-windows/"><u>How to Resolve the WSL Error 4294967295 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-a-printer-connection-in-windows/"><u>How to Troubleshoot a Printer Connection in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlink-onedrive-from-windows-11-file-explorer/"><u>How To Unlink OneDrive From Windows 11 File Explorer</u></a></li>
<li><a href="https://howto.techidaily.com/htc-u23-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>HTC U23 Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-does-pokegoplusplus-still-work-on-apple-iphone-15ipad-drfone-by-drfone-virtual-ios/"><u>In 2024, Does PokeGo++ still work on Apple iPhone 15/iPad? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-vivo-y100a-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Vivo Y100A in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-poco-f5-pro-5g-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Poco F5 Pro 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-oppo-a18-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Oppo A18 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-the-world-of-lut-filters-for-obs-mastery/"><u>In 2024, Navigating the World of LUT Filters for OBS Mastery</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-video-limits-explained-in-detail-for-2024/"><u>Instagram Video Limits Explained in Detail for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-files-automatically-accessible-in-win11/"><u>Making Your Files Automatically Accessible in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-comprehensive-removal-of-wsl-from-win-11-pcs/"><u>Master Plan: Comprehensive Removal of WSL From Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-pc-sound-with-windows-11s-advanced-mixer-features/"><u>Master Your PC Sound with Windows 11'S Advanced Mixer Features</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-email-management-9-key-upgrades-in-windows-outlook/"><u>Mastering Email Management: 9 Key Upgrades in Windows' Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/memory-cache-mastery-in-windows-systems/"><u>Memory Cache Mastery in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mending-printer-not-found-error-in-windows-11/"><u>Mending 'Printer Not Found' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-configurations-in-win11/"><u>Navigating Network Configurations in Win11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-openais-vulnerability-disclosure-program-eligibility-and-participation-steps/"><u>Navigating OpenAI’s Vulnerability Disclosure Program: Eligibility & Participation Steps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-dvd-to-digital-made-easy-a-comprehensive-conversion-guide/"><u>New 2024 Approved DVD to Digital Made Easy A Comprehensive Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-workspace-learning-to-use-windows-11s-taskbar-search/"><u>Optimizing Your Workspace: Learning to Use Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-resolving-package-could-not-be-opened-on-win11-10/"><u>Quick Steps for Resolving 'Package Could Not Be Opened' On Win11, 10</u></a></li>
<li><a href="https://win11.techidaily.com/removing-persistent-edge-toolbar-items/"><u>Removing Persistent Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/savings-saved-the-hidden-dangers-in-cheap-windows-activation-codes/"><u>Savings, Saved? The Hidden Dangers in Cheap Windows Activation Codes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/skys-best-hd-pics-top-website-guide-for-2024/"><u>Sky's Best HD Pics  Top Website Guide for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essential-blueprint-for-finding-and-enjoying-premium-cricket-streams-for-2024/"><u>The Essential Blueprint for Finding and Enjoying Premium Cricket Streams for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/the-ultimate-strategy-for-role-assignment-on-discord-for-2024/"><u>The Ultimate Strategy for Role Assignment on Discord for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-vivo-s17-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Vivo S17 Android SIM Unlock APK</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-editing-efforts-10-text-innovations-for-2024/"><u>Top Editing Efforts  10 Text Innovations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-to-virtualbox-70-on-windows-11-your-ultimate-walkthrough/"><u>Transitioning to VirtualBox 7.0 on Windows 11 – Your Ultimate Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/turn-back-to-standard-contrast-on-windows/"><u>Turn Back to Standard Contrast on Windows</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-11-pro-using-icloud-website-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 11 Pro using icloud website</u></a></li>
<li><a href="https://win11.techidaily.com/vintage-games-journey-from-backups-to-windows-11-pics/"><u>Vintage Games Journey: From Backups to Windows 11 Pics</u></a></li>
<li><a href="https://win11.techidaily.com/win-fixes-overcoming-firefox-page-load-issues-in-windows/"><u>Win Fixes: Overcoming Firefox Page Load Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-print-admin-a-user-friendly-approach/"><u>Windows Print Admin: A User-Friendly Approach</u></a></li>
</ul></div>
