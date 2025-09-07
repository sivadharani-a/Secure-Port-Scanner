🔐 SecurePort Scanner

 A lightweight, fast, and user-friendly network port scanner with a modern UI. Built for developers, students, and security professionals to detect open ports, analyze vulnerabilities, and export results as PDF reports.

🌍 Live Demo: https://secure-port-scanner.onrender.com

✨ Features

🔎 Multiple Scan Modes → Socket, Nmap, and Scapy scanning options.

⚡ Fast Scan → Quickly scans common ports (e.g., 22, 80, 443, 3306).

🎨 Modern Web UI → Clean design with Lottie animations for a professional experience.

📊 Results Dashboard → Interactive table of open/closed ports.

⬇ Export Reports → Generate and download PDF reports instantly.

🛡 Secure Awareness → Helps analyze network exposure & improve cybersecurity knowledge.

📸 Screenshots
🏠 Home Page

<img width="1905" height="882" alt="Screenshot 2025-09-06 192348" src="https://github.com/user-attachments/assets/94becafb-8871-4fec-bfaa-6b249f2c956f" />

(intro with animations & quick scan CTA)


📖 About Page

<img width="1878" height="905" alt="Screenshot 2025-09-06 192401" src="https://github.com/user-attachments/assets/c1af0292-125e-4b21-9880-c998553a68a4" />

(overview of tool with animations)


🔍 Scan Page

<img width="1906" height="906" alt="Screenshot 2025-09-06 192415" src="https://github.com/user-attachments/assets/369c6f6d-6da0-48f1-a67e-7940d87835c5" />

(run a target scan with animations & results table)


📑 PDF Report

<img width="1908" height="913" alt="Screenshot 2025-09-07 095519" src="https://github.com/user-attachments/assets/30031417-b535-4331-8acd-e1c2e79714c5" />



(sample exported report)


🛠 Tech Stack

Backend → Python, Flask

Frontend → HTML5, CSS3, JavaScript

Animations → LottieFiles

Networking → socket, scapy, nmap

PDF Reports → reportlab

⚙️ Installation

Create a virtual environment & install dependencies:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt


Run the app:

python app.py


Open in browser:
👉 http://127.0.0.1:5000

🚀 Usage

Navigate to Scan Page.

Enter a target IP or domain (example: scanme.nmap.org).

Choose scan method → Socket / Nmap / Scapy.

View results in a responsive table.

Download PDF report for records.

📌 Example Targets

For testing purposes:

scanme.nmap.org → official Nmap test server

example.com → demo domain

google.com → public server


📜 License

This project is licensed under the MIT License.
See LICENSE for details.

🔐 SecurePort Scanner — Built for Security Awareness
