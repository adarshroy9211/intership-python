#  Python Script: Validate User Input (Name & Email)

##  What I Built

This is a **basic Python script** that takes user input for:
- **Name**
- **Email**

It performs simple **validation checks**:
- Both fields must **not be empty**
- Email must contain an **'@'** symbol

The script then prints a message based on the result:
-  Success if inputs are valid
-  Error if any validation fails

This script is ideal for internship tasks, assignments, or beginner practice.

---

##  Tools Used

- **Python 3.x** – Programming language
- **Visual Studio Code** or any text editor – For writing the code
- **Terminal / Command Prompt** – For running the script

---

##  How to Run It

### Step 1: Save the Script
1. Open your code editor (e.g., VS Code)
2. Create a new file named: `validate_input.py`
3. Paste the following code:

```python
# Internship Task: Collect and Validate User Input (Name & Email)

def validate_input(name, email):
    if not name or not email:
        return " Error: Both fields are required."
    if "@" not in email:
        return " Error: Email must contain '@'."
    return f" Received data: Name - {name}, Email - {email}"

# Take input from user
name = input("Enter your name: ").strip()
email = input("Enter your email: ").strip()

# Validate and print result
result = validate_input(name, email)
print(result)
Step 2: Run the Script
Open your terminal or command prompt

Navigate to the folder where your validate_input.py file is saved

Run the script using:

bash
Copy
Edit
python validate_input.py
Use python3 instead of python if needed on your system.

 Example Output
 Valid Input

kotlin
Copy
Edit
Enter your name: Adarsh
Enter your email: adarsh@example.com
 Received data: Name - Adarsh, Email - adarsh@example.com
 Invalid Email

yaml
Copy
Edit
Enter your name: Roy
Enter your email: royexample.com
 Error: Email must contain '@'.
 Missing Fields

yaml
Copy
Edit
Enter your name:
Enter your email:
 Error: Both fields are required.
 Optional Extensions
Add stricter email validation using re (regex)

Log data to a .txt or .csv file

Build a GUI using tkinter

Add input loops 

https://github.com/user-attachments/assets/0a5daa3d-5147-4aec-a6e1-0ea78738512a

or multiple entrie
