---
title: "Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar"
date: 2024-06-25T11:28:02.816Z
updated: 2024-06-26T11:28:02.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar"
excerpt: "This Article Describes Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar"
keywords: User UX Elevation,WordPad Shortcuts Use,Menu Enhancement Tips,Accessing Toolbar Quickly,Streamline Text Editing,Integrating Menu Bar,Keyboard Navigation Optimization
thumbnail: https://thmb.techidaily.com/48491c0a3b929750d09e0d3e1dede43e654117023e73246a1998baa96a66f8fd.jpg
---

## Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

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
<li><a href="https://win11.techidaily.com/optimizing-system-resources-through-edges-webview2-controls/"><u>Optimizing System Resources Through Edge's WebView2 Controls</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-lifelong-deletion-functions-on-windows-1011-desktop/"><u>Configuring Lifelong Deletion Functions on Windows 10/11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-email-banners-in-windows-os/"><u>Solving Disabled Email Banners in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-with-windows-11-rebuild/"><u>New Horizons with Windows 11 Rebuild</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-integrating-social-networks-discord-tutorial/"><u>[Updated] 2024 Approved  Integrating Social Networks  Discord Tutorial</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-android-screen-recording-tutorial-essentials/"><u>[New] In 2024, Android Screen Recording Tutorial Essentials</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/mac-compatible-vllo-download-install-and-explore-alternatives-for-2024/"><u>Mac Compatible VLLO Download, Install, and Explore Alternatives for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-everything-from-apple-iphone-xs-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Everything from Apple iPhone XS Max to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/cloud-based-stop-motion-animation-features-best-practices-and-competitors/"><u>Cloud-Based Stop Motion Animation Features, Best Practices, and Competitors</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-step-by-step-techniques-for-clear-screen-captures-on-imac-for-2024/"><u>[Updated] Step-by-Step Techniques for Clear Screen Captures on iMac for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pinnacle-virtual-lecture-identifier/"><u>2024 Approved  Pinnacle Virtual Lecture Identifier</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-bring-back-the-buzz-transforming-previous-media-with-ig-filters/"><u>2024 Approved  Bring Back the Buzz  Transforming Previous Media with IG Filters</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-cutting-through-the-noise-posting-twitter-videos-on-instagram/"><u>[Updated] 2024 Approved  Cutting Through the Noise  Posting Twitter Videos on Instagram</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-your-videos-first-moment-with-these-trendy-intros/"><u>2024 Approved  Mastering Your Video's First Moment with These Trendy Intros</u></a></li>
</ul></div>
