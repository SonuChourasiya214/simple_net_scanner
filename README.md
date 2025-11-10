# simple_net_scanner


**What:** Host discovery + common port scan for a CIDR or single IP. Lightweight, portable Python script.


**Files included**
- `simple_net_scanner.py` — main scanner script (Python 3.8+)
- `sample_scan_output.txt` — example output from a run (included below)
- `logo.txt` — small ASCII logo


## Requirements
- Python 3.8+
- No external packages required (uses `socket`, `ipaddress`, `concurrent.futures`).
- Optional: run from inside the target network for best results.


## Installation
Clone or copy the `simple_net_scanner.py` file. Make it executable:


```bash
chmod +x simple_net_scanner.py
