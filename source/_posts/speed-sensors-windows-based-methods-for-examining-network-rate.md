---
title: "Speed Sensors: Windows-Based Methods for Examining Network Rate"
date: 2024-08-08T13:17:31.060Z
updated: 2024-08-09T13:17:31.060Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Speed Sensors: Windows-Based Methods for Examining Network Rate"
excerpt: "This Article Describes Speed Sensors: Windows-Based Methods for Examining Network Rate"
keywords: Network Rate Analysis,Speed Sensor Windows,Network Speed Test,Wireless Monitoring,Data Throughput Check,Windows Network Diagnostics,Real-Time Traffic Evaluation
thumbnail: https://thmb.techidaily.com/95788679327077f3bf6744c4870d74096e3663b00fb525d667e1a6c4f5883874.jpg
---

## Speed Sensors: Windows-Based Methods for Examining Network Rate

 The network adapter is a critical piece of hardware that connects your Windows computer to the internet via a wired or wireless connection. In order to achieve the maximum speeds offered by your Internet Service Provider, it is important to know what network speed your card is capable of.

 Whether you want to upgrade your internet plan or diagnose your network for performance issues, there are several ways to determine the network adapter speed on Windows. Let’s go over all of them one by one.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 1\. How to Check the Network Adapter Connection Speed Using the Settings App

 The quickest way to check the connection speed for a Wi-Fi or Ethernet adapter is through the Windows Settings app. Aside from network speed, the Settings app also provides important information like network band, local IP address, MAC address, and more.

To check the network adapter speed via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Select**Network & internet** from the left sidebar.
3. Click on**Properties** at the top.
4. Scroll down to the**Link speed (Receive/Transmit)** field to check the connection speed.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check Network Adapter Speed Using the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-the-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)

 Seeing too many network adapter entries on your Windows computer? Learn[how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide on[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Checking Network Adapter Connection Speed on Windows

 As we just learned, determining the network adapter connection speed on Windows is relatively simple. Do you know what else is easy? Speeding up the internet connection speed on your Windows computer.


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


