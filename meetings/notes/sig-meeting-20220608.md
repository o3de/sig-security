## Meeting Details

- **Date/Time:** June 8th, 2022 @ 6:00pm UTC / 1:00pm ET / 10:00AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Deepak Sharma](https://github.com/dshmz)
- **Note Taker** [Pip Potter](https://github.com/lmnr-pip)

[Agenda](https://github.com/o3de/sig-security/issues/43)

## Meeting Agenda
* Review [open security issues](https://github.com/o3de/sig-security/blob/main/TRIAGE_GUIDE.md)
* Charter updates done, RFC Merged : https://github.com/o3de/sig-security/pull/23
* Pillow upgrade - https://github.com/o3de/o3de/issues/9890
* Any action items/notes from May 25th meeting

### Agenda Discussion

* No Open issues to review
* Charter updates merged, maintainers welcome to make additions.
* Pillow update is completed

## Open Discussion Items

* Issues with code scanning
    - LFX limited to python, nodejs (languages common to webdev)
    - Can craft a codeql scanner in GitHub to meet our needs
    - Need to make this work in license friendly
    - Mike meeting with Royal tomorrow

* Have request to fix LGTM code scanning for O3DE: https://github.com/o3de/o3de/issues/10032
	
* Pip reached out to Nicole of LF to find out why LFX is not scanning main branch, nothing has occurred
  - Don't currently support scanning different branches
  - Mike: Wil cut issue to the LFX dashboard team about why release
  
## Action items:
* _IN PROGRESS_: Create the proposal with SLAs to present to SIG of SIGs (in conjunction with Finchy @ SIG-Operations) (Pip) - See https://github.com/o3de/sig-security/discussions/44
* _NO UPDATES_: Reach out to contributor who filed round of NVD issues to see if they want to contribute to SIG (Pip)
* _TODO_: Issue response gameday meeting to run through the steps of triaging and notifying on an issue (Setup meeting for all members, driven by Pip)
* _IN PROGRESS_: Need to follow up with LF/LFX about why scan did not change anything (@dshmz/ mike)
* _TODO_: Get updates from SIGs for Lz4 and Lua 5.4.4 updates, needs estimates for work from SIGs (@dshmz)