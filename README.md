# Interview Codespaces template

This repository is a starting point for a Node.js/TypeScript interview environment. It uses a minimal Ubuntu development container with Node.js 24 and disables VS Code completion, hover information, and Copilot suggestions in the workspace.

## Customize the environment

Add the interview prompt and starter files to this repository. Update `.devcontainer/devcontainer.json` with the language runtime, tools, or VS Code extensions candidates need. Keep extensions that provide code completion out of the image if you want the environment to remain focused on the interview.

## Share with a candidate

Keep this repository private and invite each candidate as a collaborator. They can open the repository and create a Codespace directly from its **Code** menu; they do not need to create another repository.

Candidates will share this repository, so their branches and committed work are visible to other collaborators. Protect the default branch and have candidates work on separate branches if you want to avoid changes colliding. Separate branches do not make candidate work private from each other.

Check your organization's Codespaces policy and billing before sharing.

These editor settings are defaults for this workspace, not an enforcement boundary. Candidates can change settings or install tools in their Codespace. For a strictly controlled assessment, use an environment and process designed to control candidate tooling.