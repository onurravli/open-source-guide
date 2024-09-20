# Open Source Software Development & Best Practices: A Guide

Open source projects have become a cornerstone of modern software development, enabling collaboration and innovation across the globe. Effective management and maintenance are crucial for the longevity and success of these projects. This guide provides best practices to help you navigate the complexities of managing an open source project.

## Table of Contents

1. [Maintaining Balance for Open Source Maintainers](#maintaining-balance-for-open-source-maintainers)

   - [Tips for Self-Care and Avoiding Burnout as a Maintainer](#tips-for-self-care-and-avoiding-burnout-as-a-maintainer)

2. [How to Contribute to Open Source](#how-to-contribute-to-open-source)

   - [Why Contribute to Open Source?](#why-contribute-to-open-source)
   - [What It Means to Contribute](#what-it-means-to-contribute)
   - [Orienting Yourself to a New Project](#orienting-yourself-to-a-new-project)
   - [Finding a Project to Contribute to](#finding-a-project-to-contribute-to)
   - [How to Submit a Contribution](#how-to-submit-a-contribution)
   - [What Happens After You Submit Your Contribution](#what-happens-after-you-submit-your-contribution)

3. [Starting an Open Source Project](#starting-an-open-source-project)

   - [The “What” and “Why” of Open Source](#the-what-and-why-of-open-source)
   - [Should I Launch My Own Open Source Project?](#should-i-launch-my-own-open-source-project)
   - [Launching Your Own Open Source Project](#launching-your-own-open-source-project)
   - [Naming and Branding Your Project](#naming-and-branding-your-project)
   - [Your Pre-Launch Checklist](#your-pre-launch-checklist)

4. [Finding Users for Your Project](#finding-users-for-your-project)

   - [Spreading the Word](#spreading-the-word)
   - [Figure Out Your Message](#figure-out-your-message)
   - [Help People Find and Follow Your Project](#help-people-find-and-follow-your-project)
   - [Go Where Your Project’s Audience Is (Online)](#go-where-your-projects-audience-is-online)
   - [Go Where Your Project’s Audience Is (Offline)](#go-where-your-projects-audience-is-offline)
   - [Build a Reputation](#build-a-reputation)

5. [Building Welcoming Communities](#building-welcoming-communities)

   - [Setting your project up for success](#setting-your-project-up-for-success)
   - [Growing your community](#growing-your-community)
   - [Resolving conflicts](#resolving-conflicts)

6. [Best Practices for Maintainers](#best-practices-for-maintainers)

   - [What does it mean to be a maintainer?](#what-does-it-mean-to-be-a-maintainer)
   - [Documenting your processes](#documenting-your-processes)
   - [Learning to say no](#learning-to-say-no)
   - [Leverage your community](#leverage-your-community)
   - [Bring in the robots](#bring-in-the-robots)
   - [It’s okay to hit pause](#its-okay-to-hit-pause)

7. [Leadership and Governance](#leadership-and-governance)

   - [Understanding governance for your growing project](#understanding-governance-for-your-growing-project)
   - [What are examples of formal roles used in open source projects?](#what-are-examples-of-formal-roles-used-in-open-source-projects)
   - [How do I formalize these leadership roles?](#how-do-i-formalize-these-leadership-roles)
   - [When should I give someone commit access?](#when-should-i-give-someone-commit-access)
   - [What are some of the common governance structures for open source projects?](#what-are-some-of-the-common-governance-structures-for-open-source-projects)
   - [Do I need governance docs when I launch my project?](#do-i-need-governance-docs-when-i-launch-my-project)
   - [What happens if corporate employees start submitting contributions?](#what-happens-if-corporate-employees-start-submitting-contributions)

8. [Getting Paid for Open Source Work](#getting-paid-for-open-source-work)

   - [Why some people seek financial support](#why-some-people-seek-financial-support)
   - [Funding your own time](#funding-your-own-time)
   - [Finding funding for your project](#finding-funding-for-your-project)
   - [Building a case for financial support](#building-a-case-for-financial-support)

9. [Your Code of Conduct](#your-code-of-conduct)
   - [Why do I need a code of conduct?](#why-do-i-need-a-code-of-conduct)
   - [Establishing a code of conduct](#establishing-a-code-of-conduct)
   - [Deciding how you’ll enforce your code of conduct](#deciding-how-youll-enforce-your-code-of-conduct)
   - [Enforcing your code of conduct](#enforcing-your-code-of-conduct)
   - [Your responsibilities as a maintainer](#your-responsibilities-as-a-maintainer)
10. [Open Source Metrics](#open-source-metrics)

    - [Why measure anything?](#why-measure-anything)
    - [Discovery](#discovery)
    - [Usage](#usage)
    - [Retention](#retention)
    - [Maintainer activity](#maintainer-activity)

11. [The Legal Side of Open Source](#the-legal-side-of-open-source)
    - [Understanding the legal implications of open source](#understanding-the-legal-implications-of-open-source)
    - [Why do people care so much about the legal side of open source?](#why-do-people-care-so-much-about-the-legal-side-of-open-source)
    - [Are public GitHub projects open source?](#are-public-github-projects-open-source)
    - [Just give me the TL;DR on what I need to protect my project.](#just-give-me-the-tldr-on-what-i-need-to-protect-my-project)
    - [Which open source license is appropriate for my project?](#which-open-source-license-is-appropriate-for-my-project)
    - [What if I want to change the license of my project?](#what-if-i-want-to-change-the-license-of-my-project)
    - [Does my project need an additional contributor agreement?](#does-my-project-need-an-additional-contributor-agreement)

## Maintaining Balance for Open Source Maintainers

### Tips for Self-Care and Avoiding Burnout as a Maintainer

#### 1. Identify Your Motivations

- Reflect on what aspects of open source work energize you (e.g., positive feedback, collaboration, or coding).
- Understanding your motivations can help you stay engaged and prioritize tasks effectively.

#### 2. Recognize Burnout Triggers

- **Lack of Feedback:** Users often stay silent unless they have complaints, which can feel discouraging.
- **Difficulty Saying No:** Taking on too many responsibilities can lead to feeling overwhelmed.
- **Working Alone:** Being a maintainer can be lonely, especially without in-person interaction.
- **Lack of Resources:** Volunteer maintainers may struggle with limited time or financial support.
- **Conflicting Demands:** Balancing employer expectations with community needs can create tension.

#### 3. Watch for Signs of Burnout

- Assess whether you can sustain your current pace long-term.
- Tools like the Burnout Checklist or wearable devices can help track stress and well-being.

#### 4. Sustain Yourself and Your Community

- **Lean on the Community:** Delegation and collaboration can reduce your workload. Engage with contributors and users for support.
- **Explore Funding:** Consider options like GitHub Sponsors or the GitHub Accelerator to support your open source work financially.
- **Use Tools:** Automate tasks with GitHub Copilot or GitHub Actions to save time for meaningful contributions.
- **Rest and Recharge:** Make time for hobbies, set clear boundaries for work, and take breaks to prevent burnout.

#### 5. Set Boundaries

- Learn to say no to requests that overextend you. Be clear about what you are willing to take on and communicate this in the project's README.
- Firmly address toxic behavior from contributors or users to protect your mental health.

#### Conclusion

Self-care and maintaining balance are essential for sustainable contributions to the open source community. By setting boundaries, understanding your motivations, and seeking support, you can avoid burnout and continue contributing effectively in the long term.

## How to Contribute to Open Source

### Why Contribute to Open Source?

Contributing to open source can be a rewarding way to learn, teach, and build experience in just about any skill you can imagine. Here are some key reasons why people contribute:

#### 1. Improve Software You Rely On

Many contributors start as users. If you find a bug or want to add a feature to software you use, contributing ensures that you and others can benefit from it in future releases.

#### 2. Improve Existing Skills

Whether it's coding, design, writing, or organizing, open source provides opportunities to practice and improve your skills in real-world projects.

#### 3. Meet People with Similar Interests

Open source communities often foster warm, welcoming environments. Many contributors form long-lasting friendships and connections through projects, conferences, and online interactions.

#### 4. Find Mentors and Teach Others

Collaborating on projects offers opportunities for both learning from others and teaching, which can be a deeply fulfilling experience.

#### 5. Build Public Artifacts and Reputation

Since all open source work is public, it serves as a portfolio that can help you grow your reputation and advance your career.

#### 6. Learn People Skills

Open source projects often involve leadership and management opportunities, such as conflict resolution, team organization, and prioritization of work.

#### 7. Empower Yourself by Making Changes

Even small contributions, like fixing a typo, can feel empowering. Open source gives people a sense of agency to improve the world around them, making even minor contributions gratifying.

### What It Means to Contribute

If you're new to open source, contributing might seem intimidating, but there are many ways to get involved, even if you don’t know how to code. Here are some tips for making meaningful contributions:

#### 1. You Don’t Have to Contribute Code

A common misconception is that contributions need to involve code. However, many other tasks are essential to a project’s success. Here are a few non-code contributions you can make:

#### 2. Event Planning

- Organize workshops or meetups, like @fzamperin did for NodeSchool.
- Help plan the project’s conference or help community members find speaking opportunities.

#### 3. Design Contributions

- Improve the project’s usability by restructuring layouts.
- Conduct user research to refine navigation.
- Create a style guide for consistent visual design or design t-shirts/logos, like contributors to hapi.js.

#### 4. Writing Contributions

- Improve or write documentation, as @CBID2 did for OpenSauced.
- Curate example folders or write tutorials and newsletters.
- Translate documentation, like @frontendwizard did for freeCodeCamp’s CSS Flexbox challenge.

#### 5. Organization

- Link duplicate issues, suggest labels, or organize open issues like @nzakas did for ESLint.
- Ask clarifying questions on open issues to keep discussions moving.

#### 6. Coding Contributions

- Tackle open issues or help write new features, as @dianjin did for Leaflet.
- Automate setup, improve tooling, or enhance testing for a project.

#### 7. Helping Others

- Answer questions on platforms like Stack Overflow, Reddit, or issue trackers.
- Moderate discussion channels or help newcomers understand the project.

#### 8. Helping with Code

- Review others’ code submissions, write tutorials, or mentor new contributors, like @ereichert did for @bronzdoc on Rust.

#### 9. Beyond Software Projects

Open source isn't limited to software. You can contribute to books, recipes, lists, and more. For example:

- @sindresorhus curates a list of “awesome” lists.
- @h5bp maintains potential interview questions for front-end developers.
- @stuartlynn and @nicole-a-tesla compiled fun facts about puffins.

Working on non-code contributions, like documentation, can be a great way to start in open source and build your confidence.
