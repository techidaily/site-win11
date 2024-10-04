---
title: "Modifying Windows Files: Remove Restricted Permissions"
date: 2024-09-29T08:10:16.591Z
updated: 2024-10-04T01:42:54.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Modifying Windows Files: Remove Restricted Permissions"
excerpt: "This Article Describes Modifying Windows Files: Remove Restricted Permissions"
keywords: Windows Permission Removal,File Permission Change,Unlock Windows Files,Secure Windows Editing,Bypass File Restrictions,Access Denied Error Fix,Remove Windows Protections
thumbnail: https://thmb.techidaily.com/1d1233e027868c7eb597be592cc478aeb7aba77b444eae6e981167865c0c0478.jpg
---

## Modifying Windows Files: Remove Restricted Permissions

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-obs-optimization-for-seamless-fb-broadcasting/"><u>[New] In 2024, OBS Optimization for Seamless FB Broadcasting</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-virtual-collaboration-share-your-screens-with-facebook-viewers/"><u>[New] In 2024, Virtual Collaboration Share Your Screens with Facebook Viewers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-best-collection-sites-for-quick-access-to-youtube-vids/"><u>[Updated] In 2024, Best Collection Sites for Quick Access to YouTube Vids</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1716068684504-updated-in-2024-expert-picks-top-12-screen-recording-software-no-time-limit/"><u>[Updated] In 2024, Expert Picks Top 12 Screen Recording Software, No Time Limit!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bypass-the-number-requirement-setting-up-on-messaging-services-using-email-or-social-profiles/"><u>Bypass the Number Requirement: Setting Up on Messaging Services Using Email or Social Profiles</u></a></li>
<li><a href="https://windows11.techidaily.com/control-over-edges-ongoing-tasks-in-win11-environment/"><u>Control Over Edge's Ongoing Tasks in Win11 Environment</u></a></li>
<li><a href="https://techtrends.techidaily.com/crucial-criteria-for-choosing-a-motherboard-unveiling-7-key-factors/"><u>Crucial Criteria for Choosing a Motherboard: Unveiling 7 Key Factors</u></a></li>
<li><a href="https://win11.techidaily.com/dialogue-deployment-on-windows-11-systems/"><u>Dialogue Deployment on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-workflow-on-windows-the-best-apps-for-maximum-output/"><u>Elevate Workflow on Windows: The Best Apps for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zerodxgierordevicehung-in-win11-systems/"><u>Fixing ZeroDXGIErorDeviceHung in Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-bluetooth-pin-related-connectivity-issues-in-win11win10/"><u>How To Bypass Bluetooth Pin-Related Connectivity Issues in Win11/Win10</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-samsung-galaxy-a24-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Samsung Galaxy A24 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-redmi-a2-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Redmi A2 to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-uninstalling-epic-launcher-woes-on-w11-systems/"><u>Sidestep Uninstalling Epic Launcher Woes on W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-access-to-commands-setting-up-keybinds-effortlessly/"><u>Speedy Access to Commands: Setting up Keybinds Effortlessly</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-discounts-on-roku-streaming-sticks-and-players-this-prime-day/"><u>Top Discounts on Roku Streaming Sticks & Players This Prime Day</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-stealthy-login-silencing-security-prompts-in-windows-11/"><u>Tricks for Stealthy Login: Silencing Security Prompts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-and-office-updates-a-quick-cessation-guide/"><u>Windows & Office Updates: A Quick Cessation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-the-art-of-key-management/"><u>Windows Photos: The Art of Key Management</u></a></li>
</ul></div>

