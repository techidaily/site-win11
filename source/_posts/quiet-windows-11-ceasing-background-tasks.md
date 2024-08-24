---
title: "Quiet Windows 11: Ceasing Background Tasks"
date: 2024-08-23T06:07:09.872Z
updated: 2024-08-24T06:07:09.872Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quiet Windows 11: Ceasing Background Tasks"
excerpt: "This Article Describes Quiet Windows 11: Ceasing Background Tasks"
keywords: Quiet Mode Windows 11,Noise Reduction Win11,Win11 Peaceful Settings,Silent Operations Win11,Background Tasks Suppression,Win11 Minimalist Mode,Stealthy Computing Win11
thumbnail: https://thmb.techidaily.com/992704407ab581931890c09cce338091c04f10f6ec09034fcef1854347c08c6c.jpg
---

## Quiet Windows 11: Ceasing Background Tasks

 Background apps in Windows continue to perform actions such as updates and fetch up-to-date data even when you are not using them. While Windows can intelligently manage and power-optimize background apps, it can still drain your battery and increase data usage.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

## 1\. How to Disable Background Apps via the Settings App

 If you want to disable individual Microsoft Store apps from running in the background, you can disable it from the Settings page. Follow the below steps to disable background apps from Settings.

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab in the left pane.
3. Click on **Installed apps** in the right pane and search to locate the app for which you want to change the background permission.
4. Click the **three-dots menu** icon next to the app name and select **Advanced options.** If the option is not available, then the app does not support the background app permission management feature.  
![advanced options windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-options-windows-11-settings.jpg)
5. Scroll down to the **Background apps permissions** section.  
![background app permission never](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/background-app-permission-never.png)
6. Click the drop-down for **Let this app run in background** and select **Never**. This should disable the app from running in the background.

 By default, the background permission for the app is set to **Power optimized(recommended)**. This means Windows will decide when the app can run in the background to save more power. If you set it to **Always**, the app will continuously run in the background irrespective of your power status.

## 2\. How to Disable Background Apps via Power & Battery Settings

 The Power & battery page in Windows 11 Settings provides data on the battery usage of installed apps. This is really useful If you want to disable background apps based on battery usage to save some juice.

 Here's how to do it.

1. Press **Win + X** to open the **WinX** men and select **Settings**.
2. In the **System** tab, scroll down and click on **Power & battery.**
3. Scroll down to the Battery section and click on **Battery usage.**  
![power and battery usage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/power-and-batter-usage.png)
4. Click the drop-down for **Battery levels** and select **Last 7 days.** Windows will load all the apps using the battery power in the last seven days.  
![manage background activity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/manage-background-activity.png)
5. To change the background app permission, click the **three-dots menu** beside the app name, and click on **Manage background productivity**. This option is only available for Microsoft Store apps.
6. Click the **drop-down** (**Power optimized**) under the **Background apps permissions** section and select **Never**. This will disable the app from running in the background.
7. Repeat the steps for all the apps that can drain your battery or affect system performance.

 In addition to disabling background apps, try to create and use [custom Windows power plans to extend your laptop battery life](https://www.makeuseof.com/tag/save-energy-extend-battery-life-custom-windows-power-plans/). With custom power plans, you can tweak your processor and other components to configure low-power modes to achieve an improved battery life.

## 3\. How to Disable Background Apps for the Current User

 If you want, you can disable background apps for the individual user. Useful if you share your PC with multiple users at work or home. Also useful if you need to disable a non-Microsoft third-party app from running in the background.

 For this, you will need to create a registry file and run it with administrative privilege. Before you proceed, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). You can use the restore point to revert your PC to its previous state if something goes wrong when editing the registry entries.

 To disable background apps for the current user:

1. Press **Win + R** to open the **Run** dialog.
2. Type **notepad** and click **OK** to open the text editor app.  
![disable background apps windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor.jpg)
3. In the Notepad file, copy and paste the following content:  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=dword:00000001  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=dword:00000000`
4. Next, press **Win + S** to open the **Save** dialog.
5. Here, name the file as **Disable\_Background\_Apps\_for\_current\_user.reg**. Then, click the **Save as type** drop-down and select **All Files.**  
![disable background apps windows 11 registry editor save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor-save.jpg)
6. Click the **Save** button to save the file.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`

## 4\. How to Disable Background Apps for All Users Using Registry Editor

 If you want to disable background apps for all the user accounts, you can manually create and modify the registry values in the Registry Editor.

 To disable background apps for all the user accounts:

1. Press **Win + R** to open **Run**.
2. Type **regedit**, and click **OK**. Click **Yes** to grant administrative access.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Under the **Windows** key, locate the **AppPrivacy** key**.** If not available, you will need to create a new key.  
![registry editor create new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-key.png)
5. Right-click on the **Windows** key and select **New > Key.** Rename the key as **AppPrivacy.**
6. Right-click on the **AppPrivacy** key and select **New > DWORD (32-bit) Value**. Rename the value as **LetAppsRunInBackground.**  
![registry editor create new value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-value.png)
7. Right-click on the **LetAppsRunInBackground** value and select **Modify**.  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Close the Registry Editor and restart your PC to apply the changes.

 This should disable Microsoft Store apps from running in the background. To enable the background apps, modify the **LetAppsRunInBackground** value and set it to **0**.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 5\. How to Disable Background Apps Using the Group Policy Editor

 Alternatively, you can also use the Group Policy Editor to configure background apps settings on your computer network. This is useful for system administrators having to configure multiple systems.

 Note that Group Policy Editor is officially only available in the Pro, Education, and Enterprise editions of the Windows OS. If you are on Home, read our guide on [how to enable Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). This involves a registry hack to enable the missing functionality in the Home edition of the OS.

 Once you have the policy editor up and running, continue with the steps below. To disable background apps using Group Policy Editor:

1. Press the **Win key**, type **group policy**, and click on **Edit group policy** from the search results.
2. In the Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\Windows Components\App Privacy​`
3. In the right pane, locate and double-click on **Let Windows apps run in the background** policy.  
![disable background app group policy editor policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor-policy.png)
4. In the new window that appears, select **Enabled**.
5. Next, under the **Options** section, click the drop-down for **Default for all apps** and select **Force Deny**.  
![disable background app group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor.png)
6. Click **OK** and **Apply** to save the changes.

 Alternatively, you can set the Let Windows apps run in the background policy to **Disabled** and apply the changes. However, when set to **Disabled** or **Not Configured**, individual employees in your organization can configure the apps to run in the background.

 On the contrary, setting this policy to **Force Deny** will prevent the app from running in the background, with no option for the employees to change the policy.

## Disabling Background Apps in Windows 11

 Windows allows you to configure background app permission for the Microsoft Store apps. You can disable these apps to conserve battery and avoid unnecessary data usage on a metered connection.

 That said, if you are struggling with slow system performance issues, disabling background apps may not be the solution. What you can do instead is reconfigure your OS, analyze your storage devices and look for hardware upgrades to boost system performance.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/new-crafting-captivating-jujutsu-kaisen-videos-for-tiktok/"><u>[New] Crafting Captivating Jujutsu Kaisen Videos for TikTok</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-master-your-pcs-sounds-with-easy-recording-tool-x-recorder/"><u>[New] Master Your PC's Sounds with Easy Recording Tool – X-Recorder</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-scene-selection-mastery-livestreams/"><u>[Updated] In 2024, Scene Selection Mastery Livestreams</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-ultimate-guide-to-import-photos-and-videos-into-windows-10/"><u>[Updated] In 2024, The Ultimate Guide to Import  Photos & Videos Into Windows 10</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-peeking-into-pixel-performance-a-complete-guide-to-measuring-views-and-income-on-youtube/"><u>[Updated] Peeking Into Pixel Performance  A Complete Guide to Measuring Views and Income on YouTube</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-nokia-g42-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Nokia G42 5G Activity | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-easy-access-best-free-youtube-subtitle-extractors/"><u>2024 Approved  Easy Access  Best Free YouTube Subtitle Extractors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gopro-hero5-captured-life-review/"><u>2024 Approved  GoPro Hero5 Captured Life Review</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-humorous-haven-gratuitous-meme-makers/"><u>2024 Approved  Humorous Haven  Gratuitous Meme Makers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/charting-a-course-for-youtube-success-viewer-numbers-and-income-for-2024/"><u>Charting a Course for YouTube Success  Viewer Numbers and Income for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/cookiebot-the-secret-ingredient-for-successful-online-marketing-campaigns/"><u>Cookiebot: The Secret Ingredient for Successful Online Marketing Campaigns</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-sticky-note-desynchronization-in-w11/"><u>Counteracting Sticky Note Desynchronization in W11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-dumps-on-windows-to-solve-issues/"><u>Deciphering Dumps on Windows to Solve Issues</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elite-listings-alert-texas-property-for-24-million-with-an-integrated-5786-square-foot-data-facility-and-innovative-cooling-system-no-bedroom-zone/"><u>Elite Listings Alert: Texas Property for $2.4 Million with an Integrated 5,786 Square Foot Data Facility and Innovative Cooling System – No Bedroom Zone</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-your-phones-games-enjoy-android-titles-on-windows-11-and-google-play/"><u>Embrace Your Phone's Games: Enjoy Android Titles on Windows 11 and Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-windows-ecosystem-wsl-and-win-11/"><u>Enhancing Your Windows Ecosystem: WSL & Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-interaction-failures-in-new-windows-11-os/"><u>Fixing Interaction Failures in New Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-invalid-path-in-windows-os/"><u>Fixing Invalid Path in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win-10-and-11-intruder-exceptions-error-message/"><u>Fixing Win 10 & 11 Intruder Exceptions Error Message</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xbox-subscription-issue-with-error-code-0x00000001/"><u>Fixing Xbox Subscription Issue with Error Code 0X00000001</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-infinix-hot-40i-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Infinix Hot 40i Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-15-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 15 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-restart-a-users-guide-for-quick-start-in-windows-11/"><u>How to Swiftly Restart: A User’s Guide for Quick Start in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-s23-fe-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy S23 FE to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-definitive-srt-file-generation-manual/"><u>In 2024, The Definitive SRT File Generation Manual</u></a></li>
<li><a href="https://win11.techidaily.com/missing-bluetooth-in-win-11-strategies-for-quick-recovery/"><u>Missing Bluetooth in Win 11: Strategies for Quick Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-managing-windows-like-a-whiz/"><u>Navigating and Managing Windows Like a Whiz</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-glories-accessing-file-history/"><u>Navigating Past Glories: Accessing File History</u></a></li>
<li><a href="https://win11.techidaily.com/overruling-google-chromes-default-webp-imaging-process-pc-based/"><u>Overruling Google Chrome's Default WebP Imaging Process, PC-Based</u></a></li>
<li><a href="https://win11.techidaily.com/pioneers-playbook-for-win11-directory-creation/"><u>Pioneer's Playbook for Win11 Directory Creation</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-efficiency-top-5-data-exchange-tools-for-winpc/"><u>Prioritizing Efficiency: Top 5 Data Exchange Tools for WinPC</u></a></li>
<li><a href="https://win11.techidaily.com/propel-audio-innovations-setting-up-dolby-atmos-for-pcs/"><u>Propel Audio Innovations: Setting up Dolby Atmos for PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-11-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 11 Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/senior-centric-adjustments-on-pre-ultimate-windows-pcs/"><u>Senior-Centric Adjustments on Pre-Ultimate Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-accessing-windows-11s-file-journey/"><u>Step-by-Step: Accessing Windows 11'S File Journey</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-energy-management-full-charge-alerts-on-windows-11/"><u>Streamlining Energy Management: Full Charge Alerts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-of-devhome-integrating-win11-mastery/"><u>The Blueprint of DevHome: Integrating Win11 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/the-clever-way-to-compress-streamlined-windows-explorer/"><u>The Clever Way to Compress: Streamlined Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-features-windows-evolution/"><u>The Forgotten Features: Windows Evolution</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc0000005-on-windows-pcs/"><u>Troubleshooting Error Code 0xC0000005 on Windows PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-on-iphone-15-pro-max-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication On iPhone 15 Pro Max? 5 Tips You Must Know</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-psd-style-boosting-for-2024/"><u>Ultimate PSD Style Boosting for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unleash-creativity-video-art-and-live-streaming-with-vlc-webcam-capabilities-for-2024/"><u>Unleash Creativity  Video Art & Live Streaming with VLC Webcam Capabilities for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-efficiency-grouped-installs-with-winstall-on-windows-11/"><u>Unleashing Efficiency: Grouped Installs with Winstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-advanced-settings-for-a-secure-connection-on-win-11/"><u>Unlocking Advanced Settings for a Secure Connection on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-productivity-keyboard-shortcuts-guide/"><u>Unlocking Windows Productivity: Keyboard Shortcuts Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-resource-monitor-how-to-rejuvenate-a-non-responsive-app/"><u>Win11's Resource Monitor: How To Rejuvenate a Non-Responsive App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>