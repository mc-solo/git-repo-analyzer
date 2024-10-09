# GitHub Repository Analysis CLI

## Overview

The **GitHub Repository Analysis CLI** is a command-line tool designed to fetch and analyze various aspects of a GitHub repository. Users can retrieve information such as repository stats, contributor details, open issues, pull requests, and the languages used in a repository. This tool provides a fast and simple way to gather insights from one or more GitHub repositories directly from the terminal.

## Features

- Fetch basic repository information (stars, forks, watchers, etc.).
- List open/closed issues and pull requests.
- Retrieve contributor statistics.
- Analyze languages used in a repository.
- Compare multiple repositories.
- Export analysis results to JSON or CSV files.
- User-friendly CLI with interactive and non-interactive modes.
- Customizable GitHub authentication via Personal Access Token (PAT).

# Installation

## Clone the repository:

```bash
git clone https://github.com/yourusername/github-repo-analysis-cli.git
cd github-repo-analysis-cli
```

## Install dependencies

```bash
npm install
```

## Set up GitHub API token

```makefile
GITHUB_TOKEN=your_personal_access_token
```
