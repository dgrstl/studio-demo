---
description: Steps to take when triaging customer-facing tickets/issues.
---

# Ticket Triage

## Triage

Before opening an issue with Engineering, search in the issue [search](http://github.com/stoplightio/platform-internal/issues) for any relevant errors/jargon.

If the error is unknown:

* If unclear on where the error is occurring, ask requester for screenshot/video/gif.
* Ask requester for screenshot/capture of developer console \(docs link [here](https://support.stoplight.io/hc/en-us/articles/360034152371-Opening-your-browser-s-developer-tools)\).
* Ask for any relevant actions that reproduces the error \(clicking X, adding Y model, etc\). _Be sure to include these items in the issue._
* Ask if refreshing resolves the issue \(could be related to [this](https://github.com/stoplightio/platform-internal/issues/2301) issue\).

## Creating Github Issues

> If there is already an existing issue, follow same series of steps as outlined below but without creating a new issue.

Issues should always be logged in the [platform-internal](https://github.com/stoplightio/platform-internal/issues) repository:

* Include a link to the Zendesk ticket in the issue/comment.
* If a specific error message is logged \(for example, "Cannot read property..."\), be sure to include the _text_ of that message in the issue body.
* Add labels:
  * **cs/reported**
  * **bug**, if applicable
  * **priority**
    * **p/urgent** = Needs to be worked on right now. Escalate to Ross and Filipe.
    * **p/high** = Needs to be tended relatively soon \(within the next 2-3 weeks\). This can be high priority bugs, issues that are painful, or ones that are very annoying and have a high priority of occurring.
    * **p/medium** = Non-urgent, can be worked on soon-ish.
* Add to [Customer Success Project](https://github.com/orgs/stoplightio/projects/5) for tracking purposes, under the appropriate product pipeline.

## Updating the Ticket

Update ticket attributes:

* Mark as **bug report** if Github issue was created or linked
* Mark as **product problem** or **question**, if applicable
* Mark specific components affected \(Spectral, Studio, etc\)

Paste link to Github issue into ticket. Comment back to the user letting them know we have been able to reproduce, and mark as **on-hold** while waiting for engineering for an update.







