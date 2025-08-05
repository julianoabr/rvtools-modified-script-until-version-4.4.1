<h1 align="center">
📄<br Export RVTools Script - Modified Version
</h1>

## 📚 Export RVTools Script - Modified Version

> RVTools is a Windows .NET (4.6.2 or higher) application which uses VMware vSphere Management SDK 8.0 and CIS REST API to display information about your virtual environments. Interacting with VirtualCenter 5.x, ESX Server 5.x, VirtualCenter 6.x, ESX Server 6.x, VirtualCenter 7.0, ESX server 7.0, VirtualCenter 8.0 and ESX server 8.0.  RVTools is able to list information about VMs, CPU, Memory, Disks, Partitions, Network, CD drives, USB devices. Snapshots, VMware tools, vCenter server,Resource pools, Clusters, ESX hosts, HBAs, Nics, Switches, Ports, Distributed Switches, Distributed Ports, Service consoles, VM Kernels, Datastores, multipath info, license info and health checks.

The information can be exported to csv and xlsx file(s). With a xlsx merge utility it’s possible to merge muliple vCenter xlsx reports to a single xlsx report.

When you install RVTOOLs, in default directory (C:\Program Files (x86)\Robware\RVTools) you have a script called "RVToolsBatchMultipleVCs.ps1" I modified this to include more actions. 

- Link for RVTOOLS Main Page - [Click Here To Access](https://www.robware.net/rvtools/)
- Link for RVTOOLS Version Info - [Click Here to Read](https://www.robware.net/rvtools/version/)
- Link for RVTOOLS Download - [Click Here to Download](https://www.robware.net/rvtools/download/)

## Pre-Requirements

> Powershell version 5.1 or above

> Powercli version 10 or above

> RVTOOLS Version 4.4.4 (October 10, 2023) or below (now RVTOOLs belongs to DELL - this script is only for old versions.


## What this scripts does?

1. Connect on specified(es) vCenter(s)
2. Create folders according to year, month and day to store the RVTOOLs export (pt-br or en-us format)
3. If necessary, merge the generated .xlsx files
4. If configured and necessary, send an email with the generated RVTOOLs files
5. Connect with different credentials according to defined parameters

> I will create a new script for newer versions 

<div align="center">
  <br/>
  <br/>
  <br/>
    <div>
      <h1>Open Source</h1>
      <sub>Copyright © 2023 - <a href="https://github.com/julianoabr">julianoabr</sub></a>
    </div>
    <br/>
    📚
</div>



