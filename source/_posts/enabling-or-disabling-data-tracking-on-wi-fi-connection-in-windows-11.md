---
title: Enabling or Disabling Data Tracking on Wi-Fi Connection in Windows 11
date: 2024-10-22T19:57:28.781Z
updated: 2024-10-27T09:04:51.473Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling or Disabling Data Tracking on Wi-Fi Connection in Windows 11
excerpt: This Article Describes Enabling or Disabling Data Tracking on Wi-Fi Connection in Windows 11
keywords: Wi-Fi Tracking Control,Disable Data Tracker,Windows 11 Privacy Settings,Stop Wi-Fi Monitoring,Enable/Disable Wi-Fi Tracking,Windows 11 Privacy Options,Limit Network Data Usage
thumbnail: https://thmb.techidaily.com/a9e60c359d76678f8aad5193db4d1713b6255faff22e113abbe3abedfe2cc94d.jpeg
---

## Enabling or Disabling Data Tracking on Wi-Fi Connection in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-permitted-practices-for-saving-youtube-videos/"><u>[New] 2024 Approved Permitted Practices for Saving YouTube Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-low-cost-gopro-cameras-where-to-find-them/"><u>[Updated] Low-Cost GoPro Cameras Where to Find Them</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfect-your-visual-storytelling-inserting-titles-into-photo-videos-on-windows/"><u>[Updated] Perfect Your Visual Storytelling Inserting Titles Into Photo Videos on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-huawei-p60-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-microsoft-store-issue-x80073d26-on-win11/"><u>Correcting Microsoft Store Issue X:80073d26 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/file-resurrection-made-simple-8-methods-for-windows-users/"><u>File Resurrection Made Simple: 8 Methods for Windows Users</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/get-more-bang-for-your-buck-with-the-highly-praised-arcshell-ar-5/"><u>Get More Bang for Your Buck with the Highly Praised ArcShell AR- 5.</u></a></li>
<li><a href="https://win11.techidaily.com/guide-windows-index-adjustment-steps/"><u>Guide: Windows Index Adjustment Steps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-3-sites-to-find-free-infinix-unlock-codes-to-unlock-your-infinix-phone-by-drfone-android/"><u>In 2024, Top 3 Sites to Find Free Infinix Unlock Codes to Unlock Your Infinix Phone</u></a></li>
<li><a href="https://data-wizards.techidaily.com/intergalactic-file-recovery-resource/"><u>Intergalactic File Recovery Resource</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-in-it-support-with-troubleshooters-shortcut-guide/"><u>Maximize Efficiency in IT Support with Troubleshooters Shortcut Guide</u></a></li>
<li><a href="https://win11.techidaily.com/missed-sd-card-display-how-to-locate-it-in-explorer/"><u>Missed SD Card Display: How to Locate It in Explorer</u></a></li>
<li><a href="https://extra-support.techidaily.com/speak-out-leverage-ai-gratis-for-2024/"><u>Speak Out, Leverage AI Gratis for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/srgb-versus-rgb-a-detailed-comparison-for-professionals-for-2024/"><u>Srgb Versus Rgb A Detailed Comparison for Professionals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-utorrent-download-interruptions-on-pcs/"><u>Tackling uTorrent Download Interruptions on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-disk-management-a-comprehensive-walkthrough/"><u>Win 10/11 Disk Management: A Comprehensive Walkthrough</u></a></li>
</ul></div>

