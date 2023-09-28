# Version Control with Git (JEM234) - Git-Workflows
By Martin Vondrášek, Marek Daňa, Vladyslav Ovcharenko
# Git Workflows


📑 ## Table of Contents
- [Introduction](#introduction)
- [Branching Strategy](#branching-strategy)
- [Workflow Types](#workflow-types)
  - [Feature Branch Workflow](#feature-branch-workflow)
  - [Gitflow Workflow](#gitflow-workflow)
  - [GitHub Flow](#github-flow)
- [Best Practices](#best-practices)
- [Tools and Resources](#tools-and-resources)

## Introduction
Git workflows define the processes and conventions your team follows when using Git for version control. A well-defined workflow helps maintain code quality, collaboration, and project organization. This document outlines common Git workflows and best practices for effective version control in our project.

## Branching Strategy
A branching strategy is the foundation of any Git workflow. It defines how branches are created, named, and merged. Our project follows the [choose one: centralized/decentralized] branching strategy. This strategy includes the following main branches:

- **Main**: The main branch, also known as `master` or `mainline`, represents the production-ready code.
- **Develop**: The develop branch serves as the integration branch for ongoing work.
- [Other Branches]: Describe any other important branches specific to your project.

## Workflow Types
There are several Git workflows commonly used in software development. Choose the one that best fits your project's needs or create a custom workflow.

### Feature Branch Workflow
The feature branch workflow is simple and well-suited for smaller teams or projects. It involves creating a new branch for each feature or bug fix.

**Steps:**
1. Create a new branch for each feature or bug fix.
2. Develop and test the feature in the branch.
3. Merge the feature branch into the `develop` branch when complete.

### Gitflow Workflow
The Gitflow workflow is a more complex strategy suitable for larger teams and projects. It defines specific branches for features, releases, and hotfixes.

**Branches in Gitflow:**
- **Feature Branches**: For developing new features.
- **Release Branches**: For preparing releases.
- **Hotfix Branches**: For addressing critical issues in production.

### GitHub Flow
The GitHub Flow is a lightweight workflow designed for teams using GitHub. It simplifies collaboration by focusing on pull requests.

**Steps in GitHub Flow:**
1. Create a feature branch.
2. Commit changes and open a pull request.
3. Discuss and review the pull request.
4. Merge the pull request into the `main` branch.

## Best Practices
- Commit regularly with meaningful messages.
- Keep branches small and focused on specific tasks.
- Always pull the latest changes from the `develop` branch before starting new work.
- Use pull requests or merge requests for code review.
- Write clear documentation and update it as needed.

## Tools and Resources
- [Git Documentation](https://git-scm.com/doc): Official Git documentation for in-depth learning.
- [GitHub Guides](https://guides.github.com/): Guides and tutorials on using Git and GitHub.
- [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf): A handy reference for common Git commands.
- [Atlassian Git Workflow](https://www.atlassian.com/git): Learn about Git workflows and branching strategies.

=======

## Contributing
We welcome contributions from the community. In this section, you can explain how others can contribute to the project, such as by reporting issues or submitting pull requests.

## Summary

## Sources
Specify the project's licensing information. You can include the full license text or provide a brief summary.

