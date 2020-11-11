# Scan Me Now
A python script used for personal use to quickly and portably log useful information about the machine's hardware and network connections

This script logs various information about computer, it's hardware and network connections

<a href="https://github.com/smcclennon/SMN/releases/latest/download/SMN.py"><img src="https://smcclennon.github.io/update/download.png"></a>

## Features

- Automatic Updates
- Sort logs In folders; "Network Logs" & "System Info Logs"
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

## Installation
The script is designed to be ran from a USB drive, but you can also download the latest release directly onto the target machine.

#### Requirements:
- Python 3.6+ (On a USB* or on the target machine)
- Windows 10
- [psutil](https://pypi.org/project/psutil/)

*\*If you are planning to use a python install from the USB, please create a shortcut to run the script using Python on the flash drive.*

## Screenshots
Example Output: [System Info Logs](Example%20Output/System%20Info%20Logs/Cobalt.log) - [Network Logs](Example%20Output/Network%20Logs/Cobalt%20%5B192.168.0.32%5D.log)

![SMN](https://imgur.com/i7UWfoa.png)

## Story

SMN was originally named AIO-AL (All In One - Automatic Logger), quite the mouthful, I know.

I created this script in late 2018, due to my curiosity about my college's computer hardware and internal network connections. AIO-AL's goal was to log computer information and hardware into an organised folder with appropriate filenames (computer names), and was to do the same with network logs.

Creating this script in python was my first experience with file handling. I used os-commands to generate information into temporary files, which AIO-AL would then append into the log file.

The script was portable, and I gathered information about the different types of computers in my college by running AIO-AL via a USB. The organised log files split into two folders, computer information & network logs made it easy to compare information between computers. I learnt a great deal about the computers such as how much RAM they had, which network cards they had installed (both physical and virtual), their domain, logon server, and OS version.

### The name change

AIO-AL's project name was changed to SMN [[v2.0.0](https://github.com/smcclennon/SMN/releases/tag/v2.0.0)] shortly after [LTFO](https://github.com/smcclennon/LTFO)'s name was changed. My [API](https://smcclennon.github.io/update/api) had already been created and was already in use by [LTFO](https://github.com/smcclennon/LTFO) at this time, so SMN began using it right away.

The only features which came to light after SMN experienced its name change were the **ability to choose your scan type**, as doing a full scan would take upwards of **two minutes**, but when excluding the `current TCP/IP network connections` from the `network scan`, SMN only takes **~5 seconds** to do a `full system scan` and a `network scan` (excluding `current TCP/IP network connections` of course).

First version of AIOAL (v1) created on 10th November 2018, completed at 5:30pm

Written in Python 3.7.4 on Windows 10

<a href="https://www.freepik.com/free-photos-vectors/menu">Menu vector created by freepik - www.freepik.com</a>
