# Typing-Acharya

This is a C++ program that creates a typing game. 

There are two options for the user to choose from: a typing test and a typing lesson. 

The typing test generates random words from a word bank and the user must type them as quickly and accurately as possible. 

The typing lesson presents the user with 15 lessons of progressively more difficult words and phrases to type.

The main function first displays a front screen to the user and waits for input. 

If the user enters '1', the program enters the typing test mode and creates a new thread to display the elapsed time. 

It then calls the logic_box function to handle the actual typing test. 

When the test is finished, the program waits for the user to press Enter before continuing. 

If the user enters '2', the program enters the typing lesson mode and displays 15 lessons to the user one at a time. 

If the user enters any other character, the program exits.
