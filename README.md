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
<img width="511" height="73" alt="Screenshot 2025-11-10 052603" src="https://github.com/user-attachments/assets/37c8d4d1-bf14-426d-bfd5-cbb36823859e" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="509" height="72" alt="Screenshot 2025-11-10 052617" src="https://github.com/user-attachments/assets/dda730a8-3d0b-4e1f-81f2-5beecfe91350" />

## COMMAND AND OUTPUT


Create the file Rose.txt
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z
1 file(s) copied
dir Rose.txt

<img width="762" height="356" alt="Screenshot 2025-11-10 052647" src="https://github.com/user-attachments/assets/b6b8bb34-1bc8-47ad-a648-88b00b6d65ad" />


## COMMAND AND OUTPUT
echo “hello world” > hello.txt
type hello.txt


Create the file hello.txt using echo and redirection

<img width="671" height="115" alt="Screenshot 2025-11-10 052706" src="https://github.com/user-attachments/assets/229e1832-3883-4a3c-a545-d6fee363a291" />


## COMMAND AND OUTPUT
copy hello.txt hello1.txt
Copy the file hello.txt into the file hello1.txt

<img width="599" height="159" alt="Screenshot 2025-11-10 052727" src="https://github.com/user-attachments/assets/fb78dc7d-90e5-423e-9275-f2bb15dfc487" />

## COMMAND AND OUTPUT
del hello1.txt
dir hello1.txt

Remove the file hello1.txt
<img width="528" height="196" alt="Screenshot 2025-11-10 052736" src="https://github.com/user-attachments/assets/2fdc8f8b-6a91-412f-a5db-35a921dbafa8" />



## COMMAND AND OUTPUT
assoc | more

List out the file hello1.txt in the current directory

<img width="494" height="379" alt="Screenshot 2025-11-10 052747" src="https://github.com/user-attachments/assets/9a0c0d49-491d-4491-b3e3-1edd7eddd343" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

fc hello.txt Rose.txt


<img width="581" height="243" alt="Screenshot 2025-11-10 052758" src="https://github.com/user-attachments/assets/43489302-50eb-4fa7-9da1-9299713ca052" />





## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="465" height="143" alt="Screenshot 2025-11-10 053719" src="https://github.com/user-attachments/assets/0db01942-9937-415a-ac5d-2bf3802dd3bc" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="615" height="348" alt="Screenshot 2025-11-10 053730" src="https://github.com/user-attachments/assets/765660ed-f5e8-4b17-8660-2354c4404863" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="482" height="247" alt="Screenshot 2025-11-10 053738" src="https://github.com/user-attachments/assets/e5aee7ee-d64e-4ed4-a3fc-9b0acf46abcf" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="743" height="283" alt="Screenshot 2025-11-10 053757" src="https://github.com/user-attachments/assets/f485b3c7-db4c-46eb-b69c-1096a752a260" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="451" height="414" alt="Screenshot 2025-11-10 053805" src="https://github.com/user-attachments/assets/19e2bc35-9aa5-4fca-9d40-b10638d2f685" />


# RESULT:
The commands/batch files are executed successfully.

