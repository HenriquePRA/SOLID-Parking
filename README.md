# SOLID-Parking

### Consists in the application of the SOLID principles in an system refactoring and adding new features

The project is divided in two branches:

- before_refactor

There is an parking system that needs to use several criteria to calculate the value to be requested
from their clients, the actual system is designed taking in considaration a generalistic aproach to 
veicles applying the time rules to any veicle independent of their type.

The system is made aroud the two classes:
[IMG]

The actual rules are, for each hour that a veicle spends on the parking lot, it will be charged
$ 2.00, if the veicle stays for more than twelve hours the charge will be 26$ per day and if the
veicle stays for more than fifteen days the charge will be 300$ per month

- after_refactor

After refactoring the application will need to be able to apply specific rules depending on the type 
of the veicle, for example, trucks will pay extra taxes for the number of axles in the truck and value 
of load or for passenger veicles like turistc busses.

The application refactoring and adaptation to new features applies the SOLID principles
