

# AWS S3 Cloud Storage Lab
2
 
3
## Overview
4
 
5
This project demonstrates the creation and management of an Amazon S3 bucket with security, versioning, encryption, and data recovery capabilities.
6
 
7
## Project Details
8
 
9
- **Bucket Name:** `mzu-cloud-storage-lab-njabulo`
10
- **AWS Region:** US East (N. Virginia) (`us-east-1`)
11
- **Storage Class:** S3 Standard
12
 
13
## Security Configuration
14
 
15
✅ Block Public Access: Enabled
16
 
17
✅ Bucket Versioning: Enabled
18
 
19
✅ Server-Side Encryption: Enabled
20
 
21
## Files Uploaded
22
 
23
The following text files were stored in the S3 bucket:
24
 
25
- `company-profile.txt`
26
- `cloud-notes.txt`
27
- `architecture-plan.txt`
28
 
29
## Scenario
30
 
31
A developer accidentally modified an important file:
32
 
33
| File Name | Original Content | Modified Content |
34
|------------|------------------|------------------|
35
| cloud-notes.txt | AWS Cloud Storage Notes | AWS Cloud Storage Advanced Notes |
36
 
37
## Recovery Process
38
 
39
Since **S3 Versioning** was enabled, previous versions of the file were retained.
40
 
41
Steps performed:
42
 
43
1. Reviewed object versions in the S3 bucket.
44
2. Identified the correct previous version of `cloud-notes.txt`.
45
3. Restored the original version.
46
4. Verified the file content was recovered successfully.
47
 
48
## Expected Outcome
49
 
50
- ✅ Data Recovery
51
- ✅ Operational Resilience
52
- ✅ Business Continuity
53
 
54
## Key AWS Services Used
55
 
56
- Amazon S3
57
- S3 Versioning
58
- S3 Server-Side Encryption
59
- S3 Block Public Access
60
 
61
## Lessons Learned
62
 
63
- Enable versioning to protect against accidental changes or deletions.
64
- Use encryption to secure stored data.
65
- Block public access to reduce security risks.
66
- Maintain backups and version history to support business continuity.
67
 
68
---
69
 
70
**Author:** Njabulo 




![image Alt](https://github.com/iamnjebs/mzuca-cloud-storage-lab-bhakede/blob/main/Architecture%20mzu-cloud-storage-lab-njabulo.JPG?raw=true)
