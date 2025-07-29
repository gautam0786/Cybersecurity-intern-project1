 Web Application Vulnerability Scanner

 Introduction :-

This project is a basic web application vulnerability scanner built using Python. It automates crawling, payload injection, and response analysis to detect common vulnerabilities such as Cross-Site Scripting (XSS) and SQL Injection (SQLi).

 Features:-

- Recursive crawling of URLs within the target domain  
- Detection of HTML forms and automated injection of payloads  
- Identification of reflected XSS payloads and SQL error messages  
- Simple Flask-based web UI to start scans and view vulnerability reports

 Tools Used:-
- Python 3  
- Flask  
- Requests  
- BeautifulSoup4

 Installation:-

1. Clone the repository:
   bash
   git clone <your-repo-url>
   cd web_vuln_scanner
 
2.Create and activate a virtual environment:

On Windows:

bash
python -m venv venv
venv\Scripts\activate

3.Install dependencies:

bash
pip install -r requirements.txt

Usage
1. Run the Flask application:

bash
python app.py

2. Open your web browser and navigate to:

cpp

http://127.0.0.1:5000
3. Enter the URL of the target web application (make sure you have permission to scan it) and click Start Scan.

4.View the scan results displayed on the page showing detected vulnerabilities with evidence and severity.

 Important Notes:-

 Only scan websites you own or have explicit authorization to test. Unauthorized scanning is illegal and unethical.

This scanner is a basic prototype intended for learning and demonstration purposes. It can be enhanced with more advanced crawling, payloads, and vulnerability checks.

Conclusion:-

This project demonstrates an automated approach to detecting common web vulnerabilities using Python tools and a simple web interface. It serves as a foundation for learning web application security testing and scanner development.
