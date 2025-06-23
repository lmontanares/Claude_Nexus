# Commit Workflow Command

## Description
Complete commit workflow: check pre-commits, generate 3 commit options, and commit with first option

## Category
git-workflow

## Prompt

I need you to execute the complete commit workflow for this project:

1. **Check Git Status**: Run `git status` and `git diff HEAD` to understand what changes are staged/unstaged

2. **Review Recent Commits**: Run `git log --oneline -5` to understand commit message style

3. **Pre-commit Check**: Run any pre-commit hooks or linting if available

4. **Generate 2 Commit Options** (based on git diff analysis, not development conversation):
   - Option 1: Standard commit message with key changes only
   - Option 2: Concise conventional commit format

5. **Auto-select Option 1**: Automatically choose and execute the second (standard commit) commit option

6. **Handle Pre-commit Issues**: If pre-commit hooks fail, fix the issues and retry

7. **Confirm Success**: Show the final commit hash and summary

Please execute this workflow now, being thorough with commit message quality and ensuring all pre-commit hooks pass.
