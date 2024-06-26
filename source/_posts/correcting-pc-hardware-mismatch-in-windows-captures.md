---
title: Correcting PC Hardware Mismatch in Windows Captures
date: 2024-06-25T11:39:39.836Z
updated: 2024-06-26T11:39:39.836Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting PC Hardware Mismatch in Windows Captures
excerpt: This Article Describes Correcting PC Hardware Mismatch in Windows Captures
keywords: PC Hardware Fixes,Windows Errors,Data Recovery Windows,System Compatibility Check,Hardware Adjustment Guide,Troubleshoot PC Issues,Capture Correction Steps
thumbnail: https://thmb.techidaily.com/7d954d5ef5beb31b578dcda4509d16e23f0ef0d1b79a76b01e4834ddb01328ea.jpg
---

## Correcting PC Hardware Mismatch in Windows Captures

 Many users utilize the Xbox Game Bar app pre-installed with Windows for recording game clips. However, some users can’t record anything with the Game Bar because of an error that says, “sorry, your PC doesn't meet the hardware requirements for captures.” That error message can appear within Settings or when users select to record.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

## Enable Game DVR With Game DVR Config

 Game DVR Config is third-party software with which some users have resolved the “PC doesn't meet the hardware requirements for captures” error. That software includes settings users can select to enable Game DVR along with audio and microphone capture.

 Here is how you can enable Game DVR with that software:

1. Open the [Game DVR Config](https://github.com/FunkyFr3sh/GameDVR%5FConfig/releases) page.
2. Click the **GameDVR\_Config.exe** download link.
3. Bring up Windows Explorer and the Downloads folder or other directory containing the Game DVR file.
4. Double-click the **GameDVR\_Config** file.
5. Select the **Enable Game DVR (Win+G)** checkbox.  
![The Game DVR Config software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/game-dvr-config.jpg)
6. Click the **Force software MFT** checkbox to select that setting.
7. Exit Game DVR Config and [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/).
8. Look for the Broadcast DVR server on the **Processes** tab. Right-click Broadcast DVR Server and select **End task** if you can find that process.

## Edit the Control Registry Key

 Editing the Control registry key is a fix that’s worked for some users. Try editing that key like this:

1. To activate Run, simultaneously press **Win** \+ **R**.
2. Type **regedit** within the Run command box and press the **Enter** key.
3. Clear the text in the address bar and input this registry key location there:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control`
4. If there isn’t a **PortableOperatingSystem** DWORD already, right-click on the **Control** key and select **New** and **DWORD**. Input **PortableOperatingSystem** within the new key’s text box.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options.jpg)
5. Double-click on the **PortableOperatingSystem** DWORD in the Control key.
6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.
8. Then close out of the Registry Editor app and restart Windows.

## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
5. Click **Enabled** if that policy is disabled.
6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

## Erase Data in the GameDVR Registry Key

 Corrupted GameDVR entries within the registry can cause the “PC doesn't meet the hardware requirements for captures” error. You can fix that by deleting DWORDs and strings in the GameDVR registry key, which will automatically regenerate. However, we still recommend users back up the registry before applying this potential solution.

 You can erase data from the GameDVR registry key as follows:

1. Open Registry Editor with Run, as covered in the first couple of steps of resolution two.
2. Go to this GameDVR registry key location:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\GameDVR`
3. Select all DWORDs and strings within the GameDVR key by holding the **Ctrl** key and clicking on them.
4. Then right-click and select **Delete** \> **Yes**.  
![the-delete-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-delete-option.jpg)
5. Click the Start menu’s Power button and select **Restart**.

## Get Recording Again With the Xbox Game Bar

 The potential solutions covered here are widely confirmed to resolve the “PC doesn't meet the hardware requirements for captures” by users who’ve needed to fix that issue. So, it’s most likely applying the potential fixes above will resolve that Game Bar recording issue on your Windows laptop or desktop. Then you can record video while gaming with the Game Bar’s recording feature again.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/restoring-the-antique-ribbon-interface-of-explorer/"><u>Restoring the Antique Ribbon Interface of Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-update-experience-with-easy-fixes-here/"><u>Seamless Windows Update Experience With Easy Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-windows-server-settings/"><u>Unlocking Secure Windows Server Settings</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-no-sound-on-connected-devices-windows-edition/"><u>Clearing Up No Sound on Connected Devices, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/dispel-limitations-escalating-internet-speed-past-100mbps-in-windows/"><u>Dispel Limitations: Escalating Internet Speed Past 100Mbps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-invisible-icons-menu-on-modern-windows-11/"><u>Accessing Invisible Icons Menu on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-non-interactive-components-on-windows-11/"><u>How to Resolve Non-Interactive Components on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-audio-experience-budget-friendly-asmr-mics-reviewed/"><u>[New] Ultimate Audio Experience  Budget-Friendly ASMR Mics Reviewed</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-uploading-movies-instagram-guide/"><u>2024 Approved  Uploading Movies  Instagram Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-how-to-use-periscope-cost-benefits-and-signup-guide/"><u>2024 Approved  How to Use Periscope  Cost, Benefits & Signup Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-audio-overhaul-methods-for-content-creators-online/"><u>[Updated] In 2024, Audio Overhaul Methods for Content Creators Online</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-honor-100-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-iphone-14-pro-max-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking iPhone 14 Pro Max i Do? Get Answers here</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-downloadfacebookcontent-the-premiere-addons-and-browser-plugins-for-facebook-videos-firefox-edition/"><u>[Updated] 2024 Approved  DownloadFacebookContent! - The Premiere Addons and Browser Plugins for Facebook Videos, FireFox Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-which-screen-recorder-delivers-more-insights-into-bandicam-vs-camtasia/"><u>[Updated] In 2024, Which Screen Recorder Delivers More? Insights Into Bandicam vs Camtasia</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-kinemasters-features-and-comparing-to-leading-online-games/"><u>In 2024, Navigating KineMaster's Features and Comparing to Leading Online Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-static-to-spinning-mastering-photo-effects-in-illustrator/"><u>2024 Approved  From Static to Spinning  Mastering Photo Effects in Illustrator</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>