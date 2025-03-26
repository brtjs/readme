# Git Guide

## Git History

By the early 2000s, Linux was growing rapidly, and its contributors needed a powerful system to manage thousands of code changes. They started using **BitKeeper**, a distributed version control system (DVCS).  

Unlike older systems, BitKeeper allowed developers to work offline and still track their changes. It was fast and handled large projects efficiently.  

Everything was going well… until disaster struck.

## Installation of Git

[Download Git Here](https://git-scm.com/downloads)

---

## How Code is Stored in Git

Code is stored in Git in **four ways**:

1. **Working Directory**  
   The place where files are created, modified, and deleted before being tracked by Git.  

2. **Staging Area**  
   A temporary storage where changes are added using `git add` before committing.  

3. **Local Repository**  
   The committed changes are saved in the local Git repository using `git commit`.  

4. **Remote Repository**  
   The local commits are pushed to a remote repository (e.g., GitHub, GitLab) using `git push`, allowing collaboration.  

---

## Most Used Git Commands

### **Setting Up Git**
1. `git config --global user.name "Your Name"` → Set your Git username.  
2. `git config --global user.email "youremail@example.com"` → Set your email for Git.  

### **Repository Commands**
1. `git init` → Initialize a new Git repository in a folder.  
2. `git add <file>` → Add a file to the staging area before committing.  
3. `git status` → Check the status of files in the repository.  
4. `git clone <repository_url>` → Clone a remote repository to your local machine.  
5. `git commit -m "commit message"` → Commit changes with a message.  
6. `git push -u origin main` → Push changes to the main branch.  
7. `git branch` → List all branches in the repository.  
8. `git branch <branch_name>` → Create a new branch.  
9. `git checkout <branch_name>` → Switch between branches.  
10. `git merge <branch_name>` → Merge a branch into the current branch.  

---

These are the **most commonly used Git commands**. You can add this README.md file to your repository to help others understand Git better.
