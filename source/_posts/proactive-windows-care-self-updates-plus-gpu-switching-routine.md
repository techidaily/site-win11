---
title: "Proactive Windows Care: Self-Updates + GPU Switching Routine"
date: 2024-12-26T21:25:41.211Z
updated: 2024-12-28T01:00:42.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Proactive Windows Care: Self-Updates + GPU Switching Routine"
excerpt: "This Article Describes Proactive Windows Care: Self-Updates + GPU Switching Routine"
keywords: Proactive PC Updates,Windows Update Guide,Regular System Checks,Dynamic GPU Settings,Optimized PC Health,Efficient OS Maintenance,Routine Hardware Upgrade
thumbnail: https://thmb.techidaily.com/f4b94a6052a83b6c87620891bae2ef1d10a06ae6e718f7d201b09964291e2b88.jpg
---

## Proactive Windows Care: Self-Updates + GPU Switching Routine

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-capture-and-share-the-essentials-for-posting-video-in-every-direction-on-fb/"><u>[New] In 2024, Capture and Share The Essentials for Posting Video in Every Direction on FB</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-android-gamings-new-era-with-the-rise-of-kinemaster-app/"><u>[Updated] 2024 Approved Android Gaming's New Era with the Rise of KineMaster App</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-joke-jigsaw-puzzles-build-with-kapwingenasian-memes/"><u>[Updated] Joke Jigsaw Puzzles Build with Kapwing’enasian Memes</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-spark-paves-way-but-will-mavic-air-top-the-gaming-scene-in-2024/"><u>[Updated] Spark Paves Way, But Will Mavic Air Top the Gaming Scene, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conceal-or-show-taskbars-date-and-clock-in-win-11/"><u>Conceal or Show Taskbar's Date & Clock in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-the-oled-world-asus-s15s-unique-appeal/"><u>Diving Into the OLED World: ASUS S15's Unique Appeal</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-infinix-smart-8-pro-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Infinix Smart 8 Pro Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-action-plan-reactivating-your-menu-items/"><u>Immediate Action Plan: Reactivating Your Menu Items</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-art-of-using-multiframe-in-browsing-edge-edition/"><u>In 2024, Mastering the Art of Using Multiframe in Browsing - Edge Edition</u></a></li>
<li><a href="https://fox-direct.techidaily.com/meditative-harmony-the-top-10-legally-accessible-chants-and-tracks-for-2024/"><u>Meditative Harmony – The Top 10 Legally Accessible Chants & Tracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-win11-for-a-smoother-jump-into-programs-on-startup/"><u>Optimizing Win11 for a Smoother Jump Into Programs on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-11-tools-for-unmatched-video-scripting-and-edits/"><u>Prime Windows 11 Tools for Unmatched Video Scripting & Edits</u></a></li>
<li><a href="https://win-ratings.techidaily.com/resolve-your-laptops-disk-read-error-quickly-proven-5-methods-and-insider-advice/"><u>Resolve Your Laptop's Disk Read Error Quickly - Proven 5 Methods & Insider Advice</u></a></li>
<li><a href="https://facebook.techidaily.com/restore-past-connections-after-facebook-ban/"><u>Restore Past Connections After Facebook Ban</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-files-using-powerrename-in-powertoys/"><u>Streamline Your Files: Using PowerRename in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-exe-opening-conundrum-with-ease/"><u>Tackling Windows EXE Opening Conundrum with Ease</u></a></li>
</ul></div>

