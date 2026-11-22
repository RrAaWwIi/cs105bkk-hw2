# HW2 notes

Answer each question in a few sentences. Be specific: name the function, the error or the command.

## What did you try?
I tried to complete HW2 by creating a club event management program. I worked on the Event and Club classes, implemented limited seats and a waiting list, and used custom exceptions to handle errors. I also tested the functions to check that members could register, cancel registrations, and join the waiting list correctly.
## What broke, and how did you fix it?
I had some problems handling situations such as registering for an event that was already full, registering twice, or cancelling a registration that did not exist. I fixed these problems by using custom exceptions from errors.py and adding error handling to the relevant functions. I also ran the test files (test_event.py, test_club.py, and test_errors.py) to find and fix mistakes.
## What would you do differently next time?
Next time, I would read the assignment requirements more carefully and plan the classes and functions before writing the code. I would also write and run small tests after completing each function instead of waiting until the end. This would make it easier to find errors and understand which part of the program needs fixing.