

## **Amendment to Bug Bounty Rules: Inactivity Policy**

**Effective Date:** [May 2026]


### **Overview**

To ensure the fairness and health of the Bug Bounty program, the Steering Committee has moved to address "issue hoarding"—where bugs are assigned to a contributor but remain stagnant for extended periods. This amendment shifts the program from a passive "one-week" suggestion to a proactive two-week inactivity removal policy, synchronized with the monthly review cycle.


---


### **New Policy: 2-Week Inactivity Rule**



* **Inactivity Definition:** A bug is considered "inactive" if there has been no meaningful progress for 14 consecutive days. Progress includes public updates to the bug report, draft CLs (Change Lists) in Gerrit, or active discussion regarding the implementation strategy.
* **The Monthly Review "Hard Revoke":** During each monthly review session, the administrators will audit all currently assigned bugs. Any bug showing 2+ weeks of inactivity will be subject to a hard removal—it will be unassigned and returned to the Available queue immediately. A comment will be left on the bug notifying the previous owner of the removal.
* **Re-assignment:** If a bug is returned to the available pool, the previous owner may re-assign it to themselves only if they have immediate, active work to submit. However, the bug remains "fair game" for any other contributor once it is unassigned.


---


### **Guidelines for Community Fairness**



* **Communication First (No "Going Dark"):** If a contributor is blocked (e.g., waiting for a reviewer or a spec decision), they must leave a comment on the bug to flag the delay and prevent it from appearing stagnant during the monthly audit. \
To remain exempt from a hard removal, the contributor must provide a rough ETA for when they expect to be unblocked, demonstrate active effort to resolve the blocker, and continue to update the bug with their latest status **at least every 2 weeks**. Leaving a single comment and then going silent for a month or longer will still result in the bug being unassigned.
* **Encouraging Takeovers:** After two weeks of visible inactivity, any community member is encouraged to comment on a bug and politely ask to take it over. We recommend a 24-hour waiting period after the comment before re-assigning it to oneself to allow the original owner to respond.
* **Edit Bug Access:** To level the playing field for non-committers, the program now explicitly links to the Chromium Edit Bug Access criteria. Contributors who have landed several non-trivial patches are encouraged to apply for these privileges to manage their own assignments. You can review the criteria here:[ Chromium Issue Tracking - Get Edit Bug Access](https://www.chromium.org/getting-involved/issue-tracking/#get-edit-bug-access).


---


### **Update to Payout Eligibility**



* **Stable Channel Rollout Requirement:** Bug fixes must make it to a **100% rollout** of the stable channel of a major Chromium browser (e.g., Chrome and Edge) and stay there for at least 2 weeks without being reverted or otherwise disabled. \
*Note: This ensures the feature or fix has received adequate real-world feedback and exposure before the bounty is finalized.*
