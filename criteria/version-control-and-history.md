---
order: 5
---

# Maintain version control

## Requirements

* You MUST have a way to maintain version control for your code
* All files in a codebase MUST be version controlled
* All decisions MUST be documented in commit messages
* Every commit message MUST link to discussions and issues wherever possible
* You SHOULD group relevant changes in commits
* You SHOULD mark different versions of your codebase using tags
* You SHOULD prefer file formats that can easily be version controlled

## Why this is important

Version control means keeping track of changes to your code over time. This allows you to create structured documentation of the history of the codebase. This is essential for collaboration at scale.

Version control enables you to:

* revert to an earlier version of the codebase whenever you want to
* record your changes and the reasons why you made them, to help future developers understand the process
* compare two different versions
* work on changes in parallel as a team before merging them together

## What this does not do
* Substitute for advertising maturity.
* Guarantee your code executes correctly.
* Guarantee collaborators.

## How to test

* The codebase is kept in version control using software such as Git.

* All commit messages explain:
  * why the change was made
  * what the discussion about the change was or where to find it (with a URL)
* It is possible to access a specific version of the codebase through a tag

## Policy makers: what you need to do
* If a new version of the codebase is created because of a policy change, make sure it's clear in the documentation:
  * what the policy change is
  * how it's changed the codebase

For example, adding a new category of applicant to a codebase that manages granting permits would be considered a policy change.

## Management: what you need to do
* Support policy makers, developers and designers to be clear about what improvements they're making to the codebase - making improvements isn't a public relations risk.

## Developers and designers: what you need to do
* Write clear commit messages so that it is easy to understand what why the commit was made.
* Use tags to mark different versions so that it is easy to access a specific version.
* Work with policy makers to describe how the source code was updated after a policy change.

## Further reading

* [Producing OSS: Version Control Vocabulary](https://producingoss.com/en/vc.html#vc-vocabulary) by Karl Fogel
* [Maintaining version control in coding](https://www.gov.uk/service-manual/technology/maintaining-version-control-in-coding) by the UK Government Digital Service
