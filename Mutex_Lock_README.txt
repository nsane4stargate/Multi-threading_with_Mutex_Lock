Program objective is to go over:
Threads
						This program will:
(1)Make a detached thread run processMeal(). This function wants an argument. 
Call selectFood() to obtain the name of a food to give to it.

(2)After the loop ends:
	Wait for your baby thread
	Clean up any pthread_attr_t state you may have created to define the detached threads
	
(3)Add a single mutex to class Diaper by:
	Declare them with the other member vars
	Initialize them in the constructor
	Use them in makeDeposit(). Leave the Diaper unlocked when you leave.
	Use them in replace(). Leave the Diaper unlocked when you leave.