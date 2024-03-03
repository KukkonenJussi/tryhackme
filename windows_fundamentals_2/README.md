<h3>Windows Fundamentals 2</h3>

Part 2 discovers more about System Configuration, UAC Settings, Resource Monitoring, the Windows Registry. Let's use the machine with the following command:

`xfreerdp /v:ip_address /u:administrator /p:letmein123!`

The System Configuration utility (`MSConfig`) is for advanced troubleshooting, and its main purpose is to help diagnose startup issues. More info about the MSConfig [here](https://learn.microsoft.com/en-us/troubleshoot/windows-client/performance/system-configuration-utility-troubleshoot-configuration-errors).

First questions are about System Configuration:

![](src/image.png)
![](src/image-1.png)

The module continues with the `Computer Management` (`compmgmt`) utility which has three primary sections: `System Tools`, `Storage` and `Services and Application`

![](src/image-2.png)

Next, the `System Information` (`msinfo32`) tool. It is divided into three sections:

- Hardware Resources
- Components
- Software Environment

![](src/image-3.png)

Then we take a quick look at `Resource Monitor` (`resmon`). In the Overview tab, Resmon has four sections:

- CPU
- Disk
- Network
- Memory

![](src/image-4.png)

We continue with Tools that are available through the `System Configuration` panel. The command prompt (cmd) is a way to interact with the operating system without a graphical user interface. The commands are close what Linux uses.

![](src/image-5.png)

The `Windows Registry` is a central hierarchical database used to store information necessary to configure the system for one or more users, applications, and hardware devices.

The registry contains information that Windows continually references during operation, such as:

- Profiles for each user
- Applications installed on the computer and the types of documents that each can create
- Property sheet settings for folders and application icons
- What hardware exists on the system
- The ports that are being used.

![](src/image-6.png)
