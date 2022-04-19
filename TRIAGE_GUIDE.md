
# Overview

SIG-Security holds weekly triage on [Mondays](https://lists.o3de.org/g/o3de-calendar/calendar). High priority issues can be triaged via Discord as and when required.

The standard O3DE [triage guide](https://github.com/o3de/community/) should be used to cover process for accepting issues and setting standard labels.

Very brief overview of process:
* Ensure issue can be accepted by SIG. 
    * Remove the `needs-triage` label and add `triage-accepted` label
    * Set a priority
* Or assign a reviewer/maintainer to reproduce or get more information.

## Useful Links
* Issues to triage for SIG: https://github.com/o3de/o3de/issues?q=is%3Aissue+is%3Aopen+label%3Aneeds-triage+label%3Asig%2Fsecurity
* Known security issues: https://github.com/o3de/o3de/issues?q=is%3Aissue+is%3Aopen+label%3Akind%2Fsecurity

## SIG Specific Guide
* Ensure issues have label `kind\security` set on them so SIG security can find issues shared wit other SIGs.
* SIG-Security only owns issues for code SIG-Security (see [charter] for areas of ownership) or actively intends to work on.

## Map CSVS Score to Issue Priority
If an issue has a CVE/NVD score associated with it then use the following table to set priorities. This table maps
[NVS CSVS V3 scores](https://nvd.nist.gov/vuln-metrics/cvss) to O3DE issue priorities.

| CVE/NVD Score Range | Issue Priority |
|---------------------|----------------|
| 9.0 - 10.0          | Blocker        |
| 7.0 - 8.9           | Critical       |
| 4.0 - 6.9           | Major          |
| 0.1 - 3.9           | Minor          |


