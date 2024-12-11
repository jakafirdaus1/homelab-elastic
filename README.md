# SIEM Home Lab: ELASTIC

<h2>Utilities Used</h2>

- <b>Elastic</b> 
- <b>Virtual Box</b>
- <b>Kali Linux</b>


<h2>Project Summary</h2>
In this project, i set up a home lab using Elastic SIEM and a Kali VM. I forwarded data from the kali VM to the SIEM through the Elastic Beats agent, then generated security events on the Kali VM using Nmap. Using the Elastic web interface, we queried and analyzed the logs, created a dashboard to visualize security events, and set up an alert to detect these events.</br>
</br>

<p align="center">
Generating Security Event:   </br>
<img src="https://i.imgur.com/ROEuxvu.png" height="80%" width="80%" alt="Creating Virtual Environment"/>
<br/>
<br/>
Execution Log: <br/>
<img src="https://i.imgur.com/ygKTccf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SIEM Dashboard:  <br/>
<img src="https://i.imgur.com/CkHnNy9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nmap scans rule:  <br/>
<img src="https://i.imgur.com/G6T1T89.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Action to the triggered rules:  <br/>
<img src="https://i.imgur.com/XDISiVp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 </p>
 - <b>Action: I set up an action in Elastic to send an email notification whenever a rule is triggered.</b></br>
<br />


<h2>Conclusion</h2>
This home lab offers a valuable environment for learning and practicing essential skills in security monitoring and incident response using Elastic SIEM. By completing this project, i gained hands-on experience with a SIEM, which enhanced my security monitoring skills.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
