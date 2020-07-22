My Stream Editor program works successfully.

The user is meant to attach the file of formatted command edits when the executable is run. 
Then the program outputs the edited input.

My main function incorporates the given algorithm from the instructions and calls the 3 main functions I wrote to do the heavy lifting:
   - storeFileCommands
   - inRange
   - editLines

The functions incorporated pointers as parameters which was set to avoid global variables.

I typedefed the structure, enumerated type, and union as directed in the instructions to be my data structures that I used throughout the program.

The editLines function incorporated multiple if statements to edit all the correct lines with the correct formatting for A, I, O, d, and s. For the s edit, I implemented a replaceLine function to replace the first half with the second half.