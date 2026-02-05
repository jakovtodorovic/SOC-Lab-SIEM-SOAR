<h1>SOC Detection & Response Lab (SIEM + SOAR)</h1>

<h2>Description</h2>

This project demonstrates the design and implementation of a SOC-style
detection and response environment using open-source tools.

The lab integrates Wazuh SIEM, Shuffle SOAR, and IRIS Incident Response
to detect and automatically respond to simulated attacks based on
the MITRE ATT&CK framework.

Attacks were executed from a Kali Linux host against a Windows Active
Directory environment to validate detection accuracy and response workflows.

<h2>Technologies Used</h2>

- <b>Wazuh SIEM</b>
- <b>Shuffle SOAR</b>
- <b>IRIS Incident Response</b>
- <b>MITRE ATT&CK</b>
- <b>Active Directory (Windows Server)</b>
- <b>Sysmon</b>
- <b>Kali Linux</b>

<h2>Lab Environment</h2>

- <b>VMware Workstation</b>
- <b>Windows Server 2019 (Domain Controller)</b>
- <b>Windows 10 Clients</b>
- <b>Ubuntu Server (SIEM / SOAR)</b>
- <b>Kali Linux (Attacker)</b>

<h2>Detection & Response Walkthrough</h2>

<p align="center">
Architecture overview:<br/>
<img src="https://imgur.com/a/9tOKYs5" width="80%"/>
<br/><br/>

SIEM detection mapped to MITRE ATT&CK:<br/>
<img src="images/wazuh-alert.png" width="80%"/>
<br/><br/>

Automated SOAR response workflow:<br/>
<img src="images/shuffle-playbook.png" width="80%"/>
<br/><br/>

Incident handling in IRIS:<br/>
<img src="images/iris-incident.png" width="80%"/>
</p>

<h2>Notes</h2>

This project was developed as part of a Master's final thesis and adapted
for portfolio demonstration purposes.
