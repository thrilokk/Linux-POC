How to create new user in Linux enviornment

The most common way to create a new user in linux by using the command

- Command: sudo useradd priya

![alt text](image.png)
- it will ask password to enter 

- or

- if its dont ask, please enter password like this sudo passwd priya and enter password.

- To switch between users you can use this command- su thrilokk and it will switch to another user

In Linux, file permissions are represented in two ways: symbolic and numeric notation. Both methods serve the same purpose: defining who can access a file or directory and what they can do with it. 

The below table refer about numeric Nottaion permission 

| Number  |	Permission |
| -----   | ---------- |
| 0	      | ---        |
| 1	      | --x        |
| 2	      | -w-        |
| 3	      | -wx        |
| 4	      | r--        |
|5	      | r-x        |
|6 	      | rw-        |
|7	      | rwx        |

The below refer symbolic notation

Symbolic notation uses letters to represent permissions.

- r: Read permission
- w: Write permission
- x: Execute permission

The letters are precedd by a character indicating who the permission applies to 

- u: User(Owner of the file)
- g: Group
- o: Others(everyone else)

Example: for symbolic notation

- chmod u+x file.txt: Adds execute permission for the user to file.txt
- chmod go-w directory: Removes write permission for group and others on the directory

- Understanding the Symbols

u: User (owner of the file)
g: Group (group the file belongs to)
o: Others (all other users)
a: All (user, group, and others)
+: Add permission
-: Remove permission
=: Set permission
r: Read permission
w: Write permission
x: Execute permission
