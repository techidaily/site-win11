---
title: "Ahead of the Curve: Using ViVeTool on Your PC"
date: 2024-07-13T11:18:39.563Z
updated: 2024-07-14T11:18:39.563Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Ahead of the Curve: Using ViVeTool on Your PC"
excerpt: "This Article Describes Ahead of the Curve: Using ViVeTool on Your PC"
keywords: PC ViVeTool Usage,Adopting ViVeTech,Innovative PC Tools,Advanced Tech Solutions,Curve-Ahead Technology,ViVeTools PC Enhancement,Cutting-Edge PC Software
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Ahead of the Curve: Using ViVeTool on Your PC

 ViVeTool is an open-source command-line tool to enable experimental but hidden features on your Windows computer. It is also available in a GUI version, which makes it much easier to enable or disable certain features on Windows.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

## What Is ViVeTool, and How Does It Work?

 ViVeTool is a third-party open-source C# library and console app to enable unreleased features on your Windows computer. You can also use it to restore or disable certain features.

 ViVeTool uses feature IDs, part of Windows Feature Management, a software-development practice, to identify the available features. You can then use the feature IDs to enable or disable certain features on your Windows computer by using the ViVeTool command-line or GUI utility.

 For example, if you want to remove the new search box and replace it with the classic search icon, you’ll need to run the **ViVetool /disable /id:39263329** command using the ViVeTool command-line utility.

 The **feature ID id:39263329** in the above command tells the ViVeTool and the subsequent API request which feature to toggle on your Windows computer.

 You can source the feature ID from the internet or by using the ViVeTool GUI version. That said, the feature ID description in the GUI version is mostly cryptic, so tread carefully. Once you have the feature ID, you can use the ViVeTool command-line or GUI version to enable or disable features on your Windows computer.

## Is ViVeTool Safe to Use?

 ViVeTool doesn’t add new features on its own. It simply toggles the existing features to enable or disable them for your Windows system. However, since these features are experimental by nature, activating them may sometimes cause some issues.

 If you want to use ViVeTool on your daily driver, go through the [Windows data backup and recovery options](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) and proceed with the steps below. Ideally, use a virtual machine to test new features, and if found to be stable, apply them to your daily driver.

## How to Download and Install the ViVeTool GUI Version

 ViVeTool GUI is the forked version of the ViVeTool command-line utility. It is less complicated to use and removes the hassle of executing commands or remembering them in the first place. The GUI version is available as an executable installer or portable version. Here’s how to install and use ViVeTool GUI on Windows.

 To download the ViVeTool GUI version:

1. Go to the [ViVeTool GUI page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub.  
![download vivetool gui zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-gui-zip.jpg)
2. Download the latest version of the **Setup.exe file** available. You can also download a portable version if you prefer.
3. Run the setup file and keep the default settings. Follow the on-screen instructions to install the app.

## How to Install Unreleased Features Using ViVeTool on Windows

 Now that the app is installed, you can use it to find and install unreleased features on your Windows computer. Here’s how to do it:

1. Launch the ViVeTool using a desktop shortcut or from the **Start** menu.  
![vivetool gui select build](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-gui-select-build.jpg)
2. Click the **Select Build** drop-down in the top-left corner and select your **Windows build.** You can [check Windows 11 build and version](https://www.makeuseof.com/check-build-and-version-windows-11/) using the **Settings app**. ViVeTool GUI will now start looking for all the available features for the selected build. This may take a few minutes, so wait till the list is populated.
3. ViVeTool GUI categorizes the available features into different categories, including **Always Disabled**, **Always Enabled**, **Disabled by Default**, **Enabled by Default**, and **Modifiable**. You can expand the category and select the feature to install.
4. Next, select the feature you want to enable or disable. Alternatively, type the feature name in the search bar to find a specific feature.  
![activate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/activate-feature-vivetool-gui.jpg)
5. Click the **Perform Action** drop-down select **Activate** to enable the feature. Wait for the success message and click **Close**.  
![revert to default values feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/revert-to-default-values-feature-vivetool-gui.jpg)
6. If the changes are not immediately visible, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) to apply the changes. In some instances, you may need to restart your PC to make the changes.

 To revert the changes or disable a feature, you can use the Deactivate Feature option available in ViVeTool. Here's how to disable a feature using ViVeTool:

![deactivate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/deactivate-feature-vivetool-gui.jpg)

1. Launch **ViVeTool GUI.**
2. Search and select the feature you want to disable.
3. Click the **Perform Action** drop-down in the top-right corner.
4. Select **Deactivate Feature** and click **OK**.

 Alternatively, you can also revert the feature to its default state. To do this, select the modified feature, click on **Perform Action,** and select **Revert Feature to Default Values.** The changes will take effect when you restart your computer next time.

 Here are a few new and lesser-known Windows features that you can enable using ViVeTool before anyone else:

* [Enable Windows Copilot Using ViVeTool](https://www.makeuseof.com/enable-windows-copilot-vivetool/)
* [Enable the Home Section in the Settings App in Windows 11](https://www.makeuseof.com/enable-home-section-settings-app-windows-11/)
* [Enable Instant Search Results in File Explorer in Windows 11](https://www.makeuseof.com/instant-search-results-file-explorer-windows-11/)
* [Enable the Enhanced Taskbar in Windows 11](https://www.makeuseof.com/enhanced-taskbar-settings-windows-11/)
* [Enable the Volume Mixer in the Action Center in Windows 11](https://www.makeuseof.com/volume-mixer-action-center-windows/)

## How to Use the ViVeTool Command-Line Version

 The original version of ViVeTool is a command-line utility. While it offers similar functionality as the GUI version, it is an efficient way to enable and disable Windows features quickly. Here’s how to do it:

1. Go to the [ViVeTool page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub. This lists all the releases of ViVeTools since its inception.  
![download vivetool command line zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-command-line-zip.jpg)
2. Locate the latest version of ViVeTools. As of writing this, **Version 1.6.2** is the latest stable release available, and version 1.7 is available as a pre-release.
3. Click on **Assets** to view the download options.
4. Next, click the **ViVeTool.GUI.1.6.2.0.Portable.zip** file (version may change with the new releases) to download the latest version to your local drive.  
![vivetool zip extract folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-zip-extract-folder.jpg)
5. Right-click on the **Zip** file and select **Extract** **all**. Select a destination and click **Extract**. Take note of the extraction folder.

1. Next, press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![command prompt vivetool change directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-change-directory.jpg)
3. In the Command Prompt, change the directory to ViVeTool extracted folder. So, type the following command and press **Enter** to change the directory:  
`cd /d [ViVeToolFolderPath]`
4. For example, if I have the ViVeTool folder saved in C:\\Users\\username\\Downloads\\ViVeTool-v0.3.2, then the full command will look this:  
`cd /d C:\Users\username\Downloads\ViVeTool-v0.3.2`
5. Next, to enable a feature, use the following command and press Enter:  
`ViVeTool.exe /enable /id:featureID`

1. In the above command, replace featureID with the feature ID you want to enable.  
![command prompt vivetool enable feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-enable-feature.jpg)
2. For example, to enable the tab feature in File Explorer, the feature ID is id:37634385\. So, the full command will look like this:  
`ViVeTool.exe /enable /id:37634385`
3. If you want to disable a feature, then the command will look something like this:  
`ViVeTool.exe /disable /id:featureID`
4. Once the command is executed, type exit and press Enter to close the Command Prompt.
5. Restart your PC to apply the changes. After the PC restarts, the changes should be visible.

## Why Does Enabling a Feature in ViVeTool Not Do Anything?

 You may not be able to enable all the features present in ViVeTool. Almost all the hidden features are OS build-dependent. This means if you enable a feature using ViVeTool, but the changes don’t take effect, it is likely because the feature is not supported by the Windows OS build version you are running.

 In other instances, it may be due to the feature state being set to **Always Disabled** or **Enabled** during compilation. In this instance, even if ViVeTool successfully processes your request, you are unlikely to see any real changes, as the feature is hard-coded to remain on or off.

## ViVeTool's Supported Commands

 Apart from the /enable and /disable command, ViVeTools support a bunch of other commands to reset the custom configuration for specific or all features, update ViVeTool, and export and import custom feature configuration.

| ViVeTool Command | Action                                                       |
| ---------------- | ------------------------------------------------------------ |
| /enable          | Enable a feature                                             |
| /disable         | Disable a feature                                            |
| /query           | Find a list of all the existing features configuration       |
| /reset           | To reset a custom configuration for a specific feature       |
| /resetall        | To reset a custom configuration for all the features         |
| /addsubs         | To add a feature usage subscription                          |
| /delsub          | To remove a feature usage subscription                       |
| /export          | To export custom feature configuration                       |
| /import          | To import custom feature configuration                       |
| /fixlkg          | Fix the current ‘Last Known Good’ rollback system corruption |
| /appupdate       | Look for new ViVeTool updates                                |
| /notifyusage     | Shows a feature notification                                 |

## ViVeTool Brings Hidden Windows Experimental Features to Everyone

 ViVeTool makes it easy to find and test new experimental features before they are released to the public. Whether you use the GUI or command-line version, it lets you easily enable and disable some exciting and annoying features.

 That said, many of these hidden features may be buggy and cause system malfunction. So, keep your system backup handy before you tinker with ViVeTool.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/exploring-vlc-options-and-rivals-for-2024/"><u>Exploring VLC Options and Rivals for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-guide-on-unlocking-iphone-xs-max-with-a-broken-screen-drfone-by-drfone-ios/"><u>Complete Guide on Unlocking iPhone XS Max with a Broken Screen? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-lava-blaze-curve-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Lava Blaze Curve 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-windows-11s-anti-phishing-filter/"><u>Activating/Deactivating Windows 11'S Anti-Phishing Filter</u></a></li>
<li><a href="https://win11.techidaily.com/4-futuristic-windows-features-outgrowing-cortana/"><u>4 Futuristic Windows Features Outgrowing Cortana</u></a></li>
<li><a href="https://win11.techidaily.com/automating-jpeg-creation-from-heic-images/"><u>Automating JPEG Creation From HEIC Images</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-delicate-visual-initiation-for-2024/"><u>[New] Delicate Visual Initiation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-the-flow-of-tasks-with-fast-outlook/"><u>Accelerate the Flow of Tasks with Fast Outlook</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-esl-english-as-second-language-for-vr/"><u>In 2024, The ESL (English as Second Language) for VR</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-maintaining-perpetual-ps4-windows-tether/"><u>A Guide to Maintaining Perpetual PS4-Windows Tether</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-quickcut-youtube-artist/"><u>[New] QuickCut YouTube Artist</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-fcpx-audio-cleanup-tips-and-tricks-for-removing-unwanted-sounds-for-2024/"><u>Updated FCPX Audio Cleanup Tips and Tricks for Removing Unwanted Sounds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719369059725-streamline-facebook-messenger-on-your-pc-now/"><u>Streamline Facebook Messenger On Your PC Now!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-your-first-steps-in-high-quality-youtubing/"><u>2024 Approved  Your First Steps in High-Quality YouTubing</u></a></li>
<li><a href="https://win11.techidaily.com/1719328295929-reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way!</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-0x800704b3-network-hurdles-in-win1011/"><u>Addressing 0X800704B3 Network Hurdles in Win10/11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-12-pro-max-by-restoring-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 12 Pro Max by restoring</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-insta-photography-enhancement-hacks-for-professionals/"><u>2024 Approved  Insta-Photography Enhancement Hacks for Professionals</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-cultivate-your-circle-grow-your-instagram-flock-to-1k-every-month/"><u>[Updated] Cultivate Your Circle  Grow Your Instagram Flock to 1K Every Month</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-speakers-guide-to-voiceover-on-microsoft-ppt/"><u>2024 Approved  The Speaker's Guide to Voiceover on Microsoft PPT</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11s-0x800713f-email-problem/"><u>Addressing Windows 11'S 0X800713F Email Problem</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-guide-transforming-heic-images-into-jpeg-format-with-w11-ease/"><u>Accurate Guide: Transforming HEIC Images Into JPEG Format with W11 Ease</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-windows-spotlight-images-on-the-lock-screen/"><u>3 Ways to Enable or Disable the Windows Spotlight Images on the Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-odbc-connectivity/"><u>A Comprehensive Guide to Windows' ODBC Connectivity</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-navigating-the-nuances-of-using-switch-pro-controller-on-steam/"><u>[New] In 2024, Navigating the Nuances of Using Switch Pro Controller on Steam</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-switching-onoff-comment-functionality-on-youtube/"><u>[Updated] Switching On/Off Comment Functionality on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-issues-with-windows-alt-code-operations-53-characters/"><u>Addressing Issues with Windows Alt Code Operations (53 Characters)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-video-privacy-measures-blurring-and-concealing-details/"><u>In 2024, Video Privacy Measures  Blurring and Concealing Details</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-30005-for-unsuccessful-file-generation/"><u>Addressing Windows Error 30005 for Unsuccessful File Generation</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-vivo-s17-pro-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Vivo S17 Pro Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-preview-sizes-on-windows-11/"><u>Adjusting Photo Preview Sizes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unclickable-elements-in-the-new-os/"><u>Addressing Unclickable Elements in the New OS</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-resize-images-in-windows-11/"><u>6 Ways to Resize Images in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-vdr-hd-vision-recorder-report-full-overview/"><u>[Updated] 2024 Approved  VDR HD Vision Recorder Report  Full Overview</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/auto-displaying-images-craft-your-windows-11-slide-show-7-ways/"><u>Auto-Displaying Images: Craft Your Windows 11 Slide Show (7 Ways)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-tips-for-posting-wide-angle-photos-to-facebook-from-smartphones/"><u>In 2024, Tips for Posting Wide Angle Photos to Facebook From Smartphones</u></a></li>
</ul></div>
