This project provides a hotel management system that can execute and manage activities like booking rooms of different types, ordering food for them, see room availability, unbook a room, etc.
It is menu driven and runs in the console until the user exits.
Current status of the hotel(customer details, booked rooms, food ordered) are saved in a file so that when we restart the program, the old details are not lost. 
The program reads the 
file when it restarts to know the previous status of the hotel. is stored and saved in files and are not lost when the program finishes.
Writing of file has been done in a separate thread as it can be done parallelly. 
User defined exception is thrown if the user tries to book an already allotted room. 
Exception handling is properly done to deal with any kind of unexpected exception.
This project covers different topics from OOP as classes and objects, inheritance, file Handling with objects, arrayList, User defined exception and Exception handling.
