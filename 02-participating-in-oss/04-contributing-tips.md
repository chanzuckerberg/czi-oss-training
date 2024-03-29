| Learner personas | - [code contributor](../README.md#code-contributor-)<br> - [code-adjacent contributor](../README.md#code-adjacent-contributor-)                                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Pre-requisites   | - [Module 01: Introduction to Open Source](../01-intro-to-os/) <br>- [Chapter 2.1: Why and how to contribute to Open Source](./01-why-contributing-to-oss.md) <br>- [Chapter 2.2: Understand Open Source Sustainability and Life Cycle](./02-understand-oss-sustainability.md) |

# Chapter 04: Contributing to open source

## Table of Contents 🗂️

- [Chapter 04: Contributing to open source](#chapter-04-contributing-to-open-source)
  - [Table of Contents 🗂️](#table-of-contents-️)
  - [Learning Objectives 🧠](#learning-objectives-)
  - [Contribution tips and best practices 🔖](#contribution-tips-and-best-practices-)
    - [How contributions work 🎁](#how-contributions-work-)
    - [Contributions beyond code ✨](#contributions-beyond-code-)
    - [Getting the most of the issue trackers 🎟](#getting-the-most-of-the-issue-trackers-)
  - [Development and maintenance considerations 💻](#development-and-maintenance-considerations-)
    - [The OSS Way 🌱](#the-oss-way-)
    - [Designing in the open 🤔](#designing-in-the-open-)
  - [Working with large distributed teams 🌎](#working-with-large-distributed-teams-)
    - [So, how do you engage and work with an OSS community? 🤝](#so-how-do-you-engage-and-work-with-an-oss-community-)
  - [Tools 🛠](#tools-)
    - [Community](#community)
    - [Licensing and compliance](#licensing-and-compliance)
    - [Project management and metrics](#project-management-and-metrics)
  - [Continue learning 🚥](#continue-learning-)

## Learning Objectives 🧠

- Learn more about how to best approach open source contributions
- Learn about valuable tools and practices for open source contributions and engagement

## Contribution tips and best practices 🔖

### How contributions work 🎁

For any open source project, one of the most challenging tasks for a new contributor is identifying ways to get involved by making online contributions to propose appropriate changes. Contribution processes vary depending on the open source project, its governance model, and the type of contribution you want to make. For example:

- Projects have different guidelines covering coding style, documentation style, testing, release, versioning, Pull/Merge Requests, issues, triaging, and more.
- Some projects require all contributors to sign contributor license agreements (CLAs), while others have signed-off-by or other processes.
- Some projects have a defined team of core developers or maintainers. In contrast, others follow a federated model or are organized via Working Groups/Special Interest Groups responsible for different project areas.

These are only a few ways that the contribution style might differ, so it is paramount that you familiarize yourself with the project's contribution guidelines and processes before you start contributing.

> **Note**
> We will cover community guidelines in more detail in the next chapter.

In general, an open source project allows any individual to make contributions in the form of [issues](https://help.github.com/en/github/managing-your-work-on-github/about-issues) or [Pull Requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) (called Merge Requests in GitLab). Community members can also perform [reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews) and provide feedback or suggestions through [comments](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request) on the ideas and changes which they or others have suggested. This exchange of ideas leads to a better quality of resources that are developed collaboratively and bring new perspectives regarding a particular feature.

The diagram below shows a typical workflow for code contributions to an open source project. While many projects follow this workflow, others might have additional steps or different ways of handling contributions.

<img src="./images/oss-contribution-flow.svg" alt="Contribution workflow -> Start -> identify if there is an issue or create one -> assign issue -> make and push changes -> open PR and wait for review -> address feedback cycles -> ending contribution in merge or reject and close" width="500px">

> **Note**
> As you can see, the outcome of a contribution could be getting your contribution merged or rejected.

It is important to remember that the outcome of a contribution is not a reflection of your skills or abilities. It reflects the project's needs and priorities at that time. There are loads of factors that need to be considered by a sustainer when reviewing and approving contributions: maintainability, security, performance, scalability, upstream and downstream compatibility, and more.

### Contributions beyond code ✨

Not all contributions to an open source project will be made in the form of code.
Open source projects also need contributions in documentation, design, marketing, community management, fundraising, legal counsel, accessibility auditing and remediation work, translation and localization, and more. These contributions are as significant as code contributions and are often called code-adjacent contributions.

While some of these contributions _might_ follow a similar workflow to code contributions, others might not. For example, a contribution to the documentation of a project might follow the Pull Request workflow described above. However, community-related contributions such as organizing community meetings or mentoring new contributors follow different processes.

As discussed in [Chapter 02](./02-understand-oss-sustainability.md), project sustainability requires collective actions across multiple areas; thus, including and acknowledging all types of contributions is paramount for the success of an open source project. This starts with creating no-code/code-adjacent contribution pathways to adopt mechanisms to make these contributions visible and valued.

> **Tip**
> GitHub only makes certain types of contributions visible, while many other vital contributions are obscured or not accounted for.
> You can consider adding the [all contributors bot][all-contributors] to your projects to ensure everyone gets credit for their contributions.

👉🏽 The Turing Way has a [dedicated section on their contribution guidelines for recognizing contributions using the "all contributors" bot][turing-contributions].

### Getting the most of the issue trackers 🎟

An issue tracker (often called a bug tracker, issues list or issues queue) have multiple purposes:

- It is a place to report bugs and request new features.
- A place to monitor pending tasks and allow for collaborative discussions and peer reviews.
- A place to track the progress of a project and its milestones.

As you can see, issue trackers are fundamental tools for OSS development and maintenance, and they are often the first point of contact for new contributors.
Here are a number of actionable tips for meaningful OSS participation via issue trackers:

1. Scan the issue tracker for existing issues and pull requests before opening a new one. If there is already an open issue, supplement this with your findings (more details below).
2. If there is not an issue, aim to provide enough information for the triagers or maintainers to triage and assess your issue. Make sure to cover: **what** (the issue or requested feature, the behavior you are observing vs. the expected behavior), **why** (the impact), and **how** (add reproduction steps or a hint to a solution if you already know it).
3. Give your issue a meaningful title.
4. If the project has issue templates, **use them**. This will make it easier for maintainers to triage your issue and can substantially reduce the back-and-forth search for information on both parties. If you do not have the information requested or cannot determine how to get it yourself, note what you have attempted to do in order to get the information.
5. Be kind and thoughtful. At the end of the day, OSS is, but people all the way down[^1]; take a minute to thank the maintainers for their work and be patient with them. They are often volunteers and have limited time to dedicate to the project. If they request more information (i.e., logs, OS system and dependencies versions, etc.), try to provide them.
6. You can also contribute by giving feedback or adding more information to existing issues through:
   1. Documenting issues that are missing elements to reproduce the problem, such as code samples.
   2. Suggest reformulating the title and description to make them more explicit about the problem to be solved.
   3. Linking to related issues or discussions while briefly describing how they are related, for instance, "See also `#xyz` for a similar attempt at this" or "See also `#xyz` where the same thing happened in another platform." These additions provide additional context and help the discussion.
   4. Summarizing long discussions on issues to help new and existing contributors quickly understand the background, current status, and course of action for the issue. [^2]

[^1]: You might find Virginia Shea's often-cited [The Core Rules of Netiquette](http://www.albion.com/netiquette/corerules.html) to be a useful resource if you are unfamiliar with the rules of engagement in internet communications.
[^2]: Taken from nebari contribution guidelines <https://www.nebari.dev/docs/community/file-issues>

## Development and maintenance considerations 💻

Let's start by revising a popular product-focused software development lifecycle: the Agile lifecycle.

![Agile software development lifecycle covering requirements gathering -> design -> implementation -> Test/QA -> Deployment -> User acceptance testing -> Delivery -> Feedback](./images/agile-swe.png)

The Agile methodology has gained tremendous popularity, enabling development teams to iterate on and ship new products and features efficiently and with consistent throughput.
However, these practices are best suited for "traditional tech corporate" (including startups and some not-for-profit) due to the following assumptions/processes involved:

- Assumes a dedicated team of developers, designers, and project/product management (and other roles) is working on the project.
- There is often a clear distinction between the development team and the product's end-users.
- There is a project manager, and often a project owner, responsible for determining the scope of work, prioritizing tasks, and ensuring the team meets its deadlines.
- Product goals are often tied to business goals and are measured by revenue, user growth, ROI, and more metrics.
- Depending on the licensing and revenue generation model, the organization might also be responsible for providing support to end-users and have an SLA (Service License Agreement).
- Even if using open source tools or software to build the ultimate product, the product itself may or might not be open source. Thus, the ultimate decision-maker is the product owner; no consent or consensus is sought.
- Due to the time and delivery expectations, this isn't easy to implement with a fully geographically-distributed team that communicates asynchronously.

### The OSS Way 🌱

In contrast, open source projects are often developed and maintained by a community of volunteers and/or paid contributors. There is an overlap between community members and end-users[^3] of the project, and both are involved in the development and maintenance of the project. The community members are also responsible for the project's governance and decision-making processes.

[^3]: Depending on how a project defines the boundaries of their community - and community members - users might be included in such definition of community or counted as a group of individuals interacting with the project from a more transactional or utilitarian perspective. Both are valid perspectives. However, such definitions will impact how the project is developed and maintained.

In contrast to the Agile methodology, the OSS development cycle can be slower and centered around collaboration and co-ownership, as contributions can often lead to longer-term implications in terms of maintenance for the project and other projects that depend on it.

The development cycle is often driven by the community's needs and priorities, and the project's goals are often tied to the community's goals and values and roughly follow the steps in the schematic below.

<img src="./images/oss-development-workflow.svg">

While not exhaustive, here is a list of core characteristics and differentiators of OSS development (vs. other product methodologies such as Agile or [Waterfall](./images/waterfall-swe.svg)):

- The process is designed for geographically distributed teams and asynchronous communication.
- OSS maintenance and development is based on transparency, trust, collaboration, and co-ownership.
- Relies on distributed decision-making and consensus-seeking.
- Its decentralized and community-driven nature requires an extra focus on transparency.
- Contributions are peer-reviewed.
- End-users and community members equally provide feedback, raise bugs, and request features.
- The project's goals are tied to the community's goals and values.
- Operate through processes designed to be resilient to organizational change and allow for self-organization and self-management.
- While projects usually have a release cadence, deadlines are rarely set in stone, and a significant release might be delayed if there are blockers or the community needs more time to review and test the release. Equally, many releases do not include new features but are focused on bug fixes, documentation, and maintenance tasks (e.g., CI, dependencies updates, testing).
- The development model can scale (up and down) depending on community participation and maintainers' availability.
- Trust is built by past records of productive participation and wise decisions on smaller issues.
- A common mantra in OSS is "Release Early, Release Often" (refer to the schematic above).
  While this approach allows users and maintainers alike to benefit from new features and critical patches at a reasonable pace.

### Designing in the open 🤔

While discussing the OSS development cycle, it is essential to highlight the importance of designing in the open.

Some best practices for designing in the open include:

- Communicate early and often on the project's preferred communication platform.
- Anticipate feedback and proactively provide context and rationale for your design decisions.
- Acknowledge given feedback and re-work your contribution.
- Signal willingness to adapt your design if someone else is willing to collaborate with you.
- Plan for modularity, even if the first designs are not modular.

Following these best practices will help you build trust and get effective acceptance of your design decisions and ideas. Important things to consider when designing for acceptance are:

- Design your contribution to be as modular and straightforward to implement as possible.
  - Small, well-scoped contributions are easier to review and integrate.
  - Modular contributions are easier to maintain and update.
  - Iterative development practices promote extensibility.
- Scope and divide as needed.
  - If your contribution is too extensive (i.e., touches many parts of the codebase, implies a major refactor), consider breaking it into smaller, more manageable pieces. More extensive changes will likely be completed and accepted as smaller changes with concrete goals.
  - Communicate your plans and intentions before you start working on a contribution.

## Working with large distributed teams 🌎

From earlier content in this training, it is hopefully clear that the dynamics of OSS projects and communities are different from those of purely corporate or internal development teams.
We define community as:

> A group of people united by a common identity and collective purpose and who collaborate by sharing ideas, knowledge, and resources.

While the concept of community might be something we are all familiar with, it is essential to consider the following aspects of OSS communities:

1. No two communities are the same.
2. Communities do not belong to or work for a single entity (for example, they do not work for a single company).

### So, how do you engage and work with an OSS community? 🤝

Before jumping into contributing to or working with a community, you might want to consider the following:

1. **What can you offer?** Depending on your (individual, team, or organization) capacity, you might be able to contribute in different ways, for example, through sponsorship, in-kind contributions, or making direct contributions through your teams or individuals.
2. **Determine your time commitment.** How much time can you dedicate to the project? Is it a one-off contribution or a long-term commitment?
3. **How much do you know about the community?** Spend time researching how the community communicates (e.g., identify their platforms and lurk there a bit to get a sense of their communication standards). Also, try to understand the community's governance model and decision-making processes.

You can start engaging with the community once that initial research phase is completed. Here are some tips to get you started:

1. **Introduce yourself.** If you are new to the community, introduce yourself and your intentions. This will help the community understand your motivations and how you can contribute. Once you have identified what you can offer and how long for, communicate that to the community. Suppose you are aiming for long-term engagements with the project. In that case, it is best to liaise with their decision-makers and maintainers to understand how you can contribute and identify any pressing needs you might not be aware of. Significant pieces of work might need doing but might not be logged in a Roadmap or issue tracker due to a lack of capacity or knowledge.
1. **Communicate what you are working on.** Avoid working on something for the community "until it is perfect/completed/ready to showcase"; instead, signal your intent early on and align with the maintainers on the best ways to collaborate. This will avoid wasting time and effort on something that might not be aligned with the community's goals or needs.
1. **Give back.** Besides straightforward code contributions, consider other ways in which you can help ease the burden of sustainers or how you could strengthen the social infrastructure of the project.
1. **Plan an exit strategy.** Communities, as any ecosystem, are not static and are constantly evolving (the same applies to corporations, non-profits, and all types of organizations). This might mean that you might need to leave the community at some point. Aim to leave the community in better shape than when you joined it. Some actions you can take when exiting a community are:
   1. Identify a successor or a group of successors as early as possible.
   2. Inform the community in case there is anything they need to plan on their end. Communicate what your handover looks like and revisit expectations with your successor around communication and engagement with the community.
   3. Introduce this successor to the community and help them get up to speed.

## Tools 🛠

This section contains a list of helpful tools and projects that you might find helpful when contributing to open source projects.

### Community

- [All contributors bot][all-contributors]: enables you to track and acknowledge contributions beyond code.
- [Welcome bot](https://github.com/apps/welcome): a GitHub App that welcomes new users to your repository with a custom message.
- [MVG - Minimum Viable Governance](https://github.com/github/MVG): (beta) a repository-based approach for putting lightweight governance into free and open source projects that are run in version control systems.
- [GitHub Open Source Guide](https://opensource.guide/): a set of guides on establishing open source projects and managing communities.

### Licensing and compliance

- [CLA assistant](https://github.com/cla-assistant/cla-assistant): CLA assistant is a GitHub App that enables contributors to sign CLAs from within a Pull Request.
- [LicenseFinder](https://github.com/pivotal-legacy/LicenseFinder): find licenses for your project's dependencies.
- [OSS attribution builder](https://github.com/amzn/oss-attribution-builder): the OSS Attribution Builder is a website that helps teams create attribution documents (notices, "open source screens", credits, etc.) commonly found in software products.
- [OSS review toolkit](https://github.com/heremaps/oss-review-toolkit): enables highly automated and customizable Open Source compliance checks for the source code and dependencies of a project. It does so by scanning the project, downloading its sources, reporting any errors and violations against user-defined rules, and by creating third-party attribution documentation.
- [TLDR legal](https://www.tldrlegal.com/): summarizes software licenses in plain English.

### Project management and metrics

- [Issue/PR/Discussion Metrics](https://github.com/github/issue-metrics): a GitHub Action that searches for pull requests/issues/discussions in a repository or organization and measures several available metrics like time to close and time to first response. It calculates the metrics and writes the metrics to a Markdown file. The issues/pull requests/discussions can be filtered by using a search query.
- [GitHub Settings](https://github.com/probot/settings): uses a `.github/config.yml` as the source of truth, and any changes to that file in the default branch will update GitHub.
- [pre-commit](https://pre-commit.com/): a framework for managing and maintaining multi-language pre-commit hooks, enabling you to maintain a consistent code style across your project.
- [devstats](https://github.com/cncf/devstats): a tool set to visualize GitHub archives using Grafana dashboards used by the Cloud Native Computing Foundation and Kubernetes.

## Continue learning 🚥

⬅️ **[Previous Chapter: 03 Being a Good OS Citizen as a corporate sponsor](./03-good-corporate-oss-citizen.md)** | **[Module activity: OSS Journey](./OSS-journey-activity.md)** ➡️

<!-- Reusable links -->

[all-contributors]: https://allcontributors.org/docs/en/bot/overview
[turing-contributions]: https://github.com/alan-turing-institute/the-turing-way/blob/main/CONTRIBUTING.md#recognising-contributions
