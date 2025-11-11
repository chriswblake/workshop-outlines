<img width="52" alt="github logo" align="left" src="https://gist.github.com/user-attachments/assets/bbfa3bb8-c320-469d-b4c1-e87cca0b9053">

**GitHub Learn**  
Preparing for the Foundations Certification

---

## Let’s be practical for a moment….

#### Tips – from a data scientist that made that mistake already 😅

- Never store sensitive information in your repo. (passwords, tokens, keys, urls)
- Do NOT store data in your repo.
  - Instead, clone your repo to where your data is, not the other way.
  - Reference datasets in your README.
- Jupyter Notebooks store the results internally and dirty the change history. Be careful what you commit. There are dedicated extensions for comparing notebooks.
- Many Matlab scripts can be ran using the open-source project Octave. As such, they can also be automated with Actions without need of additional licenses.

#### Tips - from a coder that made that mistake already 😅

- Commits are for small logical chunks of a bigger goal.
  Branches are for (big) features.
- Branches are not folders. They are temporary copies for reaching a single goal.
- OneDrive doesn’t like repos. Don’t do it.
- Ignore GitHub Desktop. Use the integrated tools in your IDE.
- Create a README. Add at least 1 sentence describing the project and clarifying the acronyms in the repo name.

#### What would I do as a data scientist?

- I would put all my code in a GitHub repository.
  - Use very small data subsets for unit tests.
- Modify my data server to be a GitHub Actions runner.
- Automate analysis with the big data using an Actions Workflow.
  - Triggers on a pull request.
  - Code is sent to the server.
  - Full, potentially lengthy processes run the same analysis using larger, potentially real data sets. (max 6hrs)
  - Results are published to my pull request.
- Release to a staging environment using an Actions Workflow.
  - After pull request merges, code is packaged same style as a release.
  - Release candidate is deployed to first staging environment.
  - Candidate runs against copy of real data or data stream.
  - (Logging is same as production process now.)

## Frequent Questions

- Why should I care about GitHub Foundations? How will the certification help my career?
  - Data Science, like many skills today, isn’t a standalone skill. It must be applied to a particular area, like physics, finance, sports, politics, etc. Having more tools in your tool is always an enabler.
  - GitHub is a fundamental skill that will save you from technical debt and become a significant multiplier of your skills when mastered.
  - For your manager: It adds to the team’s skills well, enabling management to justify quotes on work proposals.
- Does the certificate stay with me or the company?
  - It is linked to your GitHub account, which is yours.
- Are there any discounts?
  - GitHub often offers discount codes to key partners and at special events. 🤩
- Can I take the test at home?
  - Most likely, yes. The test provider offers both online options and several in-person testing centers.
- Are Enterprise Managed Users (EMUs) supported?
  - We recommend taking the exam as an individual.
  - It is not supported for EMU accounts at this time.
