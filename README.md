# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
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
```
  mkdir %userprofile%\Desktop\MyLab
```
<img width="556" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/e9f82d79-62ec-487d-a846-8eac83572012">


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
cd %userprofile%\Desktop\MyLab
```
<img width="557" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/cf654e0c-4128-42b5-81a3-617da1a2b6a2">
<img width="557" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/e776703c-d238-4c8b-91c4-08afbb92609a">


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

```
cd %userprofile%\Desktop\MyLab
```
<img width="557" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/cf654e0c-4128-42b5-81a3-617da1a2b6a2">
<img width="557" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/e776703c-d238-4c8b-91c4-08afbb92609a">


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```

dir %userprofile%\Desktop\MyLab


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







## OUTPUT





# RESULT:
The commands/batch files are executed successfully.

