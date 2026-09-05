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
Create a directory named "my-folder"

## COMMAND AND OUTPUT

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="602" height="185" alt="Screenshot 2026-09-03 202053" src="https://github.com/user-attachments/assets/ad750411-da10-4d58-b100-ca2d60ce59ce" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="695" height="377" alt="Screenshot 2026-09-03 092152" src="https://github.com/user-attachments/assets/30623b2c-7b16-4d25-ac75-791b5e98ea20" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="762" height="108" alt="Screenshot 2026-09-03 091920" src="https://github.com/user-attachments/assets/6a07523a-dfb6-408c-aea1-95450a6d12e0" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="645" height="190" alt="Screenshot 2026-09-03 092208" src="https://github.com/user-attachments/assets/b3f4ea60-15c0-4152-9ccc-efd46551eb8d" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="592" height="272" alt="Screenshot 2026-09-03 092014" src="https://github.com/user-attachments/assets/b90bc56d-d348-4220-a41f-4b505a9cefa2" />
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="592" height="272" alt="Screenshot 2026-09-03 092014" src="https://github.com/user-attachments/assets/56ef5546-7646-4adb-bd6d-9917b1d7924e" />

List out all the associated file extensions 

## COMMAND AND OUTPUT


<img width="551" height="560" alt="Screenshot 2026-09-03 092033" src="https://github.com/user-attachments/assets/b62ab8f0-daaa-4a5a-8183-e19fbb0128d0" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="466" height="243" alt="Screenshot 2026-09-03 092133" src="https://github.com/user-attachments/assets/816a0f51-fbfc-4651-8cc4-27311e2ed71a" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="507" height="86" alt="Screenshot 2026-09-03 092647" src="https://github.com/user-attachments/assets/615a6337-d5fa-4cd1-aac9-2befc99213ce" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="592" height="112" alt="Screenshot 2026-09-03 092810" src="https://github.com/user-attachments/assets/369e2418-0d84-4e39-ac50-95ddf1100d15" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="497" height="223" alt="Screenshot 2026-09-03 100344" src="https://github.com/user-attachments/assets/80641dee-72d8-4443-ac4a-3a8c19ebed8b" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="468" height="91" alt="Screenshot 2026-09-03 100440" src="https://github.com/user-attachments/assets/098d7644-9a26-4b85-a22d-26a1819828e7" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="542" height="486" alt="Screenshot 2026-09-03 100654" src="https://github.com/user-attachments/assets/d8e683f7-1a43-49ff-bbe3-a75b210c346f" />



# RESULT:
The commands/batch files are executed successfully.

