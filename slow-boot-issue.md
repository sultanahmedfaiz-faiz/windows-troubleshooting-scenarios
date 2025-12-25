# Scenario 1: Slow Boot Issue on Windows 11

## Issue Description
User reported that their Windows 11 laptop takes more than 4 minutes to boot and
become usable after login.

## Environment
- Operating System: Windows 11 Pro
- Device Type: Laptop
- Storage: SSD
- Network: Corporate Wi-Fi
- Domain Joined: Yes

## Initial Checks
- Confirmed issue with user
- Verified no recent hardware changes
- Checked available disk space

## Troubleshooting Steps
1. Opened Task Manager → Startup tab
2. Identified unnecessary startup applications
3. Disabled third-party startup apps
4. Checked system integrity using: sfc /scannow
5. Restarted system to verify results

## Root Cause
Multiple third-party applications configured to run at startup, increasing boot time.

## Resolution
Disabled unnecessary startup applications and verified system file integrity.

## Outcome
Boot time reduced from approximately 4 minutes to under 1 minute.
User confirmed improved performance.
