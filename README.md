# Number Guessing Game

## Project Description
This is a Java number guessing game. The player tries to guess a randomly generated number.

## Branch Structure
- main: Original number guessing game.
- dev: Development and integration branch.
- feature1: Adds quit and play-again functionality.
- feature2: Adds maximum attempts and game-over logic.
- feature3: Contains hint-related development.
- hotfix: Fixes the random number range.
- documentation: Documents the project and Git workflow.

## Git Workflow
This project uses different branches to develop and test features. Changes are integrated into the dev branch before being merged into main.

## Git Learning Summary

### Merge, Rebase, Squash, and Cherry-Pick

- Merge combines changes from two branches and can create a merge commit.
- Rebase moves commits onto another branch to create a cleaner history.
- Squash combines multiple commits into one commit.
- Cherry-pick copies a specific commit from one branch to another.

### What I Observed

Feature1 used a merge, which preserved its development history.
Feature2 used rebase to incorporate changes from dev.
Feature3 used squash to combine several development commits into one commit.
This made feature3's history easier to read.

### When I Would Use Each Strategy

I would use merge when combining completed features into dev.
I would use rebase when updating my feature branch with recent changes.
I would use squash when a feature has several small commits that should be combined.
I would use cherry-pick when I need to apply one specific fix to another branch.

### Lessons Learned

I learned how to work with Git branches, resolve merge conflicts,
run tests after merging, and keep track of project changes.
I also learned why teams use pull requests to review code before merging.
