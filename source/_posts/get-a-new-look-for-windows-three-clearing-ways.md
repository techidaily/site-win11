---
title: "Get a New Look for Windows: Three Clearing Ways"
date: 2025-01-27T18:19:30.101Z
updated: 2025-02-03T19:45:04.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Get a New Look for Windows: Three Clearing Ways"
excerpt: "This Article Describes Get a New Look for Windows: Three Clearing Ways"
keywords: WinXP Rebuild,Refresh Windows,Clean Windows,New Windows GUI,Update Windows Theme,Reformat Windows,Modernize Windows UI
thumbnail: https://thmb.techidaily.com/d00f8f89497ceffd0abb3141cb4e3658817be8d659619b87570cab49fe038d18.jpg
---

## Get a New Look for Windows: Three Clearing Ways

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 The Registry Editor is a fantastic tool that allows you to configure some PC settings or troubleshoot system issues. But before you edit the Registry keys, always ensure to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. This will ensure that you have something to revert back to if something goes wrong.

 Now, let’s explore how you can clear your wallpaper history using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Copy and paste the following command into the address bar:

Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers

 You should see the following five background history paths on the right-hand side:

* BackgroundHistoryPath0
* BackgroundHistoryPath1
* BackgroundHistoryPath2
* BackgroundHistoryPath3
* BackgroundHistoryPath4

![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Clear Wallpaper History By Using a Registry File

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Repeat this process five times. From there, you should start seeing different images in the "wallpaper history" section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Your Previous Wallpapers Are Nowhere to Be Found

 Windows allows you to personalize your device to your liking. But then the system often keeps track of the changes you make on your PC. Fortunately, you can easily prevent others from seeing the changes you make on your device. For example, you can remove your wallpaper history using any of the methods we’ve covered.

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
<li><a href="https://extra-resources.techidaily.com/new-airpods-alone-restoring-connection/"><u>[New] Airpods Alone Restoring Connection</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/tep-up-vfx-game-discover-these-8-sites-for-free-backdrops-and-footage-for-2024/"><u>[New] Step Up VFX Game - Discover These 8 Sites for FREE Backdrops & Footage for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-tips-and-tricks-for-successful-social-media-video/"><u>[Updated] In 2024, Tips & Tricks for Successful Social Media Video</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-top-photography-choices-for-sharpest-4k-reflections-for-2024/"><u>[Updated] Top Photography Choices for Sharpest 4K Reflections for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-a-step-by-step-on-youtube-annotations/"><u>2024 Approved A Step-by-Step on YouTube Annotations</u></a></li>
<li><a href="https://driver-download.techidaily.com/comprehensive-list-of-toshiba-laptop-drivers-for-a-smooth-windows-experience/"><u>Comprehensive List of Toshiba Laptop Drivers for a Smooth Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-with-microsofts-ai-hub/"><u>Elevating User Experience with Microsoft's AI Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-less-known-windows-11-custom-styles/"><u>Explore Less-Known Windows 11 Custom Styles</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/gpt-powered-approach-to-healthy-eating-blueprints/"><u>GPT-Powered Approach to Healthy Eating Blueprints</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-making-windows-kali-compatible/"><u>Guide to Making Windows-Kali Compatible</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-disguise-concealing-linguistic-line-from-windows-11-status-bar/"><u>Mastering Disguise: Concealing Linguistic Line From Windows 11 Status Bar</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/navigating-affection-conveyance-via-magyar-words/"><u>Navigating Affection Conveyance via Magyar Words</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-inaccessibility-issues-with-csgo-on-w11/"><u>Overcoming Inaccessibility Issues with CS:GO on W11</u></a></li>
<li><a href="https://win11.techidaily.com/prepping-windows-users-webcam-and-mic-checks-for-meetings/"><u>Prepping Windows Users: Webcam & Mic Checks for Meetings</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-enabling-and-disabling-windows-key/"><u>Quick Fix: Enabling and Disabling Windows Key</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-remedying-components-not-present-error-on-win10win11/"><u>Quick Guide: Remedying Components Not Present Error on Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-tasks-selecting-the-windows-terminal-as-default/"><u>Streamlining Tasks: Selecting the Windows Terminal as Default</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/why-are-there-no-more-chatgpt-jailbreaks-7-reasons-chatgpt-jailbreaks-dont-work/"><u>Why Are There No More ChatGPT Jailbreaks? 7 Reasons ChatGPT Jailbreaks Don't Work</u></a></li>
<li><a href="https://win11.techidaily.com/why-opt-for-specific-video-coders-in-windows/"><u>Why Opt for Specific Video Coders in Windows?</u></a></li>
</ul></div>

