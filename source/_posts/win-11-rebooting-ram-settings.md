---
title: "Win 11: Rebooting RAM Settings"
date: 2024-09-13T07:39:10.393Z
updated: 2024-09-17T00:29:50.696Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Rebooting RAM Settings"
excerpt: "This Article Describes Win 11: Rebooting RAM Settings"
keywords: Win 11 Optimization,RAM Tuning Win 11,RAM Settings Win 11,Memory Boost Win 11,Optimize Win 11 Memory,Fixing RAM In Win 11,RAM Performance Win 11
thumbnail: https://thmb.techidaily.com/7f531620a49852bbff7e687b5f3193b68bdfdcb0db935514f90e93325010d261.jpg
---

## Win 11: Rebooting RAM Settings

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-demystifying-macos-capture-feature-for-professional-use/"><u>[New] Demystifying macOS Capture Feature for Professional Use</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-precision-in-motion-apowersofts-pc-screen-recorder-review/"><u>[New] Precision in Motion Apowersoft's PC Screen Recorder Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pro-editors-insight-restore-true-colors-to-faded-iphone-hdr-in-adobe-premiere/"><u>[Updated] [Pro Editor's Insight] Restore True Colors to Faded iPhone HDR in Adobe Premiere</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-full-guide-to-enhancing-photos-with-facetune-app/"><u>2024 Approved Full Guide to Enhancing Photos with Facetune App</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-itel-a60-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Itel A60 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-vivo-x90s-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/aural-adventures-tech-updates/"><u>Aural Adventures Tech Updates</u></a></li>
<li><a href="https://win11.techidaily.com/m4a202c/"><u>M4Aファイル編集プログラム202C最新リリースをお勧めします!音質無傷の維持が可能</u></a></li>
<li><a href="https://win11.techidaily.com/mp4pspps3ps4ps5/"><u>MP4ビデオプレイヤー不可能：PSP/PS3からPS4、PS5までのトラブルシューティングガイド</u></a></li>
<li><a href="https://win11.techidaily.com/mpeg-4mp3/"><u>MPEG-4ファイルをMP3形式に変換するための詳細ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/new-htc-windows-phone-7-series-hd7-smartphone-hits-retail-shelves/"><u>New HTC Windows Phone 7 Series HD7 Smartphone Hits Retail Shelves</u></a></li>
<li><a href="https://win11.techidaily.com/preserve-original-excellence-with-wonderfox-turn-your-videos-into-crisp-clear-gifs-effortlessly/"><u>Preserve Original Excellence with WonderFox: Turn Your Videos Into Crisp, Clear GIFs Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-optimizing-videos-in-your-inbox-the-ultimate-compression-guide/"><u>Quick Tips for Optimizing Videos in Your Inbox: The Ultimate Compression Guide</u></a></li>
<li><a href="https://win11.techidaily.com/shazam-tutorial-how-to-identify-music-in-videos-across-android-ios-and-pcs/"><u>Shazam Tutorial: How to Identify Music in Videos Across Android, iOS, and PCs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/windows-users-ultimate-guide-to-installing-and-using-chatgpt/"><u>Windows Users' Ultimate Guide to Installing & Using ChatGPT</u></a></li>
</ul></div>

