## Meeting Details

- **Date/Time:** December 20th, 2021 @ 6:30pm UTC / 1:30pm ET / 10.30AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** Pip Potter (lmbr-pip)
- **Note Taker** Pip Potter (lmbr-pip)

[Agenda](https://github.com/o3de/sig-security/issues/6)

## SIG Updates

**What happened since the last meeting?**
N/a - No previous meeting notes available. SIG is being restarted with new chairs

## Meeting Agenda

* Recognize new Chair(s) post election - Deepak Sharma (chair), Pip Potter (co-chair)
* Decide meeting times + cadence
* Review state of charter and next steps
* Kick off process for security issue reporting - there is no defined process outside of public GHI
* Discuss need to initiate campaign to patch O3DE repro open security alerts

## Outcomes from Discussion topics

SIG recognized Deepak as chair, Pip as co-chair

Discussed meeting cadence, looking at O3DE calendar https://lists.o3de.org/g/o3de-calendar/calendar
- Frequency - every two weeks
- Morning for PST
- Proposal is for some time 9-11am every Tuesday
- Action Item: Deepak to raise time in #sig-security and drive agreement

All: Provide comments and thoughts on charter: https://github.com/o3de/sig-security/issues/2
- Action Item: Chairs will draft and bring to sig-security or next meeting

Kick off process for security issue reporting - there is no defined process outside of public GHI
- Need a Private reporting channel to provide time to patch
- Also for security scanning services and handling false alarms to avoid panic
- Need to build SLAs for venerability disclosures - agree on vulnerability
- Look at Kubernetes set up for guidance: https://kubernetes.io/docs/reference/issues-security/security/
- Action Item: Pip to provide proposal and discuss at TSC

Discussed need to initiate campaign to patch O3DE repro open security alerts relating to issues around PyYaml and Pillow (both python related)
- Action Item: Pip to lead campaign to patch

## Action Items

* Deepak: To propose regular meeting time and set up repeating meetings
* Deepak/Pip: Make an attempt to redraft charter based on community feedback.
* Deepak: action item for each meeting should be to identify notetaker up front, should be not be the person running the meeting
* Pip: Teach out to sig-leads to patch known python security issues, while SIG0-security is being set up
* Pip: Define process for vulnerability process reporting, discuss mechanisms with TSC

## Open Discussion Items

Useful to identifying the category of the security issue, for example do you need physical access, what is the impact of the issue?
- How should we react to them?
- Always consider, how can user exploit security issue, how likely is it? Difficult of exploitation.
- How do vulnerabilities map to threat models for O3DE?
- O3DE has a wide a service area

Team to discuss if we see value engaging in https://openssf.org/
