# Real Network Route Investigation

## Overview
This beginner cybersecurity networking lab investigates how traceroute behaves when tracing a route to Google's public DNS server (8.8.8.8).

Two traceroute methods were tested:
- UDP traceroute (default)
- ICMP traceroute

## Objective
- Understand traceroute.
- Observe network hops.
- Compare UDP and ICMP traceroute results.
- Learn about timeouts and network filtering.
- Document a real network diagnostic experiment.

## Target
- IP Address: 8.8.8.8
- Hostname: dns.google
- Purpose: Public DNS service

## Tools Used
- Kali Linux
- traceroute
- Terminal
- scrot

## Test 1: UDP Traceroute

### Command
```bash
traceroute -m 15 -q 1 -w 2 8.8.8.8

