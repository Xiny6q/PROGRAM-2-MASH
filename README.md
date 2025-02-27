Download link :https://programming.engineering/product/program-2-mash/

# PROGRAM-2-MASH
PROGRAM 2 MASH
The purpose of the program is to play the game of MASH (Mansion, Apartment, Shack, House). This program asks the user multiple questions and then randomly generates answers based on the answers to predict the user’s future. By the time you finish this program, you will have learned how to make a menu based program, use switch statements, validate user input with loops, allow a program to run multiple times until user wants to quit, and mix cin>> and getline() intermittently in a program.

INPUT
N ames of three people (2 they like & one they don’t like)

Three integer numbers between 1 and 100

Three locations including city & state (2 they like & one they don’t like)

Three job titles (2 they like & one they don’t like)

Three companies or restaurants (2 they like & one they don’t like)

Three integer numbers between 10000 and 500000

Three types of cars (2 they like & one they don’t like


RANDOM NUMBERS
You will be predicting the user’s future by selecting one of their three choices randomly. You will need to create a random number for each “category” – this means there should be in total 7 numbers randomly generated between 1 and 3. So for example, you will generate a random number between 1 and 3 for the names of people.

You will also generate one more random number (this would make 8 total) between 1 and 4 which will indicate if the user will live in a mansion (1), apartment (2), shack (3), or house(4).

OUTPUT
The user’s type of house (mansion, apartment, shack, or house)

The user’s spouse (based on the three people)

The number of children the user will have (based on the integer between 1 and 100)

Where the user will live (based on locations)

Where the user will work, their job title, and their salary (based on the three companies and the three integer numbers between 10000 and 500000).

What the user will drive. (based on cars)

SPECIFICATIONS
Indent and comment your code properly.
 

MENU – You will have a main menu that will ask the user to either
1) Play MASH or
2) End the program.

You must have a switch statement to figure out which choice the user selected. The program should run over and over until the user selects to end the program using a do-while loop. Use a Boolean variable to help with this!

 

You MUST validate user input with while loops if the input is a number to ensure the number is in the specified range. You may assume the user will enter in a number (not a character or string), but you can’t assume they enter a number within the specified range.
 

You MUST allow spaces to be included in all string input.
 

HOW TO PRINT OUT RESULTS
For housing you are not asking the user for the data. The words MASH stand for the different types of housing. There are four choices (Mansion, Apartment, Shack or House). You will need to generate a number between 1 and 4. If it is a 1, you will print out that the user will live in a mansion. If it is a 2, you will print out that the user will live in an apartment……and so on.
For all the other “categories” you have three choices, not four. So you will need to generate a number between 1 and 3. If it is a 1, you print out the first one, 2 the second one, and 3 the third one. For example, for spouse – generate a number between 1 and 3. If it is a 1, then print out the first person that the user said they like. If it is a 2, then print out the second person that the user said they like. If it is a 3, then print out the third person that the user dislikes. Before printing out the spouse, you should say “You will be happily married to “ and then print out the name.
For the answers you should say something like:
You will live in ….
You will be happily married to …
You and your spouse will have ….. children.
You will live in ….. (name city, state here)
You will work at ……. (place) as a ……… (job title) making $ ……… (salary) a year.
You will drive a ……


SAMPLE OUTPUT
Screen captures of a sample run of the program are below. You may also view the sample output as a text file called program2_output.txt which is available in ilearn.




TOTAL GRADE (OUT OF 100%)
OOPS POLICY? ( subtracts 5 points per day late up to 3 days late and can only be used once a semester)

Did student submit program in a zipped file and include everything needed to compile & run the program?

(subtract 1 point if not)

EXECUTION (DOES the program compile?) (20%)
Program compiles = 20 points

Program doesn’t compile because of one extremely small syntax error = 15 points

Program doesn’t compile = 0 points

does the program work as specified? (70%)
[10 points] program contains menu and runs as many times as user wishes using a do-while loop

[5 points] program correctly uses switch statement

[20 points] INPUT– all data that is supposed to be obtained from the user is obtained correctly AND all numerical input is validated with while loops if it is in the correct range

[15 points] CALCULATIONS – random number is generated correctly for each “category” and for MASH

[20 points] OUTPUT – results are printed correctly based on the random number generated and are easy to read

Readability of code (10%)
[5 points] consistent, proper indentions

[5 points] comment block at top
