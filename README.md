

# Chromium Bug Bounty Pilot Program

This Chromium Bug Bounty Pilot Program is a skill based trade promotion (“Program”) offered by The Linux Foundation (“Program Host”) in connection with its hosting and support of the [Supporters of Chromium-Based Browsers](https://www.linuxfoundation.org/supporters-of-chromium-based-browsers) initiative (“SOCBB”), to provide monetary awards (“awards”) for eligible Submissions that fix open Chromium issues that are **user-facing or developer-facing browser bugs**. Whether a Submission qualifies for an award in a particular Category will be assessed by the SOCBB Steering Committee based on the judging criteria stated herein and scaled to the importance of the bug, similar to how the [Chrome Vulnerability Reward Program](https://bughunters.google.com/about/rules/chrome-friends/5745167867576320/chrome-vulnerability-reward-program-rules) works. The total Program award budget is currently anticipated to be capped at USD$300,000 (“Budget”); the Budget or parts thereof may be unawarded or decreased, as provided herein, or may be increased, each in Program Host’s discretion. 

The Program begins on or about 12:00 am PT on or about April 1, 2025 and will end 11:59 pm PT on September 30, 2025, unless earlier terminated (due to for example reaching the total Budget amount, or exigent circumstances, such as impossibility, frustration or force majeure event), or may but without obligation be extended (because insufficient eligible Submissions are received for example) (“Program Period”). Program Host reserves the right, without notice or prior approval, to extend, postpone, cancel or terminate the Program and any element thereof in whole or in part and/or to modify or supersede these Terms in its sole absolute discretion; any revised Terms will continue to govern all participation and aspects of the Program. 

**NO PURCHASE NECESSARY TO PARTICIPATE OR WIN.** ELIGIBILITY TO USE THE GITHUB SPONSOR’S PROGRAM (AND COMPLIANCE WITH ITS TERMS) IS REQUIRED TO RECEIVE AN AWARD, IF APPLICABLE. *By participating in this Program, Participants agree (on their own behalf and on behalf of their successors, assignees, subrogors, heirs, next of kin, legal and personal representatives, and anyone who obtains any rights by, from or through them) to be bound by these Chromium Bug Bounty Pilot Program <span style="text-decoration:underline;">Official Rules</span> (“Program Terms”), The Linux Foundation’s Privacy Policy ([https://www.linuxfoundation.org/privacy/](https://www.linuxfoundation.org/privacy/)), GitHub Sponsor’s <span style="text-decoration:underline;">Terms</span> (and all related obligations), the Chromium <span style="text-decoration:underline;">Code of Conduct</span>, all Program related communications from Program Host and the interpretations and decisions of Program Host and the SOCBB Steering Committee, which are final and binding in all respects. *


## Goals


---



* Incentivize and enable external developers to fix bugs that measurably improve Chromium’s quality for web developers and users.
* Allow freedom to external developers to choose their bugs and find bugs to fix that matter to them, & demonstrate the impact of their work to us.
* Increase the size of the Chromium community.


## Issues in scope


---

Any open Chromium [issue](https://issues.chromium.org) that:



* Is not already owned by someone.
* Fixes an issue directly visible to web developers or users.
* Is present in the Stable version of a Chromium-based browser before work begins, and can be reproduced without any special feature flags set.


## Examples in scope



* A logic bug for a [web-exposed](https://www.chromium.org/blink/guidelines/web-exposed/) API supported by Chromium
* A bug causing a substantial number of Chromium crashes
* A user-visible Chromium UI error
* A performance improvement that is measurable on a [recognized competitive benchmark](https://browserbench.org/), or via A/B experiments on one or more Chromium-based browsers on a [Core Web Vital](https://web.dev/articles/vitals#core-web-vitals) (and does not also regress any other of these measures)
* Adding support for a web platform feature already that has an accepted standard and has already shipped in another browser (the same exception [enumerated here](https://www.chromium.org/blink/launching-features/wide-review/#exceptions))


## Examples not in scope



* Issues impacting only browser developers
* Code cleanup of all kinds (including refactoring, renaming, comments and removing dead code)
* Adding new features not enumerated above
* Adding or fixing tests not related to a bug or issue
* Any bug already owned by a project member that has been recently updated (older owned issues may be stale and actually available in practice)
* Fixes in downstream forks of Chromium
* Any issue that is not visible in at least one of the following products:
    * Microsoft Edge
    * Opera
    * Meta's in-app browsers
    * Android WebView
    * Google Chrome

These are not in scope because they don’t represent direct improvement to Chromium’s use by web developers or users.


## Why not other categories?



* Security fixes are already [covered](https://bughunters.google.com/about/rules/chrome-friends/5745167867576320/chrome-vulnerability-reward-program-rules#patch-bonus) by the Chrome Vulnerability Reward Program
* Rewarding refactoring or other code cleanup is difficult to measure and assess for impact
* New features often require skills other than coding, such as standards consensus-building, writing specifications and explainers, and alignment with priorities of Chromium area OWNERS. Fixing known issues in Chromium doesn’t have those challenges

If you have questions regarding the Program’s Scope, please contact [bugbounty@socbb.org](mailto:bugbounty@socbb.org).


## Submissions


---

Submissions must be submitted by an eligible Participant, compliant with these Terms, and reviewed and approved by at least 2 representatives from SOCBB or their member companies to be considered for participation in the Program and potential award. Inputs to the decision include the following:



* Code and test must be done in one of the main line Chromium repositories including:
    * Chromium
    * V8
    * Skia
    * Devtools-frontend
    * WebRTC.
* bug fixes must make it to the stable channel of a major Chromium browser (e.g. Chrome and Edge) and stay there for at least 2 weeks without being reverted or otherwise disabled.
* Any new bugs filed as being caused by the fix within this period must also be fixed (and are not independently eligible for payment).
* Fixes must not reintroduce previously fixed bugs (e.g. cannot simply revert a prior bugfix which also caused a regression).
* Participants represent and warrant that they will behave according to the [Chromium Code of Conduct](https://chromium.googlesource.com/chromium/src/+/main/CODE_OF_CONDUCT.md#:~:text=Be%20respectful%20and%20constructive.,condescension%2C%20whether%20blatant%20or%20subtle.). Violations may lead to permanent disqualification from this Program.
* Fixes need to be fully reviewed and approved by relevant code OWNERS. Chromium has a high-bar for code quality and as code architecture. Code OWNERS and other project members are available to guide new contributors, but will not do the work for them. If a submitted fix is judged by reviewers to be substantially below the Program’s bar for code quality (such as by requiring significant and repeated rounds of code review feedback atypical even for new project contributors), it will be disqualified and ineligible for award.  
* If regular progress is not made towards fixing a bug (e.g. no update in a week), it may be unassigned in order to be reassigned to someone else. In rare cases of urgent bugs (those marked Pri0 or Release blocking), proposed fixes may be required much faster to avoid reassignment. 

The SOCBB Steering Committee reserves the right to make decisions based on all relevant factors in its sole and absolute discretion. In an effort to help support the community, the SOCBB Steering Committee has proactively identified some bugs as good candidates for this Program, labeled as Hotlist in each of the award Categories. The award Categories also include bug fixes that may not be listed on the applicable Hotlist. 


## Payments will run through GitHub Sponsors


---

All payments will be processed through GitHub Sponsors, so a GitHub account is required to receive an award. Please note that only eligible Participants who are individuals participating in the[ GitHub Sponsors](https://github.com/sponsors) program may be eligible for an award.

We will attempt to review Submissions and provide a response by the 15th of the month following your Submission. If the Submission is eligible to receive one, an award will generally be issued in the first week of the month following Submission approval.


## Awards & Judging Criteria 


---

The following award amount applicable to a Large, Medium and Small award category (“Category”) is anticipated to be available per confirmed and accepted bug fix that meets the Program requirements. Eligible Submissions will be judged in accordance with the below Judging Criteria for the appropriate Category as determined by SOCBB and as stated below: 


## **Large $10,000**

HOTLIST: [https://issues.chromium.org/hotlists/6639828](https://issues.chromium.org/hotlists/6639828) 

For items not found on the hotlist, a fix **may** be appropriate for the Large award Category, based on the following criteria:



* Is a top issue for many web developers or users, (eg. has a high star count);
* Evidence that the bug significantly affects more than **1%** of the users of a Chromium-based browser;
* Affects Interop 202x score by more than **0.1%**;
* Improves competitive performance score by more than **0.5%**, or a Core Web Vital by more than **0.5%**; or
* It had most of one of the above factors, and inherent difficulty of fixing the issue is high or the fix solved a systemic code quality problem beyond the scope of the bug in question.


## **Medium $1,000**

HOTLIST: [https://issues.chromium.org/hotlists/6641288](https://issues.chromium.org/hotlists/6641288) 

For items not found on the hotlist, a fix **may** be appropriate for the Medium award Category, based on the following criteria:



* Impacts many web developers or users;
* Evidence that the bug significantly affects more than **0.1%** of the users of a Chromium-based browser;
* Affects Interop 202x score; or
* Improves competitive performance score by more than **0.1%**, or a Core Web Vital by more than **0.1%**.

To validate bugs not found on the Large or Medium hotlists please follow validation instructions on our GitHub.


## **Small $250**

HOTLIST: [https://issues.chromium.org/hotlists/6641289](https://issues.chromium.org/hotlists/6641289) 

For items not found on the hotlist, a fix **may** be appropriate for the Small award Category, based on the following criteria:



* It’s a real user or developer bug. 

Awards cannot be assigned, transferred, redeemed for a different denomination, or substituted, in whole or in part, except by Linux Foundation. Limit one (1) award per confirmed bug fix, as determined by Program Host and the SOCBB Steering Committee, regardless of the number of eligible Submissions received for the applicable bug and the number of individuals involved in the development of the bug fix and Submission.


---


# Instructions

Please follow the instructions below carefully. Failure to do so could result in disqualification or rejection of your Submission, late payment of award(s) or overlooked Submissions. Any questions regarding the SOCBB Bug Bounty Program should be directed to [bugbounty@socbb.org](mailto:bugbounty@socbb.org). 


## Step 1 Fix the bug in Chromium

[https://www.chromium.org/getting-involved/](https://www.chromium.org/getting-involved/) gives general advice on how to get started with Chromium development, and how to ask questions. If you’re stuck, you can also email [bugbounty@socbb.org](mailto:bugbounty@socbb.org) for help.


## Step 2 Submit your Award request in GitHub during the Program Period

Before reaching out, please ensure that your project has been fully tested, and released for at least 2 weeks in a stable version of a Chromium browser, as we do not review work that is still in progress. 

When your work is ready, Please Submit your contribution in a new Issue on the [SOCBB Bug Bounty GitHub](https://github.com/Supporters-Of-Chromium-Based-Browsers/Foundation) and include the following information:

You **<span style="text-decoration:underline;">Must</span>** include the following:



* Bug Name and Description: Provide a brief overview (1 sentence) highlighting your project’s community usage and its significance within the broader Chromium ecosystem.
* Link to the Chromium bug: Share links to your contributions that support your request. These contributions must be publicly accessible without requiring login or account creation.
* GitHub Profile Link: Include a link to your GitHub profile.

The more detailed and clear your submission, the faster and more efficiently SOCBB can process your request for Bug Bounty Program Award.

Please be detailed and clear in your Submission. Participants assume all risk of ineligible, damaged, lost, late, incomplete, invalid, incorrect, incompatible, non-functioning, or misdirected Submissions, in whole or in part. PROGRAM HOST MAKES NO WARANTY, REPRESENTATION OR GUARANTEE, EXPRESS OR IMPLIED, IN CONNECTION WITH THEIR ABILITY TO IN ANY WAY ENABLE, DEVELOP, MARKET OR PROMOTE THE PARTICIPANT, THEIR FIX, OR THEIR SUBMISSION, IN WHOLE OR IN PART. Participants may provide as many Submissions as they wish, but each must provide a fix for a different bug or provide a distinctly different fix if submitted for the same bug.  


# Terms and Conditions


## **Eligibility**

Eligible participants in this Program (“Participants”) must be the legal age of majority in their jurisdiction of legal residence and must not be ineligible (as provided herein) nor under a conflicting employment, contractual, political or legal restriction to enter. An eligible Participant may enter only on their own behalf, and may not enter on behalf of any third party, including any employer, business, organization, corporation, institution or other legal entity or individual. 

Participants may work on a Submission with other persons. However, the SOCBB Steering Committee shall in its sole discretion select at most one individual per confirmed bug fix as the award recipient. Any further arrangements regarding the allocation of the award among that recipient and any other involved individuals shall be determined solely between them, and Program Host and the SOCBB Steering Committee shall assume no liability or responsibility with respect thereto.

In addition, all Participants must be eligible to participate in the GitHub Sponsors program, pursuant to the terms and conditions available at [https://docs.github.com/en/site-policy/github-terms/github-sponsors-additional-terms](https://docs.github.com/en/site-policy/github-terms/github-sponsors-additional-terms). GitHub Sponsors requires your compliance with additional eligibility and program terms related to any award, including age eligibility, taxes, fees, sanctions, and other terms which you must agree with prior to making any Submission.

RESIDENTS OF U.S. EMBARGOED COUNTRIES, PERSONS SUBJECT TO U.S. OR OTHER APPLICABLE COUNTRIES’ SANCTIONS OR OTHER PROHIBITIONS ON PAYMENTS, AND RESIDENTS OF COUNTRIES WHERE THIS PROGRAM MAY BE RESTRICTED, SUBJECT TO EXPORT CONTROLS, FILING OR REGISTRATION REQUIREMENTS, OR WHERE THE PROGRAM OR PARTICIPATION THEREIN IS OTHERWISE PROHIBITED OR RESTRICTED BY LAW ARE INELIGIBLE TO PARTICIPATE. 

Employees, officers, directors, and contractors of any of the SOCBB Member Companies (as defined below), the Program Host, and/or other entities involved directly or indirectly with the organization, administration, execution, judging or award fulfillment of the Program or any element thereof, are NOT eligible to participate or obtain an award. Immediate family members (spouses and parents, partners, children and siblings and their spouses, including foster and step-relations) and members of the same households (whether related or not) of any of the aforementioned ineligible individuals are also ineligible to participate. 

As used herein, “SOCBB Member Companies” means companies that are members of SOCBB, together with their subsidiaries and affiliated entities. The SOCBB Member Companies as of the start of the Program consist of Meta, Opera, Microsoft, and Google. For purposes of the Program, any companies that become members of SOCBB during the Program shall be considered SOCBB Member Companies from and after the date of their membership, but such membership shall not retroactively invalidate awards that have been made and completed prior thereto.

Participants have the responsibility to review and understand their employer’s policies, and laws, rules and/or regulations, tax implications, and any other limitations (collectively “policies and laws”) regarding eligibility to participate in The Program and/or receive awards in connection therewith. Participants who enter without approval or participate in violation of any policies and laws, may be disqualified and forfeit their award(s), if applicable. Program Host and the SOCBB Steering Committee disclaim all responsibility and liability relating to the above; by entering, Participants agree to release, indemnify, defend and hold them harmless in all respects for any issues relating thereto.

Providing a Submission(s) does not evidence receipt, eligibility for the Program or that it will receive an award. Submissions are subject to eligibility and compliance with these Terms, and the assessment of Program Host and the SOCBB Steering Committee.


## **Conditions, Limitations of Liability and Releases**



* Once the Budget has been exhausted, you understand and agree that SOCBB will not be responsible or liable to make any additional award payments under this Program, and the Program may be immediately terminated. Consequently, some qualifying Submissions may receive reduced recognition payments or no recognition payments at all. Therefore, it is possible that your Submission could qualify for a award, yet no award will be issued. 
* Program Host and the SOCBB Steering Committee reserve the right to disqualify any Participant at any time in their absolute discretion. Without limitation, if at any time a Participant is found to have breached, violated or failed to comply with these Terms (or other applicable agreement), in whole or in part, at any time, or is or found at any time to have been ineligible, they will be immediately disqualified and agree to immediate return in full of any and all award(s) (if applicable). Without limiting any other right or term herein, a Participant may be disqualified at any time from the Program immediately if, in Program Host’s or the SOCBB Steering Committee’s (or their authorized representative’s) absolute discretion, it reasonably believes the Participant has, is suspected of, appears to, or has attempted to undermine the legitimate operation of the Program, is suspected at any time of engaging in artifice, cheating, deception, fraud, theft, using multiple identities, engaging in illegal, harmful, dangerous, unsportsmanlike activities or obnoxious behavior, or other unfair practices, or has or attempts to annoy, abuse, threaten, harass, or intimidate or cause harm to any other Participant, Program Host, the SOCBB Steering Committee, or any other person, or if their actions may cause damage, destruction or loss of property of any kind, or are not in the spirit of the Program.
* Program Host and the SOCBB Steering Committee are not responsible for errors, omissions, interruptions, deletions, defects, and/or delays; the loss, misdirection, theft or destruction of any Submission, or other Program related materials or information, in whole or in part; technical, hardware or software malfunctions, failures, problems; incompatibility, unavailable connections, garbled, corrupt, or jumbled transmissions; service provider, Internet, wi-fi, website, blog site, user net (in)accessibility, (un)availability or congestion; unauthorized human intervention or security breach; unauthorized access to or alteration of Submissions in whole or in part, the incorrect or inaccurate capture or processing of Submissions, or other information, or the failure to process, collect or communicate any such information.  If for any reason the Program, or any part thereof, is not capable of running as planned for any reason, including (but not limited to) infection by computer virus, bugs, tampering, unauthorized intervention, artifice, fraud, cheating, technical failures, a force majeure event, impossibility, impracticability, or any other causes similar or dissimilar which corrupt or affect the administration, security, fairness, integrity, or the ability to (properly) conduct the Program, or any element thereof, Program Host reserves the right in its absolute discretion to cancel, terminate, modify or suspend the Program or any part thereof. Program Host and the SOCBB Steering Committee reserve the right to select only potential winners from eligible, non-suspect Submissions received (prior to the force majeure event or otherwise), but only if doing so is deemed practicable and equitable in their determination under the circumstances. ANY ATTEMPT BY A PARTICIPANT TO DELIBERATELY DAMAGE OR UNDERMINE THE LEGITIMATE OPERATION OF THE PROGRAM, OR ANY PART THEREOF, IS A VIOLATION OF LAWS AND SHOULD SUCH AN ATTEMPT BE MADE, PROGRAM HOST RESERVES THE RIGHT TO DISQUALIFY PARTICIPANT AND SEEK DAMAGES FROM ANY SUCH PARTICIPANT TO THE FULLEST EXTENT OF THE LAW.
* To the maximum extent permitted by applicable law, Participants and any other participants agree to release, indemnify, defend and hold harmless (“Release”) Program Host, the SOCBB Steering Committee, and the SOCBB Member Companies (the “Released Parties”) from and against any and all threatened or actual claims, debts, demands, actions, causes of action, suits, proceedings, judgments, settlements (whether or not litigation is commenced), obligations, damages (including without limitation wrongful death, bodily or personal injury and disability), losses, accounts, reckonings, executions, liabilities, costs and expenses (including reasonable attorney’s fees), property damages and any other losses, penalties or fines whatsoever of any kind or nature, whether at law or in equity, known or unknown, asserted or un-asserted, that entrant ever had, now have, or that may arise in the future (“disputes”) asserted in, arising out of or based upon participation in the Program, the Submission (in whole or in part), participation in any Program related activity (or inability to participate therein), the delivery, acceptance, use, mis-use of an award or any failure with respect thereto, damage to or destruction of property, rights of publicity or privacy, defamation or portrayal in a false light (whether intentional or unintentional), whether under a theory of contract, tort (including negligence), warranty or other theory, any act, default, omission, non-compliance, and/or a violation or breach of any agreement, representation, warranty or covenant made herein, or any other agreements by/with other contributors, Participants, Program Host, the SOCBB Steering Committee, and/or any other party or entity. Further, to the maximum extent permitted by law, and without limiting the foregoing, Participants covenant not to sue any Released Party or cause them to be sued regarding any matter released herein, and further covenant not to disaffirm, limit or rescind these releases. 
* A waiver by Program Host of any term in these Terms does not constitute a waiver of any other provision. 
* Any provision determined to be invalid shall be stricken to the extent of its invalidity and the remainder of these Terms shall remain in full force and effect.
* Program Host and the SOCBB Steering Committee shall have the right, where necessary, to undertake all action and/or require further information as is reasonable to protect themselves against fraudulent or invalid claims, potential public scandal, ridicule, or disrepute in connection with the Program and/or providing an award. 
* TO THE EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT WILL THE RELEASED PARTIES BE RESPONSIBLE OR LIABLE FOR INDIRECT, INCIDENTAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES ARISING OUT OF THIS PROGRAM OR ANY ASPECT THEREOF, PARTICIPATION (OR INABILITY TO PARTICIPATE) IN THE PROGRAM OR ANY ELEMENTS THEREOF, AND/OR THE DELIVERY, ACCEPTANCE AND/OR USE/MISUSE OF AN AWARD.
* THIS PROMOTION IS GOVERNED BY THE LAWS OF THE UNITED STATES AND THE STATE OF CALIFORNIA WITHOUT REGARD TO CONFLICT OF LAW OR CHOICE OF LAW DOCTRINES. ANY DISPUTES REGARDING OR RELATING TO THE PROGRAM OR THESE PROGRAM TERMS SHALL BE BROUGHT EXCLUSIVELY IN THE STATE OR FEDERAL COURTS LOCATED IN SAN FRANCISCO, CALIFORNIA.
* If a Participant who is eligible for an award cannot be reached after two (2) unsuccessful attempts (in Program Host’s discretion), and/or declines or refuses the award for any reason, and/or fails to timely respond or follow the instructions specified by Program Host or the SOCBB Steering Committee, and/or is non-compliant or ineligible, the award will be forfeited. Participants may waive their right to receive an award. If requested by Program Host, recipients in the Large award Category may be required to sign and return a Declaration of Eligibility, Liability and Publicity Release. 
* If Program Host and the SOCBB Steering Committee determine that a Participant’s Submission is eligible for an award, we will notify and provide instructions for processing. All award recipients are solely responsible for any local, state, federal/country or any other applicable taxes, compliance with (governmental) reporting, filing and documentation requirements, and for any other costs, expenses and fees connected with their acceptance and use of the award in their respective jurisdictions. Participants will be provided the relevant tax documentation and agree to complete, file and return such documents, as applicable. 
* All decisions made by SOCBB are final. If you do not receive a confirmation email after making your Submission, notify [bugbounty@socbb.org](mailto:bugbounty@socbb.org) to ensure your Submission was received.


---


# FAQ



* Q: Where should I make comments of different types?
    * A: technical comments about fixing bugs should be on the relevant Chromium issue. General questions should be on email lists or Chromium slack channels. Award discussions should be on the github issues for payments.
* Q: Who do I reach out to regarding Payments?
    * A: [bugbounty@socbb.org](mailto:bugbounty@socbb.org)
* Q: Can I submit more than one bug fix?
    * A: YES! There is no award limit.
* Q: How do I get access to edit bugs, commit code or access the Chromium Slack channels?
    * A: See [here](https://www.chromium.org/getting-involved/become-a-committer/) for more information.
* Q: How do I get access to faster builds?
    * A: See [here](https://chromium.googlesource.com/chromium/src/+/main/docs/linux/build_instructions.md#use-reclient).
* Q: How can I know how what category my bug will end up in?
    * A: Unfortunately we can't guarantee any particular category until the bug fix is complete, but you can email us at [bugbounty@socbb.org](mailto:bugbounty@socbb.org) for advice.

	


---
