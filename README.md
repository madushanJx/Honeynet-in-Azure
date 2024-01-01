# Honeynet-in-Azure

## Description
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

## Languages Used
PowerShell: Extract RDP failed logon logs from Windows Event Viewer
![Screenshot 2024-01-01 181808](https://github.com/ravana-one/Honeynet-in-Azure/assets/53973045/bc067232-1887-451a-bdd8-d709b8e51d78)

## Utilities Used
ipgeolocation.io: IP Address to Geolocation API
![68747470733a2f2f692e696d6775722e636f6d2f6b725246724b352e706e67](https://github.com/ravana-one/Honeynet-in-Azure/assets/53973045/ad91a3f7-9662-48d2-beca-1009c5148c33)
