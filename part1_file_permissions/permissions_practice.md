# Linux File Permissions Practice

## Created file: file1.txt

## Initial permissions:

ls -l myfile.txt

## chmod commands used:

- chmod u+x myfile.txt
- chmod o-r myfile.txt
- chmod 754 myfile.txt

# Note: On Windows (Git Bash), chmod command does not fully change file permissions due to NTFS limitations. This is expected.

# Commands used:

chmod u+x myfile.txt
ls -l myfile.txt

# Output:

-rw-r--r-- 1 username groupname 0 Jun 9 14:15 file1.txt

# Comment: On real Linux systems, this would change to -rwxr--r--. On Windows, this effect is not visible.


## Conclusion:
Practiced using chmod for owner, group, others.
