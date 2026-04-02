# Detailed Usage Guide

## Command line arguments (not implemented yet – interactive only)

Currently the scanner is fully interactive. Future versions will support CLI arguments.

## Understanding the severity levels

- **Critical** – Immediate action required (e.g., SQLi, RCE, exposed secrets).
- **High** – Severe risk (XSS, open redirect, weak TLS).
- **Medium** – Should be fixed (CORS misconfig, missing security headers).
- **Low** – Best practice issues (info disclosure, missing cache headers).
- **Info** – Reconnaissance data (subdomains, open ports).

## Example scan of a test target

```bash
python dragon_scanner.py
Target: http://testphp.vulnweb.com
# ... output ...
