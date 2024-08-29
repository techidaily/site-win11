---
title: Refresh Virtual Memory on New Windows 11
date: 2024-08-28T00:49:55.283Z
updated: 2024-08-29T00:49:55.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Refresh Virtual Memory on New Windows 11
excerpt: This Article Describes Refresh Virtual Memory on New Windows 11
keywords: Win11 VM Refresh,Update Mem Windows 11,WM11 RAM Enhance,New OS RAM Update,Windows 11 Memory Boost,11 Windoze Virtual Memory,Optimize WM11 Memory
thumbnail: https://thmb.techidaily.com/b1e13c65cf79c8bfe0a90a1ea55d4cf4b25b6f465fd497be9c6686a8f2877ff5.jpg
---

## Refresh Virtual Memory on New Windows 11

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

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/n-2024-unlock-cross-platform-content-sharing-convert-and-upload-with-these-tools/"><u>[New] In 2024, Unlock Cross-Platform Content Sharing  Convert and Upload with These Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-your-digital-den-top-12-animal-simulator-games-on-android/"><u>[New] Your Digital Den  Top 12 Animal Simulator Games on Android</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-hitting-high-notes-enhance-your-youtube-content-with-music-edits-for-2024/"><u>[Updated] Hitting High Notes  Enhance Your YouTube Content with Music Edits for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-filming-made-easy-selecting-the-right-audio-devices/"><u>[Updated] In 2024, Filming Made Easy  Selecting the Right Audio Devices</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-perfect-for-broadcasters-top-360-cameras-listed-for-2024/"><u>[Updated] Perfect for Broadcasters  Top 360° Cameras Listed for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-realme-c55-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Realme C55 is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-windows-11-tips-easy-rdc-entry/"><u>Convenient Windows 11 Tips: Easy RDC Entry</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-disms-potential-in-win11-system-restoration/"><u>Decoding Dism's Potential in Win11 System Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-nvidia-experience-on-windows-devices/"><u>Fixing Unresponsive NVIDIA Experience on Windows Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-daydream-to-reality-a-short-vr-history/"><u>From Daydream to Reality  A Short VR History</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-windows-11-sign-in-issue-caused-by-user-profile-service-malfunction/"><u>Guide to Correcting Windows 11 Sign-In Issue Caused by User Profile Service Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unaltered-screenscape-in-windows-11/"><u>Guide to Unaltered Screenscape in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-windows-11s-tracking-features/"><u>How to Disable Windows 11'S Tracking Features</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-xiaomi-13t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-windows-error-code-1053-for-non-responsive-services/"><u>How to Handle Windows' Error Code 1053 for Non-Responsive Services</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-portable-recording-stands-and-lenses/"><u>In 2024, Portable Recording Stands and Lenses</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-uncover-unique-user-understanding/"><u>In 2024, Uncover Unique User Understanding</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-fixes-for-disabled-hard-drives-on-windows-11-systems/"><u>Innovative Fixes for Disabled Hard Drives on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/instant-access-merge-your-onedrive-and-microsoft-account/"><u>Instant Access: Merge Your OneDrive & Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-eliminate-microsoft-store-error-0x80072efd/"><u>Master Plan to Eliminate Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-instagram-increasingdecreasing-stories-frame-rate/"><u>Mastering Instagram  Increasing/Decreasing Stories' Frame Rate</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-camera-quirks-with-ease/"><u>Navigating Window's Camera Quirks with Ease</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-guide-learning-the-right-ways-to-start-facebook-live-shopping-for-2024/"><u>New Guide Learning the Right Ways To Start Facebook Live Shopping for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-nord-n30-se-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Nord N30 SE Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-upload-obstacles-with-onedrive-on-win-11/"><u>Overcoming Upload Obstacles with OneDrive on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unnoticed-windows-11-camera-use/"><u>Preventing Unnoticed Windows 11 Camera Use</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-fixes-for-resident-evil-5-wont-start-on-pc/"><u>Resolved: Fixes for 'Resident Evil 5 Won't Start on PC'</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-not-available-errors-on-your-windows-11-pc/"><u>Resolving 'Network Not Available' Errors on Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/retrieve-past-cortana-interactions-in-windows-files/"><u>Retrieve Past Cortana Interactions in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11-after-password-hurdle/"><u>Reviving Windows 11 After Password Hurdle</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-ends-refund-trap-consequences-explored/"><u>Steam Ends Refund Trap: Consequences Explored</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-twilight-zone-paints-dark-mode-magic/"><u>Step Into the Twilight Zone: Paint's Dark Mode Magic</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-solutions-to-windows-11-login-screen-problems/"><u>Surgical Solutions to Windows 11 Login Screen Problems</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-photographers-path-to-perfected-colors-for-2024/"><u>The Photographer's Path to Perfected Colors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-must-have-apps-to-replace-windows-11-essentials/"><u>Top 10 Must-Have Apps to Replace Windows 11 Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-mobile-hotspot-connectivity-on-windows-11/"><u>Troubleshooting Failed Mobile Hotspot Connectivity on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-tecno-pop-8-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Tecno Pop 8 Phones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-honor-magic-6-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Honor Magic 6 | Dr.fone</u></a></li>
</ul></div>
