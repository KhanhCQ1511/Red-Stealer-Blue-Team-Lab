# Red-Stealer-Blue-Team-Lab

Link Lab: https://cyberdefenders.org/blueteam-ctf-challenges/red-stealer/

Join the lab and download the resource. Here you will get a hash file. Try to use some decode tool to decode it but it doesn't work. Use VirusTotal to check the given Hash

### Q1: Categorizing malware allows for a quicker and easier understanding of the malware, aiding in understanding its distinct behaviors and attack vectors. What's the identified malware's category?
#### ANS: Trojan

![image](https://github.com/user-attachments/assets/ad216727-1030-41bd-90d2-986e2061da30)

Using VirusTotal we can identify the malware associated with the given hash.

### Q2: Clear identification of the malware file name facilitates better communication among the SOC team. What's the file name associated with this malware?
#### ANS: WEXTRACT

![image](https://github.com/user-attachments/assets/feebebca-5cde-4c65-ba88-abac573b956c)

### Q3: Knowing the exact time the malware was first seen can help prioritize actions. If the malware is newly detected, it may warrant more urgent containment and eradication efforts compared to older, well-known threats. Can you provide the UTC timestamp of first submission of this malware on VirusTotal?
#### ANS: 2023-10-06 04:41:50 UTC

![image](https://github.com/user-attachments/assets/e457efbf-70aa-428e-9abd-b687f4e668ba)

### Q4: Understanding the techniques used by malware helps in strategic security planning. What is the MITRE ATT&CK technique ID for the malware's data collection from the system before exfiltration?
#### ANS: T1005

![image](https://github.com/user-attachments/assets/61788f85-3d9d-4bdd-b4ba-c4feae934ca7)

### Q5: Following execution, what domain name resolution is performed by the malware?
#### ANS: facebook.com

![image](https://github.com/user-attachments/assets/5150a409-279c-45fe-bd09-458f7a307475)

### Q6: Once the malicious IP addresses are identified, network security devices such as firewalls can be configured to block traffic to and from these addresses. Can you provide the IP address and destination port the malware communicates with?
#### ANS: 77.91.124.55:19071

![image](https://github.com/user-attachments/assets/125202ad-6cf9-4bd0-93db-a59074410c39)

### Q7: YARA rules are designed to identify specific malware patterns and behaviors. What's the name of the YARA rule created by "Varp0s" that detects the identified malware?
#### ANS: detect_Redline_Stealer

![image](https://github.com/user-attachments/assets/f87e5fb2-6307-46fb-8669-cabd4b869b98)

Search hash on Internet, you will see some interesting things

### Q8: Understanding which malware families are targeting the organization helps in strategic security planning for the future and prioritizing resources based on the threat. Can you provide the different malware alias associated with the malicious IP address?
#### ANS: RECORDSTEALER

Search in ThreatFox with keyword: ioc:77.91.124.55:19071

![image](https://github.com/user-attachments/assets/ea565cd6-2e45-4078-b7bb-a25aa7029026)

### Q9: By identifying the malware's imported DLLs, we can configure security tools to monitor for the loading or unusual usage of these specific DLLs. Can you provide the DLL utilized by the malware for privilege escalation?
#### ANS: advapi32.dll

![image](https://github.com/user-attachments/assets/c3d2cfec-f59c-4dc0-805c-76d3e8e7bc4a)

