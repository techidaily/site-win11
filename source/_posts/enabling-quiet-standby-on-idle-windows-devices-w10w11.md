---
title: Enabling Quiet Standby on Idle Windows Devices W10/W11
date: 2024-10-04T04:16:47.031Z
updated: 2024-10-09T09:20:54.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Quiet Standby on Idle Windows Devices W10/W11
excerpt: This Article Describes Enabling Quiet Standby on Idle Windows Devices W10/W11
keywords: Quiet Mode,Standby Windows 10/11,Sleep Settings W10/W11,Power Save Windows Devices,Quiet Boot W10/W11,Idle Device Energy-Saving,Low Power Mode Windows 10/11
thumbnail: https://thmb.techidaily.com/98af3c33462a260586336a96ddc2cbdb473875d7a720808faf7dee8c99a861a3.jpg
---

## Enabling Quiet Standby on Idle Windows Devices W10/W11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Schedule a Windows 11 Shutdown Using Command Prompt or PowerShell

 Task Scheduler is an excellent utility but may feel a little complicated for those who don’t use it often. Maybe you want to make your computer turn off after inactivity, but occasionally. In this instance, creating a scheduled task is unnecessary and tedious.

 If you don’t want to go through the learning curve, you can use the **shutdown** command in Command Prompt. The shutdown command lets you set a shutdown timer to power off and restart your Windows computer automatically.

 To schedule a system shutdown using Command Prompt:

1. Press the **Win + X** to open the **WinX menu.**  
![automated shut down windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/automated-shut-down-windows-11-command-prompt.png)
2. Click on **Windows Terminal (Admin)** to open the elevated terminal.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111964/7443" target="_top" id="2111964">
  <img src="//a.impactradius-go.com/display-ad/7443-2111964" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111964/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/2024-approved-asus-leads-the-charge-with-their-mg28uq-the-future-of-4k-monitors/"><u>2024 Approved ASUS Leads the Charge with Their MG28UQ - The Future of 4K Monitors</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-charting-the-differences-in-youtubes-ownership-and-cc-models/"><u>2024 Approved Charting the Differences in YouTube's Ownership and CC Models</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-untapped-windows-features-reliability-and-performance/"><u>Comparing Untapped Windows Features: Reliability & Performance</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-the-oled-world-asus-s15s-unique-appeal/"><u>Diving Into the OLED World: ASUS S15's Unique Appeal</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhanced-windows-11-features-integrated-printer-and-scanner-functions-fixed/"><u>Enhanced Windows 11 Features: Integrated Printer and Scanner Functions Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-supercharge-your-startup-with-windows-11/"><u>Essential Steps to Supercharge Your Startup with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-xbox-app-working-again-on-your-windows-laptop/"><u>Get the Xbox App Working Again on Your Windows Laptop</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hassle-free-canon-driver-installation-and-updates-for-windows-systems/"><u>Hassle-Free Canon Driver Installation and Updates for Windows Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Infinix Smart 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mini-2-and-air-2s-luts-free-trial-then-paid-upgrade/"><u>In 2024, Mini 2 & Air 2S LUTS - Free Trial, Then Paid Upgrade</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mould-laughter-inducing-images-giphy-style/"><u>Mould Laughter-Inducing Images, Giphy Style</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-add-the-popular-video-text-effects-to-your-video-in-2024/"><u>New How to Add the Popular Video Text Effects to Your Video, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-win11-for-a-smoother-jump-into-programs-on-startup/"><u>Optimizing Win11 for a Smoother Jump Into Programs on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-vintage-directx-apps-by-harnessing-dxvk-power/"><u>Revitalizing Vintage DirectX Apps by Harnessing DXVK Power</u></a></li>
<li><a href="https://win11.techidaily.com/signs-your-pc-struggles-when-to-consider-clean-slate/"><u>Signs Your PC Struggles, When to Consider Clean Slate</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-timely-purge-of-steam-dns-cache-on-pc/"><u>Techniques for Timely Purge of Steam DNS Cache on PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-comprehensive-guide-to-cutting-edge-hardware/"><u>Tom's Comprehensive Guide to Cutting-Edge Hardware</u></a></li>
</ul></div>

