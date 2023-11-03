# Commit Message Guidelines

## Introduction

Welcome to the commit message guidelines for BOSS.Tech. These guidelines are designed to ensure consistency, clarity, and organization in our version control history. By following these guidelines, we can streamline the process of reviewing and understanding changes made to the project.

## General Principles

1. **Keep It Concise**: Commit messages should be brief and to the point. Aim for clarity without unnecessary verbosity.

2. **Focus on the What and Why**: Explain what the commit does and why it's necessary. If it fixes an issue, reference the issue number.
TODO:(cr) - will we be using issues here? 
3. **Use Imperative Mood**: Write commit messages in the imperative mood (e.g., "Add feature" rather than "Added feature").

4. **Separate Subject and Body**: If necessary, provide a more detailed explanation in the body of the commit message, separated by a blank line.

5. **Reference Related Issues**: When a commit addresses or closes an issue, include a reference to the issue number in the commit message.

## Commit Message Structure

Each commit message should follow the structure:

```
<type>: <subject>

<body (optional)>

<issue reference (optional)>
```

- **Type**: Describes the purpose of the commit. Common types include "feat" (feature), "fix" (bugfix), "docs" (documentation), "style" (formatting), "refactor" (code improvement), "test" (adding or updating tests), and "chore" (maintenance tasks). Use lowercase letters.

- **Subject**: Briefly explains what the commit does. Start with a verb in the imperative mood.

- **Body (optional)**: Provides a more detailed description of the commit, if necessary. Use the body to explain the reasoning behind the change or additional context.

## Examples

### Adding a new feature:

```
feat: Add integration between Zendesk Ticketing count and Salesforce Users

- Allow users to track Salesforce entities who have recently submitted tickets via Zendesk

Closes #42
```

### Fixing a bug:

```
fix: Resolve issue with Spotify and Salesforce integration

- Fixed a bug where the API calls failed due to a misconfigured Payload

Closes #55
```

### Updating documentation:

```
docs: Update installation instructions

- Clarified installation steps for macOS users.

```

## Review and Collaboration

Following these guidelines will help maintain a clean and informative version control history for our project. All contributors are encouraged to review each other's commit messages and provide feedback to ensure consistency.

## Additional Resources

- [Conventional Commits](https://www.conventionalcommits.org/): A specification for standardized commit messages.
