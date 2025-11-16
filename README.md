My ATM sample code will establish 2 primary Classes, BankAccount - will handle account number, pin/validation, and balance 
with functions that handle user actions like deposit/withdraw/show balance

The 2nd Class, ATM, will handle the functional aspects such as insert card, enter pin, select transaction (deposit/withdraw/check balance/quit).
This part can also be the section that handles a nested switch/if statements to handle menu options, and a session part that can handle finishing/logging out.


Psuedo Code/basic outline:

#simplified what makes a bank account unique to an acount number, a pin, and balance
# did not include name becuase I could not think of any situations when an ATM interacts with that aside from displaying it
# also, seperating this from ATM functions simplifies from having too many nested if/else statements I saw when working on group effort

class BankAccount:
  def __init__(self, account_number, pin, balance)

  def validate_pin
    frozen card, enter pin check, wrong pin counter, if 3 trys or more you can exit 

  def desposit #mechanics
    += balance

  def withdraw #mechanics
    -= balance
    
  def show_balance
    print balance


#decided to split the "at the ATM" actions you perfomr for this Class to inherit BankAccount functions/balance/info

Class ATM
  def__init__(self, account)

  def insert_card

  def enter_pin

  def select_transaction
    print 1 deposit
    print 2 Withdraw
    print 3 Check Balance
    print 4 Quit
    
  def perfomr_transaction 
    if 1 = take input deposit number/set to BankAccount balance
    if 2 = withdraw function from BankAccount above to balance
    if 3 = show balance from BankAccount
    if 4 = quit/break/return out 
    maybe an invalid number display/return


  def session
    check for card input, 
    check for pin entered,

    have a done_yet check, takes input from user, if yes, exits 

  have some users/accounts to fill to BankAccount:

  simple one could be:

  account = BankAccount(account number, pin, balance)
  atm = ATM(account)
  print (values) ??









    
  
