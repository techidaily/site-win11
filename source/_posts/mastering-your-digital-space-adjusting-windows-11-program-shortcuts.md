---
title: "Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts"
date: 2024-06-25T11:28:01.615Z
updated: 2024-06-26T11:28:01.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts"
excerpt: "This Article Describes Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts"
keywords: Digital Mastery Tips,Win11 Shortcut Config,Optimize WinShortcuts,Space Organizing Guide,Windows Program Efficiency,Shortcut Customization Win11,Adjusting Win11 Icons
thumbnail: https://thmb.techidaily.com/08702778e13a63a51dde09a4b23ab862a68808a42d3ab8c5759ae25bd6bbada4.jpg
---

## Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts

 If you are not satisfied with any of the default apps assigned by Windows, you can change them to your preferred options. This process was quite simple in Windows 10, but Microsoft has made it a bit complicated for Windows 11 users.

 In this guide, we will discuss the method of changing the default apps in Windows 11 in detail. We have also discussed several troubleshooting methods later in this guide that you can try if the default apps fail to change.

## How to Change the Default Apps in Windows 11

[Changing the default apps in Windows 10](https://www.makeuseof.com/tag/change-default-settings-windows-10/) is quite simple. You can access the**Default Apps** section of the Settings app and replace the current default app with your preferred option.

 In Windows 11, this method is slightly different. You must set a program default for all the registered file types and links relevant to it since there isn’t a**Set default for all** option available.

 Below, we have listed different ways of changing the default apps in Windows 11:

### 1\. Choose the Open With Option

 The easiest method of changing the default apps option is by using the Open with option in the context menu for files.

Here is how you can do that:

1. Right-click on the targeted file. For instance, an image file that you want to open with an app other than the default Photos app.
2. Choose**Open with** \>**Choose another app** from the context menu.  
![Choose another app to open the targeted file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-open-with-choose-another-app.jpg)
3. Now, in the following dialog, choose the app you want to set as the default option. If you cannot find the targeted app in the list, choose**Look for another app on this PC** and then select the app.
4. Click on**Always use this app to open files** and click**OK** . This should set the selected app as the default preference.  
![Set a default app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/set-the-default-app.jpg)

### 2\. Use the Settings App

 The next thing that you can do is access the Default Apps option and choose the preferred app from there.

Follow these steps to proceed:

1. Press the Win + I keys together to open the Windows Settings.
2. Choose**Apps** from the left pane.
3. Click on**Default apps** .  
![Click on the Default apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-settings-apps-default-apps.jpg)
4. Next, choose the app that you want to set as default. You should now see all the file types and link types the app is registered with.
5. If you want to choose a program as the default for all its registered file types and links, you'd need to click each type and choose the desired application in the following dialog.  
![Pick a default file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pick-a-default-file-type.jpg)

 This should set the app as the default option for the selected file and link types. However, if you[reset Windows 11 to its default state](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) ever, you will lose all these settings.

### 3\. Use File Properties

 You can also change the file properties of the targeted file to open it with a new default app.

To proceed, follow these steps:

1. Right-click on the targeted file and choose**Properties** from the context menu.  
![Access the properties of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties.jpg)
2. Head over to the General tab and click on the**Change** button associated with**Opens with** .  
![Click on the Change button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties-general-change.jpg)
3. Now, choose the desired app and click**OK** .

## What to Do If You Cannot Change the Default Apps in Windows 11?

 If you are unable to change the default apps in Windows 11 despite trying the different methods mentioned above, it could be due to the following reasons:

* The app that you are trying to set as the default option is dealing with a corruption error or is not installed correctly.
* A group policy setting in the system is preventing you from changing these configurations.
* You do not have sufficient permissions to make changes of this level in the system.
* The app is not compatible with your system.

 In this case,[ensure that your user account has administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/) and that the app you are trying to set as default is compatible with the system. Here are some more steps you can follow to resolve the problem.

### 1\. Update Windows 11

 If you're running an outdated version of Windows, you may be experiencing problems due to incompatibility issues. Windows 11 needs to be updated to the latest version in this case.

Here is how you can do that:

1. Press the Win + I keys together to open Windows Settings.
2. Choose**Windows Update** from the left pane.
3. Now, click on the**Check for updates** button on the right side.
4. Install all the pending updates one by one by clicking on the**Download & install** button and then restart your PC.  
![Click on the Download & install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-windows-update-download-and-install.jpg)

 Once this is done, follow one of the steps above to change the default app.

### 2\. Reset the Targeted App

 If the problem is within the app that you are trying to change, you can reset the program to solve the problem.

Follow these steps to proceed:

1. Press Win + S keys together to open Windows Search.
2. Type Powershell and choose**Run as administrator** .
3. Click**Yes** in the User Account Control prompt.
4. In the Powershell window, type the command mentioned below and click Enter. Replace packagename with the name package name of the app that you want to set as default.  
Get-AppxPackage packagename -AllUsers | Reset-AppxPackage
5. For instance, if you want to change the Photos app, execute the following command:  
Get-AppxPackage Microsoft.Windows.Photos -AllUsers | Reset-AppxPackage  
![Reset the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-appxpackage-packagename.jpg)
6. Once the command is executed, check if you can change the default app.

### 3\. Reinstall the App

 Lastly, you can try reinstalling the app that you want to set as default. This will eliminate any corruption errors are bugs within the app that are preventing you from setting it as the default option.

Here is how you can proceed:

1. Press the Win + R keys together to open a Run dialog.
2. Type control in Run and click Enter.
3. In the following window, navigate to**Uninstall a program** .  
![Uninstall a program](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/uninstall-a-program.jpg)
4. Locate the targeted app and right-click on it.
5. Choose**Uninstall** and follow the on-screen instructions to proceed.  
![Uninstall the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-uninstall-program.jpg)

 Once the uninstallation is completed, restart the computer and reinstall the app. Hopefully, this time, you will be able to set it as the default option without any problems.

## Make Your Preferred Apps Default

 The apps set as the default options on Windows are quite user-friendly and efficient. It is possible, however, to change the default preference to a better option if you have found one that suits your system better.

 With the methods listed above, you should be able to change the default apps on your Windows 11 system in no time. Nevertheless, keep in mind that in the event that Windows is reinstalled or reset, these options will return to the default configuration.

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
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-0x0000004e-on-windows-xp7/"><u>Decoding and Fixing 0X0000004E on Windows XP/7</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-microphone-use-a-deep-dive-into-win-11/"><u>Conquering Microphone Use: A Deep Dive Into Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/opera-stuck-swift-solutions-for-a-smooth-windows-patch/"><u>Opera Stuck? Swift Solutions for a Smooth Windows Patch</u></a></li>
<li><a href="https://win11.techidaily.com/the-swift-way-to-access-control-panel/"><u>The Swift Way to Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-comic-archives-with-windows-11-interface/"><u>Exploring Comic Archives with Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-overcoming-forbidden-errors/"><u>Mastering the Art of Overcoming Forbidden Errors</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-enforced-driver-checks-for-easier-updates/"><u>Skirting Enforced Driver Checks for Easier Updates</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-8-proven-techniques-to-amplify-content-for-2024/"><u>Top 8 Proven Techniques to Amplify Content for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-moonlit-mastery-tips-for-perfecting-nighttime-photos/"><u>2024 Approved  Moonlit Mastery  Tips for Perfecting Nighttime Photos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-quieting-the-cinematic-chaos-techniques-for-audio-trimming-in-imovie-videos/"><u>Updated Quieting the Cinematic Chaos Techniques for Audio Trimming in iMovie Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-photo-hdr-techniques-in-adobe-ps/"><u>[Updated] Mastering Photo HDR Techniques in Adobe PS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-maximize-watch-time-minimize-leaving-6-key-tactics-to-retain-more-audience/"><u>[New] Maximize Watch Time, Minimize Leaving  6 Key Tactics to Retain More Audience</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-samsung-galaxy-m34-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Samsung Galaxy M34 Phone Pattern Lock</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-effortless-access-download-tactics-for-live-social-feeds/"><u>[New] In 2024, Effortless Access  Download Tactics for Live Social Feeds</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-v27e-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo V27e Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-leveraging-the-power-of-creative-commons-rights/"><u>In 2024, Leveraging the Power of Creative Commons Rights</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-zte-nubia-z60-ultra-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track ZTE Nubia Z60 Ultra without Them Knowing | Dr.fone</u></a></li>
</ul></div>
