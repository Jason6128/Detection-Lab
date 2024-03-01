## Soc automation Project 

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen my understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Deep comprehension of SIEM principles and their useful application.
- Skill in interpreting and evaluating host malicious.
- Capacity to create and identify patterns and signatures of attacks.
- Improved familiarity with security flaws and Event logs.
- The improvement of critical thinking and cybersecurity problem-solving abilities.

### Tools Used
- Security Information and Event Management (SIEM) system for logs and analysis.
- Use case management and document the case scenarios.
- Telemetry generation tools to create realistic malicious host and attack scenarios.

## Steps
<p align="center">
Home Lab Topology: <br/>
<img src="https://i.imgur.com/R0fa0cp.jpeg" height="80%" width="80%" />
<br />
<br />
  
<p align="center">
Windows 10 agents configuration: <br/>
<img src="https://i.imgur.com/CURPFMf.png" height="80%" width="80%" />
<br />
<br />
  
<p align="center">
Apply the Sysmon configuration: <br/>
<img src="https://i.imgur.com/JMknElA.png" height="80%" width="80%" />
 <br />
  This step should be first confirmed if the host another has sysmon conf already
<br />

<p align="center">
Cloud Host for wazuh service:  <br/>
<img src="https://i.imgur.com/A2A84eP.png" height="80%" width="80%" />
<br />
 <br /> 
  
## Prerequisites:
- DigitalOcean account with a running Ubuntu server.
- Basic knowledge of the steps.

## Step: Create a DigitalOcean Droplet
1. Log in to your DigitalOcean account.
2. Click on "Create Droplet."
3. Choose an image: Select the latest Ubuntu version.
4. Choose a plan and configure additional settings.
5. Click "Create Droplet."

<p align="center">
After the wazuh configuration: <br/>
<img src="https://i.imgur.com/eBlI75V.png" height="80%" width="80%" />
 <br />
<br />


<p align="center">
 Network configuration for the droplet: <br />
<img src="https://i.imgur.com/FRlareD.png" height="80%" width="80%" />
 <br />
  configuration of Firewall for our wazuh.
<br />


<p align="center">
 Accessing the wazuh-manager:  <br />
<img src="https://i.imgur.com/UAMSXtC.png" height="80%" width="80%" />
 <br />
<br />


<p align="center">
 Accessing the wazuh-manager:  <br />
<img src="https://i.imgur.com/5Jwj9lg.png" height="80%" width="80%" />
 <br />
 <br />




















  
</p>

