# Bug-Bounty-Program
Chromium Bug Bounty Program

This is a program funded by [Supporters of Chromium-Based Browsers](https://www.linuxfoundation.org/supporters-of-chromium-based-browsers), to provide payment for fixing open Chromium issues that are **user-facing or developer-facing browser bugs**. The amount of the payment will be scaled to the importance of the bug, similar to how the [Chrome Vulnerability Reward Program](https://bughunters.google.com/about/rules/chrome-friends/5745167867576320/chrome-vulnerability-reward-program-rules) works. The total Program Budget is $300,000 with an initial time frame of 6 Months


## Goals



* Incentivize and enable external developers to fix bugs that measurably improve Chromium’s quality for web developers and users.
* Allow freedom to external developers to choose their bugs and find bugs to fix that matter to them, & demonstrate the impact of their work to us.
* Increase the size of the Chromium community.


# Issues in scope

Any open Chromium [issue](https://issues.chromium.org) that:



* Is not already owned by someone.
* Fixes one or more logical errors directly visible to web developers or users.
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

If you have questions RE: Scope please contact  


---


# Submissions

Submissions must be reviewed and approved by at least 2 representatives from SOCBB or their member companies to receive payment. Inputs to the decision include the following:



* Code and test must be done in one of the main line Chromium repositories including:
    * Chromium
    * V8
    * Skia
    * Devtools-frontend
    * WebRTC.
* bug fixes must make it to the stable channel of a major Chromium browser (e.g. Chrome and Edge) and stay there for at least 2 weeks without being reverted or otherwise disabled.
* Any new bugs filed as being caused by the fix within this period must also be fixed (and are not independently eligible for payment).
* Fixes must not reintroduce previously fixed bugs (e.g. cannot simply revert a prior bugfix which also caused a regression).
* Contributors are expected to behave according to the [Chromium Code of Conduct](https://chromium.googlesource.com/chromium/src/+/main/CODE_OF_CONDUCT.md#:~:text=Be%20respectful%20and%20constructive.,condescension%2C%20whether%20blatant%20or%20subtle.). Violations may lead to permanent disqualification from this program.
* Fixes need to be fully reviewed and approved by relevant code OWNERS. Chromium has a high-bar for code quality and as complex code architecture. Code OWNERS and other project members are available to guide new contributors, but will not do the work for them. If a submitted fix is judged by reviewers to be substantially below the project's bar for code quality (such as by requiring significant and repeated rounds of code review feedback atypical even for new project contributors), it will become ineligible for payment.  
* If regular progress is not made towards fixing a bug (e.g. no update in a week), it may be unassigned in order to be reassigned to someone else. In rare cases of urgent bugs (those marked Pri0 or Release blocking), proposed fixes may be required much faster to avoid reassignment. 

The SOCBB Steering Committee reserves the right to make a holistic decision based on all factors. In an effort to help support the community, the SOCBB Steering Committee has  proactively identified some bugs as good candidates for this program, labeled by the minimum expected payment category. If the work has been deemed to be more than the initial assumption the steering committee may choose to increase the category but will not decrease it. 




# SOCBB Bug Bounty GitHub Submission Template

Before reaching out, please ensure that your project has been fully tested, and released for at least 2 weeks in a stable version of a Chromium browser, as we do not review work that is still in progress. 

When your work is ready, Please Submit your contribution in a new Issue on the [SOCBB Bug Bounty GitHub](https://github.com/Supporters-Of-Chromium-Based-Browsers/bug-bounty-program) and include the following information:


* Bug Name and Description: Provide a brief overview (1 sentence) highlighting your project’s community usage and its significance within the broader Chromium ecosystem.
* Link to the Chromium bug: Share links to your contributions that support your request. These contributions must be publicly accessible without requiring login or account creation.
* GitHub Profile Link: Include a link to your GitHub profile.

The more detailed and clear your submission, the faster and more efficiently SOCBB can process your request for Bug Bounty Program Award.


## Payments will run through Github Sponsors

All payments will be processed through GitHub Sponsors, so a GitHub account is required to receive a financial recognition. Please note that only individuals and organizations participating in the[ GitHub Sponsors](https://github.com/sponsors) Program are eligible for rewards.

We will generally review submissions and provide a response by the 15th of the month following your submission. Payments will generally be issued in the first week of the month following submission approval.


---


# Award Sizing


## Large $10,000

HOTLIST: 

Items not found on the hotlist will also be considered if one of these factors holds, the fix **may** be appropriate for the Large payment category:



* Is a top issue for many web developers or users, (eg. has a high star count)
* Evidence that the bug significantly affects more than **1%** of the users of a Chromium-based browser
* Affects Interop 202x score by more than **0.1%**
* Improves competitive performance score by more than **0.5%**, or a Core Web Vital by more than **0.5%**
* It had most of one of the above factors, and inherent difficulty of fixing the issue is high or the fix solved a systemic code quality problem beyond the scope of the bug in question.


## Medium $1,000

HOTLIST

Items not found on the hotlist will also be considered if one of these factors holds, the fix **may** be appropriate for the Medium payment category:



* Impacts many web developers or users
* Evidence that the bug significantly affects more than **0.1%** of the users of a Chromium-based browser
* Affects Interop 202x score
* Improves competitive performance score by more than 0.1%, or a Core Web Vital by more than 0.1%


## Small $250



* It’s a real user or developer bug.


---


# Instructions

Please follow the instructions below carefully. Failure to do so could result in late payments or overlooked submissions. Any questions regarding the SOCBB Bug Bounty Program Should be directed to [bugbounty@socbb.org](mailto:bugbounty@socbb.org). 

How to submit a Bug Fix 


## Step 1 Fix the bug in Chromium

[https://www.chromium.org/getting-involved/](https://www.chromium.org/getting-involved/) gives general advice on how to get started with Chromium development, and how to ask questions. If you’re stuck, you can also email [bugbounty@socbb.org](mailto:bugbounty@socbb.org) for help.


## Step 2 Submit your Award request in GitHub

When your work is ready, Please Submit your contribution in a new Issue on the [SOCBB GitHub](https://github.com/Supporters-Of-Chromium-Based-Browsers/Foundation) and include the following information:

**Bug Name or Description: **Provide a brief overview (1 to 5 sentences) highlighting your bug’s ge and its significance.

**Contribution Links:** Share links to your contributions that support your request. These contributions must be publicly accessible without requiring login or account creation.

**GitHub Profile Link: **Include a link to your GitHub profile.

**Request Reward Size: **Specify the amount you are requesting and explain why. Please refer to the Size table for details on what is expected for each reward level.

The more detailed and clear your submission, the faster and more efficiently SOCBB can process your request for Pilot Program recognition.


---


# Terms and Conditions


## Eligibility

All participants must be eligible to use the GitHub Sponsor’s program, available at[ https://docs.github.com/en/site-policy/github-terms/github-sponsors-additional-terms](https://docs.github.com/en/site-policy/github-terms/github-sponsors-additional-terms)

GitHub Sponsors requires your compliance with additional eligibility and program terms related to any recognition payment, including age eligibility, taxes, fees, sanctions, and other terms which you must agree with prior to making any Submission.

Employees or family members of employees of sponsoring companies are not eligible for a recognition payment.

It is your responsibility to comply with any policies that your employer may have that would affect your eligibility to participate in the Pilot Program. If you are participating in violation of your employer’s policies, you may be disqualified from participating or receiving any recognition payment.

There may be additional restrictions on your ability to enter depending upon your local


## Terms



* SOCBB reserves the right to change or terminate this Pilot Program at any time. Any Submission under the Pilot Program is subject to the program details and terms available at that time.
* Do not undertake any contribution or work with an expectation of a recognition payment for a future Submission. This is a Pilot Program with a limited budget for reward payments. Once the budget has been exhausted, SOCBB will not make any additional recognition payments under this Pilot Program. Consequently, some qualifying Submissions may receive reduced recognition payments or no recognition payments at all. Therefore, it is possible that your Submission could qualify for a recognition payment, yet no recognition payment will be issued. SOCBB is not responsible for Submissions that we do not receive for any reason.
* SOCBB also reserves the right to refuse payment at its sole discretion if it believes a submission undermines the spirit of this Pilot Program or if making the recognition payment would be illegal.
* If SOCBB determines that your Submission is eligible for a recognition payment, we will notify you and provide instructions for processing your payment. You also have the option to be recognized but choose to waive the recognition payment if you prefer not to receive a recognition payment. If you are unable or unwilling to accept a recognition payment, SOCBB reserves the right to rescind any recognition payment.
* If you accept a recognition payment, you will be solely responsible for all applicable taxes related to that recognition payment
* All decisions made by SOCBB are final. If you do not receive a confirmation email after making your Submission, notify info@SOCBBdev.com to ensure your Submission was received.


---


# FAQ



* Q: Where should I make comments of different types?
    * A: technical comments about fixing bugs should be on the relevant Chromium issue. General questions should be on email lists or Chromium slack channels. Payment discussions should be on the github issues for payments.
* Q: Who do I reach out to regarding Payments?
    * A: [operations@socbb.org](mailto:operations@socbb.org) 
* Q: Can I submit more than one bug fix?
    * A: YES! There is no award limit.
* How do I get access to edit bugs, commit code or access the Chromium Slack channels?
    * A: See [here](https://www.chromium.org/getting-involved/become-a-committer/) for more information.
* How do I get access to faster builds?
    * A: See [here](https://chromium.googlesource.com/chromium/src/+/main/docs/linux/build_instructions.md#use-reclient).
* How can I know how what category my bug will end up in?
    * A: Unfortunately we can't guarantee any particular category until the bug fix is complete, but you can email us at [bugbounty@socbb.org](mailto:bugbounty@socbb.org) for advice.

	


---
