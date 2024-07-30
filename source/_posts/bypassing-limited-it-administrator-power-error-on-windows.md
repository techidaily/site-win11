---
title: Bypassing Limited IT Administrator Power Error on Windows
date: 2024-07-29T15:53:16.692Z
updated: 2024-07-30T15:53:16.692Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Limited IT Administrator Power Error on Windows
excerpt: This Article Describes Bypassing Limited IT Administrator Power Error on Windows
keywords: WIN_IT_Admin_Error,Bypassing IT Admin Fix,PowerShell Correction,WinErrorOverride,Administrator Limit Bypass,Windows IT Error Solve,Err0rBypass_Win10
thumbnail: https://thmb.techidaily.com/c62b5284641027dfddd7dff7e86c9bcc06523e51b87668f0c388f2d39f0ecdca.jpg
---

## Bypassing Limited IT Administrator Power Error on Windows

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to[changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to[removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to[open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article[about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on[creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://youtube-zero.techidaily.com/arths-premier-online-income-tycoon/"><u>[New] Earth’s Premier Online Income Tycoon</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-examining-the-strengths-and-weaknesses-in-free2x-tools-for-2024/"><u>[New] Examining the Strengths and Weaknesses in Free2X Tools for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-independent-android-adventures-the-ultimate-list-of-unplugged-titles-for-2024/"><u>[New] Independent Android Adventures - The Ultimate List of Unplugged Titles for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-youtube-monetization-a-cpm-perspective/"><u>[New] Mastering YouTube Monetization  A CPM Perspective</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-bottom-line-gear-collect-all-these-trendsetting-tools-to-win-in-business/"><u>[Updated] In 2024, Bottom Line Gear  Collect All These Trendsetting Tools to Win in Business</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-exploring-isprings-screencap-capabilities/"><u>2024 Approved  Exploring iSpring's Screencap Capabilities</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-fine-tune-your-virtual-interaction-with-close-up-google-meet-tips/"><u>2024 Approved  Fine-Tune Your Virtual Interaction with Close-Up Google Meet Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-learn-how-to-rewind-video-ordering-on-android/"><u>2024 Approved  Learn How to Rewind Video Ordering on Android</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleashing-creativity-the-top-10-after-effects-templates/"><u>2024 Approved  Unleashing Creativity  The Top 10 After Effects Templates</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-disable-microsoft-edge-tab-preloading-in-windows-11/"><u>4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-github-desktop-adoption-in-windows-11/"><u>Best Practices for GitHub Desktop Adoption in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-wakeable-entities-on-dormant-windows/"><u>Controlling Wakeable Entities on Dormant Windows</u></a></li>
<li><a href="https://win11.techidaily.com/critics-common-grumbles-windows-11-unveiled/"><u>Critics' Common Grumbles: Windows 11 Unveiled</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/dominate-search-results-essential-tips-for-optimizing-youtube-videos-for-2024/"><u>Dominate Search Results  Essential Tips for Optimizing YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-functional-state-in-dead-usb-ports-win-edition/"><u>Enabling Functional State in Dead USB Ports, Win Edition</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-frozen-grammarly-app-a-windows-users-guide/"><u>Fixing Frozen Grammarly App: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/from-easy-access-to-higher-security-transitioning-your-logon-method-on-windows-11/"><u>From Easy Access to Higher Security: Transitioning Your Logon Method on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-rectify-erroneous-device-listings-in-windows/"><u>Guidelines to Rectify Erroneous Device Listings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-windows-11-search-icon-from-a-text-bar/"><u>How to Change Windows 11 Search Icon From a Text Bar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-win-os-files-editable-again/"><u>How to Make Win OS Files Editable Again</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-the-quick-assist-tool-in-windows-11/"><u>How to Start the Quick Assist Tool in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-20-minutes-to-master-vrecorder-instalment/"><u>In 2024, 20 Minutes To Master VRecorder Instalment</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-apple-iphone-6s-mirror-to-pc-top-apps-you-must-know-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 6s Mirror to PC? Top Apps You Must Know | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/is-your-iphone-se-2020-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>Is Your iPhone SE (2020) in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-account-lockout-tally-post-unsuccessful-login-attempts-in-windows-1011/"><u>Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigating-high-definition-zoom-features-for-2024/"><u>Navigating High-Definition Zoom Features for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-task-management-in-windows-11-via-enhanced-run-functionality/"><u>Optimizing Task Management in Windows 11 via Enhanced Run Functionality</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-y100i-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-efficient-downloads-tips-from-microsofts-store/"><u>Quick and Efficient Downloads: Tips From Microsoft’s Store</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-rejuvenate-a-non-operative-resource-monitor-in-windows-11/"><u>Quick Fixes to Rejuvenate a Non-Operative Resource Monitor in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-guide-eliminating-photo-viewer-crashes-on-windows-10-for-2024/"><u>Quick Guide  Eliminating Photo Viewer Crashes on Windows 10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-help-app-failure/"><u>Resolving Windows 11 Help App Failure</u></a></li>
<li><a href="https://data-wizards.techidaily.com/restore-ravaged-dv-avi-video-streams/"><u>Restore Ravaged DV, AVI Video Streams</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-offline-mode-in-microsoft-onedrive/"><u>Setting Up Offline Mode in Microsoft OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-app-management-on-windows-11-os/"><u>Speedy App Management on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-error-code-0x000-on-your-windows-11-devices-xbox-game-pass/"><u>Swiftly Resolving Error Code 0X000_ on Your Windows 11 Devices' Xbox Game Pass</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tips-for-entering-a-friends-tiktok-live-stream/"><u>Tips for Entering a Friend's TikTok Live Stream</u></a></li>
<li><a href="https://win11.techidaily.com/transition-windows-calculator-to-dark-mode/"><u>Transition Windows Calculator to Dark Mode</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unheard-voices-on-youtube-livestream-success-beyond-1000-supporters/"><u>Unheard Voices on YouTube  Livestream Success Beyond 1000 Supporters</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-pcs-integrating-enhanced-run-utility-for-windows/"><u>Unleash Potential of PCs: Integrating Enhanced Run Utility for Windows</u></a></li>
</ul></div>
