## **simple calculator**
- I added the function ```try``` so that if it sees any error it disables the program so as not to cause problems with the user
- A variable was written with the name Cal. This variable contains True so that the loop runs all the time
- A variable was defined with the name enter so that I can receive the mathematical operation from it later
- I added the conditional expression if so that if the person wants to exit the program he can write exit
- I added another condition because I noticed that when I ran the program without that condition there was a problem in the division, which is if I wrote it for example ```10/2``` the output will appear to me in this form ```5.0``` and I do not want it to appear in this form. I solved it by adding this condition that it is pressed on ```/``` if it finds it it replaces it with this command which is ```//``` because in this command the result of the division appears to me ```5``` like this
- And if not Something happens that converts that text to a number through the function ```eval``` so that I can calculate it.
- I added ```except``` to ```try``` then I called this command from inside it ```Exception``` and I stored a variable for it so that I could call it later to show me what the exact problem is and I added the letter ```f``` so that I could add a variable inside the text
