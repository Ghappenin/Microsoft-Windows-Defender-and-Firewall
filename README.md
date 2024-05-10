<h1>Microsoft Windows Defender and Firewall</h1>

<h2>Description</h2>
In these projects you will locate Microsoft Windows Security Virus and Threat Protection Settings, Run Microsoft Windows Defender Antivirus Quick Scan and Configure Microsoft Windows Firewall Rules 

<h2>Operating System Used<h2>

- <b>MacOS Monterey Version 12.7.4</b>

<h2>Project # 1- Windows Defender Antivirus<h2>
You’ll access and review Windows Security Virus & threat protection. Windows Defender Virus & threat protection is a built-in security feature that scans for threats on your system.


<h2>Project walk-through:</h2>

<p align="center">
Download VirtualBox: <br/>
<img src="https://i.imgur.com/TrQnZkK.png" height="80%" width="80%" />
<br />
<br />
Download Kali Linux: <br/>
<img src="https://i.imgur.com/M6gccC7.png" height="80%" width="80%" />
<br />
<br />
Using '+' add Kali Linux download to VirtualBox: <br/>
<img src="https://i.imgur.com/eoJHcJ9.png" height="80%" width="80%" />
<br />
<br />
With "Start" launch Kali Box:  <br/>
<img src="https://i.imgur.com/E0s7KwZ.png" height="80%" width="80%" />
<br />
<br />
Log into Elastic SIEM -> Navigate to 'Integrations' -> Download "Elastic Defend":  <br/>
<img src="https://i.imgur.com/BXmTwTc.png)height=" height=80%" width="80%" />
<br />
<br />
Paste command into Kali Terminal -> "ENTER" for install:  <br/>
<img src="https://i.imgur.com/NyjiXmG.png" height="80%" width="80%" />
<br />
<br />
Once message “Elastic Agent has been successfully installed.” It will automatically start collecting and forwarding logs to your Elastic SIEM  <br/>
<img src="https://i.imgur.com/AW19rNt.png" height="80%" width="80%" />
<br />
<br />
Verify that the agent has been installed correctly by running this command: sudo systemctl status elastic-agent.service  <br/>
<img src="https://i.imgur.com/BSbRH5o.png" height="80%" width="80%" />
<br />
<br />
Create Security Events by using "Nmap" (“nmap -sS <ip address>”, “nmap -sT <ip address>”, “nmap -p- <ip address>”etc..) <br/>
<img src="https://i.imgur.com/zCVJzfU.png" height="80%" width="80%" />
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






