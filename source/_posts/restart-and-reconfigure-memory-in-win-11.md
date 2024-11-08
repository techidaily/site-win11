---
title: Restart and Reconfigure Memory in Win 11
date: 2024-11-02T16:05:59.306Z
updated: 2024-11-07T23:43:25.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restart and Reconfigure Memory in Win 11
excerpt: This Article Describes Restart and Reconfigure Memory in Win 11
keywords: Win 11 Memory Refresh,Win 11 RAM Reset,Windows 11 Mem Control,Win11 Restart Cache,Win11 RAM Reconfig,Win 11 Memory Clearance,Win11 Memory Tuning
thumbnail: https://thmb.techidaily.com/6f24909f969f84628da7cca908a8ecbcf1f1310799ac0e990b393370971b6be4.jpg
---

## Restart and Reconfigure Memory in Win 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144288/7443" target="_top" id="2144288">
  <img src="//a.impactradius-go.com/display-ad/7443-2144288" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144288/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-safe-video-extraction-from-youtube-tips-on-downloading-to-mp4/"><u>[New] In 2024, Safe Video Extraction From YouTube - Tips on Downloading to MP4</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-toolwiz-unveiled-the-full-scope-photo-software-review/"><u>[New] In 2024, Toolwiz Unveiled - The Full Scope Photo Software Review</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-x-factor-photo-session-the-classic-iphone-experience/"><u>[New] In 2024, X-Factor Photo Session The Classic iPhone Experience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-from-setup-to-masterpiece-the-comprehensive-tutorial-for-zoom-based-audio-recordings/"><u>[Updated] 2024 Approved From Setup to Masterpiece The Comprehensive Tutorial for Zoom-Based Audio Recordings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-navigating-instagrams-video-time-policy/"><u>2024 Approved Navigating Instagram's Video Time Policy</u></a></li>
<li><a href="https://win11.techidaily.com/best-free-and-premium-pc-based-flv-video-editing-tools-top-picks/"><u>Best Free and Premium PC-Based FLV Video Editing Tools: Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/best-video-conversion-tools-from-dvd-to-mp4-on-windows-11-2024-edition/"><u>Best Video Conversion Tools From DVD to MP4 on Windows 11 - 2024 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/convert-aiff-audio-files-to-free-and-open-source-ogg-format-with-ease/"><u>Convert AIFF Audio Files to Free and Open-Source Ogg Format with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/convert-videos-seamlessly-for-psp-top-tools-that-transform-media-into-optimal-ps-portable-size-and-resolution/"><u>Convert Videos Seamlessly for PSP - Top Tools That Transform Media Into Optimal PS Portable Size and Resolution</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-oppo-k11-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Oppo K11 5G? Look No Further | Dr.fone</u></a></li>
</ul></div>

