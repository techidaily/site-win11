---
title: "Win 11: Rebooting RAM Settings"
date: 2024-10-03T07:09:42.188Z
updated: 2024-10-08T16:46:08.727Z
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/ed-channel-catalysts-affiliates-aiding-budgeted-buzzers-for-2024/"><u>[Updated] Channel Catalysts Affiliates Aiding Budgeted Buzzers for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-eyewear-challenge-google-vs-samsung-virtual-reality/"><u>[Updated] In 2024, The Eyewear Challenge Google Vs. Samsung Virtual Reality</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unraveling-the-mystery-of-non-uploading-video-features/"><u>[Updated] In 2024, Unraveling the Mystery of Non-Uploading Video Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-you-need-to-know-about-micromobility-events-news-hearsay-and-more/"><u>All You Need to Know About Micromobility: Events, News, Hearsay & More</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-zero-error-in-win11-with-easy-steps/"><u>Eliminate Zero Error in Win11 with Easy Steps</u></a></li>
<li><a href="https://extra-information.techidaily.com/find-your-favorite-general-knowledge-quiz-channel-of-the-year-24/"><u>Find Your Favorite General Knowledge Quiz Channel of the Year, '24</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-no-internet-access-on-an-ethernet-connection-on-windows/"><u>How to Fix No Internet Access on an Ethernet Connection on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-magic-5-lite-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor Magic 5 Lite to New Android? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-honor-v-purse-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Honor V Purse ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-depth-look-at-gaming-screen-capture-tools-for-2024/"><u>In-Depth Look at Gaming Screen Capture Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-where-win11-stores-window-picture-files/"><u>Pinpoint Where Win11 Stores Window Picture Files</u></a></li>
<li><a href="https://win11.techidaily.com/solving-access-denied-issues-in-windows-11-a-top-5-approach/"><u>Solving Access Denied Issues in Windows 11: A Top 5 Approach</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-locating-your-gpu-model-on-windows-11/"><u>Speed Up: Locating Your GPU Model on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steadfast-safety-quick-fixed-strategies-for-family-protection/"><u>Steadfast Safety: Quick Fixed Strategies for Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-your-pcs-readying-with-win11-speed-fixes/"><u>Turbo Charge Your PC’s Readying with Win11 Speed Fixes</u></a></li>
</ul></div>

