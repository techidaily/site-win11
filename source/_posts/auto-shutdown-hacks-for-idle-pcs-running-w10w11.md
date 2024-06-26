---
title: Auto Shutdown Hacks for Idle PCs Running W10/W11
date: 2024-06-25T09:47:01.211Z
updated: 2024-06-26T09:47:01.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Auto Shutdown Hacks for Idle PCs Running W10/W11
excerpt: This Article Describes Auto Shutdown Hacks for Idle PCs Running W10/W11
keywords: PC Auto Shutoff,Power Saving Tricks,Idle PC Safety,Windows 10 Hacks,Win11 Energy-Saving,Efficient PC Management,Automatic System Downtime
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Auto Shutdown Hacks for Idle PCs Running W10/W11

### Key Takeaways

* Schedule a shutdown in Windows 11 and 10 using Task Scheduler for daily, weekly, or monthly tasks. Customize the start date and time.
* Add a trigger condition to your shutdown task to run it after a specified period of inactivity using Task Scheduler.
* Use Command Prompt to schedule a system shutdown with a specific timer or define a shutdown time. Customize with shutdown parameters.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.

 By default, Windows is configured to put your computer to sleep after a few minutes of inactivity. But if you prefer to shut down your computer every day or when idle for a long time, you can use the Task Scheduler to schedule an automatic system shutdown instead.

 Here we show you how to schedule a shutdown in Windows 11 and 10 computers.

## How to Schedule a Windows 11 Shutdown Using Task Scheduler

 Task Scheduler is a job scheduling utility available on the Windows operating system. You can [use Task Scheduler to run programs automatically on Windows](https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/).

 You can also use it to create a scheduled task to shut down your PC daily at a specified time. Scheduling a task via Task Scheduler is preferred if you need to repeat a task daily, weekly, or once a month.

 To create a shutdown task:

1. Press the **Win** key to open the **Windows search** bar.
2. Type **Task scheduler** and click on the app from the search result to open it.
3. In the Task Scheduler window, click on **Action** and select **Create Basic Task.**  
![create basic task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-basic-task.png)
4. In the Basic Task window, type a name for the task. For example, type **Shutdown** as the name. You can also provide a description of the task.  
![task name task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/task-name-task-scheduler.png)
5. Click **Next**.  
![daily trigger set date time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/daily-trigger-set-date-time.png)

1. Next, select a trigger point. You can choose from **Daily, Weekly, Monthly, One Time,** etc. For this guide, we will select the **Daily** trigger to schedule a daily shut down at a specific time.
2. So, select **Daily** and click **Next**.
3. Next, set the **Start date** and **time** for the recurring shut down and click **Next**.  
![start a program task action](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-action.png)
4. In the **Action** tab, select **Start a program** and click **Next**.  
![start a program task command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-a-program-task-command.png)
5. Type **shutdown.exe** in the **Program/Script** field and click **Next**.
6. Review the changes and click **Finish** to create and add the new task to your Windows schedule.

 That’s it. The Task Scheduler will trigger the shutdown action daily at your specified time and power off your PC.

## How to Automatically Shut Down Windows on Idle via Task Scheduler

 If you want, you can add a trigger condition to your shutdown task to determine when the task should run. This is helpful if you want to run the shutdown task after a specified period of inactivity.

 For this guide, we will modify the shutdown task created earlier. If you want, you can create a new task as well.

1. Select your existing shutdown task in the Task Scheduler.
2. Right-click on the task and select **Properties**.  
![active task properties task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/active-task-properties-task-scheduler.png)
3. Open the **Conditions** tab in the Properties window.  
![start the task only if the computer is idle for the option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/start-the-task-only-if-the-computer-is-idle-for-the-option.png)
4. Select **Start** **the task only if the computer is idle for the** option.
5. In both the **time** **fields**, enter the same time. For example, if you enter 10 minutes, the Task Scheduler will wait for the system to be idle for 10 minutes before triggering the Shut down task. You can choose anywhere from a few minutes to two hours.
6. Click **OK** to save the changes.

## How to Stop an Automatic Shutdown via Task Scheduler

![disable active tasks task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/disable-active-tasks-task-scheduler.png)

 To stop automatic Windows shutdown, you'll need to delete or [disable the scheduled task in Windows Task Scheduler](https://www.makeuseof.com/disable-scheduled-tasks-windows-10/). Disabling it is best if you only want to stop it for a temporary amount of time, but if you're tired of your PC turning off by itself, it's best to delete it instead.

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.
3. In the Windows Terminal window, type the following command and press Enter:  
`Shutdown /s -t Nseconds`
4. In the above command, replace **Nseconds** with the number of seconds. For example, if you want to set a timer for 5 minutes (300 seconds), then the complete command will look like this:  
`Shutdown /s -t 300`
5. The above command will trigger the Windows logoff action and shutdown your PC after 5 minutes.
6. If you want to perform a scheduled restart, type the following command and press Enter:  
`Shutdown -r -t Nseconds`
7. In the above command, replace **Nseconds** with the number of seconds to set a timer for a restart.  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
8. If you want to define a specific shutdown time instead, use the **at time shutdown /s** command. For example, to schedule a shutdown at 12:30 AM, use the following command:  
`at 00:30 shutdown /s`
9. To cancel the shutdown or restart the timer, type the following command and press Enter:  
`Shutdown -a`
10. You will see a logoff is canceled notification indicating the shutdown has been canceled.

![shutdown command parameters command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/shutdown-command-parameters-command-prompt.jpg)

 You can further customize the shutdown task by using the shutdown parameters. For example, use the **\-f** parameter to force close the running application without warning. Additionally, type **shutdown** and press Enter to view all the available parameters for the shutdown command.

## How to Schedule Auto Shut Down Using a Desktop Shortcut

 You can [create a desktop shortcut with a shutdown timer to turn off your PC](https://www.makeuseof.com/windows-11-shutdown-desktop-shortcut/). This is useful if you don’t want to run the Command Prompt each time to set a timer.

 To create a shutdown timer desktop shortcut:

1. Right-click on your Windows desktop and select **New > Shortcut.**  
![create new desktop shortct](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-new-desktop-shortct.png)
2. In the shortcut wizard, type the following command in the **Type the location of the item** field:  
`Shutdown -s -t 300`
3. In the above command, **300 seconds (5 minutes)** represents the number of seconds for the timer. You can change the seconds as per your need.  
![automated shut down shortcut command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-shortcut-command.png)
4. Click **Next**.
5. Next, type a name for your shortcut. For example, type **ShutDownTimer.**  
![shutdown timer shortcut name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdown-timer-shortcut-name.png)

1. Click the **Finish** button to add the shortcut to your desktop.
2. Next, right-click on the **ShutDownTimer** desktop shortcut and select **Properties**.
3. In the shortcut tab, click on the **Change** icon.  
![shutdowntimer desktop shortcut icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/shutdowntimer-desktop-shortcut-icon.png)
4. Select an icon that represents the shortcut best. For this guide, we will select the **Power** icon.
5. Click **OK** to make a selection.
6. Then, click **Apply** and **OK** to save changes.

 You can double-click on the ShutDownTimer shortcut to initiate a shutdown. To cancel the shutdown, use the **shutdown -a** command in Command Prompt.

## Automate a Windows Shut Down When It Goes Idle

 You can use Command Prompt and Task Scheduler to automate system shutdown in Windows 11 and 10 computers. However, unlike Command Prompt, Task Scheduler offers better task automation and supports more conditions. You can also configure it to automate Windows start-up.


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
<li><a href="https://win11.techidaily.com/enhancing-responsiveness-of-the-windows-downloads-hub/"><u>Enhancing Responsiveness of the Windows Downloads Hub</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-windows-with-5-mac-inspired-ideas/"><u>Simplify Your Windows with 5 Mac-Inspired Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-apps-to-monitor-win-os-temperatures/"><u>Ideal Apps to Monitor Win OS Temperatures</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-back-into-windows-service-tool-with-these-7-methods/"><u>Breathing Life Back Into Windows Service Tool With These 7 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/visionary-screenplay-crafting-hub/"><u>Visionary Screenplay Crafting Hub</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-the-world-of-animated-image-design/"><u>[New] Exploring the World of Animated Image Design</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/cheap-but-powerful-video-editing-software-for-2024/"><u>Cheap but Powerful Video Editing Software for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-mastering-visual-storytelling-the-cutting-edge-6-instagram-reel-tools-for-2024/"><u>[New] Mastering Visual Storytelling  The Cutting-Edge 6 Instagram Reel Tools for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>How to Get and Use Pokemon Go Promo Codes On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-5-ways-to-record-vr-gameplay/"><u>[Updated] 5 Ways to Record VR Gameplay</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-obsudio-screencast-review-finding-your-best-live-broadcast-tool/"><u>2024 Approved  Obsudio Screencast Review  Finding Your Best Live Broadcast Tool</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-influence-of-luts-on-digital-imagery-quality/"><u>In 2024, Exploring the Influence of LUTs on Digital Imagery Quality</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-become-an-expert-at-capturing-every-detail-on-xiaomi-mi-11/"><u>[Updated] In 2024, Become an Expert at Capturing Every Detail on Xiaomi Mi 11</u></a></li>
</ul></div>
