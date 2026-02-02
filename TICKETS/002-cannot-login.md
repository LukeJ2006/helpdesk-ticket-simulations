Title: User Unable to Log In
Role: Helpdesk Tier 1
Priority: High
User Impact: User cannot access workstation or company resources
Environment: Windows 11, Domain-joined system

## Symptoms
- User receives incorrect password error
- User unable to log in to Windows

## Initial Triage Questions
- Is the user typing the correct username?
- Has the password recently been changed?
- Is the account locked?
- Are other users affected?

## Steps Taken
1. Verified correct username format
2. Checked account lockout status
3. Confirmed password expiration policy
4. Reset user password and unlocked account

## Tools Used
Active Directory Users and Computers

## Root Cause
User account was locked due to multiple failed login attempts

## Resolution
Unlocked user account and reset password

## Verification
User successfully logged in to workstation

## Time to Resolve
10 minutes
