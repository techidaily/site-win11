---
title: Elevate Your Command Prompt Skills with These 20 Essentials
date: 2024-10-06T15:07:43.127Z
updated: 2024-10-09T13:39:11.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Your Command Prompt Skills with These 20 Essentials
excerpt: This Article Describes Elevate Your Command Prompt Skills with These 20 Essentials
keywords: Mastery in CMD,Powering up CMD,Essential CMD Tools,Streamline Command Prompt,Elevate Command Skills,Top CMD Essentials,Boost Cmd Proficiency
thumbnail: https://thmb.techidaily.com/545f7379c0befa5a44cab74ccb395e1f4653a53c66c0461613d4a49d7a7f9a57.jpg
---

## Elevate Your Command Prompt Skills with These 20 Essentials

 The command prompt is slowly disappearing from the Windows interface and for good reasons: CMD commands are an antiquated and mostly unnecessary tool from an era of text-based input. But many commands remain useful, and Windows 8 and 10 even added new features.

 Here we present the essential commands every Windows user must know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Access the Windows Command Prompt

 To open the command prompt in Windows 10 and Windows 11, follow these steps:

1. Press **Windows + R** to open the Run command window.
2. Type "cmd" into the box.
3. Hit **Enter** or click **OK**.

 That's it. For additional ways to access the command prompt, how to run it with administrator privileges, and other tips and tricks, refer to our [beginners guide to the Windows command line](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).

 Curious about the Run command box? We have also compiled a list of [essential Windows Run commands](https://www.makeuseof.com/tag/windows-run-commands-cheat-sheet/) for your convenience.

## Windows Command Prompt Commands

 If you haven't poked around inside Windows' command line, you're missing out. There are lots of handy tools you can use if you know the correct things to type.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Assoc

![Screenshot of Windows command prompt with assoccommand.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/assoccmd.png)

 Most files on Windows are associated with a specific program that is assigned to open the file by default. At times, remembering these associations can become confusing. You can remind yourself by entering the command **assoc** to display a full list of filename extensions and program associations.

 You can also extend the command to change file associations. For example, **assoc .txt=** will change the file association for text files to whatever program you enter after the equal sign. The a**ssoc** command itself will reveal both the extension names and program names, which will help you properly use this command.

 In Windows 10, you can view a more user-friendly interface that also lets you change file type associations on the spot. Head to **Settings (Windows + I) > Apps > Default apps > Choose default app by file type**.

### 2\. Cipher

![Cipher command in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/ciphercmd.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Deleting files on a mechanical hard drive doesn't really delete them at all. Instead, it marks the files as no longer accessible and the space they took up as free. The files remain recoverable until the system overwrites them with new data, which can take some time.

 The cipher command, however, lets you wipe a directory on an NTFS-formatted volume by writing random data to it. To wipe your C drive, for example, you'd use the **cipher /w:d** command, which will wipe free space on the drive. The command does not overwrite undeleted data, so you will not wipe out the files you need by running this command.

 When you run the cipher command by itself, it returns the encryption state of the current directory and the files it contains. Use **cipher /e:<filename>** to encrypt a file, **cipher /c:<filename>** to retrieve information about encrypted files, and **cipher /d:<filename>** to decrypt the selected file. Most of these commands are redundant with the [Windows encryption tool BitLocker](https://www.makeuseof.com/tag/bitlocker-drive-encryption-windows-10/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. File Compare

![File compare command as seen in Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/filecomparecmd.png)

 You can use this command to identify differences in text between two files. It's particularly useful for writers and programmers trying to find small changes between two versions of a file. Simply type **fc** and then the directory path and file name of the two files you want to compare.

 You can also extend the command in several ways. Typing **/b** compares only binary output, **/c** disregards the case of text in the comparison, and **/l** only compares ASCII text.

 So, for example, you could use the following:

`fc /l "C:\Program Files (x86)\example1.doc" "C:\Program Files (x86)\example2.doc"`

 The above command compares ASCII text in two Word documents.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111967/7443" target="_top" id="2111967">
  <img src="//a.impactradius-go.com/display-ad/7443-2111967" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111967/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Ipconfig

![Ipconfig command in Windows command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/ipconfigcmd.png)

 This command relays the IP address that your computer is currently using. However, if you're behind a router (like most computers today), you'll instead receive the local network address of the router.

 Still, ipconfig is useful because of its extensions. **ipconfig /release** followed by **ipconfig /renew** can force your Windows PC into asking for a new IP address, which is useful if your computer claims one isn't available. You can also use **ipconfig /flushdns** to refresh your DNS address. These commands are great if the [Windows network troubleshooter](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) chokes, which does happen on occasion.

### 5\. Netstat

![Netstat command run on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/netstatcmd.png)

 Entering the command **netstat -an** will provide you with a list of currently open ports and related IP addresses. This command will also tell you what state the port is in; listening, established, or closed.

 This is a great command for when you're trying to troubleshoot devices connected to your PC or when you fear a Trojan infected your system and you're trying to locate a malicious connection.

### 6\. Ping

![Ping command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/pingcmd.png)

 Sometimes, you need to know whether packets are making it to a specific networked device. That's where ping comes in handy.

 Typing **ping** followed by an IP address or web domain will send a series of test packets to the specified address. If they arrive and are returned, you know the device is capable of communicating with your PC; if it fails, you know that there's something blocking communication between the device and your computer. This can help you decide if the root of the issue is an improper configuration or a failure of network hardware.

### 7\. PathPing

![Windows command prompt with PathPing command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/pathpingcmd.png)

 This is a more advanced version of ping that's useful if there are multiple routers between your PC and the device you're testing. Like ping, you use this command by typing **pathping** followed by the IP address, but unlike ping, pathping also relays some information about the route the test packets take.

### 8\. Tracert

![Screenshot of Tracert command in Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/tracertcmd.png)

 The **tracert** command is similar to pathping. Once again, type **tracert** followed by the IP address or domain you'd like to trace. You'll receive information about each step in the route between your PC and the target. Unlike pathping, however, tracert also tracks how much time (in milliseconds) each hop between servers or devices takes.

### 9\. Powercfg

![Powercfg command on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/powercfgacmd.png)

 Powercfg is a very powerful command for managing and tracking how your computer uses energy. You can use the command **powercfg hibernate on** and **powercfg hibernate off** to manage hibernation, and you can also use the command **powercfg /a** to view the power-saving states currently available on your PC.

 Another useful command is **powercfg /devicequery s1\_supported**, which displays a list of devices on your computer that support connected standby. When enabled, you can use these devices to bring your computer out of standby, even remotely.

 You can enable this by selecting the device in **Device Manager**, opening its properties, going to the **Power Management** tab, and then checking the **Allow this device to wake the computer** box.

**Powercfg /lastwake** will show you what device last woke your PC from a sleep state. You can use this command to troubleshoot your PC if it seems to wake from sleep at random.

![Powercfg energy command in Administrator command prompt on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/powercfgenergycmd.png)

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the **powercfg /energy** command to build a detailed power consumption report for your PC. The report saves to the directory indicated after the command finishes.

 This report will let you know of any system faults that might increase power consumption, like devices blocking certain sleep modes, or poorly configured to respond to your power management settings.

 Windows 8 added **powercfg /batteryreport**, which provides a detailed analysis of battery use, if applicable. Normally output to your Windows user directory, the report provides details about the time and length of charge and discharge cycles, lifetime average battery life, and estimated battery capacity.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 10\. Shutdown

![Shutdown command on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/shutdowncmd.png)

 Windows 8 introduced the shutdown command that, you guessed it, [shuts down your computer](https://www.makeuseof.com/tag/how-to-shutdown-or-sleep-windows-10-with-a-keyboard-shortcut/).

 This is, of course, redundant with the already easily accessed shutdown button, but what's not redundant is the **shutdown /r /o** command, which restarts your PC and launches the Advanced Start Options menu, which is where you can access Safe Mode and Windows recovery utilities. This is useful if you want to restart your computer for troubleshooting purposes.

### 11\. System File Checker

![System File Checker sfc command options available on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/sfccmd.png)

 System File Checker is an [automatic scan and repair tool](https://www.makeuseof.com/tag/fix-corrupted-windows-10-installation/) that focuses on Windows system files.

 You will need to run the command prompt with administrator privileges and enter the command **sfc /scannow**. If SFC finds any corrupt or missing files, it will automatically replace them using cached copies kept by Windows for this purpose alone. The command can require a half-hour to run on older notebooks.

### 12\. Tasklist

![Tasklist command as shown in Windows command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/tasklistcmd.png)

 You can use the **tasklist** command to provide a current list of all tasks running on your PC. Though somewhat redundant with Task Manager, the command may sometimes find tasks hidden from view in that utility.

 There's also a wide range of modifiers. **Tasklist -svc** shows services related to each task, use **tasklist -v** to obtain more detail on each task, and **tasklist -m** will locate DLL files associated with active tasks. These commands are useful for advanced troubleshooting.

 Our reader Eric noted that you can "get the name of the executable associated with the particular process ID you're interested in." The command for that operation is **tasklist | find \[process id\].**

### 13\. Taskkill

![Taskkill command options available on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/taskkillcmd.png)

 Tasks that appear in the **tasklist** command will have an executable and process ID (a four- or five-digit number) associated with them. You can force stop a program using **taskkill -im** followed by the executable's name, or **taskkill -pid** followed by the process ID. Again, this is a bit redundant with Task Manager, but you can use it to kill otherwise unresponsive or hidden programs.

### 14\. Chkdsk

![Running a chkdsk command to initiate a scan on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/Windows-chckdsk-command.jpg)

 Windows automatically marks your drive for a diagnostic chkdsk scan when symptoms indicate that a local drive has bad sectors, lost clusters, or other logical or physical errors.

 If you suspect your hard drive is failing, you can manually initiate a scan. The most basic command is **chkdsk c:**, which will immediately scan the C: drive, without a need to restart the computer. If you add parameters like /f, /r, /x, or /b, such as in **chkdsk /f /r /x /b c:**, **chkdsk** will also fix errors, recover data, dismount the drive, or clear the list of bad sectors, respectively. These actions require a reboot, as they can only run with Windows powered down.

 If you see **chkdsk** run at startup, let it do its thing. If it gets stuck, however, refer to our [chkdsk troubleshooting article](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/).

### 15\. schtasks

![Scheduling tasks using the Windows schtasks command prompt command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/Windows-schtasks-command.jpg)

**Schtasks** is your command prompt access to the Task Scheduler, one of many underrated Windows administrative tools. While you can use the GUI to manage your scheduled tasks, the command prompt lets you copy&paste complex commands to set up multiple similar tasks without having to click through various options. Ultimately, it's much easier to use, once you've committed key parameters to memory.

 For example, you could schedule your computer to reboot at 11pm every Friday:

`schtasks /create /sc weekly /d FRI /tn "auto reboot computer weekly" /st 23:00 /tr "shutdown -r -f -t 10"`

 To complement your weekly reboot, you could schedule tasks to launch specific programs on startup:

`schtasks /create /sc onstart /tn "launch Chrome on startup" /tr "C:\Program Files (x86)\Google\Chrome\Application\Chrome.exe"`

 To duplicate the above command for different programs, just copy, paste, and modify it as needed.

### 16\. Format

![Windows Command Prompt showing the format command with various parameters.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/07/Windows-Command-Prompt-Format.jpg)

 When you need to [format a drive](https://www.makeuseof.com/tag/format-usb-drive/), you can either use the Windows File Explorer GUI or you can turn to the command prompt. You'll need Administrator rights to use this command. Be sure you specify the volume you want to format, followed by the desired parameters.

 The command below will quick-format the D drive with the [exFAT file system](https://www.makeuseof.com/tag/exfat-better-different-fat32/), with an allocation unit size of 2048 bytes, and rename the volume to "label" (without the quotes).

`format D: /Q /FS:exFAT /A:2048 /V:label`

 You can also use this command to dismount a volume (/X) or, if it's formatted with NTFS, make file compression the default setting (/R). If you're stuck, use format /? to summon help.

### 17\. prompt

![The prompt command in action in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/07/Windows-Command-Prompt-Prompt-Command.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Would you like to customize your command prompt to include instructions or certain information? With the prompt command, you can!

 Try this one:

`prompt Your wish is my command:`

 You can add the current time, date, drive and path, Windows version number, and so much more.

`prompt $t on $d at $p using $v:`

 Type "prompt" to reset your command prompt to default settings or just restart the command prompt. Unfortunately, these settings aren't permanent.

### 18\. cls

 Cluttered up your command prompt window trying out all the commands above? There's one last command you need to know to clean it all up again.

`cls`

 That's all. Bet Marie Kondo didn't know that one.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 19\. Systeminfo

![Systeminfo command as seen on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/systeminfocmd.png)

 This command will give you a detailed configuration overview of your computer. The list covers your operating system and hardware. For example, you can look up the original Windows installation date, the last boot time, your BIOS version, total and available memory, installed hotfixes, network card configurations, and more.

 Use **systeminfo /s** followed by the hostname of a computer on your local network, to remotely grab the information for that system. This may require additional syntax elements for the domain, user name, and password, like this:

`systeminfo /s [host_name] /u [domain]\[user_name] /p [user_password]`

### 20\. Driverquery

![Windows command prompt showing driverquery command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/driverquerycmd.png)

 Drivers remain among the most important software installed on a PC. Improperly configured, missing, or [old Windows drivers](https://www.makeuseof.com/windows-pc-move-drivers-to-new-pc/) can cause all sorts of trouble, so it's good to have access to a list of drivers on your PC.

 That's exactly what the **driverquery** command does. You can extend it to **driverquery -v** to obtain more information, including the directory in which the driver is installed. Unfortunately, this command isn't relevant post Windows 8 or Windows Server 2012\.

## Windows 8 Only: Recovery Image

 Virtually all Windows 8/8.1 computers ship from the factory with a recovery image, but the image may include bloatware you'd rather not have re-installed. Once you've uninstalled the software you can create a new image using the **recimg** command. Entering this command presents a very detailed explanation of how to use it.

 You must have administrator privileges to use the **recimg** command, and you can only access the custom recovery image you create via the Windows 8 **refresh** feature.

 In [Windows 10, system recovery](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has changed. Windows 10 systems don't come with a recovery partition, which makes it more important than ever to back up your data.

## Command and Conquer Your Windows PC

 This article can only give you a taste of what's hidden within the Windows command line. When including all variables, there are literally hundreds of commands. Which ones will turn you into a command prompt master?

 The command prompt is slowly disappearing from the Windows interface and for good reasons: CMD commands are an antiquated and mostly unnecessary tool from an era of text-based input. But many commands remain useful, and Windows 8 and 10 even added new features.

 Here we present the essential commands every Windows user must know.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-streamline-your-video-production-ipad-time-lapse/"><u>[Updated] 2024 Approved Streamline Your Video Production IPad Time-Lapse</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-syncing-soundscapes-to-pixelated-portraits/"><u>[Updated] 2024 Approved Syncing Soundscapes to Pixelated Portraits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-competing-camerasdrones-gopro-max-dji-action-insta360/"><u>[Updated] Competing Cameras/Drones GoPro Max, DJi Action, Insta360</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-charting-growth-the-best-online-stock-yts/"><u>2024 Approved Charting Growth The Best Online Stock YTs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-seamlessly-blend-music-with-visuals-in-premiere-pro/"><u>2024 Approved Seamlessly Blend Music with Visuals in Premiere Pro</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/boosting-views-through-imaginative-video-thumbnails-for-2024/"><u>Boosting Views Through Imaginative Video Thumbnails for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-no-servers-found-8-fixes-in-apex-legends-(156-chars/"><u>Conquer 'No Servers Found': 8 Fixes in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-adjusting-smartfilter-on-modern-windows-version/"><u>Easy Guide: Adjusting SmartFilter on Modern Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/end-the-struggle-winning-over-chrome-file-upload-snags/"><u>End the Struggle: Winning Over Chrome File Upload Snags</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/examining-chatgpts-privacy-concerns/"><u>Examining ChatGPT's Privacy Concerns</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-grandparents-existing-windows-pc-more-accessible/"><u>How to Make Your Grandparents' Existing Windows PC More Accessible</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-best-of-free-and-paid-8-ranked-android-videomosaic-apps-explored/"><u>The Best of Free & Paid #8 Ranked Android Videomosaic Apps Explored</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-beware-troubleshooting-icloud-installation/"><u>Windows Users Beware: Troubleshooting iCloud Installation</u></a></li>
</ul></div>

