---
title: Unlocking Administrator Rights for Your Home Win11/10
date: 2024-09-27T00:26:05.683Z
updated: 2024-10-04T04:10:55.311Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Administrator Rights for Your Home Win11/10
excerpt: This Article Describes Unlocking Administrator Rights for Your Home Win11/10
keywords: Home Win11 Admin Access,Gain Win11 Admin Control,Win11 Enable Superuser,Unlock Home PC Admin,Obtain Windows Admin Rights,Activate Win10/11 Admin Mode,Elevate Win10 Home Power User
thumbnail: https://thmb.techidaily.com/02374ddd20d049e41c0d0fe41e4dbd023d73e596f3add5f5b8f6d266eddb08ec.png
---

## Unlocking Administrator Rights for Your Home Win11/10

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934138/19272" target="_top" id="1934138">
  <img src="//a.impactradius-go.com/display-ad/19272-1934138" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934138/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-how-to-make-money-from-instagram/"><u>[New] In 2024, How to Make Money From Instagram</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-vdq-quickscreen-recorder-report-in-depth-analysis/"><u>[Updated] 2024 Approved VDQ QuickScreen Recorder Report In-Depth Analysis</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-charting-a-path-to-youtube-wealth-cpm-analysis/"><u>[Updated] Charting a Path to YouTube Wealth CPM Analysis</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-harness-youtubes-creative-commons-in-video-making/"><u>[Updated] How to Harness YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44kk44oz44k44o844on44od44oi44gl44kj5yuv55s744ks44kt44oj44ox44ob44oj44gz44kl44gf44kb44gu44k544og44od44ox44oq44kk44k544og44od44ox44ks44kk44oj44cn/"><u>「インターネットから動画をキャプチャするためのステップバイステップガイド」</u></a></li>
<li><a href="https://win11.techidaily.com/1726030191811-mp4/"><u>「プロモーションビデオ作成後にMP4ファイルが正常に再生されない場合の解決法」</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-recommended-steadicams-for-professional-dslr-work/"><u>2024 Approved Expert-Recommended Steadicams for Professional DSLR Work</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-surge-to-subscriber-success-with-strategic-tactics/"><u>2024 Approved Surge to Subscriber Success with Strategic Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/2024-ps5/"><u>2024年版 PS5 ビデオ再生問題解決法：ステップバイステップガイド</u></a></li>
<li><a href="https://win11.techidaily.com/1726029921217-20246/"><u>2024年最高のオンラインビデオ編集プラットフォームベスト6</u></a></li>
<li><a href="https://win11.techidaily.com/1726030205806-wav/"><u>高度WAV編集ガイド：効果的にトリミング・組み合わせ・ボリューム調整法</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-your-view-count-this-tutorials-top-hit-for-2024/"><u>Boost Your View Count This Tutorial's Top Hit for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/excel-file-recovery-recover-corrupt-excel-2019-files-easily-stellar-by-stellar-guide/"><u>Excel File Recovery – Recover Corrupt Excel 2019 Files Easily | Stellar</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/maximizing-online-visibility-through-advanced-cookiebot-features/"><u>Maximizing Online Visibility Through Advanced Cookiebot Features</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-itel-s23-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Itel S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1726030041701-youtube/"><u>YouTube ミュージックダウンロードガイド - 曲を正しく記録するための効果的な手法</u></a></li>
<li><a href="https://win11.techidaily.com/1726029971792-obs-studio/"><u>ぜひ体験！OBS Studioで美しくキレイに高精細化されたゲーム動画の作成法</u></a></li>
<li><a href="https://win11.techidaily.com/1726028587575-dvd/"><u>トラブルシューティング: DVDプレイヤーでエラー発生時の原因分析・修正手順</u></a></li>
<li><a href="https://win11.techidaily.com/44oh44oh44kj44ki44ov44kh44kk44or566h55cg44gr54m55yyw44gx44gf44gv44gplus44gw44gplus44gq44k944ov44oi44km44kn44ki44o744oe44o844or44go44ki44ox44oq44kx44o844k34490/"><u>メディアファイル管理に特化したさまざまなソフトウェア・ツールとアプリケーションを紹介する</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    