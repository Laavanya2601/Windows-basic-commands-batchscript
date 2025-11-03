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
<img width="621" height="125" alt="Screenshot 2025-11-03 114229" src="https://github.com/user-attachments/assets/7705340c-af9f-4d1e-8d42-853d863e84d0" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="670" height="133" alt="Screenshot 2025-11-03 114305" src="https://github.com/user-attachments/assets/f2d7d5c8-c690-44a7-8859-7a1ecb378f6e" />


## COMMAND AND OUTPUT


Create the file Rose.txt



## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="848" height="66" alt="Screenshot 2025-11-03 114359" src="https://github.com/user-attachments/assets/4b532ede-52cc-4321-b66e-8c9db08bf045" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="723" height="166" alt="Screenshot 2025-11-03 114422" src="https://github.com/user-attachments/assets/44b7141f-4870-44bc-8c7d-56dca2dd5cc4" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="753" height="115" alt="Screenshot 2025-11-03 114444" src="https://github.com/user-attachments/assets/b0dbd160-0274-4fdc-a182-5c851917291a" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="612" height="200" alt="Screenshot 2025-11-03 114508" src="https://github.com/user-attachments/assets/faf9d294-3156-4714-b56b-051fc6dcac50" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="639" height="1053" alt="Screenshot 2025-11-03 114543" src="https://github.com/user-attachments/assets/051f748f-26ae-42f7-98b5-8733da356bb4" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="663" height="168" alt="Screenshot 2025-11-03 114605" src="https://github.com/user-attachments/assets/9cce9790-921d-47a9-94b5-d90e52b7f443" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

