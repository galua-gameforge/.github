# Shared galua-gameforge configuration

This repository contains shared community templates for projects in the
[galua-gameforge](https://github.com/galua-gameforge) organization

GitHub automatically uses these files in organization repositories when the
target repository does not provide its own template of the corresponding type

## Contents

- [Bug report template](.github/ISSUE_TEMPLATE/bug_report.yml)
- [Feature request template](.github/ISSUE_TEMPLATE/feature_request.yml)
- [Issue creation settings](.github/ISSUE_TEMPLATE/config.yml)
- [Pull request template](.github/pull_request_template.md)

## How inheritance works

Shared templates are applied automatically and are not copied into child
repository history. A local file serving the same purpose takes precedence

Issue forms have an additional rule: when a child repository contains a
`.github/ISSUE_TEMPLATE` directory with any configuration file or template,
GitHub does not inherit shared files from that directory

## Updating templates

1. Create a separate branch
2. Update the shared template
3. Validate the YAML and Markdown
4. Open a pull request describing the impact on games and libraries
