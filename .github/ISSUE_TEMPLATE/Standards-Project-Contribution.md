---
name: "\U0001F58AStandard Project Contribution and Onboarding"
about: To Contribute a Standard Project to FINOS
title: Standard Project Contribution and Onboarding
labels: contribution
assignees: maoo, TheJuanAndOnly99

---
Please note that only FINOS members can propose new projects. If you're interested in membership, see https://www.finos.org/membership-benefits#become-a-member.

# Onboarding Process

Completing an onboarding of a project into FINOS requires following these 5 main steps:  

1.  [**Describing the Contribution**](#1-describing-the-contribution) _led by contributor_
2.  [**Approval**](#2-approval) _led by FINOS TOC_
3.  [**Preparing for Onboarding**](#3-preparing-for-onboarding) _led by contributor_
4.  [**Onboarding**](#4--finos-onboarding) _completed by FINOS Infra_
5.  [**Announcement**](#4--finos-onboarding) _led by FINOS Marketing_

# 1. Describing The Contribution

This is a list of questions that need to be answered by the contributor in order to allow a new project to pass to the approval stage of onboarding.

## Business Problem
*Describe the business problem or opportunity the proposed standard addresses*
 
## Proposed Solution
*Describe the proposed standard, including the format if known (e.g. specification, model, extension to existing standard) and how it solves that business problem*

## Tentative Roadmap
*Describe the short and medium term goals and phases of the project. What does success look like for this project?* 

## Scope
*Clearly define the scope of the standard. In cases where the scope is expected to be defined by the standard project participants this should be one of the first tasks the group completes. Guidelines can be found in the [Community Specification documentation](https://github.com/finos/standards-project-blueprint).*

## Current State
*Summarize the history and current state of the project*
 
## Existing Materials
*If materials already exist, provide a link to them that Foundation staff can access - if it's in a private GitHub.com repository, you should invite the finos-admin user with R/O permissions to those repositories*

 ## Identify project meta (Lead: FINOS Contrib POC, Support: FINOS Marketing)
- [ ] Project Name
    - [ ] Standard Name
    - [ ] Assess current trademark status
    - [ ] Define new project name (if applicable)
    - [ ] Design new project logo (if applicable)
    - [ ] Trademark new project name and logo (if applicable)
- [ ] Category and sub-category (for FINOS Landscape)
- [ ] Existing code or new Github repository
- [ ] Existing code releases (and which artifact repositories are used)
- [ ] Team composition: lead maintainer and other maintainers
- [ ] Meetings (existing/yes/no)
- [ ] Meeting minutes, agenda, attendance tracking (existing/yes/no)
- [ ] Continuous Integration (existing/yes/no)
- [ ] Documentation website (existing/yes/no)
- [ ] Define project slug

## Development Team

### Maintainers
*Who will be the [project maintainer(s)](https://community.finos.org/docs/finos-maintainers-cheatsheet/#maintainer-responsibilities-and-available-resources)? Provide full name, affiliation, work email address, and GitHub / GitLab username.*

|Name                        |Affiliation              |Work Email Address             |Github / GitLab username              |
|----------------------------|-------------------------|-------------------------------|--------------------------------------|
|John Example                |Example LTD              |john@example.com               |@johnexampleabc                       |
|Jane Example                |Example LTD              |jane@example.com               |@janeexamplexyz                       |


### Confirmed contributors
*If applicable, list all of the individuals that have expressed interest in and/or are committed to contributing to this project, including full name, affiliation, work email address, and GitHub.com username*

|Name                        |Affiliation              |Work Email Address             |Github / GitLab username              |
|----------------------------|-------------------------|-------------------------------|--------------------------------------|
|Contributor1 Example        |Example LTD              |con1@example.com               |@con1xampleabc                        |
|Contributor2 Example        |Example LTD              |con2@example.com               |@con2examplexyz                       |


### Target Contributors
*Describe the contributor profile (background, position, organization) you would like to get contributions from.*

## Project Communication Channel(s)

- [ ] Contributor to ask maintainers which communications channels they'd like to use:
- Asynchronous
  - [ ] GitHub Issues _(public)_
  - [ ] GitHub Discussions _(public)_
  - [ ] GitHub Team Discussions _(consisting of the above described contributors)_
    - [ ] Public
    - [ ] Private
  - [ ] Mailing-list (groups.io)
  - [ ] FINOS Slack Channel (consisting of the above described contributors)
    - [ ] General (public) _(supply channel name)_ 
    - [ ] Leadership (private) _(supply channel name)_
- Synchronous
  - [ ] Recurring meetings

## Understanding FINOS Onboarding Requirements

As a project onboarding into FINOS, you will need to familiarize yourself and your contributor team with the following materials:

 - [FINOS overview](https://www.finos.org/hubfs/An%20Introduction%20to%20FINOS.pdf) (if necessary)
 - [FINOS Maintainers cheatsheet](https://community.finos.org/docs/finos-maintainers-cheatsheet/)
 - [FINOS Project/Standards Governance](https://community.finos.org/docs/governance)
 - [FINOS Project Lifecycle](https://community.finos.org/docs/governance/Software-Projects/project-lifecycle)

## Socialisation 
- [ ] Write and send contribution proposal announcement (optional - see below)
- [ ] Lead maintainer to send out announcement to community@finos.org using this template:
    
    ```
    Dear FINOS Community, 
    
    We would like to propose a new FINOS project. Please review the proposal details at (_TODO: add link to the GitHub issue proposal_).
    
    If you're interested in participating, please :+1: the GitHub issue proposal and drop a comment with your name, org and email

   Thanks a lot,
   ```     

# 2. Approval
- [ ] Assign issue to Executive Director (@mindthegab) to trigger voting. If additional socialization is required, the Executive Director may bring standards projects to the FINOS Governing Board
- [ ] FINOS Governing Board accepts the contribution/new standard project (and the contribution process can move forward)

# 3. Preparing For Onboarding

Before the FINOS team can onboard your project, there are a few housekeeping items that need to be taken care of.  These must be completed by the contributor, with help if required from the FINOS Infra.   

## Kick-off meeting
- [ ] Review the [project contribution agreement](https://community.finos.org/governance-docs/The.Linux.Foundation.--.Form.of.Trademark.Assignment.20221202.pdf) to allow FINOS to act on behalf of the contributor for accounts related to the project (e.g., GitHub, domain names, social media) and to optionally manage trademark assignment.
  - If the project name is new to FINOS and has not been used publicly by the contributor this agreement is not necessary.
  - If the name is not new and has been used publicly in the past the contribution agreement must be signed even if no trademarks have been filled due to Common Law Trademark Rights.
  - The above applies to any logos as well
- [ ] Review contribution checklist with FINOS staff
- [ ] Review FINOS project blueprint

# 4.  FINOS Onboarding

This is performed by FINOS Infra once the three previous stages are complete, with support from the contributor and the FINOS Infra team.

## Code transfer preparation
- [ ] Ensure [finos-admin](http://github.com/finos-admin) is Admin of the GitHub repository to transfer

## Code Transfer Meeting
- [ ] Transfer all code assets as GitHub repositories under github.com/finos
- [ ] Rename main branch to `main` (instead of `master`)
- [ ] Enable EasyCLA
- [ ] Check that CVE (and preferably static code analysis, if applicable) scanning is in place
- [ ] Enable [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) (`Require a pull request before merging`)
- [ ] Enable automated dependency update, using [Renovate](https://renovatebot.com/)
- [ ] (best effort) Update release coordinates and code namespace to include `finos`

# 5. Announcement 
- [ ] Lead maintainer works with FINOS marketing to send out announcement to announce@finos.org , checkout announcement template at the [Contribution page](https://community.finos.org/docs/governance/Software-Projects/contribution#step-5-contribution-announcements)
