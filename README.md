# PasswordChecker
Checks if your password has been hacked

Python Version: **Python 3.8.10**

**To install python:**
  * Visit https://www.python.org/downloads/release/python-3810/ for more information

**Install Dependencies**
  * Install Requests:
    >     python -m pip install requests

**How to use:**
  * Open your terminal
* Navigate to the directory that contains the **checkMyPassword.py** file
  * Run the following command:
    >     python checkMyPassword.py {your_password_here} {another_password}
  * Replace {your_password} with a password you choose to test:
  * eg:
    >     python checkMyPassword.py P@ssw0rd 'P@ss123'
  * Example Response:
    >     P@ssw0rd was found 83846 times... You should probably change your password!!!
    >     P@ss123 was found 263 times... You should probably change your password!!!
    >     done!
    
  * Response will return how many times your password has been hacked or if it is secure

**NOTES:**
  * Your actual password does not get sent to the API
  * Your password gets HASHED with SHA1 and then only send the first 5 characters
  * Passwords get matched locally

**Be safe and NEVER share your passwords**
