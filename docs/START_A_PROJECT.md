# Start a New Project (Beginner Friendly)

This guide walks you through creating a small, clean project repo and
getting your first commit pushed.

## What you need
- Git installed
- A GitHub account (or another Git host)

## 1) Pick a name and goal
Write a one-sentence goal for the project.
Example: "CLI tool to rename photos."

## 2) Create a repo
- GitHub UI: New repository -> choose name -> create
- CLI: gh repo create <name> --public (or --private)

Copy the repo URL.

## 3) Initialize locally
```
mkdir my-project
cd my-project
git init
git branch -M main
git remote add origin <repo-url>
```

## 4) Add a minimal structure
```
mkdir src tests docs
```

Create these files:
- README.md
- LICENSE
- .gitignore

Minimal README template:
```
# Project Name

One-line description.

## Getting Started
Describe how to install and run.

## Contributing
Brief note or link to CONTRIBUTING.md
```

## 5) First commit and push
```
git add .
git commit -m "Initial project structure"
git push -u origin main
```

## 6) Next steps
- Choose a language toolchain and add a basic "hello world"
- Add tests and a CI workflow
- Document how to run, test, and release
