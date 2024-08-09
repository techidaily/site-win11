---
title: The Complete Guide to Local Users and Groups on WIN11/10
date: 2024-08-08T13:20:56.080Z
updated: 2024-08-09T13:20:56.080Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Complete Guide to Local Users and Groups on WIN11/10
excerpt: This Article Describes The Complete Guide to Local Users and Groups on WIN11/10
keywords: Windows LUAG Guide,Win11 Local Groups,Group Policy Management,LUA Settings in WIN10,Manage Users on WIN11,User Group Config WIN10/WIN11,Windows Local User Adjustment
thumbnail: https://thmb.techidaily.com/9b8cd7a1defe234b7c5e19ea975a65111eb68a7f947172e793fdb9bfe98621fe.jpg
---

## The Complete Guide to Local Users and Groups on WIN11/10

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
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

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-control-youtube-audio-mobiledesktop-approach/"><u>[New] 2024 Approved  Control YouTube Audio  Mobile/Desktop Approach</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-skyrocket-traffic-and-views-discover-the-best-5-video-marketing-techniques/"><u>[New] 2024 Approved  Skyrocket Traffic and Views – Discover the Best 5 Video Marketing Techniques</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-channel-expansion-sharing-your-show-across-30-platforms/"><u>[New] In 2024, Channel Expansion  Sharing Your Show Across 30 Platforms</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cut-down-catch-more-the-best-url-reducers-for-youtube/"><u>[New] In 2024, Cut Down, Catch More  The Best URL Reducers for YouTube</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-harnessing-viral-potential-the-20-best-tiktok-caption-insights/"><u>[New] In 2024, Harnessing Viral Potential  The 20 Best TikTok Caption Insights</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-do-a-poll-on-instagram-stories-a-complete-guide/"><u>[Updated] How to Do a Poll on Instagram Stories - a Complete Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-expert-tips-efficiently-download-igtv-on-windows-and-macos/"><u>[Updated] In 2024, Expert Tips  Efficiently Download IGTV on Windows & MacOS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-innovative-cameras-for-circular-coverage-for-2024/"><u>[Updated] Innovative Cameras for Circular Coverage for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-the-excellent-church-streaming-services/"><u>[Updated] Navigating the Excellent Church Streaming Services</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-skyrocket-your-earnings-on-tiktok-discover-the-top-8-ways-for-2024/"><u>[Updated] Skyrocket Your Earnings on TikTok  Discover the Top 8 Ways for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-samsung-galaxy-f34-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Samsung Galaxy F34 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-life-for-outdated-bios-features/"><u>Breath of Life for Outdated BIOS Features</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-winvpn-fixed-remote-access-errors/"><u>Bridging Gaps in WinVPN: Fixed Remote Access Errors</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-the-grayed-extend-volume-buttons/"><u>Brighten Up the Grayed Extend Volume Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-vibrancy-to-windows-extended-volume-controls/"><u>Bring Back Vibrancy to Windows’ Extended Volume Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bring-life-to-monitors-with-custom-spotlight-backdrops/"><u>Bring Life to Monitors with Custom Spotlight Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bring-slack-notifications-back-from-the-dead-in-windows-11/"><u>Bring Slack Notifications Back From the Dead in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forth-hidden-windows-drive/"><u>Bringing Forth Hidden Windows Drive</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-stranded-status-a-quick-guide-for-xbox-users/"><u>Bypassing ‘Stranded’ Status: A Quick Guide for Xbox Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-0x800713f-in-windows-1011s-mail-app/"><u>Bypassing 0X800713F in Windows 10/11'S Mail App</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-store-crash-code-x800704cf/"><u>Bypassing Microsoft's Store Crash Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windowed-world-exiting-wired-networks-at-100mbps/"><u>Bypassing the Windowed World: Exiting Wired Networks at 100Mbps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11s-operation-failure-error-code-0x0000011b/"><u>Bypassing Windows 11'S Operation Failure (Error Code: 0X0000011B)</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-0x80072af9-solution/"><u>Bypassing Windows Error: 0X80072AF9 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/changing-default-administrator-in-windows-11-pro/"><u>Changing Default Administrator in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-and-justifying-your-preferred-video-codecs-on-windows/"><u>Choosing and Justifying Your Preferred Video Codecs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigate-windows-s-mode-limitations/"><u>Circumnavigate Windows' S Mode Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-windows-restrictions-quickly/"><u>Circumventing Windows Restrictions Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-cluttered-drives-the-defrag-walkthrough/"><u>Clearing Cluttered Drives: The Defrag Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-black-screen-problem-in-windows-marketplace/"><u>Clearing Up Black Screen Problem in Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/combat-code-confusion-skyrim-sse-troubleshoot/"><u>Combat Code Confusion: Skyrim SSE Troubleshoot</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-breakdown-of-thermaltakes-premium-laptop-chiller-quality-vs-price-insights/"><u>Comprehensive Breakdown of Thermaltake's Premium Laptop Chiller: Quality vs Price Insights</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-delete-facebook-story-for-2024/"><u>How to Delete Facebook Story for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-nokia-c22-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Nokia C22 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-xiaomi-mix-fold-3-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Xiaomi Mix Fold 3 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/leading-alternatives-to-twitter-ranked-best/"><u>Leading Alternatives to Twitter, Ranked Best</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/master-screen-grabber-list-1-8-for-2024/"><u>Master Screen Grabber List #1-8 for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-8-free-screen-recorder-for-android/"><u>Top 8 Free Screen Recorder for Android</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Vivo X Flip | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>