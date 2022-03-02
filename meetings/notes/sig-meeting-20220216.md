## Meeting Details

- **Date/Time:** February 16nd, 2022 @ 6:00pm UTC / 1:00pm ET / 10:00AM PT
- **Location:** [Discord SIG-Security Voice Room](https://discord.gg/FDA3s4FBD2)
- **Moderator:** [Deepak Sharma](https://github.com/dshmz)
- **Note Taker** [Brian Herrera](https://github.com/brianherrera)

[Agenda](https://github.com/o3de/sig-security/issues/18)
  
## Meeting Agenda
* Discussed the LFX Security Bot enrollment.
  * Most repos in the O3De org have already been onboarded. Mike will investigate the missing repos.
  * The bot currently only scans the python code in the repo. C++ is not included in the scans. Tool is based on Snyk and BlueBracket.
  * Other tools may provide C++ coverage (e.g CodeQL).
  * Link provided to request access to the dashboard: https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/139
  
* Reviewed open RFCs:
  * https://github.com/o3de/sig-security/issues/12 (no additional comments)
  * https://github.com/o3de/sig-security/issues/14 (will be moved to final comment period)
  * Discussed implementing a process to asynchronously provide feedback and also provide info regarding RFC discussions to sig-security members that are unable attend the meetings.
  * Reviewed the intake process and the option to use private discord channels.
  * Pip will review this process with the TSC and move the security response RFC to the final comment period.
  * Also proposed the option of running through the security intake process with a test security report and going through the response steps. 
 
 * Issue triage: we will review the open issues in the next meeting due to time constraints. 


## Outcomes from Discussion topics

* SIG to perform a trial run of the intake process using a test security report
  - This will be used to verify each step in the process and that sig-security members have access to perform each action.

* Security dashboard: sig-security members should request access using the link provided. 


## Action Items
* Mike: To follow up on the missing repos on the LFS security dashboard
* Pip: To review the sig-scecurity response proposal with the TSC



## Open Discussion Items
What other tools can we utilize to provide C++ coverage for security issues (e.g. CodeQL)?

