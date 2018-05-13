# EDA491 Network Security Lab 2
# Peer review for Group 1 by Group 75

### 0: Formatting and formalities
- version missing

### 1: General
- multiple typos: pg 3 'meaans', pg 12 'emply', pg 5 'i the INPUT chain'
- minor grammar mistakes. Perhaps run a grammar check on the whole document?
- report refers to actors (eg. attackers) as 'he'. using 'they' is a better gender-neutral alternative

### 3: System configuration
- not stated which transport protocol (TCP or UDP) the services use
- 'Initial configuration' section appears twice (in pg 2 and in pg 3)

### 5: Firewall configuration
- for requirement on spoofed packets: only packets that originate on host are handled by the proposed rule. spoofed packets that originate outside are not handled
- in addition to TCP port 111, portmapper requires UDP port 111 to be opened

### 6: Correctness
- verification methods not detailed (eg. 4.1.4 simply says 'falsly crafted IP packets were issued', but doesn't say how)
- verification for rule ordering not performed

### 7: Discussion
- discussion of firewall statefulness (section 5.3) doesn't make sense

### 9: References
- unknown references in sections 2.2.4, 4.1.8
- citation no. 4 isn't formatted properly
