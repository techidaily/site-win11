---
title: "Win11/10 NAT Transition: Altering Type Effectively"
date: 2024-07-13T10:58:50.338Z
updated: 2024-07-14T10:58:50.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11/10 NAT Transition: Altering Type Effectively"
excerpt: "This Article Describes Win11/10 NAT Transition: Altering Type Effectively"
keywords: Win11NATChange,WindowsNATShift,Win10ToWin11NAT,Win10NATAdjustment,NATTransitionWin11,EffectiveNATTypeUpdate,Win10/11NATModification
thumbnail: https://thmb.techidaily.com/c739c4d92993cdf5c81414cb8125592c32746d89c1607964f11f2698f737ca9b.png
---

## Win11/10 NAT Transition: Altering Type Effectively

### Key Takeaways

* Changing the NAT type from strict to open can improve network connectivity and reduce network-related issues when playing multiplayer games online.
* You can change your NAT type on Windows by enabling Discovery Mode, UPnP, or port forwarding.
* Port forwarding provides greater control over open ports and enhances security compared to UPnP, but it requires knowing the specific TCP and UDP ports used by your game.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

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
<li><a href="https://audio-shaping.techidaily.com/updated-unveiling-the-premier-10-audio-reversal-tools-for-personal-computers-and-mobile-devices/"><u>Updated Unveiling the Premier 10 Audio Reversal Tools for Personal Computers & Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/excellent-video-recorders-for-desktops-for-2024/"><u>Excellent Video Recorders for Desktops for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/rating-playlist-videos-from-youtube-on-websites-for-2024/"><u>Integrating Playlist Videos From YouTube on Websites for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-subscriber-boost4-simplest-tricks-to-grow-your-channel-for-2024/"><u>YouTube Subscriber Boost–4 Simplest Tricks to Grow Your Channel for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-elevate-your-content-premier-youtube-rank-tracker-apps-for-2024/"><u>[Updated] Elevate Your Content  Premier YouTube Rank Tracker Apps for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-top-ways-to-make-fast-motion-video-on-iphone-solved/"><u>2024 Approved Top Ways to Make Fast Motion Video on iPhone Solved</u></a></li>
<li><a href="https://extra-resources.techidaily.com/intrinsic-storytelling-principles/"><u>Intrinsic Storytelling Principles</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-exploring-the-depths-of-online-voice-recording-beyond-vocaroo/"><u>Updated Exploring the Depths of Online Voice Recording Beyond Vocaroo</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ow-to-make-a-stunning-lyric-video-with-lyric-video-maker/"><u>[New] How to Make a Stunning Lyric Video with Lyric Video Maker</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-realme-narzo-n53-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Realme Narzo N53 Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-on-walls-top-3-techniques/"><u>Fresh Start on Walls: Top 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-the-windows-11-guide-to-altering-fax-cover-pages/"><u>Getting Started: The Windows 11 Guide to Altering Fax Cover Pages</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-spot-and-defeat-keygen-malware-in-your-windows-os-environment/"><u>How to Spot & Defeat Keygen Malware in Your Windows OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-blue-screen-wins-unhandled-exception/"><u>How to Address Blue Screen: Win's Unhandled Exception</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/dubbing-videos-with-voiceovers-using-wondershare-filmora/"><u>Dubbing Videos With Voiceovers | Using Wondershare Filmora</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-15-online-and-desktop-platforms-to-create-gifs/"><u>Top 15 Online & Desktop Platforms to Create GIFs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-inspecting-and-cleaning-windows-logs/"><u>Mastering the Art of Inspecting & Cleaning Windows Logs</u></a></li>
<li><a href="https://win11.techidaily.com/must-remember-tips-for-clean-installation-of-windows/"><u>Must-Remember Tips for Clean Installation of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-linuxs-power-to-boost-android-on-windows/"><u>Leveraging Linux's Power to Boost Android on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/neutralizing-windows-update-triggers/"><u>Neutralizing Windows Update Triggers</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-strategies-for-background-blur-perfection-using-windows-11-photos-app/"><u>In-Depth Strategies for Background Blur Perfection Using Windows 11 Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-upgrade-error-0xc004f050/"><u>How to Fix the Windows Upgrade Error 0Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-newcomers-cheat-sheet-unlock-ps-editing-secrets/"><u>2024 Approved  Newcomer's Cheat Sheet  Unlock PS Editing Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-stopping-discords-autostart-and-updating-habits/"><u>Guide on Stopping Discord's Autostart & Updating Habits</u></a></li>
</ul></div>
