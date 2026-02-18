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
<img width="861" height="101" alt="image" src="https://github.com/user-attachments/assets/3ab4417a-75bd-4401-b8a0-1c7da13d4e4b" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="939" height="105" alt="image" src="https://github.com/user-attachments/assets/2229b33b-e006-4f06-95bf-44cd2ed28ca9" />


## COMMAND AND OUTPUT

Create the file Rose.txt
<img width="976" height="65" alt="image" src="https://github.com/user-attachments/assets/949aea33-a83e-40d8-9c28-c1aa2c70630f" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection
<img width="1063" height="36" alt="image" src="https://github.com/user-attachments/assets/aaa8361d-3b34-4285-a5ba-8f7776c12f5d" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="990" height="115" alt="image" src="https://github.com/user-attachments/assets/5adbc775-f471-4541-879b-1446606c9b86" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="848" height="85" alt="image" src="https://github.com/user-attachments/assets/01097d14-c0ce-4803-9792-b98a305b557e" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="944" height="184" alt="image" src="https://github.com/user-attachments/assets/c5f6667c-88f3-4760-95b3-7d8c50058afc" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="788" height="1064" alt="image" src="https://github.com/user-attachments/assets/b7c03e5e-41c2-4919-898a-ffb9883e9720" />
<img width="1059" height="1089" alt="image" src="https://github.com/user-attachments/assets/7f8264b9-35be-4495-aa27-261b8696a80e" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt
<img width="948" height="161" alt="image" src="https://github.com/user-attachments/assets/a3399719-dd6b-45fb-b2ee-499231a36bc2" />



## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT
<img width="510" height="97" alt="image" src="https://github.com/user-attachments/assets/820a65f9-80db-4407-bdd6-a8283b837dde" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="591" height="231" alt="image" src="https://github.com/user-attachments/assets/f1e3ed64-e43b-47e8-9e33-1f558f13f355" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="433" height="197" alt="image" src="https://github.com/user-attachments/assets/07f0713f-870a-48a4-87cd-bff6ce6f2b36" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="412" height="62" alt="image" src="https://github.com/user-attachments/assets/602fc7ed-b506-4ead-a95f-bdb9666a7bf5" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="380" height="159" alt="image" src="https://github.com/user-attachments/assets/7f54050a-c5d9-4ec9-9059-c53558550ad0" />



# RESULT:
The commands/batch files are executed successfully.

