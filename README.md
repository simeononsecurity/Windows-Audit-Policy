# Windows-Audit-Policy

[![VirusTotal Scan](https://github.com/simeononsecurity/Windows-Audit-Policy/actions/workflows/virustotal.yml/badge.svg)](https://github.com/simeononsecurity/Windows-Audit-Policy/actions/workflows/virustotal.yml)

Max out Windows Auditing

## Recommended reading material:
  - [auditpol](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/auditpol)
  - [auditpol clear](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/auditpol-clear)
  - [auditpol backup](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/auditpol-backup)
  - [auditpol restore](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/auditpol-restore)
  - [auditpol list](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/auditpol-list)

## How to run the script
### Manual Install:
If manually downloaded, the script must be launched from the directory containing all the other files from the [GitHub Repository](https://github.com/simeononsecurity/Windows-Audit-Policy)
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Force
Get-ChildItem -Recurse *.ps1 | Unblock-File
.\sos-auditpolicy.ps1
```
<a href="https://simeononsecurity.ch" target="_blank" rel="noopener noreferrer">
  <h2>Explore the World of Cybersecurity</h2>
</a>
<a href="https://simeononsecurity.ch" target="_blank" rel="noopener noreferrer">
  <img src="https://simeononsecurity.ch/img/banner.png" alt="SimeonOnSecurity Logo" width="300" height="300">
</a>

### Links:
- #### [github.com/simeononsecurity](https://github.com/simeononsecurity)
- #### [simeononsecurity.ch](https://simeononsecurity.ch)
