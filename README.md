# DRAFT RequestForComments

## This is a demonstration only and not for actual use within DESC

*Modeled after [DM/Project's Request For Comments](https://developer.lsst.io/communications/rfc.html)*

By creating a Request for Comments (RFC) issue in this repository, you can make a proposal, collect feedback, build consensus, adopt a course of action, and track a decision’s implementation.

**RFCs are required when**
* Proposing a new scheme or methodology that has broad consequences related to DESC Computing.
* Updating or Deprecating Interfaces, including changes to programming interfaces and removal of packages.
* TBD

**Overview of the RFC Process**

![image](https://github.com/heather999/RequestForComments/blob/main/RFC-Flow.png)

**General Description of the RFC Process**

*Slightly modified from https://developer.lsst.io/communications/rfc.html#extended-discussion-of-the-rfc-process*

The purpose of an RFC is to inform others about the existence and content of the proposed decision and implementation in order to allow them to evaluate its impact, comment on it, refine it if necessary, and agree (implicitly or explicitly) or object (explicitly) to its execution.

The discussion of the RFC primarily takes place in the RFC issue opened in this repository.

In the RFC process, the opinions of those who will be doing the work (and fixing any problems if something goes wrong) are given more weight. In some cases, this may mean that the RFC issue’s Assignee passes to someone else. The opinions of people more experienced in the area should also be given more weight and may also result in the Assignee changing.

The Assignee is responsible for determining when no serious objections remain. In particular, there is no need to call for a formal vote on the resolution. If no explicit objections have been raised within, typically, 72 hours for “ordinary” issues and 1 week for “major” issues, the Assignee should assume that there are none. This is known as “lazy consensus.” When this state has been reached, the Assignee is responsible for ensuring that the final consensus has been recorded in the RFC issue before closing it and proceeding with implementation of the decision.

The requestor must be especially careful about not making irreversible changes in the “lazy consensus” time period unless they are absolutely certain there’s a general agreement on the stated course of action. If something is broken, the requestor must be ready to fix it. It is critical to apply sound reasoning and good judgment about what may be acceptable and what might be not. Mistakes will happen; accept that occasionally there will be a requirement to revert an action for which it was thought agreement existed.

**How to start a RFC**
* Create a [new RFC Issue](https://github.com/heather999/RequestForComments/issues) making sure to provide an adequate description of the situation and proposal as well as a "Planned End" date for comments.
* If you will be responsible for implementing the proposal, assign the issue to yourself.  If you have reached agreement with someone else to take responsibility, assign them.  If it is unclear who will handle the implementation, leave the issue unassigned and the DESC Computing Change Control Board (DCCCB) will identify an assignee.
* Once the issue is created, a notification will be posted to the #desc-rfc Slack channel
* All are welcome to comment through the indicated "Planned End" date.

**DESC Computing Change Control Board**

The DESC Computing Change Control Board (DCCCB) responsibilties include:
* Review all RFCs 
* Identify an assignee for unassigned RFCs
* Consider all "escalated" RFCs for approval or withdrawal.

Membership:  
* Computing Coordinator
* Deputy Computing Coordinator 
* Computing Working Group Conveners
* Computing Deputy Operations Manager

**Escalate a RFC**

Anyone, including DCCB members, may "escalate" an RFC if the issue requires an RFC or if the dicussion is failing to reach a consensus.  Escalated RFCs will be considered by the DCCCB for approval or withdrawal. 

**Adoption**

Before an RFC may be adopted, one or more GitHub issues must be created to capture the work required to implement the RFC’s decision.

When
* the Planned End date has passed;
* the RFC is either labelled *proposed* (that is, it has not been escalated) or *approved* (it has been escalated and subsequently approved by the DCCCB);
* the assignee judges that positive consensus has been reached; and
* a set of GitHub issues to address the RFC have been created

Then 
* Label the RFC issue as *adopted* 
* Add the RFC issue to the [*Adopted* Project](https://github.com/heather999/RequestForComments/projects/1)

**Withdrawing an RFC**

If the RFC cannot be adopted (by consensus, decision of the DCCCB, or decision of the Assignee), then you can withdraw the RFC. Assign the *withdraw* label to the RFC issue.

**Implementing an RFC**

Create a [new Project in this repo](https://github.com/heather999/RequestForComments/projects) to help track the GitHub issues necessary for an RFCs implementation.

Once all the GitHub issues associated with an RFC have been closed, the RFC issue can be labelled as *implemented* and closed.

