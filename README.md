🔍 Network Scanner Tool
A simple and effective Python-based Network Scanner designed to identify live hosts, open ports, and basic service information on a local or remote network. Ideal for cybersecurity enthusiasts, ethical hackers, and network administrators to perform quick reconnaissance during security assessments or troubleshooting.

⚙️ Features
🌐 Scan Local or Remote Networks

⚡ Ping Sweep to detect active devices

🔓 Port Scanning on custom or default ports

🛡️ Banner Grabbing for basic service identification

📄 Export scan results (optional feature)

🚀 Getting Started
Prerequisites
Python 3.x

Required libraries:

scapy

socket

argparse (usually built-in)

ipaddress

Install dependencies:

bash
Copy
Edit
pip install scapy
🔧 Usage
bash
Copy
Edit
python network_scanner.py -t 192.168.1.0/24
Options:

-t or --target: Network range or single IP to scan

-p or --ports: Comma-separated ports (optional)

Example:

bash
Copy
Edit
python network_scanner.py -t 192.168.0.0/24 -p 22,80,443
📌 Why Use This Tool?
Whether you're conducting penetration testing, performing network inventory, or just learning about network protocols, this tool gives you hands-on experience with foundational techniques like:

Subnet scanning

ICMP echo requests

TCP SYN port checks

Basic fingerprinting

🧠 Educational Use Only
This tool is intended strictly for educational and authorized use. Do not scan networks you do not own or have permission to audit.

🛠️ To-Do / Upcoming Features
Threading for faster scans

OS detection

GUI version

Export results to CSV/JSON

🤝 Contributing
Pull requests and feedback are welcome! Let’s grow this into a more powerful reconnaissance toolkit together.

📜 License
MIT License — free to use, modify, and share under proper attribution.

