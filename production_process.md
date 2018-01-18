# Lexicata Production Process

### Table of Contents

* [Sprints](#sprints)
  - [Key Components of a Sprint](#key-components-of-a-sprint)
    - [Sprint Planning](#sprint-planning)
    - [Product Preview](#product-preview-upcoming-design-and-feature-scope)
    - [Product Planning](#product-planning-design-revisions-and-finalize-scope)
    - [Backlog Grooming](#backlog-grooming)
    - [Retro](#retro)
  - [Stories, Epics, and Projects](#stories-epics-and-projects)
    - [Story](#story)
    - [Epic](#epic)
    - [Project](#project)
* [Roles](#roles)
  - [Product Owner](#product-owner)
  - [Tech Lead](#tech-lead)
  - [Development Team](#development-team)
  - [Users](#users)

## Sprints

As defined by Scrum, "A Sprint, a time-box of one month or less during which a “Done”, useable, and potentially releasable product Increment is created. Sprints have consistent durations throughout a development effort."

At Lexicata our sprints will be 2 weeks in length, beginning on a Thursday and ending on a Wednesday.

### Key Components of a Sprint

Should also cover any larger upcoming features that may need fleshing out

Backlog Grooming	Before retro/release	Devs (maybe PO)	Go through every backlog ticket; make sure still accurate/relevant
Retro	last day of sprint	All stakeholders


#### Sprint Planning
**Who:** Dev Team and PO

**When:** First day of sprint (first Thursday); Expect this meeting to take 2-3 hours

**What:** Stories are written, estimated, and assigned. The PO determines the story priority. Though a large time commitment up-front, done correctly, will reduce or eliminate blockers later in the sprint allowing the team to complete work more efficiently.

**Desired Outcome:** By the end of sprint planning, every member of the development team should know which tasks they will be working on during the sprint and know all required details and business logic for each story.

#### Product Preview: Upcoming design and feature scope
**Who:** All Stakeholders

**When:** 5th day of sprint (first Wednesday); Meeting should not exceed 30-45 minutes

**What:** Designs and scope for the next sprint are reviewed. This is the chance for stakeholders to ask questions, view proposed design work, and identify any potential issues with the scope. This is not the first time the new feature is introduced to the dev team. Ideally that has taken place 3-5 weeks prior. See notes on Feature Meetings below.

**Desired Outcome:**  Attendees should leave this meeting knowing the clearly defined high-level scope for the feature(s) to be completed in the next sprint. This is the time to ask questions and present concerns. Individual tasks and stories are not part of this meeting.

#### Product Planning: Design revisions and finalize scope
**Who:** Dev Team, PO, and Designer

**When:** Last week of sprint (ideally second Tuesday or Wednesday); Meeting should not exceed 30-45 minutes

**What:** Designs and scope for the next sprint are confirmed. This is a follow up to the Product Preview meeting the week before. Changes to design from the previous week are generally expected to be minor.

**Desired Outcome:**  Attendees should leave this meeting knowing the clearly defined detailed scope for the feature(s) to be completed in the next sprint. Developers and the PO should be able to begin Sprint Planning the next morning following this meeting.

#### Backlog Grooming
**Who:** Dev Team

**When:** Last week of sprint (ideally second Monday or Tuesday); Expect this meeting to take up to 1 hour

**What:** Developers review every backlogged issue for relevance and accuracy as changes from the current sprint may affect backlogged issues.

**Desired Outcome:** A well groomed backlog is easier to maintain in the log run rather than letting issues sit stale for long periods of time. The purpose of this meeting is good housekeeping. A clean projet board is a happy project board.

#### Retro
**Who:** All Stakeholders

**When:** Last day of sprint (last Wednesday); Expect this meeting to take about 30-60 minutes

**What:** All stakeholder convene to discuss the recently completed sprint. This can have several different formats. Generally, the following questions are discussed:
* What went well?
* What did not go well?
* What are actionable things that we can change for next sprint?

**Desired Outcome:** Make changes to the next sprint cycle based on the team's restrospective discussion.

### Stories, Epics, and Projects

#### Story

A story defines a single user path in which the user, business value, action, and outcome of the path are defined.

All stories should contain an estimate agreed upon by the development team. Since team members have varying skill levels and areas of expertise, the estimate should be based on an average and not increased or decreased to match the speed of any one member on the team.

Estimates are generally done using a point system which should be decided upon by the development team. Let's assume a 3 point scale.

* 1 point: This is a story that could be completed by the average team member in about a half a day to a day (or 3-6 hours)

* 2 points: This is a story that could be completed by the average team member in 1-1.5 days (or 8-12 hours). Usually these stories can (and should!) be broken down further in to multiple 1 point stories.

* 3 points: This a story that needs more information to be fully understood and broken out in to do-able tasks. A 3 point story should always be broken down in to smaller stories before work begins.  


##### How to write a story

As a(n) [user type] </br>
In order to [extract business value] <--- Optional but valuable </br>
When I [take some action]</br>
(and [take some other action]) <--- Actions/steps necessary to get value</br>
Then I [observe an outcome]</br>
(and I [observe another outcome]) <--- Achieving business value (as a result of input)

_If there are more than two 'ands' for the 'when' clauses, the story is probably too big._

#### Epic
Epics are broader themes of functionality under which like stories can be categorized.

For example, all stories having to do importing contacts might all go under the Epic for Contact Importing.

#### Project
Optionally, the team can further segment features by project. Projects could be defined by project team, if there is more than one project team within the development team as a whole.

A project could also be defined as such based on breadth of scope such that it requires its own repository, for example.

## Roles

#### Product Owner
* Define business requirements of project (what it should/shouldn't do)
* Approve completed work (does this fulfill expectations based on defined criteria)
* Provide info needed to write stories
* Setting story priority

#### Tech Lead
* Advise overall technical approach
* Ensure code is well-built, follows defined convention for the team, and is documented appropriately
* Ensure technical workflow is followed as defined by team (commits, PRs, Jira, documentation, etc)
* Connect team to technical resources
* Determine "what is our platform as an organization?"

#### Development Team
* Turn business requirements into stories
* Estimate stories
* Complete tasks in order of PO's priorities
* Implement features as defined by stories
* Follow workflow as defined by team

#### Users
* Use software
* Provide feedback
