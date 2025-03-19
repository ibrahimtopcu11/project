## İbrahim Topcu 2220674032
## Overview
This document provides a structured overview of using Git and GitHub workflows. It includes the Git commands used, challenges faced, and benefits of using AI assistance. Additionally, it features a comparison between local Git workflows and GitHub workflows.

---

## Screenshots
Below are the screenshots taken during the process:

1. **Initializing a Git Repository**  
   ![Git Init](Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202025-03-19%20113208.png)

2. **Checking Remote Repository**  
   ![Git Remote](Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202025-03-19%20114603.png)

3. **Verifying Remote Repository URL**  
   ![Git Remote URL](Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202025-03-19%20112311.png)

---

## Git Commands Used

| Command | Description |
|---------|------------|
| `git init` | Initializes a new Git repository in the project directory |
| `git remote -v` | Displays the current remote repository URL(s) |
| `git remote add origin <URL>` | Adds a remote repository URL |
| `git commit -m "message"` | Commits changes with a message |
| `git push -u origin main` | Pushes commits to the main branch of the remote repository |

---

## **Local Git Workflow vs GitHub Workflow**

| Aspect | Local Git Workflow | GitHub Workflow |
|--------|--------------------|----------------|
| Version Control | Manages versions locally | Manages versions in a remote repository |
| Collaboration | Limited to local machine | Enables team collaboration |
| Backup | No automatic backup | Cloud-based backup on GitHub |
| Accessibility | Available only on the local system | Accessible from anywhere |

---

## Challenges Faced
- **Remote Repository URL Issues:** Incorrectly configured remote repository led to errors while pushing.
- **Branch Issues:** The default branch was `master`, while GitHub expected `main`.
- **Authentication Problems:** Git required authentication using a Personal Access Token (PAT) instead of passwords.

---

## When I Decided to Make a Commit
I made commits whenever a significant change was completed, such as:
- After initializing the repository.
- After configuring the remote repository.
- After resolving authentication errors.

---

## Benefits of AI Assistance
I used AI to:
- Troubleshoot Git errors efficiently.
- Understand the difference between `main` and `master` branches.
- Get help on configuring authentication methods.

---

## My Question and What I Learned
### **My Question:**
I encountered an error while trying to push my repository to GitHub. The error message was:

### **Platform Used:**
I used ChatGPT to debug and resolve my issue.

### **What I Learned:**
- How to correctly set up a GitHub remote repository.
- The importance of checking the correct repository URL.
- The difference between `master` and `main` branches in modern Git workflows.
- How to authenticate using a GitHub Personal Access Token.

---

## Conclusion
This document summarizes the Git and GitHub workflows followed, the commands used, and the challenges faced. The integration of AI assistance made the process more efficient and helped in quickly resolving Git-related issues. 🚀
