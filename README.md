# AIO-AL
A python script used for personal use to quickly and portably log useful information about the machine's hardware and network connections

This script logs various information about computer, it's hardware and network connections

Features:
- Separate logs between folders; "Network Map Logs" & "System Info Logs"
- Logs are
- Get Computer Name
- Get Computer Manufacturer information
- Get BIOS Version
- Get OS Information
- Get System Directories
- Get Processor type
- Get System Time Zone
- Get System Language
- Get System Product ID
- Get System Boot Time
- Get System Model
- Get RAM Information
- Get Network Card(s)
- Get IPV4 Address
- Get Public IP
- Get Active Internal Connections

View [AIO-AL Releases](https://github.com/smcclennon/AIO-AL/releases)

Example Logs: [System Log](Example Output/System Info Logs/Cobalt.log), [Network Logs](Example Output/Network Logs/Cobalt [192.168.0.32].log)

[AIO-AL](https://i.imgur.com/i7UWfoa.png)

Requirements:
- Python 3+
- Windows
- An internet connection*
- [psutil](https://pypi.org/project/psutil/)
- [requests](https://pypi.org/project/requests/)

*This will be changed in a later version


First version of AIOAL (v1) coded on 10/11/18, completed at 5:30pm

Written in Python 3.7.4 on Windows 10