---
title: How to Tackle Windows 'Admin-Imposed' Setup Barriers
date: 2024-08-16T00:26:14.516Z
updated: 2024-08-17T00:26:14.516Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Tackle Windows 'Admin-Imposed' Setup Barriers
excerpt: This Article Describes How to Tackle Windows 'Admin-Imposed' Setup Barriers
keywords: Bypassing Admin Restrictions,Unlocking Windows Settings,Disable Setup Limits,Overcoming Windows Locks,Easing Windows Configurations,Eliminate Default Barriers,Removing Windows Hurdles
thumbnail: https://thmb.techidaily.com/3bbe537e8e6d43ee38a009c5ba9253564dbe37ab479840f5e7760ebe6f9d088b.jpg
---

## How to Tackle Windows 'Admin-Imposed' Setup Barriers

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



