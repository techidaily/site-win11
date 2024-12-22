---
title: Stepwise Guide to Immediate Accessibility of Software Shortcuts
date: 2024-12-15T17:00:38.727Z
updated: 2024-12-22T17:41:27.210Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Guide to Immediate Accessibility of Software Shortcuts
excerpt: This Article Describes Stepwise Guide to Immediate Accessibility of Software Shortcuts
keywords: Quick Shortcut Enabling,Accessible Shortcut Use,Immediate Software Keybinding,Easy Shortcut Setup Guide,Instant Software Commanding,Fast F1+F2 Shortcut Activation,Direct Access Software Keys
thumbnail: https://thmb.techidaily.com/51471ca8a7054ce3eae075b674d92ea208c6509841b94168b4ee14b78abb841b.jpg
---

## Stepwise Guide to Immediate Accessibility of Software Shortcuts

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  
![The Key context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-key-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Input **Edge** as the new registry key’s title.
2. Right-click your **Edge** key and select the **New** \> **Key** options again.
3. Enter **command** to be the new subkey’s name.  
![The command registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-command-key.png)
4. Click File Explorer’s taskbar button.
5. Open Edge’s folder, which has this default path: **C:\\Program Files (x86)\\Microsoft\\Edge\\Application**.

1. Right-click msedge.exe there to select the **Copy as** **path** option shown directly below.  
![The Copy as path option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/copy-as-path-option.png)
2. Then return to the Registry Editor, and select the new **command** key you added.
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

## How to Add Program Shortcuts to the Context Menu With Easy Context Menu

 If you prefer not to manually edit the registry, add program shortcuts to the desktop’s context menu with Easy Context Menu. Easy Context Menu is a freeware third-party app for customizing context menus in Windows 11/10\. It enables you to add and remove shortcuts to and from the context menu. This is how you can add shortcuts for opening programs to Windows 11’s context menu with that software:

1. Open this [Easy Context Menu page](https://www.sordum.org/7615/easy-context-menu-v1-6/) in a web browser and download the app.
2. Extract the **ec\_menu** ZIP archive with a method in this article about [unzipping ZIP files in Windows 11](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).
3. Open the extracted **ec\_menu** folder and double-click the **EcMenu\_x64** file to open Easy Context Menu.
4. Click the **List Editor** button.  
![The List Editor button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/list-editor-button.jpg)
5. Press the **Add new** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Select the application (EXE) file for a program to add to the context menu and click **Open**.
2. Next, select **Desktop Context Menu** on the **Target Context Menu** drop-down menu for the shortcut.  
![The Target Context Menu drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/target-context-menu-drop-down-menu.jpg)
3. Click the **Show at bottom of the menu** radio button.
4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/updated-augment-canon-imagery-unlimited-freebies-and-customized-purchases-for-2024/"><u>[Updated] Augment Canon Imagery Unlimited Freebies & Customized Purchases for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-top-6-networks-fueling-business-innovation-and-growth/"><u>[Updated] Top 6 Networks Fueling Business Innovation and Growth</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-motorola-moto-g23-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Motorola Moto G23 Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-the-world-of-windows-11-the-taskbar-search-basics/"><u>Dive Into the World of Windows 11: The Taskbar Search Basics</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722971900021-download-hp-officejet-5740-printer-drivers-compatible-with-windows-11-10-and-8/"><u>Download HP OfficeJet 5740 Printer Drivers Compatible with Windows 11, 10 & 8</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-gesture-driven-navigation-within-microsoft-edge-windows-11/"><u>Embark on Gesture-Driven Navigation Within Microsoft Edge, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-opening-windows-11s-calculator-feature/"><u>Fast Track to Opening Windows 11'S Calculator Feature</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-personalize-your-windowed-terminal-environment/"><u>How To Personalize Your Windowed Terminal Environment</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-plus-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 15 Plus With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-speech-conversion-for-everyday-use-with-whisper/"><u>Instantaneous Speech Conversion for Everyday Use - With Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-your-auditory-capture-capabilities-with-w11/"><u>Maximizing Your Auditory Capture Capabilities with W11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/roku-vs-amazons-fire-tv-stick-the-definitive-guide-for-savvy-viewers/"><u>Roku Vs. Amazon's Fire TV Stick – The Definitive Guide for Savvy Viewers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/tech-evolution-unveiled-measuring-the-new-samsung-galaxy-s2-3-ultra-against-the-former-marvel-the-s21-ultra/"><u>Tech Evolution Unveiled - Measuring the New Samsung Galaxy S2 3 Ultra Against the Former Marvel, The S21 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-wintoys-leveraging-windows-capabilities/"><u>The Essential Guide to 'WinToys': Leveraging Windows Capabilities</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-oneplus-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on OnePlus Phones</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-list-of-elite-15-inch-laptops-for-2abbreviations2024-professional-insights-and-ratings-pcmag/"><u>Ultimate List of Elite 15-Inch Laptops for 2Abbreviations!2024: Professional Insights and Ratings | PCMag</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-harnessing-the-strength-of-windows-11s-auto-hdr/"><u>Understanding and Harnessing the Strength of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://win11.techidaily.com/win-the-battle-of-content-top-8-videography-tools-unveiled/"><u>Win the Battle of Content - Top 8 Videography Tools Unveiled</u></a></li>
</ul></div>

