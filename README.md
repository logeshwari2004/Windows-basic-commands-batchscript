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


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![326150191-c206b1a2-a6cd-4a05-8be1-0e757209c1bd](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/47f83def-a9af-422b-b6e6-ff1667a12c66)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![326150288-4b447d26-41f7-404f-9b36-abeade389383](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/e2b6f21e-03c9-40ab-b324-a0516370af36)

![326150304-5fdde096-136f-429f-b875-df720b5ace5f](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/be896f17-f328-4c2f-bae3-beebb2d67f3d)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![326150376-d7c09055-e3c0-40a6-acc8-9c7a0d074a87](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/1a37454a-44c7-49d1-978a-46f20bd67e96)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![326150376-d7c09055-e3c0-40a6-acc8-9c7a0d074a87](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/f9afedd0-0a6f-4380-b1db-8856be1435fb)


## COMMAND AND OUTPUT
![326150461-7ec9d35f-de3b-471f-a9ca-6f2a6d423eb2](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/71668238-a37b-4fbf-861b-56e4084d0944)
![326150446-b745898c-a420-4802-8b01-515134b5f90a](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/20c469d4-9e19-4b01-b210-e822477efac8)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!





## OUTPUT
![326150530-404d9504-2a72-4f94-aaed-bc617279bb62](https://github.com/logeshwari2004/Windows-basic-commands-batchscript/assets/94211349/098b1286-910f-4e6f-8604-dd6c26190fa4)





# RESULT:
The commands/batch files are executed successfully.

