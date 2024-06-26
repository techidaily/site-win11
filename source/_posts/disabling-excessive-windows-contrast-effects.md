---
title: Disabling Excessive Windows Contrast Effects
date: 2024-06-25T09:55:41.759Z
updated: 2024-06-26T09:55:41.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Excessive Windows Contrast Effects
excerpt: This Article Describes Disabling Excessive Windows Contrast Effects
keywords: Reduce Windows Contrast,Minimize Windows Palette,Lower Window Brightness,Decrease Windows Glare,Dim Windows Overexposure,Cut Windows Highlighting,Control Windows Luminosity
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Disabling Excessive Windows Contrast Effects

 Microsoft first introduced high-contrast themes with Windows 7\. The idea was to add a theme that helps users with low vision or photosensitivity see screen elements better. But not everyone needs the high contrast mode on Windows 11 or older versions. Maybe you turned it on by accident and are now struggling to turn it off.

 High contrast mode makes the screen elements darker to increase clarity, but the result may not look inviting for every user. As such, we will explore multiple methods to turn off the high contrast mode on Windows 11 or older operating systems.

## What Is High Contrast Mode?

 High Contrast Mode is an accessibility feature that comes free with Windows. It makes certain screen elements darker and more distinguishable so that users with low vision can see everything. High contrast mode isn’t limited to Windows only; you can also find it in Android, iOS, macOS, Linux, and more.

 But there is a dark mode on Windows 11, isn't there? So, why do we need high-contrast themes? It is because dark mode can reduce the strain on the eyes and is helpful for users who don’t have problems with their vision. But dark mode makes everything black except the text and people with low vision may struggle with it.

 High contrast themes offer customizability to tweak different screen elements, like text, links, background, button text, and more. It's a lot more helpful than dark mode, which just adds a dark or black-grayish background with a white color.

## How to Disable High Contrast Mode on Windows

 If High Contrast Mode has been turned on and you'd like to change that, there are multiple ways to get the job done.

### 1\. Using the High Contrast Mode Shortcut keys

 To disable high contrast mode on Windows using keyboard shortcuts, press the**Left Alt + Left Shift + Print Screen** keys at once. You won’t see any pop-up window to confirm the action, but you will hear a “beep” sound before the system reverts to the default theme. You can use this shortcut again if you need to re-enable High Contrast mode.

### 2\. Using the Settings app

 To disable the high contrast mode using the Settings app on Windows 8 and above, do as follows.

1. Press**Win + I** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) on your system.
2. Navigate to the left-hand side menu and click on**Personalization** .
3. Click on the**Themes** option under Personalization. Scroll down and click on the**Contrast Themes** option.
4. Click on the drop-down menu in the Contrast Themes option and select the**None** option.  
![Disable High Contrast Mode Using Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-settings-app.jpg)
5. Then, click on the**Apply** option. Windows will change back to the previous theme.

### 3\. Using the Sign-in screen

 You can even disable the high contrast mode on Windows 11 and 10 before you sign in. Here’s how to do it:

1. Power on your Windows PC. Press any key or click the mouse key to go to the sign-in screen.
2. Navigate to the bottom-right area and click on the**Accessibility** icon.
3. The Accessibility menu will pop up. Click on the**Contrast Theme** toggle to disable it.  
![Disable High Contrast Mode Using Sign In Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-sign-in-screen.jpg)
4. Windows will revert to the default theme. Enter your PIN or password and log in.

### 4\. Using the Control Panel

 To disable the high contrast mode in Windows 11 and 10, do as follows:

1. Press the**Win + S** to bring up Windows Search. Type Control Panel and click on the search result
2. The Control Panel will launch. Click on the**Appearance and Personalization** option.
3. Select the Ease of Access option and click on the**Set Up high contrast** option.
4. Now, select the**Choose a high contrast theme** option.  
![Disable High Contrast Mode Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-control-panel.jpg)
5. Navigate to**Themes > Contrast Themes** .
6. Click on the drop-down menu in the Contrast Themes option and select the**None** option.
7. Then, click on the**Apply** button.

 Windows 7 doesn’t have a Settings app, so the process of disabling high contrast mode using the Control Panel is a bit different:

1. Press the**Win** key and click on the Control Panel option.
2. Navigate to**Appearance and Personalization > Personalization** .
3. Click on the Windows classic theme or any other system theme.
4. Windows 7 will switch from the high contrast theme to a normal theme.

### 5\. Using the Run Dialog Box

 Repeat the following steps to disable high contrast mode using the run command box:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}** ” in the text input area and press the Enter key.  
![Disable High Contrast Mode Using Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-run-box.jpg)
3. The old personalization settings control panel window will launch.
4. Click on any system theme. It will deactivate the current high-contrast theme and apply the selected theme.

### 6\. Using Another Theme

 You can disable the high-contrast theme by applying another theme to your system. Here’s how to do it:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Personalization > Themes** .
3. Move to the**Current theme** section and click on any default system theme or a downloaded theme.  
![Disable High Contrast Mode Using A Different Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-different-theme.jpg)
4. Windows will apply the selected theme.

 If you want to re-enable the high-contrast theme, you have to visit the "high contrast theme" section here and choose a compatible theme.

### 7\. Using a Script

 It is also possible to revert to a system theme using a script file on Windows. It will take less time as opposed to navigating the settings app to disable the high contrast mode. Here’s how to do it:

1. Go to the desktop. Right-click on the desktop and click on**New > Text Document** .
2. Open the newly created text file and paste the following script into it.  
@echo off C:\Windows\resources\Themes\aero.themetaskkill /F /IM systemsettings.exe
3. Now, press**Ctrl + S** to save the file. Type the name “**disablehc.bat** ” and click on the**save** button.  
![Disable High Contrast Mode Using a script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-script.jpg)
4. Go to the desktop again and right-click on the newly created .bat file.
5. Select the**Run as administrator** option in the context menu.
6. UAC will pop up. Click on the**Yes** button to grant administrator privileges to the .bat file. Otherwise, it won’t be able to make changes to the system theme.
7. The command prompt will pop up for a few seconds, run the script, and then close automatically. Your Windows system will disable the high contrast mode and switch to the aero theme.

## The Windows High Contrast Theme Won’t Bother You Anymore

 These were the seven methods using which you can disable the high contrast theme on Windows. The quickest way is to use the hotkeys for contrast themes or use a BAT script. If you want to save your eyes from the harsh white light but cannot stand high-contrast themes, use a dark theme on Windows 11.

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
<li><a href="https://win11.techidaily.com/searching-for-a-slender-browser-footprint-on-your-desktop/"><u>Searching For a Slender Browser Footprint on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-signs-on-screen-when-booting-windows/"><u>Fixing No Signs on Screen When Booting Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-latency-and-silence-in-valorants-voice-communication-windows/"><u>Fixing Latency and Silence in Valorant's Voice Communication (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-energy-requirement-monitoring-machine-might/"><u>Windows Energy Requirement: Monitoring Machine Might</u></a></li>
<li><a href="https://win11.techidaily.com/set-windows-clock-without-automatic-regional-switching/"><u>Set Windows Clock Without Automatic Regional Switching</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-rectify-erroneous-device-listings-in-windows/"><u>Guidelines to Rectify Erroneous Device Listings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-users-a-comprehensive-guide-to-windows-tweaks-via-alomware/"><u>Empowering Users: A Comprehensive Guide to Windows Tweaks via AlomWare</u></a></li>
<li><a href="https://win11.techidaily.com/chocolatey-vs-windows-package-manager-which-is-the-better-tool-to-download-software-on-windows/"><u>Chocolatey Vs. Windows Package Manager: Which Is the Better Tool to Download Software on Windows?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/explore-the-ultimate-list-of-comedy-tears-on-instagram-for-2024/"><u>Explore the Ultimate List of Comedy-Tears On Instagram for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-creator-to-earnings-successful-youtube-short-strategies-for-2024/"><u>[Updated] From Creator to Earnings  Successful YouTube Short Strategies for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-quality-microphone-recorders-for-mac-devices-our-five-choices-revealed/"><u>[New] In 2024, Quality Microphone Recorders for Mac Devices  Our Five Choices Revealed</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-advanced-editing-guide-for-creating-compelling-360-degree-videos-using-premiere-pro/"><u>In 2024, Advanced Editing Guide for Creating Compelling 360-Degree Videos Using Premiere Pro</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-top-rated-free-game-download-sites-for-pc-android-and-mobile-devices/"><u>2024 Approved Top-Rated Free Game Download Sites for PC, Android, and Mobile Devices</u></a></li>
<li><a href="https://extra-hints.techidaily.com/15-recommended-stop-motion-films-of-all-time/"><u>15 Recommended Stop Motion Films of All Time</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tailoring-your-canvas-a-guide-to-erasing-background-elements/"><u>[New] Tailoring Your Canvas  A Guide to Erasing Background Elements</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-unveiling-the-art-of-reshaping-your-tiktok-avatar/"><u>[New] In 2024, Unveiling the Art of Reshaping Your TikTok Avatar</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-xml-demystified-unlocking-fcpxs-full-potential/"><u>2024 Approved XML Demystified Unlocking FCPXs Full Potential</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Oppo Find N3 Flip | Dr.fone</u></a></li>
</ul></div>
