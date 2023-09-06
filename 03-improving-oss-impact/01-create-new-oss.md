| Learner personas | - [code contributor](../README.md#code-contributor-)<br> - [code-adjacent contributor](../README.md#code-adjacent-contributor-)<br> - [manager/stakeholder](../README.md#managerstakeholder-) |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pre-requisites   | - [Module 01: Introduction to Open Source](../01-intro-to-os/) <br>- [Module 02: Participating in Open Source](../02-participating-in-oss/)                                                   |

# Chapter 01: Creating a New OSS Project

- [Chapter 01: Creating a New OSS Project](#chapter-01-creating-a-new-oss-project)
  - [Learning Objectives 🧠](#learning-objectives-)
  - [New OSS Project Motivations ⚡️](#new-oss-project-motivations-️)
  - [Preliminary Considerations 🧱](#preliminary-considerations-)
  - [OSS Development and Maintenance 🏗️](#oss-development-and-maintenance-️)
  - [Community Engagement 🌱](#community-engagement-)
  - [Exit Strategy 🏛️](#exit-strategy-️)
  - [Resources 📚](#resources-)
  - [Continue learning 🚥](#continue-learning-)

## Learning Objectives 🧠

- Understand when corporate organizations should consider creating new open source over contributing to existing projects.
- Learn the critical steps in sustainably starting, developing, and growing a new project.

## New OSS Project Motivations ⚡️

New tools that innovate on new solutions address critical gaps in current tools and provide competitive alternatives to existing libraries, helping the open source ecosystem grow. As we'll discuss in this section, there are many situations where contributing new open source projects is the best corporate open source partnership approach. At the same time, new projects can also be detrimental to the corporation and the community if not developed sustainably.

> **Note**
> The chapter focuses on corporate sponsors creating new OSS projects, but you can use it as a reference for transitioning internal software into an open source project.
> Moreover, most practices shared here can help you contribute new supporting, adjacent, or incubated projects to open source communities/organizations you're already supporting.

Before creating a new OSS project around an idea, consider the following questions:

- **Is the project idea beneficial to a substantial community of users?** If created with org-specific assumptions or for proprietary integrations, the project will be open source in legality but not in spirit.
- **Is there an existing community OSS project implementing a similar solution?** You should always consider contributing improvements to existing projects before starting new ones to avoid duplicated efforts. Note that sometimes existing projects have foundational limitations and massive technical debt; in such cases, creating a new project with better foundations is better.
- **What is your core [motivation](../02-participating-in-oss/01-why-contributing-to-oss.md/#organizational-funded-contributors) to develop this project under an open source license?** If the new open source project is created _solely_ for marketing purposes or to maintain corporate control over the project, it's unlikely to gain serious community adoption in the long term. If the project is useful to the community at its core, adoption, and community goodwill will follow, and you will have a better chance of success in creating potential corporate products or services around it.
- **Can you dedicate resources to build and maintain the project sustainably?** OSS projects require financial support and contributor expertise to see the project through various [stages of their life cycle][oss-life-cycle], especially for long-term maintenance. For example, it's not practical to expect support from the volunteer community without investing in community building first. Managing resources effectively from the beginning will help you plan for sustainability and protect against unintentionally creating abandonware.
- **Are you prepared to collaborate with the open source community?** New projects may not follow strict community-first practices during initial project development. Still, development often involves upstream contributions and integrations with community projects—where you must be good corporate OSS citizens. You can explore open source contribution training for team members to equip them with the necessary knowledge, tools, and best practices.

The following sections detail some crucial stages of developing a new open source project, aligned with the [OSS Life Cycle introduced in Module 2][oss-life-cycle]. We'll assume you have identified the core value of your project, discussed corporate motivations, procured resources, and onboarded a team of initial contributors.

## Preliminary Considerations 🧱

Once you've decided to create a new OSS project, you can begin discussing the following details and aligning team members, organization stakeholders, and the open source community.

- **Open Source Values:** Discuss and document some principles for your corporate open source partnership, like building for interoperability, [transparent communication](../02-participating-in-oss/03-good-corporate-oss-citizen.md/#tips-for-transparent-communication-💡), and more.
- **User Workflows:** As in any software development project, consider potential users, their workflows, needs, and pain points. Additionally, consider the open source alignment and expectations of individuals and corporate users of your project.
- **Project Roadmap:** Define a well-structured roadmap that balances organization and open source community goals. Outline the project's milestones, features, and anticipated releases, and offer a direction for the project's evolution.
- **Preliminary Governance:** Discuss potential open source governance strategies, like including corporate stakeholders in project leadership, having a community-focused advisory board, targeting to join a community organization or federation in the future, and more, as all these considerations will influence the initial development practices.
- **Licenses and CLAs:** Select an appropriate [OSI-approved open source license](../01-intro-to-os/02-types-of-oss.md/#oss-licenses-🧑‍⚖️) to dictate how the project can be used and distributed based on organizational policy, open source values, and motivations [^1]. Corporations must also establish Contributor License Agreements (CLAs) to govern contributions, ensuring that all contributors grant the necessary permissions for their contributions to be included in the project.
  [^1]: Recently, several instances of corporate-backed software have been licensed under Business Source License (BUSL) or custom licenses. While these licenses provide restricted access to the use, modification, and re-distribution, they are not **open source** by definition. Wording and intentions matter, so it is essential to make this explicit when licensing a project under a non-open source license.
- **Stakeholder Review:** Garner input from critical stakeholders, including the leadership, legal and compliance, software security, and marketing teams, to ensure the project aligns with the company's strategic vision and regulatory policies.
- **Project management:** Create initial project repositories, set up a documentation framework, and create concrete tasks corresponding to the roadmap milestones in your preferred project management tool.

## OSS Development and Maintenance 🏗️

Project development and maintenance start right after the preliminary setup phase and continues for years till the eventual project wind-down. The following OSS development guidelines apply through most of your OSS life cycle and will take different forms as your project matures.

- **OSS Development Practices:** Follow the [OSS development workflow](../02-participating-in-oss/04-contributing-tips.md/#the-oss-way-🌱) during all development stages to set the project up for a context-rich and collaborative environment that welcomes new contributors. Encourage code reviews, pull requests, and iterative development cycles that allow contributors to share ideas and insights.
- **Documentation:** Create comprehensive documentation for:

  - Users to quickly onboard to the project and understand its value, features, and necessary background.
  - Contributors to work on various enhancements, maintenance, and sustenance activities.

  Regularly update and refine documentation to reflect the latest changes and improvements.

- **Maintenance:** Dedicate resources to maintenance efforts like security updates, dependency upgrades, extensive test infrastructure, stable CI/CD workflows, triaging issue & PR backlogs, smooth release process, regular release cadence, and more.
- **Upstream Contributions:** Collaborate with upstream projects by contributing improvements and fixes that can benefit more projects in the ecosystem.[^2]
  [^2]: The next chapter covers upstream contributions in detail.

## Community Engagement 🌱

Community is the beating heart of open source software. The following activities can prepare you to create and nurture a vibrant community of users, contributors, enthusiasts, advocates, collaborators, and more.

- **Code of Conduct (CoC):** Establish a robust CoC and enforcement strategy to ensure an inclusive, respectful, and welcoming community. You can adopt some community-created CoC policies in the ecosystem and create a small committee to handle reports[^3].
  [^3]: If possible, provide the CoC committee members with adequate training to handle reports effectively.
- **Governance:** Implement (and document) a governance structure with guidelines for decision-making and project leadership roles and responsibilities.
- **Messaging and Brand:** Craft a consistent messaging strategy that highlights the project's unique value proposition, and design brand guidelines that reflect the project's identity. These can align with the organization's overarching brand and messaging framework or stand independently.
- **Communication Channels:** Set up spaces for community collaboration and aim to have separate channels for user support, contributor discussions, and regular community (video) meetings. Actively engage in community spaces, foster community interaction, and seek feedback to improve the spaces and workflows.
- **Advocacy:** Share your project with the broader ecosystem through various channels, including blog posts, social media, and relevant community events. Highlight the project's value proposition and success stories to attract new users and contributors.
- **Partnerships:** Partner with related projects, organizations, or industry groups to increase the project's exposure and foster cross-community collaboration.

## Exit Strategy 🏛️

Finally, it would be best to gracefully reduce your contributions to the open source project. This is not a plan for failure but a path to building a project and community that can thrive independently and eventually make space for newer projects. The following points outline some elements of a non-disruptive exit to guide your planning and expectations.

- **Exit Conditions:** Determine when you will begin winding down. You can define some [project metrics](../03-improving-oss-impact/01-impactful-contribution-model.md#measuring-success) that indicate maturity and trigger the exit phase.
- **Communication:** You must share your desire to slow down with the project community and upstream & downstream collaborators and incorporate their input and feedback in your transition.
- **Knowledge sharing:** Work with the community to identify and fill any gaps in the project (and community) documentation.
- **Onboard leaders:** As initial authors, your team likely holds some leadership positions in the project, and you may need to find and mentor successors from the community to take on leadership roles. You can recognize past contributors by creating an "Emeritus" group in the project governance and support team members who wish to continue contributing as volunteers.

If the project shows signs of stagnation, or you need to reduce investment when the project is still young, you can work with the community to evaluate one of the following robust exit strategies:

- **Transfer:** You can transfer the project to a community organization, federation, or non-profit interested in and has the resources for continued development and maintenance. This process will also require communication and knowledge sharing mentioned previously, for a smooth transition.
- **Archive:** You can archive the project such that your community can still use released versions, inspect the repositories, or even revive the project. Again, give your community time to adapt by communicating your decision early.

> **Note**
> If absolutely necessary, due to company policies or other strict requirements, you can shut down the project and delete the project repositories, past releases, and web properties. It would help if you tried to archive first because the project resources are still valuable to the OSS community and can provide useful lessons for future projects.

## Resources 📚

- [Open Source Project Creation Overview, TODO Group](https://github.com/todogroup/ospo-career-path/blob/main/OSPO-101/module7/README.md)
- [A Guide to Outbound Open Source Software, TODO Group](https://todogroup.org/guides/outbound-oss/#how-to-contribute-to-oss-projects)
- [How to launch an open source project, Red Hat](https://www.redhat.com/en/resources/how-to-launch-an-open-source-project-overview)
- [Developing a strategy for your open source project, Red Hat](https://www.redhat.com/en/resources/developing-strategy-open-source-project)
- [Winding Down an Open Source Project, Linux Foundation](https://www.linuxfoundation.org/resources/open-source-guides/winding-down-an-open-source-project)

## Continue learning 🚥

**[Next Chapter: 02 Effective upstream and downstream collaboration](./02-effective-upstream-contributions.md)** ➡️

<!-- reusable links -->

[oss-life-cycle]: ../02-participating-in-oss/02-understand-oss-sustainability.md/#oss-project-life-cycle-🌲
