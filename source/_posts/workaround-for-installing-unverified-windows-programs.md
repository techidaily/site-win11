---
title: Workaround for Installing Unverified Windows Programs
date: 2024-12-22T07:05:39.697Z
updated: 2024-12-27T16:52:21.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Workaround for Installing Unverified Windows Programs
excerpt: This Article Describes Workaround for Installing Unverified Windows Programs
keywords: WinUSBInstallation,UnblockedWindowsApps,BypassWindowsVerification,ExecuteUnsignedWinPrograms,InstallUnverifiedWindows,WorkaroundForWinInstaller,SideloadWindowsSoftware
thumbnail: https://thmb.techidaily.com/7893aa47861abae86c2201349f48204a58f66be5a4db0cfc4bb799b623cb07e4.jpg
---

## Workaround for Installing Unverified Windows Programs

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out[how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.

4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  

![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-audience-connection-mastering-the-art-of-viewpoint-based-youtube-reaction-vids-2-pov-method/"><u>[New] 2024 Approved Audience Connection – Mastering the Art of Viewpoint-Based YouTube Reaction Vids (2 POV Method)</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-enhanced-audio-playback-acceleration-tools-list/"><u>[New] In 2024, Enhanced Audio Playback Acceleration Tools List</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-evaluating-video-editing-tools-bandicam-vs-camtasia-for-2024/"><u>[Updated] Evaluating Video Editing Tools Bandicam vs Camtasia for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-streamline-your-income-youtubes-new-rules/"><u>[Updated] In 2024, Streamline Your Income YouTube's New Rules</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-iphone-guide-to-slow-motion-magic-for-2024/"><u>[Updated] The Ultimate iPhone Guide to Slow-Motion Magic for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/44cm5yuv55s75pku5b2x5oqa6kgt77ya44gv44gplus44gw44gplus44gq44ki44oz44kw44or44go5b6u6kq5pw05pa55rov44gu44ks44kk44oj44cn/"><u>「動画撮影技術：さまざまなアングルと微調整方法のガイド」</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-best-in-class-number-8-online-image-weaver/"><u>2024 Approved Best in Class Number 8 Online Image Weaver</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-privilege-access-denial-error-error-0x80070522-on-modern-windows-pcs/"><u>Fixing Privilege Access Denial Error (Error 0X80070522) on Modern Windows PCs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-itel-p55plus-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Itel P55+ Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/master-control-unscheduling-gpgpu-on-windows-platforms/"><u>Master Control: Unscheduling GPGPU on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-attributes-on-windows-a-practical-guide/"><u>Mastering File Attributes on Windows: A Practical Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-safe-mode-in-6-steps/"><u>Navigate to Windows 11 Safe Mode in 6 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/nvidias-geforce-error-on-windows-heres-the-fix/"><u>Nvidia's GeForce Error on Windows? Here’s the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/premium-windows-emulators-for-nintendos-switch-library/"><u>Premium Windows Emulators for Nintendo's Switch Library</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/retrieve-forgotten-passwords-from-your-mac-with-simple-tricks/"><u>Retrieve Forgotten Passwords From Your Mac with Simple Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-tasks-using-ifttt-for-microsoft-to-do/"><u>Simplifying Tasks: Using IFTTT for Microsoft To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-update-9-tactics-against-steady-verify-failures/"><u>Unlock Windows Update: 9 Tactics Against Steady Verify Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-fixing-missing-updates-on-windows-os-code-0x80070003/"><u>Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)</u></a></li>
<li><a href="https://win-docs.techidaily.com/mpg-swf-movavi/"><u>영구성 MPG SWF 파일을 비용 없이 웹 문제를 위해 전환하세요 - Movavi</u></a></li>
</ul></div>

