# Create Repository Tasks

A set of tasks to set up a new repository.

## Table of Contents

- [Create Repository Tasks](#create-repository-tasks)
  - [Table of Contents](#table-of-contents)
  - [Tasks](#tasks)
    - [General](#general)
    - [Language Specific](#language-specific)

## Tasks

### General

- Add a `pull_request_template.md` file to the root of the repository.
- Add a `.editorconfig` file to the root of the repository.
- Add a `LICENSE` file to the root of the repository. If one wasn't created with the repository.
- Add a `README.md` file to the root of the repository.
- Set up a `CODE_OF_CONDUCT.md` file to the root of the repository.
- Set up a `CONTRIBUTING.md` file to the root of the repository.
- Set up a `SECURITY.md` file to the root of the repository.
- Set up issue templates for the repository.
- Set up generic Git Hooks for the repository.

### Language Specific

- Set up debug configurations for the language in the `.vscode` directory.
  - Set up a `launch.json` file in the `.vscode` directory.
- Configure unit tests for the language
  - Set up configuration in the `.vscode/settings.json` file.
- Set up Git Hooks for the language for linting and formatting.
