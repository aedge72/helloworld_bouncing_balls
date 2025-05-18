# Bouncing Balls Animation

An HTML page with bouncing balls and a color-changing "Hello World" message that floats around the screen.

## Features
- Realistic physics with balls that bounce off walls and each other
- Color-changing text that floats randomly across the screen
- Smooth animations and transitions

## Git and GitHub Workflow Guide

### Understanding Git vs GitHub

**Git** is a local version control system that runs on your computer:
- Tracks changes to your files
- Creates a history of your project
- Allows you to revert to previous versions
- Works entirely on your local machine

**GitHub** is a web-based platform that:
- Hosts Git repositories online
- Provides a backup of your code
- Enables collaboration with others
- Offers project management tools

### Setting Up a Git Repository

1. **Initialize a Git repository in your project folder:**
   ```bash
   git init
   ```

2. **Check the status of your repository:**
   ```bash
   git status
   ```
   This will show untracked files (marked with "U" in some interfaces).

3. **Create a .gitignore file (optional)** to exclude files that shouldn't be tracked:
   ```bash
   echo ".env" > .gitignore
   git add .gitignore
   git commit -m "Add gitignore file"
   ```

### Adding Files to Git

1. **Stage files** to prepare them for committing:
   ```bash
   # Add a specific file
   git add filename.html

   # Add all files in the directory
   git add .
   ```

2. **Commit your changes** to save a snapshot:
   ```bash
   git commit -m "Your commit message describing the changes"
   ```

### Connecting to GitHub

1. **Create a new repository on GitHub:**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon and select "New repository"
   - Name your repository and click "Create repository"

2. **Connect your local repository to GitHub:**
   ```bash
   git remote add origin https://github.com/username/repository-name.git
   ```

3. **Push your local commits to GitHub:**
   ```bash
   # First-time push
   git push -u origin main

   # Subsequent pushes
   git push
   ```

### Workflow for Updates

1. **Make changes to your files**

2. **Stage the changes:**
   ```bash
   git add filename.html
   ```

3. **Commit the staged changes:**
   ```bash
   git commit -m "Describe your changes"
   ```

4. **Push to GitHub:**
   ```bash
   git push
   ```

### Common Git Commands

- `git status`: Check the current state of your repository
- `git log`: View commit history
- `git diff`: View changes between commits
- `git pull`: Get the latest changes from GitHub
- `git branch`: List, create, or delete branches
