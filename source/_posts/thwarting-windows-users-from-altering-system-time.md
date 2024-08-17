---
title: Thwarting Windows Users From Altering System Time
date: 2024-08-15T23:48:05.719Z
updated: 2024-08-16T23:48:05.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Thwarting Windows Users From Altering System Time
excerpt: This Article Describes Thwarting Windows Users From Altering System Time
keywords: Stop Time Change on Win PCs,Prevent Windows Clock Adjustment,Halt User Time Manipulation (Windows),Block System Time in Windows,Secure Windows Time Settings,Thwart Clock Changes Windows,Protect Windows Time Accuracy
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Thwarting Windows Users From Altering System Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-building-an-impressive-instagram-network-for-2024/"><u>[New] Building an Impressive Instagram Network for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-content-choice-conundrum-is-podcasting-right-or-should-you-go-for-youtube/"><u>[New] Content Choice Conundrum  Is Podcasting Right, Or Should You Go for YouTube?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-enhance-your-feed-efficiently-adding-multiple-photographs-and-videos-to-ig-for-2024/"><u>[New] Enhance Your Feed  Efficiently Adding Multiple Photographs & Videos to IG for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-embark-on-a-wanderlust-adventure-becoming-a-professional-travel-vlogger-for-2024/"><u>[Updated] Embark on a Wanderlust Adventure  Becoming A Professional Travel Vlogger for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-raw-footage-to-final-cut-chroma-mastery-for-2024/"><u>[Updated] From Raw Footage to Final Cut  Chroma Mastery for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-zero-to-live-streaming-hero-essential-tips-and-tricks/"><u>[Updated] From Zero to Live-Streaming Hero  Essential Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-purifypicture-premium-bg-eraser-and-editor/"><u>2024 Approved  PurifyPicture  Premium BG Eraser & Editor</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-higher-view-counts-through-sustained-compliance-with-youtube-cc/"><u>2024 Approved  Unlocking Higher View Counts Through Sustained Compliance with YouTube CC</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/6-android-apps-perfect-for-a-windows-11-enthusiast/"><u>6 Android Apps Perfect for a Windows 11 Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-accessing-windows-odbc-tools/"><u>A Beginner's Guide to Accessing Windows' ODBC Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-removable-storage-via-explore-navigation-menu/"><u>Adding Removable Storage via Explore Navigation Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-brightness-control-software-for-windows-multiscreen-enthusiasts/"><u>Advanced Brightness Control Software for Windows Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-volume-control-on-windows-bluetooth/"><u>Amplifying Volume Control on Windows-Bluetooth</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-sonic-full-screen-pitfalls-on-windows-11-os/"><u>Avoiding Sonic Full-Screen Pitfalls on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blues-effective-methods-for-hybrid-os-errors-in-winxose/"><u>Beat the Blues: Effective Methods for Hybrid OS Errors in WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-a-valid-temp-folder-in-windows-11/"><u>Best Practices for a Valid Temp Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/blending-gmail-with-outlook-on-windows-comprehensive-guide/"><u>Blending Gmail with Outlook on Windows: Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-overturning-monochrome-windows-display/"><u>Breaking Free: Overturning Monochrome Windows Display</u></a></li>
<li><a href="https://extra-hints.techidaily.com/composing-captivating-cinema-trailers/"><u>Composing Captivating Cinema Trailers</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-monitors-non-full-screen-output-in-win11/"><u>Corrected Monitor's Non-Full Screen Output in Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-y55s-5g-2023-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo Y55s 5G (2023) Is Unlocked</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-14-plus-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 14 Plus with 3 Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unleash-your-creative-vision-with-youtubes-filmmaking-courses/"><u>Unleash Your Creative Vision with YouTube's Filmmaking Courses</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/what-is-youtube-tag-and-how-to-find-great-tags-for-your-videos-in-2024/"><u>What Is YouTube Tag and How to Find Great Tags For Your Videos, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
</ul></div>
