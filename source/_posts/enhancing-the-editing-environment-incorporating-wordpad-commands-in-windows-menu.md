---
title: "Enhancing the Editing Environment: Incorporating WordPad Commands in Window's Menu"
date: 2024-10-21T05:23:53.923Z
updated: 2024-10-27T05:07:09.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing the Editing Environment: Incorporating WordPad Commands in Window's Menu"
excerpt: "This Article Describes Enhancing the Editing Environment: Incorporating WordPad Commands in Window's Menu"
keywords: Editing Software Integration,Windows Customization,Wordpad Command Access,Text Editing Enhancement,Menu Interface Upgrade,File Management Improvement,Productivity Software Tweaks
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## Enhancing the Editing Environment: Incorporating WordPad Commands in Window's Menu

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538">
  <img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-tiny-tempo-truths-character-beats-exposed/"><u>[New] 2024 Approved Tiny Tempo Truths Character Beats Exposed</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-verified-posts-do-they-matter-in-2024/"><u>[New] Instagram Verified Posts - Do They Matter, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-youtube-integration-in-instagram-narratives/"><u>[Updated] In 2024, YouTube Integration in Instagram Narratives</u></a></li>
<li><a href="https://win-excellent.techidaily.com/lenovohdd-ssd/"><u>完全指南：将 Lenovo电脑上的HDD 成功转移到 SSD，获取无需重新安装且立即运行的方法</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsofts-commitment-to-long-term-support-of-windows-11/"><u>Decoding Microsoft's Commitment to Long-Term Support of Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevate-your-videography-instagram-captioning-techniques-for-2024/"><u>Elevate Your Videography Instagram Captioning Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-memdump-reports-from-blue-screen-errors/"><u>Exploring Memdump Reports From Blue Screen Errors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-tecno-pova-6-pro-5g-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Tecno Pova 6 Pro 5G Activity | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-motorola-moto-g84-5g-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Motorola Moto G84 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-the-same-wallpaper-on-windows-11-always/"><u>Keeping the Same Wallpaper on Windows 11 Always</u></a></li>
<li><a href="https://app-tips.techidaily.com/mastering-emoji-use-in-android-a-step-by-step-tutorial/"><u>Mastering Emoji Use in Android - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-silenced-pc-audio-sound-restoration-tips/"><u>Reactivate Silenced PC Audio – Sound Restoration Tips</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-smoothing-out-windows-update-problems/"><u>Strategies for Smoothing Out Windows Update Problems</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-the-shadows-of-window-11s-interface/"><u>Uncovering the Shadows of Window 11'S Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-error-files-without-preview-thumbnails/"><u>Windows 11 Error: Files Without Preview Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-gains-additional-lifespan-with-new-yearly-patches/"><u>Windows 11 Gains Additional Lifespan with New Yearly Patches</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-notes-made-simple-no-software-required/"><u>Windows 11 Notes Made Simple, No Software Required</u></a></li>
</ul></div>

