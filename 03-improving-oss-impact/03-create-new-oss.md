| Learner personas | - [code contributor](../README.md#code-contributor-)<br> - [code-adjacent contributor](../README.md#code-adjacent-contributor-)<br> - [manager/stakeholder](../README.md#managerstakeholder-) |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pre-requisites   | - [Module 01: Introduction to Open Source](../01-intro-to-os/) <br>- [Module 02: Participating in Open Source](../02-participating-in-oss/)                                                   |

# Chapter 03: Create New OSS Project

- [Chapter 03: Create New OSS Project](#chapter-03-create-new-oss-project)
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
- Learn the key steps in starting, developing, and growing a new project sustainably.

## New OSS Project Motivations ⚡️

New tools that innovate on brand new solutions, address critical gaps in current tools, and provide competitive alternatives to existing libraries, help the open source ecosystem grow. As we’ll discuss in this section, there are many situations where contributing new open source projects is the best corporate open source partnership approach. At the same time, new projects can also be detrimental to the corporation and the community if not developed sustainably.

> **Note**
> The chapter focuses on corporate sponsors creating fresh OSS projects, but you can use it as a reference for transitioning internal software into an open source project.
> Moreover, most of the practices shared here can help you contribute new supporting, adjacent, or incubated projects to open source communities/organizations you’re already supporting.

Analyze the following prompts before creating a new OSS solution:

- **Is the project idea beneficial to a substantial community of users?** If created with org-specific assumptions or for proprietary integrations, the project will be open source in legality but not in spirit.
- **Is there an existing community OSS project that implements a similar solution?** You should always consider contributing improvements to existing projects before starting new ones to avoid duplicated effort. Note that sometimes existing projects have foundational limitations and massive technical debt, and in such cases it’s better to start a new project with better foundations.
- **What is your core [motivation](../02-participating-in-oss/01-why-contributing-to-oss.md/#organizational-funded-contributors) to develop this project under an open source license?** If the new open source project is created _solely_ for marketing purposes or with the intention to maintain corporate control over the project, it’s unlikely to gain serious community adoption in the long-term. If the project is useful the community at it’s core, adoption and community goodwill will follow, and you will have a better chance of success for creating potential corporate products or services around it.
- **Can you dedicate resources to build and maintain the project sustainably?** OSS projects require financial support and contributor expertise to see the project through various [stages of the life cycle](../02-participating-in-oss/02-understand-oss-sustainability.md/#oss-project-life-cycle-🌲), especially for long-term maintenance. For example, it’s not practical to expect support from the volunteer community without investing in community building first. Managing resources effectively from the beginning will help you plan for sustainability and protect against unintentionally creating abandonware.
- **Are you prepared to collaborate with the open source community?** New projects may not follow strict community-first practices during initial project development, but development may often involve upstream contributions and integrations with community projects—where you need to be good corporate OSS citizens. You can explore open source training for team members to equip them with the necessary OSS practices.

The following sections detail some important stages of developing a new open source and they assume you have identified the core value of your project, discussed corporate motivations, procured resource, and onboarded a team of initial contributors.

## Preliminary Considerations 🧱

- **Open Source Values:** Discuss and document some principles for your corporate open source partnership, like building for interoperability, [transparent communication](../02-participating-in-oss/03-good-corporate-oss-citizen.md/#tips-for-transparent-communication-💡), and more.
- **User Workflows:** As in any software development project, think about potential users, their workflows, their needs and pain points. Additionally, consider the open source alignment and expectation of individuals and corporate users of your project.
- **Project Roadmap:** Define a well-structured roadmap that balances both organization goals and open source community goals. Outline the project's milestones, features, and anticipated releases, and offer a direction for the project's evolution.
- **Preliminary Governance:** Discuss potential open source governance strategies, like including corporate stakeholders in project leadership, having a community-focused advisory board, targeting to join a community organization or federation in the future, and more, because it influences initial development practices.
- **Licenses and CLAs:** Select an appropriate [OSI-approved open source license](../01-intro-to-os/02-types-of-oss.md/#oss-licenses-🧑‍⚖️) to dictate how the project can be used and distributed based on organizational policy, open source values, and motivations [^2]. Corporations must also establish Contributor License Agreements (CLAs) to govern contributions, ensuring that all contributors grant the necessary permissions for their contributions to be included in the project.
  [^2]: Recently, there have been several instances of corporate-backed software licensed under Business Source License (BUSL) or custom licenses. While these licenses provide restricted access to the use, modification, and re-distribution, they are not **open source** by definition.
- **Stakeholder Review:** Garner input from key stakeholders, including the leadership, legal and compliance, software security, and marketing teams, to ensures the project aligns with the company's strategic vision and regulatory policies.
- **Project management:** Create initial project repositories, set up a documentation framework, and create concrete tasks corresponding to the roadmap milestones in your preferred project management tool.

## OSS Development and Maintenance 🏗️

- **OSS Development Practices:** Follow the [OSS development workflow](../02-participating-in-oss/04-contributing-tips.md/#the-oss-way-🌱) during all development stages to set the project up for a context-rich and collaborative environment that welcomes new contributors. Encourage code reviews, pull requests, and iterative development cycles that allow contributors to share ideas and insights.
- **Messaging and Brand:** Craft a consistent messaging strategy that highlights the project's unique value proposition, and design brand guidelines that reflect the project's identity. These can align with the organization’s overarching brand and messaging framework or stand independently.
- **Documentation:** Create comprehensive documentation for:

  - Users to quickly onboard to the project and understand it’s value, features, and necessary background.
  - Contributors to work on various enhancements, maintenance, sustainance activities.

  Regularly update and refine documentation to reflect latest changes and improvements.

- **Maintenance:** Dedicate resources to maintenance efforts like security updates, dependency upgrades, extensive test infrastructure, stable CI/CD workflows, triaging issue & PR backlogs, smooth release process, regular release cadence, and more.
- **Upstream Contributions:** Collaborate with upstream projects by contributing improvements and fixes that can benefit more projects in the ecosystem.

## Community Engagement 🌱

- **Code of Conduct (CoC):** Establish a robust CoC and enforcement strategy to ensure an inclusive, respectful, and welcoming community. You can adopt some community created CoC policies available in the ecosystem and create a small committee to handle reports[^3].
  [^3]: If possible, provide the CoC committee members with adequate training to handle reports effectively.
- **Governance:** Implement (and document) a governance structure with guidelines for decision-making and project leadership roles and responsibilities.
- **Communication Channels:** Set up spaces for community collaboration and aim to have separate channels for user support and contributor discussions, as well as regular community (video) meetings. Actively engage on community spaces, foster community interaction, and seek feedback to improve the spaces and workflows.
- **Advocacy:** Share your project with the broader ecosystem through various channels, including blog posts, social media, and relevant community events. Highlight the project’s value proposition and success stories to attract new users and contributors.
- **Partnerships:** Partner with related projects, organizations, or industry groups to increase the project's exposure and fosters cross-community collaboration.

## Exit Strategy 🏛️

<!-- TODO -->

## Resources 📚

- [Open Source Project Creation Overview, TODO Group](https://github.com/todogroup/ospo-career-path/blob/main/OSPO-101/module7/README.md)
- [A Guide to Outbound Open Source Software, TODO Group](https://todogroup.org/guides/outbound-oss/#how-to-contribute-to-oss-projects)
- [How to launch an open source project, Red Hat](https://www.redhat.com/en/resources/how-to-launch-an-open-source-project-overview)
- [Developing a strategy for your open source project, Red Hat](https://www.redhat.com/en/resources/developing-strategy-open-source-project)
- [Winding Down an Open Source Project, Linux Foundation](https://www.linuxfoundation.org/resources/open-source-guides/winding-down-an-open-source-project)

## Continue learning 🚥

<!-- TODO -->
