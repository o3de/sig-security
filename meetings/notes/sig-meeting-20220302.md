## Meeting Details

- **Date/Time:** February 16nd, 2022 @ 6:00pm UTC / 1:00pm ET / 10:00AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Deepak Sharma](https://github.com/dshmz)
- **Note Taker** [Pip Potter](https://github.com/lmnr-pip)

[Agenda](https://github.com/o3de/sig-security/issues/21)

## Meeting Agenda

* Open RFC: https://github.com/o3de/sig-security/issues/14
    * Pip to split out notification list to own RFC as that can be addressed with TSC later as needed.
    * Will move to accept at next security meeting.
  
* PY 3.7.12 patching 
    * Steve Pham (AWS) has patched outstanding NVD issues https://github.com/o3de/o3de/pull/7990
    * Locally patching 3.7.12 in O3DE 3P sources

* Do we want to follow local patching model in future? 
    * Depends on if we are locked to versions due to support / major versions
    * It's definitely something to remember for future patching, where there is no sense of official patch in progress. 
    * We may need to go to next major point release for other patching efforts (ie Python 3.8)
    
* Open Security Campaign Status
    * No open security advisories on O3DE/O3DE outside of 2 moderates related to python packages.
    * 4 open kind/security issues: https://github.com/o3de/o3de/issues?q=is%3Aissue+is%3Aopen+label%3Akind%2Fsecurity+
        * One of Python 3.7.12 patching as discussed above 
        * One for patching OpenSSL, has now testing plan, but pending resources to complete OpenSSL update, that Amazon will provide/

## Open Discussion Items
* Charter Completion
   * Read current charter, updates have not been pushed to [charter](https://github.com/o3de/sig-security/blob/main/governance/SIG%20Security%20Charter.md) from https://github.com/o3de/sig-security/issues/2.
   * Require updates to be pushed to repository.
  
## Action items: 
* Split disclosure list from open RFC (Pip)
* Advertise charter changes again in sig-sec channels (Pip)
    * Mike C. will get PR for next meeting