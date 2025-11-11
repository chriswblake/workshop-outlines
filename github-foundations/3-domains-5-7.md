<img width="52" alt="github logo" align="left" src="https://github.com/user-attachments/assets/edf42a56-6e3a-4399-8d90-a240e9839ae3" />

**GitHub Learn**  
Preparing for the Foundations Certification

---

**Event:** Part 3/3 - Intro to Task Management and Security  
**Date:** 14-Nov-2025  
**Duration:** 1.5hrs content + 30min QA  
**Hosts:**

- Christopher W. Blake - @chriswblake

### Vision/Goal

1. Learn to organize tasks across repositories.
2. Learn to protect your code with engineering controls.
3. Learn how Open Source projects function.

### Overview

#### Project Management

- Items - Organize issues from multiple repositories.
- Layouts - View the same data in different ways.
- Custom Fields - Track higher level information.
- Custom Views - Filter, sort, slice, group, etc.
- Workflows - Simple automations (add, open, close, etc.)
- Insights - Simple statistics charts

#### Privacy, Security, and Administration

- Features - Enable/disable collaboration tools.
- Visibility - Who can view content.
- Collaborators - People that can make changes.
   - Contributors - People that have already made changes.
- Protections
   - Rulesets - Enforce best practices (like testing and reviewing).
   - Codeowners - Who should automatically review PRs.
- Advanced Security
   - Dependencies - Stay informed about upstream risks.
   - Code Scanning - Identify vulnerabilities in code design.
   - Secret Scanning - Find and prevent passwords, tokens, etc.
- Organizations
   - Org - Group people, repositories, and projects.
   - Team - Group people with similar permissions or duties.

#### Benefits of the GitHub Community
   - Open Source
   - Inner Source
   - Sponsors

## Intro

1. **Welcome!** (5 min)

   1. Hello 👋

   2. Poll - Link: (insert link)
      I Don't know yet?

      - Option 1
      - Option 2

   3. Open list of learning domains: https://learn.github.com/certification/GHF

   4. Share Link to slack channel [#cs-foundations-certification-study-group](https://github-grid.enterprise.slack.com/archives/C09KT0FPL9X)

2. **Previous Session** (5min) - Quick review and important reminders.

   <!--
   Important topics to understand from the last
   session to follow along in this session.
   -->

   - Git - The key version control software.
   - Repository - All versions and history of your project, managed by Git.
   - Branch - A single version/copy of the project.
   - Pushing - Sending changes into another branch. Ex: From local to GitHub.
   - Pulling - Absorbing changes from another branch. Ex: From GitHub into local.

## Domain 5 - Project Management

1. **Projects**
   
   **Takeaway:** Projects provides visibility across several repositories (and other projects) without duplicating tasks.
   
   ### Demo

   1. Open a sample repository.
   2. Create an new issue (Issues tab).
   3. Create a new project.
   4. Add an existing issue.
   5. Add a new issue.
   6. Add a draft issue.
   7. Create/Modify new fields.
      - Iteration (Month)
      - Priority (Low, Medium, High)
      - Notes
   8. Adjust current view's fields (columns).
      - Labels
      - Milestones
      - Assigned to: @me
   9. Adjust filters
      - Group by `Iteration` and filter. Ex: `schedule:>=@current-1 schedule:<=@current+6`
      - Sort by Priority.
   10. Add another view
      - Layout: Roadmap
      - Start Date: Iteration
      - End Date: Iteration
   11. Extra (if time)
      - Workflow: titex
      - Insights: teted
   12. Mention
      - Projects Classic vs New Projects
      - Template Repositories
   13. Other

   ### Practice 🧑‍💻

   [![YouTube](https://img.shields.io/badge/YouTube-Issues%20and%20Projects%20in%20GitHub%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://youtu.be/fFrq28RY1SQ?t=217) (12 min)

2. **Issue Labels**

   **Takeaway:** Labels enable quickly grouping common issues and pull requests (and enable metrics).

   ### Demo

   1. Open a sample repository.
   2. Create an issue.
   3. Apply a label.
   4. Change available labels.

   ### Practice 🧑‍💻

   [![YouTube](https://img.shields.io/badge/YouTube-Adding%20and%20creating%20labels%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.YouTube.com/watch?v=KoFBpfSFmuY) (2 min)

   [![YouTube](https://img.shields.io/badge/YouTube-Issues%20label%20style%20guide%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.YouTube.com/watch?v=cjzGxDEFcu8) (2 min)


3. **Milestones**

   **Takeaway:** Group related issues and pull requests together to track progress toward a larger goal.

   ### Demo
   
   1. Open a sample repository.
   2. Navitage to Issues tab.
   3. Create a milestone.
   4. (Optional) Open the sample Project and show relationship.

   ### Practice 🧑‍💻

   [![YouTube](https://img.shields.io/badge/YouTube-How%20to%20Create%20a%20Milestone%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.YouTube.com/watch?v=3xFXFRuKUS0) (1 min)

4. **Saved Replies**

   **Takeaway:** Project maintainers and import contributors handle a lot of incoming issues and pull requests. Template responses make them faster.

   ### Demo

   1. Open user settings.
   2. Navigate to saved replies.
   3. Create a saved reply.
   4. Find an example issue.
   5. Show the "Saved Reply" picker.
   6. Show the keyboard shortcut.

   ### Practice 🧑‍💻

   [![YouTube](https://img.shields.io/badge/YouTube-GitHub%20Pull%20Requests%3A%20Saved%20Replies%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.YouTube.com/watch?v=W5RXVLrxo3Q) (6 min)

      
## Domain 6 - Privacy, Security, and Administration

1. **Authentication and Security**

   **Takeaway:** GitHub takes security seriously and provides most/all of the important 2FA options.

   ### Demo

   1. Open User Settings.
   2. Open Password and Authentication.
   3. Discuss Authenticator App.
   4. Discuss Security Keys.
   5. Discuss GitHub Mobile.
   5. Discuss SMS (less secure).

2. **Repo Settings**

   ### Demo

   1. Open Repository Settings tab.
   2. Disable/Enable Issues.
   3. Change visibility (public/private).
   4. Add a collaborator.

3. **Rulesets**

   **Takeaway:** Engineering controls can be used to require best practices.

   1. Add a Codeowners file.
   2. Enable a Ruleset 
      - Target: main
      - Require pull requests.
      - Require codeowners
   3. Create a pull request to demonstrate.

   ### Practice 🧑‍💻

   [![Skills Exercise](https://img.shields.io/badge/Skills-Intro%20to%20repository%20management%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills/introduction-to-repository-management)

4. **Security**

   **Takeaway:** Detect and manage vulnerabilities in your codebase and its dependencies.

   ### Demo

   1. Open the Security tab.
      - Mention free for public repos.
   2. View Dependabot results.
   3. View Code Scanning results.
   3. View Secret Scanning results.

   ### Practice 🧑‍💻

   [![Skills Exercise](https://img.shields.io/badge/Skills-Intro%20to%20repository%20management%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills/introduction-to-repository-management)

   [![Skills Exercise](https://img.shields.io/badge/Skills-Secure%20your%20repository%20supply%20chain%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/secure-repository-supply-chain)

   [![Skills Exercise](https://img.shields.io/badge/Skills-Intro%20to%20secret%20scanning%20chain%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/introduction-to-secret-scanning)

5. **Other** - Less common but still useful.

   ### Discussion

   - Repository Insights
   - Organization Settings
   - Organization Members and Teams

## Domain 7 - Benefits of the GitHub Community

1. **Open Source**

   **Takeaway:** Anyone can fork a visible project to their account, make changes to their copy, and then request the original to incorporate the changes.

   ### Demo

   1. Open a sample repository.
   2. Fork the repository to another account.
   3. Submit a pull request to the original repository.

   ### Resources

   [![Open Source Initiative](https://img.shields.io/badge/Resource-Open%20Source%20Initiative%20%E2%86%92-text?style=flat&logo=thestorygraph&labelColor=1f2328&color=f6f8fa)](https://opensource.org/osd)


2. **Inner Source**

   **Takeaway:** Same forking mechanic as Open Source, but with a lesser set of users (like 1 organization).

   ### Demo

   1. (optional) Repeat the steps for open source, but within an organization and with `internal` repos.

   ### Resources

   [![Inner Source Commons](https://img.shields.io/badge/Resource-Inner%20Source%20Commons%20%E2%86%92-text?style=flat&logo=thestorygraph&labelColor=1f2328&color=f6f8fa)](https://innersourcecommons.org)

3. **GitHub Sponsors**

   **Takeaway:** Many open source projects are passion projects or "just because". Sponsors is a way for the community to give back.

   ### Demo

   1. Navigate to github.com/sponsors.
   2. View your dependencies.
   3. Explore donation options.

   ### Practice 🧑‍💻

   [![YouTube](https://img.shields.io/badge/YouTube-What%20is%20GitHub%20Sponsors%3F%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.youtube.com/watch?v=EG45lEhSURY) (1 min)

   [![YouTube](https://img.shields.io/badge/YouTube-Earning%20on%20GitHub%3A%20Set%20up%20Sponsors%20%E2%86%92-text?style=flat&logo=youtube&labelColor=1f2328&color=f6f8fa&logoColor=FF0000)](https://www.youtube.com/watch?v=WUoFZKYDDCQ) (10 min)

## References

- Official Study Guide - https://learn.github.com/certification/GHF
- MS Learn Course - https://learn.microsoft.com/en-us/training/courses/gh-900t00
- Community Practice Questions - https://ghcertified.com/practice_tests/foundations/
- GitHub Learn, Skills Exercises - https://learn.github.com/skills
