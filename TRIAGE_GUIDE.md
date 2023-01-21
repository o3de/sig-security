
# Overview

SIG-Security holds weekly triage on [Mondays](https://lists.o3de.org/g/o3de-calendar/calendar). High priority issues can be triaged via Discord as and when required.

The standard O3DE [triage guide](https://github.com/o3de/community/) should be used to cover process for accepting issues and setting standard labels.

Brief overview of process for maintainers:
* Ensure issue can be accepted by SIG. 
    * Remove the `needs-triage` label and add `triage-accepted` label
    * Set a priority
* Or assign a reviewer/maintainer to reproduce, get more information or followup on issue.

## Triage Links
* O3DE issues to triage for SIG: https://github.com/o3de/o3de/issues?q=is%3Aissue+is%3Aopen+label%3Aneeds-triage+label%3Asig%2Fsecurity
* O3DE known security issues: https://github.com/o3de/o3de/issues?q=is%3Aissue+is%3Aopen+label%3Akind%2Fsecurity
* Dependabot alerts to check (link only accessible to SIG-Security maintainers): https://github.com/o3de/o3de/security/dependabot
    * For new alerts, create new GitHub issues against [O3DE](https://github.com/o3de/o3de) and tag with `kind\security` label for tracking.
    * **WARNING**: Since the O3DE _python/requirements.txt_ file includes hashes, Dependabot-generated PRs against this file should be **manually tested** against a clean `/python` folder (that is, no `/runtime` child dir) **prior to merging** in order to suss out any issues with hashing transitive dependencies.

## SIG Specific Guide
* Ensure issues have the label `kind\security` set on them. SIG security uses this label to find issues assigned to other SIGs.
* SIG-Security should only own issues for code areas SIG-Security maintains (see [charter](https://github.com/o3de/sig-security/blob/main/governance/SIG%20Security%20Charter.md) for areas of ownership) or actively intends to work on.

## Map CSVS Score to Issue Priority
If an issue has a CVE/NVD score associated with it then use the following table to set priorities. This table maps
[NVS CSVS V3 scores](https://nvd.nist.gov/vuln-metrics/cvss) to O3DE issue priorities.

| CVSS/NVD Range | CVSS 3.0 Issue Priority | O3DE Issue Priority                                                 |
|----------------|-------------------------|---------------------------------------------------------------------|
| 9.0 - 10.0     | Critical                | [Blocker](https://github.com/o3de/o3de/labels/priority%2Fblocker)   |
| 7.0 - 8.9      | High                    | [Critical](https://github.com/o3de/o3de/labels/priority%2Fcritical) |
| 4.0 - 6.9      | Medium                  | [Major](https://github.com/o3de/o3de/labels/priority%2Fmajor)       |
| 0.1 - 3.9      | Low                     | [Minor](https://github.com/o3de/o3de/labels/priority%2Fminor)       |
| 0.0            | None                    | No Priority                                                         |

The O3DE issue priority is only a guide and where we should start the discussion of the issue with the SIG that owns the code.
The owning SIG should work out if the vulnerability is applicable to O3DE and can propose change of issue priority.



