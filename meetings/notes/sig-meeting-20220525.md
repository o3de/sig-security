## Meeting Details

- **Date/Time:** May 25th, 2022 @ 6:00pm UTC / 1:00pm ET / 10:00AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Deepak Sharma](https://github.com/dshmz)
- **Note Taker** [Pip Potter](https://github.com/lmnr-pip)

[Agenda](https://github.com/o3de/sig-security/issues/36)

## Meeting Agenda
* Review open security issues
* Charter update
* Discuss plans for LFX dashboard review post May 12th release.

### Agenda Discussion

* No Open issues to review
* No security related issues from release 
* Have only two open dependabot issues (both moderate and for sig-testing)
    - @Allisaurus will open issues for SIGs for these

* Next meeting need to review open kind/security issues to see if we need to escalate/engage with owning SIGs now release is out of the way.

* LFX Security bot review, post 2205 release
    - has not updated 13 days post 2205 delivery
    - need to find contact with LF / LFX teams to understand issues

* TSC meeting / SIGs taking over triage 
    * TSC is looking for new owners for the cross SIG issue triage process
    * One item discussed is to use automation to escalate blockers/criticals that aren't being triaged: https://github.com/o3de/sig-operations/issues/38

## Open Discussion Items

* (Mike) The pillow issue ended up becoming a blocker for release and needed exceptions to get into the release
  - (Mike) We should to establish timelines and gather learnings where a critical security vulnerability was left for months
  - (Seapip) Yes, we should at least get some backstory about the process and timelines
  - (Seapip) [Action item] - Do a quick investigation on the timeline of Pillow remediation for documentation, for next SIG meeting

* (Seapip) Looking for dangling ownership and dealing with them with SIGs
  - (Seapip) Certain gems, including using 3p services can be broken out as external repos, to be owned by SIGs or partners
  
## Action items:
* _IN PROGRESS_: Create the proposal with SLAs to present to SIG of SIGs (in conjunction with Finchy @ SIG-Operations) (Pip)
* _IN PROGRESS_: Reach out to contributor who filed round of NVD issues to see if they want to contribute to SIG (Pip)
* _TODO_: Issue response gameday meeting to run through the steps of triaging and notifying on an issue (Setup meeting for all memebers, driven by Pip)
* _TODO_: Need to follow up with LF/LFX about why scan did not change anything (@dshmz)

* _DONE_: Review LFX security dashboard post release (post May 12th) (All members for next meeting, driven by Pip)
* _DONE_: Fix inverted priority guide (Pip)
* _DONE_: Do a quick investigation on the timeline of Pillow remeditaion for documentation, for next SIG meeting (Mike)
