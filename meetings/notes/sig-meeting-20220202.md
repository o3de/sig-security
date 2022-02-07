## Meeting Details

- **Date/Time:** February 2nd, 2022 @ 6:30pm UTC / 1:30pm ET / 10.30AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Deepak Sharma](https://github.com/dshmz)
- **Note Taker** [Pip Potter](https://github.com/lmbr-pip)

[Agenda](https://github.com/o3de/sig-security/issues/17)

## SIG Updates

* Python patching continues. Have 1 critical and 2 highs that are pending PR to patch.
* [O3DE contributor](https://github.com/o3de/o3de/issues?q=is%3Aissue+NVD+author%3AJackie9527+) created a number of issues related to known CVE/NVD in 3rd party dependencies.
   * Do not have a way to thank them for their contribution unfortunately or to encourage them to participate in SIG-Security.
  
## Meeting Agenda
* Discuss when we use o3de/o3de issues versus sig-security issues
* Open RFC: https://github.com/o3de/sig-security/issues/12 (in final comment period)
* Open RFC: https://github.com/o3de/sig-security/issues/14
* Issue triage on public issues: https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Aneeds-triage+label%3Asig%2Fsecurity
     * Propose we use the following CVSS score ranges for setting priorities when manually entering issues: 0.1 - 3.9 | Low, 4.0 - 6.9 | Medium, 7.0 - 8.9 | High, 9.0 - 10.0 | Critical  (based on [Atlassian Documentation](https://www.atlassian.com/trust/security/security-severity-levels)) 
* Discuss cadence for public issue triage  
* Charter updates

## Outcomes from Discussion topics

* SIG to use o3de/o3de issues for any issues we expect to share externally to SIG-Security
- procedural, issues or tasks internal to SIG in our repro

* RFCs: Due to time we advertise for comments and review async for RFC proposals
   * Reporting - no real concerns raised
   * Response - looking for help with open questions

Issue Triage:
* Most SIGs have already grabbed issues and are actively working on issues reported.
* Concern that multiple SIG ownership of issues causes confusion
* Propose a security label, so we can track security issues, without having to have SIG/Security on everything.


## Action Items
* Pip: To promote RFCs in SIG-Network to gather more engagement
* Pip: To ask TSC for `feature/security` or `kind/security` to replace existing [committee/product-security](https://github.com/o3de/o3de/labels/committee%2Fproduct-security), so we can cleanly hand off issues to other SIGs
* Pip: To set up SIG-Security public issue triage weekly. As most members are on PT will pick time that folks can attend. SIG can adjust as required, based on engagement.
* Pip: To create an automation investigation task for once security label is defined

Added item to next meeting around automating 3rd party dependency scanning for security issues.

## Open Discussion Items
* Can we set up automation based on `security` label? Escalate when issues are ignored by SIGs.
    * SIG needs to reach out to SIG-ops for guidance.
* Dependabot missed some issues, gaps in python scanning: https://github.com/o3de/o3de/issues/7271 
    * missed pip .whl scanning, may require further investigation