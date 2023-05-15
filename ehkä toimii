# via Powershell
$PSVersionTable.PSVersion.Major
# via Registry
(Get-ItemProperty -Path 'HKLM:\SOFTWARE\Microsoft\PowerShell\1\PowerShellEngine').PowerShellVersion # Versions 1
and 2
(Get-ItemProperty -Path 'HKLM:\SOFTWARE\Microsoft\PowerShell\3\PowerShellEngine').PowerShellVersion # Versions 3
and 4
# via Remote
Invoke-Command -ComputerName $computer -ScriptBlock { $PSVersionTable.PSVersion.Major }
