<h1>Microsoft Windows Defender and Firewall</h1>

<h2>Description</h2>
In these projects you will locate Microsoft Windows Security Virus and Threat Protection Settings, Run Microsoft Windows Defender Antivirus Quick Scan and Configure Microsoft Windows Firewall Rules 

<h2>Operating System Used<h2>

- <b>MacOS Monterey Version 12.7.4</b>

<h2>Project # 1- Microsoft Windows Defender Antivirus<h2>
You’ll access and review Windows Security Virus & threat protection. Windows Defender Virus & threat protection is a built-in security feature that scans for threats on your system.


<h2>Project walk-through:</h2>

<p align="center"> 
Click the Windows Start button and select Settings: <br/>
<img src="https://i.imgur.com/5Z8AWdx.png" height="80%" width="80%" />
<br />
<br />
On the Windows Settings page, select Privacy & Security -> Windows Security.: <br/>
<img src="https://i.imgur.com/3uv5nIc.png" height="80%" width="80%" />
<br />
<br />
Select Virus and threat protection: <br/>
<img src="https://i.imgur.com/y49EXfj.png" height="80%" width="80%" />
<br />
<br />
On this screen, you’ll see the following features: <br/>
Current threats: Here, you can see any threats that have been detected on your device. You can see when the last scan occurred, how long the scan took, and how many files were scanned. Here you can also click the button to start a quick scan or access scan options to run a full scan or a custom scan. Virus and threat protection settings: Here, you can access options for managing your virus and threat protection settings. You can customize your protection level, opt to send sample files to Microsoft, exclude files or folders from scans, or temporarily stop your protection.
Virus and threat protection updates: Here, you can view the last time your virus definitions were updated. You can also opt to manually check for updates.
Ransomware protection: Here, you can choose to enable controlled folder access. This protects memory, files, and folders from unauthorized changes.:  <br/>
<img src="https://i.imgur.com/tKwa4lj.png" height="80%" width="80%" />
<br />
<br />
Under Virus & threat protection updates, select Protection updates:  <br/>
<img src="https://i.imgur.com/mdzIUjT.png" height=80%" width="80%" />
<br />
<br />
You can view details for the most recent update to your threat definitions. Select Check for updates. This process could take a few minutes. When the update has completed, the Check for updates button will return, and you should notice that the last update time and date have changed. Select the back button to return to the Virus & threat protection screen.:  <br/>
<img src="https://i.imgur.com/D3UAlEb.png" height="80%" width="80%" />
<br />
<br />
Now we can run an antivirus scan. Click the Quick scan button on the Virus & threat protection screen. The scan will take several minutes to run. When complete, the Quick scan button will reappear. <br/>
<img src="https://i.imgur.com/2F2urC0.png" height="80%" width="80%" />
<br />
<br />
Click Protection history to view any recent findings.This page shows you the results of the last scan. You see the files identified as a threat and quarantined, so they cannot damage your device. You then see files identified as potential threats but allowed to continue running.
  <br/>
<img src="https://i.imgur.com/xQeT8Uo.png" height="80%" width="80%" />
<br />
<br />

<h2>Project # 2- Microsoft Windows Defender Firewall<h2>
Windows Defender Firewall is a host-based software firewall that is included with the Windows operating system. In this lesson we will learn to configure firewall rules using Windows Defender Firewall and Windows Defender Firewall with Advanced Security.

<h2>Project walk-through:</h2>

<p align="center"> 
Click the Windows Start button -> Privacy and Security -> Windows Security -> Firewall and Network Protection . <br/>
<img src="https://i.imgur.com/BF9S2vr.png" height="80%" width="80%" />
<br />
<br />
Navigate to "Logs" in Elastic to view logs fron Kali VM  <br/>
<img src="https://i.imgur.com/aj1TnOD.png" height="80%" width="80%" />
<br />
<br />
Filter the results by using "Search"  <br/>
<img src="https://i.imgur.com/byjLPJn.png" height="80%" width="80%" />
<br />
<br />
Click on the menu icon on the top-left, then under “Analytics,” click on “Dashboards.” -> Create a Dashboard to Visualize the Events  <br/>
<img src="https://i.imgur.com/BPXi94a.png" height="80%" width="80%" />
<br />
<br />
Click on the “Create Visualization” button to add a new visualization to the dashboard <br/>
Select “Area” or “Line” as the visualization type. This will create a chart that shows the count of events over time. <br/>
In the “Metrics” section, select “Count” as the vertical field type and “Timestamp” for the horizontal field. This will show the count of events over time. <br/>
<br />
<br /> 
Click on the “Save” button to save the visualization and then complete the rest of the settings. <br/>
<img src="https://i.imgur.com/3CYbLef.png" height="80%" width="80%" />
<br />
<br /> 
Set an "ALERT" -> Click on the menu icon on the top-left, then under “Security,” click on “Alerts.” <br>
<img src="https://i.imgur.com/FC6LSnF.png" height="80%" width="80%" />" 
<br />
<br /> 
Click on the “Create new rule” button at the top right <br>
Under the “Define rule” section, select the “Custom query” option from the dropdown menu <br>
Under “Custom query,” set the conditions for the rule <br>
Set the severity level for the alert. Keep all the other default settings under “Schedule rule” and click “Continue.” <br>
<br />
<br /> 
Finally, click the “Create and enable rule” button to create the alert. Once you’ve created the alert, it will monitor your logs for Nmap scan events <br>
<img src="https://i.imgur.com/YaLzbD3.png" height="80%" width="80%" />" 






