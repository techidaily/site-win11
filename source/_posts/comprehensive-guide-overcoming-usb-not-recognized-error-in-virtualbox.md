---
title: "Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox"
date: 2024-09-05T08:43:19.589Z
updated: 2024-09-06T08:43:19.589Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox"
excerpt: "This Article Describes Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox"
keywords: Fix USB Error VirtualBox,Resolve USB Unrecognized VM,Guidance USB Issue Virtual Box,Troubleshoot Unplugged USB VBox,Eliminate 'USB Not Recognized' VBox,Address USB Recognition Failure VBox,Fixing Non-Detected USB in Virtualization
thumbnail: https://thmb.techidaily.com/b815cea54066fecbfdb8d09a425aaf17a53c85016a043f7f7cbe8c68c234f33d.png
---

## Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-navigating-the-maze-fb-messengers-a-video-downloading-guide/"><u>[New] 2024 Approved  Navigating the Maze  FB Messengers - A Video Downloading Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/est-budget-friendly-video-stock-sites-for-2024/"><u>[New] Best Budget-Friendly Video Stock Sites for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-maintaining-image-integrity-effective-instagram-photowatermarking/"><u>[New] In 2024, Maintaining Image Integrity  Effective Instagram Photowatermarking</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-mastering-twitter-archives-for-analysis-for-2024/"><u>[Updated] Mastering Twitter Archives for Analysis for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1-mastering-invisible-cell-duplication-a-step-by-step-guide-to-copying-and-pasting-hidden-data-in-excel/"><u>1. Mastering Invisible Cell Duplication: A Step-by-Step Guide to Copying and Pasting Hidden Data in Excel</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-accessing-global-hitters-the-1-6-short-video-downloaders/"><u>2024 Approved  Accessing Global Hitters  The #1-#6 Short Video Downloaders</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-top-15-free-web-based-image-enhancers-2023/"><u>2024 Approved  Top 15 Free Web-Based Image Enhancers 2023</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-confirmation-signs-that-indicate-receipt-of-your-sms/"><u>Deciphering Confirmation: Signs That Indicate Receipt of Your SMS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/full-application-review-with-az-video-loggers-for-2024/"><u>Full Application Review with AZ Video Loggers for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-honor-90-pro-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Honor 90 Pro Phone Screen?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-honor-by-drfone-android/"><u>How to Bypass FRP on Honor?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/in-depth-evaluation-of-microsoft-windows-10-decoding-the-enigma-of-its-touch-functionality-for-ultimate-user-experience/"><u>In-Depth Evaluation of Microsoft Windows 10: Decoding the Enigma of Its Touch Functionality for Ultimate User Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-ps4-nat-failures-effortlessly-with-this-detailed-tutorial/"><u>Overcome PS4 NAT Failures Effortlessly with This Detailed Tutorial</u></a></li>
<li><a href="https://tech-haven.techidaily.com/starting-out-professional-guide-to-prompt-engineering/"><u>Starting Out: Professional Guide to Prompt Engineering</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-creating-a-workday-function-in-ms-excel/"><u>Step-by-Step Guide: Creating a Workday Function in MS Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-effective-naming-strategies-for-your-microsoft-excel-tables/"><u>Step-by-Step Guide: Effective Naming Strategies for Your Microsoft Excel Tables</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-identifying-and-working-with-combined-cell-structures-in-excel/"><u>Step-by-Step Guide: Identifying and Working with Combined Cell Structures in Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-inserting-and-sign-into-excel-headers-and-footers-for-professional-layouts/"><u>Step-by-Step Guide: Inserting & Sign Into Excel Headers and Footers for Professional Layouts</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-integrating-excel-sheets-into-microsoft-word/"><u>Step-by-Step Guide: Integrating Excel Sheets Into Microsoft Word</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-mastering-cell-movement-techniques-in-microsoft-excel/"><u>Step-by-Step Guide: Mastering Cell Movement Techniques in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-mastering-cell-range-addition-in-microsoft-excel/"><u>Step-by-Step Guide: Mastering Cell Range Addition in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-splitting-a-single-column-into-several-sections-in-microsoft-excel/"><u>Step-by-Step Guide: Splitting a Single Column Into Several Sections in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-transferring-data-from-excel-to-google-sheets/"><u>Step-by-Step Guide: Transferring Data From Excel to Google Sheets</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-tutorial-on-determining-moving-averages-with-microsoft-excel-tools/"><u>Step-by-Step Tutorial on Determining Moving Averages with Microsoft Excel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-tutorial-on-importing-visuals-data-as-cells-values-in-macs-excel-program/"><u>Step-by-Step Tutorial on Importing Visuals Data as Cells Values in Mac's Excel Program</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-spreadsheet-with-ease-unlocking-the-power-of-exceler-sort-functionality/"><u>Streamlining Your Spreadsheet with Ease: Unlocking the Power of Excel'er Sort Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/the-definitive-walkthrough-on-systematically-assessing-formulas-in-ms-excel/"><u>The Definitive Walkthrough on Systematically Assessing Formulas in MS Excel</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-time-stamping-your-photos-for-2024/"><u>The Ultimate Guide to Time-Stamping Your Photos for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-4-best-no-cost-cad-software-a-comprehensive-guide/"><u>Top 4 Best No-Cost CAD Software: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/top-no-cost-substitutes-for-microsoft-excel/"><u>Top No-Cost Substitutes for Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-top-tips-solve-black-ops-4-severe-system-failures/"><u>Troubleshooting Top Tips: Solve Black Ops 4 Severe System Failures</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-converting-and-importing-pdf-files-into-excel-spreadsheets/"><u>Ultimate Guide: Converting and Importing PDF Files Into Excel Spreadsheets</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-eliminating-unwanted-spaces-from-your-data-in-microsoft-excel/"><u>Ultimate Guide: Eliminating Unwanted Spaces From Your Data in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-toggling-scroll-lock-feature-onoff-within-ms-excel/"><u>Ultimate Guide: Toggling Scroll Lock Feature On/Off Within MS Excel</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-how-to-eliminate-a-pivottable-in-ms-excel-effortlessly/"><u>Ultimate Tutorial: How To Eliminate A PivotTable In MS Excel Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-ai-capabilities-with-copilot-pro-in-your-ms-office-suite/"><u>Unleashing AI Capabilities with Copilot Pro in Your MS Office Suite</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-s-demystified-understanding-its-special-editions-and-key-variations-from-the-standard-os/"><u>Windows 11 S Demystified: Understanding Its Special Editions and Key Variations From the Standard OS</u></a></li>
</ul></div>
