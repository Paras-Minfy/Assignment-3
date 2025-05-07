# Assignment 3: Git Branching & Merge Conflict Resolution

## 🎯 Purpose
The goal of this assignment is to understand and apply **GitHub Flow** by creating feature branches, making changes to the same file, and resolving merge conflicts using Git.

## 🗂️ Project Summary
This project uses a single HTML file (`index.html`) to demonstrate:
- Creating and working on multiple branches
- Making overlapping edits
- Handling merge conflicts manually
- Merging feature branches successfully

## 🔁 Workflow Breakdown

### ✅ Step 1: Branch Creation
Two feature branches were created from the `main` branch:
- Branch A -> `feature/add-content`: Focused on adding new content to `index.html`
- Branch B -> `feature/update-styling`: Focused on updating styling and tailwindcss in `index.html`

### ⚠️ Step 2: Creating a Conflict
Both branches made changes to the same sections of the file, which led to a **merge conflict** during the second pull request.

### 🔧 Step 3: Conflict Resolution
While merging `feature/add-content` after `feature/update-styling`, a conflict occurred. To resolve it:
1. Git highlighted the conflicting code
2. The file was manually edited to combine both changes
3. Conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) were removed
4. Final version was tested and committed
5. The merge was completed without losing any updates

## 📸 Visual Demonstration

- ### Styling & Content Branch Merged

- ### Conflict Detection and Resolution which is Resolved Manually and Final Output
 - ![](https://github.com/Paras-Minfy/Assignment-3/blob/main/SS-A3/Screenshot%202025-05-07%20102155.png)
 - ![](https://github.com/Paras-Minfy/Assignment-3/blob/main/SS-A3/Screenshot%202025-05-07%20102220.png)
 - ![](https://github.com/Paras-Minfy/Assignment-3/blob/main/SS-A3/Screenshot%202025-05-07%20102326.png)
 - ![](https://github.com/Paras-Minfy/Assignment-3/blob/main/SS-A3/Screenshot%202025-05-07%20102716.png)
 - ![Final Web Page](https://github.com/Paras-Minfy/Assignment-3/blob/main/SS-A3/Screenshot%202025-05-07%20103010.png)

## 📘 Key Learnings
- Conflicts are normal when collaborating on the same files
- Manual conflict resolution is essential to preserve everyone’s work
- Following GitHub Flow ensures a clean and trackable development process

---
