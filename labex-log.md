# LabEx Practice Log

## 2026-02-16
Lab: Linux xargs command

Commands:
xargs
| pipe first command into second ~/project/file_archive.txt
The -n option of xargs allows us to limit the number of arguments passed to each command execution
-I {} tells xargs to replace occurrences of {} in the command with each input line

Key Takeaway:
Learned how to use the xargs command to automate file management tasks.

Difficulty:
Easy

Real Use Case:
Organising archives/databases, for example, making folders for each each line of text in a file