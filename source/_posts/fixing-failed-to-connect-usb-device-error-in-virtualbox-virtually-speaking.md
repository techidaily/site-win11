---
title: Fixing Failed to Connect USB Device Error in VirtualBox, Virtually Speaking
date: 2024-11-05T19:11:47.898Z
updated: 2024-11-07T19:59:51.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Failed to Connect USB Device Error in VirtualBox, Virtually Speaking
excerpt: This Article Describes Fixing Failed to Connect USB Device Error in VirtualBox, Virtually Speaking
keywords: USB Error Fix VirtualBox,Connected USB VirtualError,VirtualBox USB Failure Repair,Resolve USB Not Connecting VM,Fix Virtually Speaking USB Issue,Troubleshoot Vbox USB Disconnect,Correct Failed USB in VirtualBox
thumbnail: https://thmb.techidaily.com/6c30e06757b848b8822a0592ade3cd707135548fc958e44df6b196388e83adbe.jpg
---

## Fixing Failed to Connect USB Device Error in VirtualBox, Virtually Speaking

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.

6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.

6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the[official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

## Easily Connect USB Devices to Your Virtual Machine Once More

 VirtualBox needs the extension pack to enable connectivity for USB 2.0 and 3.0 devices. Check your USB devices for errors and verify that they mount properly on the host system. Reinstall USB drivers if you face the error again. Lastly, remove VirtualBox from the system and do a fresh installation.

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
<li><a href="https://vp-tips.techidaily.com/new-maximal-brightness-for-android-videos-explained/"><u>[New] Maximal Brightness for Android Videos Explained</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-self-expression-through-instacraze-100-captivating-captions/"><u>[Updated] Self-Expression Through #InstaCraze 100 Captivating Captions</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-new-ray-ban-stories-details-and-price/"><u>Facebook's New Ray-Ban Stories - Details and Price?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-oppo-find-n3-flip-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Oppo Find N3 Flip to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-intel-rst-rapid-storage-technology-driver-install-boost-your-drive-efficiency-today/"><u>Latest Intel RST (Rapid Storage Technology) Driver Install - Boost Your Drive Efficiency Today!</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-dilemmrances/"><u>Overcoming Windows Exe Opener Dilemmrances</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-start-guide-for-the-latest-wacom-intuos-tablet-drivers-plug-and-play/"><u>Quick-Start Guide for the Latest Wacom Intuos Tablet Drivers – Plug and Play!</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-error-e8024002e/"><u>Steps to Overcome Windows Error E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-picks-of-drawing-apps-for-windows-11-enthusiasts/"><u>The Top 7 Picks of Drawing Apps for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-blue-screen-mysteries-where-are-the-logs/"><u>Unlocking Blue Screen Mysteries: Where Are the Logs?</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-top-11-premium-mobile-apps-for-enhancing-sound-quality/"><u>Updated 2024 Approved Top 11 Premium Mobile Apps for Enhancing Sound Quality</u></a></li>
</ul></div>

