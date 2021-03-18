# PowerShell.

Windows PowerShell is based on .NET Standard and is feature complete. 

PowerShell Core is the new version and it is based on .NET Core. Can be downloaded from GitHub and runs on all OSs. It is open source. Has a subset of Windows PowerShell commands.

Verb-Noun = Do something-To something

Parameters used to pass information into PowerShell commands. All parameters are called with a dash (-).

Three important commands are Get-Command Get-Help Get-Member.

PowerShell treats Data as Objects. Pipelining in PowerShell is to send the output of a command into another.
	
Troubleshooting - identify the issues > find root cause > determine and implement a solution > verify results. Get-NetFirewallRule -Name *remotedesktop* | Format-Table  Get-NetFirewallRule -Name *remotedesktop* | Set-NetFirewallRule -Enabled True -WhatIf
