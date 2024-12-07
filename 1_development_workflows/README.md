# Development Workflows

> “I'm not a great programmer; I'm just a good programmer with great habits.”
>
> - [Kent Beck](https://en.wikiquote.org/wiki/Kent_Beck)

Learn the skills required to work a software project using only Markdown.
Limiting your projects to Markdown lets you focus on the big picture without
getting distracted by more challenging code.  

- [Learning Objectives](#learning-objectives)
- [Prep Work](./prep_work.md)
- [Lesson Plan](./lesson_plan.md)

---

## Learning Objectives

<details>
<summary>Priorities: 🥚, 🐣, 🐥, 🐔 (click to learn more)</summary>
<br>

There is a lot to learn in this repository. If you can't master all the material
at once, that's expected! Anything you don't master now will always be waiting
for you to review when you need it. These 4 emoji's will help you prioritize
your study time and to measure your progress:

- 🥚: Understanding this material is required, it covers the base skills you'll
  need for this module and the next. You do not need to finish all of them but
  should feel comfortable that you could with enough time.
- 🐣: You have started all of these exercises and feel you could complete them
  all if you just had more time. It may not be easy for you but with effort you
  can make it through.
- 🐥: You have studied the examples and started some exercises if you had time.
  You should have a big-picture understanding of these concepts/skills, but may
  not be confident completing the exercises.
- 🐔: These concepts or skills are not necessary but are related to this module.
  If you are finished with 🥚, 🐣 and 🐥 you can use the 🐔 exercises to push
  yourself without getting distracted from the module's main objectives.

---

</details>

### Local Development Without Git

Practice the foundational workflows of software development by learning to write
Markdown locally on your own computer using Visual Studio Code (VSCode), the
Command Line Interface (CLI) to automate your code's quality
(formatting, linting and spell checking).

- [X] 🥚 **Folder Structures**: You can explain how files and folders are stored
      in your computer and can find, open or create files in your computer
      without using the Command Line Interface.
- 🥚 **Command Line Interface (CLI)**: In a Unix shell you can ...
  - [X] Open a new terminal window
  - [X] Navigate up and down directories using `cd`
  - [X] List the contents of a directory using `ls`
  - [X] View the contents of a file using `cat`
  - [X] Create new files using `touch`
  - [X] Create new folders using `mkdir`
- [X] 🥚 **READMEs**: You can write a README file that describes the project you
      are working on, why it's helpful, and how someone can use it.
- 🥚 **Formatting Markdown**: You can use Prettier to make sure all the code in
  your project is well-formatted:
- 🥚 **Linting Folder and File Names**: You can ...
  - [X] Use `ls-lint` to check all folder and file names in your project
  - [X] You can fix all linting mistakes reported by `ls-lint`
- 🥚 **Linting Markdown**: You can use the MarkdownLint VSCode extension to find
  and fix linting errors in markdown documents.
  - [X] 🥚 **Spell Check**: You can use the Code Spell Checker VSCode extension
        to correct spelling mistakes in your Markdown documents while you are
        writing
- [X] 🥚 **File and Folder Naming Conventions**: You can use _snake_case_ to
      name all files and folders in your project.
- [X] 🐣 **File Extensions**: You can identify all of the languages covered at
      HYF and give the correct file extension. You don't need to know the
      languages, just recognize them.
- [X] 🐣 **Touch Typing**: You can write a Markdown file without looking at your
      keyboard to find any letters, numbers or special characters. (slowly is
      ok!)

### Local Development With Git

Practice using Git to save and organize your development process. You will learn
how you can use Git to go back to previous versions of your project, and to work
on different changes in parallel.

- 🥚 **Git**: Using the CLI you can ...
  - [X] Initialize a new git repository with `git init`
  - [X] Stage changes using `git add <path>`
  - [X] Check what is staged with `git status`
  - [X] Commit changes using `git commit -m <message>`
  - [X] Display your repository's git history using `git log`
  - [X] Create a new branch using `git branch <branch-name>`
  - [X] Check out a branch using `git checkout <branch-name>`
  - [X] Create a new branch and check it out using
        `git checkout -b <branch-name>`
  - [X] Merge changes from one branch to another using `git merge <branch-name>`
  - [X] Update current branch (your branch) from _main_ branch:
    - [X] Check out to _main_ branch using `git checkout main`
    - [X] Pull changes from remote repository using `git pull`
    - [X] Check out to your branch using `git checkout <branch-name>`
    - [X] Merge changes from _main_ branch to your branch using `git merge main`
  - [X] Merge changes from _main_ branch to current branch in one step using
        `git pull origin main`
  - [X] Return to a previous version of your project with `git log` and
        `git checkout <commit-hash>`
  - [X] Stash and retrieve uncommitted changes with `git stash` and `git pop`
  - [X] Display list of existing remote URLs using `git remote -v`
  - [X] Add a new remote repository URL using
        `git remote add <shortname> <remote-url>`
  - [X] Update a remote repository URL using
        `git remote set-url <exsit-shortname> <new-remote-url>`
  - [X] Rename a remote repository URL using
        `git remote rename <old-shortname> <new-shortname>`
  - [X] Remove a remote repository URL using `git remote rm <exsit-shortname>`
- 🥚 **`.gitignore`**: You can use a `.gitignore` file to describe which files
  you don't want included in your git history.
- 🥚 **VSCode**: You can ...
  - [X] Use the _Git Graph_ extension to to visualize your repo's commit history
  - [X] Use the _Git Lens_ extension to investigate your repository's commit
        history
  - [X] Explain how the file tree in VSCode can show you which files have
        uncommitted changes
- [X] 🥚 **Atomic Commits**: You can save your development progress using small
      commits with clear and helpful message.
- [X] 🐣 **Feature Branches**: You can organize your development process using
      branches. You can create a new branch for each part of your project and
      merge those changes to `main` when they are finished.

### Local/Remote Development

Learn how you can connect your local Git repositories with a GitHub repository
to add more structure to your development process and to share your projects.

- 🥚 **Licenses**: You can ...
  - [X] Explain why it's important to include a license for your code on GitHub
  - [X] Choose a license for your projects that matches how you want others to
        use your code
- [X] 🥚 **Contributor Guidelines**: You can explain why contributor guidelines
      are important for a public repository.
- [X] 🥚 **Code of Conduct**: You can explain why a code of conduct is important
      for a public repository.
- [X] 🥚 **GitHub SSH Key**: You can connect your computer to your GitHub
      account using an SSH key, clone using the SSH link, and push/pull using
      your SSH connection.
- 🥚 **GitHub Repositories**: You can ...
  - [X] Create new repository on GitHub
  - [X] Write a description for your repository
  - [X] Turn on GitHub Pages
  - [X] Configure your repository to block pushing to `main`
  - [X] Configure your repository to block merging to `main` until Continuous
        Integration (CI) checks have passed
- 🥚 **Git Remote/Local Connection**: You can ...
  - [X] Clone a remote repository to your computer using
        `git clone <remote-url>`
  - [X] initialize a new repository locally and connect it to an empty remote
        repository
  - [X] `git push` command is used to upload local repository content to a
        remote repository
  - [X] `git fetch` a primary command used to download contents from a remote
        repository
  - [X] `git pull` command downloads the changes directly and then applies those
        changes to the current working files
  - [X] `push` and `pull` changes between remote & local branches
  - [X] You can distinguish between `git fetch` and `git pull`
- [X] 🥚 **Pull Requests**: You can create a pull request between two branches
      in your repository and merge changes without causing any conflicts.
- [X] 🥚 **PR templates**: You can use a PR template to add a checklist to all
      of your PRs so you are sure the code is great before merging to `main`.
- [X] 🥚 **Continuous Integration**: You can use GitHub Actions to check your
      code's quality before merging a pull request to the `main` branch.
- [X] 🐣 **Local/Remote Branching Workflow**: You can use a branching workflow
      that keeps mistakes away from the `main` branch and prevents conflicts
      from happening in GitHub. For each contribution to the project you can ...
  1. Check out a new local branch and write your code
  2. Check out `main` on your local machine
  3. Pull changes from remote `main` to local `main`
  4. Merge changes locally from `main` to your new branch
     - Fix any conflicts on your new branch before pushing!
  5. Format and lint your code
  6. Push your new local branch to your remote repository
  7. Open a Pull Request from the new branch to `main`
     - Go through the PR's checklist to make sure everything is correct
     - Make sure all CI checks pass!
  8. Merge your new remote branch to `main`
     - You can delete the branch after it's merged if you want to
