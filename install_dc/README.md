# Installing the Domain Controller

1. User 'sconfig' to: 
    - change hostname
    - change IP address to static
    - change the DNS server to our own IP address

2. Install the Active Directory Windows Feature

```shell
    Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```