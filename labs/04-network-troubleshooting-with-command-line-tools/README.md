# Lab 04 - Network Troubleshooting with Command Lines Tools

## Objective
- Use Windows command line tools to diagnose and troubleshoot network connectivity issues.

## Lab Environment
- Personally built computer - Windows 11
- Command prompt (cmd)
- Active internet connection

## Tools Used
- "ipconfig"
- "ping"
- "tracert"
- "nslookup"
- "netstat"
- "pathping"

## Commands Practiced

### 1. ipconfig
Displays IP configuration information
- Command used > ipconfig /all

### 2. ping
- Tests connectivity to another device or website 
- Command used > ping google.com

### 3. tracert
- Shows the path patch packets take to a destination
- Command used > tracert google.com

### 4. nslookup
- Resolves domain names to IP addresses
- Command used > nslookup google.com

### 5. netstat
- shows active connections and ports
- Command used > netstat

### 6. pathping
- Combines both ping and tracert
- command used > pathping google.com

## Steps Performed

### 1. Check IP Configuration
- Opened Command Prompt
- Ran > ipconfig /all
- Verified IP address, subnet mask and default gateway

### 2. Test Network Connectivity
- Ran > ping google.com
- COnfirmed successful replies and response times

### 3. Trace Network Route
- Ran > tracert google.com
- Observed the path and hops to the destination

### 4. Resolve Domain Name
- Ran > nslookup google.com
- Verified domain resolved to an IP address

### 5. Simulate a Network Issue
- Disabled network adapter
- Ran > ping google.com
- Observed "Could not find host" error

### 6. Troubleshoot the Issue
- Reenabled network adapter
- Ran > ping google.com to verify

## Results
- Successfully used command line tools to verify connectivity, trace network paths, and resolve domain names

## Issues Encountered 
- Experienced "Could not find host" during simulated network failure

## Resolution
- Reenabled network adapter and restored network connection

## Key Takeaways
