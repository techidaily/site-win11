---
title: "Unlock Local Admin: Navigating Win11/10 Homes Effortlessly"
date: 2024-09-12T01:31:12.996Z
updated: 2024-09-16T16:06:31.629Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Local Admin: Navigating Win11/10 Homes Effortlessly"
excerpt: "This Article Describes Unlock Local Admin: Navigating Win11/10 Homes Effortlessly"
keywords: Win11AdminAccess,LocalWin10Control,AdminUnlockWindows,EasyWinElevation,HomeUserAdvance,HomesOSMgmtTools,WindowsHomeAdmin
thumbnail: https://thmb.techidaily.com/9ed4d2a342c503dc1182b48b6f97e1914eb836100fe0df4621fadbbe35959f4b.jpg
---

## Unlock Local Admin: Navigating Win11/10 Homes Effortlessly

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

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-operational-obs-cam-after-fix/"><u>[New] In 2024, Operational OBS Cam After Fix</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-10-best-youtube-makeup-artists-you-must-have-heard/"><u>2024 Approved 10 Best YouTube Makeup Artists You Must Have Heard</u></a></li>
<li><a href="https://tech-haven.techidaily.com/advanced-prompting-tricks-for-superior-results-from-chatgpt/"><u>Advanced Prompting Tricks for Superior Results From ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-art-generation-how-to-combine-dall-e-with-the-power-of-chatgpt-4/"><u>AI Art Generation: How to Combine DALL-E with the Power of ChatGPT-4</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatgpt-in-commerce-7-ways-to-enhance-business-operations/"><u>ChatGPT in Commerce: 7 Ways to Enhance Business Operations</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-guide-clearing-browsing-history-and-caches-across-all-top-web-browsers/"><u>Complete Guide: Clearing Browsing History & Caches Across All Top Web Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-fixes-for-winupdater-errors-solve-x80246007/"><u>Efficient Fixes for WinUpdater Errors – Solve X80246007</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordevicehunk-on-windows-11-systems/"><u>Handling DXGI_ERROR_DEVICE_HUNK on Windows 11 Systems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-lava-blaze-2-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Lava Blaze 2</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-poco-m6-pro-5g-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Poco M6 Pro 5G to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/showcasing-peak-and-base-states-of-your-cpu-in-windows/"><u>Showcasing Peak and Base States of Your CPU in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-apex-legends-crashes-in-windows-11/"><u>Winning Against Apex Legends Crashes in Windows 11</u></a></li>
</ul></div>

