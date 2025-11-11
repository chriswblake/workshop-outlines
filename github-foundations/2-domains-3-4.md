<img width="52" alt="github logo" align="left" src="https://github.com/user-attachments/assets/edf42a56-6e3a-4399-8d90-a240e9839ae3" />

**GitHub Learn**  
Preparing for the GitHub Foundations Certification

---

**Event:** Part 2/3 - Intro to Collaboration and Automation  
**Date:** 7-Nov-2025  
**Duration:** 1.5hrs content + 30min QA  
**Hosts:**

- Christopher W. Blake - @chriswblake

### Vision/Goal

1. Learn to scale using async collaboration.
2. Learn to accelerate using automation and AI.

### Overview

Collaboration

- Issues - Track and assign your TODO items.
- Pull Requests - Collect feedback on your work before finishing it.
- Discussions - Community forums for your project.
- Gists - Snippets worthy of sharing, but not full projects.
- Wikis - Wikipedia but specific to your project.
- Pages - Host a website directly from a repository.

Modern Development

- Actions - Automate tasks when repository events happen.
- Copilot - Bootstrap most task with AI.
- Codespaces - Preconfigured cloud computer. Avoid "it works on my machine"

## (Optional) Prework

1. Review the topics in learning domains 3 and 4 from the [official guide](https://learn.github.com/certification/GHF).
2. MS Learn Module - [Using Pull Requests](https://learn.microsoft.com/en-us/training/modules/manage-changes-pull-requests-github/)
   - Includes: GitHub Skills Exercise - [Review Pull Requests](https://github.com/skills-dev/review-pull-requests)
3. MS Learn Module - [Introduction to GitHub Copilot](https://learn.microsoft.com/en-us/training/modules/introduction-to-github-copilot/)
   - Includes GitHub Skills Exercise: [Getting Started with GitHub Copilot](https://github.com/skills/getting-started-with-github-copilot)

## Intro (10min)

<img height="150px" align="right" src="https://octodex.github.com/images/octobiwan.jpg"/>

1. **Welcome!** (5 min)

   1. Hello 👋

   2. Poll
      
      Link: https://forms.gle/Jrh6cAs9kJALZMv28  
      How do you currently track your tasks?

      - Notepad 🗒️
      - Spreadsheets 🧐
      - Paper notebook 📓
      - GitHub Issues ☑️
      - Other 🦄 (describe in the chat)

   3. Open list of [learning domains](https://learn.github.com/certification/GHF).
   
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

## Domain 3 - Collaboration (45min)

<img height="150px" align="right" src="https://octodex.github.com/images/forktocat.jpg"/>

1. **Issues and Pull Requests** (20min) - A common development flow.

   **Takeaway:** Issues and PRs provide a transparent and traceable development process.
   This enables others to understand why decisions were made (and maybe contribute one day).

   ### Demo

   1. Open a sample repository.
   2. Explore open issues.
   3. Create an issue.
   4. Assign an issue.
   5. Create a branch.
   6. Start a PR and link with the issue.
   7. Request feedback using a review.
   8. Provide feedback using a review.
   9. Make changes.
   10. Merge

   > 💬 **Worthy Mention:** Upstream Repos (forking), Copilot Review, Coding Agent  
   
   ### Practice 🧑‍💻

   [![Static Badge](https://img.shields.io/badge/Skills-Review%20pull%20requests%20management%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/review-pull-requests)

2. **Discussions** (10min) - Self-enablement by the community for the community.

   **Takeaway**: A community forum provides space to fill support gaps and explore.
   (You are only 1 person.)

   ### Demo

   1. Navigate to Discussions tab.
   1. Start a new discussion.
   1. Show the dicussion types.
   1. Add a comment.

3. **Notifications** (5min) - Stay informed, and provide timely responses.

   **Takeaway:** The world runs on shared projects (Open Source).
   Staying informed will keep your project healthy, and collaborators happy.

   ### Demo

   1. Watch a repo.
   1. Watch a PR.
   1. Watch an issue.
   1. Open the home dashboard.

4. **Pages** (5min) - Host a website directly from your repo.

   ### Demo

   1. Open example site from Skills exercise.
   1. Show deployed version.
   1. Show repo files and make a change.
   1. Show Pages settings area.
   1. Show deployed change.

   ### Practice 🧑‍💻

   [![Static Badge](https://img.shields.io/badge/Skills-GitHub%20Pages%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/github-pages)


5. **Other** (5min) - Less common but still useful.

   - Gists - Snippets worthy of sharing, but not full projects.
   - Wikis - Wikipedia, but specific to your project.

## Domain 4 - Modern Development (30min)

<img height="150px" align="right" src="https://octodex.github.com/images/droctocat.png"/>

1. **Actions** (10min) - Automatically test, build, publish, etc. when events in your project happen.

   **Takeaway**: If you are repeatedly doing something, someone has probably automated it already.

   ### Demo

   1. Create a new public repository with README.
   2. Open Actions Marketplace. Find the "Greetings" action and add it.
   3. Briefly discuss the workflow anatomy. Specifically: Triggers and Steps.
   4. Create an issue. Switch to the Actions tab to show what is happening.

   ### Practice 🧑‍💻

   [![Static Badge](https://img.shields.io/badge/Skills-GitHub%20Actions%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/hello-github-actions)


2. **Codespaces** (10min) - Preconfigured cloud machine.

   **Takeaway**: A common machine configuration promotes speed, reliability,
   and avoids "it works on my machine".

   Demo

   1. Open a codespace. While that is preparing, also open the lightweight editor.
   2. Show changing and pushing a file in both.
   3. Generate the Devcontainer config file.
   4. Show there are options to change image, extensions, editor settings, etc.

   ### Practice 🧑‍💻

   [![Static Badge](https://img.shields.io/badge/Skills-Code%20with%20Codespaces%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills-dev/code-with-codespaces)


3. **Copilot** (10min) - A coding friend familiar with most things.

   **Takeaway:** Copilot can bootstrap most efforts, give you time to humanize and refine.

   ### Demo

   1. Ensure the codespace is still open.
   2. Demo inline suggestion.
   3. Demo Agent mode.

   > 🪧 **Worthy Mention**: Code Review, Coding Agent, Agent HQ, Tools (MCP)  

   ### Practice 🧑‍💻

   [![Static Badge](https://img.shields.io/badge/Skills-Getting%20started%20with%20GitHub%20Copilot%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa)](https://github.com/skills/getting-started-with-github-copilot)


## Wrap Up / Buffer (30min)

<img height="150px" align="right" src="https://octodex.github.com/images/Mardigrastocat.png"/>

1. **Preview: Next Session** (5min)

   - Domain 5 - Project Management
   - Domain 6 - Privacy, Security, Administration
   - Domain 7 - Benefits of the GitHub Community (aka Open Source)

2. **QA** (15min)

3. **Practice Together** (10min) - Let's see how we are doing.

   [![Static Badge](https://img.shields.io/badge/Verify-GH%20Certified%3A%20Foundations%20%E2%86%92-text?style=flat&logo=checkmarx&labelColor=1f2328&color=f6f8fa&logoColor=fff)](https://ghcertified.com/questions/foundations/)


4. (Optional) **Let’s Register! 🧑‍🚀**

   [![Static Badge](https://img.shields.io/badge/Learn-Register%20for%20Exam%20%E2%86%92-text?style=flat&logo=github&labelColor=1f2328&color=f6f8fa&logoColor=fff)](https://learn.github.com/certification/GHF)

   - Availability: In person or online. Almost daily options.
   - Length: 100 minutes. 75 multiple choice questions

## Not enough?! Want more? 🤓

<img height="150px" align="right" src="https://octodex.github.com/images/minertocat.png"/>

Here are some recommend topics you can research on your own. Learn more from the Open Source community!

- Personal Profile using Pages – Highlight your projects (and how awesome you are).
- GitHub CLI – Stay on the keyboard. Skip the web UI!
- GitHub Models - Easily compare responses from different AI models.

## References

- Official Study Guide - https://learn.github.com/certification/GHF
- MS Learn Course - https://learn.microsoft.com/en-us/training/courses/gh-900t00
- Community Practice Questions - https://ghcertified.com/practice_tests/foundations/
- GitHub Learn, Skills Exercises - https://learn.github.com/skills
