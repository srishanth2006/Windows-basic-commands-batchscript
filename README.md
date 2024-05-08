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

<img width="608" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/42889211-6926-485b-98c4-0618fc65ff65">


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```
<img width="578" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/7bc66f40-2c28-4cde-8421-32fbc1cd7cb0">


<img width="570" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/f5e219e7-c493-4019-802e-3d5f1181a9e4">



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```

<img width="539" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/e0da1b72-ee9d-42f6-aee7-d6af77816408">

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```
<img width="524" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/7a255209-33f6-41de-9e16-fdeaa96e625d">


<img width="677" alt="image" src="https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/fd63cf21-915f-4a0d-b7ec-4c2744921039">

## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```

![image](https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/96bc25c5-7331-4f49-b3d4-a70b3ab28bf3)




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![image](https://github.com/srishanth2006/Windows-basic-commands-batchscript/assets/150319470/cba00f83-1281-41e6-b4ec-a357ef2557d7)



# RESULT:
The commands/batch files are executed successfully.

