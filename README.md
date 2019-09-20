SecureSet Academy
=================================================

## Login Script

#### Group: Andrew Galvin, Amilcar Spezia, Alex White, Steven Wilkins


### Modules
```
main/
├── login.py
├── loginInfo.text
└── 10K-common-passwords.txt
```
#### `login.py`
This is the main file that contains the login script

#### `loginInfo.txt`
This file contains all the usernames and salted/hashed passwords

#### `10k-common-passwords.txt`
This file contains the 10K most common paswwords to compare against

### Running the app

* Run `./login.py`

### Psuedo Code

#### Login script
1. PEP 8 standards for format `-Amilcar`
2. 3 validation functions - `Andrew`
3. Try/except statement - `Steven`
4. Ability to log info of any type. Must include login levels - `Alex`

#### Login script
* Username - function
* Password - function
* dictionary
* 5 attempts
* Stretch goal: timeout 30s, 2 mins, 10 mins, etc.

#### PEP 8
* Python Enhancement Proposal.Makes your code more organized and readable. 
* Use 4 spaces per indentation level.
* Spaces are the preferred indentation method.
* Pick a rule and stick to it when a string contains single or double quote characters.
* limit all lines to 79 chars max.
* Comments should have 72 characters of line length. 


#### Validation
* password validation - 1 capital letter, 1 special characer, 1 number,
* regular expression
* 8 char min, 24 char max
* No show password
* prevent certain characters
* \n, SELECT,

#### Try/except
* Try/except instead of while loops
* Try to validate
* Try to login

#### Logs
* Succesful login
* log for exempt characters
* log for attempts(5)
* log to sys
* log to file


### Login Script
This is a basic paragraph about the login script
* This is basic bullet point

### PEP8 Standards
This is a basic paragraph about PEP8 Standards
* This is basic bullet point

### Validation
We used 3 basic validation functions in our login script. The password mustbe between 5-25 characters, contain a capital letter and must not contain \n. We picked these 3 functions to sanitize the password in the best way for our purpose.
*\n
*Uppercase character
*5-25 characters

### Try/Except
This is a basic paragraph about Try/Except
* This is basic bullet point

### Logs
This is a basic paragraph about Log
* This is basic bullet point

### References
* 
* 
