# Text Processing commands in UNIX 

## Tail - command
1. List bottom/recently appended n records in a file

### " -n" prints the last "n" number of lines in the file.
   - Example: tail 3 day1 and here n = 3, which means numbers.
  
   <img width="301" alt="image" src="https://github.com/user-attachments/assets/11ee7ad4-9dae-4765-80cd-3734af8d83c2">
   
### " -c " command tells no of characters in file and from end to it will calculate
  - Example: tail -c 30 day1 
<img width="335" alt="image" src="https://github.com/user-attachments/assets/a917e8e5-aca3-475b-aa41-75c37297f280">

### "-f" follow the changes in the file it means constantly watches the file 
  - Example: tail -f day1
<img width="365" alt="image" src="https://github.com/user-attachments/assets/3774f8d8-26fd-4438-b1b4-dcf60f4b33aa">


