Title: No Internet Access on Windows PC
Role: Helpdesk Tier 1
Priority: High
User Impact: User unable to access internet or internal resources
Environment: Windows 11, WiFi

## Symptoms
- User reports no internet access
- Web pages fail to load

## Initial Triage Questions
- Are other users affected?
- Is the user connected to VPN?
- Has this worked earlier today?

## Steps Taken
1. Verified network adapter was enabled
2. Checked IP address and gateway configuration
3. Tested connectivity to public IP and DNS resolution

## Commands Used
ipconfig /all
ping 8.8.8.8
nslookup google.com

## Root Cause
Incorrect DNS configuration on client system

## Resolution
Manually configured system to use a known working DNS server

## Verification
User confirmed successful internet access

## Time to Resolve
15 minutes
