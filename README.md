# Cloud Computing Lab – Lab 2

**Name:** Nimra Mursleen  
**Reg No:** 2023-BSE-47  
**Course:** Cloud Computing Lab  
**Section:** V-B  

**LAB-2**

## Install Git on your PC

![Git Installation](screenshots/git_installation.png)

---

## Task 1: Create Private GitHub Repository

![Private Repo](screenshots/repo_private.png)

---

## Task 2: Connect Repository via SSH

1. Generate a new SSH key  
![Generate SSH Key](screenshots/ssh_keygen.png)

2. Add SSH public key to GitHub  
![Add SSH Key to GitHub](screenshots/github_sshkey.png)

3. Clone your Lab2 repo using SSH  
![Clone via SSH](screenshots/ssh_clone.png)

---

## Task 3: Configure Git Username and Email

1. Set up Git identity  
![Git Identity](screenshots/git_identity.png)

2. Verify configuration  
![Git Config List](screenshots/git_config_list.png)

---

## Task 4: Explore the .git Folder

![Explore .git Folder](screenshots/git_folder.png)

---

## Task 5: Local Repository Management

1. Delete the existing `.git` folder  
![Delete .git Folder](screenshots/delete_git.png)

2. Re-initialize the local git repository  
![Reinitialize Git](screenshots/git_init.png)

3. Add a file named `README.md` and commit it  
![First Commit](screenshots/first_commit.png)

4. Connect local repo to GitHub and push  
![First Push](screenshots/first_push.png)

---

## Task 6: File Status & Staging

1. Create a new file `notes.txt`, write a note, and check status  
![File Status](screenshots/status1.png)

2. Stage and commit  
![Commit Notes](screenshots/commit_notes.png)

---

## Task 7: Branch Creation Using GitHub GUI

1. On GitHub, create a branch named `bugfix/user-auth-error`  
![Branch Creation in GUI](screenshots/bugfix_branch_gui.png)

2. Pull the branch to local repository to sync  
![Pull Branch Locally](screenshots/bugfix_branch_local.png)

---

## Task 8: Branch Creation and Push Using Git Bash

![Feature Branch Push](screenshots/feature_db_branch.png)

---

## Task 9: Branching & Merging

1. Create and switch to a branch `feature-1`  
![Create Feature Branch](screenshots/branch_create.png)

2. Modify `main.py` (add a function) and commit  
![Commit Changes](screenshots/feature_commit.png)

3. Switch back to `master` and merge  
![Merge Branch](screenshots/merge.png)

4. Push all branches  
![Push Branches](screenshots/push_branches.png)

---

## Task 10: Pull Request and Branch Review (GitHub GUI)

1. Pull Request creation  
![PR Creation](screenshots/pr_creation.png)

2. Pull Request review and merge  
![PR Merge](screenshots/pr_merge.png)

3. Branch deletion  
![Branch Deletion](screenshots/branch_delete.png)

---

## Task 11: Detailed Branch Strategy (Develop/Staging)

1. Branch list  
   - Create `develop` and `staging` branch  
   ![Branch Strategy Part 1](screenshots/branch_strategy_part1.png)

   - Create `feature/login` and `bugfix/error-msg` branch in `develop`  
![Branch Strategy Part 2](screenshots/branch_strategy_part2.png)
![Branch Strategy Part 3](screenshots/branch_strategy_part3.png)


2. Merges into `develop` and `staging`  
![Branch Merges](screenshots/branch_merges.png)

3. Final merge into `master`  
![Final Merge](screenshots/final_merge.png)

