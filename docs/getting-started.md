# Getting started

This guide covers the first steps for working with the RetroWowUpdateResp
repository.

## Prerequisites

- Git, to clone the repository and push changes
- A text editor, to edit response and documentation files
- A web browser, optional, only if you add HTML files later

## Clone the repository

git clone https://github.com/PritheshPoobalan/RetroWowUpdateResp.git
cd RetroWowUpdateResp

## Create your first update response

1. Copy example/sample-update.txt to a new file, for example my-update.txt.
2. Edit the title, date, status, and body fields with your own values.
3. Keep lines beginning with # as comments, or remove them.
4. Commit the new file:

   git add my-update.txt
   git commit -m "docs: add my-update response"

5. Push the change:

   git push origin HEAD

## Conventions

- Use the YYYY-MM-DD format for dates.
- Keep all user-facing text in English.
- Do not use emojis in commit messages or file content.
- Use conventional commit prefixes such as docs:, feat:, fix:, chore:.
- Do not commit real credentials or secrets.
