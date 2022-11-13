# ToraHooks
This repository contains hooks designed for a better CI

# Directory build props
- Ensure use git hooks

# Hooks

## Pre Commit
- Verify git hooks version
- Run dotnet format
- Run dotnet test

## Prepare Commit Message
- Checks if the branch name matches the expected pattern
- Automatically add branch name at end of commit message 

# Actions

## Code review work item creator
- Automatically create task when creating a new pull request 