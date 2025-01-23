# Learning Git Branching

This repository demonstrates the concepts of Git branching, merging, and conflict resolution. It includes examples of creating branches, merging them into the main branch, handling merge conflicts, and resolving them.

## Repository Overview

- **Branches**:
  - `main`: The primary branch with the base code.
  - `feature`: A branch created to add new features.
  - `conflict`: A branch created to simulate and resolve merge conflicts.

- **Commits**:
  - `Initial Commit`: Basic setup of the repository.
  - `Commit 3`: Added a new file to the repository.
  - `bugfix`: Fixes added to the `main` branch before merging.
  - `Conflict`: A commit created to simulate merge conflicts.

## Learning Steps

1. **Creating a New Branch**  
   A new branch `feature` was created to add new features. Changes were made and committed in this branch.

2. **Merging Branches**  
   The `feature` branch was merged into the `main` branch after adding the `bugfix` commit.

3. **Simulating and Resolving Merge Conflicts**  
   - A `conflict` branch was created to introduce conflicting changes to the `main` branch. 
   - The conflict was resolved manually during the merge process.

## Key Git Commands Used

- **Branching**:
  ```bash
  git branch feature
  git checkout feature
- **Merging**:
   ```
   git merge feature
   ```
- **Resolving Merge Conflicts: Open the conflicted file(s), manually resolve the conflicts, then**:
  ```
  git add <file>
  git commit
  ```
## Purpose
This repository serves as a hands-on exercise to understand:

- **The purpose of branching in Git.**
 - How to merge branches and handle conflicts.
 - Effective use of Git for collaborative development.
