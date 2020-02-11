## Device Documentation

| Hostname | MGMT IP Address |   
| :--- | ---:|   
| LEAF101 | 10.10.10.1 |   
| LEAF102 | 10.10.10.2 |   
| LEAF103 | 10.10.10.3 |   
| LEAF104 | 10.10.10.4 |   
| LEAF105 | 10.10.10.5 |   
| LEAF106 | 10.10.10.6 |   

## Config Example

```
hostname LEAF101
!
interface Lookback0
   ip address 10.10.10.1/32
!
ntp-server 10.50.100.10
ntp-server 10.50.100.11

syslog host 10.50.102.10

banner - Miami
```
