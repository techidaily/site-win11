---
title: "Windows 11: Guide to Security-Focused Dialogue Shortcuts"
date: 2024-06-25T09:42:52.063Z
updated: 2024-06-26T09:42:52.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Guide to Security-Focused Dialogue Shortcuts"
excerpt: "This Article Describes Windows 11: Guide to Security-Focused Dialogue Shortcuts"
keywords: Windows 11 Secure Keyboard,W11 Safety Shortcuts,Protecting PC with W11,Security in W11 Shortcuts,W11 Safe Function Keys,Enhancing W11 Safety,W11 Secure Commands Guide
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## Windows 11: Guide to Security-Focused Dialogue Shortcuts

 After inserting an external USB flash drive, you can select an option on Windows 11’s system tray to eject it. The eject option is available to enable users to remove external storage devices safely. Data can get corrupted if you remove a USB drive still in use.

 The Safely Remove Hardware dialog is a window that displays all connected USB devices and enables you to stop them for safe ejection. That dialog is accessible with a Run command, but you can set up shortcuts for opening it with the methods below.

## How to Set Up a "Safely Remove Hardware" Desktop Shortcut

 The Safely Remove Hardware dialog has a long Run command that’s not easy to remember. To make that feature more directly accessible, you can create a desktop shortcut based on its command. Then you can also turn that shortcut into a taskbar, Start menu, or keyboard one. This is how to set up a Safely Remove Hardware dialog desktop shortcut in Windows 11:

1. Click anywhere on the desktop wallpaper with the mouse’s right button to select**New** and**Shortcut** .  
![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)
2. Input this command within the location box:  
`rundll32.exe shell32.dll,Control_RunDLL hotplug.dll`
3. Select**Next** to view the shortcut name box.
4. Delete the text in the box, and input**Safely Remove Hardware** to replace it.
5. Click**Finish** to add the Safely Remove Hardware desktop shortcut.

 Now try opening the Safely Remove Hardware window with the shortcut. Double-clicking the**Safely Remove Hardware** shortcut should open the window shown directly below. Select a listed USB device you want to remove there and click**Stop** . Clicking that button opens a**Stop** hardware device window on which you can select to stop a device before removing it.

![The Safely Remove Hardware dialog window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-devices-window.jpg)

 That**Stop** option is not entirely the same as an ejection one. Selecting**Eject Portable** in the system tray will merely tell you if the device is still in use or safe to remove. Clicking**Stop** will stop what’s using the drive to make the device free for removal.

![The Eject Portable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/eject-portable-option.jpg)

 The Safely Remove Hardware window also enables you to view properties for listed devices. To do so, select a device and click the**Properties** button. That will bring up a window that includes general, event, and driver details for the device.

 The Safely Remove Hardware desktop shortcut will be blank by default. However, you can add an icon to it by following the instructions in our[guide for customizing Windows 11/10 icons](https://www.makeuseof.com/tag/customize-icon-windows/) .

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our[how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

## How to a Set Up a "Safely Remove Hardware" Context Menu Shortcut

 The context menu is an out-of-the-way place to stick shortcuts for opening things. Adding a Safely Remove Hardware option there will enable you to access that dialog by right-clicking the desktop area. Such a shortcut will probably be preferable for users who prefer to minimize desktop and taskbar clutter.

 However, this final method for creating a Safely Remove Hardware shortcut involves editing the registry because Windows 11 doesn’t include any editing feature for customizing the context menu. The registry tweak is a relatively straightforward one to apply that adds a couple of new keys. Follow these steps exactly as specified to add a**Safely Remove Hardware** option to the context menu:

1. Press**Start** (the taskbar menu button) and click inside the search box.
2. Enter**Registry Editor** inside the file search tool and select to open that app from the results.
3. Delete whatever text is in Registry Editor’s address bar, and input this key location there:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Then right-click the Shell key and select**New** to bring up a context menu submenu.
5. Select the**Key** option to add a new registry entry.

1. Type**Safely Remove Hardware** inside the key’s text box.
2. Then right-click the newly added**Safely Remove Hardware** registry entry and select the**New** \>**Key** options.
3. Input**command** to be the second key’s title.
4. Select the newly added**command** registry entry and double-click its**(Default)** string value.
5. Then input the following Safely Remove Hardware dialog location inside the**Data value** box:  
`C:\\Windows\\System32\\control.exe hotplug.dll`
6. Click**OK** to confirm the new value.

 Now you can have a look at what you’ve just added to Windows 11’s context menu. Right-click an empty part of your desktop area to select Show more options, which opens the secondary classic menu. Select the**Safely Remove Hardware** option on the classic context menu to bring up that window.

![The Safely Remove Hardware context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-option.jpg)

 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

## Utilize the Safely Remove Hardware Dialog Faster on Windows

 Creating a Safely Remove Hardware shortcut with any method above will make that dialog window more accessible whenever you need to remove a device. That dialog provides a handy alternative way for users to safely remove USB drives with additional options for viewing device details. You can use that dialog to view properties for connected drives and select to stop them so they can be removed without corrupting data.

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
<li><a href="https://win11.techidaily.com/fixing-windows-1011s-audacity-audio-connection-failures/"><u>Fixing Windows 10/11’S Audacity Audio Connection Failures</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ical-integration-on-windows-11-systems/"><u>Mastering iCal Integration on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-approach-to-disable-unnecessary-windows-11-services/"><u>Proactive Approach to Disable Unnecessary Windows 11 Services</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-non-existent-drive-letters-on-windows-causes-corrections/"><u>Understanding Non-Existent Drive Letters on Windows: Causes, Corrections</u></a></li>
<li><a href="https://win11.techidaily.com/easy-auto-shutdown-techniques-for-idle-windows-pcs/"><u>Easy Auto-Shutdown Techniques for Idle Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-the-hidden-pathway-how-to-seamlessly-integrate-youtube-content-onto-facebook/"><u>[Updated] In 2024, The Hidden Pathway  How to Seamlessly Integrate YouTube Content Onto Facebook</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-realme-c53-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Realme C53 Phone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/steps-for-controlling-video-comment-settings-in-youtube/"><u>Steps for Controlling Video Comment Settings in YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-introduction-to-adding-new-fonts-in-ae/"><u>[Updated] Introduction to Adding New Fonts in AE</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-video-editing-for-virality-a-comprehensive-guide-to-instagram-success/"><u>[Updated] 2024 Approved  Video Editing for Virality  A Comprehensive Guide to Instagram Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hottest-youtube-music-playback-responses-23/"><u>[Updated] 2024 Approved  Hottest YouTube Music Playback Responses '23</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-maximize-webcam-capabilities-in-mac-os/"><u>[New] Maximize Webcam Capabilities in Mac OS</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-crafting-shareable-moments-a-guide-to-enhanced-viewership-in-15-second-videos/"><u>In 2024, Crafting Shareable Moments  A Guide to Enhanced Viewership in 15-Second Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-childhood-wings-5-best-drone-companions/"><u>[New] Childhood Wings  5 Best Drone Companions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-instant-title-insertion-for-your-videos-on-windows-photos/"><u>In 2024, Instant Title Insertion for Your Videos on Windows Photos</u></a></li>
</ul></div>
