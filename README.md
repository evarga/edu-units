[![pages-build-deployment](https://github.com/evarga/edu-units/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/evarga/edu-units/actions/workflows/pages/pages-build-deployment)
# Overview
This is an umbrella project for centralizing access to various self-contained educational units from different domains, like software engineering, parallel and distributed computing, computer science, etc. The key benefits from this approach are as follows:

- **Centralized Overview**: An umbrella project allows visitors to see all linked projects in one place, making it easier to navigate and understand the scope of each individual learning material.
- **Increased Visibility**: GitHub limits the number of pinned repositories to 6, so this approach allows for more projects to be highlighted.
- **Simplified Maintenance**: Updating information or adding new projects becomes more streamlined when managed through a single repository.
- **Community Contributions**: This project is open for contributions from the community. If you have a self-contained educational unit that you would like to share, please consider contributing it to this project. Read the [Contributors' Guide](https://github.com/evarga/edu-units/blob/main/CONTRIBUTING.md) for details.

- **Independent Evolution**: Subprojects may evolve independently of their container website. This is particularly useful when the subprojects are maintained by different authors or teams (in case people decide to contribute their unit(s) to this project).
- **Self-Referencing Property**: This project is itself an educational unit, showcasing how to organize and present subordinate educational materials in a structured manner. More specifically, technologies like Jekyll, GitHub Pages, and Markdown are used to create a website that lists all linked projects. The custom subdomain for this site was obtained via the [dnsimple](https://dnsimple.com/r/fefeb14211521c) service.

The GitHub Pages based website for this project contains a list of all the linked projects, along with a brief description and a link to the respective repository. The website is accessible by following the link displayed in the right sidebar of this repository.

## Learning Objectives
Since this site is also an educational unit, it has its own learning objectives. By exploring this site, you will learn how to:
- Craft a GitHub Pages based website using Jekyll, Markdown and Liquid.
- Customize the appearance of the site using a custom theme as well as how to further configure the selected theme via CSS, a layout definition and `_config.yml` file to define site-wide settings. The theme used in this project is [Architect](https://github.com/pages-themes/architect/).
- Produce a GitHub social media preview image for a project with [Microsoft Designer](https://designer.microsoft.com). It speeds up design work by allowing you to describe in natural language what you want to create, and then Designer generates an image based on your description. You can then customize the generated image to better fit your needs by changing colors, fonts, and other properties as well as accepting ideas from the Designer itself.

## What is an Educational Unit?
An _educational unit_ is a self-contained piece of educational material that can be used to learn a specific topic or skill. It can be a demo application, tutorial, a course, a workshop, a blog, a video series, etc. The key characteristics of an educational unit are as follows:
- It is managed as a full-fledged software product, with its own repository, documentation, and possibly a website. Quality expectations must be commensurate with a production level project.
- It is self-contained, meaning that it can be used independently of other educational units. It should have all the necessary resources to be used by learners. This includes source code, documentation, and any other necessary materials including external references that are required to understand the content.
- There are clear learning objectives stated in the inaugural section of the README file. These objectives should be specific, measurable, achievable, relevant, and time-bound (SMART). They should provide a clear understanding of what a learner will be able to do after completing the educational unit. This should be emphasized inside the closing section of the README file, where a learner is encouraged to reflect on what they have learned and how they can apply it in practice. Regarding scope, each educational unit should be covered in one instructor lead lecturing session, which is typically 45-90 minutes.
- The educational unit is designed to be self-paced, meaning that learners can go through the material at their own speed. This is particularly important for online learning, where a learner may not have direct access to a teacher or instructor. That being said, an educational unit is not like classical step-by-step tutorials, instead they require active engagement from a learner, who is expected to experiment with the provided material and reflect on the results.
- The concept of an educational unit allows authors to segregate stable theoretical content from volatile technology specific parts. This protects a book or course from becoming outdated too quickly. The educational unit can be updated independently of the rest of the material, ensuring that the content remains relevant and up to date.

The accompanying website contains a collection of educational units that complement each other with minimal overlap. Educational units may be used both by teachers and students, although the primary focus is on self-learning. The units are organized by domain, and each domain may contain multiple educational units.

# Usage
The UI is designed to be simple and intuitive. The main page contains a selection box with currently available domains (the _All Domains_ option is chosen by default). The rest of the home page lists all educational units filtered by domain. Each educational unit is represented as a clickable card that will open the respective repository in a new tab.

# Conclusion
You have witnessed the power of an umbrella project that centralizes access to various self-contained educational units from different domains. This approach allows for increased visibility, simplified maintenance, and community contributions. Exploring the content of the `docs` folder (this is the specified source for the GitHub Pages) you were able to fathom relevant details how the Jekyll, Liquid and GitHub Pages technology stack operates as well as how to customize the appearance of the site using a custom theme. You also learned how to produce a GitHub social media preview image for a project with Microsoft Designer.
