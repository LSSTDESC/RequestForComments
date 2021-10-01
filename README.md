# RequestForComments

By creating a Request for Comments (RFC) issue in this repository, you can make a DESC Computing proposal deserving of DESC-wide visiblity, collect feedback, build consensus, adopt a course of action, and track a decision’s implementation.

Some example proposals:
* add/deprecating packages in the DESC Computing environment
* configurations settings for simulations or processing
* choosing a file format for a particular use-case  

Any DESC member is free to comment on and open an issue for RFC. The individual submitting the RFC is not expected to take part in the implementation of the idea presented.

## Outline of the DESC Computing RFC Process

* Once the RFC issue is created, a notification will be posted to the #desc-co Slack channel
* All are welcome to respond during the comment period which is nominally one week
* When a preliminary decision has been made, it will be outlined in the RFC issue and a final opportunity will be provided for people to comment.
* After the comment period has closed and a decision is made, it will be summarized in the RFC issue.
* If the RFC results in some decision or action, the issue will be labelled ["adopted"](#adoption)
* If the RFC cannot be accepted, the issue will be labelled ["withdrawn"](#withdrawing-an-rfc)
* If an adopted RFC requires action for implementation, a new Project will be created in this repo
  * Issues will be opened to address all tasks necessary.
  * Once the Project and corresponding issues are closed, the RFC issue will be labelled as "implemented" and closed.
* The RFC issues in this repository will serve as a searchable record of porpo

## How to start a RFC
* Create a [new RFC Issue](https://github.com/LSSTDESC/RequestForComments/issues) making sure to provide an adequate description of the situation and proposal.
* Once the issue is created, a notification will be posted to the [#desc-co](https://lsstc.slack.com/archives/C2M6H2LAX) Slack channel
* All are welcome to comment.


## Adoption

Before an RFC may be adopted, one or more GitHub issues should be created to capture the work required to implement the RFC’s decision.

* Label the RFC issue as *adopted* 
* Add the RFC issue to the [*Adopted* Project](https://github.com/LSSTDESC/RequestForComments/projects/1)

## Withdrawing an RFC

If the RFC cannot be adopted, then it can be withdrawn. Assign the *withdraw* label to the RFC issue and close.

## Implementing an RFC

Create a [new Project in this repo](https://github.com/LSSTDESC/RequestForComments/projects) to help track any GitHub issues necessary for an RFCs implementation.

Once all the GitHub issues associated with an RFC have been closed, the RFC issue can be labelled as *implemented* and closed.

