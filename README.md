# Schedule-Comparison
This document holds schedule information in a dictionary, that can be compared with everyone else's schedule.
Literally, just a dictionary that can be requested through an API


The program asks whether you would like to 'analyze' or 'create'
  If the user picks 'analyze':
    - The program will output a list of created profiles, 
      which when typed will list all the classes this person 
      shares with other people.
  If the user picks 'create':
    - The program will follow the steps labeled below.

On 'create' request, put the number of classes you have into the program.
The program will request class information equal to the number of classes you said you had.

Input each class like so: "[class#]/[title]/[instructor(s)]/[day(s)]/[time(s)]"

NOTE: Type each inquiry *exactly* how it is written in My ASU. 

NOTE: If you have multiple instructors, write both names-- E.X. "Meuth, Miller"

NOTE: If your class does not have a [day(s)] or a [time(s)] set, 

  |>  most likely because of hybrid, replace them with none. (see E.X. 2 below)

Here are 3 example inputs (Do not use quotation marks):
E.X. 1) "86189/The ASU Experience/Holcomb/W/1:25 PM - 2:15 PM"
E.X. 2) "76815/Principles of Programming/Meuth/ Miller/none/none"
E.X. 3) "93189/First-Year Composition/Brooks/T Th/12:00 PM - 1:15 PM"
