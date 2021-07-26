# Project Structure and Roles

## Project Structure

**Sub-projects**

The Telco Global API Project is organized primarily into sub-projects. Each sub-project is comprised of members from multiple companies and organizations, with a common purpose of advancing the project with respect to a specific Service API topic, for example ‘streaming’ or ‘localization’. Our goal is to enable distributed decision making and code ownership. This will be done by providing focused forums for getting work done, making decisions, and onboarding new contributors.

Areas covered by sub-projects may be vertically focused on particular Service API components or functions, cross-cutting/horizontal or spanning many/all functional areas of Service APIs. Some examples of each type are:

- Vertical: Quality on Demand, Localization, Identification
- Horizontal: Scalability, Architecture, Lifecycle, Service

Sub-projects are documented in the respective sub directory of the APIs directory.

Each sub-project must have a MAINTAINERS.md file. A sub-project should have at least one maintainer. Ideally a sub-project is managed by two or more maintainers, depending on the size and scope of the sub-project. Here, the responsibilities must be clearly agreed upon between all of the maintainers. This includes coordinating who is responsible for which issues and pull requests. Each maintainer should also be listed in the [Participants](./PARTICIPANTS.MD) file and in the contributors list of the [NOTICE](./NOTICE) file in the root directory.

Some sub-projects may have distinct (although sometimes overlapping) sets of contributors and maintainers, who act as the sub-project’s technical leaders, organizers and facilitators.

Where a sub-project has a release process, access and documentation should be such that more than one person can perform a release. Releases should be announced on the Telco Global API Project mailing list. Any new sub-projects should be first proposed on Telco Global API Project mailing list following the voting procedures listed in the project charter.

**Working Groups**

Community rallying points are used to facilitate discussions/work regarding topics that are short-lived or that span multiple sub-projects.

Working groups are primarily used to facilitate topics of discussion that are in scope for the Telco Global API Project but that cross sub-project lines. If a subset of community members wants to get together and discuss a topic, they can do so with forming a Working Group.

See “working group governance” _Tbd_ for more details about forming and disbanding Working Groups.

Working groups are documented in _Tbd_.

## Roles, Responsibilities and Requirements

**Team members**

Team member status may be given to those who have made ongoing contributions to the Telco Global API Project for at least 3 months. This is usually in the form of code submissions and improvements and/or notable work on documentation but may also include other contributions such as organizing events or user support.

The current team members are listed in PARTICITPANTS.MD.

Please note that Telco Global API had received significant contributions from a number of unlisted individuals before this governance document was written, and thus formal team membership was created.

**Maintainers**

Maintainers are first and foremost contributors that have shown they are committed to the long-term success of a sub-project. Contributors wanting to become maintainers are expected to be deeply involved in contributing code, pull request review, and triaging issues in the project for a minimum of three months and perform an ongoing contribution.

**Changes in Maintainership**

Changes in maintainership have to be announced on the Telco Global API Project mailing list. They are decided by [lazy consensus ](https://couchdb.apache.org/bylaws.html#lazy)and formalized by changing the MAINTAINERS.md file of the respective sub project.

A maintainer or committer may resign by notifying the team mailing list. A maintainer with no project activity for a year is considered to have resigned. Maintainers that wish to resign are encouraged to propose another team member to take over the project.

Requirements

The following requirements must be met by an individual wishing to become a maintainer for a sub-project: 

- Deep understanding of the technical goals and direction of the sub-project
- Deep understanding of the technical domain of the sub-project
- Sustained contributions to the design and direction of the sub-project, demonstrated by performing all of the following:
  - Authoring and reviewing proposals
  - Initiating, contributing and resolving discussions (emails, GitHub issues, meetings)
  - Identifying subtle or complex issues in designs and implementation PRs
- Direct contributions to the subproject through implementation and / or review

Responsibilities

Maintainers lead one or more sub-project(s) or parts thereof and serve as a point of conflict resolution amongst the contributors and are the technical authority for a subproject (responsible for vision and direction and overall design, choose/approve change proposal (KEP) approvers, field technical escalations, etc.). They *MUST* have demonstrated both good judgement and responsibility towards the health of that sub-project. Sub-project Maintainers *MUST* set technical direction and make or approve design decisions for their sub-project - either directly, or through delegation of these responsibilities.

Maintainers are also intended to be organizers and facilitators, responsible for the continued operation and progress of the sub-project and for communication and co-ordination with the other sub-projects, the Steering Committee, and the broader community. Maintainers are granted commit rights to their sub-projects.

Defined by: entry in sub-project MAINTAINERS.MD file. Maintainers of the overall project documentation are documented in [Code Owners](./CODEOWNERS).

Maintainers should actively participate in Pull Request reviews and are expected to respond to assigned Pull Requests in a *reasonable* time frame, either providing insights, or assign the Pull Requests to other maintainers.

The following responsibilities must be met by the maintainer for a sub-project:

- Make and approve technical design decisions for the sub-project.
- Set the technical direction and priorities for the sub-project.
- Define milestones and releases.
- Mentor and guide approvers, reviewers, and contributors to the sub-project.
- Ensure continued health of sub-project
  - Adequate test coverage to confidently release
  - Tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Ensure a healthy process for discussion and decision making is in place and is followed by the sub-project’s members.
- Work with other sub-project owners to maintain the project's overall health and success holistically.

Types of maintainers

There are different types of maintainers (Reviewers and Committers) with different responsibilities, but all maintainers have 3 things in common:

1. They share responsibility in the project's success.
1. They have made a long-term, recurring time investment to improve the project.
1. They spend that time doing whatever needs to be done, not necessarily what is the most interesting or fun.

Reviewers

- A reviewer is a maintainer within the project. They share in reviewing issues and pull requests and their LGTM counts towards the required LGTM count to merge a code change into the project.
- Reviewers are part of the organization but do not have write access. Becoming a reviewer is a core aspect in the journey to becoming a committer.

Committers

- A committer is a core maintainer who is responsible for the overall quality and stewardship of the project. They share the same reviewing responsibilities as reviewers but are also responsible for upholding the project bylaws as well as participating in project level votes.
- Committers are part of the organization with write access to all repositories. Committers are expected to remain actively involved in the project and participate in voting and discussing of proposed project level changes.

**Security Advisors**

- A security advisor is an advisory role in the project responsible for helping classify and advise on embargoed security disclosures. Security advisors are part of the organization without write access, but with read access to security disclosures and advisories before becoming public. Security advisors help maintain the integrity of the security review process and encourage responsible disclosure.
- Security advisors are individuals trusted by maintainers and representing significant users of the project. A reviewer may also be a security advisor, however, committers do not need this role as it is part of their regular duties. The security advisor duties are not part of the duties of being a reviewer. There is no expectation of advisors to become reviewers or participate in issue triage and code review.

## On- / Offboarding

The On- / Offboarding section is informational and can be changed by [lazy consensus ](https://couchdb.apache.org/bylaws.html#lazy)unless challenged. If no consensus can be reached, the matter may be resolved by majority vote.

**Onboarding**

The new member is

- added to the list of team members ([Participants](./PARTICIPANTS.MD)). Ideally by sending a PR of their own, at least approving said PR.
- announced on the Telco Global API Project mailing list by an existing team member. Ideally, the new member replies in this thread, acknowledging team membership.
- added to group accounts where applicable. Services with some variety of a group account include but are not restricted to Digital Ocean, DockerHub, GSuite, Netlify, Twitter (via Tweetdeck), Youtube.
- optionally added to the list of contributors.
- added to the team mailing list.

**Offboarding**

The ex-member is

- removed from the list of team members ([Participants](./PARTICIPANTS.MD)). Ideally by sending a PR of their own, at least approving said PR. In case of forced removal, no approval is needed.
- removed from the team mailing list , all lists of maintainers and the list of contributors.
- removed from group accounts where applicable. Services with some variety of a group account include but are not restricted to Digital Ocean, DockerHub, GSuite, Netlify, Twitter (via Tweetdeck), Youtube.
- not allowed to call themselves an active team member anymore, nor allowed to imply this to be the case.
- added to a list of previous members if they so choose.

If needed, we reserve the right to publicly announce removal.

## Stepping down policy

Life priorities, interests, and passions can change. If you're a maintainer but feel you must remove yourself from the list, inform other maintainers that you intend to step down, and if possible, help find someone to pick up your work. At the very least, ensure your work can be continued where you left off.

After you've informed other maintainers, create a pull request to remove yourself from the MAINTAINERS.MD file.

## FAQ

**How do I propose a decision?**

Send an email to the Telco Global API Project mailing list with your motion. If there is no objection within a reasonable amount of time, consider the decision made. If there are objections and no consensus can be found, a vote may be called by a team member.

**How do I become a team member?**

To become an official team member, you should intend to make ongoing contributions to one or more project(s) for at least three months. At that point, a team member (typically a maintainer of the project) may propose you for membership. The discussion about this will be held in private, and you will be informed privately when a decision has been made. A possible, but not required, graduation path is to become a maintainer later.

Should the decision be in favor, your new membership will also be announced on the Telco Global API Project mailing list.

**How do I add a sub project?**

As a team member, propose the new sub project on the Telco Global API Project mailing list. If nobody objects, create the sub project in the GitHub repository. Add at least a README.MD explaining the goal of the project, and a MAINTAINERS.MD with the maintainers of the project (at this point, this probably means you).

**How do I archive or remove a sub project?**

All sub projects should be kept and not removed.

**How do I remove an inactive maintainer?**

A maintainer may resign by notifying the team mailing list. A maintainer with no project activity for a year will be treated as if they had resigned. If there is an urgent need to replace a maintainer, discuss this on the team mailing list.

**How do I remove a team member?**

Team members may resign by notifying the team mailing list. If you think a team member should be removed against their will, propose this to the team mailing list. Discussions will be held there in private.