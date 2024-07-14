---
title: Troubleshooting 6 Typical Windows Display Issues
date: 2024-07-13T10:19:02.782Z
updated: 2024-07-14T10:19:02.782Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastery-setting-updeactivating-metric-tracker-in-win11/"><u>Mastery: Setting Up/Deactivating Metric Tracker in Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-ultimate-tips-for-exceptional-vr-gaming-video-quality/"><u>[New] In 2024, Ultimate Tips for Exceptional VR Gaming Video Quality</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-site-trust-on-windows-11/"><u>Mastering Site Trust on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-hues-overcoming-color-issues-on-windows/"><u>Harmonizing Hues: Overcoming Color Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-interruptions-during-steam-video-streaming/"><u>Preventing Interruptions During Steam Video Streaming</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-how-to-add-edit-and-optimize-youtube-tagstitledescription-for-more-views/"><u>[Updated] In 2024, How to Add, Edit and Optimize YouTube Tags/Title/Description for More Views</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-login-after-failures/"><u>How to Reactivate Windows Login After Failures</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-nonexistent-devices-in-os-windows-1011/"><u>Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-momentfreeze-immediate-screen-grab-guide/"><u>[Updated] MomentFreeze  Immediate Screen Grab Guide</u></a></li>
<li><a href="https://win11.techidaily.com/first-day-with-windows-11-heres-what-not-to-do-top-7-mistakes/"><u>First Day with Windows 11? Here's What Not to Do! - Top 7 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-system-top-tips-for-black-screen-on-win11/"><u>Jumpstart Your System: Top Tips for Black Screen on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-list-best-free-video-special-effects-apps-for-ios-and-android/"><u>New 2024 Approved The Ultimate List Best Free Video Special Effects Apps for iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-playable-media-error-xc10100bf/"><u>Overcoming Non-Playable Media Error XC10100BF</u></a></li>
<li><a href="https://extra-information.techidaily.com/ace-10-drones-for-photography-and-cinematic-prowess/"><u>Ace 10 Drones for Photography & Cinematic Prowess</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-discover-the-best-digital-stores-for-authentic-wildlife-audio/"><u>New In 2024, Discover the Best Digital Stores for Authentic Wildlife Audio</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-error-x800704cf-on-windows-devices/"><u>Guide to Resolving Error X800704CF on Windows Devices</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-maximize-your-reach-ideal-video-dimensions-for-instagram-feed-and-stories-for-2024/"><u>Updated Maximize Your Reach Ideal Video Dimensions for Instagram Feed and Stories for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-recorded-reality-facebook-live-2023-for-2024/"><u>[Updated] Recorded Reality  Facebook Live, 2023 for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevate-your-video-profiles-using-smart-templates-for-2024/"><u>[Updated] Elevate Your Video Profiles Using Smart Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-and-fixing-windows-update-issues/"><u>Mastering the Art of Finding and Fixing Windows Update Issues</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-high-res-display-settings-in-windows/"><u>Mastering High-Res Display Settings in Windows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-best-applications-for-crafting-dynamic-video-entrances/"><u>[New] 2024 Approved  Best Applications for Crafting Dynamic Video Entrances</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-shooting-high-quality-slow-mo-on-tiktok/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Shooting High-Quality Slow Mo on TikTok</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-gentle-silence-how-to-fade-out-music-in-adobe-editing/"><u>[Updated] Gentle Silence  How to Fade Out Music In Adobe Editing</u></a></li>
</ul></div>
