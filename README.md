# Python Booking System
Welcome to my Python Booking System, created in three days for a college final project. 
The project was initially labelled a C grade, however, this code caused it to be bumped up to an A.

### Notes from the project documents:
I wrote the code for this system in Python, a language I am familiar with. As of yet, I havent
converted this code to PHP, but I know how I would be able to do this if needed. I would
definitely have to link it to the database, adding the connect, insert, delete functions with SQL.
I would also provide a more user-friendly interface, such as using drop-down boxes to select
a treatment, and a date/time picker. The main step is actually converting the code, but this
would be fairly easy for me since I know both languages well.

#### What it does
This code starts by giving the user a ‘Welcome’ message, letting them know that they are in a
booking system, and that they can quit at any time by simply typing ‘quit’. ‘QUIT’ and ‘Quit’ are
also accepted. For most stages of the booking, this command will allow them to exit. The only
time they can’t use this command is when having to type a Yes/No answer, or while entering
their contact email after confirming their booking time/date.

After the welcome message, the user enters their name. This is then stored as a variable
which will be combined with their date and time choice and be put into the booking list. The
name ‘ela123’ is set as the admin username, meaning that if this is typed in, a password box
will appear. In short, it is a hidden admin login method. If the password is entered incorrectly,
the user will be prompted to enter it again until it is correct.

If NOT logged in, the booking algorithm will continue. The user will be shown a list of
weekdays (Monday – Sunday) with corresponding numbers, and will have to type in the
number of the weekday they would like. This is then set in a variable as their weekday choice.
