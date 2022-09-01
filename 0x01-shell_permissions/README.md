<h1> Shell, Permissions </h1><br/>
1. 0-iam_betty - The script switches the current user to the user betty.<br/>
2. 1-who_am_i - Prints the effective username of the current user.<br/>
3. 2-groups - Prints all the groups the current user is part of.<br/>
4. 3-new_owner - Changes the owner of the file hello to the user betty.<br/>
5. 4-empty - Creates an empty file called hello.<br/>
6. 5-execute - Adds execute permission to the owner of the file hello<br/>
7. 6-multiple_permissions - Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.<br/>
8. 7-everybody - Adds execution permission to the owner, the group owner and the other users, to the file hello.<br/>
9. 8-James_Bond - Write a script that sets the permission to the file hello as follows:<br/>Owner: no permission at all.<br/>- Group: no permission at all.<br>- Other users: all the permissions<br/>
10. 9-John_Doe - Write a script that sets the mode of the file hello to this:<br/>-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello<br/>
11. 10-mirror_permissions - Sets the mode of the file hello the same as olleh’s mode.<br/>- The file hello will be in the working directory.<br/>- The file olleh will be in the working directory<br/>
12. 11-directories_permissions - Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.<br/>
13. 12-directory_permissions - Creates a directory called my_dir with permissions 751 in the working directory.<br/>
14. 13-change_group - Changes the group owner to school for the file hello<br/>
