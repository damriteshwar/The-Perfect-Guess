# The-Perfect-Guess

------------------------------------------------------------------------------------------------------------------------------
What we are gonna do?
The random function generates the number between 1 to 100. The user has 10 chances to guess the number. So, we ask max 10 times to user to enter a number. Once the user guess is matched with an actual number then the game is over. Every time user also sees how many no. of chances are left. If the user can’t guess the number then the game is over. Simple!!

Which Python concepts are covered?
If-else
While Loop
Random function
break statement
-------------------------------------------------------------------------------------------------------------------------------------------

We ask the user to guess the number. And store guessed number in num variable. Then we do comparisons with the generated number n.

In the first condition, if the guessed number is higher then the actual number than prints Your guess was too high: Guess a number lower than (your number). So, the user can get the idea, and next time he/she enters a lower number.

If the first condition is false, then flow goes for check second condition, if the guessed number is lower than actual number then prints Your guess was too low: Guess a number higher than (your number). So, the user can get the idea, and next time he/she enters a higher number.

If above both condition returns false. Then the user guessed number is matched with the actual number and the loop will be terminated by a break statement. Code also prints You Win! message and number of guesses taken by the user that counted by count variable.

With this above all condition, code also prints the number of guesses left for the user, and the count variable increases by one in every iteration to print a number of guesses taken by the user once the user wins the game.
So, the above all conditions are written in a while loop. while loop gets terminated once the user wins the game or no. of guesses reaches the limit.
Outside of the loop, code will print the Game Over message with the actual number.

Hope you like this game. Now it’s your turn to make guess the number in python with some modifications. Share with your friends and family who learning python.
