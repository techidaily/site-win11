---
title: Eliminate Microsoft Edge From Windows 11
date: 2024-10-14T21:16:11.145Z
updated: 2024-10-15T18:53:17.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Microsoft Edge From Windows 11
excerpt: This Article Describes Eliminate Microsoft Edge From Windows 11
keywords: Remove Edge Browser Windows 11,Eradicate Microsoft Edge W11,Banish Edge to Win11,Oust Edge From W11 OS,Disable Microsoft Edge W11,Expel Edge in Windows 11,Exclude Edge on Win11
thumbnail: https://thmb.techidaily.com/b4bf5489aa58d7829034f75f3060e06c6a303902d9f1c209f852264705aa9ec8.jpg
---

## Eliminate Microsoft Edge From Windows 11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.

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
<li><a href="https://facebook-videos.techidaily.com/new-the-path-to-pinpointing-your-liked-content-on-facebook/"><u>[New] The Path to Pinpointing Your Liked Content on Facebook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-unleash-creativity-on-instagram-mastering-bulk-image-and-video-additions/"><u>[New] Unleash Creativity on Instagram Mastering Bulk Image & Video Additions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-easy-guide-to-taking-and-saving-twitters-gifs/"><u>[Updated] The Easy Guide to Taking and Saving Twitter's Gifs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-streamlining-gameplay-logs-for-social-media-sharing/"><u>2024 Approved Streamlining Gameplay Logs for Social Media Sharing</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-honor-90-gt-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Honor 90 GT</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-understanding-aids-and-assists/"><u>First Steps in Windows: Understanding Aids and Assists</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oppo-a59-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Oppo A59 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-precise-approach-to-blend-gopro-videos-with-surrounding-virtual-landscapes/"><u>In 2024, Precise Approach to Blend GoPro Videos with Surrounding Virtual Landscapes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-yt-shorts-soundtrack-hits-top-10-trending-sounds/"><u>In 2024, YT Shorts Soundtrack Hits Top 10 Trending Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/make-file-explorer-more-informative-diskspace-insight-in-menu/"><u>Make File Explorer More Informative: Diskspace Insight in Menu</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-time-management-on-your-computer-choose-from-these-top-5-dynamic-clock-screen-saver-tools/"><u>Maximize Time Management on Your Computer: Choose From These Top 5 Dynamic Clock Screen Saver Tools</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-local-policy-application-for-specific-users-in-win-1011/"><u>Navigating Local Policy Application for Specific Users in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/note-without-ink-optimal-windows-notepad-alternatives/"><u>Note Without Ink: Optimal Windows Notepad Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-deletion-made-simple-configuring-the-desktop-trash-on-windows-pcs-11/"><u>Permanent Deletion Made Simple: Configuring the Desktop Trash on Windows PCs (11)</u></a></li>
<li><a href="https://win11.techidaily.com/regain-sight-restart-gpu-in-windows-11/"><u>Regain Sight: Restart GPU in Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/solution-guide-successfully-repairing-your-ps4-wi-fi-connection-issues-june-2021-update/"><u>Solution Guide: Successfully Repairing Your PS4 Wi-Fi Connection Issues - June 2021 Update</u></a></li>
<li><a href="https://win11.techidaily.com/stop-vscode-from-shutting-down-suddenly-in-w11/"><u>Stop VSCode From Shutting Down Suddenly in W11</u></a></li>
</ul></div>

