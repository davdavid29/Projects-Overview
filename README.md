
# Projects
Welcome to my portfolio! Here, I document a summary of my various projects.

## Table of Contents
1. [University Projects](#university-projects)
2. [SQL Projects](#sql-projects)
3. [Python Projects](#python-projects)
4. [Data Engineering](#data-engineering)
5. [FAQs](#faqs)

### University Projects
#### Computer Engineering Projects
| Project Name & Link | Project Description | Year | Course  | Tools/Software |
|--|--| --| -- | -- |
| [MATLAB GUI Keypad with DTMF Tones and Frequency Filtering](https://github.com/davdavid29/Projects/tree/main/University%20Projects/MATLAB%20GUI%20Keypad%20with%20DTMF%20Tones%20and%20Frequency%20Filtering) | In this project, I use MATLAB's GUI functionality to design a keypad with buttons that are each assigned a unique DTMF tone. We also incorporate three graphs that display the DTMF input, filtered low frequency signal, and filtered high frequency signal. This project showcases the use of MATLAB's GUI capabilities and signal processing techniques. | 2021 | CPE 166 – Digital Signal Processing | MATLAB |
| [Calculator Program with VB.NET 10](https://github.com/davdavid29/Projects/tree/main/University%20Projects/Calculator%20Program%20with%20VB.NET%2010) | This code implements a basic calculator program with a graphical user interface (GUI) created using Visual Basic 2010. The program allows the user to perform arithmetic operations such as addition, subtraction, multiplication, and division on two numbers. It also includes a button to clear the current calculation and start over. The GUI includes textboxes to enter the two numbers and display the result, as well as buttons for each arithmetic operation. The program uses simple if-else statements to determine which operation the user wants to perform and performs the calculation accordingly. | 2020 | CPE 114_K12 – Software Design | Microsoft Visual Basic 2010 Express |
| [Student Record Management System Code in C++](https://github.com/davdavid29/Projects/tree/main/University%20Projects/Student%20Record%20Management%20System%20Code%20in%20C%2B%2B) | This project implements a basic student record management system that allows the user to add, search, edit, and delete student records. The program stores the student's ID, course, name, age, and gender in a struct and can store up to five records. It uses a switch statement to determine which option the user chooses and uses loops to iterate through the student records. The program outputs the student records to the console. | 2019 | CPE 113_K12 – Data Structure & Algorithms | Dev C++ |
| [ATM Machine Code in Java Swing GUI with MySQL Database](https://github.com/davdavid29/Projects/tree/main/University%20Projects/ATM%20Machine%20Code%20in%20Java%20Swing%20GUI%20with%20MySQL%20Database) | This project implements a basic ATM machine using Java Swing GUI and a MySQL database through the use of the phpMyAdmin web application. The user can input their account number and PIN, withdraw or deposit money, and check their account balance. The program connects to a MySQL database to store account information and transactions. It uses event listeners to detect button clicks and perform corresponding actions. The program displays account information and transaction history in the GUI. | 2019 | CPE 112_K12 – Object Oriented Programming | Netbeans and phpMyAdmin (for MySQL Database administration) |

### SQL Projects

### Python Projects

### Data Engineering

### FAQs
# Projects
Welcome to my portfolio! Here, I document a summary of my various projects.

## Table of Contents
1. [University Projects](#university-projects)
2. [SQL Projects](#sql-projects)
3. [Python Projects](#python-projects)
4. [Data Engineering](#data-engineering)
5. [FAQs](#faqs)

### University Projects
#### Computer Engineering Projects
| Project Name & Link | Project Description | Year | Course  | Tools/Software |
|--|--| --| -- | -- |
| [MATLAB GUI Keypad with DTMF Tones and Frequency Filtering](https://github.com/davdavid29/Projects/tree/main/University%20Projects/MATLAB%20GUI%20Keypad%20with%20DTMF%20Tones%20and%20Frequency%20Filtering) | In this project, I use MATLAB's GUI functionality to design a keypad with buttons that are each assigned a unique DTMF tone. We also incorporate three graphs that display the DTMF input, filtered low frequency signal, and filtered high frequency signal. This project showcases the use of MATLAB's GUI capabilities and signal processing techniques. | 2021 | CPE 166 – Digital Signal Processing | MATLAB |
| [Calculator Program with VB.NET 10](https://github.com/davdavid29/Projects/tree/main/University%20Projects/Calculator%20Program%20with%20VB.NET%2010) | This code implements a basic calculator program with a graphical user interface (GUI) created using Visual Basic 2010. The program allows the user to perform arithmetic operations such as addition, subtraction, multiplication, and division on two numbers. It also includes a button to clear the current calculation and start over. The GUI includes textboxes to enter the two numbers and display the result, as well as buttons for each arithmetic operation. The program uses simple if-else statements to determine which operation the user wants to perform and performs the calculation accordingly. | 2020 | CPE 114_K12 – Software Design | Microsoft Visual Basic 2010 Express |
| [Student Record Management System Code in C++](https://github.com/davdavid29/Projects/tree/main/University%20Projects/Student%20Record%20Management%20System%20Code%20in%20C%2B%2B) | This project implements a basic student record management system that allows the user to add, search, edit, and delete student records. The program stores the student's ID, course, name, age, and gender in a struct and can store up to five records. It uses a switch statement to determine which option the user chooses and uses loops to iterate through the student records. The program outputs the student records to the console. | 2019 | CPE 113_K12 – Data Structure & Algorithms | Dev C++ |
| [ATM Machine Code in Java Swing GUI with MySQL Database](https://github.com/davdavid29/Projects/tree/main/University%20Projects/ATM%20Machine%20Code%20in%20Java%20Swing%20GUI%20with%20MySQL%20Database) | This project implements a basic ATM machine using Java Swing GUI and a MySQL database through the use of the phpMyAdmin web application. The user can input their account number and PIN, withdraw or deposit money, and check their account balance. The program connects to a MySQL database to store account information and transactions. It uses event listeners to detect button clicks and perform corresponding actions. The program displays account information and transaction history in the GUI. | 2019 | CPE 112_K12 – Object Oriented Programming | Netbeans and phpMyAdmin (for MySQL Database administration) |

### SQL Projects
#### Stored Procedure Log Table
-	The table records all the DML operation in the SP. When a certain stored procedure runs, the log table automatically populated with the details of the sp operation like either update or insert plus it will also records the date and time when was the sp runs also the execution time. It will also handles runtime errors like when a data is not compatible to a column it will record that this SP not executed successfully there the Status for this SP is 'Error' plus the error message showing what is the cause for that error.
- Used SQL techiques:
	- Try-catch block (handling runtime errors) Note: Try-catch block is designed only to handles runtime errors not compilation errors. Compile errors occur during the compilation phase of the SQL code, before it is executed, and they prevent the code from being executed altogether.-   [Runtime and Compilation Error](https://inchcapeglobal.atlassian.net/wiki/spaces/~712020d33a6ad2745641638c70aa8c9b365e93/pages/6579487437)
	-  [@@ROWCOUNT](https://inchcapeglobal.atlassian.net/wiki/spaces/~712020d33a6ad2745641638c70aa8c9b365e93/pages/6571917437/@@ROWCOUNT) - system variable
	- [@@PROCID and System Catalog Views](https://inchcapeglobal.atlassian.net/wiki/spaces/~712020d33a6ad2745641638c70aa8c9b365e93/pages/6574801271/@@PROCID+and+System+Catalog+Views) - system variable
	- [ERROR_NUMBER() and ERROR_MESSAGE()](https://inchcapeglobal.atlassian.net/wiki/spaces/~712020d33a6ad2745641638c70aa8c9b365e93/pages/6571851973) - system built-in function
	- [$action](https://inchcapeglobal.atlassian.net/wiki/spaces/~712020d33a6ad2745641638c70aa8c9b365e93/pages/6580273186)  - system special column

#### Trigger History table
-	This table also records but this time it records all the inserted and updated data's in a certain table that the trigger is created. This trigger is automatically executed when a triggering action is done in the table. The history table shows that the data inserted in the history table is either 'A' for Added or inserted and 'U' for updated for the TransactionType then ff fields are the important fields that necessary to know the history for it.


### Python Projects

### Data Engineering

### FAQs
