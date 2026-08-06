# AWS S3 Cloud Storage Lab

## Overview

This project demonstrates the creation and management of an Amazon S3 bucket with security, versioning, encryption, and data recovery capabilities.

## Project Details

**Bucket Name:** `mzu-cloud-storage-lab-njabulo`
**AWS Region:** US East (N. Virginia) (`us-east-1`)
**Storage Class:** S3 Standard
## Security Configuration
✅ Block Public Access: Enabled
✅ Bucket Versioning: Enabled
✅ Server-Side Encryption: Enabled

## Files Uploaded
The following text files were stored in the S3 bucket:
- `company-profile.txt`
- `cloud-notes.txt`
- `architecture-plan.txt`
  
## Scenario
A developer accidentally modified an important file:
cloud-notes.txt | AWS Cloud Storage Notes  
accidentally updated to AWS Cloud Storage Advanced Notes 

## Recovery Process
Since **S3 Versioning** was enabled, previous versions of the file were retained.
Steps performed:
Reviewed object versions in the S3 bucket.
Identified the correct previous version of `cloud-notes.txt`.
Restored the original version.
Verified the file content was recovered successfully.

## Expected Outcome
✅ Data Recovery
✅ Operational Resilience
✅ Business Continuity

## Key AWS Services Used
- Amazon S3
- S3 Versioning
- S3 Server-Side Encryption
- S3 Block Public Access
  
## Lessons Learned
- Enable versioning to protect against accidental changes or deletions.
- Use encryption to secure stored data.
- Block public access to reduce security risks.
- Maintain backups and version history to support business continuity.

**Author:** Njabulo 




![image Alt](https://github.com/iamnjebs/mzuca-cloud-storage-lab-bhakede/blob/main/Architecture%20mzu-cloud-storage-lab-njabulo.JPG?raw=true)
