# Windows-basic-commands-batchscript

# Ex08-Windows-basic-commands-batchscript

## AIM :

To execute Windows basic commands and batch scripting

## DESIGN STEPS :

### Step 1 :

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2 :

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3 :

Execute the necessary commands/batch file for the desired output. 

```
DEVELOPED BY : DILIP MP
REG NO : 212223230048
```
## WINDOWS COMMANDS :
## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT :

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![Screenshot 2024-04-27 091411](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/708655da-fe73-49da-9599-ec1597ccbce2)


## COMMAND AND OUTPUT :

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab

![Screenshot 2024-04-27 091507](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/875b70b2-5b3e-40c1-b565-51d7a6270a30)
![Screenshot 2024-04-27 091537](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/a56dc6d9-b4ec-4dc0-8f83-e33466b9cdce)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![Screenshot 2024-04-27 091622](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/6cf8bb16-bb75-4bb5-9926-e0ade3c21438)

## COMMAND AND OUTPUT :

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![Screenshot 2024-04-27 091710](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/20628e44-4610-4038-8116-56a140d128e5)

![Screenshot 2024-04-27 091748](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/43b703ff-8fde-4ea5-a7a0-38e3ab507582)



## COMMAND AND OUTPUT :

mv Myfile.txt %userprofile%\Documents
![Screenshot 2024-04-27 091829](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/f440e49d-7ca2-4903-acb3-8cfacca12b54)

## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT :
![Screenshot 2024-04-27 091914](https://github.com/DilipDofy/Windows-basic-commands-batchscript/assets/147223497/440c7efe-2b49-46f4-9843-c6493a0a987a)

## RESULT :
The commands/batch files are executed successfully.

