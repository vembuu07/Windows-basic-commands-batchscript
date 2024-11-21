# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# NAME: Vembarasan
# REG NO: 212223220123
# AIM
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/0137c8da-104a-4592-9d21-94a3068eb069)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/1b74cad8-d3c5-4727-9be9-3639e1714d60)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/29497d6e-478f-4d85-ab7b-fce449cdeea6)


Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/39586b4e-72d4-4bea-9fdf-c068791f53a1)


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/3791b3f7-9eb3-42e2-b2dd-b688197ab4ac)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:

```txt
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT

![image](https://github.com/user-attachments/assets/17a3725f-dea2-42b2-9209-2d022265e10c)




# RESULT:
The commands/batch files are executed successfully.
