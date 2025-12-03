# Contributing to PostureGuard

First, thank you for considering contributing to PostureGuard. This project adheres to the highest standards of software engineering, and we welcome contributions that align with our core principles of precision, performance, and user-centric design.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

## 🚀 Core Philosophy

We operate on a "Zero-Defect, High-Velocity, Future-Proof" philosophy. All contributions should be:

- **Well-Architected:** Adhering to established design patterns like Feature-Sliced Design (FSD) and SOLID principles.
- **Rigorously Tested:** Covered by unit, integration, and end-to-end tests where applicable.
- **Cleanly Coded:** Formatted and linted using our strict Biome configuration.

##  Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS version)
- [Rust & Cargo](https://www.rust-lang.org/tools/install) (for Tauri)
- [pnpm](https://pnpm.io/installation) (recommended package manager)

## 🛠️ Development Setup

1.  **Fork the repository:**
    Click the "Fork" button at the top right of the [PostureGuard repository page](https://github.com/chirag127/PostureGuard-AI-Posture-Correction-Desktop-App).

2.  **Clone your fork:**
    bash
    git clone https://github.com/YOUR_USERNAME/PostureGuard-AI-Posture-Correction-Desktop-App.git
    cd PostureGuard-AI-Posture-Correction-Desktop-App
    

3.  **Install dependencies:**
    bash
    pnpm install
    

4.  **Run the development server:**
    This command will start the Vite frontend and the Tauri backend in development mode.
    bash
    pnpm tauri dev
    

## Linting and Formatting

We use [Biome](https://biomejs.dev/) for ultra-fast code formatting and linting. All code must pass Biome checks before a Pull Request can be merged.

- **Check for issues:**
  bash
  pnpm lint:check
  

- **Automatically fix issues:**
  bash
  pnpm lint:fix
  

## 提交 Commit Message Convention

We enforce the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification. This convention liaises with semantic versioning by describing the features, fixes, and breaking changes made in commit messages.

Your commit messages should be structured as follows:


<type>[optional scope]: <description>

[optional body]

[optional footer(s)]


**Example:**
`feat(auth): implement passwordless email login`
`fix(ui): correct button alignment on settings page`

## Pull Request (PR) Process

1.  Create a new branch from `main` with a descriptive name (e.g., `feat/new-camera-filter` or `fix/login-bug`).
    bash
    git checkout -b feat/your-new-feature
    
2.  Make your changes, adhering to the coding standards and architectural principles.
3.  Ensure all linting checks pass: `pnpm lint:check`.
4.  Commit your changes using the Conventional Commits format.
5.  Push your branch to your forked repository.
    bash
    git push origin feat/your-new-feature
    
6.  Open a Pull Request to the `main` branch of the [original repository](https://github.com/chirag127/PostureGuard-AI-Posture-Correction-Desktop-App).
7.  Fill out the PR template, linking any relevant issues (e.g., `Closes #123`).
8.  The PR will be reviewed, and once approved, it will be merged by a maintainer.

## Reporting Bugs and Suggesting Features

Please use the GitHub Issues tab to report bugs or suggest enhancements. Use our provided templates to ensure you include all necessary information:

-   [**Report a Bug**](https://github.com/chirag127/PostureGuard-AI-Posture-Correction-Desktop-App/issues/new?template=bug_report.md)
-   **Request a Feature** (Template will be available)

Thank you for making PostureGuard better!