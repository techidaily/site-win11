---
title: "Accessing Windows 11'S Security: Six Pathways for Safe Mode"
date: 2024-07-13T09:45:52.125Z
updated: 2024-07-14T09:45:52.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accessing Windows 11'S Security: Six Pathways for Safe Mode"
excerpt: "This Article Describes Accessing Windows 11'S Security: Six Pathways for Safe Mode"
keywords: Windows 11 Secure Mode,Safe Mode Access Guide,Safe Boot Options Win11,Secure Startup Procedures,Entering Win11 Safe Mode,Win11 Security Entryways,Secure Windows 11 Boot Paths
thumbnail: https://thmb.techidaily.com/9eb4aae367e8d7c80e3c075f7bffa3926b7f3e2ef755ab623092abbe72eca2c0.jpg
---

## Accessing Windows 11'S Security: Six Pathways for Safe Mode

### Key Takeaways

* Boot into safe mode using System Configuration for easy setup and boot customization.
* Access safe mode via the Settings app for a straightforward method to reboot in safe mode.
* To boot into safe mode from the lock screen, restart your PC and navigate through the Windows Recovery Environment.

 In safe mode, Windows starts with a basic set of drivers and files essential to run the system. Everything else, including start-up apps, networking, and Command Prompt, is disabled in safe mode. This helps you determine if an external hardware driver or program conflict is causing your system to malfunction.

 There are different types of safe modes and many ways to access them. If you need to diagnose your PC, here is how to boot into safe mode in Windows 11 on a working or non-booting computer.

## The Different Types of Safe Mode and When to Use Them

 There are three types of safe mode options available in advanced boot options:

* **Safe Mode:** Windows starts with a minimal set of drivers and files and disables everything else.
* **Safe Mode with Networking:** Windows starts with a basic set of drivers in addition to the network drivers necessary to connect to a network or the Internet. Wi-Fi connectivity is not available in this mode.
* **Safe Mode with Command Prompt:** For advanced users who want to access the Command Prompt in safe mode and don’t need the Windows graphical interface.

## 1\. Boot into Safe Mode Using the Microsoft System Configuration Utility

 You can boot into safe mode using the System Configuration utility, which is less intimidating than other methods. Another advantage is that it allows you to configure your desired safe mode (Standard, Networking, Command Prompt) before restarting and also automatically set your computer to boot into safe mode on the next restart.

 To boot into safe mode using the System Configuration utility:

1. Press **Win + R** to open **Run**, type **msconfig** and click **OK**. Alternatively, click **Start**, type **System Configuration** and open the best matching result.
2. In the **System Configuration** window, open the **Boot** tab.  
![Windows 11 Dekstop Showing the Microsoft System Configuration Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility.png)
3. Under **Boot options**, select **Safe boot**. By default, the default mode is set to **Minimal**. Depending on your requirements, you can switch between **Alternate Shell (Command Prompt)**, **Network** or **Active Directory repair** options.  
![Windows 11 Desktop Showing the Microsoft System Configuration Utility Advanced Boot options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility-advanced-boot-options.png)
4. The **Advanced options** dialog offers more granular control over the processor and memory usage. Leave it as default if you don’t know what you are doing.
5. Once done, click **OK** and **Apply** to save the changes.
6. Restart your computer to boot into safe mode.

## 2\. How to Boot Into Safe Mode Using the Settings App

 Another way to boot into safe mode is via the Settings app. You can use the Recovery option to access the Advanced Start-up settings and then boot into safe mode. Here’s how to do it:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on the **Recovery option.**
3. Click the **Restart** now button for **Advanced startup.**  
![Windows 11 recovery startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-11-recovery-startup-settings.png)
4. Click the **Restart now** button to confirm the action.
5. In the **Choose an option** screen, click **Troubleshoot**.  
![Troubleshoot menu in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/bootable-usb-troubleshoot-windows-recpvery-environment.png)
6. Next, click **Advanced options.**  
![Troubleshoot showing Advanced options in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-troubleshoot-windows-recovery-environment.png)
7. Click **Start-up settings** under Advanced options.  
![Advanced options for startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-up-settings-advanced-options.png)
8. Click the **Restart** button to confirm and open the start-up-up settings. Windows will populate your screen with multiple numbered options.  
![Startup settings in the Windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/startup-settings-windows-recovery-environemnt.png)
9. Press **4, 5 or 6** depending on the safe mode type you want to boot into. Windows will now restart and boot into safe mode.

 To exit safe mode, restart your PC and Windows will boot normally.

## 3\. How to Boot Into Safe Mode From the Lock-Screen

![Booting into safe mode from the lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-into-safe-mode-from-lock-screen.png)

 If you have [forgotten your Windows password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/) or can't log in, you can boot into safe mode from the lock screen itself. Here’s how to do it:

1. Restart your PC.
2. When at the lock screen, press any key to see your logon screen.
3. Click the **Power/Shutdown** button. Then, press and hold the **Shift** key and click **Restart**. If prompted for confirmation, click **Restart anyway**.
4. Your computer will restart and show the Windows Recovery Environment. From here, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
5. Press **4** to restart and boot into safe mode.

 Alternatively, you also do this from the desktop**. Click Start > Power** and while holding the **Shift** key, click **Restart**.

## 4\. Boot Into Safe Mode Using Command Prompt and WinRE

 In addition to the above steps, you can use Command Prompt to restart your computer with advanced options enabled. Once in Windows RE, you can navigate to Startup Settings and access safe mode. Here's how to do it.

1. Press the **Win** key, type **cmd**, then right-click on **Command Prompt** and choose **Run as administrator**.  
![Shutdown command in a Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-command-prompt-showing-the-restart-with-advanced-option-command.png)
2. In the Command Prompt window, type the following command and press Enter to execute:  
`shutdown.exe /r /o`
3. Click the **Close** button when a pop-up dialog appears.  
![Windows 11 prompt to restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/safe-mode-windows-11-command-prompt.png)
4. That’s it. Windows will restart in one minute. So, wait till the PC restarts and boots into the Windows Recovery Environment.
5. In Windows RE, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
6. After the restart, press the appropriate key to boot into safe mode.

## 5\. Boot Into Safe Mode When Windows is Not Booting

 If [Windows is not booting](https://www.makeuseof.com/tag/windows-10-wont-boot/), or you can't see the login screen, you can still access safe mode using the advanced boot option by triggering the Windows Recovery Environment.

 While you can press the F8 key repeatedly during the boot process to access advanced boot options, it doesn't always work. Instead, you can force [Windows to boot into the Windows Recovery Environment](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) by deliberately force shutting down your computer a few times during startup.

 After two consecutive failed attempts, Windows will automatically start WinRE and give access to advanced boot options. To do this:

1. Shut down your computer.
2. Press the **Power** button to power on your PC.
3. When it starts loading, press and hold the Power button to force a shutdown. Repeat the steps to abruptly shut down your computer again.
4. At the third attempt, press the power button and let Windows load and boot into Windows Recovery Environment.
5. Under **Choose an option,** click **Troubleshoot**.
6. Then go to **Advanced options > Start-up settings > Restart.**
7. After the restart, press **4,5 or 6** to boot into safe mode with different options.

## 6\. Perform a Safe Boot Using a Bootable USB Drive and Command Prompt

 If your computer is experiencing a critical system failure or startup issues and cannot boot normally, you can perform a safe boot using a bootable USB drive.

 If you don’t have installation media, follow our guide to [create a Windows 11 bootable USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you've created got a bootable drive, continue with the steps below:

1. Connect the bootable USB drive to your computer.
2. Press the **Power** button and start pressing the **F9** key on an HP laptop or **F2** on a Lenovo laptop to bring up the Boot Manager. The Boot Manager key can vary depending on your laptop/motherboard manufacturer.  
![Booting Windows from a USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-from-USB-drive.jpg)
3. In the Boot Manager, use the arrow keys to select the bootable USB drive as the boot device. Press **Enter** to select the option to open the Windows Setup wizard.
4. In the **Windows Setup** wizard, click on **Next**.  
![repair computer bootable USb windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/repair-computer-bootable-USb-windows-11.png)
5. Then, click on **Repair your computer** in the bottom left corner to enter **Windows RE.**

1. Under **Choose an option,** go to **Troubleshoot > Command Prompt.**  
![Advanced options showing the command prompt option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-command-prompt.png)
2. In the Command Prompt window, type the following command and press enter to change Boot Configuration Data (BCD) file.  
`bcdedit /set {default} safeboot minimal`
3. Alternatively, to enable safe boot with networking, type the following command:  
`bcdedit /set {default} safeboot network`
4. If successful, you will see the **operation completed successfully message.**  
![Clean boot command prompt from a bootable USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/clean-boot-command-prompt-bootable-usb-drive.png)
5. Type **exit** and press **Enter** to close Command Prompt.
6. In Windows RE, click **Continue**. Windows will now restart in safe boot mode.

## How to Exit Safe Mode in Windows 11

![Exiting Safe Mode in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/exit-safe-mode-windows-11.png)

 To exit safe mode, restart your PC and wait for it to restart normally. However, if your computer continues to boot into safe mode, follow these steps to exit safe mode manually.

1. Press **Win + R** to open **Run**.
2. Type **msconfig** and click **OK** to open the **System Configuration.**
3. In the **Boot** tab, uncheck the **Safe boot** option.
4. Click **Apply** and **OK** to save the changes. Restart your PC, and it should start normally.

 Safe mode is a handy diagnostic space in Windows. It allows you to access critical drivers and is ideal for diagnosing your system for hardware issues. However, if you want to troubleshoot third-party vendor software-related issues, [try a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/). It lets you load your system with a minimal set of drivers and startup apps to isolate the cause triggering the conflict.

 In safe mode, Windows starts with a basic set of drivers and files essential to run the system. Everything else, including start-up apps, networking, and Command Prompt, is disabled in safe mode. This helps you determine if an external hardware driver or program conflict is causing your system to malfunction.

 There are different types of safe modes and many ways to access them. If you need to diagnose your PC, here is how to boot into safe mode in Windows 11 on a working or non-booting computer.

## The Different Types of Safe Mode and When to Use Them

 There are three types of safe mode options available in advanced boot options:

* **Safe Mode:** Windows starts with a minimal set of drivers and files and disables everything else.
* **Safe Mode with Networking:** Windows starts with a basic set of drivers in addition to the network drivers necessary to connect to a network or the Internet. Wi-Fi connectivity is not available in this mode.
* **Safe Mode with Command Prompt:** For advanced users who want to access the Command Prompt in safe mode and don’t need the Windows graphical interface.

## 1\. Boot into Safe Mode Using the Microsoft System Configuration Utility

 You can boot into safe mode using the System Configuration utility, which is less intimidating than other methods. Another advantage is that it allows you to configure your desired safe mode (Standard, Networking, Command Prompt) before restarting and also automatically set your computer to boot into safe mode on the next restart.

 To boot into safe mode using the System Configuration utility:

1. Press **Win + R** to open **Run**, type **msconfig** and click **OK**. Alternatively, click **Start**, type **System Configuration** and open the best matching result.
2. In the **System Configuration** window, open the **Boot** tab.  
![Windows 11 Dekstop Showing the Microsoft System Configuration Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility.png)
3. Under **Boot options**, select **Safe boot**. By default, the default mode is set to **Minimal**. Depending on your requirements, you can switch between **Alternate Shell (Command Prompt)**, **Network** or **Active Directory repair** options.  
![Windows 11 Desktop Showing the Microsoft System Configuration Utility Advanced Boot options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility-advanced-boot-options.png)
4. The **Advanced options** dialog offers more granular control over the processor and memory usage. Leave it as default if you don’t know what you are doing.
5. Once done, click **OK** and **Apply** to save the changes.
6. Restart your computer to boot into safe mode.

## 2\. How to Boot Into Safe Mode Using the Settings App

 Another way to boot into safe mode is via the Settings app. You can use the Recovery option to access the Advanced Start-up settings and then boot into safe mode. Here’s how to do it:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on the **Recovery option.**
3. Click the **Restart** now button for **Advanced startup.**  
![Windows 11 recovery startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-11-recovery-startup-settings.png)
4. Click the **Restart now** button to confirm the action.
5. In the **Choose an option** screen, click **Troubleshoot**.  
![Troubleshoot menu in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/bootable-usb-troubleshoot-windows-recpvery-environment.png)
6. Next, click **Advanced options.**  
![Troubleshoot showing Advanced options in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-troubleshoot-windows-recovery-environment.png)
7. Click **Start-up settings** under Advanced options.  
![Advanced options for startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-up-settings-advanced-options.png)
8. Click the **Restart** button to confirm and open the start-up-up settings. Windows will populate your screen with multiple numbered options.  
![Startup settings in the Windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/startup-settings-windows-recovery-environemnt.png)
9. Press **4, 5 or 6** depending on the safe mode type you want to boot into. Windows will now restart and boot into safe mode.

 To exit safe mode, restart your PC and Windows will boot normally.

## 3\. How to Boot Into Safe Mode From the Lock-Screen

![Booting into safe mode from the lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-into-safe-mode-from-lock-screen.png)

 If you have [forgotten your Windows password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/) or can't log in, you can boot into safe mode from the lock screen itself. Here’s how to do it:

1. Restart your PC.
2. When at the lock screen, press any key to see your logon screen.
3. Click the **Power/Shutdown** button. Then, press and hold the **Shift** key and click **Restart**. If prompted for confirmation, click **Restart anyway**.
4. Your computer will restart and show the Windows Recovery Environment. From here, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
5. Press **4** to restart and boot into safe mode.

 Alternatively, you also do this from the desktop**. Click Start > Power** and while holding the **Shift** key, click **Restart**.

## 4\. Boot Into Safe Mode Using Command Prompt and WinRE

 In addition to the above steps, you can use Command Prompt to restart your computer with advanced options enabled. Once in Windows RE, you can navigate to Startup Settings and access safe mode. Here's how to do it.

1. Press the **Win** key, type **cmd**, then right-click on **Command Prompt** and choose **Run as administrator**.  
![Shutdown command in a Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-command-prompt-showing-the-restart-with-advanced-option-command.png)
2. In the Command Prompt window, type the following command and press Enter to execute:  
`shutdown.exe /r /o`
3. Click the **Close** button when a pop-up dialog appears.  
![Windows 11 prompt to restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/safe-mode-windows-11-command-prompt.png)
4. That’s it. Windows will restart in one minute. So, wait till the PC restarts and boots into the Windows Recovery Environment.
5. In Windows RE, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
6. After the restart, press the appropriate key to boot into safe mode.

## 5\. Boot Into Safe Mode When Windows is Not Booting

 If [Windows is not booting](https://www.makeuseof.com/tag/windows-10-wont-boot/), or you can't see the login screen, you can still access safe mode using the advanced boot option by triggering the Windows Recovery Environment.

 While you can press the F8 key repeatedly during the boot process to access advanced boot options, it doesn't always work. Instead, you can force [Windows to boot into the Windows Recovery Environment](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) by deliberately force shutting down your computer a few times during startup.

 After two consecutive failed attempts, Windows will automatically start WinRE and give access to advanced boot options. To do this:

1. Shut down your computer.
2. Press the **Power** button to power on your PC.
3. When it starts loading, press and hold the Power button to force a shutdown. Repeat the steps to abruptly shut down your computer again.
4. At the third attempt, press the power button and let Windows load and boot into Windows Recovery Environment.
5. Under **Choose an option,** click **Troubleshoot**.
6. Then go to **Advanced options > Start-up settings > Restart.**
7. After the restart, press **4,5 or 6** to boot into safe mode with different options.

## 6\. Perform a Safe Boot Using a Bootable USB Drive and Command Prompt

 If your computer is experiencing a critical system failure or startup issues and cannot boot normally, you can perform a safe boot using a bootable USB drive.

 If you don’t have installation media, follow our guide to [create a Windows 11 bootable USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you've created got a bootable drive, continue with the steps below:

1. Connect the bootable USB drive to your computer.
2. Press the **Power** button and start pressing the **F9** key on an HP laptop or **F2** on a Lenovo laptop to bring up the Boot Manager. The Boot Manager key can vary depending on your laptop/motherboard manufacturer.  
![Booting Windows from a USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-from-USB-drive.jpg)
3. In the Boot Manager, use the arrow keys to select the bootable USB drive as the boot device. Press **Enter** to select the option to open the Windows Setup wizard.
4. In the **Windows Setup** wizard, click on **Next**.  
![repair computer bootable USb windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/repair-computer-bootable-USb-windows-11.png)
5. Then, click on **Repair your computer** in the bottom left corner to enter **Windows RE.**

1. Under **Choose an option,** go to **Troubleshoot > Command Prompt.**  
![Advanced options showing the command prompt option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-command-prompt.png)
2. In the Command Prompt window, type the following command and press enter to change Boot Configuration Data (BCD) file.  
`bcdedit /set {default} safeboot minimal`
3. Alternatively, to enable safe boot with networking, type the following command:  
`bcdedit /set {default} safeboot network`
4. If successful, you will see the **operation completed successfully message.**  
![Clean boot command prompt from a bootable USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/clean-boot-command-prompt-bootable-usb-drive.png)
5. Type **exit** and press **Enter** to close Command Prompt.
6. In Windows RE, click **Continue**. Windows will now restart in safe boot mode.

## How to Exit Safe Mode in Windows 11

![Exiting Safe Mode in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/exit-safe-mode-windows-11.png)

 To exit safe mode, restart your PC and wait for it to restart normally. However, if your computer continues to boot into safe mode, follow these steps to exit safe mode manually.

1. Press **Win + R** to open **Run**.
2. Type **msconfig** and click **OK** to open the **System Configuration.**
3. In the **Boot** tab, uncheck the **Safe boot** option.
4. Click **Apply** and **OK** to save the changes. Restart your PC, and it should start normally.

 Safe mode is a handy diagnostic space in Windows. It allows you to access critical drivers and is ideal for diagnosing your system for hardware issues. However, if you want to troubleshoot third-party vendor software-related issues, [try a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/). It lets you load your system with a minimal set of drivers and startup apps to isolate the cause triggering the conflict.

 In safe mode, Windows starts with a basic set of drivers and files essential to run the system. Everything else, including start-up apps, networking, and Command Prompt, is disabled in safe mode. This helps you determine if an external hardware driver or program conflict is causing your system to malfunction.

 There are different types of safe modes and many ways to access them. If you need to diagnose your PC, here is how to boot into safe mode in Windows 11 on a working or non-booting computer.

## The Different Types of Safe Mode and When to Use Them

 There are three types of safe mode options available in advanced boot options:

* **Safe Mode:** Windows starts with a minimal set of drivers and files and disables everything else.
* **Safe Mode with Networking:** Windows starts with a basic set of drivers in addition to the network drivers necessary to connect to a network or the Internet. Wi-Fi connectivity is not available in this mode.
* **Safe Mode with Command Prompt:** For advanced users who want to access the Command Prompt in safe mode and don’t need the Windows graphical interface.

## 1\. Boot into Safe Mode Using the Microsoft System Configuration Utility

 You can boot into safe mode using the System Configuration utility, which is less intimidating than other methods. Another advantage is that it allows you to configure your desired safe mode (Standard, Networking, Command Prompt) before restarting and also automatically set your computer to boot into safe mode on the next restart.

 To boot into safe mode using the System Configuration utility:

1. Press **Win + R** to open **Run**, type **msconfig** and click **OK**. Alternatively, click **Start**, type **System Configuration** and open the best matching result.
2. In the **System Configuration** window, open the **Boot** tab.  
![Windows 11 Dekstop Showing the Microsoft System Configuration Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility.png)
3. Under **Boot options**, select **Safe boot**. By default, the default mode is set to **Minimal**. Depending on your requirements, you can switch between **Alternate Shell (Command Prompt)**, **Network** or **Active Directory repair** options.  
![Windows 11 Desktop Showing the Microsoft System Configuration Utility Advanced Boot options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility-advanced-boot-options.png)
4. The **Advanced options** dialog offers more granular control over the processor and memory usage. Leave it as default if you don’t know what you are doing.
5. Once done, click **OK** and **Apply** to save the changes.
6. Restart your computer to boot into safe mode.

## 2\. How to Boot Into Safe Mode Using the Settings App

 Another way to boot into safe mode is via the Settings app. You can use the Recovery option to access the Advanced Start-up settings and then boot into safe mode. Here’s how to do it:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on the **Recovery option.**
3. Click the **Restart** now button for **Advanced startup.**  
![Windows 11 recovery startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-11-recovery-startup-settings.png)
4. Click the **Restart now** button to confirm the action.
5. In the **Choose an option** screen, click **Troubleshoot**.  
![Troubleshoot menu in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/bootable-usb-troubleshoot-windows-recpvery-environment.png)
6. Next, click **Advanced options.**  
![Troubleshoot showing Advanced options in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-troubleshoot-windows-recovery-environment.png)
7. Click **Start-up settings** under Advanced options.  
![Advanced options for startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-up-settings-advanced-options.png)
8. Click the **Restart** button to confirm and open the start-up-up settings. Windows will populate your screen with multiple numbered options.  
![Startup settings in the Windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/startup-settings-windows-recovery-environemnt.png)
9. Press **4, 5 or 6** depending on the safe mode type you want to boot into. Windows will now restart and boot into safe mode.

 To exit safe mode, restart your PC and Windows will boot normally.

## 3\. How to Boot Into Safe Mode From the Lock-Screen

![Booting into safe mode from the lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-into-safe-mode-from-lock-screen.png)

 If you have [forgotten your Windows password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/) or can't log in, you can boot into safe mode from the lock screen itself. Here’s how to do it:

1. Restart your PC.
2. When at the lock screen, press any key to see your logon screen.
3. Click the **Power/Shutdown** button. Then, press and hold the **Shift** key and click **Restart**. If prompted for confirmation, click **Restart anyway**.
4. Your computer will restart and show the Windows Recovery Environment. From here, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
5. Press **4** to restart and boot into safe mode.

 Alternatively, you also do this from the desktop**. Click Start > Power** and while holding the **Shift** key, click **Restart**.

## 4\. Boot Into Safe Mode Using Command Prompt and WinRE

 In addition to the above steps, you can use Command Prompt to restart your computer with advanced options enabled. Once in Windows RE, you can navigate to Startup Settings and access safe mode. Here's how to do it.

1. Press the **Win** key, type **cmd**, then right-click on **Command Prompt** and choose **Run as administrator**.  
![Shutdown command in a Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-command-prompt-showing-the-restart-with-advanced-option-command.png)
2. In the Command Prompt window, type the following command and press Enter to execute:  
`shutdown.exe /r /o`
3. Click the **Close** button when a pop-up dialog appears.  
![Windows 11 prompt to restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/safe-mode-windows-11-command-prompt.png)
4. That’s it. Windows will restart in one minute. So, wait till the PC restarts and boots into the Windows Recovery Environment.
5. In Windows RE, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
6. After the restart, press the appropriate key to boot into safe mode.

## 5\. Boot Into Safe Mode When Windows is Not Booting

 If [Windows is not booting](https://www.makeuseof.com/tag/windows-10-wont-boot/), or you can't see the login screen, you can still access safe mode using the advanced boot option by triggering the Windows Recovery Environment.

 While you can press the F8 key repeatedly during the boot process to access advanced boot options, it doesn't always work. Instead, you can force [Windows to boot into the Windows Recovery Environment](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) by deliberately force shutting down your computer a few times during startup.

 After two consecutive failed attempts, Windows will automatically start WinRE and give access to advanced boot options. To do this:

1. Shut down your computer.
2. Press the **Power** button to power on your PC.
3. When it starts loading, press and hold the Power button to force a shutdown. Repeat the steps to abruptly shut down your computer again.
4. At the third attempt, press the power button and let Windows load and boot into Windows Recovery Environment.
5. Under **Choose an option,** click **Troubleshoot**.
6. Then go to **Advanced options > Start-up settings > Restart.**
7. After the restart, press **4,5 or 6** to boot into safe mode with different options.

## 6\. Perform a Safe Boot Using a Bootable USB Drive and Command Prompt

 If your computer is experiencing a critical system failure or startup issues and cannot boot normally, you can perform a safe boot using a bootable USB drive.

 If you don’t have installation media, follow our guide to [create a Windows 11 bootable USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you've created got a bootable drive, continue with the steps below:

1. Connect the bootable USB drive to your computer.
2. Press the **Power** button and start pressing the **F9** key on an HP laptop or **F2** on a Lenovo laptop to bring up the Boot Manager. The Boot Manager key can vary depending on your laptop/motherboard manufacturer.  
![Booting Windows from a USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-from-USB-drive.jpg)
3. In the Boot Manager, use the arrow keys to select the bootable USB drive as the boot device. Press **Enter** to select the option to open the Windows Setup wizard.
4. In the **Windows Setup** wizard, click on **Next**.  
![repair computer bootable USb windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/repair-computer-bootable-USb-windows-11.png)
5. Then, click on **Repair your computer** in the bottom left corner to enter **Windows RE.**

1. Under **Choose an option,** go to **Troubleshoot > Command Prompt.**  
![Advanced options showing the command prompt option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-command-prompt.png)
2. In the Command Prompt window, type the following command and press enter to change Boot Configuration Data (BCD) file.  
`bcdedit /set {default} safeboot minimal`
3. Alternatively, to enable safe boot with networking, type the following command:  
`bcdedit /set {default} safeboot network`
4. If successful, you will see the **operation completed successfully message.**  
![Clean boot command prompt from a bootable USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/clean-boot-command-prompt-bootable-usb-drive.png)
5. Type **exit** and press **Enter** to close Command Prompt.
6. In Windows RE, click **Continue**. Windows will now restart in safe boot mode.

## How to Exit Safe Mode in Windows 11

![Exiting Safe Mode in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/exit-safe-mode-windows-11.png)

 To exit safe mode, restart your PC and wait for it to restart normally. However, if your computer continues to boot into safe mode, follow these steps to exit safe mode manually.

1. Press **Win + R** to open **Run**.
2. Type **msconfig** and click **OK** to open the **System Configuration.**
3. In the **Boot** tab, uncheck the **Safe boot** option.
4. Click **Apply** and **OK** to save the changes. Restart your PC, and it should start normally.

 Safe mode is a handy diagnostic space in Windows. It allows you to access critical drivers and is ideal for diagnosing your system for hardware issues. However, if you want to troubleshoot third-party vendor software-related issues, [try a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/). It lets you load your system with a minimal set of drivers and startup apps to isolate the cause triggering the conflict.

 In safe mode, Windows starts with a basic set of drivers and files essential to run the system. Everything else, including start-up apps, networking, and Command Prompt, is disabled in safe mode. This helps you determine if an external hardware driver or program conflict is causing your system to malfunction.

 There are different types of safe modes and many ways to access them. If you need to diagnose your PC, here is how to boot into safe mode in Windows 11 on a working or non-booting computer.

## The Different Types of Safe Mode and When to Use Them

 There are three types of safe mode options available in advanced boot options:

* **Safe Mode:** Windows starts with a minimal set of drivers and files and disables everything else.
* **Safe Mode with Networking:** Windows starts with a basic set of drivers in addition to the network drivers necessary to connect to a network or the Internet. Wi-Fi connectivity is not available in this mode.
* **Safe Mode with Command Prompt:** For advanced users who want to access the Command Prompt in safe mode and don’t need the Windows graphical interface.

## 1\. Boot into Safe Mode Using the Microsoft System Configuration Utility

 You can boot into safe mode using the System Configuration utility, which is less intimidating than other methods. Another advantage is that it allows you to configure your desired safe mode (Standard, Networking, Command Prompt) before restarting and also automatically set your computer to boot into safe mode on the next restart.

 To boot into safe mode using the System Configuration utility:

1. Press **Win + R** to open **Run**, type **msconfig** and click **OK**. Alternatively, click **Start**, type **System Configuration** and open the best matching result.
2. In the **System Configuration** window, open the **Boot** tab.  
![Windows 11 Dekstop Showing the Microsoft System Configuration Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility.png)
3. Under **Boot options**, select **Safe boot**. By default, the default mode is set to **Minimal**. Depending on your requirements, you can switch between **Alternate Shell (Command Prompt)**, **Network** or **Active Directory repair** options.  
![Windows 11 Desktop Showing the Microsoft System Configuration Utility Advanced Boot options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-11-dekstop-showing-the-microsoft-system-configuration-utility-advanced-boot-options.png)
4. The **Advanced options** dialog offers more granular control over the processor and memory usage. Leave it as default if you don’t know what you are doing.
5. Once done, click **OK** and **Apply** to save the changes.
6. Restart your computer to boot into safe mode.

## 2\. How to Boot Into Safe Mode Using the Settings App

 Another way to boot into safe mode is via the Settings app. You can use the Recovery option to access the Advanced Start-up settings and then boot into safe mode. Here’s how to do it:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on the **Recovery option.**
3. Click the **Restart** now button for **Advanced startup.**  
![Windows 11 recovery startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-11-recovery-startup-settings.png)
4. Click the **Restart now** button to confirm the action.
5. In the **Choose an option** screen, click **Troubleshoot**.  
![Troubleshoot menu in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/bootable-usb-troubleshoot-windows-recpvery-environment.png)
6. Next, click **Advanced options.**  
![Troubleshoot showing Advanced options in the Windows Recovery Environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-troubleshoot-windows-recovery-environment.png)
7. Click **Start-up settings** under Advanced options.  
![Advanced options for startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-up-settings-advanced-options.png)
8. Click the **Restart** button to confirm and open the start-up-up settings. Windows will populate your screen with multiple numbered options.  
![Startup settings in the Windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/startup-settings-windows-recovery-environemnt.png)
9. Press **4, 5 or 6** depending on the safe mode type you want to boot into. Windows will now restart and boot into safe mode.

 To exit safe mode, restart your PC and Windows will boot normally.

## 3\. How to Boot Into Safe Mode From the Lock-Screen

![Booting into safe mode from the lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-into-safe-mode-from-lock-screen.png)

 If you have [forgotten your Windows password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/) or can't log in, you can boot into safe mode from the lock screen itself. Here’s how to do it:

1. Restart your PC.
2. When at the lock screen, press any key to see your logon screen.
3. Click the **Power/Shutdown** button. Then, press and hold the **Shift** key and click **Restart**. If prompted for confirmation, click **Restart anyway**.
4. Your computer will restart and show the Windows Recovery Environment. From here, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
5. Press **4** to restart and boot into safe mode.

 Alternatively, you also do this from the desktop**. Click Start > Power** and while holding the **Shift** key, click **Restart**.

## 4\. Boot Into Safe Mode Using Command Prompt and WinRE

 In addition to the above steps, you can use Command Prompt to restart your computer with advanced options enabled. Once in Windows RE, you can navigate to Startup Settings and access safe mode. Here's how to do it.

1. Press the **Win** key, type **cmd**, then right-click on **Command Prompt** and choose **Run as administrator**.  
![Shutdown command in a Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-command-prompt-showing-the-restart-with-advanced-option-command.png)
2. In the Command Prompt window, type the following command and press Enter to execute:  
`shutdown.exe /r /o`
3. Click the **Close** button when a pop-up dialog appears.  
![Windows 11 prompt to restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/safe-mode-windows-11-command-prompt.png)
4. That’s it. Windows will restart in one minute. So, wait till the PC restarts and boots into the Windows Recovery Environment.
5. In Windows RE, go to **Troubleshoot > Advanced Options > Start-up settings > Restart.**
6. After the restart, press the appropriate key to boot into safe mode.

## 5\. Boot Into Safe Mode When Windows is Not Booting

 If [Windows is not booting](https://www.makeuseof.com/tag/windows-10-wont-boot/), or you can't see the login screen, you can still access safe mode using the advanced boot option by triggering the Windows Recovery Environment.

 While you can press the F8 key repeatedly during the boot process to access advanced boot options, it doesn't always work. Instead, you can force [Windows to boot into the Windows Recovery Environment](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) by deliberately force shutting down your computer a few times during startup.

 After two consecutive failed attempts, Windows will automatically start WinRE and give access to advanced boot options. To do this:

1. Shut down your computer.
2. Press the **Power** button to power on your PC.
3. When it starts loading, press and hold the Power button to force a shutdown. Repeat the steps to abruptly shut down your computer again.
4. At the third attempt, press the power button and let Windows load and boot into Windows Recovery Environment.
5. Under **Choose an option,** click **Troubleshoot**.
6. Then go to **Advanced options > Start-up settings > Restart.**
7. After the restart, press **4,5 or 6** to boot into safe mode with different options.

## 6\. Perform a Safe Boot Using a Bootable USB Drive and Command Prompt

 If your computer is experiencing a critical system failure or startup issues and cannot boot normally, you can perform a safe boot using a bootable USB drive.

 If you don’t have installation media, follow our guide to [create a Windows 11 bootable USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you've created got a bootable drive, continue with the steps below:

1. Connect the bootable USB drive to your computer.
2. Press the **Power** button and start pressing the **F9** key on an HP laptop or **F2** on a Lenovo laptop to bring up the Boot Manager. The Boot Manager key can vary depending on your laptop/motherboard manufacturer.  
![Booting Windows from a USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/boot-from-USB-drive.jpg)
3. In the Boot Manager, use the arrow keys to select the bootable USB drive as the boot device. Press **Enter** to select the option to open the Windows Setup wizard.
4. In the **Windows Setup** wizard, click on **Next**.  
![repair computer bootable USb windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/repair-computer-bootable-USb-windows-11.png)
5. Then, click on **Repair your computer** in the bottom left corner to enter **Windows RE.**

1. Under **Choose an option,** go to **Troubleshoot > Command Prompt.**  
![Advanced options showing the command prompt option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/advanced-options-command-prompt.png)
2. In the Command Prompt window, type the following command and press enter to change Boot Configuration Data (BCD) file.  
`bcdedit /set {default} safeboot minimal`
3. Alternatively, to enable safe boot with networking, type the following command:  
`bcdedit /set {default} safeboot network`
4. If successful, you will see the **operation completed successfully message.**  
![Clean boot command prompt from a bootable USB drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/clean-boot-command-prompt-bootable-usb-drive.png)
5. Type **exit** and press **Enter** to close Command Prompt.
6. In Windows RE, click **Continue**. Windows will now restart in safe boot mode.

## How to Exit Safe Mode in Windows 11

![Exiting Safe Mode in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/exit-safe-mode-windows-11.png)

 To exit safe mode, restart your PC and wait for it to restart normally. However, if your computer continues to boot into safe mode, follow these steps to exit safe mode manually.

1. Press **Win + R** to open **Run**.
2. Type **msconfig** and click **OK** to open the **System Configuration.**
3. In the **Boot** tab, uncheck the **Safe boot** option.
4. Click **Apply** and **OK** to save the changes. Restart your PC, and it should start normally.

 Safe mode is a handy diagnostic space in Windows. It allows you to access critical drivers and is ideal for diagnosing your system for hardware issues. However, if you want to troubleshoot third-party vendor software-related issues, [try a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/). It lets you load your system with a minimal set of drivers and startup apps to isolate the cause triggering the conflict.


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
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://win11.techidaily.com/timeless-windows-syncing-the-digital-second-hand/"><u>Timeless Windows: Syncing the Digital Second Hand</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-winapp-and-browser-mastery/"><u>Navigating the Landscape of WinApp and Browser Mastery</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-apple-iphone-13-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Apple iPhone 13 without Passcode or Face ID</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-windows-10-video-editing-programs-for-beginners/"><u>New In 2024, Top Windows 10 Video Editing Programs for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recover-lost-access-to-ubisofts-launcher/"><u>Steps to Recover Lost Access to Ubisoft's Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-user-error-in-windows-1111/"><u>Overcoming Unauthorized User Error in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-steam-content-unavailable-glitches/"><u>Bypassing Steam Content Unavailable Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-exception-breakpoint-errors/"><u>Strategies to Address Windows Exception Breakpoint Errors</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unshaken-learn-to-stabilize-your-videos-like-a-pr-for-2024/"><u>New Unshaken Learn to Stabilize Your Videos Like a Pr for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-an-enhanced-run-tool-to-windows-10-and-11/"><u>How to Add an Enhanced Run Tool to Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-spotlight-on-figure-skaters-2022-edition/"><u>[New] Spotlight on Figure Skaters  2022 Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-uses-of-b-roll-beyond-traditional-applications/"><u>[New] Innovative Uses of B-Roll  Beyond Traditional Applications</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unlocking-potential-a-guide-to-dominating-your-instagram-posts/"><u>In 2024, Unlocking Potential  A Guide to Dominating Your Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rediscovering-missing-panes-top-tips-and-hacks-for-windows-users/"><u>The Ultimate Guide to Rediscovering Missing Panes: Top Tips and Hacks for Windows Users</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-tecno-pova-5-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Tecno Pova 5 Quickly? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-from-raw-footage-to-final-cut-the-art-of-online-video-editing-for-2024/"><u>New From Raw Footage to Final Cut The Art of Online Video Editing for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-the-ultimate-resource-for-free-sound-effects-a-guide-for-final-cut-pro-editors/"><u>2024 Approved The Ultimate Resource for Free Sound Effects A Guide for Final Cut Pro Editors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-exploring-stop-motion-a-detailed-comparison-of-studio-and-alternative-tools-for-2024/"><u>New Exploring Stop Motion A Detailed Comparison of Studio and Alternative Tools for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/leading-apps-for-dji-video-manipulation-and-mixing/"><u>Leading Apps for DJi Video Manipulation and Mixing</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-search-backup-procedure/"><u>Navigate to Windows 11 Search Backup Procedure</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-enhance-teamwork-and-efficiency-8-must-have-task-apps/"><u>[Updated] Enhance Teamwork & Efficiency  8 Must-Have Task Apps</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-fix-inaudible-microphone-during-screen-recordings/"><u>Techniques to Fix Inaudible Microphone During Screen Recordings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-the-comprehensive-blueprint-for-vimeo-video-logging/"><u>[New] 2024 Approved  The Comprehensive Blueprint for Vimeo Video Logging</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-optimizing-windows-lockscreen-with-spotlight/"><u>Tips for Optimizing Windows Lockscreen with Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-nvidia-geforce-notaxc0f1103f-error/"><u>Correcting Windows Nvidia GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-early-edges-methods-to-stop-tab-preload-on-windows-11/"><u>Trimming Early Edges: Methods to Stop Tab Preload on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-power-of-task-manager-with-admin-rights-in-win11/"><u>Unleash Full Power of Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-mobile-app-match-android-plus-windows-pc-edition/"><u>Perfect Mobile App Match: Android + Windows PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-0x80070522-on-windows-by-accessing-client-rights/"><u>Sidestepping Error 0X80070522 on Windows by Accessing Client Rights</u></a></li>
<li><a href="https://win11.techidaily.com/post-install-windows-heres-how-to-get-online/"><u>Post-Install Windows? Here's How to Get Online</u></a></li>
</ul></div>
