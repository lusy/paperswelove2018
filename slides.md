% Operationalizing Conflict and Cooperation between Automated Software Agents in Wikipedia: A Replication and Expansion of “Even Good Bots Fight”
% Papers We Love Berlin October 2018

---

## Background

* replication study of "Even Good Bots Fight" (2016)
* published November 2017

---

## Aim of the paper

> "to what extent are bot-bot reverts in Wikipedia genuine conflicts where disagreements about how Wikipedia ought to be written were embedded in opposing bot codebases?"

---

## Who are the authors

background: wikipedia researchers + long-time contributors

* **Geiger**:  "a staff ethnographer at the Berkeley Institute for Data Science at UC-Berkeley"
* **Halfaker**: computer scientist, principle research scientist of the Wikimedia Foundation

---

## Structure of the paper

* introductory vignette
* authors' positioning
* epistemology
* operationalise key terms
* limitations

---

## Operationalising conflict

According to "Even good bots fight"

> "The EGBF paper operationalized bot-bot conflict through reverts, which is when one user account undoes another user account’s edit." 

---

According to Geiger and Halfaker

* Conflict typology: task conflict - process conflict -relationship conflict
* it's a culturally specific concept!

---

Types of conflicts:

* bot-bot conflict: bots are programed with opposing directives --> not many cases found
* conflict about bots: human editors in conflict over what bots ought to be developed --> many cases found, conflict not limited to discussions about bots though, part of day-to-day work on Wikipedia
* sometimes conflict turns interpersonal

---

## What is actually a bot

> "for us, bots are inextricably linked to their developers, rather than autonomous agents who can be studied independently of the people who develop and operate them. Speaking to this, many Wikipedia bot developers name their bot not after the task it does, but after themselves [...]"

---

## Methodology

iterative mixed method combination of:

* quantitative methods: mining big data sets/computational social science
* more traditional social science/qualitative methods, e.g. interviews, observations, experiments

---

* trace ethnography
* cooking data with care

---

What are the traces they looked at:

- start with the revision ID of an identified bot-bot revert
- follow other traces to find other contextual information, such as:
  - what was changed in the revert,
  - the bot developer’s summary of what the bot was doing at the time,
  - the other edits that both bots had made,
  - both bots’ Requests for Approval before the Bot Approvals Group (if any),

---

  - the various talk pages where Wikipedians would raise and resolve the conflict (in cases of genuine conflict),
  - and the various policies and guidelines in force at the time of the revert.

---

## Dataset

### EGBF

* 2001-2010
* does not contain full metadata for each edit
* generated by software code that is not publicly available

---

### Here

* Dec 31 2016
* which language versions does it comprise
English, German, Japanese, French, Portuguese, Spanish, and Mandarin Chinese

---

* identify bots
  * bot user group (limitations: bots get frequently removed from/unflagged when they are no longer active)
  * user_former_groups : former bots
  * "Bot user" cross-wiki category
* identify reverts with: https://github.com/mediawiki-utilities/python-mwreverts

---

### important metrics
  
  * time between reverts
  * number of reverts per article for the same bot pair

---

## Various types of bot-bot reverts

---

### Non Conflict

* fixing double redirects (evtl diagram)
* migrating interwiki links
- updating of article notification templates (page is protected from editing or has some issue; template removed when the issue is resolved)
- moving categories
- editing "per" justification: "single purpose bots that are written to implement a decision reached
by Wikipedians that applies to many articles in a category or even across the encyclopedia." --> may be reverted when consensus change again

---

###  conflict

Mathbot and Frescobot over link syntax.

  - no fundamental disagreement between developers about what ought to be done
  - bots still programmed with opposing tasks
  - took over 2 years before it was noticed

---

Mathbot's disambiguation links

  - conflict/disagreement between Wikipedians about: first task, then process and at the end it also turned to interpersonal for some people

---

Archiving links: AnomieBot vs CyberBot II.

  - 41 revert sequence on a single page over the course of only 4 days,
  - most intensive bot-bot revert war in our dataset in terms of reverts per page per day
  - task conflict; one of the bots had a bug

---

## Limitations

* limitations in found data: the traces they work with have a primary purpose other than facilitating scientific research
* limitations in trace ethnography: although Wikipedia is an open system, data do not speak for themselves, but contextual knowledge is needed
* primary language of both authors is English
* "We are humans and humans make mistakes."

---

## Key insights

* only a very small amount of the bot-bot reverts are cases of genuine conflict
* majority of reverts: cases of routine collaborative work between bots
* do not tear data out of context! apply critical scrutiny to your whole process

---

> "There is inevitably something left behind or incompletely captured in any transcription or translation of an entity or event in the world."

---

## What's so great about the paper

* the positioning of the authors; objectivity from a unmarked perspective vs situated knowledges
* methodology! --> open science (repos, ...)
* replication study

---

# Thank you!

These slides are under the [by-sa Creative Commons License](https://creativecommons.org/licenses/by-sa/4.0/).

![by](images/Cc-by_new_white.svg)
![sa](images/Cc-sa_white.svg)

---

# Questions? Comments? Thoughts?
