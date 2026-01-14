# cloudtrail-iam-breach-investigation

Objective / Task:

In this lab, you’ll take on the role of a Digital Forensics and Incident Response (DFIR) expert brought in to assist Terrapin CloudWorks, a mid-sized logistics and cloud-native company based in Maryland. The company recently detected suspicious activity in its AWS account—shortly after receiving intelligence that internal credentials were discovered in a dark web leak, linked to a previous breach of its on-prem

As part of your investigation, you’ve been provided with a set of AWS CloudTrail logs captured during the timeframe of the suspected breach, which can be found below. 

Terrapin-Cloudworks_CloudTrail_Logs.zip Download Terrapin-Cloudworks_CloudTrail_Logs.zip 

Your job is to:

Confirm whether a breach occurred
Reconstruct the attack timeline
Identify compromised IAM identities
Determine if any lateral movement or privilege escalation occurred
Analyze if any data exfiltration took place
Provide prevention recommendations going forward
⚠️ Disclaimer: This lab is entirely log-analysis based. You will not use AWS credentials or interact with any live infrastructure. All investigative work will be done using the CloudTrail log files provided in the ZIP archive.
