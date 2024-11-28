---
title: Solutions to Stop Repeated Edge Toolbar
date: 2024-11-27T02:31:36.676Z
updated: 2024-11-27T20:34:44.932Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions to Stop Repeated Edge Toolbar
excerpt: This Article Describes Solutions to Stop Repeated Edge Toolbar
keywords: Eliminate Adware Bars -,Remove Toolbar Irritation -,Freeze Pop-Up Blockers -,Stop UX Toolbar Appearance -,Eradicate Edge Toolbar Fixes -,Clear Browser Extensions Ads -,Prevent Toolbar Redirects -
thumbnail: https://thmb.techidaily.com/9c704c9ab8ca818eb8c547f35c543ea321e006214fab450eba00af5408d5f618.jpg
---

## Solutions to Stop Repeated Edge Toolbar

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-embrace-the-season-ideal-winter-backgrounds-for-yt/"><u>[New] 2024 Approved Embrace the Season Ideal Winter Backgrounds for YT</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-introduction-to-moving-visual-content/"><u>[New] Introduction to Moving Visual Content</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-revenue-protection/"><u>[Updated] 2024 Approved Revenue Protection</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-fundamental-concepts-of-cyber-narratives-for-2024/"><u>[Updated] Fundamental Concepts of Cyber Narratives for 2024</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-transform-youtube-live-with-these-must-know-secrets/"><u>2024 Approved Transform YouTube Live with These Must-Know Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/6-simple-steps-to-successfully-install-a-pc-card-on-windows-a-comprehensive-guide/"><u>6 Simple Steps to Successfully Install a PC Card on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-on-how-to-change-flv-videos-to-mp4-for-free-without-restrictions/"><u>A Step-by-Step Guide on How to Change FLV Videos to MP4 for Free without Restrictions</u></a></li>
<li><a href="https://win-amazing.techidaily.com/asus-bluetooth-drivers-quick-downloads-and-easy-update-tutorials/"><u>ASUS Bluetooth Drivers - Quick Downloads & Easy Update Tutorials</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ng-edge-techniques-for-incorporating-soundtracks-in-youtube-creations-for-2024/"><u>Cutting-Edge Techniques for Incorporating Soundtracks in YouTube Creations for 2024</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/deciphering-and-deleting-fake-apple-safety-notifications-with-expert-tips-from-malwarefox/"><u>Deciphering and Deleting Fake Apple Safety Notifications with Expert Tips From MalwareFox</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-best-15-non-windows-movie-editing-tools/"><u>Discover the Best 15 Non-Windows Movie Editing Tools</u></a></li>
<li><a href="https://win11.techidaily.com/download-the-latest-update-of-flash-video-converter-factory-pro-no-cost-includes-a-risk-free-test-drive-with-secure-payment-option/"><u>Download the Latest Update of Flash Video Converter Factory Pro - No Cost, Includes a Risk-Free Test Drive with Secure Payment Option</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-to-upgrading-from-hevc-to-av1-video-codec-without-hitches/"><u>Easy Guide to Upgrading From HEVC to AV1 Video Codec Without Hitches</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-converting-videos-tofrom-quicktime-format-on-windows-and-mac-devices/"><u>Easy Guide: Converting Videos To/From QuickTime Format on Windows & Mac Devices</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-methods-for-iphone-users-to-enjoy-ogg-files/"><u>Effortless Methods for iPhone Users to Enjoy OGG Files</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-transformation-mastering-the-switch-from-wmv-to-webm-files/"><u>Effortless Transformation: Mastering the Switch From WMV to WebM Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unable-to-connect-to-nvidia-geforce-experience-error-in-windows-10-and-11/"><u>How to Fix the “Unable to Connect to NVIDIA” GeForce Experience Error in Windows 10 & 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-how-to-properly-credit-chatgpt-usage/"><u>Step-by-Step Instructions: How to Properly Credit ChatGPT Usage</u></a></li>
<li><a href="https://win11.techidaily.com/44ox44ot44gm5o6o5awo44gz44kl5pyj5paz44gu6auy5ocn6io95yuv55s744ko44oz44kz44o844oa44k944ov44oi44km44kn44ki44oq44k544oi/"><u>プロが推奨する有料の高性能動画エンコーダソフトウェアリスト</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    