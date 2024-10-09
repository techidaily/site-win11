---
title: How to Address Fabricated Hardware Errors in Windows 11
date: 2024-10-02T03:13:14.657Z
updated: 2024-10-08T23:27:30.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Address Fabricated Hardware Errors in Windows 11
excerpt: This Article Describes How to Address Fabricated Hardware Errors in Windows 11
keywords: Fixing Hardware Errors Win11,Correcting Fabricated Errors MS,Troubleshoot Erroneous WinHardware,Resolve Fake Hardware Windows,Identify False Windows Hardware Error,Stop Phony PC Hardware Issues,Tackle Unreal Hardware in Windows 11
thumbnail: https://thmb.techidaily.com/0f7cc598462e00e671398d3de2bdb7c71a59af5f2607e912d55b8b85ab2b5c83.jpg
---

## How to Address Fabricated Hardware Errors in Windows 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-becoming-an-expert-broadcaster-streaming-high-quality-video-online/"><u>[New] Becoming an Expert Broadcaster Streaming High-Quality Video Online</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-essential-insights-into-using-discord/"><u>[Updated] 2024 Approved Essential Insights Into Using Discord</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-overcoming-wwe-2k23-freezes-in-windows/"><u>Accelerated Action: Overcoming WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-surge-in-cpu-usage-by-wlanext/"><u>Addressing the Surge in CPU Usage by WLANEXT</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-code-0xca00a009/"><u>Addressing Windows Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-monitor-settings-quickly/"><u>Adjusting Monitor Settings Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-game-access-blocks-fixing-unreachable-errors/"><u>Avoiding Game Access Blocks: Fixing Unreachable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-windows-overload-7-ways-to-fix-too-many-requests-error/"><u>Beating Back Window's Overload: 7 Ways to Fix Too Many Requests Error</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-excels-speed-on-windows-pcs/"><u>Boost Your Excel's Speed on Windows PCs</u></a></li>
<li><a href="https://fox-glue.techidaily.com/cutting-edge-techniques-for-rapid-video-playback-for-2024/"><u>Cutting-Edge Techniques for Rapid Video Playback for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/elevate-your-content-mastery-in-live-streaming-screens/"><u>Elevate Your Content Mastery in Live Streaming Screens</u></a></li>
<li><a href="https://extra-hints.techidaily.com/explore-10-open-source-media-engines-for-pc-users/"><u>Explore 10 Open Source Media Engines for PC Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-spark-20-pro-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Spark 20 Pro to PC? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionize-your-workflow-discover-8-key-benefits-of-implementing-chatgpt-vision/"><u>Revolutionize Your Workflow: Discover 8 Key Benefits of Implementing ChatGPT Vision</u></a></li>
<li><a href="https://android-transfer.techidaily.com/two-ways-to-sync-contacts-from-samsung-galaxy-s23plus-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Two Ways to Sync Contacts from Samsung Galaxy S23+ to Gmail | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/wireless-methods-to-mirrorapple-iphone-15-pro-and-ipad-to-fire-stick-with-ease-drfone-by-drfone-ios/"><u>Wireless Methods to MirrorApple iPhone 15 Pro & iPad to Fire Stick With Ease | Dr.fone</u></a></li>
</ul></div>

