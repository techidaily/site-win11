---
title: "Customizing Win 11'S Context Menu: Exclude More Options"
date: 2024-10-13T16:16:33.426Z
updated: 2024-10-15T16:14:04.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing Win 11'S Context Menu: Exclude More Options"
excerpt: "This Article Describes Customizing Win 11'S Context Menu: Exclude More Options"
keywords: Win 11 Menu Customization,Exclude Win 11 Menu Items,Modify Win 11 Context Menu,Remove Win 11 Menu Options,Personalize Win 11 UI,Opt Out Windows 11 Commands,Edit Win 11 Taskbar Menu
thumbnail: https://thmb.techidaily.com/1925602951b4d52698ec670857ef818988d6fc983d6278e2dead21b251870b2b.jpg
---

## Customizing Win 11'S Context Menu: Exclude More Options

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-optimizing-youtube-content-for-instagram-platforms/"><u>[New] 2024 Approved Optimizing YouTube Content for Instagram Platforms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-seamless-integration-transferring-snapchat-images-directly/"><u>[New] 2024 Approved Seamless Integration Transferring Snapchat Images Directly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-burst-mode-enhances-gopro-videos/"><u>[New] How Burst Mode Enhances GoPro Videos</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-the-most-acclaimed-cloud-services-on-android-platform/"><u>[New] In 2024, The Most Acclaimed Cloud Services on Android Platform</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-ultimate-rule-book-on-instagram-video-length-for-2024/"><u>[New] The Ultimate Rule Book on Instagram Video Length for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-tackling-muted-frames-on-snapchat-videos-the-ultimate-solution/"><u>[Updated] Tackling Muted Frames on Snapchat Videos - The Ultimate Solution</u></a></li>
<li><a href="https://games-able.techidaily.com/craftsmads-and-fun-try-larger-arcade-cabinet-framing/"><u>Craftsmads and Fun: Try Larger Arcade Cabinet Framing!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-error-of-invalid-onedrive-blob-tag-presence/"><u>Fixing the Error of Invalid OneDrive Blob Tag Presence</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-the-reset-account-lockout-counter-after-failed-logon-attempts-in-windows-11-and-11/"><u>How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-ditch-input-lag-top-fixes-for-faster-typing-on-microsoft-os/"><u>How to Ditch Input Lag: Top Fixes for Faster Typing on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-microsoft-store-themes-a-step-by-step-approach/"><u>Implementing Microsoft Store Themes: A Step-by-Step Approach</u></a></li>
<li><a href="https://os-tips.techidaily.com/1723620276679-lost-iphone-discover-swift-solutions-with-this-complete-search-tutorial/"><u>Lost iPhone? Discover Swift Solutions with This Complete Search Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-7-fixes-for-non-scrolling-mouse-wheels/"><u>Mastering 7 Fixes for Non-Scrolling Mouse Wheels</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-ms-paint-windows-11s-toolbox/"><u>Navigating to MS Paint, Windows 11'S Toolbox</u></a></li>
<li><a href="https://win11.techidaily.com/secure-win-vbox-install-deps-must-come-first/"><u>Secure Win VBox Install: Deps Must Come FIRST</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-default-commands-interpreter-in-windows/"><u>Tweaking the Default Commands Interpreter in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-discussion-treasures-for-listener-retention/"><u>Updated Discussion Treasures for Listener Retention</u></a></li>
</ul></div>

