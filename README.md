# AWS Assets Finder - A Hacker's Recon Tool
### "Uncover. Exploit. Secure."

## Overview
AWS Assets Finder is a **powerful reconnaissance tool** designed to automate the **discovery of AWS cloud assets**. Whether you're a security researcher, penetration tester, or red team operator, this tool helps you uncover:

- 🕵️ **Subdomains** (via Amass, Subfinder, Assetfinder)
- ☁️ **S3 Buckets** (via S3Scanner, AWS CLI)
- 🚀 **CloudFront Distributions** (via crt.sh, dig)
- 🔥 **EC2 Instances** (via Shodan, Censys)
- 🗄️ **RDS Databases** (via Nmap, Cloudbrute)
- 👤 **IAM Users** (via Enumerate-IAM, AWS CLI)

It uses **multithreading** to speed up scans and automatically saves results for later analysis.

---
## 🛠️ Installation & Dependencies
### 📌 Prerequisites
Ensure you have the following installed on your system:

- **Python 3.x**
- `amass`, `subfinder`, `assetfinder`
- `s3scanner`, `aws-cli`
- `jq`, `dig`
- `shodan`, `censys`
- `nmap`, `cloudbrute`
- `enumerate-iam`

📥 **Install Python dependencies:**
```bash
pip install shodan censys
```

---
## 🎯 Usage
💀 Fire up the scanner:
```bash
python aws_enum.py
```
Enter the **target domain** when prompted, and let the tool do the work! 🕶️

---
## 📜 Output
- The results will be saved in a file named:
```plaintext
aws_enum_<domain>.txt
```
- Example results include **subdomains, S3 bucket URLs, EC2 IPs, CloudFront mappings**, and more.

---
## ⚠️ Legal Disclaimer
**This tool is for authorized security testing and educational purposes only.** Unauthorized usage against systems **without explicit permission** is illegal and punishable under cybersecurity laws. **Use responsibly.**

👨‍💻 **Author:** r4x4nj031 | 🚀 Happy Hacking!

