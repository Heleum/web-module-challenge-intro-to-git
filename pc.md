## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control system for tracking code changes by multilpe people on a project stored on a network.

2. What is the difference between Git and GitHub?
Git is the library of special keywords to operate the version control system. GitHub is a website, currenly owned by Microsoft, where many millions of project folders (repositories) are stored.

3. Why do we create a branch?
We create branches to separate our new code changes from previous code so we can compare both versions after the changes are made.

4. What is the purpose of a Pull Request?
A Pull Request is for asking someone to integrate your code changes into a previous set of changes. On a Pull Request, other reviewers can make comments, suggest additional edits, and test or merge the changes.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
`git checkout`
Ex: git checkout -b pace-ellsworth
Ex: git checkout main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
`git fetch` retrieves additional changes from the cloud without adding them to the current working branch.
`git merge` merges your current changes into another branch, local or remote
`git pull` merges remote changes into your current branch

7. What is a merge conflict?
A merge conflict is a situation where two versions of the code exist and one is attempting to overwrite the other.

8. How do you resolve a merge conflict?
You should see which version of the code is the correct one to exist on the final state of the target branch. Depending on how the code functions, you may need to also merge corresponding changes on other lines on the same file or other files in the same repository.
