FRC1018 Template Robot Project
======================================

This repository is a template intended to be used to bootstrap new robot projects quickly.

### Out of the box features:
- Code style checking with Spotless
- GitHub Actions CI
- All vendordeps we typically use installed

## Creating a new project

### 1. Clone this repo to your computer

Replace `MyNewProject` with the name of the project directory.

    git clone https://github.com/PikeRoboDevils/JavaTemplateProject.git MyNewProject

### 2. Remove `.git` directory and initialize git

This is so the project will have its own history.

    rm -rf .git
    git init

### 3. Update package name if necessary

It's easier to use a refactoring tool like IntelliJ for this step.

Be sure to update `ROBOT_MAIN_CLASS` in `build.gradle`.
