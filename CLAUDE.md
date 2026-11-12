# DISA STIG scripts

Project instructions for Claude. Client: Personal.

## What this is
PowerShell scripts that remediate individual DISA STIG controls on Windows 10. Each file is named after its STIG ID.

## How to run it
Run a script in an elevated PowerShell session on a test VM, then re-scan to confirm the finding is fixed.

## Rules for this project
- One control per file, named by STIG ID. Never run against a production machine without a backup.
