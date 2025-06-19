# Create Repository Tasks

A set of tasks to set up a new repository.

## Table of Contents

- [Create Repository Tasks](#create-repository-tasks)
  - [Table of Contents](#table-of-contents)
  - [Tasks](#tasks)
    - [General](#general)
    - [Language Specific](#language-specific)
    - [CI/CD](#cicd)

## Tasks

### General

- Add a `pull_request_template.md` to the `.github` directory.
- Add a `.editorconfig` file to the root of the repository.
- Add a `LICENSE` file to the root of the repository. If one wasn't created with the repository.
- Add a `README.md` file to the root of the repository.
  - Add project status badges to the `README.md` file.
- Set up a `CODE_OF_CONDUCT.md` file to the root of the repository.
- Set up a `CONTRIBUTING.md` file to the root of the repository.
- Set up a `SECURITY.md` file to the root of the repository.
  - Ensure that the `SECURITY.md` file links to the security tab of the repository.
- Set up issue templates for the repository.
- Set up generic Git Hooks for the repository.
- Set up task runners for the repository. Such as `just` and `make`.

### Language Specific

- Set up debug configurations for the language in the `.vscode` directory.
  - Set up a `launch.json` file in the `.vscode` directory.
- Configure unit tests for the language
  - Set up configuration in the `.vscode/settings.json` file.
- Set up Git Hooks for the language for linting and formatting.

### CI/CD

- Set up Code Quality Checks for the repository.
  - Set up SuperLinter for the repository.
  - Set up Language Specific formatting and linting CI/CD for the repository.
  - Set up Markdown link checker for the repository.
  - Set up task runner formatting for the repository. Such as `just` and `make`.
- Check pull request title if necessary.
- Sync labels for the repository.
- Apply labels to pull requests.
- Set up Dependency Updates for the repository using Dependabot.
- Set up CodeQL analysis for the repository.
- Set up dependency review for the repository.
- Set up unit testing in a CI/CD pipeline for the repository.
- Set up SonarCloud analysis for the repository.
- Set up integration testing in a CI/CD pipeline for the repository.
- Add zizmor GitHub Workflow/Action analysis.
