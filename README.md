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
Click Domain network  <br/>
<img src="https://i.imgur.com/utn6MKs.png" height="80%" width="80%" />
<br />
<br />
Verify that the Windows Defender Firewall is toggled to On -> Select the back arrow button to return to the Firewall and network protection window.  <br/>
<img src="https://i.imgur.com/b4n4bIJ.png" height="80%" width="80%" />
<br />
<br />
Click Allow an app through firewall.  <br/>
<img src="https://i.imgur.com/mi5AHuJ.png" height="80%" width="80%" />
<br />
<br />
Scroll to google Chrome OR Mozilla Firefox. Observe in the screenshot below that the current configuration allows for Firefox to communicate on the Private network only but denies it from communicating on the Public network.
 <br/>
<img src="https://i.imgur.com/ZIvm4go.png" height="80%" width="80%" />
<br />
<br /> 
Select Advanced settings on the Firewall & network protection screen. <br/>
<img src="https://i.imgur.com/EkbDH4X.png" height="80%" width="80%" />
<br />
<br /> 
Make special note of the two rule types listed on the left panel -> Inbound rules: Inbound rules determine what traffic is allowed to the computer. -> Outbound rules: Outbound rules determine what traffic is allowed to leave the computer. Click Inbound Rules: <br>
<img src="https://i.imgur.com/iPEBxfx.png" height="80%" width="80%" />" 
<br />
<br /> 
Here you will see a long list of inbound rules. Note that some of the rules have a green checkmark next to them. This indicates that the rule is enabled to allow inbound communication. The rules without a checkmark are available for use but are not enabled. <br>
<img src="https://i.imgur.com/E79wruu.png" height="80%" width="80%" />" 
<br />
<br /> 
Scroll to the Key Management Service inbound rule in the Overview panel of Windows Defender Firewall with Advanced Security -> Double-click this rule.
 <br>
<img src="https://i.imgur.com/XYbsMxX.png" height="80%" width="80%" />" 
<br />
<br /> 
Here you will see the details of this rule. You will note that the General tab includes the name of the rule, a description of the rule, and whether the rule has been allowed or blocked -> Click the Advanced tab <br>
<img src="https://i.imgur.com/d0iVnbQ.png" height="80%" width="80%" />" 
<br />
<br /> 
Here you will see which profiles the rule applies to. In this case, Domain, Private and Public are all selected.  <br>
<img src="https://i.imgur.com/ABa4XO8.png" height="80%" width="80%" />" 
<br />
<br /> 
Because we want to allow communication only with the domain and private networks, For Public this box should not have a checkmark. Next, click Apply, then click Ok. <br>
<img src="https://i.imgur.com/dqQ5dhv.png" height="80%" width="80%" />" 
<br />
<br /> 
Now we will create an inbound rule that blocks communication with the public network. Since the new rule will be similar to the last, we will copy the existing rule. Right-click the Key Management Service (TCP-In) inbound rule and click Copy. Press Ctrl+V to paste. <br>
<img src="https://i.imgur.com/13Oxfxr.png" height="80%" width="80%" />" 
<br />
<br /> 
Since we want to block connection with the public network, select Block the connection on the General tab. Click Apply.  <br>
<img src="https://i.imgur.com/YaLzbD3.png" height="80%" width="80%" />" 
<br />
<br /> 
Click the Advanced tab -> Click the Domain and Private boxes to remove the checkmarks. Click the Public to add the checkmark. Click Ok. <br>
<img src="https://i.imgur.com/FC6LSnF.png" height="80%" width="80%" />" 
<br />
<br /> 
The Overview panel will show your changes. Right-click each Key Management Service (TCP-In) rule and click Enable rule. <br>
<img src="https://i.imgur.com/YaLzbD3.png" height="80%" width="80%" />" 
<br />
<br /> 
Now you will see that a green checkmark appears next to the first rule indicating that the rule allowing communication is enabled. A circle with a line through it appears next to the second rule indicating that the rule blocking communication is enabled. <br>
<img src="https://i.imgur.com/YaLzbD3.png" height="80%" width="80%" />" 
<br />
<br /> 







