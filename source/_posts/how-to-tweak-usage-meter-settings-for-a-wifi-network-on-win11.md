---
title: How to Tweak Usage Meter Settings for a Wifi Network on Win11
date: 2024-10-21T10:21:38.454Z
updated: 2024-10-27T05:32:23.490Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Tweak Usage Meter Settings for a Wifi Network on Win11
excerpt: This Article Describes How to Tweak Usage Meter Settings for a Wifi Network on Win11
keywords: Win11 Wi-Fi Adjustment Guide,Win11 Meter Tuning Tips,Win11 WiFi Speed Control,Win11 Usage Settings Edit,Windows 11 Wifi Configuration,Win11 Network Performance Tweaks,Optimize Win11 Wi-Fi Meter
thumbnail: https://thmb.techidaily.com/39537ef670f74abdd3937163bf686c62a000d8146ce98f4b0e1e21a62378c3d8.jpg
---

## How to Tweak Usage Meter Settings for a Wifi Network on Win11

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
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-off-facebook-activity-expose-is-it-worth-the-scrutiny-for-2024/"><u>[New] Off-Facebook Activity Exposé - Is It Worth The Scrutiny for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-sounds-of-laughter-top-ringtones-downloaders/"><u>[New] Sounds of Laughter Top Ringtones Downloaders</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-guide-on-transforming-youtube-videos-into-mp3-using-safe-procedures/"><u>[Updated] Guide on Transforming YouTube Videos Into MP3 Using Safe Procedures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-digital-portraits-proven-the-science-of-social-snap-validation/"><u>[Updated] In 2024, Digital Portraits Proven The Science of Social Snap Validation</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-samsung-galaxy-s23-ultra-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Samsung Galaxy S23 Ultra to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/direct-linking-of-onedrive-and-microsoft-live-id/"><u>Direct Linking of OneDrive and Microsoft Live ID</u></a></li>
<li><a href="https://howto.techidaily.com/fix-xiaomi-redmi-note-12-pro-4g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Xiaomi Redmi Note 12 Pro 4G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-automate-attachment-behavior-in-word-for-pure-text-viewing-only/"><u>How to Automate Attachment Behavior in Word for Pure Text Viewing Only</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-most-value-from-windows-11-product-codes/"><u>How to Get the Most Value From Windows 11 Product Codes</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-google-pixel-fold-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-vivo-y36i-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Vivo Y36i</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-stopping-windows-11s-surveillance-systems/"><u>Mastery in Stopping Windows 11'S Surveillance Systems</u></a></li>
<li><a href="https://win11.techidaily.com/optimized-email-checking-securely-placement-of-gmail-bar/"><u>Optimized Email Checking: Securely Placement of Gmail Bar</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-supported-audio-problems-windowss/"><u>Overcoming Non-Supported Audio Problems Windowss</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-inactive-airflow-management-guidelines/"><u>Reviving Inactive Airflow Management Guidelines</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-disabled-taskbar-icon-clicks/"><u>Solutions for Disabled Taskbar Icon Clicks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-troubleshooting-curing-your-facetime-black-display-problem/"><u>Step-by-Step Troubleshooting: Curing Your FaceTime Black Display Problem</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-write-access-blockade-in-winos/"><u>Unlocking File Write Access Blockade in WINOS</u></a></li>
<li><a href="https://fox-access.techidaily.com/video-movie-maker-for-windows-8-for-2024/"><u>Video Movie Maker for Windows 8 for 2024</u></a></li>
</ul></div>

