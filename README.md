# arpSpoofer

Tools for learning ARP spoofing and detection. Intended for training, lab use, and security research.

## Usage

Prerequisites:
- Python 3.x installed
- Administrator/root privileges may be required for low-level network operations

Typical usage (from this folder):
`powershell
python .\arpSpoof.py --help
python .\ARPspoofDetector.py --help
`

Optional: create and use a virtual environment:
`powershell
python -m venv .venv
. .\.venv\Scripts\Activate.ps1
# Install any dependencies if a requirements.txt is provided
pip install -r requirements.txt
`

## Disclaimer

This project is provided for educational purposes and authorized security testing only. Do not run these tools on networks you do not own or have explicit permission to test. Misuse may violate laws or policies and is your responsibility.
