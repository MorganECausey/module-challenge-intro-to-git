## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a tool that allows developers to work locally on repositories. Working locally not only allows developers to manage multiple versions of source code. 
 
2. What is the difference between Git and GitHub?
While Git is a tool for developers to use, GitHub works as a location for developers to upload copies of a repository. 

3. Why do we create a branch?
You create a branch in order to keep different changes separate from the main branch. This allows you to keep changes both big and small, separate from the origional repository code. Any time you want to create a new feature or fix bugs you create a new branch. 

4. What is the purpose of a Pull Request?
A pull request allows developers to tell others working on the project about the changes that they have made to the project. This is seen by others by comparing the main branch with the branch that the developer has made to a branch. 

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
To switch branches, you use the "git switch" command to change the branch you are on. 

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The command 'git fetch' allows developers to download any remote updates like commits while keeping the remote repository the same . The command 'git merge' allows developers to merge multiple commits into one unified history. The command 'git pull' allows developers to fetch and download updates from a remote repository and immediately update the loacl repository to match, but this does not allow the developer to see what changes will be made until after the update. 

7. What is a merge conflict?
A merge conflict is when you merge branches that have commits that compete against each other. 

8. How do you resolve a merge conflict?
You resolve a merge conflict by choosing what changes need to be made until there are no more conflicting commits. 