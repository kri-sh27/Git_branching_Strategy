# Project Title

This repository demonstrates a standard Git workflow including branch management, pull requests, tags, and best practices for maintaining code quality.

## Workflow Overview

1. **Repository Initialization**
    - Created a new repository on GitHub.
    - Cloned the repository to local machine.

2. **Branch Management**
    - Created `dev` branch from `main`.
    - Created `feature` branch from `dev`.
    - Feature development was done in `feature` branch.

3. **Using Pull Requests**
    - Pushed code to GitHub via the `feature` branch.
    - Created a pull request to merge `feature` into `dev` branch.
    - After code review, merged `feature` into `dev`.
    - Created a pull request to merge `dev` into `main` branch.
    - Merged `dev` into `main` upon approval.

4. **.gitignore Usage**
    - Included a `.gitignore` file to exclude unnecessary files/folders from the repository (e.g., build files, OS files, IDE files).


## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/kri-sh27/Git_branching_Strategy.git
    ```

2. Working with branches:
    ```bash
    git checkout main
    git checkout -b dev
    git checkout -b feature dev
    ```

3. After making changes:
    ```bash
    git add .
    git commit -m "Your commit message"
    git push origin feature
    ```

4. Merging changes via pull requests on GitHub.

## .gitignore

This repository uses a `.gitignore` file to exclude files like:
- Node modules (`node_modules/`)
- OS/IDE settings
- Log files

## Contributing

To contribute:
- Create a new feature branch off `dev`.
- Commit and push your changes.
- Make a pull request to merge your branch into `dev`.
- After review, merge into `main`.

