---
title: Navigating to Local Users in Windows 11/10 Homes Quickly
date: 2024-09-16T08:23:43.977Z
updated: 2024-09-16T16:58:21.895Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Local Users in Windows 11/10 Homes Quickly
excerpt: This Article Describes Navigating to Local Users in Windows 11/10 Homes Quickly
keywords: Home User Navigate Windows,Windows 11 User Guide,Fast Homes Navigation,Windows Login Paths,Local Users Search Win,Find Homes in Win10/Win11,Quickly Locate Homes OS
thumbnail: https://thmb.techidaily.com/f29016c0fce2f518937f68251a2431a5f707a01cf190eb7eb7552fa0f6fd65d9.jpg
---

## Navigating to Local Users in Windows 11/10 Homes Quickly

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-breathtaking-review-and-different-directions/"><u>[New] Breathtaking Review & Different Directions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapchat-mastery-the-essential-guide-to-smartphone-screen-recording-for-2024/"><u>[New] Snapchat Mastery The Essential Guide to Smartphone Screen Recording for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-mirthful-milestones-an-examination-of-goofy-odyssey/"><u>[Updated] 2024 Approved 'Mirthful Milestones' An Examination of 'Goofy Odyssey'</u></a></li>
<li><a href="https://screen-recording.techidaily.com/beatback-bungalow-recordings-downloads-and-reviews/"><u>Beatback Bungalow Recordings Downloads & Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-adding-diamond-shadow-plug-in-compatible-with-matrix-to-your-kodi-setup/"><u>Easy Guide: Adding Diamond Shadow Plug-In Compatible with Matrix to Your Kodi Setup</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-of-m2ts-files-to-avi-a-step-by-step-tutorial-at-no-charge/"><u>Effortless Conversion of M2TS Files to AVI - A Step-by-Step Tutorial at No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-summer-discounts-buy-factory-pro-hd-video-converter-software-directly-from-our-website/"><u>Exclusive Summer Discounts: Buy Factory Pro HD Video Converter Software Directly From Our Website</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-shrinking-ogg-soundtracks-discover-the-leading-ogg-compression-software-solutions/"><u>Expert Tips for Shrinking OGG Soundtracks: Discover the Leading OGG Compression Software Solutions</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-a-broken-iphone-qr-reader-in-just-10-steps/"><u>Fixing a Broken iPhone QR Reader in Just 10 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/h264/"><u>H264形式適用方法：他の形式への変換手順と、それをもとに戻す簡単ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-and-save-threads-video-content/"><u>How to Download and Save Thread's Video Content</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-realme-narzo-60x-5g-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Realme Narzo 60x 5G FRP</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/youtube-meets-facebook-1080p-live-mastery-guide-for-2024/"><u>YouTube Meets Facebook 1080P Live Mastery Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dvd-walkman/"><u>ワイヤレスでDVDコピー - 簡単! Walkman内へのビデオと音声移行</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    