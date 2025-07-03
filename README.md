
Description
This is a Java console-based coffee machine simulator. The program mimics a coffee machine that can sell different types of coffee, refill supplies, collect money, clean itself, and show its current status.

Features
buy – Purchase espresso, latte, or cappuccino

fill – Refill water, milk, coffee beans, and disposable cups

take – Withdraw all money collected from sales

clean – Clean the machine (resets the coffee cup counter)

remaining – Display the machine’s current resources and money

exit – Exit the program

Installation & Running
Clone or download the project.

Compile the program:

bash
Copy
Edit
javac CoffeeMachine.java
Run the program:

bash
Copy
Edit
java machine.CoffeeMachine
How to Use
The program prompts you to enter one of these commands:
buy, fill, take, clean, remaining, exit

When buying (buy), select the coffee type:
1 = espresso
2 = latte
3 = cappuccino
back = return to main menu

Refill supplies using fill and follow the prompts.

Collect money with take.

Clean the machine with clean.

Check resources and money with remaining.

Resources Managed
Resource	Initial Amount	Espresso	Latte	Cappuccino
Water (ml)	400	250	350	200
Milk (ml)	540	0	75	100
Coffee Beans (g)	120	16	20	12
Disposable Cups	9	1	1	1
Money ($)	550	4	7	6

Important Notes
The machine requires cleaning after 10 cups of coffee; otherwise, it won’t make more.

It checks for enough resources before making coffee and informs if anything is missing.

Uses Scanner for console input.

Possible Improvements
Refactor into OOP with separate classes for machine, coffee types, and UI.

Add more coffee varieties.

Save machine state to a file to persist data between runs.

Add a GUI for better user experience.
