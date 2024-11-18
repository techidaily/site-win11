---
title: Remove Highlighted Desktop Icons in Windows 11
date: 2024-11-12T03:21:39.425Z
updated: 2024-11-17T21:22:42.534Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remove Highlighted Desktop Icons in Windows 11
excerpt: This Article Describes Remove Highlighted Desktop Icons in Windows 11
keywords: WINDOWS Icon Removal,Desktop Icons Hide,Remove Icons Highlight,Windows 11 Icon Hide,Icons Not Showcase,De-Highlighting Icons,Disable Highlighted Icons
thumbnail: https://thmb.techidaily.com/aa427c93a364e264a275d02d7b783f7e962d85c1fac24bb52cc0d4742cbe1750.jpg
---

## Remove Highlighted Desktop Icons in Windows 11

 Spotlight is a feature that adds different Bing images to Windows 11’s desktop background when enabled. That feature also adds a "Learn about this picture" icon to the desktop you can double-click to bring up image info. Right-clicking that icon brings up a context menu that includes a **Switch to next picture** option.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove the Spotlight Desktop Icon With a Manual Registry Tweak

 A relatively simple registry tweak is required to remove the "Learn about this picture" icon from the Windows Spotlight wallpaper. These are the steps for removing the Spotlight desktop icon by manually tweaking the registry:

1. Launch Run by right-clicking **Start** (the taskbar icon) and selecting **Run**.
2. Enter **regedit** inside Run’s **Open** command box and select **OK** to [access the Registry Editor app](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Next, go to this **NewStartPanel** key by inputting its path in the registry address bar:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel`
4. Right-click **NewStartPanel** and select **New** to view a submenu with options for adding new registry entries.  
![The New DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-new-dword-option.jpg)
5. Click **DWORD (32-bit) Value** on the submenu.

1. Copy **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** to your clipboard by selecting the text and pressing **Ctrl** \+ **C**. Then press **Ctrl** \+ **V** to paste that into the DWORD’s name text box.
2. Double-click the **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you just added.
3. Delete **0** in the **Value data** box.
4. Input **1** in the **Value data** box and click **OK**.  
![The NewStartPanel key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-window.jpg)
5. Click Registry Editor’s **X** window button.
6. Right-click any empty part of the desktop and select **Refresh**. The "Learn about this picture icon" will no longer be on the desktop.

 If you ever want to restore that Spotlight icon, you can do so by changing the value of the {**2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you added to the registry. Double-click **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** in the **NewStartPanel** key to input **0** in that DWORD’s **Value data** box. Refreshing the desktop will then restore the "Learn about this picture" icon.

![The Learn about this picture desktop icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-learn-about-this-picture-icon.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Remove the Spotlight Desktop Icon With Winaero Tweaker

 The manual registry tweaking required for removing the "Learn about this picture" icon is relatively straightforward. However, you can remove the Spotlight desktop icon with Winaero Tweaker if you still prefer not to fiddle with the registry.

 At any rate, Winaero Tweaker is a fantastic piece of Windows customization software that’s worth installing. You can remove the Spotlight desktop icon with Winaero Tweaker like this:

1. Go to this [Winaero Tweaker download page](https://winaero.com/download-winaero-tweaker/) and click the download link there.
2. Extract the Winaero Tweaker ZIP and install the software with its setup file. Our guide to [customizing Windows with Winaero Tweaker](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes step-by-step installation instructions for that software.
3. Next, double-click the **Windows 11** category within Winaero Tweaker’s sidebar.  
![The Windows 11 category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-11-category.jpg)
4. Click **Remove Windows Spotlight** icon from the desktop.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select the **Remove Windows Spotlight icon from Desktop** checkbox.  
![The Remove Windows Spotlight Icon from Desktop option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-remove-windows-spotlight-icon.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896560/19272" target="_top" id="1896560">
  <img src="//a.impactradius-go.com/display-ad/19272-1896560" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896560/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now the "Learn about this picture" icon will no longer be there. It’s easy to restore that icon with Winaero Tweaker if you ever want to utilize its Spotlight options again. Uncheck the **Remove Windows Spotlight icon from Desktop** checkbox in Winaero Tweaker to bring it back.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of the "Learn About This Picture" Icon on Windows 11

 The "Learn about this picture" icon only adds extra Windows 11 desktop clutter for users who never utilize its options. If you don’t want that additional Spotlight icon on your Windows 11 desktop, it’s straightforward to remove it with a manual registry tweak or Winaero Tweaker.

 The ExplorerPatcher software also includes an option for disabling that icon, along with other settings for making Windows 11 look like Windows 10\.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capturing-content-the-leading-online-television-recordings/"><u>[New] In 2024, Capturing Content The Leading Online Television Recordings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-enabling-autoplay-youtube-videos-in-social-media-network-for-2024/"><u>[Updated] Enabling Autoplay Youtube Videos in Social Media Network for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-pioneers-in-the-digital-realm-vr-past-and-future/"><u>[Updated] In 2024, Pioneers in the Digital Realm VR Past and Future</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-best-choices-essential-support-gear-for-your-gopro-camera/"><u>2024 Approved Best Choices Essential Support Gear for Your GoPro Camera</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-streamlining-in-game-video-production-a-complete-guide/"><u>2024 Approved Streamlining In-Game Video Production A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-methods-to-fire-up-win-11-rdc/"><u>Cutting-Edge Methods to Fire Up Win 11 RDC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-on-iphone-13-pro-max-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud on iPhone 13 Pro Max Safe and Legal</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhancing-your-video-cover-images-updating-techniques-for-fb-for-2024/"><u>Enhancing Your Video Cover Images Updating Techniques for FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-memory-test-failed-errors-in-windows/"><u>Fixing 'Memory Test Failed' Errors in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-infinix-note-30i-by-fonelab-android-recover-call-logs/"><u>How To Restore Missing Call Logs from Infinix Note 30i</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-a-novel-framework-redefining-admin-access-control/"><u>Introducing a Novel Framework: Redefining Admin Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steganography-hiding-zip-in-photos-windows-11/"><u>Mastering Steganography: Hiding ZIP in Photos (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-cant-access-the-source-problem-in-windows-os/"><u>Overcoming Can't Access the Source Problem in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-virtualbox-on-win-starts-with-deps-checks/"><u>Ready, Set, Go! VirtualBox on Win Starts With Deps Checks</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-process-setting-up-msoffice-on-windows-11/"><u>Streamlining the Process: Setting Up MSOffice on Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-top-webm-to-mp3-converters-you-need-to-know-for-2024/"><u>The Top WebM to MP3 Converters You Need to Know for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-cab-file-mystique-its-structure-and-implementation-methods/"><u>Unraveling Windows Cab File Mystique: Its Structure & Implementation Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    