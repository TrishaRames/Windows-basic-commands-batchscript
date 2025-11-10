# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

```
mkdir %userprofile%\Desktop\MyLab
```
<img width="707" height="51" alt="image" src="https://github.com/user-attachments/assets/77ca6559-d49f-4f7f-b25c-74e3fa534423" />

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```
<img width="707" height="51" alt="image" src="https://github.com/user-attachments/assets/e6a953f9-7323-4daf-83ec-e0abead91d21" />

type nul > MyFile.txt
<img width="698" height="101" alt="image" src="https://github.com/user-attachments/assets/99d69682-2bb1-40a1-a604-c3caacb43ce1" />


## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```
<img width="815" height="321" alt="image" src="https://github.com/user-attachments/assets/7df860ff-f673-4fa1-8785-d96ba62ab642" />

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
<img width="925" height="143" alt="image" src="https://github.com/user-attachments/assets/e2ea3acb-7de4-4e5b-9f62-c0323c212bd6" />

Move the "MyLab" directory to the "Documents" folder.
## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents
```
move MyLab Documents
## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

## COMMAND AND OUTPUT
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
<img width="891" height="223" alt="image" src="https://github.com/user-attachments/assets/2a5e18fc-7ba8-435b-9b12-bf18592a7b76" />

# RESULT:
The commands/batch files are executed successfully.

