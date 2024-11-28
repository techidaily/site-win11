---
title: Containing Insider Versions to Trusted Users
date: 2024-11-27T04:15:44.747Z
updated: 2024-11-27T17:27:40.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Containing Insider Versions to Trusted Users
excerpt: This Article Describes Containing Insider Versions to Trusted Users
keywords: Trustworthy Access,Insider Controls,Secure User Grp,Privacy-Limited View,Exclusive Data Hand,Trusted Content Share,Authorized Version Use
thumbnail: https://thmb.techidaily.com/a2e90f9c59ddfc76d24d52ddf99c58f1453c310ceab2f51cc25530b47d90892e.jpg
---

## Containing Insider Versions to Trusted Users

 Microsoft rolls out Insider builds to Windows Insiders before releasing them to the public. The preview is only intended for testing and feedback, and it provides access to the latest features & changes that will be included in the next release.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

## How to Stop Users From Getting Insider Preview Builds in Windows 11

 If you share your computer with others and don't want them to get the newer build, you need to prevent them from getting Insider Preview Builds in Windows 11\. There are basically three ways to achieve this, using System Settings, Group Policy Editor, or Registry Editor. For a detailed explanation of each, please see the following.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Use the System Settings

 If you don't want someone to access the Insider builds, you can disable it from the Windows System settings. This option is hidden in the Windows Update settings, so you will need to navigate through the menus to find it. Here's how to do it:

1. Press **Win + I** to open System settings. You can also open it from the Start menu.
2. Once you're in System Settings, go to **Windows Update**.
3. Then navigate to **Windows Insider Programme** \> **Stop getting preview builds**.  
![Stop Getting Preview Builds in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/stop-getting-preview-builds-in-windows.jpg)
4. Now toggle the **Unenroll this device when the next version of Windows releases** switch to disable it.

 This will prevent the device from downloading further Insider builds even if someone initiates it manually.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use the Local Group Policy Editor

 Windows 11's Local Group Policy Editor provides you with a wide range of options for configuring system settings. In fact, you can use this tool to disable access to preview builds. However, you will not have access to the Local Group Policy editor if you use Windows Home Edition.

 For this to work, you must first [activate the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems too complicated, you may skip it and move on to the next solution.

 Here are the steps you need to take to prevent other users from getting Insider Preview Builds

1. Press the **Win + R** keys to open the Run dialog box.
2. Type "gpedit.msc" into the text field, and then click the **OK** button to launch the Local Group Policy Editor.
3. In the Local Group Policy Editor, go to the following locations:  
`Computer Configuration > Administrative Templates > Windows Components > Data Collection and Preview Builds`
4. From the left menu, select the **Data Collection and Preview Builds** folder.
5. Then double-click on the **Toggle user control over Insider builds** on the right.  
![Block Insider Preview Builds Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Group-Policy.jpg)
6. Select the **Disabled** radio button in the dialog box that appears.  
![Toggle user control over Insider builds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Toggle-user-control-over-Insider-builds.jpg)
7. After you've made your changes, click **Apply** and **OK** to save them

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you have completed the steps above, you will need to restart your computer to ensure the changes are applied. After doing that, you'll no longer be able to install or receive Insider builds. If you ever need to give users access to Insider builds on your computer, open the Local Group Policy Editor again.

 Then, set "Toggle user control over Insider builds" either to the **Not Configured** or **Enabled** option. When you have finished making the changes, click Apply > OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Tweak the Registry Editor

 Tweaking the Registry Editor is another method you can use to prevent users from getting Insider Preview Builds in Windows 11\. The process is easy and only requires a few steps. It is important, however, not to [accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) while doing so.

 If you edit the wrong keys, you may seriously damage your device. For this reason, you should always [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to it.

 To prevent other users from getting Insider Preview Builds, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. In the search field, type "regedit" and click **OK**.
3. You will see a UAC window on your screen. Click **Yes** to confirm your action.
4. When you're in the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\PreviewBuilds`
5. If you don't find the PreviewBuilds key there, you will have to create it. In order to do this, right-click on the **Windows** key and select **New** \> **Key**.
6. Specify **PreviewBuilds** as the file name and hit Enter to save it.
7. In the right pane, right-click on an empty area and select **New > DWORD (32-bit) Value**.
8. This DWORD key should have the name **AllowBuildPreview**.
9. Click twice on the newly created DWORD key to open a pop-up menu.  
![Block Insider Preview Builds Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Registry-Editor.jpg)
10. Set the value data to **0** and choose the Hexadecimal base.
11. Click **OK** to save the changes.

 When you're done making these changes, restart your computer. If you ever need to roll back the changes, you can do so whenever you like.

 To do this, right-click the AllowBuildPreview key in the Registry Editor and choose **Modify**. You then need to set the Value data to **1** and hit **OK** to apply the changes.

## Do I Need to Enroll in the Windows Insider Program?

 Windows Insider Program is a feature that allows you to try out new builds and features of Windows OS before they become publicly available. It is a great way to get early access to new features and provide feedback to Microsoft. The program is free to join, and you can opt out at any time.

 If you are considering joining the Windows Insider Program, here are a few things to keep in mind:

1. First, you should be aware that by joining the program, you will be sharing information with Microsoft about your device and how you use it. This information will help Microsoft improve Windows 10 for all users.
2. The second thing you should know is how beta testing works. When you join the Windows Insider Program, you can test out the new features and give feedback to Microsoft. It is important to note that you will be using pre-release software that could be unstable. Some of these builds may have bugs or other issues that could cause problems for your computer.

## Why Would You Want to Prevent Access to Insider Builds?

 There are a few reasons people may want to prevent access to insider builds:

1. Insider builds are usually released before the public version, which means there could be more bugs and glitches.
2. It often contains new features that aren't ready for everyone to use, and some prefer the stability of the older versions.
3. Last but not least, insider builds are often released more frequently. As a result, they are harder to maintain, and some people would prefer a slower update rate for public builds.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## The Windows Insider Preview Build, Now Disabled

 If you want to prevent others from downloading and installing Insider Preview Builds on your Windows 11, you can turn off the Insider Preview feature on your computer. There are two ways to do this, either through the Group Policy Editor or through the Registry Editor. You can learn more about this in the article.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-discovering-the-top-10-invisible-story-lovers-for-2024/"><u>[New] Discovering the Top 10 Invisible Story Lovers for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-quick-start-with-screencastify-video-recording/"><u>[New] Quick Start with Screencastify Video Recording</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tapping-into-igtvs-potential-a-hashtag-guide-to-growth/"><u>[New] Tapping Into IGTV's Potential A Hashtag Guide to Growth</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-ig-tunes-crafting-perfect-music-posts-for-2024/"><u>[Updated] IG Tunes Crafting Perfect Music Posts for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mac-dvd/"><u>「Mac環境向け: DVDの完全なクローン作成方法を初心者にもわかりやすく解き明かす」</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-iphone-13-mini-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock iPhone 13 mini After Forgetting the Passcode?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-geforce-experience-error-code-0x0001-in-windows-11-and-11/"><u>How to Fix the GeForce Experience Error Code 0X0001 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-restart-and-rectify-non-functional-obs-on-pc/"><u>How to Restart and Rectify Non-Functional OBS on PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-4-ways-to-mirror-apple-iphone-6s-plus-to-laptop-via-usb-or-wi-fi-drfone-by-drfone-ios/"><u>In 2024, 4 Ways to Mirror Apple iPhone 6s Plus to Laptop via USB or Wi-Fi | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Spoofing Life360 How to Do it on Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-mouse-navigation-in-powertoys-tools/"><u>Mastering Mouse Navigation in PowerToys Tools</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-disabled-state-on-windows-11-fix-for-error-code-22/"><u>Reversing the Disabled State on Windows 11 - Fix for Error Code 22</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-file-organization-with-multiple-windows-11-folders/"><u>Streamline File Organization with Multiple Windows 11 Folders</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-your-iphone-torch-a-guide-with-12-steps/"><u>Troubleshoot Your iPhone Torch: A Guide with 12 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/turn-voice-into-written-words-immediately-whispers-secret/"><u>Turn Voice Into Written Words Immediately - Whisper's Secret</u></a></li>
</ul></div>

