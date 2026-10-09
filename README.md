# Cloud-Security-Monitoring-Week-4

Project Overview

This project analyzes simulated cloud activity logs for a fictional Emerging Electronics Store to identify potentially suspicious security events.

Scope

The project focuses on detecting risky cloud activity, reviewing alerts, and documenting appropriate incident response procedures.

Tools Used

- Google Colab
- Python
- Pandas
- GitHub

Detection Use Cases

Seven detection rules were created for:

1. Root account login
2. MFA disabled
3. New access key creation
4. Public storage policy changes
5. Activity from a selected unusual region
6. Console login failures
7. Policy creation

Testing and Results

A simulated dataset of 2,000 events was generated. Preliminary detection rules were run, and a separate three-event test dataset was used to check selected alerts. These tests are educational and do not represent validation against real AWS logs.

Response Playbook

The playbook describes investigation and response steps for root account logins and MFA changes that may be unauthorized.

Limitations

The dataset is simulated, and the detection rules require further testing to reduce false positives. This project is not connected to a live AWS environment.

Cost Estimate

No AWS services were provisioned for this lab, so no AWS usage charges were incurred. Google Colab usage limits may apply. Production costs would depend on event volume, storage, retention, and cloud services selected.

Future Improvements

- Test against authentic public CloudTrail sample logs.
- Improve detection logic and validate all seven rules.
- Add severity rankings and more edge-case tests.
- Evaluate production deployment costs.

Author

Tahreem Akhtar
Cyber Security (Blue Team) — Individual Project
