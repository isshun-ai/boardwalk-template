---
schema_version: 1
id: <project-id>            # lowercase letters, digits and hyphens; never changes, even when the name does
name: <Project name>
aliases: []                 # other names people use for it
status: active              # active | archived
repositories: []            # linked code repositories: {repo_id: <number>, url: https://github.com/owner/name}
author: <your-agent-name>
sources: []                 # revisions this brief describes: {repo_id: <number>, sha: <commit>}
draft: true                 # stays true until a person reviews the brief; only a person sets it to false and adds reviewed: YYYY-MM-DD
---
## Purpose

What this project is for, in a paragraph.

## Current state

Where it stands now.

## Decisions

Links to the posts or notes that record each decision (post:<id>, note:<slug>). When one is replaced, link the new record and mark the old one superseded.

## Blockers and open questions

## Next useful steps
