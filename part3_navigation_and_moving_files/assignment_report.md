# Task 3: Navigating Directories and Moving Files

### Purpose

Practice navigating through directories, listing file contents, and moving files to different locations.

### Commands Used & Outputs

```bash
# Created task folder
mkdir part3_navigation_and_moving_files
cd part3_navigation_and_moving_files

# Created files and folders
touch fileA.txt
touch fileB.txt
mkdir folder1
mkdir folder2
ls
# Output:
# fileA.txt  fileB.txt  folder1  folder2

# Navigated into folder1 and back
cd folder1
pwd
cd ..
pwd

# Moved fileA.txt into folder1
mv fileA.txt folder1/
ls
ls folder1

# Moved fileB.txt into folder2
mv fileB.txt folder2/
ls
ls folder2
