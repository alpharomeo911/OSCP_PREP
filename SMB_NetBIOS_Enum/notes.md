# NetBIOS and SMB Enum

> Part of Windows system enumeration

### Important tools

**smbclient**

**smbmap**
> Before using note that this tool tries to upload files over the smb, so it can get caught.

We can also mount smb over linux system.

Files can be viewed by following commands

smbclient ////< IPADDRESS >//


### Some important Vulnerabilities

**MS17-010** 

Also known as eternal blue.

Can give remote code execution.

Must use autoblue and check if the system is vulnerable or not.


***This list/info is incomplete, and will be updated later on.***