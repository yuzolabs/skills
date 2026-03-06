# skills

[Japanese README](README_ja.md)

This repository is a storage place for yuzolabs's personal Agent Skills.

## Agent Skills

This repository contains the following Agent Skills.

### fetch-github-copilot-reviews

A skill to fetch GitHub Copilot-generated Pull Request reviews.
Since GitHub Copilot reviews cannot be retrieved with the standard `gh pr` command, this skill internally calls the GitHub API directly to fetch the reviews.

**Main Features:**

- Supports PR numbers or full URLs
- Filters reviews by Copilot (using bot detection patterns)
- Retrieves review body and inline comments
- Structured JSON output

### markdown-format

A skill that runs markdownlint-cli2 and textlint repeatedly to format Markdown files.

**Main Features:**

- Automatic correction of Markdown syntax errors
- Japanese style proofreading
- Identification of issues requiring manual correction
