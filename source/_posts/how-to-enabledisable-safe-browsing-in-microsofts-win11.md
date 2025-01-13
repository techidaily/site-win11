---
title: How to Enable/Disable Safe Browsing in Microsoft's Win11
date: 2025-01-12T03:22:36.551Z
updated: 2025-01-12T20:21:45.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable/Disable Safe Browsing in Microsoft's Win11
excerpt: This Article Describes How to Enable/Disable Safe Browsing in Microsoft's Win11
keywords: Safe Browser Windows 11,Win11 Safe Mode Switch,Enabling Win11 Guard,Disable Win11 Safety,Browse Securely Win11,Turning On Win11 Shield,Win11 Protect Settings
thumbnail: https://thmb.techidaily.com/0e850e00d907836de022b6a5493d7e424fd91aacae9c4b818ed3e14b82d98585.jpg
---

## How to Enable/Disable Safe Browsing in Microsoft's Win11

### Key Takeaways

* Microsoft Defender SmartScreen is enabled by default in Windows and provides reputation-based protection against malicious apps and websites. It can be disabled if it mistakenly blocks safe files.
* SmartScreen is also a part of Microsoft Edge's security settings and can be turned off or on from the browser's settings menu. It helps protect against phishing sites and blocks potentially unwanted apps.
* SmartScreen can be turned off or on using various methods, including the Windows Security settings, Microsoft Edge settings, Internet Properties dialog, Registry Editor, and Group Policy Editor. It is recommended to enable SmartScreen for added PC security.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-unhindered-routine-changing-video-direction-with-vlc/"><u>[New] 2024 Approved Unhindered Routine Changing Video Direction with VLC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-temporary-pause-image-save-guide/"><u>[New] In 2024, Temporary Pause Image Save Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-ultimate-list-of-engaging-moba-titles-on-android/"><u>[Updated] In 2024, The Ultimate List of Engaging MOBA Titles on Android</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-step-by-step-screen-recording-snapshots-on-mobile/"><u>[Updated] Step-by-Step Screen Recording Snapshots on Mobile</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streamlining-your-gaming-diary-overwatch-video-documentation/"><u>[Updated] Streamlining Your Gaming Diary Overwatch Video Documentation</u></a></li>
<li><a href="https://some-tips.techidaily.com/affordable-upgrades-openai-reduces-costs-of-fine-tuning-for-gpt-4o-mini-on-zdnet/"><u>Affordable Upgrades: OpenAI Reduces Costs of Fine-Tuning for GPT-4o Mini on ZDNet</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/hering-digital-dominance-youtube-content-strategy-comparison/"><u>Deciphering Digital Dominance YouTube Content Strategy Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-workspace-transformation-go-fancywm/"><u>Dynamic Workspace Transformation: Go FancyWM</u></a></li>
<li><a href="https://some-tips.techidaily.com/expand-your-digital-workspace-empowering-your-m3-macbook-pro-with-multi-monitor-setup-just-like-its-successor/"><u>Expand Your Digital Workspace: Empowering Your M3 MacBook Pro with Multi-Monitor Setup Just Like Its Successor</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-mcuicnt-entry-not-found-error-in-windows-os/"><u>Fixing McUICnt Entry Not Found Error in Windows OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/giggles-on-iphones-for-2024/"><u>Giggles on iPhones for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-hyper-v-for-flawless-linux-vm-development-on-windows/"><u>Harnessing Hyper-V for Flawless Linux VM Development on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-screen-flashing-on-windows-11-pcs/"><u>How to Stop Screen Flashing on Windows 11 PCs</u></a></li>
<li><a href="https://fox-access.techidaily.com/light-and-shadow-masterful-edits-that-transform-images-for-2024/"><u>Light & Shadow Masterful Edits That Transform Images for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/limiting-processes-a-pc-guide/"><u>Limiting Processes: A PC Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-upgrades-a-windows-11-in-place-blueprint/"><u>Reimagining Upgrades: A Windows 11 In-Place Blueprint</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-excel-file-problems-opening-in-notepad/"><u>Remedy: Excel File Problems Opening in Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-hidden-windows-startup-details/"><u>Revealing Hidden Windows Startup Details</u></a></li>
<li><a href="https://win11.techidaily.com/why-limiting-antiviruses-is-key-for-your-windows-pcs-health/"><u>Why Limiting Antiviruses Is Key for Your Windows PC's Health</u></a></li>
</ul></div>

