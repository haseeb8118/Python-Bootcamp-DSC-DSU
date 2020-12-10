# DSC-DSU | Python Bootcamp 2020 | Week 1

Paste questions and brief writeup here


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q1: Define a function to print a string diagonally

 *  what you did and why you did it
      #Function Created
      #Took User Input and stored in 'word' variable
      #Created space variable and assign null value init
      #For Loop which prints 'char' 'word' times, so that it can run word's variable times. 
      #Print space and char inside of for loop
      #increase space for next loop's turn
      #Called Fucntion, so that it can print.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q2: Create a program to take as input 5 student records in the following format:
roll_num | name | age | marks(out of 100)
And then output the records in a tabular form with class average, class highest and class lowest at end in the following format.
Use dictionaries (list of dictionaries in exact)
Insert atleast 5 records
Input must be user-given
(Optional) validate the user input, i.e marks aren't greater 100 and other such validations you think there might be

* what you did and why you did it
      #Takin input in array form and storing it in 'first' variable

      { #Using while loop, so that loop works until user input a value which is less than 100
      #Print "Please enter no. between 1 to 100" when user input a larger value than 100  
      #Again ask the same input from user
      #Again check if user entered value is less than 100 or not      
      #If entered value less than 100 while loop will be break or else it will work until user enter value which is less than 100 }   
      
     #Ask and verify using while loop five times and store these values in "second", "third", "fourth", "fifth" variables
      #from tabulate import tabulate #import tabulate package for package manager to print program in tabular form
      #Print "first", "second", "third", "fourth", "fifth" variable in tabular form


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q3:A function that will print lyrics of given song with 1 second delay between each line.
Use time.sleep()
Use split() function of string

* what you did and why you did it
      #Importing sleep from python library so that sleep command can work
      #Stored my favourite song in array form in mySong variable
      #For Loop which prints 's' 'mySong' times, So that it can print every array in mySong
      #Inside of for loop it will print 's' 'mySong' times and it will take a break of 1 second after every array
      #Stored "THE END" in txt variable
      #Using split breaking "THE END" into ["THE", "END"] and Stored txt variable in x variable
      #Print 0 index of x "THE"
      #Print 1 index of x "END"

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
