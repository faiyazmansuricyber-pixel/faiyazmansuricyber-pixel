<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:38BDAE&height=180&section=header&text=Faiyaz%20Razak%20Mansuri&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Cloud%20Security%20%7C%20AWS%20IAM%20%7C%20Python&descAlignY=60&descSize=16)

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=38BDAE&center=true&vCenter=true&width=640&lines=Cloud+Security+%7C+AWS+IAM;Python+%2B+Boto3+Security+Automation;AWS+Certified+Cloud+Practitioner;Open+to+Cloud+Security+Internships)](https://github.com/faiyazmansuricyber-pixel)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mansuri-faiyaz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/faiyazmansuricyber-pixel)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:faiyazmansuri.cyber@gmail.com)
[![AWS](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](#-certifications--achievements)
[![Location](https://img.shields.io/badge/Surat-Gujarat,_India-0A66C2?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

### `>_ whoami`

Third-year B.E. student in Computer Science & Engineering (**Cybersecurity & IoT**) at Shree Dhanvantary College of Engineering & Technology (GTU), Gujarat, India. I focus on **cloud security**, mainly **AWS identity and access management**, and on automating security checks with **Python and Boto3**.

My college gives theory, so I build the practical side myself: I create deliberately misconfigured labs, find the problems, fix them, verify the fix, and publish the evidence.

- **Focus Areas:** AWS IAM, S3 security, cloud misconfiguration auditing, SIEM detection, container security
- **Current Status:** Cybersecurity Intern (project-based) at LabMentix, Jun 2026 to Dec 2026
- **Looking For:** Cloud Security internship / entry-level roles
- **Based In:** Surat, Gujarat, India. Open to remote.

---

### `>_ NOW`

- Working on mentor-guided vulnerability assessment and security tooling projects at **LabMentix**
- Building **Autonomous SOC Investigator**, an AI-assisted pipeline for security alert triage
- Extending my AWS IAM audit into an automated **Boto3** script
- Deepening AWS security skills beyond the Cloud Practitioner level

---

### `>_ FEATURED_PROJECTS`

#### [AWS IAM Policy Audit](https://github.com/faiyazmansuricyber-pixel/AWS-IAM-policy-audit)
`AWS IAM` `IAM Access Analyzer` `Policy Simulator`

- **Problem:** IAM misconfigurations are one of the most common causes of cloud breaches.
- **What I did:** Built a deliberately misconfigured AWS lab (test users, an overly permissive policy) and audited it like a real review.
- **Found:** Over-permissioned users, wildcard policies, missing MFA, unused access keys. 4 findings, each severity-rated.
- **Fixed:** Applied least-privilege remediation and verified every fix with before/after evidence.
- **Output:** Full findings report with screenshots in the repo.

#### [PortWatch, Network Exposure Monitor](https://github.com/faiyazmansuricyber-pixel/PortWatch)
`Python` `asyncio` `Scapy`

- Concurrent TCP scanner with timestamped snapshots and **change detection** (what opened or closed since last scan)
- Service detection plus HTTP/TLS inspection
- Reports in JSON, CSV, Nmap XML and HTML
- Documented test: all 65,535 localhost TCP ports scanned in **59.72 seconds** (200 workers, 0.35s timeout)

#### S3 Bucket Misconfiguration Detection
`AWS S3` `Python` `Boto3`

- Script that detects public access and weak bucket policies
- Gives remediation guidance for each finding

#### Cloud SIEM & Container Security Scan
`Elastic Stack (ELK)` `Amazon CloudWatch` `Trivy` `Grype` `Docker Scout`

- Cloud SIEM pipeline with detection rules and alerts
- Container images scanned for CVEs and insecure configurations with three scanners, findings prioritized by severity

#### [Content Transformation Platform, Smart India Hackathon 2026](https://github.com/faiyazmansuricyber-pixel/GEN-AI-AUTOMATED-CONTENT-TRANSFORMATION)
`Next.js` `FastAPI` `Gemini API`

- Six-member team project
- One source (text, PDF/DOCX, image, video) becomes up to 7 output formats in 22 Indian languages
- Source-chunk traceability, so generated claims can be checked against the original

#### Autonomous SOC Investigator *(in progress)*
- Pipeline: Ingest, Detect, Investigate, Correlate, Classify, Explain, Recommend, Verify
- Design rules: least privilege, human approval for high-impact actions, audit logs, confidence and evidence attached to every conclusion

---

### `>_ HOW_I_AUDIT_AWS_IAM`

The checklist I follow in my IAM lab work:

1. **Inventory** users, roles, groups and policies
2. **Check MFA** on every human user
3. **Look for wildcards** (`Action: *`, `Resource: *`) in policies
4. **Find unused** access keys and stale users
5. **Rate severity** of each finding with a clear reason
6. **Fix with least privilege**, never "just make it work"
7. **Verify** the fix with IAM Access Analyzer / Policy Simulator and keep before/after evidence

---

### `>_ TECHNICAL_ARSENAL`

| Area | Skills |
|---|---|
| **Cloud & AWS** | IAM, IAM policy auditing, S3, CloudTrail, KMS, CloudWatch, least-privilege remediation |
| **Security** | Cloud misconfiguration assessment, vulnerability assessment, CVE scanning, container security, SIEM detection rules, network exposure monitoring, TLS inspection |
| **Languages** | Python, Boto3, JavaScript / TypeScript |
| **Tools** | Linux, Nmap, Wireshark, Scapy, ELK, Trivy, Grype, Docker Scout, Git / GitHub |
| **Development** | FastAPI, React, Next.js, asyncio |

<div align="center">

[![Skills](https://skillicons.dev/icons?i=aws,py,js,ts,react,nextjs,fastapi,linux,docker,git,github,elasticsearch,vscode&perline=13)](https://skillicons.dev)

</div>

---

### `>_ LEARNING_ROADMAP`

Skills I am actively working toward (not claiming them yet):

- [x] AWS Cloud Practitioner (CLF-C02)
- [x] AWS IAM auditing and remediation
- [ ] Boto3 automation of the full IAM audit
- [ ] Cross-checking findings with Prowler
- [ ] AWS Security Specialty exam preparation
- [ ] Infrastructure as Code basics (Terraform) for secure cloud setups
- [ ] Threat detection with AWS GuardDuty and Security Hub

---

### `>_ CERTIFICATIONS & ACHIEVEMENTS`

- **AWS Certified Cloud Practitioner (CLF-C02)**, Amazon Web Services
- **OPSWAT Cybersecurity Fundamentals Associate**
- **HYPNEXIS '26 Hackathon**, Manipal University Jaipur, 36-hour event, Oct 2026
- **Smart India Hackathon 2026**, team project for an NTRO / NCIIPC problem statement (Blockchain & Cybersecurity)

---

### `>_ PRINCIPLES`

- Least privilege first
- Every finding needs evidence
- Fixing is not done until it is verified
- Document it so someone else can repeat it

---

### `>_ GITHUB_STATS`

<div align="center">

[![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=faiyazmansuricyber-pixel&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true)](https://github.com/faiyazmansuricyber-pixel)
[![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=faiyazmansuricyber-pixel&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/faiyazmansuricyber-pixel)

[![Streak](https://streak-stats.demolab.com?user=faiyazmansuricyber-pixel&theme=tokyonight&hide_border=true)](https://github.com/faiyazmansuricyber-pixel)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=faiyazmansuricyber-pixel&theme=tokyo-night&hide_border=true&area=true)](https://github.com/faiyazmansuricyber-pixel)

</div>

---

### `>_ LET'S CONNECT`

Hiring for a cloud security internship, or want to collaborate on a security project? Email me at **faiyazmansuri.cyber@gmail.com** or message me on [LinkedIn](https://linkedin.com/in/mansuri-faiyaz).

<div align="center">

*"Learn. Build. Secure. Repeat."*

</div>

> **Disclaimer:** All labs and projects here are done in my own accounts or authorized environments, for learning and education only.

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:38BDAE,100:0f172a&height=100&section=footer)

</div>
