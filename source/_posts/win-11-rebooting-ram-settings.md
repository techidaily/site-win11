---
title: "Win 11: Rebooting RAM Settings"
date: 2024-09-20T20:43:26.426Z
updated: 2024-09-21T18:02:07.191Z
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
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-xiaomi-mi-11-a-guide-to-screen-recording-pro/"><u>[New] In 2024, Xiaomi Mi 11 A Guide to Screen Recording Pro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-must-visit-web-resources-for-text-aesthetics-and-functionality/"><u>[New] Must-Visit Web Resources for Text Aesthetics & Functionality</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-secure-total-visual-display-for-2024/"><u>[Updated] Secure Total Visual Display for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-lava-yuva-3-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Lava Yuva 3</u></a></li>
<li><a href="https://games-able.techidaily.com/examine-pimaxs-crystal-clarity-a-visual-treat-with-bugs/"><u>Examine Pimax's Crystal Clarity - A Visual Treat with Bugs</u></a></li>
<li><a href="https://win11.techidaily.com/give-your-windows-mail-and-calendar-apps-a-cool-look-with-your-favorite-pictures/"><u>Give Your Windows Mail and Calendar Apps a Cool Look With Your Favorite Pictures</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-infinix-note-30-pro-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Infinix Note 30 Pro Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-frozen-intellij-unison-app-on-your-win11-pc/"><u>How to Fix a Frozen IntelliJ Unison App on Your Win11 PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-cricket-apple-iphone-11-for-free-by-drfone-ios/"><u>In 2024, How To Unlock Cricket Apple iPhone 11 for Free</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-a-technical-approach-to-combining-soundtracks-with-video-footage-on-mobile-devices/"><u>New A Technical Approach to Combining Soundtracks with Video Footage on Mobile Devices</u></a></li>
<li><a href="https://win-able.techidaily.com/scavenger-race-victory-guide-master-your-match-on-pc/"><u>Scavenger Race Victory Guide - Master Your Match on PC!</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-to-the-too-many-requests-error-on-windows-platform/"><u>Swift Solutions to the Too Many Requests Error on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-gen-workstation-a-closer-look-at-the-asus-s15-bape-edition/"><u>The Next-Gen Workstation: A Closer Look at the ASUS S15 BAPE Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-hidden-mastering-dark-modes-in-notepad-win-11-edition/"><u>Unlock the Hidden: Mastering Dark Modes in Notepad, Win 11 Edition</u></a></li>
</ul></div>

