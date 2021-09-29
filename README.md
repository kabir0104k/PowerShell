# PowerShell

## Basic Commands 
```bash
> cd cd\ cd..(Change Directory)
> New-Item ABC -ItemType Directory(Creating Folder)
> md/mkdir(Creating Folder)
> md/mkdir"ABC 123"(Space Between Folder Names)
> dir/gci/ls/Get-ChildItem(Files List)
> cls(Clear Screen)
> xcopy/cp/copy{Name With Extension} "Folder Name" (Copy Single File)
> xcopy/cp/copy{(*).Only Extension} "Folder Name" (Copy All File)
> Move/Mv{Name With Extension} "Folder Name" (Move Single File)
> Move/Mv{(*).Only Extension} "Folder Name" (Move All File)
> cd  Move abc.txt "C:\users\KABIR\Desktop (Move From Folder)
> del (.Extension)
> del (*.Extension)
```

---------
### Tasks & Services
```bash
> New-Item abc.html/mp3/mp4/zip(Exporting Any Extension File)
> type nul>abc.txt/jpg/zip/mp3/mp4(Exporting Any Extension File)
> Get-Command(All Existing Command)
> tasklist (Show All Running Task)
> taskkill /pid No. (To Kill Task)
> net start (For Starting Services)
> net stop/start "Target" (For Stopping Services)
> Show-NetFirewallRule(Show InBound/OutBound Rule)
> driverquery(Installed Driver List)
> date(Current Date&Time)
> timezone(Current TimeZone)
```

---------
## System Info
```bash
> systeminfo/msinfo32/Get-ComputerInfo(System Info)
> Get-WmiObject win32_processor(Processer Info)
> chkdsk (Health Status Of HDD)
> Diskpart>List Disk>Select Disk 2>Detail Disk(Hardrive Details)
> winver(For Windows Version)
> Get-WmiObject win32_product(Installed Software List)
> Invok-History/H/History(PowerShell Current History)
```

---------
## Basic Network Essential
```bash
> ipconfig (For Getting Ip Address)
> Get-NetIPConfiguration(Connected Ip)
> tracert www.google.com (For Tracing Route Towards Destination)
> Get-NetAdapter(Physical Adaptor Details)
> Disable-NetAdapter "Wi-Fi" (Disable Wifi)
> Enable-NetAdapter "Wi-Fi" (Enable Wifi)
> nslookup www.google.com(For Converting Domain Into Ip)
> nslookup 172.217.161.4(For Converting Ip Into Domain)
> ping www.google.com(For Checking Connection)
```

---------
## Network Shell
```bash
> netsh Wlan Show Interface(Connected Adaptor Details)
> netsh wlan show profiles (For Connected Wifi Networks)
> netsh wlan show profile name=KABIR key clear (For Wifi Pass)
> netsh wlan show all (Networks Currently Visible)
> netsh advfirewall set all state off(Firewall Off)
> netsh advfirewall set all state on(Firewall On)
> netsh wlan delete profile name="KABIR"(Delete Connected Wifi)
> netsh wlan add profile filename="file.xml"(ReConnect Wifi)
```

---------
## User Management
```bash
> net user "Name" "Pass" /add (For Adding User)
> net user "Name" /del (For Deleting User)
> net user "Name" *(Bypass Password)
```

---------
## Drive Operations
```bash
> $pass = ConvertTo-SecureString "123456" -AsPlainText -Force
> Enable-Bitlocker -MountPoint D: -EncryptionMethod Aes128 -pin $pass(Enable Bitlocker)
> Disable-Bitlocker(Disable Bitlocker)
> Format-Volume"Select Drive"(Format Drive)
> echo ________  > Name.txt (Exporting Written Text File)
```

---------
## Interesting Commands
```bash
> Notepad Name.txt(File Direct Open In Notepad)
> date (Current Date)
> time (Current Time)
> shutdown -s -t 05 (Shutdown Pc)
> restart  -r -t 05 (Restart Pc)
> (Get-Item Abc.Extension).Encrypt
> (Get-Item Abc.Extension).Decrypt
> attrib +h +r +s  abc.Extension (Hide All File)
> attrib -h -r -s  abc.Extension (Show All File)
```
---------



#### Author / Creator : [`KABIR`](https://github.com/kabir0104k)
