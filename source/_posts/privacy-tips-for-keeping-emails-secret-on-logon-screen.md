---
title: Privacy Tips for Keeping Emails Secret on Logon Screen
date: 2024-11-12T04:10:47.294Z
updated: 2024-11-17T16:36:18.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Privacy Tips for Keeping Emails Secret on Logon Screen
excerpt: This Article Describes Privacy Tips for Keeping Emails Secret on Logon Screen
keywords: Email Privacy Secrets,Hide Email Login,Secure Email Access,Protect Personal Mail,Stealthy Email View,Safeguard Logon E-Mails,Keep Email Concealed Login
thumbnail: https://thmb.techidaily.com/dc54f112c78b3afb0110331eb25c5f493a4d3b2149d6ee352dfe8394d4845198.jpg
---

## Privacy Tips for Keeping Emails Secret on Logon Screen

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144275/7443" target="_top" id="2144275">
  <img src="//a.impactradius-go.com/display-ad/7443-2144275" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144275/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-audiovisual-excellence-on-youtube-through-enhancements/"><u>[Updated] 2024 Approved Audiovisual Excellence on YouTube Through Enhancements</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-premium-sound-selection-optimal-websites-list/"><u>[Updated] Premium Sound Selection Optimal Websites List</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-efficient-tactics-for-viewing-subscribers-on-yt/"><u>2024 Approved Efficient Tactics for Viewing Subscribers on YT</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-understanding-your-chances-for-regular-youtube-payments/"><u>2024 Approved Understanding Your Chances for Regular YouTube Payments</u></a></li>
<li><a href="https://tech-revival.techidaily.com/advanced-ai-integration-in-microsoft-teams-for-seamless-webcam-backdrop-management/"><u>Advanced AI Integration in Microsoft Teams for Seamless Webcam Backdrop Management</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-iphone-15-pro-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On iPhone 15 Pro? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://buynow-info.techidaily.com/decoding-the-strength-and-weakness-of-vyancs-link-tracker-sturdy-performance-marred-by-confusing-pricing-plans/"><u>Decoding the Strength and Weakness of Vyanc's Link Tracker: Sturdy Performance Marred By Confusing Pricing Plans</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-gpu-within-your-operating-system-windows/"><u>Disabling GPU Within Your Operating System Windows</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-disruption-fixes-for-windows-update/"><u>Error 2E Disruption? Fixes for Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/from-out-of-sight-to-front-and-center-recovering-windows-1011-panels/"><u>From Out of Sight to Front and Center: Recovering Windows 10/11 Panels</u></a></li>
<li><a href="https://win11.techidaily.com/maintaining-your-data-regularly-back-up-windows-files/"><u>Maintaining Your Data: Regularly Back Up Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-online-ops-top-4-windows-steps-to-gauge-network-velocity/"><u>Optimize Your Online Ops: Top 4 Windows Steps to Gauge Network Velocity</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-honor-x50-gt-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Honor X50 GT Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-limited-access-to-wi-fi-in-windows-11-top-7-fixes/"><u>Unblock Limited Access to Wi-Fi in Windows 11: Top 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/win-back-control-solutions-to-thwart-stuck-menu-clicks/"><u>Win Back Control: Solutions to Thwart Stuck Menu Clicks</u></a></li>
</ul></div>

