
# Incident Response & Malware Analysis Project

##  Project Overview
This project simulates a basic incident response investigation performed by an entry-level cybersecurity analyst. The investigation focuses on a suspicious file discovered on a user system, analyzed safely using industry-standard techniques.

The project demonstrates:
- Safe malware analysis
- File hashing and verification
- Use of VirusTotal for threat intelligence
- Professional incident reporting

---

##  Objectives
- Analyze a suspicious file safely
- Generate file hashes (SHA256) for identification
- Use VirusTotal to verify the file status
- Classify the incident based on risk
- Document findings in a professional report

---

##  Tools Used
- Windows OS : forensic and analysis environment
- Notepad / CMD : file hash and documentation
- VirusTotal : malware detection and verification on a website
- GitHub : project documentation and portfolio

---

## 🔍 Methodology

# Step 1: File Identification
- Created a test file (EICAR standard antivirus test)
- Verified file properties (size, timestamps)

# Step 2: Hash Generation
- Generated SHA256 hash of the file using Windows `certutil` tool
- Recorded hash as evidence

# Step 3: Threat Verification
- Searched the hash on VirusTotal
- Reviewed detection results and vendor classifications

# Step 4: Incident Classification
- Determined incident type: **Suspicious File Detection**
- Risk Level: **Low**
- Reason: file is a known antivirus test file, not real malware

# Step 5: Reporting
- Documented investigation process and findings
- Created professional incident report

---

##  Key Findings
- File identified as the EICAR test file
- No real malware activity detected
- Incident classified as **low risk**
- Safe incident analysis demonstrated SOC workflow

---

## 📁 Project Files

