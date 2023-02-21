# Git Interview question....

#### 1. https://manoj777.medium.com/git-interview-questions-and-answers-for-devops-5d0b971f8fbb

## Git command
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mydev911/java_devops.git
git push -u origin main
![image](https://user-images.githubusercontent.com/23219981/220357330-f30fcfe0-9b08-448c-a206-70bb1708fde2.png)
```

### 1. Explain the difference between rebasing and merge in Git?
- Git rebase is a command that allows developers to integrate changes from one branch to another.
- Git merge is a command that allows you to merge branches from Git.

- Git rebase and merge both integrate changes from one branch into another. Where they differ is how they used. Git rebase moves a feature branch into a master. Git merge adds a new commit, preserving the history.

(If you’re working alone or on a small team, use rebase. If you’re working with a big team, use merge.)

### 2. Have you faced the situation where you resolve conflicts in Git? How?
A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits. Git can merge the changes automatically only if the commits are on different lines or branches. Here are the steps that will help you resolve conflicts in Git:
1. The easiest way to resolve a conflicted file is to open it and make any necessary changes
2. After editing the file, we can use the git add a command to stage the new merged content
3. The final step is to create a new commit with the help of the git commit command
4. Git will create a new merge commit to finalize the merge

### 3. How to revert a commit that has already been pushed and made public?
There are two processes through which you can revert a commit:
1. Remove or fix the bad file in a new commit and push it to the remote repository. Then commit it to the remote repository using:
git commit –m “commit message”
2. Create a new commit to undo all the changes that were made in the bad commit. Use the following command:
git revert <commit id>

### 4. Tell about the commands git reset — mixed and git merge — abort?.
git reset — mixed is used to undo changes made in the working directory and staging area.
git merge — abort helps stop the merge process and return back to the state before the merging began 
  
 

