---
title: Guide to Fix 'Unstoppable Volume Controller' On Windows
date: 2024-09-26T21:39:28.652Z
updated: 2024-09-28T21:18:08.188Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Fix 'Unstoppable Volume Controller' On Windows
excerpt: This Article Describes Guide to Fix 'Unstoppable Volume Controller' On Windows
keywords: Unstop Volume Control Guide,Win Fix 'Volume Issue',Stop PC 'Volume Maker',Resolve Volume Freeze Windows,Stopping PC Volume Error,Fixing Volume Controller WIN,End Unstoppable VC on PC
thumbnail: https://thmb.techidaily.com/cfaa471734b434d1f940355dfb1b76c8db9d162f456d0da8fe799d1c6ecd8924.jpg
---

## Guide to Fix 'Unstoppable Volume Controller' On Windows

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  
![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-estimate-income-from-youtube-video-snippets-for-2024/"><u>[New] How to Estimate Income From YouTube Video Snippets for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-budget-friendly-obs-configuration-guide/"><u>[New] In 2024, Budget-Friendly OBS Configuration Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-pureimagezone-premium-tool-to-remove-backgrounds-for-2024/"><u>[New] PureImageZone Premium Tool to Remove Backgrounds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-substitutes-for-bitlocker-in-winxp-systems/"><u>10 Substitutes for BitLocker in WinXP Systems</u></a></li>
<li><a href="https://win11.techidaily.com/10-trusted-secure-windows-software-download-spots/"><u>10 Trusted, Secure Windows Software Download Spots</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-tips-for-srt-file-production-mastery/"><u>2024 Approved In-Depth Tips for SRT File Production Mastery</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-tips-and-tricks-for-editing-your-way-to-greatness-in-facebook-reels/"><u>2024 Approved Tips and Tricks for Editing Your Way to Greatness in Facebook Reels</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-sam-mismanagement/"><u>Addressing Windows SAM Mismanagement</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-network-settings-with-precision-win11/"><u>Adjusting Network Settings with Precision (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-slowness-essential-tricks-for-windows-11s-pace/"><u>Beat the Slowness: Essential Tricks for Windows 11'S Pace</u></a></li>
<li><a href="https://win11.techidaily.com/beware-the-traps-in-budget-friendly-windows-license-purchases/"><u>Beware the Traps in Budget-Friendly Windows License Purchases</u></a></li>
<li><a href="https://some-techniques.techidaily.com/evaluating-wirecast-other-options-to-consider-for-2024/"><u>Evaluating WireCast Other Options To Consider for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-seamlessly-update-your-asus-computers-touchpad-driver-for-optimal-performance-on-windows-10/"><u>How to Seamlessly Update Your ASUS Computer's Touchpad Driver for Optimal Performance on Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-samsung-galaxy-s23-tactical-edition-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Samsung Galaxy S23 Tactical Edition Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719251209823-overcome-wwinplusprint-hurdles-for-seamless-operations-in-windows/"><u>Overcome WWin+Print Hurdles for Seamless Operations in Windows.</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-itel-a60-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Itel A60</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    