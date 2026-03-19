# SOC 2 Gap Analysis

This artifact is part of a GRC portfolio project based on a realistic SaaS company running in AWS and handling customer data.

I created this gap analysis to practice thinking through what an auditor or security leader would actually look for in an environment like this. Instead of just listing controls, I focused on comparing what exists today versus what would be expected in a SOC 2 aligned environment.

The scenario reflects common cloud realities: IAM in AWS, logging through CloudTrail, vendor dependencies, and backup/recovery expectations.

Each row represents:
- what the control is trying to achieve
- what the environment currently looks like
- where the gap exists
- how risky that gap is
- what should be done to close it

I also included ownership, evidence, and target dates to make this feel closer to how real organizations track remediation work.

This project helped me practice translating technical cloud conditions into governance conversations and audit-ready actions, which is a core part of GRC work.
