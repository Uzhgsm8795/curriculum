---
summary: Understand why version control is necessary, and use GitHub to store code and collaborate with others.
topic: Tooling
icon:
---

# 9 Version control fundamentals (Git/GitHub)

Version control tools are an essential part of modern workflows, for backing up and collaborating on codebases. This module takes you through the essentials of version control using Git and GitHub.

Learning outcomes:

- Understand why version control systems are necessary

> **Notes:**
>
> - Git and associated social coding sites like GitHub have a lot of functionality, and can be intimidating and unfriendly to begin with. This set of conformance criteria does not expect mastery of all aspects of these tools, but rather an understanding of the basics, and why it is necessary to have some experience here before entering the industry.
> - Git is the web industry standard for version control, and has been for some time.

- Understand that sites such as GitHub, GitLab, etc. enable teamwork and collaboration that wasn't so easy in the past

- Understand the difference between Git, and websites like GitHub or GitLab

- Basic setup — installing git, signing up for an account for your chosen social coding site

  - Handling security requirements, like SSH/GPG keys

- Creating a repo

- Pushing changes — `add`, `commit`, `push`

- Contributing to others' repos

  - Forking

  - Creating a new branch

  - Creating a PR

  - Review flow

- Using GitHub pages to publish a sample project

- Good housekeeping

  - Regularly update local repos so that they are in sync with their remote counterparts. This includes pulling remote changes to your local repo, and installing package updates (e.g. with `npm install` or `yarn`). Always do this before you start working on a local repo

  - Use `.gitignore` to ignore all the stuff you don't want to commit, for example, dependencies, dev source files, and OS-level admin files like `.DS_Store`

  - Delete branches you've finished with

- Handling merge conflicts

Resources:

- [Git and GitHub](https://developer.mozilla.org/docs/Learn/Tools_and_testing/GitHub)
