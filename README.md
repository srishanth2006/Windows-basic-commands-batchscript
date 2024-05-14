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

DEVELOPED BY : SHANMUGA RAJ.K <br>REG NO : 212223040192



# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
```
mkdir %userprofile%\Desktop\MyLab
```

<img width="475" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/25bcfdfb-fe09-4cbe-be9e-6a090521bb9c">



Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```
<img width="434" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/2ce767e7-8c06-461c-a5f9-f26b581ed266">
```
type nul > MyFile.txt
```

<img width="464" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/3aa80ec0-c738-4afd-b0de-9d7fc2d73e3d">

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```

<img width="542" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/33d216fa-a207-49a0-bb0e-20cfec616dba">

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
```
<img width="533" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/2723c481-f3d2-4fd7-be75-3f710ba9c0d9">
```
copy MyFile.txt %userprofile%\Desktop\Backup
```
<img width="556" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/032194cc-33eb-4cea-a5db-813e1bb9fec7">

## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```

<img width="553" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/67af9b36-9929-432d-963d-cab6fdf8c1a1">




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
## OUTPUT
<img width="556" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/8991ebe5-1ac1-4c3f-a68e-2b696fdde8ed">

Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

<img width="557" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/90cd6c02-2e9e-4b87-b86c-5d68df5bfe8a">


# RESULT:
The commands/batch files are executed successfully.

