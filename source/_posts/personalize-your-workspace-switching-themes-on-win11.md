---
title: "Personalize Your Workspace: Switching Themes on Win11"
date: 2024-06-25T11:25:34.695Z
updated: 2024-06-26T11:25:34.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalize Your Workspace: Switching Themes on Win11"
excerpt: "This Article Describes Personalize Your Workspace: Switching Themes on Win11"
keywords: Workspace Personalization,Win11 Theme Change,Custom Windows Desktop,Enhance Workspace UI,Dynamic Win11 Aesthetics,User-Defined Window Layouts,Adaptive Win11 Design
thumbnail: https://thmb.techidaily.com/f247ef7a94b421ec0fcafea579ee074c3050225ad0c19a044a9d73401964e5e7.jpg
---

## Personalize Your Workspace: Switching Themes on Win11

 Windows has inbuilt support for themes in customization settings. While Microsoft doesn’t officially make any new themes as it did before, plenty of options are available on Microsoft Store. If you aren’t satisfied with them, you can also try third-party themes.

 Microsoft moved many Control Panel options to the Settings app. So, you need to head over to the Personalization options in the Settings app to apply a new theme. But, do you know that you can do it using multiple other methods? Here’s how:

## 1\. Using the Desktop Context Menu

 The desktop context menu is the most preferred method to change desktop wallpaper and themes in Windows OS. Windows 11 retains that option in the context menu, and we hope that it doesn’t go away. Here’s how to change the theme using the Desktop context menu:

1. Boot up your Windows PC and right-click on the desktop.
2. Now, click on the**Personalization** option from the context menu.  
![Changing Theme Using the Desktop Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-desktop-context-menu.jpg)
3. Scroll down and click on the**Themes** option.
4. Under the Current theme section, click on any of the available themes to apply them to your system.
5. Close the settings app.

## 2\. Using the Settings App

 Since the desktop context menu redirects you to the Settings app, you can directly open it and change the system theme. Here’s how:

1. Press**Win + I** to launch the Settings app.
2. Click on the**Personalization** option in the left-hand side menu.
3. Scroll down and select the**Themes** option.  
![Changing Theme Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-settings-app.jpg)
4. Now, click on any theme from the section of available themes. You can also apply a high-contrast theme by selecting the Contrast Theme option below.

## 3\. Using the Old Control Panel Personalization Utility

 The older version of Windows OS had a control panel personalization utility, using which you could change the themes, color schemes, and wallpapers. Microsoft hid this option in Windows 11, but you can still access it using the run command box. Here’s how:

`shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}-Microsoft.Personalization`

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type the following command and press the enter key.
2. The old Personalization utility will launch. Navigate to the themes window and click on any theme to apply it. The utility won’t redirect you to the Settings app.  
![Changing Theme Using the Old Control Panel Personalization Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-old-control-panel-personalization-utility.jpg)
3. Close the Personalization utility window.

## 4\. Using the Run Command Box

 You can even skip the hassle to go through layers of the Settings app and can directly launch the theme settings using the Run command box. Here’s how:

1. Press**Win + R** to launch the Run command box. Type**ms-settings:themes** and press the enter key.
2. Windows 11 Settings app will launch and directly take you to the themes section.
3. Click on any of the available themes to apply and change the current theme.

## 5\. Using File Explorer

 All the installed themes on your Windows 11 system reside in the Windows AppData folder. You can access the folder using File Explorer and then apply any theme on your system. Here’s how:

1. Press**Win + E** to[launch the File Explorer app](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, paste the following path, and press the enter key:**%LocalAppData%\\Microsoft\\Windows\\Themes**
3. You will see a bunch of themes listed here. Double-click on any ".theme" file to apply it to your system.  
![Changing Theme Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-file-explorer.jpg)
4. There will be a bunch of folders as well. These usually belong to the downloaded themes. Open the folder, and locate the theme file to apply a downloaded theme.

## 6\. Using CMD

 You can change the theme in Windows 11 using the command prompt. All you need to do is enter the location of the theme and run it. Repeat the following steps:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (admin)** option from the menu.
2. The Terminal app will launch. Click on the**+** icon to open a command prompt window with admin privileges.
3. Now, type**C:\\Windows\\resources\\Themes\\aero.theme** command and press the enter key.  
![Changing Theme Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-cmd.jpg)
4. Your Windows 11 system will change to the inbuilt aero theme. Similarly, you can replace the name of any other inbuilt theme and apply it.

## 7\. Using a Shortcut

 You can apply your favorite theme by creating a shortcut on the desktop. That way, you won’t have to launch the File Explorer or Settings app to change the theme. Here’s how to do it:

1. Press**Win + E** to launch the File Explorer app.
2. Navigate to the address bar and type the following path:**C:\\Windows\\resources\\Themes\\**
3. Press the enter key to open the Themes folder.
4. Now, right-click on a theme and click on**Show More** options.
5. Then click on the**Send to** option and select the**Desktop (create shortcut)** option.  
![Changing Theme Using a Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-a-shortcut.jpg)
6. Press**Win + D** to switch to the Desktop. Make sure to close the Settings app before running the shortcut.
7. Double-click on the newly created theme shortcut to apply the theme to your computer

## 8\. Using PowerShell

 Like CMD, you can access the theme files from PowerShell and change the theme. Repeat the following steps:

1. Press**Win + R** to launch the Run command box. Type PowerShell in the text input area and press**Ctrl + Shift + Enter** to launch PowerShell with admin privileges.
2. Now enter the following command and press the enter key:
3. start-process -filepath "C:\\Windows\\Resources\\Themes\\aero.theme"
4. You can replace the “aero.theme” portion of the command with any other theme name. Some of the examples include: “dark.theme” and “spotlight.theme”.  
![Changing Theme Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-powershell.jpg)
5. Type**exit** and press enter to close the command prompt.

## 9\. Using a Batch File

 You can create a batch file and run it every time someone changes your preferred theme. Moreover, you can place it on the desktop to quickly switch to a theme. Here’s how to do it:

`C:\Windows\resources\Themes\aero.theme  
 taskkill /F /IM systemsettings.exe`

1. Press**Win + S** and type Notepad. Click on the first search result to open the Notepad app.
2. Now, paste the following script into the Notepad file:
3. Go to the top menu bar and click on**File > Save as** option. Keep the filename as**changetheme.bat** , select the**All files** option, and save it on the desktop.  
![Changing Theme Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-a-batch-file.jpg)
4. Close the Notepad app and Press Win + D to switch to the desktop.
5. Now, right-click on the changetheme.bat file and select the**Run as administrator** option.
6. The file will open a command prompt window, change the theme and close the CMD and System Settings window automatically.

## Change Your Windows 11 Themes Like a Pro

 Windows 11 stores themes in multiple locations. The simplest way to change the theme is by using the Settings app. But if you want to keep the mouse clicks to a minimum, creating the shortcut of a theme file or running a batch script is better. If you aren’t afraid of the Terminal, the command prompt and PowerShell methods also work like a charm.


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
<li><a href="https://win11.techidaily.com/how-to-disable-autonomous-command-line-openings/"><u>How to Disable Autonomous Command Line Openings</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-11-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-devhome-navigating-windows-11-with-ease/"><u>Introducing DevHome: Navigating Windows 11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-finding-fixes-for-systemsettingsexe-in-win11/"><u>Tips for Finding Fixes for SystemSettings.exe in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-path-not-found-in-windows-os/"><u>Troubleshooting PATH Not Found in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-inability-to-remove-apps/"><u>Troubleshooting Windows' Inability to Remove Apps</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-same-account-issues-on-a-device/"><u>Disentangling Same-Account Issues on a Device</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-secrets-of-seamlessly-sharing-in-tiktok-livestreams-for-2024/"><u>[New] Secrets of Seamlessly Sharing in TikTok Livestreams for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-6s-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 6s Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-your-photos-top-6-iphone-tools-for-object-elimination/"><u>Streamline Your Photos  Top 6 iPhone Tools for Object Elimination</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unrestricted-story-preservation-free-for-2024/"><u>[New] Unrestricted Story Preservation, FREE for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unveiling-the-art-of-discopf-making-your-virtual-self-shine-for-2024/"><u>[New] Unveiling the Art of DiscoPf  Making Your Virtual Self Shine for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-sony-camcorder-video-editing-tutorial-from-capture-to-masterpiece-for-2024/"><u>Updated Sony Camcorder Video Editing Tutorial From Capture to Masterpiece for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-stealthy-watcher-of-digital-tales/"><u>[Updated] 2024 Approved  Stealthy Watcher of Digital Tales</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-net-booster-fb-stories-repository-app/"><u>[New] In 2024, Net Booster  FB Stories Repository App</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-boost-mobile-stream-quality-on-android-and-ios-devices/"><u>[Updated] 2024 Approved  Boost Mobile Stream Quality on Android and iOS Devices</u></a></li>
</ul></div>
