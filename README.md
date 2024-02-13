The project represents hotel room reservation process. There is no GUI, interacting is done via command line.
In the menu there is common information about total number of rooms, their sizes, prices per night and discount conditions. Then there are options user chooses.
During reservation process user chooses room number, then program checks if it is available. If not, user is asked to choose another room. If it is available user is asked to give number of nights and customer name. Then program gives reservation number and total price with discount made.
Also, room can be chosen by program.
When reservation is done, program returns back to menu, and user can choose another option.
Basically, after every chosen menu option is done, program returns to menu. To exit menu user can type anything else besides option numbers.
During making choices the program checks if input is correct and if not, it asks to type choice again.
As additional features I added subroutine roomAvailability, which can be called separately without starting reservation process. Also, there is feature, which gives free bottle of beer for every 3rd customer. And, when program returns to the menu, program checks, if all rooms are reserved. If they are, reservation process is not possible anymore, it says that all rooms are reserved.

To see example of running app, download **hotel.webm** file.
