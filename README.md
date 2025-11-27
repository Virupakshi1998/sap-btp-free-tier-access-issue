# sap-btp-free-tier-access-issue
This repository contains detailed logs, screenshots, and steps of an SAP BTP Free Tier onboarding issue.   The goal is to help the SAP community diagnose the problem and assist learners who encounter similar errors while trying to access SAP Business Application Studio (BAS) using trial or free tier accounts.

# 🔧 Issue Summary

## Issue 1: BAS Access Denied in Trial Account

When navigating:
SAP BTP Cockpit → Services → Instances and Subscriptions → SAP Business Application Studio

#### I receive the following error:

Access Denied  
You do not have the necessary roles to access SAP Business Application Studio.

![alt text](SAP_BAS_AccessDenied.png)

Multiple SAP community posts suggest that **BAS access is restricted in Trial**, and that switching to **Free Tier** resolves the problem.

#### What I Tried Next — SAP Free Tier Setup
I followed SAP’s official page:
Get an Account on SAP BTP to Try Out Free Tier Service Plans

#### But two new issues appeared:
## Issue 2: Personal Email Not Allowed for Free Tier
When attempting to convert/join Free Tier:

To access SAP Free Tier, personal email domains are not allowed.  
Please use a company or university email.


I used my University email (even though I already graduated).

## Issue 3: Account Creation Failure (DCPP_017 Error)
After entering the required details using my university email, the process fails with:


![alt text](ErrorCode_DCPP_017.png)

I retried several times—same error.

# 🆘 Support Ticket
I raised a support request through the SAP community.
It has been 3 days with no response yet.

# Request for Community Help
If anyone has:

Faced similar errors

Solved DCPP_017

Successfully enabled Free Tier using university email

Has insights into BAS access limitations

Your guidance will truly help me continue my SAP learning journey.

Thank you in advance!
