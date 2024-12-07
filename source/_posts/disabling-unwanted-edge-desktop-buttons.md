---
title: Disabling Unwanted Edge Desktop Buttons
date: 2024-12-04T16:48:39.397Z
updated: 2024-12-07T11:41:34.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Unwanted Edge Desktop Buttons
excerpt: This Article Describes Disabling Unwanted Edge Desktop Buttons
keywords: Disable Desktop Toolbar,Remove Unwanted Edges,Eliminate Edge Buttons,Desktop Button Hide,Stop Edge Panels,Clear Edge Menu,Desktop Clutter Free
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Disabling Unwanted Edge Desktop Buttons

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-elevate-your-social-media-presence-top-25-hashtags-for-instagram-mastery/"><u>[Updated] In 2024, Elevate Your Social Media Presence Top 25 Hashtags for Instagram Mastery</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/broadcasting-breakthroughs-4-innovations-for-livetv-and-fb-for-2024/"><u>Broadcasting Breakthroughs 4 Innovations for LiveTV and FB for 2024</u></a></li>
<li><a href="https://fox-sys.techidaily.com/comment-restaurer-vos-fichiers-a-partir-dune-sauvegarde-sur-windows-11-une-methode-simple-et-efficace/"><u>Comment Restaurer Vos Fichiers À Partir D'une Sauvegarde Sur Windows 11: Une Méthode Simple Et Efficace</u></a></li>
<li><a href="https://win11.techidaily.com/connect-to-common-windows-shared-docs/"><u>Connect to Common Windows Shared Docs</u></a></li>
<li><a href="https://win11.techidaily.com/decluttering-made-simple-personalize-your-w11-desktop/"><u>Decluttering Made Simple: Personalize Your W11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/fortifying-the-fortress-stabilizing-windows-dwarf-gameplay/"><u>Fortifying the Fortress: Stabilizing Windows-Dwarf Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-the-lock-screen-on-windows-11/"><u>How to Disable the Lock Screen on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-you-need-to-format-the-disk-in-drive-before-you-can-use-it-error-on-windows/"><u>How to Fix the “You Need to Format the Disk in Drive Before You Can Use It” Error on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-a24-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Samsung Galaxy A24 Phone Without Password?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-phantom-v-flip-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Tecno Phantom V Flip Phone without Google Account?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-smooth-out-the-shakes-8-free-online-video-stabilizers-to-try/"><u>New 2024 Approved Smooth Out the Shakes 8 Free Online Video Stabilizers to Try</u></a></li>
<li><a href="https://win-help.techidaily.com/recovering-lost-zip-compressed-files-for-free-on-windows-10-and-11-platforms/"><u>Recovering Lost ZIP Compressed Files for Free on Windows 10 and 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-internal-failure-for-win10plus-networking/"><u>Resolving Internal Failure for Win10+ Networking</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-by-step-download-and-personalize-whatsapp-ringtones-on-mobile/"><u>Step-by-Step Download & Personalize WhatsApp Ringtones on Mobile</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-infinix-hot-40-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Infinix Hot 40 Screen | Dr.fone</u></a></li>
</ul></div>

