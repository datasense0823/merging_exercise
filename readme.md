# Overview: In this assignment, you will learn how to:

1. Create a Git repository and work on different branches.
2. Merge branches using Git.
3. Simulate a merge conflict by making incompatible changes on different branches.
4. Resolve merge conflicts by editing files and finalizing the merge.

## 1.Setup: Folder & File Creation:

1. Create a folder named git-merge-assignment.
2. Inside this folder, create a file named example.txt.
3. Initial File Content: Open example.txt and write the following:

```
This is the initial content of example.txt.
```
## 2. Branch Creation and Modifications

1. Create Branch:Create a new branch named feature-a.

2. Modify the File:
   
```
Open example.txt and, immediately after the initial text, add the following line:
```
Save the file and commit this change on the feature-a branch.

## 3. Return to Main and Create Branch:Switch back to the main branch, then create a new branch named feature-b.

1.Modify the File Differently:Open example.txt and, in the same area where the change was made in feature-a, add the following line:

```
Feature B: I have implemented an alternative approach.
```
Save the file and commit this change on the feature-b branch.

## 4.Merging and Creating a Conflict

1. Merge Process:While you are on the feature-b branch, merge the feature-a branch into feature-b.
2. Because both branches modified the same section of example.txt, Git will generate a merge conflict.

## 5. Examine the conflicts, Solve then commit the changes again




