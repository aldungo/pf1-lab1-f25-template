# Programming Fundamentals CSCI 1436
## Week of Jan 19
## Professor Dungo

## Welcome to In-Class 1/ Lab 1

**Purpose:** The first lab assignment is an opportunity to test your GitHub Classroom environment, making sure you understand how to begin writing programs using a codespace. This will also be your first look at variables, which will be a fundamental part of all your programs.

**Learning Objectives:**
- Navigate GitHub Codespaces
- Compile and run Java programs
- Declare and assign String variables
- Use System.out.println() for output

### Step 1: Accept the Assignment
You have already done this by creating your repository!

### Step 2: Access Your Codespace
Click the green "Code" button, select the "Codespaces" tab, and click "Create codespace on main".

### Step 3: Explore Your Workspace
On the left side, you will see the file explorer. Locate the `README.md` (this file) and the Java source files.

## Understanding Variables

**In-Class 1:** Variables are used to hold values in your programs. This allows you to set the value once and use that value many times later. For example, a String variable is used to hold a sequence of characters (think of it like a string of words). Instead of rewriting that sequence of characters repeatedly, you only need to use the variable.

To make this String variable, you must declare it. This variable declaration looks like the following:

```java
String message;
```

This includes the String type, the name of the variable, and the terminating semi-colon. There are rules about variable names to learn later, but you can effectively name the variable whatever you like. To give this variable a value, you must assign that value to it. This variable assignment looks like the following:

```java
message = "Welcome to Java!";
```

The equals sign is known as the assignment operator. The variable is placed on the left-hand side, and the value is placed on the right-hand side. Also notice that you do not specify the String type. That type only ever needs to be stated when you declare the variable. Once this variable has a value, you can now use it. The simplest use-case for a String is to print it:

```java
System.out.println(message);
```

Variables are placed into statements in order to use them, such as the placement of the message variable in this print statement. You will learn more about the rules for placing variables into statements later. And again, remember that you do not specify the String type when using a variable.

## Try Me: In-Class Example

Before you start the main lab, try this quick exercise in your codespace:

1. Open the Java file named `InClass1_FirstName_LastName.java` (replace with your name). Be sure to change this in the class header as well, on Line 9. 
2. Inside the file, declare a String variable, assign it a value (like your favorite quote or greeting), and print it to the console.
3. Run your program to see the output.

This is a simple way to practice using variables and printing output before you begin the full lab assignment below.

## Lab Assignment Instructions

### Task Overview
For this lab only, the Java file is already created for you, named `Lab1_FirstName_LastName.java`. Replace FirstName and LastName with your actual name, and do the same in the class header on Line 9. **Note:** In future labs, you will be responsible for creating the `.java` file yourself, including writing the correct class and method headers. This is an important skill for building your own programs from scratch.

**Example:** If your name is John Smith, create `Lab1_John_Smith.java`

### Step-by-Step Instructions for Lab1.java

#### Step 1: Open Your Java File
The file `Lab1_FirstName_LastName.java` is already created for you. Make sure to update the filename and class name with your actual first and last name.

#### Step 2: Add File Header and Class Structure
Fill in the header comments at the top of the file with your name, today's date, and a brief purpose statement. Confirm the class name matches your filename.

#### Step 3: Declare a String Variable
Inside the `main` method, declare a String variable. Choose a meaningful name, such as `message`, `statement`, or `whyStatement`.

#### Step 4: Assign a String Value
Assign a value to your variable. Write a sentence about why you want to be a programmer or your goals for this course.

#### Step 5: Display the Variable
Use `System.out.println()` to print your variable to the console.

#### Step 6: Add Your Own Comment
Add at least one comment in your code explaining what your code does or why you wrote it that way. This helps build good habits for future labs.

### Sample Program Structure
```java
/**
 * Name: [Your Name]
 * Date: [Today's Date]
 * Purpose: Lab 1 - Introduction to Variables and GitHub Classroom
 */

public class Lab1_YourFirstName_YourLastName 
{
    public static void main(String[] args) 
    {
        // Declare a String variable
        
        // Assign your personal statement to the variable
        
        // Print the variable to the console
    }
}
```


## Running Your Program

### Method 1: Using the Terminal
1. Open the terminal in your codespace (Terminal → New Terminal)
2. Compile your program:
   ```bash
   javac Lab1_YourFirstName_YourLastName.java
   ```
3. Run your program:
   ```bash
   java Lab1_YourFirstName_YourLastName
   ```

## Testing Your Program

### What Should Happen
When you run your program, you should see your personal statement printed to the console. For example:

   I want to learn how to solve real-world problems with code.

If you see your message, your program is working correctly!

**For every lab, you will take a screenshot of Terminal Output. This allows me to verify that I see what you do! You can paste or save this image to your file repository on the left.**

### Troubleshooting Common Issues
- **Compilation errors:** Check that your filename, class name, and method headers match the instructions. Make sure you end statements with a semicolon.
- **No output:** Confirm you used `System.out.println()` and assigned a value to your variable.
- **Wrong filename/class name:** Both should use your actual first and last name, and match each other.
- **Typos:** Double-check spelling, capitalization, and punctuation.

## Commit Your Changes
### Step 1: Stage and Commit
1. Use VS Code's Source Control panel:
   - Click the Source Control icon in the left sidebar
   - Type a commit message (e.g., "Completed Lab 1")
   - Click "Commit"

### Step 2: Sync Changes
   - Click "Sync Changes" to push your code to GitHub.

### Step 3: Verify Submission
After pushing your changes, visit your assignment repository on GitHub Classroom. Confirm that your latest code and commit message appear, and that your files are named correctly. You should also see the addition of the screenshot image you added. 

### Step 4: Submit to Blackboard Assignment
Once you have verified your submission on GitHub Classroom, copy the URL of your assignment repository and submit this GitHub repository link to Blackboard as confirmation that you are DONE.

## Grading Criteria

**Lab1.java (100 points total):**
Criteria: Make sure you have the following in your program:

• String declaration (30 points)

• String assignment (40 points)

• println() statement (30 points)


**InClass1.java (Participation points):**
Full credit is awarded for completing and submitting the in-class exercise, regardless of output or minor errors.

**Remember:** This is your first programming assignment! Take your time, ask questions, and don't worry if it takes a few tries to get everything working. The goal is to learn the process and get comfortable with the tools you'll be using throughout the course.

**Important:** Do NOT edit or tamper with any files besides the .java files you are instructed to. If something doesn't look right, you accidentally deleted the instructions, or anything else - don't worry! Most things are undoable. Ask questions and reach out!