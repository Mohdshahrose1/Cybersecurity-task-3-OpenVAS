# Task 3: Vulnerability Scan Using OpenVAS

## Objective
Perform a basic vulnerability scan on a personal computer using OpenVAS Community Edition to identify common security issues.

## Tools Used
- **OpenVAS Community Edition** (via Greenbone GVM)
- **Windows CMD** for IP discovery

## Target
- **Localhost IP**: ----------
- **Scan Type**: Full vulnerability scan

## Deliverables
- Vulnerability scan report
- Documentation of findings

## Files Included
- `get_ip.cmd`: Script to capture IP address
- `ip_report.txt`: Output of IP discovery
- `scan_report.md`: Summary of scan findings

## Scan Summary
The scan was successfully executed using OpenVAS on the local machine.  
**Result**: No vulnerabilities were detected.

| Host       | High | Medium | Low | Log | False Positive |
|------------|------|--------|-----|-----|----------------|
| Localhost  | 0    | 0      | 0   | 0   | 0              |

## Analyst Reflection
This scan confirms that the system is currently free of known vulnerabilities based on OpenVAS definitions and QoD filtering.  
While no issues were found, it's recommended to:
- Keep system packages and services updated
- Re-scan periodically or after major changes
- Use external scans for broader network visibility
