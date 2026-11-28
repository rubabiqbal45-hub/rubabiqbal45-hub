# Hi there, I'm Umm e Rubab Muhammad Iqbal 👋

Information Technology Graduate | SOC Analyst (aspiring) | IT Infrastructure Administration, Systems Monitoring & Detection Engineering

🟢 **Open to work** — SOC Analyst roles (remote/relocation open)

---

### 🛠 Technical Matrix

- **Core Focus:** Detection Engineering, SIEM/Log Analysis, IT Infrastructure Administration, Virtualization, Patch & Backup Management
- **Operating Systems & Services:** Windows Server, Linux, Active Directory, DNS, DHCP, File Services / DFS
- **Security Tools:** Splunk, Sysmon, Wazuh, VirusTotal API, SIEM Telemetry
- **Networking & Protocols:** TCP/IP, Routing & Switching, VLANs, Packet Tracer Network Simulation
- **Languages & Automation:** Python (Scripting & Automation), PowerShell, Bash, Git/Git Bash
- **Frameworks & Methodologies:** NIST SP 800-61 Incident Handling, ITIL Processes, Retrieval-Augmented Generation (RAG)

---

### 🔬 Security Projects

#### 🔍 [SOC Detection Lab](https://github.com/rubabiqbal45-hub/soc-detection-lab)
A self-built Active Directory attack-and-detection lab (Windows Server 2022 DC + Windows Server 2016 workstation), with detections verified against real Windows Security log output and live-fired through Splunk.
- Built and fired two live Splunk detections: Kerberoasting (RC4 ticket encryption) and password spraying (distinct-account threshold), confirmed via Splunk's Trigger History
- Diagnosed and fixed real infrastructure issues along the way: a VirtualBox Host-Only subnet mismatch, and the common "4625 alone misses most password-guessing attempts" detection gap

#### 🎣 [Phishing Investigation & IOC Enrichment](https://github.com/rubabiqbal45-hub/phishing-investigation-ioc-enrichment)
A Python tool that investigates real phishing emails — parses headers, extracts every IOC (URLs, domains, IPs, attachment hashes), enriches each against VirusTotal's live API, scores risk, and writes an actionable report.
- Processed 19 real phishing emails from the Nazario Phishing Corpus; every risk score traces back to a real VirusTotal vendor verdict
- Flagged a real typosquat of a federal agency's domain (NCUA) hidden inside a URL path

#### 📋 [Ransomware Incident Response Playbook](https://github.com/rubabiqbal45-hub/ransomware-ir-playbook)
A NIST SP 800-61–based IR playbook, stress-tested with a live solo tabletop exercise rather than left untested.
- Played every IR role against a live-injected ransomware scenario, answering cold before checking the playbook
- Found and fixed 4 real gaps: missing containment fallback, a too-vague eradication step, no named IC succession, no public-decryptor trust criteria

#### ☁️ [Cloud & IAM Misconfiguration Assessment](https://github.com/rubabiqbal45-hub/cloud-iam-misconfig-assessment)
A deliberately misconfigured AWS environment (built locally, no cloud account needed), audited and remediated the way a real cloud security/IAM review works.
- Found and fixed two real-world misconfigurations: a publicly-readable S3 bucket (`AllUsers: READ`) and an IAM role with unrestricted `*:*` admin access — each confirmed via CLI audit, fixed, then re-verified
- Pivoted through three different tools (flaws.cloud → LocalStack → moto) after hitting a paid-AWS-account requirement and a vendor's free tier disappearing mid-project, without spending a cent

#### 📋 [Security Risk Assessment (NIST CSF)](https://github.com/rubabiqbal45-hub/security-risk-assessment)
A risk assessment of a fictional small e-commerce company, scored by likelihood × impact and mapped to the NIST Cybersecurity Framework, written so a non-technical business owner can act on it — aimed at GRC/Compliance/Risk Analyst roles rather than SOC.
- Built a full risk register (8 risks, each rated likelihood × impact) and prioritized a remediation order instead of treating every finding as equally urgent
- Mapped every recommended control to one of NIST CSF's five functions (Identify, Protect, Detect, Respond, Recover) and explained every technical term in plain language

#### 🛡️ [SOC Alert Triage & Fatigue Mitigation Pipeline](https://github.com/rubabiqbal45-hub/SOC-Projects-to-Mitigate-Alert-Fatigue)
An automated, context-aware alert-triage framework in Python that correlates multi-layered security alerts at runtime to cut down background log noise.
- **The tech:** Python, in-context prompt blueprints, a custom multi-layered data blender matching raw logs against mock CMDB configurations
- **Validation rigor:** covered by an automated `unittest` suite confirming logic validation across critical, medium, and unmapped infrastructure pathways

#### 🛡️ [Native ML Alert Triage & Deceptive False Positive Reduction Framework](https://github.com/rubabiqbal45-hub/deceptive-FP_Benign-alert-)
- Engineered an offline-capable, CPU-run backend pipeline handling structured system logs and enterprise-scale telemetry
- Implemented data parsing, feature engineering, and baseline configurations matching enterprise monitoring needs
- Incorporated temporal splits, queue simulation metrics, and adversarial/drift stress tests into an automated evaluation framework

#### 📱 Android Hall Booking Application
Designed and developed a full-scale digital management framework, implementing secure user authentication flows and optimized data storage schemes to handle concurrent transactional requests.

---

### 💼 Leadership & Professional Experience

- **Clothing Warehouse Business | Operations & Leadership Manager**
  Directed infrastructure logistics, transaction record management, digital payment frameworks, and operational scaling budgets.
- **PwC US | Cybersecurity Consulting Job Simulation (Forage)** — *November 2026*
  Completed a job simulation focused on a cybersecurity risk assessment for PwC: determined whether controls were missing from a process, identified the risks associated with those gaps, completed Test of Design and Operating Effectiveness documentation, and created a one-slide summary to present findings.
- **Mastercard | Cybersecurity Virtual Experience Program (Forage)** — *November 2026*
  Served as an analyst on Mastercard's Security Awareness Team: helped identify and report security threats such as phishing, and analyzed which areas of the business needed more robust security training, implementing training courses and procedures for those teams.
- **Government College Women University Faisalabad (GCWUF) | Student Intern / IT Support**
  Assisted campus administrative divisions with digital asset organization, technical network troubleshooting, hardware/software maintenance, and local IT operations support.

---

### 🎓 Academic & Professional Certifications

- **Bachelor of Science in Information Technology (BS IT)** – Government College Women University Faisalabad (GCWUF), Pakistan *(CGPA: 3.29/4.0, H+ Accredited Degree, Verified English Medium of Instruction available)*
- **Specialized Certifications:**
  - *CS50 Introduction to Cybersecurity* – Harvard University
  - *Introduction to Cybersecurity* – Cisco
  - *Networking Basics* – Cisco
  - *Getting Started with Cisco Packet Tracer* – Cisco
  - *AWS Networking Basics* – Coursera
  - *Professional Security & Technical Specializations* – Coursera
- **Core Toolkit:** Python, LangChain, Linux, Git Version Control, Threat Infrastructure Modeling

---

### 📫 Connect with Me

- **GitHub:** [@rubabiqbal45-hub](https://github.com/rubabiqbal45-hub)
- **Email:** rubabiqbal45@gmail.com
- **LinkedIn:** [add your LinkedIn URL here]

---

### 📊 GitHub Statistics

![Rubab's GitHub Stats](https://github-readme-stats.vercel.app/api?username=rubabiqbal45-hub&show_icons=true&theme=default)
