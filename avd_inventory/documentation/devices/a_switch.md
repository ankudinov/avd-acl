# a_switch

## Table of Contents

- [Interfaces](#interfaces)
  - [Ethernet Interfaces](#ethernet-interfaces)
- [ACL](#acl)
  - [IP Access-lists](#ip-access-lists)

## Interfaces

### Ethernet Interfaces

#### Ethernet Interfaces Summary

##### L2

| Interface | Description | Mode | VLANs | Native VLAN | Trunk Group | Channel-Group |
| --------- | ----------- | ---- | ----- | ----------- | ----------- | ------------- |

*Inherited from Port-Channel Interface

#### Ethernet Interfaces Device Configuration

```eos
!
interface Ethernet1
   no switchport
   ip access-group ACL_SIMPLE_TEST in
   ip access-group ACL_SIMPLE_TEST out
```

## ACL

### IP Access-lists

#### IP Access-lists Configuration

```eos
ip access-list ACL_SIMPLE_TEST
   remark test acl without sequence numbers
   deny udp any any log
   permit icmp any any 3 4 ttl eq 40
   permit icmp any any unreachable ttl gt 3
```
