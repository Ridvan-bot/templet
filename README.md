# templet

## This is a Templet repo to duplicate.

## Checklist to use shared workflow

### Create a github token 
### Add it as a secret
### In Settings > Actions of your repository, ensure that Actions permissions are set correctly (for example, allowing actions to push to the repository).



# Template Repository
## Overview
This repository serves as a template for quickly duplicating workflows and configurations into other projects. The goal is to streamline your development process by providing a pre-configured set of tools, workflows, and settings that can be copied into new repositories.

## Features
Pre-configured GitHub Actions workflows for CI/CD pipelines.
Automated Semantic Release for versioning and changelog generation.
TypeScript support and type definitions for Node.js.
Ready-to-use configuration for managing conventional commits.

## Getting Started
1. Clone the Repository
To create a new project using this template, clone the repository and rename it to fit your project:

```bash
git clone https://github.com/Ridvan-bot/templet.git your-new-project
cd your-new-project
```

2. Update Project Details
Edit the package.json file to include your project’s specific information:

Update the name, version, description, author, and repository fields.
Adjust dependencies as needed for your new project.

3. Install Dependencies
Ensure you have all necessary packages installed:

```bash
npm install
```

4. GitHub Actions
This template includes pre-configured workflows for GitHub Actions. To use them:

Copy the .github/workflows directory to your new repository.
Adjust the workflow files if necessary to match your project structure.

5. Semantic Release Configuration
The template is set up with Semantic Release to automate the release process:

Automatic versioning based on commit messages.
Generates a CHANGELOG.md file.
Publishes releases to GitHub and updates the package on npm.
Make sure your new repository has the required environment variables set up:

GITHUB_TOKEN (for GitHub releases).
NPM_TOKEN (if publishing to npm).

Dependencies
The project includes the following dependencies:

TypeScript for type safety (typescript, @types/node).
Semantic Release plugins:
@semantic-release/changelog: Generates a changelog.
@semantic-release/git: Commits version changes back to your repository.
@semantic-release/github: Publishes releases to GitHub.
@semantic-release/npm: Handles npm publishing.
Scripts
The package.json contains the following script:

test: A placeholder script (echo "Error: no test specified").
You can modify this to include tests specific to your project.

Issues & Contributions
If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub Issues page.

License
This project is licensed under the ISC License. Feel free to modify and use it in your own projects.

Links
Repository: GitHub
Issues: Submit Issues
Homepage: Project Homepage