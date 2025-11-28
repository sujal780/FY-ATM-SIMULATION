 # VIRTUAL ATM SIMULATION
 A simple yet powerful python based ATM simulation that allows users to create accounts,log in,deposit money, withdraw money, check balance, and change pin all with strong validation.
 * user account system
   * create account with:
   i)Name
   ii)10 digit mobile number
   iii)4 digit pin
* secure pin validation
* stores balance for each user

* login system
  i) login using mobile number and pin
  ii) incorrect pin handling
  iii)account existence checks


* ATM Functionalities
  After logging in, users can:
  i) check balance
  ii) deposite money 
  iii) withdraw money with validation
  iv) change pin
   v) logout safely

* Input validation everywhere
  i) vaidates mobile number length
  ii) validates pin format
  iii) validates deposites/withdraw inputs
  iv) prevents negative or invalid amounts

* project structure
  PROJPY2/
│── atm.py      # Main Python file
│── README.md   # Documentation

* how to run :
  1. install python(3.x recommended )
  2. save the script as atm.py
  3. open terminal and run
 
* Program preview (text)
  ====== welcome to python atm =======
  1. create account
  2. login
  3. exit
 
* Future improvements(optional ideas )
  i) save users in JSON file ( permenent data )
  ii) add transaction history
  iii) add admin panel
  iv) add UI using tkinter / flask

* contributing
  PULL REQUESTS AND SUGGESTIONS ARE WELCOME!
* licence
  This project is open source under the MIT License
  
