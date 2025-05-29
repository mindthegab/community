---
name: "\U0001F58AStandard Project Contribution and Onboarding"
about: To Contribute a Standard Project to FINOS
title: "[insert name here] Standard Project Contribution and Onboarding"
labels: contribution
assignees: maoo, TheJuanAndOnly99
---

---
# Prerequisites

## Membership requirement to contribute new projects

Please note that only FINOS members can propose new projects. If you're interested in membership, see [here](https://www.finos.org/membership-benefits#become-a-member). You can still submit this contribution if your organization is not a [FINOS member](https://finos.org/members), but you will be required to have a maintainer from a FINOS member.

- [ ] I confirm I am contributing on behalf of a FINOS member (`add FINOS member organization name`) or I will seek a maintainer from a FINOS member during socialization 

## Understading the contribution Process

Completing an onboarding of a project into FINOS comprises following 5 main steps described in details in our [Community Repository](https://community.finos.org/docs/governance/Software-Projects/contribution#contribution-of-an-existing-code-base-into-finos-as-a-new-project). 

 - [ ] I confirm I have reviewed the contribution process.

## Understanding FINOS

As a project onboarding into FINOS, you should familiarize yourself and your contributor team with the following FINOS information: [FINOS overview](https://www.finos.org/hubfs/An%20Introduction%20to%20FINOS.pdf), [FINOS Standard Projects Governance](/docs/governance/#open-standard-projects), [FINOS Project Lifecycle](/docs/governance/Software-Projects/project-lifecycle), [FINOS Maintainers cheatsheet](/docs/finos-maintainers-cheatsheet/).

- [ ] I confirm I am familiar with the FINOS Standards governance and maintainers responsibilities

---
# Contribution information

## Describing The Contribution

This section contains information to be provided by the original to give it the best chances to be approved. They largely mirror the requirements described in the [incubation checklist](/docs/governance/software-projects/stages/incubating/#incubating-lifecycle-checklist). Please fill below as appropriate:

### Proposed Project Metadata
- Name: `enter here proposed standard name`
- Slug: `enter here proposed standard short description`
  
> Please review the [trademark checks](docs/governance/Software-Projects/contribution#trademark) that will be performed on the projects.

### Business Problem
> Describe the business or technical problem the standard solves and for whom
 
### Proposed Solution
> Describe how this standard project solves that business problem

### Tentative Roadmap
> Describe the short and medium term goals and phases of the project. What does success look like for this project?

### Scope
> Clearly define the scope of the standard to define the patent license boundaries. In cases where the scope is expected to be defined by the standard project participants this should be one of the first tasks the group completes. Guidelines can be found in the [Community Specification Best Practices #3]([https://github.com/finos/standards-project-blueprint](https://github.com/finos/standards-project-blueprint/blob/main/governance-documents/Getting%20Started.md#best-practices))

### Current State
*Summarize the history and current state of the project*
 
### Identify existing project resources and materials
 - [ ] Does the project have a public Source Repository?
   - If so, what's the URL for the repository: `replace if it exists or add N/A`
   - [ ] If code is private, was @finos-admin already given read-only permissions to the repo or a code provided to the team?
 - [ ] Is Continuous Integration used?
   - If so, which CI/CD system is used: `enter here`
 - [ ] Was the project ever had public releases? 
   - If so, where's the latest released version: `add link here`
 - [ ] Does the project build work successfully?
   - If so, please add link to build instructions: `add link to build instructions`
 - [ ] Does the project have existing documentation?
   - If so, provide more information: `add site URL / PDF / etc here`
 - [ ] Does the project have a registered trademark or the name has been prevously used in the public domain?
   - If so, add link to previously used public links : `link to press release / repository / blog`
 - [ ] Is there an existing logo?
   - If so, please add link or attach to the issue: `link to high res logo or added as attachment`
 - [ ] Is there a high-level pitch deck to be evaluated by Technical Oversight Committee?
   - If so, please add link or attach to the issue: `link to a ~15 mins slide deck or added as attachment`
 - [ ] Are meetings currently held for the project?
   - If so, please add link to current meeting schedule / minutes: `link to meeting details`
 - [ ] Is it a data model?
   - [ ] If so, are you interested in modeling it in the [FINOS Legend Studio Sandbox](https://www.finos.org/legend)?

## Standard Project Team
FINOS uses the [Community Specification License](https://github.com/finos/standards-project-blueprint/blob/main/governance-documents/1._Community_Specification_License-v1.md) for its standards, which clearly defines [three key roles](https://github.com/finos/standards-project-blueprint/blob/main/governance-documents/5._Governance.md#1roles) to develop a specification. Please provide as much information as possible on who will fulfill these roles: 

### Maintainers
*Maintainers are responsible for organizing activities around developing, maintaining, and updating the specification(s). Provide full name, affiliation, GitHub / GitLab username and email address where available:*

|Name                        |Affiliation              |Work Email Address             |Github / GitLab username              |
|----------------------------|-------------------------|-------------------------------|--------------------------------------|
|John Example                |Example LTD              |john@example.com               |@johnexampleabc                       |
|Jane Example                |Example LTD              |jane@example.com               |@janeexamplexyz                       |

### Editors
*Editors are responsible for ensuring that the contents of the document accurately reflect the decisions that have been made by the group, and that the specification adheres to formatting and content guidelines. Provide full name, affiliation, GitHub / GitLab username and email address where available:*

|Name                        |Affiliation              |Work Email Address             |Github / GitLab username              |
|----------------------------|-------------------------|-------------------------------|--------------------------------------|
|John Example                |Example LTD              |john@example.com               |@johnexampleabc                       |
|Jane Example                |Example LTD              |jane@example.com               |@janeexamplexyz                       |

### Confirmed Participants
*Participants are those who are expected to made Contributions by joining project meetings and via pull requests. Please list all of the individuals that have expressed interest in and/or are committed to contributing to this project, including full name, affiliation, GitHub  / GitLab username and email address where available:*

|Name                        |Affiliation              |Work Email Address             |Github / GitLab username              |
|----------------------------|-------------------------|-------------------------------|--------------------------------------|
|Contributor1 Example        |Example LTD              |con1@example.com               |@con1xampleabc                        |
|Contributor2 Example        |Example LTD              |con2@example.com               |@con2examplexyz                       |

### Target Contributors
*Describe the contributor profile (background, position, etc) and if applicable organizational profile (financial institutions, tech vendors, consulting firms, etc) you would like to get contributions from*

## Preferred project infrastructure
If the project is approved, FINOS will provision the infrastructure necessary for [development, release and project collaboration](https://community.finos.org/docs/collaboration-infrastructure). Below a list of questions which will help us accelerate the onboarding process and tailor it to the maintainers needs:

- Which code hosting platform does the project prefer? *[Github](https://github.com/finos/)|[GitLab](https://gitlab.com/finos)* 
- Please check below which asynchronous collaboration channels will the project like to use?
  - [ ] GitHub Issues
  - [ ] GitHub Public Discussions
  - [ ] GitHub Team Discussions _(consisting of the above described contributors)_
    - Public (Mandatory) _(consisting of the above described contributors)_
    - [ ] Private (Optional)
  - [ ] Mailing-list (lists.finos.org)
    - General (Mandatory, for project community): `add preferred address, XXXX-general@lists.finos.org`
    - [ ] Private (Optional)
  - [ ] FINOS Slack Channel _(consisting of the above described contributors)_
    - General Project Community Public channel (mandatory): `add preferred channel name, e.g. #projectName-general`
    - [ ] Maintainers Private Channel (Optional) `add preferred channel name, e.g. #projectName-maintainers`
- Synchronous
  - [ ] Will the project host recurring meetings complying with the [FINOS meeting procedures](https://community.finos.org/docs/governance/meeting-procedures)?

---
# Next steps and what to expect 

## 1. Socialisation 
It's highly recommended that once you submit this issue, you or anyone in the maintainer team proceed with socializing directly to the [FINOS community](mailto:community@finos.org) and through your personal network. The goal is to generate interest, support and ideally additional committed maintainers expressing the interest on the issue before it's sent to the Technical Oversight Committee for approval. 

Instructions and a template for you to adjust are avaialble in the [Contribution Process Socialization](https://community.finos.org/docs/governance/software-projects/contribution/#step-2-socialization) documentation.

- [ ] I confirm I have socialized this contribution to `community@finos.org` (to be checked after the issue is raised)
    
## 2. Approval
The [FINOS Governing Board]([https://github.com/finos/technical-oversight-committee](https://www.finos.org/governing-board)) is responsible for approving new FINOS standards.

Once you are happy with the socialization phase (garnered enough support / interest, addressed open questions, etc), please check the box below and put a comment on this issue so it can be sent to the Governing Board for approval via email or at the next Governing Board meeting . 

- [ ] I am happy for this issue to be sent to the Governing Board for formal review and approval
- [ ] FINOS Infra team notifies leadership@finos.org to trigger Governing Board approval and assigned this issue to COO
- [ ] FINOS Leadership confirmed timing and procedure of Governing Board vote with contributors 

### Governing Board Approval findings 
- [ ] FINOS Governing Board reviewed the contribution and the contribution was: `accepted|rejected`

> FINOS team to enter high level findings summary here supporting the decision

## 3. Preparing For Onboarding
Before the FINOS team can onboard your project, there are a few housekeeping items that need to be taken care of from an IP and infastructure standpoint. These must be completed by the contributor, with help if required from the FINOS Infrastructure team, so please familiarize yourself with the [requirements](/docs/governance/software-projects/contribution/#step-4-ip-review--transfer-of-contributions).

### Steps
- [ ] Usable name and logo identified (either existing or new)
  - [ ] FINOS team confirmed project brand and logo are usable in the public domain. This might require completion of [project contribution agreement](https://community.finos.org/governance-docs/The.Linux.Foundation.--.Form.of.Trademark.Assignment.20221202.pdf) to properly assign trademarks.
  - [ ] Failed the above, new project name and logo is identified
- [ ] FINOS team enables [EasyCLA](https://easycla.lfx.linuxfoundation.org/#/) with Community Specification License
- [ ] FINOS contributor license agreement is reviewed and executed by all maintainers
- [ ] FINOS team was given admin access to any existing project account (e.g. GitHub, domain names, social media) to be able to act on behalf of the contributor for accounts related to the project  
- [ ] Kick-off meeting organized by FINOS team, including:
   - [ ] Review contribution checklist with FINOS staff
   - [ ] Contributor confirms having reviewed [FINOS standard project procedures](/docs/governance/Standards-Projects)) and agreed to adopt governance
   - [ ] FINOS agrees with maintainers on category and sub-category (for [FINOS Landscape](https://landscape.finos.org/))
   - [ ] Update Project badge


## 4.  Transfer and onboarding in FINOS
This is performed by FINOS Infra once the three previous stages are complete, with support from the contributor and the FINOS Infra team.

## Code transfer preparation
- [ ] Maintainer has made [finos-admin](http://github.com/finos-admin) Admin of the GitHub repository to transfer

## Existing assets transfer Meeting
- [ ] Transfer all  assets as GitHub repositories under github.com/finos
- [ ] Rename main branch to `main` (instead of `master`)
- [ ] Check that CVE (and preferably static code analysis, if applicable) scanning is in place
- [ ] Enable [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) (`Require a pull request before merging`)
- [ ] Enable automated dependency update, using [Renovate](https://renovatebot.com/)
- [ ] (best effort or to be completed right after onboarding) Update release coordinates and code namespace to include `finos`
- [ ] Communication channels are linked front and center in the project README.md

---
# Announcement 
- [ ] Issue assigned to FINOS DevRel team
- [ ] Mantainer team agreed with FINOS DevRel team on announcements sequencing: `add link to internal task`
  - [ ] Technical announcement was sent to announce@finos.org (see [template](https://community.finos.org/docs/governance/Software-Projects/contribution#step-5-contribution-announcements): `add link to announce@ archive` 
  - [ ] If applicable, project was announced on FINOS marketing channels: `add link to FINOS social / press release`
