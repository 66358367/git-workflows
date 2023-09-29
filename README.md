# Version Control with Git (JEM234) - Git-Workflows
By Martin Vondrášek, Marek Daňa, Vladyslav Ovcharenko
# Git Workflows


##📑 Table of Contents
- [Introduction](#introduction)
- [Branching Strategy](#branching-strategy)
- [Workflow Types](#workflow-types)
  - [Feature Branch Workflow](#feature-branch-workflow)
  - [Gitflow Workflow](#gitflow-workflow)
  - [GitHub Flow](#github-flow)
- [Best Practices](#best-practices)
- [Summary](#summary)
- [Tools and Resources](#tools-and-resources)

## Introduction
Git workflows define the processes and conventions one should follow when using Git for version control of project development. A well-defined workflow helps maintain code quality, collaboration, and project organization. This wiki-like project outlines common Git workflows and best practices for effective version control in projects.

## Branching Strategy
A branching strategy is the foundation of any Git workflow. It defines how branches are created, named, and merged. Our project follows the [choose one: centralized/decentralized] branching strategy. This strategy includes the following main branches:

- **Main**: The main branch, also known as `master` or `mainline`, represents the production-ready code.
- **Develop**: The develop branch serves as the integration branch for ongoing work.
- [Other Branches]: Describe any other important branches specific to your project.

## Common Git Workflows

### 1. Centralized Workflow
- **Description**: A single master branch for simple projects.
- **How it works**: Developers commit directly to the master branch.
- **Use cases**: Small teams, straightforward projects.

### 2. Feature Branch Workflow
- **Description**: Each feature gets a branch.
- **How it works**: Developers create feature branches and merge them.
- **Use cases**: Medium to large teams, complex features.

### 3. Gitflow Workflow
- **Description**: Defines a branching model.
- **How it works**: Uses master, develop, feature, release, and hotfix branches.
- **Use cases**: Projects with frequent releases.

### 4. Forking Workflow
- **Description**: Contributors fork the repository.
- **How it works**: Changes are proposed via pull requests.
- **Use cases**: Open-source projects.

### 5. Release-Based Workflow
- **Description**: Focused on versioning and releases.
- **How it works**: Development in feature branches, tagged releases.
- **Use cases**: Projects with strict version control.

### 6. GitOps Workflow
- **Description**: Infrastructure and app delivery through Git.
- **How it works**: Git manages infrastructure and application changes.
- **Use cases**: DevOps and infrastructure management.


## Best Practices
- Commit regularly with meaningful messages.
- Keep branches small and focused on specific tasks.
- Always pull the latest changes from the `develop` branch before starting new work.
- Use pull requests or merge requests for code review.
- Write clear documentation and update it as needed.
  
## Summary
Git workflows define the processes and conventions your team follows when using Git for version control. A well-defined workflow helps maintain code quality, collaboration, and project organization. Our project follows a [centralized/decentralized] branching strategy, with main branches like Main and Develop. We explore three common Git workflows: the Feature Branch Workflow, ideal for smaller teams; the Gitflow Workflow, suited for larger projects; and the GitHub Flow, designed for GitHub-based teams. We emphasize best practices such as regular commits, focused branches, and code review through pull requests. The document also provides links to valuable resources to support our team in achieving efficient version control and collaboration.

## Tools and Resources
- [Git Documentation](https://git-scm.com/doc): Official Git documentation for in-depth learning.
- [GitHub Guides](https://guides.github.com/): Guides and tutorials on using Git and GitHub.
- [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf): A handy reference for common Git commands.
- [Atlassian Git Workflow](https://www.atlassian.com/git): Learn about Git workflows and branching strategies.





