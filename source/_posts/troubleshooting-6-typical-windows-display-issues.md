---
title: Troubleshooting 6 Typical Windows Display Issues
date: 2024-06-25T11:31:43.232Z
updated: 2024-06-26T11:31:43.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting 6 Typical Windows Display Issues
excerpt: This Article Describes Troubleshooting 6 Typical Windows Display Issues
keywords: Fix Windows Displays,Display Errors Resolved,Troubleshoot Screen Problems,Windows Graphics Fixes,Improve Display Performance,Correcting Windows Issues,Diagnose Display Glitches
thumbnail: https://thmb.techidaily.com/5e5b9ce0dc07e3f4c01f086c082ef2c0bbdb4ea2b6b782415a93738cfbe92996.jpg
---

## Troubleshooting 6 Typical Windows Display Issues

 You could spend thousands on a monitor, but if you've managed to mess up with display settings in Windows, or within an app or game, it will ruin your viewing experience. In some cases, it could be the driver or a hardware component giving you trouble.

 Regardless of the reason for your viewing perils, we're going to help troubleshoot the display issue, so you can go back to enjoying high-quality viewing. We'll talk about the problems that can lead to a screen resolution issue and how you can fix them.

## 1\. Incorrect Resolution Settings

 Resolution can often change by itself on Windows because of a corrupted graphics driver, a new Windows update, or a conflicting third-party app. If this is the case with your display, you can easily fix it by changing the resolution settings.

 Press **Win + I** to launch Settings and navigate to **System > Display**. Click on the drop-down menu next to **Display Resolution** and select the recommended option from the list.

![changing resolution from settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/settings-resolution.jpg)

## 2\. Incorrect App-Specific Settings

 A third-party app may override the screen resolution you set on Windows and apply a resolution it requires to properly run and display its content. The most common example is games. Games typically have an option to change the resolution within their settings, and that's where you'll be able to control it.

 It doesn't require much fixing after you exit the app, though. In most cases, the resolution should revert to what you've set in Windows by default. If it doesn't, just go to Setting and change the resolution as explained in the previous section.

## 3\. Problems With the Hardware

 The resolution issue could also result from hardware issues. There are two components you need to check: the graphics card, and the display cable.

 When your display's resolution is higher than the resolution that either or both of these hardware components support, you could have a problem.

 For instance, if you're using an integrated graphics card or a very old one, your 4K display probably won't live up to your expectations. On the other hand, if you're using a single or double-link DVI, 4K isn't an option.

 If you're using an HDMI cable, you'll need to check for two things. First up is the type of HDMI cable. A category 3 HDMI supports 4K @60Hz. But there's another variable in this equation. You need to check what type of HDMI your graphics card supports. You'll need HDMI 1.3 at a minimum to view 4K @60Hz.

 If the issue is with your cable, try switching from [HDMI to DisplayPort](https://www.makeuseof.com/displayport-vs-hdmi/). If that's not an option, you'll need to spend some money upgrading your hardware.

 You can also diagnose problems with the hardware using the Hardware and Devices troubleshooter that is built into Windows by default.

 Here is how you can run it:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "cmd" in Run and press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the command below:  
msdt.exe -id DeviceDiagnostic  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/hardware-troubleshooter-command.jpg)
5. In the following dialog, click **Next** and wait for the troubleshooter to scan the system. If it finds an issue, it will notify you and suggest a fix. In that case, click on **Apply this fix**.  
![Run the Hardware and Devices Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-the-hardware-and-devices-troubleshooter.jpg)

## 4\. Faulty or Corrupt Display Drivers

 Drivers are necessary for your hardware to function properly. If your display driver is corrupt or outdated, it could lead to a problem with your display. Fortunately, it's easy to update the display or graphics driver. Below, we walk you through the steps of both updating and reinstalling drivers in detail.

### Update Drivers

 Press **Win + R**, type **devmgmt.msc**, and press **Enter** to launch Device Management. Expand the category called **Display adapters** by clicking on the tiny arrow to its left. Right-click on the display adapter you want to update and select **Update driver**.

![updating the driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/update-driver.jpg)

 You can search for drivers automatically, but there's a good chance Windows won't find anything. The second option will let you install the driver manually.

 To use the second option, you'll need to first download driver installation files from the manufacturer's website. When you're done, add the driver folder's location in the wizard and follow the wizard's prompts.

![updating the drivers manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/update-manual.jpg)

### Rollback or Reinstall Drivers

 In some cases, the updated driver can cause a problem instead of fixing it. If you started encountering the resolution issue after an update, consider rolling back the updated driver. Doing so uninstalls the updated driver and reverts to the previous driver.

 You'll first need to check if the option to roll back is available. You can do this by clicking on the relevant device and selecting properties. Switch to the **Driver** tab and select **Roll Back Driver**. If the option isn't grayed out, it's available. Click on it and follow the on-screen prompts to roll back the driver.

![rolling back the driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/roll-back-driver.jpg)

 Finally, if updating the driver or rolling it back to a previous version has not worked for you, you can consider reinstalling the driver using the manufacturer's website. Follow the steps in our guide on [cleanly installing and reinstalling GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for step-by-step instructions on this.

## 5\. An Incorrect Display Adapter Mode

 If you've got multiple monitors connected to your PC, and one or more of them seem to have a resolution problem, try checking the Display Mode settings on Windows. If you're duplicating a display on two screens that have different resolutions, one of them will have the wrong resolution.

 Unfortunately, there's no way to use the right resolution for each screen when using duplicate screens. You can either "extend" the display, or use the Display Adapter mode to select the right resolution for one display and let the other one stay as-is.

 To change the Display Adapter mode, go to **Settings** and navigate to **System > Display > Advanced Display**. Click on **Display adapter properties for Display 1** (click this option for the relevant display). Click on **List All Modes**, select the correct resolution, and click **OK**.

![changing the display mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/display-mode.jpg)

## 6\. Incorrect Font and Icon Sizes

 If you've set the correct resolution, but the text and icons on your screen appear too small, you might consider [tweaking the DPI](https://www.makeuseof.com/how-to-configure-display-scaling-windows-10/) (Dots Per Inch). Usually, this happens on small-sized high-resolution screens, like a 4K screen 15.6-inch.

 Changing DPI scaling is pretty easy, but not recommended. You might end up with illegible text and fuzzy-looking apps. Plus, it can often be difficult to revert to the original settings. If you decide to go ahead, be conservative with changing these numbers. The smaller the change, the better.

 You can change DPI scaling by going to Settings and navigating to **System > Display**. Click on the right arrow next to Custom scaling. On the next screen, you'll see a box where you need to enter a number between 100 and 500\. That's the percentage for DPI scaling you'd like to use.

![changing DPI scaling on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/custom-scaling.jpg)

## Windows Resolution Issues Resolved

 Hopefully, you were able to identify the issue and fix it. If you're facing a resolution issue while gaming, you might be tempted to choose the highest resolution from within the game. However, for you to be able to run the game at that resolution, your hardware will need to support it. It's best to get a basic idea of the best gaming resolution for your PC before you change it.

 Regardless of the reason for your viewing perils, we're going to help troubleshoot the display issue, so you can go back to enjoying high-quality viewing. We'll talk about the problems that can lead to a screen resolution issue and how you can fix them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-safe-slumber-techniques/"><u>Understanding Window's Safe Slumber Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-downloads-in-qbittorrent-for-windows/"><u>Reviving Stalled Downloads in qBittorrent for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-smooth-spotify-link-functionality-in-windows-11/"><u>Unlocking Smooth Spotify Link Functionality in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-diverse-windows-operations-to-start-software/"><u>Discovering Diverse Windows Operations to Start Software</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-probing-instagrams-max-video-length-rule/"><u>2024 Approved  Probing Instagram's Max Video Length Rule</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-camera-editing-showdown-hero-vs-cubes-battle-of-the-screens/"><u>In 2024, Camera Editing Showdown  Hero Vs. Cube's Battle of the Screens</u></a></li>
<li><a href="https://change-location.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-youtube-lives-thumbnail-code-for-2024/"><u>Unlocking YouTube Live's Thumbnail Code for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/which-is-better-for-streamers-obs-studio-or-fraps-in-2024/"><u>Which Is Better for Streamers, OBS Studio or Fraps, In 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtube-studio-for-beginners-basic-to-pro-editing-guide/"><u>In 2024, YouTube Studio for Beginners  Basic to Pro Editing Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mastering-image-dimensions-how-to-calculate-the-perfect-ratio/"><u>New 2024 Approved Mastering Image Dimensions How to Calculate the Perfect Ratio</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-top-video-enhancement-tools/"><u>2024 Approved Top Video Enhancement Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-optimal-vr-experience-a-review-of-top-oculus-models/"><u>[New] 2024 Approved  Optimal VR Experience  A Review of Top Oculus Models</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>