## Device Documentation

| Hostname | MGMT IP Address | Node Type
| :--- | :---| :--- |
| SPINE1 | 192.168.1.250 | spine
| SPINE2 | 192.168.1.251 | spine
| LEAF1A | 192.168.1.252 | leaf
| LEAF1B | 192.168.1.253 | leaf
&nbsp;
&nbsp;

## Config Example

```
hostname LEAF101
!
interface Lookback0
   ip address 10.10.10.1/32
!
ntp-server 10.50.100.10
ntp-server 10.50.100.11
!
syslog host 10.50.102.10
```
