# CZI Open Source Training Materials

This repository contains the training materials for the CZI Imaging Tech team focused on good open-source citizenship.

- [CZI Open Source Training Materials](#czi-open-source-training-materials)
  - [Format and structure 🔖](#format-and-structure-)
  - [Learning personas 🙋🏽‍♀️](#learning-personas-️)
    - [Code contributor 💻](#code-contributor-)
    - [Code-adjacent contributor 🎨](#code-adjacent-contributor-)
    - [Manager/stakeholder 🤝](#managerstakeholder-)
  - [Course outline 🗺](#course-outline-)
  - [Contributing](#contributing)
    - [Pre-commit hooks 🧹](#pre-commit-hooks-)
  - [Code of Conduct](#code-of-conduct)
  - [License 📄](#license-)

## Format and structure 🔖

This repository contains several modules intended to drive knowledge and culture around open source at CZI.

- Each module covers specific topics and is intended to be self-contained.
- Each module is broken into chapters, which are prefixed by a number to reflect the order in which they should be read.
- Each chapter indicates the main personas at which the content is aimed (though this is not prescriptive,
  and all stakeholders involved in open source should be able to follow all the content in this repository).
- Files are written in Markdown format.
- This course is aimed at three major [learning personas](#learning-personas-️), learning paths relevant to each persona are indicated in the [learning personas](#learning-personas-️) section of this README.

---

## Learning personas 🙋🏽‍♀️

This training is created for three types of people (personas) who interact with open source projects:
code contributors, code-adjacent contributors, and managers who support the first two groups.

You can read the material chapter-wise for a thorough understanding. However, certain chapters are more relevant and valuable for particular personas, and this persona is indicated at the top of each chapter.

The following sections outline the role each persona plays in the open source project.

### Code contributor 💻

Community members who:

- report issues and create pull requests to improve or maintain the software codebase;
- propose plans to advance the software design and implementation;
- regularly participate in community discussions;
- contribute to upstream or downstream projects where relevant.

**Learning path:**

- [Module 01 - Introduction to open-source](./01-intro-to-os/README.md)
- Module 02 - [Participating in open source communities](02-participating-in-oss/README.md)
  - Chapter 2.1 - [Why contribute to open source](./02-participating-in-oss/01-why-contributing-to-oss.md)
  - Chapter 2.2 - [Understand open source sustainability and life cycle](./02-participating-in-oss/02-understand-oss-sustainability.md)
  - Chapter 2.3 - [Contributing to open source: tooling and best practices](./02-participating-in-oss/03-contibuting-tips.md)
  - Chapter 2.4 - [Being a good open source citizen as a corporate contributor](./02-participating-in-oss/04-good-corporate-oss-citizen.md)

### Code-adjacent contributor 🎨

Community members who:

- report issues and create pull requests to improve or maintain the software documentation, design, user and developer experience;
- propose plans to improve community collaboration, planning, and workflows;
- participate in community discussions;
- interact with upstream or downstream project communities.

**Learning path:**

- [Module 01-Introduction to open-source](./01-intro-to-os/README.md)
- Module 02 - [Participating in open source communities](02-participating-in-oss/README.md)
  - Chapter 2.1 - [Why contribute to open source](./02-participating-in-oss/01-why-contributing-to-oss.md)
  - Chapter 2.2 - [Understand open source sustainability and life cycle](./02-participating-in-oss/02-understand-oss-sustainability.md)
  - Chapter 2.3 - [Contributing to open source: tooling and best practices](./02-participating-in-oss/03-contibuting-tips.md)
  - Chapter 2.4 - [Being a good open source citizen as a corporate contributor](./02-participating-in-oss/04-good-corporate-oss-citizen.md)

### Manager/stakeholder 🤝

Community members who support teams of regular contributors, specifically:

- manage teams of Individual Contributors (ICs) or advise team members/managers;
- set goals for the team that align with team members' skill sets, the team's mission, and the broader project roadmap;
- track, record, and communicate progress on various tasks;
- participate in community discussions, primarily around project-level strategy and direction.

**Learning path:**

- [Module 01-Introduction to open-source](./01-intro-to-os/README.md)
- Module 02 - Participating in open source communities
  - Chapter 2.1 - [Why contribute to open source](./02-participating-in-oss/01-why-contributing-to-oss.md)
  - Chapter 2.2 - [Understand open source sustainability and life cycle](./02-participating-in-oss/02-understand-oss-sustainability.md)
  - Chapter 2.4 - [Being a good open source citizen as a corporate contributor](./02-participating-in-oss/04-good-corporate-oss-citizen.md)

## Course outline 🗺

- [Module 01 - Introduction to open-source](./01-intro-to-os/README.md): Provides a brief introduction to open-source, its ethos, and its benefits.
- [Module 02 - Participating in open source](./02-participating-in-oss/): This module explores different ways to engage with and participate in open source communities. It also provides some best practices for contributing to open source as an individual and a corporate stakeholder.

## Contributing

### Pre-commit hooks 🧹

This repository uses the `prettier` pre-commit hook to standardize our Markdown structure.
To install and run the pre-commit hooks, use these commands from the repository root:

```bash
# install the pre-commit hooks
pre-commit install

# run the pre-commit hooks
pre-commit run --all-files
```

Once installed, the hooks should run automatically on every commit.

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](https://github.com/chanzuckerberg/.github/blob/master/CODE_OF_CONDUCT.md?rgh-link-date=2023-06-28T16%3A31%3A48Z). By participating, you are expected to uphold this code. Please report unacceptable behavior to [opensource@chanzuckerberg.com](mailto:opensource@chanzuckerberg.com).

## License 📄

This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
