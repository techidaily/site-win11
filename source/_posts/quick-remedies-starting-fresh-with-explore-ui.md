---
title: "Quick Remedies: Starting Fresh with Explore UI"
date: 2025-01-22T07:12:30.764Z
updated: 2025-01-24T19:30:51.843Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Remedies: Starting Fresh with Explore UI"
excerpt: "This Article Describes Quick Remedies: Starting Fresh with Explore UI"
keywords: Quick Fixes,Fresh UI Tips,UI Improvement Ideas,Easy UI Upgrades,Fast UI Revamping,Novel UI Enhancements,Streamlined User Interface
thumbnail: https://thmb.techidaily.com/e8d04162a361e101c6d5fe7cceb85fa9aae79c5e50584f8b8db01d521f6c1c1d.jpg
---

## Quick Remedies: Starting Fresh with Explore UI

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is File Explorer in Windows?](#what-is-file-explorer-in-windows)
* [Restart File Explorer Using Task Manager](#restart-file-explorer-using-task-manager)
* [Exit Explorer and Manually Restart It (Windows 10 Only)](#exit-explorer-and-manually-restart-it-windows-10-only)
* [Restart Windows Explorer Manually Using Command Prompt](#restart-windows-explorer-manually-using-command-prompt)
* [Use a Batch File to Restart File Explorer in Windows](#use-a-batch-file-to-restart-file-explorer-in-windows)

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

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
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-how-to-harness-the-power-of-obs-on-android-gadgets/"><u>[Updated] 2024 Approved How to Harness the Power of OBS on Android Gadgets</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-depth-examination-androids-photography-solution-lightroom-for-2024/"><u>[Updated] In-Depth Examination Android's Photography Solution, Lightroom for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-the-full-capabilities-of-morphvox-voice-alteration/"><u>[Updated] Unlocking the Full Capabilities of MorphVOX Voice Alteration</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-cost-effective-pc-video-archive-tools/"><u>2024 Approved Cost-Effective PC Video Archive Tools</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-pinnacle-cloud-space-for-enterprise-success/"><u>2024 Approved Pinnacle Cloud Space for Enterprise Success</u></a></li>
<li><a href="https://win11.techidaily.com/3-essential-methods-to-enable-telnet-in-win11/"><u>3 Essential Methods to Enable Telnet in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-task-management-in-microsoft-project/"><u>Accelerate Task Management in Microsoft Project</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-email-checking-add-gmail-to-your-windows-side/"><u>Accelerated Email Checking: Add Gmail to Your Window's Side</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-ide-performance-android-studio-tips/"><u>Accelerating IDE Performance: Android Studio Tips</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-odds-tackling-installer-errors-in-win11-successfully/"><u>Beating the Odds: Tackling Installer Errors in Win11 Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakdown-is-windows-hello-still-reliable/"><u>Biometric Breakdown: Is Windows Hello Still Reliable?</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-w11-0x8004def5-onedrive-fixes/"><u>Breaking Down the W11 0X8004DEF5 Onedrive Fixes</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210055275-9781989838341-guided-mindfulness-meditations-for-deep-sleep-overcoming-anxiety-stress-relief/"><u>Guided Mindfulness Meditations for Deep Sleep, Overcoming Anxiety & Stress Relief | Free Book</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-xs-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/netflix-connectivity-fixes-for-xbox-players-back-online/"><u>Netflix Connectivity Fixes for Xbox Players – Back Online!</u></a></li>
<li><a href="https://win11.techidaily.com/1719360575372-trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/uniting-networks-sharing-fb-vids-on-whatsapp-chat-for-2024/"><u>Uniting Networks Sharing FB Vids on WhatsApp Chat for 2024</u></a></li>
</ul></div>

