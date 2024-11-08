---
title: Privacy Tips for Keeping Emails Secret on Logon Screen
date: 2024-11-01T22:04:13.370Z
updated: 2024-11-07T22:07:04.029Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016129/19272" target="_top" id="2016129">
  <img src="//a.impactradius-go.com/display-ad/19272-2016129" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016129/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/updated-how-to-use-android-phones-in-watching-vr-or-360-videos/"><u>[Updated] How to Use Android Phones in Watching VR or 360 Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-from-flat-panes-to-360-viewing-a-vr-comparison/"><u>2024 Approved From Flat Panes to 360 Viewing A VR Comparison</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-from-followers-to-brand-ambassadors-the-five-pillars-of-influencer-success/"><u>2024 Approved From Followers to Brand Ambassadors The Five Pillars of Influencer Success</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/assessing-ergodriven-topo-mats-how-they-transform-your-desk-into-a-comfort-zone-against-tiredness/"><u>Assessing Ergodriven Topo Mats: How They Transform Your Desk Into a Comfort Zone Against Tiredness</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-registry-tweaks-via-terminal-commands/"><u>Delving Deep Into Windows Registry Tweaks via Terminal Commands</u></a></li>
<li><a href="https://win11.techidaily.com/effective-fix-tackling-winscomrssvc-errors-on-your-pc/"><u>Effective Fix: Tackling WinscomrsSvc Errors on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/embarking-on-the-journey-setting-up-outlook-preview-in-windows-11/"><u>Embarking on the Journey: Setting Up Outlook Preview in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-instantly-design-custom-coverage-for-your-short-videos/"><u>How To Instantly Design Custom Coverage For Your Short Videos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-itel-p40plus-to-mac-drfone-by-drfone-android/"><u>How to Mirror Itel P40+ to Mac? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-lava-blaze-curve-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Lava Blaze Curve 5G</u></a></li>
<li><a href="https://win11.techidaily.com/hush-unmet-system-mandates-on-windows-os/"><u>Hush Unmet System Mandates on Windows OS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-through-fresh-twitter-conspiracies-the-inception-of-meta-verification-and-a-deep-dive-into-chatgpt/"><u>Navigating Through Fresh Twitter Conspiracies: The Inception of Meta Verification & A Deep Dive Into ChatGPT-</u></a></li>
<li><a href="https://win11.techidaily.com/snip-and-sketch-vs-prtsc-the-windowed-capturing-conundrum/"><u>Snip and Sketch Vs. PrtSc: The Windowed Capturing Conundrum</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-activate-windows-admin-tools-in-homes/"><u>Step-by-Step: Activate Windows Admin Tools in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-fix-eliminating-connection-issues-in-windows/"><u>Streamline & Fix: Eliminating Connection Issues in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-poco-c55-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Poco C55 Phones</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-buying-a-high-quality-smart-tv-for-2nnd-century-insights-from-zdnets-tech-experts/"><u>Ultimate Guide to Buying a High-Quality Smart TV for 2Nnd Century: Insights From ZDNet's Tech Experts</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-fatal-components-missing-in-w10w11/"><u>Unraveling the 'Fatal Components Missing' In W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-wisely-enabling-tpm-and-secure-boot-pre-windows-11-installation/"><u>Upgrading Wisely: Enabling TPM and Secure Boot Pre-Windows 11 Installation</u></a></li>
</ul></div>

