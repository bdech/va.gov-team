# Checklist for 10-10EZR Health Benefits Update form online
- This is a brand new product for the Health Apps team!

## List your team, project contributors, and reviewers
<details>

### Product Team
- OCTO-DE Product Lead: Patrick Bateman
- Product Manager: Alex Seelig, Heather Justice
- FE Engineer: Matt Long
- BE Engineer: Lihan Li, Chapley Watson
- QA Engineer: Fletcher Bonds
- Designer: Hieu Vo, David Kennedy
- Researcher: Hieu Vo
- Slack channel: #1010-health-apps
- GitHub tag: 1010-ezr

</details>

## List of project artifacts for requests

<details>

- Project epic [#57417](https://github.com/department-of-veterans-affairs/va.gov-team/issues/57417)
- [10-10EZR Product outline](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/application/va-application/EZ(R)%20Update%20Capabilities/10-10EZR%20Product%20Brief%20(standalone%20form).md)
- [Sketch Wireframes](https://www.sketch.com/s/da85cf44-4503-4e98-834e-ff068b242ef6/p/D391CBC5-D341-4B4B-B1D8-566325DDF8A4/canvas)
- [User flows](https://www.sketch.com/s/912cab8e-d234-44dd-be1f-2bedb3f50b22/v/Mrk8ab/p/A0C657F6-3318-45A0-93CB-246BA8722E37/canvas?posX=-3289.158203125&posY=-10403.73046875&zoom=0.25)
- [Initial Research plan](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/application/va-application/research/2023-06-Priority%20Group%20and%20Financial%20Disclosure/research-plan.md) 
- [Initial Conversation guide](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/application/va-application/research/2023-06-Priority%20Group%20and%20Financial%20Disclosure/conversation-guide.md)
- Secondary Usability Research Plan
- Secondary Usability Conversation Guide
- [North Star and KPIs for the product](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/health-care/application/va-application/EZ(R)%20Update%20Capabilities#measuring-success)
- Authenticated test-user logins, when applicable. **_Do not put staging credentials in your va.gov-team ticket; store or reference them in a .md file in the va.gov-team-sensitive repository_**
- Product URL(s)
     - TBD
- [Use cases](https://github.com/department-of-veterans-affairs/va.gov-team-sensitive/blob/master/Administrative/vagov-users/staging-test-accounts-1010EZR-Update-health-care-benefits.md)
- Finalized design, prototype or mockup
- [CAIA Ticket](https://github.com/department-of-veterans-affairs/va.gov-team/issues/64095)
- Content brief
- Regression test plans
- TestRail 
     - Test cases
     - Test plans
- Accessibility Testing ticket
- Technical diagrams (architecture diagram, sequence diagram)
- Any new publicly-exposed endpoints
- Any new interactions with dependent VA backends
- Release plan
- Product guide for contact center

</details>
     
## List of process steps

<details>

- [x] **Create Product Brief with the Problem Statement and as many details known**
- [x] Discovery
     - [x] What is the problem to be solved
     - [x] What solutions have been made (internal or external) to resolve this problem
     - [x] What are the possible solutions
     - [x] How would we solve the problem
     - [x] What are the efforts involved (time, design, technical)
     - [x] What is the ROI potential for each solution
     - [x] Does the solution require engagement with downstream system
          - [x] Is there a data change, and can the downstream system accept the data?
- [x] **Create Epic to identify the problem and solution**
- [ ] Optional - **Sign up for a Product Review session to present the initiative (~after Design Intent)**
- [x] Create corresponding stories to align with the work needed (start with this list!)
- [ ] Initial design
     - [x] Lo-Fi design ideas
     - [x] Presentation and agreement with the team on direction
          - [x] Confirm Frontend and Backend efforts
     - [ ] Presentation to Stakeholders and downstream system representatives - **9/13/2023**
- [x] **Submit Collaboration Cycle request ticket**
     - [x] **Review Collaboration Cycle site**
     - [x] **Start gathering artifacts (list above)**
     - [x] **Maintain this checklist of artifacts, updating as they are shared**
- [ ] **Schedule Design Intent review - 9/18/23 at 3:30p ET**
     - [ ] Present design and obtain feedback
- [x] **Request CAIA (Content, Accessibility & IA) review - Kickoff 9/12/23 at 4p ET**
- [ ] Finalize design with feedback
     - [ ] Present to team, stakeholders and any other interested parties
- [ ] Create prototype or basic working functionality in environments
     - [ ] The team can determine the best path, used for research
- [ ] Create Research Plan and Conversation Guide
- [ ] **Schedule Midpoint Review - Refer back to the initial Collaboration Cycle Request ticket**
- [ ] **Request Research Review - Refer back to the initial Collaboration Cycle Request ticket**
- [ ] Schedule research sessions with Perigean
- [ ] Conduct research sessions
     - [ ] Synthesize research findings
     - [ ] Review findings with the team
     - [ ] Make any necessary tickets/changes for design
- [ ] **Create Use Cases**
     - [ ] **Identify test users**
- [ ] **Create Release Plan**
- [ ] Complete development
     - [ ] Engineers work with Designers on any questions/clarifications
     - [ ] Present to team for validation
     - [ ] Present to Stakeholders for validation
- [ ] **Submit QA ticket and schedule with Tze (based on Dev ETA)**
- [ ] **Engage downstream system team for End-to-End QA coordination**
     - [ ] **Create E2E use cases and document results**
     - [ ] **Obtain signoff from downstream system team**
- [ ] **Request Analytics review - Refer back to the initial Collaboration Cycle Request ticket**
- [ ] Complete QA and Accessibility QA
     - [ ] Complete QA with feature toggle enabled and disabled to confirm toggle effectiveness (Reference [Testing process notes](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/application/va-application/10-10EZ%20Form/Testing%20with%20the%20Feature%20Toggle.md))
     - [ ] [Accessbility QA ticket template](https://github.com/department-of-veterans-affairs/va.gov-team/issues/new?assignees=briandeconinck&labels=a11y-testing&template=a11y-testing.yaml&title=Accessibility+Testing+for+%5BTeam+Name%2C+Product+Name%2C+Feature+Name%5D)
- [ ] **Request Staging Review - Refer back to the initial Collaboration Cycle Request ticket**
     - [ ] **Review findings with the team**
     - [ ] **Create tickets for work to be completed before launch**
- [ ] Create Usability and/or UAT research plan and conversation guide
- [ ] **Request Research Plan review**
- [ ] Schedule Usability/UAT sessions with Perigean
- [ ] Conduct Usability/UAT sessions
     - [ ] Synthesize research findings, if needed (not usually needed for UAT)
     - [ ] Review findings with the team
     - [ ] Make any necessary tickets/changes for design and/or development
- [ ] Complete any Design and/or Development work from Usability/UAT sessions
- [ ] Update Error matrix documentation with any new error states
- [ ] Update any FE and/or BE Engineering documentation
- [ ] **Request Privacy, Security, Infrastructure readiness review - Refer back to the initial Collaboration Cycle Request ticket**
- [ ] **Update Contact Center guide**
- [ ] **Submit Contact Center guide review ticket**
- [ ] **Update Release Plan**
     - [ ] **Include E2E test results & signoff**
- [ ] **Schedule or close all remaining tickets**
     - **Some tickets may be backlogged for future work, as they were not required to launch**
- [ ] **Review this checklist for any missing artifacts**
- [ ] **Review the [Product Development Checklist](https://depo-platform-documentation.scrollhelp.site/collaboration-cycle/product-development-checklist)**
- [ ] **Conduct Launch Go/No Go with the team**
     - [ ] **Review this checklist**
     - [ ] **Review Release Plan**
- [ ] **Launch in a phased manner, according to Release Plan**
- [ ] **Continuous check-ins with downstream system**
- [ ] Conduct Usability/UAT sessions
     - [ ] Synthesize research findings, if needed (not usually needed for UAT)
     - [ ] Review findings with the team
     - [ ] Make any necessary tickets for design and/or development
- [ ] **PM to sign up for an Impact review session to present the impact that the change has had on the product (~1 month after 100% launch)**


</details>
