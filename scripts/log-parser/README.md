# Log Parser

A Python script that scans system/application log files for suspicious patterns 
(failed logins, repeated access attempts, unusual timestamps) and flags entries 
that match common indicators of compromise.

## How to run
python log_parser.py --file /var/log/auth.log --pattern failed_login

## What I learned
Writing the regex patterns for different log formats taught me how inconsistent 
log structures are across systems, and why real SIEM tools normalize logs before 
analyzing them rather than parsing raw text directly.
