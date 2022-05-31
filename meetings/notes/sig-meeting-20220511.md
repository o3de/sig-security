## Meeting Details

- **Date/Time:** May 11th, 2022 @ 6:00pm UTC / 1:00pm ET / 10:00AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Pip Potter](https://github.com/lmnr-pip)
- **Note Taker** [Mike Chang](https://github.com/amzn-changml)

[Agenda](https://github.com/o3de/sig-security/issues/35)

## Meeting Agenda
* Review open security issues
* Charter update
* Discuss plans for LFX dashboard review post May 12th release.

### Agenda Discussion

(Note: Discussion members are denoted by Discord user names)

* Open security issues - None discussed

* (Seapip) SIG-security should work with TSC/all SIGs to set response SLAs
  - (DWeiss) Escalation paths for each SIG? We won't be able to enforce SLAs without them
  - (Seapip) We have some paths using triage methods (within 3 business days)
  - (Brian) We can apply labels to the ticket for triage and notify SIG-Chairs
  - (Seapip) Contact 1 is to the SIG, Contact 2 to the SIG Chair, Contact 3 to the TSC
  - (Seapip) We do need some success/exit critira
  - (Seapip) Can be proposed to the SIG of SIGs monthly meetings
  - (Seapip) 3 business days to triage, few weeks to resolve critical/highs
  - (Seapip) [Action item] - Create the proposal with SLAs to present to SIG of SIGs (in conjunction with Finchy @ SIG-Operations)

* (Seapip) The charter PR has gotten enough time for comments
  - (Mike) The changes have been merged.

* (Seapip) Followup for the contributor who filed NVD issues
  - (Seapip) Need to contact the contributor (Maybe through another Huawei employee?)
  - (Seapip) The goal is to find the tooling used to scan for NVD to be more proactive

* (Seapip) [Action item (continued)] - Contact LF on the LFX bot O3DE expectations,trainings (with Royal or Nicole Huesman)

* (Seapip) [Action item] - Issue response gameday meeting to run through the steps of triaging and notifying on an issue

* (Seapip) [Action item] - Fix inverted priority guide

## Open Discussion Items

* (Mike) The pillow issue ended up becoming a blocker for release and needed exceptions to get into the release
  - (Mike) We should to establish timelines and gather learnings where a critical security vulerability was left for months
  - (Seapip) Yes, we should at least get some backstory about the process and timelines
  - (Seapip) [Action item] - Do a quick investigation on the timeline of Pillow remeditaion for documentation, for next SIG meeting

* (Seapip) Looking for dangling ownership and dealing with them with SIGs
  - (Seapip) Certain gems, including using 3p services can be broken out as external repos, to be owned by SIGs or partners
  
## Action items:
* Create the proposal with SLAs to present to SIG of SIGs (in conjunction with Finchy @ SIG-Operations) (Pip)
* Reach out to contributor who filed round of NVD issues to see if they want to contribute to SIG (Pip)
* Review LFX security dashboard post release (post May 12th) (All members for next meeting, driven by Pip)
* LFX Security Bot Questions (Pip)
    * See if critical bug has been patched 
    * Reach out to see how often LFX security runs and does it autoclose issues 
    * Followup on trainings, O3DE expectations
    * Contact Royal O'Brian or Nicole Huesman
* Issue response gameday meeting to run through the steps of triaging and notifying on an issue (Setup meeting for all memebers, driven by Pip)
* Fix inverted priority guide (Pip)
* Do a quick investigation on the timeline of Pillow remeditaion for documentation, for next SIG meeting (Mike)
