---
title: "Optimize Windows Experience: Key CMD Commands for Efficiency"
date: 2024-10-18T05:31:47.397Z
updated: 2024-10-21T05:49:01.724Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Windows Experience: Key CMD Commands for Efficiency"
excerpt: "This Article Describes Optimize Windows Experience: Key CMD Commands for Efficiency"
keywords: WinExperienceOptimization,CommandLineEfficiencyTips,CMDEfficiencyCommands,PerformanceCmdKeys,OptimizeCMDWindows,KeyWindowsCmdImprove,EfficientCommandOptions
thumbnail: https://thmb.techidaily.com/0e8b59a0a7e5a9b9173ae5feaad5ddb56b135eee3ed22a8b3f83cf8fa8dfaeb8.jpg
---

## Optimize Windows Experience: Key CMD Commands for Efficiency

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Command Prompt Commands

 If you haven't poked around inside Windows' command line, you're missing out. There are lots of handy tools you can use if you know the correct things to type.

### 1\. Assoc

![Screenshot of Windows command prompt with assoccommand.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/assoccmd.png)

 Most files on Windows are associated with a specific program that is assigned to open the file by default. At times, remembering these associations can become confusing. You can remind yourself by entering the command **assoc** to display a full list of filename extensions and program associations.

 You can also extend the command to change file associations. For example, **assoc .txt=** will change the file association for text files to whatever program you enter after the equal sign. The a**ssoc** command itself will reveal both the extension names and program names, which will help you properly use this command.

 In Windows 10, you can view a more user-friendly interface that also lets you change file type associations on the spot. Head to **Settings (Windows + I) > Apps > Default apps > Choose default app by file type**.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Cipher

![Cipher command in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/ciphercmd.png)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Deleting files on a mechanical hard drive doesn't really delete them at all. Instead, it marks the files as no longer accessible and the space they took up as free. The files remain recoverable until the system overwrites them with new data, which can take some time.

 The cipher command, however, lets you wipe a directory on an NTFS-formatted volume by writing random data to it. To wipe your C drive, for example, you'd use the **cipher /w:d** command, which will wipe free space on the drive. The command does not overwrite undeleted data, so you will not wipe out the files you need by running this command.

 When you run the cipher command by itself, it returns the encryption state of the current directory and the files it contains. Use **cipher /e:<filename>** to encrypt a file, **cipher /c:<filename>** to retrieve information about encrypted files, and **cipher /d:<filename>** to decrypt the selected file. Most of these commands are redundant with the [Windows encryption tool BitLocker](https://www.makeuseof.com/tag/bitlocker-drive-encryption-windows-10/).

### 3\. File Compare

![File compare command as seen in Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/filecomparecmd.png)

 You can use this command to identify differences in text between two files. It's particularly useful for writers and programmers trying to find small changes between two versions of a file. Simply type **fc** and then the directory path and file name of the two files you want to compare.

 You can also extend the command in several ways. Typing **/b** compares only binary output, **/c** disregards the case of text in the comparison, and **/l** only compares ASCII text.

 So, for example, you could use the following:

`fc /l "C:\Program Files (x86)\example1.doc" "C:\Program Files (x86)\example2.doc"`

 The above command compares ASCII text in two Word documents.

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

 You can use the **powercfg /energy** command to build a detailed power consumption report for your PC. The report saves to the directory indicated after the command finishes.

 This report will let you know of any system faults that might increase power consumption, like devices blocking certain sleep modes, or poorly configured to respond to your power management settings.

 Windows 8 added **powercfg /batteryreport**, which provides a detailed analysis of battery use, if applicable. Normally output to your Windows user directory, the report provides details about the time and length of charge and discharge cycles, lifetime average battery life, and estimated battery capacity.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 14\. Chkdsk

![Running a chkdsk command to initiate a scan on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/Windows-chckdsk-command.jpg)

 Windows automatically marks your drive for a diagnostic chkdsk scan when symptoms indicate that a local drive has bad sectors, lost clusters, or other logical or physical errors.

 If you suspect your hard drive is failing, you can manually initiate a scan. The most basic command is **chkdsk c:**, which will immediately scan the C: drive, without a need to restart the computer. If you add parameters like /f, /r, /x, or /b, such as in **chkdsk /f /r /x /b c:**, **chkdsk** will also fix errors, recover data, dismount the drive, or clear the list of bad sectors, respectively. These actions require a reboot, as they can only run with Windows powered down.

 If you see **chkdsk** run at startup, let it do its thing. If it gets stuck, however, refer to our [chkdsk troubleshooting article](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 17\. prompt

![The prompt command in action in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/07/Windows-Command-Prompt-Prompt-Command.jpg)

 Would you like to customize your command prompt to include instructions or certain information? With the prompt command, you can!

 Try this one:

`prompt Your wish is my command:`

 You can add the current time, date, drive and path, Windows version number, and so much more.

`prompt $t on $d at $p using $v:`

 Type "prompt" to reset your command prompt to default settings or just restart the command prompt. Unfortunately, these settings aren't permanent.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 18\. cls

 Cluttered up your command prompt window trying out all the commands above? There's one last command you need to know to clean it all up again.

`cls`

 That's all. Bet Marie Kondo didn't know that one.

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-streamline-caption-insertion-photos-app-tutorials-for-win-11/"><u>[New] 2024 Approved Streamline Caption Insertion Photos App Tutorials for WIN 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-picture-perfect-pairings-expert-comparison-of-top-8k-televisions/"><u>[New] In 2024, Picture Perfect Pairings Expert Comparison of Top 8K Televisions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-highlighting-the-best-of-fig-skates-2022/"><u>[Updated] Highlighting the Best of Fig Skates 2022</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/3g2mp3-movavi/"><u>3G2ビデオからMP3へ自由に変換: Movaviの無料オンラインツールの利用ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/actionable-guide-xml-to-srt-conversion-techniques/"><u>Actionable Guide XMl-to-Srt Conversion Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-techniques-to-prevent-disconnect-errors-during-discord-setup/"><u>Avoidance Techniques to Prevent Disconnect Errors During Discord Setup</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oppo-k11x-by-drfone-android/"><u>How to Bypass FRP on Oppo K11x?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-easily-unlock-sony-screen-by-drfone-android/"><u>In 2024, How To Easily Unlock Sony Screen?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-8-plus-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win-rpc-failures-five-must-try-fixes/"><u>Navigating Win RPC Failures: Five Must-Try Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-techniques-for-unlocking-your-system-writable-files/"><u>Powerful Techniques for Unlocking Your System' Writable Files</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-gtfo-software-crashes-a-step-by-step-guide/"><u>Resolving GTFO Software Crashes: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-windows-dism-hurdle-error-0x800f082f/"><u>Steering Clear of Windows' DISM Hurdle: Error 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-how-to-engage-windows-11s-system-restore-mechanism/"><u>Step-by-Step: How to Engage Windows 11'S System Restore Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-a-guide-to-idle-shutdown-in-windows-11/"><u>Streamline System Use: A Guide to Idle Shutdown in Windows 11</u></a></li>
</ul></div>

