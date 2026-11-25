# Usage guide

This document explains how to work with update responses in this repository.

## Creating an update response

An update response is a plain text file that describes an update. Use the
example under example/sample-update.txt as a template. Each response should
include:

- A title line at the top.
- A date in YYYY-MM-DD format.
- A body describing what changed.
- An optional status field, for example status: applied or status: pending.

## Example file with inline comments

See example/sample-update.txt. It uses # comment lines to explain each
section. Comments are for humans and are ignored by any tooling that parses
the response body.

## Pushing changes

Because this is a public repository, push every branch so collaborators can
see the full history:

git push origin --all

Do not include secrets, passwords, or API keys in committed files.
