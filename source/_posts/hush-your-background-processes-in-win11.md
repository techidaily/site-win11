---
title: Hush Your Background Processes in Win11
date: 2025-01-18T19:10:30.805Z
updated: 2025-01-25T08:46:18.842Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hush Your Background Processes in Win11
excerpt: This Article Describes Hush Your Background Processes in Win11
keywords: Win11 Hush BG Processes,Silence Win11 Bg Tasks,Minimize Win11 Bg Noise,Reduce Win11 Background Load,Quieten Win11 Runner Jobs,Tame Win11 Hidden Processes,Diminish Win11 BG Tasks
thumbnail: https://thmb.techidaily.com/09131504d6b18963281f522bba9f2baa6f9c4f1ee05a4b5b8a249fec882bec30.jpg
---

## Hush Your Background Processes in Win11

 Background apps in Windows continue to perform actions such as updates and fetch up-to-date data even when you are not using them. While Windows can intelligently manage and power-optimize background apps, it can still drain your battery and increase data usage.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Background Apps via the Settings App

 If you want to disable individual Microsoft Store apps from running in the background, you can disable it from the Settings page. Follow the below steps to disable background apps from Settings.

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab in the left pane.
3. Click on **Installed apps** in the right pane and search to locate the app for which you want to change the background permission.
4. Click the **three-dots menu** icon next to the app name and select **Advanced options.** If the option is not available, then the app does not support the background app permission management feature.  
![advanced options windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-options-windows-11-settings.jpg)
5. Scroll down to the **Background apps permissions** section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![background app permission never](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/background-app-permission-never.png)
6. Click the drop-down for **Let this app run in background** and select **Never**. This should disable the app from running in the background.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Background Apps for the Current User

 If you want, you can disable background apps for the individual user. Useful if you share your PC with multiple users at work or home. Also useful if you need to disable a non-Microsoft third-party app from running in the background.

 For this, you will need to create a registry file and run it with administrative privilege. Before you proceed, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). You can use the restore point to revert your PC to its previous state if something goes wrong when editing the registry entries.

 To disable background apps for the current user:

1. Press **Win + R** to open the **Run** dialog.
2. Type **notepad** and click **OK** to open the text editor app.  
![disable background apps windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor.jpg)
3. In the Notepad file, copy and paste the following content:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=dword:00000001  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=dword:00000000`
4. Next, press **Win + S** to open the **Save** dialog.
5. Here, name the file as **Disable\_Background\_Apps\_for\_current\_user.reg**. Then, click the **Save as type** drop-down and select **All Files.**  
![disable background apps windows 11 registry editor save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor-save.jpg)
6. Click the **Save** button to save the file.
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.
9. Close the Registry Editor and restart your PC to apply the changes.

 This should disable Microsoft Store apps from running in the background. To enable the background apps, modify the **LetAppsRunInBackground** value and set it to **0**.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can set the Let Windows apps run in the background policy to **Disabled** and apply the changes. However, when set to **Disabled** or **Not Configured**, individual employees in your organization can configure the apps to run in the background.

 On the contrary, setting this policy to **Force Deny** will prevent the app from running in the background, with no option for the employees to change the policy.

## Disabling Background Apps in Windows 11

 Windows allows you to configure background app permission for the Microsoft Store apps. You can disable these apps to conserve battery and avoid unnecessary data usage on a metered connection.

 That said, if you are struggling with slow system performance issues, disabling background apps may not be the solution. What you can do instead is reconfigure your OS, analyze your storage devices and look for hardware upgrades to boost system performance.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-highlight-heroes-iosandroid-covers-that-shine-bright/"><u>[New] Highlight Heroes IOS/Android Covers That Shine Bright</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-a-detailed-guide-to-streamlabs-obs/"><u>[Updated] A Detailed Guide to Streamlabs OBS</u></a></li>
<li><a href="https://win11.techidaily.com/7-symptoms-your-pc-may-need-a-new-beginning/"><u>7 Symptoms Your PC May Need A New Beginning</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ace-your-tweets-expert-reviews-of-the-finest-twitter-clients-on-the-market/"><u>Ace Your Tweets: Expert Reviews of the Finest Twitter Clients on the Market</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/android-as-a-w11-secondary-display-step-by-step-guide/"><u>Android as a W11 Secondary Display: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/android-extension-in-w11-workspace-enhancing-productivity/"><u>Android Extension in W11 Workspace: Enhancing Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-how-to-stop-apex-legends-freezes/"><u>Beat the Bug: How to Stop Apex Legends Freezes</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-through-strategic-task-management-in-windows-11/"><u>Boosting Productivity Through Strategic Task Management in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-find-and-apply-new-driver-software-for-your-toshiba-notebook-windows-guide/"><u>How to Find and Apply New Driver Software for Your Toshiba Notebook - Windows Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-tecno-pop-8-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Tecno Pop 8 Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719249883200-revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/simple-solutions-eliminate-that-unwanted-buzz-in-audio-equipment/"><u>Simple Solutions: Eliminate That Unwanted Buzz in Audio Equipment</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-anticipated-arrival-of-google-pixel-tablet-insight-into-the-specs-and-release-info/"><u>The Anticipated Arrival of Google Pixel Tablet - Insight Into the Specs and Release Info</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/reme-de-la-creme-leading-makeup-personalities-for-2024/"><u>The Crème De La Crème Leading Makeup Personalities for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-ups-battery-systems-your-essential-guide/"><u>Top-Rated UPS Battery Systems : Your Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719358387590-troubleshoot-frozen-shift-key-on-pc/"><u>Troubleshoot Frozen Shift Key on PC.</u></a></li>
</ul></div>

