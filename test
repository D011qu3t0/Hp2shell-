**Critical unauthenticated RCE in PHP core**  
CVE-2026-109618 + CVE-2026-109619  
CVSS 9.2

> One name, two bugs: OOM corruption and stale global state that allow remote code execution before any application code runs.

## What this repository contains

| Component          | Purpose                                      |
|--------------------|----------------------------------------------|
| `scanner/`         | Behavioural detector (does not rely on version strings) |
| `exploit-kit/`     | Controlled research harness (proof-of-access only) |
| `docs/`            | Technical write-ups and timeline             |

## Quick start

```bash
git clone https://github.com/yourname/php2shell.git
cd php2shell

# Check if a target is exposed
./scanner/scan -u https://target.example.com

# Batch scan
./scanner/scan -l targets.txt -o results.json
