"# Week2" 
Intro to Java Week 2 Coding Assignment
Points possible: 70
Category	Criteria	% of Grade
Functionality	Does the code work?	25
Organization	Is the code clean and organized? Proper use of white space, syntax, and consistency are utilized. Names and comments are concise and clear.	25
Creativity	Student solved the problems presented in the assignment using creativity and out of the box thinking.	25
Completeness	All requirements of the assignment are complete.	25

Instructions: In Eclipse, or an IDE of your choice, write the code that accomplishes the objectives listed below. Ensure that the code compiles and runs as directed. Take screenshots of the code and of the running program (make sure to get screenshots of all required functionality) and paste them in this document where instructed below. Create a new repository on GitHub for this week’s assignments and push this document, with your Java project code, to the repository. Add the URL for this week’s repository to this document where instructed and submit this document to your instructor when complete.
Coding Steps:
1.	What do each of the following Boolean expressions evaluate to?
Boolean Expression	Answer
true && false	False
true || false	True
false && false	True
true && (false || true)	True
false || (true && false)	False
false || 1 < 5	True
5 >= 4 && 1 > 3	False
10 < 4 || 1 > 4	False
12 >= 2 && 1 < 24	True
“Hello”.charAt(0) == ‘h’	

2.	In Eclipse, create the following Boolean variables and choose what values they hold:
a.	isHotOutside
b.	isWeekday
c.	hasMoneyInPocket
3.	Create the following variables (not boolean type, choose the best data type for the variable):
a.	costOfMilk
b.	moneyInWallet
c.	thirstLevel (how thirsty you are on a scale of 1-10)
4.	Using the variables you created above and Boolean operators, create variables for the following scenarios:
a.	shouldByIcecream – this should be true if it is hot outside and there is money in your pocket
b.	willGoSwimming – this should be true if it is hot outside and it is not a weekday
c.	isAGoodDay – this should be true if it is hot outside, there is money in your pocket, and it is not a weekday
d.	willBuyMilk – this should be true if it is hot outside, and thirstLevel is greater than or equal to 3, and moneyInWallet is greater than or equal to 2 times the cost of milk.
Example: If I had the variables isWeekday and isSummer and I was going to create a variable isSchoolDay, I would do something like the following:
boolean isSchoolDay = isWeekday && !isSummer;
5.	Create a new class called Loops. In the main method of this class, create the following loops with any variables you feel are needed:
a.	A while loop that prints all even numbers from 0 to 100
b.	A while loop that prints every 3rd number going backwards from 100 until we reach 0
c.	A for loop that prints every other number from 1 to 100
d.	A for loop that prints every number from 0 to 100, but if the number is divisible by 3, it prints “Hello” instead of the number, and if the number is divisible by 5, it prints “World” instead of the number, and if it is divisible by both 3 and 5, it prints “HelloWorld” instead of the number.
Screenshots of Code:

Screenshots of Running Application:

URL to GitHub Repository:
