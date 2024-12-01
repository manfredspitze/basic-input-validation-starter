# basic-input-validation-starter

### Getting Started
  
- Create a GitHub repo named: **input-validation-starter**
    - Upload your project files to the repo
    - **No need to share your repo with your teacher**
    - Teacher will discuss your work with you **during Teacher Time**
---

### Coding Tasks

#### Task 1: Validate String Input Using `isalpha( )` Method

- Write a simple script that prompts the user to enter their last name
- Use an `if-else` statement and the `isalpha( )` string method to check if the user's input string contains **only** letters
- Let the user know if their input string contains -- or doesn't contain -- only letters

#### Task 2: Validate String Input Using `len( )` Function

- Write a script that prompts the user to enter a password
- The minimum length of a **valid** password is 8 characters
- Use the `len( )` function to count the number of characters in the user's password
- If the password meets the minimum length requirement, tell the user that their password is at least 8 characters long; otherwise, warn the user that their password is too short

#### Task 3: Is The User's Input String an Empty String?

- Write a simple function named `check_username ( )` that takes one parameter, `username`
- Add an `if-else` statement to the function body
  - if the user passes (sends) an **empty string** to the function (when the function is called), **return** a warning that the user must enter a username
  - otherwise, **return** a message that displays the username the user entered
- Outside the function, define a variable `my_username` and assign it an **empty string**  (check how to do this online if you don't know how to create an empty string in Python)
- Then define another variable, `message` and assign the function call to your `message` variable; use the variable `my_username` as an argument when calling the function
- Print the contents of the `message` variable
