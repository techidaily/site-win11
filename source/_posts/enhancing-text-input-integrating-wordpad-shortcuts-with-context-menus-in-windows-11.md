---
title: "Enhancing Text Input: Integrating WordPad Shortcuts with Context Menus in Windows 11"
date: 2024-09-09T22:09:14.758Z
updated: 2024-09-16T19:00:34.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Text Input: Integrating WordPad Shortcuts with Context Menus in Windows 11"
excerpt: "This Article Describes Enhancing Text Input: Integrating WordPad Shortcuts with Context Menus in Windows 11"
keywords: TextInputShortcutsWindows11,EnhancedWordPadControls,ContextMenuIntegrationWin11,ShortcutsForTextEntryWin11,WordPadAdvancedFeaturesWin11,Windows11ShortcutEnhancement,TextInputContextMenusWin11
thumbnail: https://thmb.techidaily.com/84a4620f422e4279d6cc9c20449448701c42416dfe9f4fbdd744755993fb5c2e.png
---

## Enhancing Text Input: Integrating WordPad Shortcuts with Context Menus in Windows 11

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

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-decoding-kinemaster-complexities-best-practices-and-alternative-digital-tools-for-2024/"><u>[New] Decoding KineMaster Complexities Best Practices & Alternative Digital Tools for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-optimizing-social-media-interaction-with-automatic-youtube-video-playback/"><u>[New] Optimizing Social Media Interaction with Automatic Youtube Video Playback</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-crafting-captivating-tiktoks-mastering-the-use-of-pre-designed-templates-for-2024/"><u>[Updated] Crafting Captivating TikToks Mastering the Use of Pre-Designed Templates for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-laugh-out-loud-meme-making-techniques/"><u>[Updated] Laugh Out Loud Meme-Making Techniques</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-top-5-budget-friendly-camcorders-with-hd-quality/"><u>2024 Approved Top 5 Budget-Friendly Camcorders with HD Quality</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-1011-tackling-expiration-notifications/"><u>Easing Windows 10/11: Tackling Expiration Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-lowering-edges-resource-load/"><u>Enhancing Performance: Lowering Edge's Resource Load</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-microsoft-store-error-on-win11-with-code-0x80073cf3/"><u>Fixing the Microsoft Store Error on Win11 with Code 0X80073cf3</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-0x8007045d-blue-screen-issue/"><u>Fixing Windows 11'S 0X8007045D Blue Screen Issue</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11s-screen-configurations-a-guide-to-10-methods/"><u>Mastering Window 11'S Screen Configurations: A Guide to 10 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-application-unable-to-initialize-due-to-missing-qt-plugin/"><u>Overcoming 'Application Unable to Initialize Due to Missing Qt Plugin'</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/playstation-5-compact-edition-latest-updates-on-costs-debut-timeline-and-technical-details/"><u>PlayStation 5 Compact Edition: Latest Updates on Costs, Debut Timeline & Technical Details</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/selecting-your-perfect-monitor-and-recorder-duo/"><u>Selecting Your Perfect Monitor & Recorder Duo</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-renaming-limitations-on-windows-11s-system/"><u>Strategies to Overcome Renaming Limitations on Windows 11'S System</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-analyzing-windows-reliable-tools/"><u>Unleashing Potential: Analyzing Windows' Reliable Tools</u></a></li>
</ul></div>

