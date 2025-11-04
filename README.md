Final 12-Month Roadmap
Total Projects: 20 (9 Azure, 7 AWS, 4 Multi; mix of core + leadership for senior roles).
Certs: 3 (AZ-500, AWS Sec Specialty, CCSP for 50K edge).
Labs: Free Tier (Azure UAE North, AWS Bahrain) + TryHackMe (AED 360/year).
Social: LinkedIn (3 posts/week), X (#UAECyber), Meetups (Dubai Cyber Hub).
Budget: AED 2,500 (certs AED 2,000 + tools AED 500).
Milestones: 4 Locks (Contrib, OT Optional, Video, Cashflow).

Month,Focus (Skills for 50K),Projects,Certs/Badges/Deliverables,Labs/Tools,Social/Networking,Job Actions (Salary Ramp),Hrs/Wk
1,Azure Foundations + NESA,"1, 2",NESA Awareness Badge + Loom Intro Video,"Azure Free Tier (UAE North), Loom","LinkedIn: 1 post (""Day 1: 0 exp → Sentinel""); Join UAE Cyber Slack","Post portfolio; Apply 5 entry roles (Etisalat Jr, 23K)",16
2,AWS Basics + Identity,"3, 4",AWS Bahrain Region Badge,"AWS Free Tier (Bahrain), TryHackMe (NESA path)","LinkedIn: 2 posts (""2/20 live""); X: #UAECyber tweet w/ screenshot","Network Dubai Cyber Hub Meetup; Apply 5 (DEWA Jr, 23K)",18
3,NESA Compliance + Contrib Lock,5,Open-Source PR #1 (Azure Sentinel) + NESA Excel Matrix,"Terraform Cloud, GitHub Codespaces",LinkedIn: 3 posts (tag @EmiratesCyber); X: Follow @Mubadala,"Apply 10 mid-entry (Etihad Jr, 25K); GitHub ""Contributor"" badge",18
4,AZ-500 Prep + Policy,"6, 7",AZ-500 Exam (Apr 15),"Whizlabs (AED 110), Microsoft Learn",LinkedIn: Post cert progress; UAE Cyber Slack intro,"Apply 10 (Etisalat Mid, 25K); Update CV w/ AZ-500",20
5,SOAR/XDR + Aviation Sec,"8, 9",—,"Sentinel Playground, Logic Apps",LinkedIn: 3 posts (SOAR demo); Speak at Dubai Cyber Hub (15-min talk),"Apply 15 (DEWA Mid, 28K); DM 5 Emirates recruiters",20
6,OT/SCADA (Optional) + IR,"10, 11 (Optional OT)",IR Playbook PDF + IEC Report (if OT),"Azure RTOS/IoT Hub (Free), TryHackMe OT room","LinkedIn: Video series (""IR in 60s""); X: #CloudSecUAE thread","Apply 15 senior-entry (Mubadala Mid, 30K); Emirates networking event",22
7,AWS Sec Prep + Remediation,"12, 13",AWS Security Specialty Exam (Jul 15),"Qwiklabs (AED 300/3 mo), AWS Skill Builder",LinkedIn: Cert announcement post; UAE Cyber Slack AMA,"Apply 20 (Etisalat Senior, 30K); DM Mubadala leads",22
8,AI/Containers + Aviation Sim,"14, 15, 19",CCSP Prep Start + O365 Aviation Sim (#19),"EKS Free Cluster, SageMaker, MCAS",LinkedIn: 3 posts (AI demo); Submit GISEC 2026 CFP (talk on aviation sec),"Apply 20 (Etihad Senior, 35K); GISEC networking",22
9,Threat Hunting + Video Lock,"16, 17, 20",CCSP Exam (Sep) + 20/20 Loom GIFs + PR #2 Merged,"Athena, Sigma Rules, Pramp mocks",LinkedIn: Portfolio launch post; X: #UAECyber thread w/ videos,"Apply 25 lead (Emirates Lead, 38K); Video Lock = shortlist boost",18
10,Leadership + CISO Deck,18,CISO 1-Pager PDF + KPI Dashboard + Leadership Blog (Medium post),"GitHub Pages, Power BI Free",LinkedIn: Blog share (3x); UAE Cyber Slack leadership discussion,"Apply 20 lead/architect (Mubadala Lead, 38K); Send CISO deck to 20 recruiters",16

-----------------------------------------------------------------------------------------------------------------------------------
Projects (20 Total: 10 Azure, 7 AWS, 3 Multi)
All deployable in free tiers (UAE North/Bahrain regions); each with Terraform, KQL/Python code, NESA mapping, 60-sec Loom video, and resume line. Focus: Leadership (playbooks, dashboards) for senior pay.
#,Repo Name,Cloud,Target,NESA Control,Key Tech/Lab,Resume Line (50K Level),Hrs
1,splunk-to-sentinel-uae,Azure,All,AM-03,Sentinel + KQL (Azure Free Tier),Led 50+ Splunk-to-Sentinel migration (95% accuracy),6
2,guardduty-phishing-emirates,AWS,Emirates,AM-05,GuardDuty + O365 (AWS Free Tier),Phishing detection playbook for aviation O365,6
3,mcas-uae-north,Azure,Etihad,AM-04,MCAS + Conditional Access (Azure Free),Implemented MCAS for risky app access,8
4,aad-ip-uae,Azure,Emirates,IA-02,AAD Identity Protection (Microsoft Learn Lab),Automated MFA for high-risk sign-ins,8
5,nsg-hardening-uae,Azure,DEWA,SC-07,NSG + Flow Logs (Azure Sandbox),Hardened NSGs with NESA-compliant rules,8
6,kv-uae-north,Azure,Mubadala,SC-12,Key Vault + RBAC (Azure Free),Secrets rotation policy w/ JIT access,8
7,policy-nesa-uae,Azure,All,CM-06,Azure Policy as Code (Terraform Cloud Free),NESA compliance engine (100+ controls),10
8,connectors-uae,Azure,All,AM-02,Sentinel Connectors (AAD/Defender),Integrated 5+ data sources for SIEM,8
9,ir-runbook-uae,Azure,Etihad,IR-04,Logic App Playbook (Power Automate Free),End-to-end IR playbook (<90s response),10
10,hunting-uae,Multi,All,AM-05,Jupyter + KQL/Athena (GitHub Codespaces),Proactive threat hunting notebook,10
11,firewall-uae,Azure,DEWA,SC-07,Azure Firewall + Threat Intel (Free Tier),WAF ruleset w/ 1M RPS simulation,10
12,paw-uae,Azure,Mubadala,AC-02,PAW + Intune (Azure Lab),Privileged workstation deployment,8
13,backup-uae,Azure,All,CP-09,Backup Vault + Recovery (Free Tier),RTO <4hr recovery plan,8
14,retention-uae,Azure,All,AU-11,Log Retention Policy (Sentinel),90-day compliant retention engine,6
15,nesa-dashboard,Multi,All,CA-07,Power BI + Sentinel (Free),NESA KPI dashboard for CISOs,8
16,lambda-remediation-mubadala,AWS,Mubadala,IR-05,Lambda + GuardDuty (AWS Free),<60s auto-remediation pipeline,12
17,eks-ai-security-mubadala,AWS,Mubadala,CS-03,EKS + SageMaker Clarify (Free Cluster),AI model poisoning detection,12
18,o365-aviation-sim-emirates,Azure,Emirates,IR-06,O365 Threat Sim (MCAS Lab),In-flight WiFi phishing simulation,8
19,flight-data-ir-etihad,Multi,Etihad,IR-08,IR for Aviation Data (Pramp Mock),Breach response for flight systems,8
20,leadership-nesa-ot-mubadala,Multi,Mubadala,GC-OT,OT NESA Mapping (Optional; TryHackMe OT),OT leadership playbook (IEC/NESA),6 (Optional)
----------------------------------------------------------------------------------------
Certifications (3 Total for 50K Edge)
Cert,Month,Cost (AED),Why 50K?,Prep Resources
AZ-500,4,600,Azure sec standard (DEWA/Emirates),"Whizlabs (AED 110), Microsoft Learn Free"
AWS Security Specialty,7,"1,100",AWS lead roles (Mubadala/Etisalat),"AWS Skill Builder (AED 300/3 mo), Qwiklabs"
CCSP,9,"1,100",Cloud architect cred (50K boost),(ISC)² Free Resources + Practice Exams (AED 200)
---------------------------------------------------------------------------------------------
Labs & Tools (Free/Low-Cost Setup)
Tool/Lab,Cost (AED),Use,Region
Azure Free Tier,0,"Sentinel, MCAS, NSG (UAE North)",UAE North
AWS Free Tier,0,"GuardDuty, Lambda, EKS (Bahrain)",Bahrain
TryHackMe,360/year,"NESA/OT rooms, aviation cyber labs",—
Whizlabs/Qwiklabs,410,AZ-500/AWS prep,—
GitHub Codespaces,0,Jupyter/Terraform dev,—
Loom,0,60-sec demos,—
Pramp,0,Mock interviews,—
---------------------------------------------------------------------------------------------------
Social Media & Networking (Build Visibility for 50K)
Platform,Frequency,Content Strategy,Goal
LinkedIn,3 posts/week,"Project demos (w/ Loom GIFs), cert updates, #UAECyber #CloudSecUAE; Tag @Emirates @Mubadala",500+ connections; Recruiter DMs (20/month)
X (Twitter),5 tweets/week,"Screenshots, NESA tips, threads (#NESACompliance); Follow @UAENESA @GISECGlobal",200 followers; Viral threads for visibility
Meetups/Slack,1 event/month,Dubai/Abu Dhabi Cyber Hub talks (15-min on IR/aviation); UAE Cyber Slack (#hiring channel),50 contacts; Speaking slots (GISEC CFP Month 8)
--------------------------------------------------------------------------------------------------
Quick Enhancements for 100% Fit

ADNOC: Month 8—Add AI-HSE sim (#21: ai-ot-hse-adnoc, AWS, 4 hrs; aligns w/ their 2025 AI awards).
DEWA: Month 6—Add cloud SCADA (#21: scada-cloud-dewa, Azure IoT Hub, 6 hrs; per NCSC guidance).
General: Use Loom videos to demo NESA mapping; certs cover compliance.
Blog/Medium,1 post/month (Month 10+),"""NESA in Aviation"" or ""AI Sec Playbooks""",Leadership proof for lead roles
-----------------------------------------------------------------------------------------------------
Interview Scripts (For 50K Negotiation)
Objection,20-Second Answer
"""No senior exp?""","""20 projects simulate 5+ yrs: Led Sentinel migration (#1, 95% accuracy) + AI sec playbook (#17, <60s remediation). CCSP + portfolio = immediate impact."""
"""Salary 50K?""","""Base 40K + 10K bonus/perks = 50K effective. My NESA dashboard (#16) saves audit costs; aviation IR (#20) fits Emirates' needs."""
