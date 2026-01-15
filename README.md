# rtom03 — Project Collection

[![Repo Size](https://img.shields.io/github/repo-size/rtom03/food_stack)](https://github.com/rtom03/food_stack)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)
[![Issues](https://img.shields.io/github/issues/rtom03/food_stack)](https://github.com/rtom03/food_stack/issues)

A curated collection of small projects and experiments maintained by rtom03. This repository aggregates multiple projects for learning, demos, and tooling practice.

Table of Contents
- About
- Projects
  - Astronomical Simulater
  - DSA (Data Structures & Algorithms)
  - Chrome Extension
- Features & Highlights
- Quickstart
- Contributing
- Advanced README features
- License

About
-----
This repo houses compact projects that showcase frontend, algorithmic, and browser-extension work. Each project is self-contained in its folder; the root README provides discoverability and quick links for maintainers and contributors.

Projects
--------
- Astronomical Simulater — ./astronomical-simulater
  - A simulation/demonstration of celestial mechanics and orbital motion. Intended as an educational visualizer built with web technologies.
- DSA — ./DSA
  - Collection of data structure and algorithm implementations, puzzles, and benchmarks (good for interview practice and algorithmic learning).
- Chrome Extension — ./chrome-extension
  - A browser extension prototype demonstrating a small useful feature (productivity/privacy/tooling). Uses the WebExtensions API.

Features & Highlights
---------------------
- Centralized README with badges and quick links to individual projects.
- Suggested CI & checks (see Contributing) to keep builds and lints green.
- Quickstart sections below for local development.

Quickstart
----------
General steps to get started locally for each project:

1. Clone the repo

   git clone https://github.com/rtom03/food_stack.git
   cd food_stack

2. Astronomical Simulater (if web app)

   - cd astronomical-simulater
   - npm install
   - npm run dev

3. DSA (node / scripts)

   - cd DSA
   - npm install (or use provided language-specific instructions)
   - run tests or specific scripts (e.g., npm test or python run_examples.py)

4. Chrome Extension

   - cd chrome-extension
   - follow README in that folder to load as an unpacked extension in Chrome/Edge (open chrome://extensions, enable Developer mode, Load unpacked)

Note: Each subproject should include its own README with detailed, project-specific setup instructions. If any are missing, open an issue or a PR to add them.

Contributing
------------
- Add issues or PRs for bugs, enhancements, or broken docs.
- Suggested GitHub Actions CI for each project: install, lint, build, and test matrix (node versions as needed).
- Enable Dependabot/renovate to keep dependencies updated automatically.
- Suggested pre-commit hooks: husky + lint-staged to run formatters and linters on staged files.

Advanced README features (suggested enhancements)
-------------------------------------------------
To make this README more beautiful and functional, consider adding:

- Project badges (build, test coverage, npm version) for each subproject.
- Auto-generated Table of Contents using a GitHub Action or markdown generator.
- Live demo GIFs or embedded CodeSandbox/Vercel links for the Astronomical Simulater.
- Architecture diagram or Mermaid flowcharts for complex logic (Mermaid is supported in GitHub Markdown):

  ```mermaid
  flowchart LR
    A[User] --> B[Chrome Extension]
    B --> C[Background Script]
    C --> D[API]
  ```

- Interactive examples or small notebooks (e.g., Jupyter, Observable) for algorithms or visualizations.
- A "Getting Help" section linking to issues, Discussions, or a small FAQ.

What I changed / Next steps
--------------------------
- Added a root README to centralize project information and link to subprojects.
- Next: add/verify READMEs inside each subproject (astronomical-simulater, DSA, chrome-extension). I can open PRs that add example READMEs inside each folder and create a GitHub Actions workflow to run lint/build steps—say if you want those, tell me which subproject to prioritize.

License
-------
This repository is provided under the MIT License unless otherwise specified in subproject folders.
