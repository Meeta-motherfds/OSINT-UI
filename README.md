# OSINT-UI

OSINT-UI

Professional Open Source Intelligence Platform

OSINT-UI is a virtual desktop environment designed for professionals and enthusiasts in Open Source Intelligence (OSINT). It provides a comprehensive suite of integrated tools within a modern "hacker-style" desktop interface, enabling efficient collection, analysis, and investigation of publicly available information.


<img width="2048" height="1175" alt="17826450877845890488645521072229" src="https://github.com/user-attachments/assets/5af01ec1-62de-4831-b6ee-d63963b4a725" />


---

1. Introduction

The environment simulates a desktop operating system where windows can be moved, resized, minimized, and maximized. Each application is dedicated to a specific OSINT task, ranging from social media profile investigations to domain infrastructure analysis.




---

2. Using the Features

To launch any tool, simply click its corresponding desktop icon.

---

Username Analyzer

Searches for a specific username across hundreds of social media platforms and websites to identify existing accounts.

How to Use

1. Enter the username into the search field.
2. Click Analyze.
3. The application scans supported platforms and displays the results.
4. Results are color-coded:
   - Green (Found): An account exists. Click the result to visit the profile.
   - Gray (Not Found): No account was found.
   - Orange/Red (Error/Filtered): An error occurred during verification or the result was identified as a potential false positive.
5. For greater accuracy, use Verify False Positives to perform an additional verification pass on detected accounts.
6. Export the complete results in JSON format.

---

Email Analyzer

Analyzes an email address to determine its validity, reputation, and online presence.

How to Use

1. Enter the email address.
2. Click Analyze.
3. The application provides a technical summary, including:
   - Email syntax validation
   - MX records
   - SPF records
   - DMARC records
4. The tool also evaluates the address using the Dymo API to determine whether it may be:
   - Phishing-related
   - Corporate
   - No-reply
   - Disposable
   - Or another email category
5. Generate Google Dorks to perform advanced web searches related to the email address.
6. Export the results as a JSON file.

---

Phone Analyzer

Collects publicly available information about a phone number, including line type, country, and international formatting.

How to Use

1. Enter the phone number using international format (e.g., +14155552671).
2. Click Analyze.
3. Review the available information, including:
   - Country
   - International formatting
   - Carrier (when available)
   - Line type (mobile, landline, VoIP)
4. Use dedicated links to investigate the number on WhatsApp and Telegram.
5. Generate Google Dorks for additional web investigation.
6. Export the findings in JSON format.

---

Domain Analyzer

Retrieves publicly available information about a domain, including WHOIS records, DNS records, and validated subdomains.

How to Use

1. Enter the domain name (e.g., google.com).
2. Click Analyze.
3. Review WHOIS information:
   - Registrar
   - Creation date
   - Expiration date
4. Examine DNS records:
   - A
   - AAAA
   - MX
   - TXT
   - NS
   - CNAME
5. Browse validated subdomains.
6. Generate Google Dorks for additional domain investigation.
7. Export all collected information as JSON.

---

Port Scanner

Scans an IP address or domain to identify open ports and discover potentially running services.

How to Use

1. Enter an IP address or domain.
2. Select the scan mode:
   - Fast Scan: Scans the 100 most common ports.
   - Complete Scan: Scans the 1,000 most common ports for a more comprehensive assessment.
3. Click Scan.
4. Review the results showing:
   - Open ports
   - Closed ports
   - Filtered ports
   - Potentially detected services
5. Export the scan results as JSON.

---

Reputation Checker

Checks the reputation of an IP address or domain by consulting Cyber Threat Intelligence (CTI) databases to determine whether it has been associated with malicious activity.

How to Use

1. Enter the IP address or domain.
2. Click Check.
3. Review the security assessment, including:
   - Overall verdict (Benign or Malicious)
   - Risk score
4. Examine the intelligence sources contributing to the assessment.
5. Generate Google Dorks for further investigation.
6. Export the report as JSON.

---

Metadata Extractor

Extracts hidden EXIF metadata from image files, including GPS coordinates, camera information, timestamps, and other technical metadata.

How to Use

1. Analyze an image by either:
   - Uploading a local file
   - Providing an image URL
2. Click Extract or Upload Image.
3. When metadata is available, the application displays:
   - Camera: Manufacturer and model
   - Timestamps: Creation and modification dates
   - GPS Location: Interactive map and Google Maps link (if coordinates are present)
   - Raw EXIF Data: Complete metadata table
4. Export the extracted metadata as JSON.

---

Hash Analyzer

Identifies the most likely hashing algorithm used to generate a given hash value (e.g., MD5, SHA-256, bcrypt) and provides an option to test common hashes using CrackStation.

How to Use

1. Paste the hash value into the input field.
2. Click Identify.
3. The application displays the most probable hash algorithms along with confidence estimates.
4. A direct link to CrackStation is provided for educational purposes to check whether the hash exists in publicly available databases.
5. Export the identification results in JSON format.

---

Export Features

Every OSINT module supports exporting investigation results as structured JSON files, making it easy to:

- Archive investigations
- Share findings
- Integrate with other OSINT platforms
- Perform additional automated analysis
- Build reproducible investigation workflows

---

Key Features

- Modern hacker-style desktop interface
- Multi-window virtual operating system environment
- Integrated OSINT toolkit
- Username investigation
- Email intelligence
- Phone number analysis
- Domain intelligence
- Port scanning
- Reputation checking
- Image metadata extraction
- Hash identification
- Google Dork generation
- JSON export support
- Interactive maps for GPS metadata
- Public threat intelligence integration
- Cross-platform compatibility

---

Disclaimer

OSINT-UI is intended solely for educational purposes, cybersecurity research, digital investigations, and authorized security assessments. Users are responsible for ensuring compliance with all applicable laws, regulations, and organizational policies. Unauthorized or unlawful use of this software is strictly prohibited.
