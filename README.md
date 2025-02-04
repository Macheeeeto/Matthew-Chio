<h1>Failed RDP to IP Geolocation</h1>


<h2> Description </h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
I setup Azure Sentinel (SIEM) and connected it to a live virtual machine acting as a honey pot. This honey pot
is used as a way to attract hackers. The point of this project is to truly point out how vulnerable any company or small business is.
For a short period of time I'm able to observe live attacks (RDP Brute Force) from all around the world. 
I used a custom PowerShell script to 
look up the attackers Geolocation information and plotted it on an Azure Sentinel Map using ipgeolocation.io

<h2> Skills Learned </h2>

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

<h2> Tools Used </h2>

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
<br />
<br />

![API](https://github.com/Macheeeeto/AzureSentinal-Lab/assets/135657145/d8d75dc3-8667-46e1-ac40-4b5a1ff03024)

<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer
  
<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from all around the world coming in; Custom logs being output with geodata</h2>

  ![Names](https://github.com/Macheeeeto/AzureSentinal-Lab/assets/135657145/1f67ee2a-8559-4b7f-b4c6-ee272e324f48)


<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2> 

![Map](https://github.com/Macheeeeto/AzureSentinal-Lab/assets/135657145/fa87627f-7c10-43af-b2b0-8d26b5a70605)



