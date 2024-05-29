
# ATM Bill Output Simulator
## Basic information: 
#### Title: 
ATM Bill Output Simulator
### Author: 
Juliano Martins Scherer
### Date: 
05/28
### Version: 
1.0
### Description: 
This C++ program simulates the output of banknotes from an ATM, allowing the registration of banknote values ​​and the simulation of withdrawals, calculating the quantity of banknotes needed for a value specified by the user. Execution can be stopped with code 9999.

## Functionalities: 
### Record of Notes:
The user registers the values ​​of the notes that will be used.
### Withdrawal Simulation: 
The user enters an amount to be withdrawn and the program calculates the amount of each note needed.
### System Interruption: 
Entering the value 9999 stops the program.
##Code Structure: 
AccountNotes function: Calculates the quantity of each note for the withdrawal value.

### Parameters: 
qtyNotes, valNotes, withdrawal.
### Registration functionNotes: 
Allows the user to record note values.

### Parameters: 
valNotes.
### SimulateOutput function: 
Displays the amount of each calculated note.

### Parameters: 
qtyNotes, valNotes.
###Main function: 
Controls program flow, calls functions, and manages memory.

## Example of use: 
- The user registers the values ​​of the notes.
- The user enters the amount to be withdrawn.
- The program displays the quantity of each note required.
- The user can continue entering values ​​or interrupt the system with code 9999.
## License: 
This project is licensed under the MIT License
