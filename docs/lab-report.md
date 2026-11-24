# Suricata IDS — Lab report worksheet

**Experiment date:** To fill

**Sensor OS:** To fill  
**Suricata version:** 8.0.3 (observed in config screenshot; verify installed binary)  
**Sensor interface / address:** To fill  
**Test VM / address:** To fill  
**HOME_NET:** To fill

## Test records

| Test | Command used | Actual alert SID | Observed timestamp | Pass/Fail | Notes |
|---|---|---|---|---|---|
| ICMP Echo | `ping -c 4 TARGET_IP` | | | | |
| TCP SYN probes | `sudo nmap -sS -Pn -p 1-100 TARGET_IP` | | | | |
| SSH port attempt | `nc -vz -w 2 TARGET_IP 22` | | | | |

## Findings

_To complete only after observing results._

## False positives and limitations

A TCP SYN packet is not by itself evidence of malicious scanning; TCP port 22 connection attempts are not by themselves evidence of brute force.

## Evidence

Link only sanitized, real screenshots from `../screenshots/`.
