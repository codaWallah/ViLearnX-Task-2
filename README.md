# Vulnerability Scanning Tool
## Description
### This repository contains a project for a Vulnerability Scanning Tool. The tool is designed to scan a network or website for common security vulnerabilities such as open ports, outdated software versions, and misconfigurations. The tool provides a detailed report of the findings and offers remediation steps.

## Features
<p> <h3> Open Ports Scanning: Uses Nmap to scan for open ports on a network or website.
Outdated Software Detection: Checks for outdated software versions using OpenVAS.
Configuration Checks: Identifies common misconfigurations that could lead to security risks.
Reporting: Generates a comprehensive report summarizing the findings and suggesting remediation steps.
Automation: Supports automated scans on a regular schedule.
User Interface: Provides a simple web-based interface for ease of use.</h3></p>
Technologies Used
Programming Language: Python
Libraries: Nmap, OpenVAS, Flask, Schedule
Vulnerability Scanners: Nmap, OpenVAS, Nessus
Installation
Clone the repository:
git clone https://github.com/yourusername/vulnerability-scanning-tool.git
Navigate to the project directory:
cd vulnerability-scanning-tool
Install the required libraries:
pip install nmap openvas-lib flask schedule
Run the Flask application:
python app.py
Usage
Open your web browser and navigate to http://127.0.0.1:5000/.
Enter the target IP address or domain name in the input field.
Click the "Scan" button to start the vulnerability scan.
The tool will analyze the target and generate a report of open ports, outdated software, and misconfigurations.
The report will be saved as vulnerability_report.txt in the project directory.
Outputs
Open Ports: List of open ports and their states.
Outdated Software: Report of outdated software versions.
Misconfigurations: List of common misconfigurations found.
Report: A comprehensive report summarizing the findings and suggesting remediation steps.
About Vilearnx
Vilearnx is a leading company specializing in cybersecurity solutions. We are committed to providing top-notch security tools and services to help individuals and organizations protect their digital assets. Our team of experts works tirelessly to develop innovative solutions that address the evolving challenges in the cybersecurity landscape.
About CoderAnash
Our coding website offers comprehensive resources to learn programming languages, build projects, and connect with a global community of passionate coders.

For any queries or support, please contact our support team at support@vilearnx.com and {CoderAnash} anashmohd611@gmail.com

License
This project is licensed under the MIT License - see the LICENSE file for details.

Developed by Vilearnx and CoderAnash(MOHD ANASH)
