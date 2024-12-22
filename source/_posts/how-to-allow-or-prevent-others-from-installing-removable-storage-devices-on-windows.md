---
title: How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
date: 2024-12-16T17:37:22.927Z
updated: 2024-12-22T17:25:33.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
excerpt: This Article Describes How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
keywords: Permit USB Access,Block Removable USB,USB Device Control,Prevent External Storage,Allow Removable Devices Windows,Disable USB Installation,Secure USB Access Windows
thumbnail: https://thmb.techidaily.com/19529825bc864f6a7105eee056c51264b322fc80a0ff9dab5d25b004c909ef6a.jpg
---

## How to Allow or Prevent Others From Installing Removable Storage Devices on Windows

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

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
<li><a href="https://on-screen-recording.techidaily.com/new-pulling-fun-on-pedal-power-for-2024/"><u>[New] Pulling Fun on Pedal Power for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-enter-virtual-realms-top-10-immersive-videos/"><u>[Updated] 2024 Approved Enter Virtual Realms Top 10 Immersive Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-the-potential-of-instagrams-filters-a-modern-guide-2e23/"><u>[Updated] 2024 Approved Unlocking the Potential of Instagram's Filters - A Modern Guide (2E23)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-youtube-venture-made-easy-the-most-accessible-biz-channel-ideas-ranked/"><u>[Updated] YouTube Venture Made Easy The Most Accessible Biz Channel Ideas Ranked</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-the-fix-overcome-freeze-problems-with-assassins-creed-odyssey-on-pc/"><u>Master the Fix: Overcome Freeze Problems with Assassin's Creed Odyssey on PC</u></a></li>
<li><a href="https://win11.techidaily.com/precision-adjustments-for-top-level-amd-radeon-performance/"><u>Precision Adjustments for Top-Level AMD Radeon Performance</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-method-for-activatingdeactivating-windows-key/"><u>Step-by-Step Method for Activating/Deactivating Windows Key</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-multi-tasking-issue/"><u>Steps to Fix 'Windows Multi-Tasking Issue'</u></a></li>
<li><a href="https://some-techniques.techidaily.com/streamline-your-arch-linux-experience-how-to-prevent-pacman-mishaps-with-smart-mirror-update-automation/"><u>Streamline Your Arch Linux Experience: How to Prevent 'Pacman' Mishaps with Smart Mirror Update Automation</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prevent-auto-start-of-spotify-in-windows/"><u>Techniques to Prevent Auto-Start of Spotify in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-your-taskbar-group-no-more/"><u>Tidy Up Your Taskbar: Group No More</u></a></li>
</ul></div>

