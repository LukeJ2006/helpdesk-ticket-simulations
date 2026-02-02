Title: Network Printer Showing Offline
Role: Helpdesk Tier 1
Priority: Medium
User Impact: User unable to print documents
Environment: Windows 11, Network printer

## Symptoms
- Printer status shows offline
- Print jobs stuck in queue

## Initial Triage Questions
- Is the printer powered on?
- Are other users affected?
- Has the printer worked recently?

## Steps Taken
1. Verified printer power and network connection
2. Checked printer IP address
3. Restarted print spooler service
4. Cleared stuck print jobs
5. Re-added printer using correct IP address

## Tools Used
- Devices and Printers
- Services (Print Spooler)

## Root Cause
Printer IP address changed due to DHCP lease renewal

## Resolution
Reconfigured printer using correct static IP address

## Verification
Test page printed successfully

## Time to Resolve
20 minutes
