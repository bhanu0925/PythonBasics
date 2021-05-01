**PythonBasics_1**

1. In the below elements which of them are values or an expression? eg:- values can be
integer or string and expressions will be mathematical operators.
  '*', 'hello', -87.8,-, /, +, 6

2. What is the difference between string and variable?

3. Describe three different data types.

4. What is an expression made up of? What do all expressions do?
5. This assignment statements, like spam = 10. What is the difference between an
expression and a statement?
6. After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1

7. What should the values of the following two terms be?
&#39;spam&#39; + &#39;spamspam&#39;
&#39;spam&#39; * 3

8. Why is eggs a valid variable name while 100 is invalid?

9. What three functions can be used to get the integer, floating-point number, or string
version of a value?
10. Why does this expression cause an error? How can you fix it?
&#39;I have eaten &#39; + 99 + &#39; burritos.&#39;

**PythonBasics_2**

1.What are the two values of the Boolean data type? How do you write them?
2. What are the three different types of Boolean operators?
3. Make a list of each Boolean operator&#39;s truth tables (i.e. every possible combination of Boolean
values for the operator and what it evaluate ).
4. What are the values of the following expressions?
(5 &gt; 4) and (3 == 5)
not (5 &gt; 4)
(5 &gt; 4) or (3 == 5)
not ((5 &gt; 4) or (3 == 5))
(True and True) and (True == False)
(not False) or (not True)
5. What are the six comparison operators?
6. How do you tell the difference between the equal to and assignment operators?Describe a
condition and when you would use one.
7. Identify the three blocks in this code:
spam = 0
if spam == 10:
print(&#39;eggs&#39;)
if spam &gt; 5:
print(&#39;bacon&#39;)
else:
print(&#39;ham&#39;)
print(&#39;spam&#39;)
print(&#39;spam&#39;)
8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints
Greetings! if anything else is stored in spam.
9.If your programme is stuck in an endless loop, what keys you’ll press?
10. How can you tell the difference between break and continue?
11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?
12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent
program that prints the numbers 1 to 10 using a while loop.
13. If you had a function named bacon() inside a module named spam, how would you call it after
importing spam?


**PythonBasics_3**

1. Why are functions advantageous to have in your programs?
2. When does the code in a function run: when it&#39;s specified or when it&#39;s called?
3. What statement creates a function?
4. What is the difference between a function and a function call?
5. How many global scopes are there in a Python program? How many local scopes?
6. What happens to variables in a local scope when the function call returns?
7. What is the concept of a return value? Is it possible to have a return value in an expression?
8. If a function does not have a return statement, what is the return value of a call to that function?
9. How do you make a function variable refer to the global variable?
10. What is the data type of None?
11. What does the sentence import areallyourpetsnamederic do?
12. If you had a bacon() feature in a spam module, what would you call it after importing spam?
13. What can you do to save a programme from crashing if it encounters an error?
14. What is the purpose of the try clause? What is the purpose of the except clause?

**PythonBasics_4**

1. What exactly is []?
2. In a list of values stored in a variable called spam, how would you assign the value &#39;hello&#39; as the
third value? (Assume [2, 4, 6, 8, 10] are in spam.)
Let&#39;s pretend the spam includes the list [&#39;a&#39;, &#39;b&#39;, &#39;c&#39;, &#39;d&#39;] for the next three queries.
3. What is the value of spam[int(int(&#39;3&#39; * 2) / 11)]?
4. What is the value of spam[-1]?
5. What is the value of spam[:2]?
Let&#39;s pretend bacon has the list [3.14, &#39;cat,&#39; 11, &#39;cat,&#39; True] for the next three questions.
6. What is the value of bacon.index(&#39;cat&#39;)?
7. How does bacon.append(99) change the look of the list value in bacon?
8. How does bacon.remove(&#39;cat&#39;) change the look of the list in bacon?
9. What are the list concatenation and list replication operators?
10. What is difference between the list methods append() and insert()?
11. What are the two methods for removing items from a list?
12. Describe how list values and string values are identical.
13. What&#39;s the difference between tuples and lists?
14. How do you type a tuple value that only contains the integer 42?
15. How do you get a list value&#39;s tuple form? How do you get a tuple value&#39;s list form?
16. Variables that &quot;contain&quot; list values are not necessarily lists themselves. Instead, what do they
contain?
17. How do you distinguish between copy.copy() and copy.deepcopy()?


**PythonBasics_5**

1. What does an empty dictionary&#39;s code look like?
2. What is the value of a dictionary value with the key &#39;foo&#39; and the value 42?
3. What is the most significant distinction between a dictionary and a list?
4. What happens if you try to access spam[&#39;foo&#39;] if spam is {&#39;bar&#39;: 100}?
5. If a dictionary is stored in spam, what is the difference between the expressions &#39;cat&#39; in spam and
&#39;cat&#39; in spam.keys()?
6. If a dictionary is stored in spam, what is the difference between the expressions &#39;cat&#39; in spam and
&#39;cat&#39; in spam.values()?
7. What is a shortcut for the following code?
if &#39;color&#39; not in spam:
spam[&#39;color&#39;] = &#39;black&#39;

8. How do you &quot;pretty print&quot; dictionary values using which module and function?

**PythonBasics_6**

1. What are escape characters, and how do you use them?
2. What do the escape characters n and t stand for?
3. What is the way to include backslash characters in a string?
4. The string &quot;Howl&#39;s Moving Castle&quot; is a correct value. Why isn&#39;t the single quote character in the
word Howl&#39;s not escaped a problem?
5. How do you write a string of newlines if you don&#39;t want to use the n character?
6. What are the values of the given expressions?
&#39;Hello, world!&#39;[1]
&#39;Hello, world!&#39;[0:5]
&#39;Hello, world!&#39;[:5]
&#39;Hello, world!&#39;[3:]

7. What are the values of the following expressions?
&#39;Hello&#39;.upper()
&#39;Hello&#39;.upper().isupper()
&#39;Hello&#39;.upper().lower()
8. What are the values of the following expressions?
&#39;Remember, remember, the fifth of July.&#39;.split()
&#39;-&#39;.join(&#39;There can only one.&#39;.split())
9. What are the methods for right-justifying, left-justifying, and centering a string?
10. What is the best way to remove whitespace characters from the start or end?

**PythonBasics_7**

1. What is the name of the feature responsible for generating Regex objects?
2. Why do raw strings often appear in Regex objects?
3. What is the return value of the search() method?
4. From a Match item, how do you get the actual strings that match the pattern?
5. In the regex which created from the r&#39;(\d\d\d)-(\d\d\d-\d\d\d\d)&#39;, what does group zero cover?
Group 2? Group 1?
6. In standard expression syntax, parentheses and intervals have distinct meanings. How can you tell
a regex that you want it to fit real parentheses and periods?
7. The findall() method returns a string list or a list of string tuples. What causes it to return one of
the two options?
8. In standard expressions, what does the | character mean?
9. In regular expressions, what does the character stand for?
10.In regular expressions, what is the difference between the + and * characters?
11. What is the difference between {4} and {4,5} in regular expression?
12. What do you mean by the \d, \w, and \s shorthand character classes signify in regular
expressions?
13. What do means by \D, \W, and \S shorthand character classes signify in regular expressions?
14. What is the difference between .*? and .*?
15. What is the syntax for matching both numbers and lowercase letters with a character class?
16. What is the procedure for making a normal expression in regax case insensitive?
17. What does the . character normally match? What does it match if re.DOTALL is passed as 2nd
argument in re.compile()?
18. If numReg = re.compile(r&#39;\d+&#39;), what will numRegex.sub(&#39;X&#39;, &#39;11 drummers, 10 pipers, five rings, 4
hen&#39;) return?
19. What does passing re.VERBOSE as the 2nd argument to re.compile() allow to do?
20. How would you write a regex that match a number with comma for every three digits? It must
match the given following:
&#39;42&#39;
&#39;1,234&#39;
&#39;6,368,745&#39;

but not the following:
&#39;12,34,567&#39; (which has only two digits between the commas)
&#39;1234&#39; (which lacks commas)
21. How would you write a regex that matches the full name of someone whose last name is
Watanabe? You can assume that the first name that comes before it will always be one word that
begins with a capital letter. The regex must match the following:
&#39;Haruto Watanabe&#39;
&#39;Alice Watanabe&#39;
&#39;RoboCop Watanabe&#39;
but not the following:
&#39;haruto Watanabe&#39; (where the first name is not capitalized)
&#39;Mr. Watanabe&#39; (where the preceding word has a nonletter character)
&#39;Watanabe&#39; (which has no first name)
&#39;Haruto watanabe&#39; (where Watanabe is not capitalized)
22. How would you write a regex that matches a sentence where the first word is either Alice, Bob,
or Carol; the second word is either eats, pets, or throws; the third word is apples, cats, or baseballs;
and the sentence ends with a period? This regex should be case-insensitive. It must match the
following:
&#39;Alice eats apples.&#39;
&#39;Bob pets cats.&#39;
&#39;Carol throws baseballs.&#39;
&#39;Alice throws Apples.&#39;
&#39;BOB EATS CATS.&#39;
but not the following:
&#39;RoboCop eats apples.&#39;
&#39;ALICE THROWS FOOTBALLS.&#39;
&#39;Carol eats 7 cats.&#39;

**PythonBasics_8**

1. Is the Python Standard Library included with PyInputPlus?
2. Why is PyInputPlus commonly imported with import pyinputplus as pypi?
3. How do you distinguish between inputInt() and inputFloat()?
4. Using PyInputPlus, how do you ensure that the user enters a whole number between 0 and 99?
5. What is transferred to the keyword arguments allowRegexes and blockRegexes?
6. If a blank input is entered three times, what does inputStr(limit=3) do?
7. If blank input is entered three times, what does inputStr(limit=3, default=&#39;hello&#39;) do?


**PythonBasics_9**

1. To what does a relative path refer?
2. What does an absolute path start with your operating system?
3. What do the functions os.getcwd() and os.chdir() do?
4. What are the . and .. folders?
5. In C:\bacon\eggs\spam.txt, which part is the dir name, and which part is the base name?
6. What are the three “mode” arguments that can be passed to the open() function?
7. What happens if an existing file is opened in write mode?
8. How do you tell the difference between read() and readlines()?
9. What data structure does a shelf value resemble?

**PythonBasics_10**

1. How do you distinguish between shutil.copy() and shutil.copytree()?
2. What function is used to rename files??
3. What is the difference between the delete functions in the send2trash and shutil modules?
4.ZipFile objects have a close() method just like File objects’ close() method. What ZipFile method is
equivalent to File objects’ open() method?
5. Create a programme that searches a folder tree for files with a certain file extension (such as .pdf
or .jpg). Copy these files from whatever location they are in to a new folder.

**PythonBasics_11**

1. Create an assert statement that throws an AssertionError if the variable spam is a negative
integer.
2. Write an assert statement that triggers an AssertionError if the variables eggs and bacon contain
strings that are the same as each other, even if their cases are different (that is, &#39;hello&#39; and &#39;hello&#39; are
considered the same, and &#39;goodbye&#39; and &#39;GOODbye&#39; are also considered the same).
3. Create an assert statement that throws an AssertionError every time.
4. What are the two lines that must be present in your software in order to call logging.debug()?
5. What are the two lines that your program must have in order to have logging.debug() send a
logging message to a file named programLog.txt?
6. What are the five levels of logging?
7. What line of code would you add to your software to disable all logging messages?
8.Why is using logging messages better than using print() to display the same message?
9. What are the differences between the Step Over, Step In, and Step Out buttons in the debugger?
10.After you click Continue, when will the debugger stop ?
11. What is the concept of a breakpoint?


**PythonBasics_12**

1. In what modes should the PdfFileReader() and PdfFileWriter() File objects will be opened?
2. From a PdfFileReader object, how do you get a Page object for page 5?
3. What PdfFileReader variable stores the number of pages in the PDF document?
4. If a PdfFileReader object’s PDF is encrypted with the password swordfish, what must you do
before you can obtain Page objects from it?
5. What methods do you use to rotate a page?
6. What is the difference between a Run object and a Paragraph object?
7. How do you obtain a list of Paragraph objects for a Document object that’s stored in a variable
named doc?
8. What type of object has bold, underline, italic, strike, and outline variables?
9. What is the difference between False, True, and None for the bold variable?
10. How do you create a Document object for a new Word document?
11. How do you add a paragraph with the text &#39;Hello, there!&#39; to a Document object stored in a
variable named doc?
12. What integers represent the levels of headings available in Word documents?

**PythonBasics_13**

1. What advantages do Excel spreadsheets have over CSV spreadsheets?
2.What do you pass to csv.reader() and csv.writer() to create reader and writer objects?
3. What modes do File objects for reader and writer objects need to be opened in?
4. What method takes a list argument and writes it to a CSV file?
5. What do the keyword arguments delimiter and line terminator do?
6. What function takes a string of JSON data and returns a Python data structure?
7. What function takes a Python data structure and returns a string of JSON data?

**PythonBasics_14**

1. What does RGBA stand for?
2. From the Pillow module, how do you get the RGBA value of any images?
3. What is a box tuple, and how does it work?
4. Use your image and load in notebook then, How can you find out the width and height of an
Image object?
5. What method would you call to get Image object for a 100×100 image, excluding the lower-left
quarter of it?
6. After making changes to an Image object, how could you save it as an image file?
7. What module contains Pillow’s shape-drawing code?
8. Image objects do not have drawing methods. What kind of object does? How do you get this kind
of object?


**PythonBasics_15**

1.How many seconds are in an hour? Use the interactive interpreter as a calculator and multiply the
number of seconds in a minute (60) by the number of minutes in an hour (also 60).
sol. 60
2. Assign the result from the previous task (seconds in an hour) to a variable called
seconds_per_hour.
3. How many seconds do you think there are in a day? Make use of the variables seconds per hour
and minutes per hour.
4. Calculate seconds per day again, but this time save the result in a variable called seconds_per_day
5. Divide seconds_per_day by seconds_per_hour. Use floating-point (/) division.
6. Divide seconds_per_day by seconds_per_hour, using integer (//) division. Did this number agree
with the floating-point value from the previous question, aside from the final .0?
7. Write a generator, genPrimes, that returns the sequence of prime numbers on successive calls to
its next() method: 2, 3, 5, 7, 11, ...


**PythonBasics_16**

1. Create a list called years_list, starting with the year of your birth, and each year thereafter until
the year of your fifth birthday. For example, if you were born in 1980. the list would be years_list =
[1980, 1981, 1982, 1983, 1984, 1985].
2. In which year in years_list was your third birthday? Remember, you were 0 years of age for your
first year.
3.In the years list, which year were you the oldest?
4. Make a list called things with these three strings as elements: &quot;mozzarella&quot;, &quot;cinderella&quot;,
&quot;salmonella&quot;.
5. Capitalize the element in things that refers to a person and then print the list. Did it change the
element in the list?
6. Make a surprise list with the elements &quot;Groucho,&quot; &quot;Chico,&quot; and &quot;Harpo.&quot;
7. Lowercase the last element of the surprise list, reverse it, and then capitalize it.
8. Make an English-to-French dictionary called e2f and print it. Here are your starter words: dog is
chien, cat is chat, and walrus is morse.
9. Write the French word for walrus in your three-word dictionary e2f.
10. Make a French-to-English dictionary called f2e from e2f. Use the items method.
11. Print the English version of the French word chien using f2e.
12. Make and print a set of English words from the keys in e2f.
13. Make a multilevel dictionary called life. Use these strings for the topmost keys: &#39;animals&#39;, &#39;plants&#39;,
and &#39;other&#39;. Make the &#39;animals&#39; key refer to another dictionary with the keys &#39;cats&#39;, &#39;octopi&#39;, and
&#39;emus&#39;. Make the &#39;cats&#39; key refer to a list of strings with the values &#39;Henri&#39;, &#39;Grumpy&#39;, and &#39;Lucy&#39;.
Make all the other keys refer to empty dictionaries.
14. Print the top-level keys of life.
15. Print the keys for life[&#39;animals&#39;].
16. Print the values for life[&#39;animals&#39;][&#39;cats&#39;]



**PythonBasic_17**

1. Assign the value 7 to the variable guess_me. Then, write the conditional tests (if, else, and elif) to
print the string &#39;too low&#39; if guess_me is less than 7, &#39;too high&#39; if greater than 7, and &#39;just right&#39; if equal
to 7.
2. Assign the value 7 to the variable guess_me and the value 1 to the variable start. Write a while
loop that compares start with guess_me. Print too low if start is less than guess me. If start equals
guess_me, print &#39;found it!&#39; and exit the loop. If start is greater than guess_me, print &#39;oops&#39; and exit
the loop. Increment start at the end of the loop.
3. Print the following values of the list [3, 2, 1, 0] using a for loop.
4. Use a list comprehension to make a list of the even numbers in range(10)
5. Use a dictionary comprehension to create the dictionary squares. Use range(10) to return the
keys, and use the square of each key as its value.
6. Construct the set odd from the odd numbers in the range using a set comprehension (10).
7. Use a generator comprehension to return the string &#39;Got &#39; and a number for the numbers in
range(10). Iterate through this by using a for loop.
8. Define a function called good that returns the list [&#39;Harry&#39;, &#39;Ron&#39;, &#39;Hermione&#39;].
9. Define a generator function called get_odds that returns the odd numbers from range(10). Use a
for loop to find and print the third value returned.
10. Define an exception called OopsException. Raise this exception to see what happens. Then write
the code to catch this exception and print &#39;Caught an oops&#39;.
11. Use zip() to make a dictionary called movies that pairs these lists: titles = [&#39;Creature of Habit&#39;,
&#39;Crewel Fate&#39;] and plots = [&#39;A nun turns into a monster&#39;, &#39;A haunted yarn shop&#39;].


**PythonBasics_18**

1. Create a zoo.py file first. Define the hours() function, which prints the string &#39;Open 9-5 daily&#39;.
Then, use the interactive interpreter to import the zoo module and call its hours() function.
2. In the interactive interpreter, import the zoo module as menagerie and call its hours() function.
3. Using the interpreter, explicitly import and call the hours() function from zoo.
4. Import the hours() function as info and call it.
5. Create a plain dictionary with the key-value pairs &#39;a&#39;: 1, &#39;b&#39;: 2, and &#39;c&#39;: 3, and print it out.
6.Make an OrderedDict called fancy from the same pairs listed in 5 and print it. Did it print in the
same order as plain?
7. Make a default dictionary called dict_of_lists and pass it the argument list. Make the list
dict_of_lists[&#39;a&#39;] and append the value &#39;something for a&#39; to it in one assignment. Print
dict_of_lists[&#39;a&#39;].


**PythonBasics_19**

1. Make a class called Thing with no contents and print it. Then, create an object called example
from this class and also print it. Are the printed values the same or different?
2. Create a new class called Thing2 and add the value &#39;abc&#39; to the letters class attribute. Letters
should be printed.
3. Make yet another class called, of course, Thing3. This time, assign the value &#39;xyz&#39; to an instance
(object) attribute called letters. Print letters. Do you need to make an object from the class to do
this?
4. Create an Element class with the instance attributes name, symbol, and number. Create a class
object with the values &#39;Hydrogen,&#39; &#39;H,&#39; and 1.
5. Make a dictionary with these keys and values: &#39;name&#39;: &#39;Hydrogen&#39;, &#39;symbol&#39;: &#39;H&#39;, &#39;number&#39;: 1. Then,
create an object called hydrogen from class Element using this dictionary.
6. For the Element class, define a method called dump() that prints the values of the object’s
attributes (name, symbol, and number). Create the hydrogen object from this new definition and
use dump() to print its attributes.
7. Call print(hydrogen). In the definition of Element, change the name of method dump to __str__,
create a new hydrogen object, and call print(hydrogen) again.
8. Modify Element to make the attributes name, symbol, and number private. Define a getter
property for each to return its value.
9. Define three classes: Bear, Rabbit, and Octothorpe. For each, define only one method: eats(). This
should return &#39;berries&#39; (Bear), &#39;clover&#39; (Rabbit), or &#39;campers&#39; (Octothorpe). Create one object from
each and print what it eats.
10. Define these classes: Laser, Claw, and SmartPhone. Each has only one method: does(). This
returns &#39;disintegrate&#39; (Laser), &#39;crush&#39; (Claw), or &#39;ring&#39; (SmartPhone). Then, define the class Robot that
has one instance (object) of each of these. Define a does() method for the Robot that prints what its
component objects do.

**PythonBasics_20**

1. Set the variable test1 to the string &#39;This is a test of the emergency text system,&#39; and save test1 to a
file named test.txt.
2. Read the contents of the file test.txt into the variable test2. Is there a difference between test 1
and test 2?
3. Create a CSV file called books.csv by using these lines:
title,author,year
The Weirdstone of Brisingamen,Alan Garner,1960
Perdido Street Station,China Miéville,2000
Thud!,Terry Pratchett,2005
The Spellman Files,Lisa Lutz,2007
Small Gods,Terry Pratchett,1992
4. Use the sqlite3 module to create a SQLite database called books.db, and a table called books with
these fields: title (text), author (text), and year (integer).
5. Read books.csv and insert its data into the book table.
6. Select and print the title column from the book table in alphabetical order.
7. From the book table, select and print all columns in the order of publication.
8. Use the sqlalchemy module to connect to the sqlite3 database books.db that you just made in
exercise 6.
9. Install the Redis server and the Python redis library (pip install redis) on your computer. Create a
Redis hash called test with the fields count (1) and name (&#39;Fester Bestertester&#39;). Print all the fields for
test.
10. Increment the count field of test and print it.

**PythonBasics_21**

1. Add the current date to the text file today.txt as a string.
2. Read the text file today.txt into the string today_string
3. Parse the date from today_string.
4. List the files in your current directory
5. Create a list of all of the files in your parent directory (minimum five files should be available).
6. Use multiprocessing to create three separate processes. Make each one wait a random number of
seconds between one and five, print the current time, and then exit.
7. Create a date object of your day of birth.
8. What day of the week was your day of birth?
9. When will you be (or when were you) 10,000 days old?

**PythonBasics_22**

1. What is the result of the code, and explain?

&gt;&gt;&gt; X = &#39;iNeuron&#39;
&gt;&gt;&gt; def func():
print(X)

&gt;&gt;&gt; func()

2. What is the result of the code, and explain?

&gt;&gt;&gt; X = &#39;iNeuron&#39;
&gt;&gt;&gt; def func():
X = &#39;NI!&#39;

&gt;&gt;&gt; func()
&gt;&gt;&gt; print(X)

3. What does this code print, and why?

&gt;&gt;&gt; X = &#39;iNeuron&#39;
&gt;&gt;&gt; def func():
X = &#39;NI&#39;
print(X)

&gt;&gt;&gt; func()
&gt;&gt;&gt; print(X)

4. What output does this code produce? Why?

&gt;&gt;&gt; X = &#39;iNeuron&#39;
&gt;&gt;&gt; def func():
global X
X = &#39;NI&#39;

&gt;&gt;&gt; func()
&gt;&gt;&gt; print(X)

5. What about this code—what’s the output, and why?

&gt;&gt;&gt; X = &#39;iNeuron&#39;
&gt;&gt;&gt; def func():
X = &#39;NI&#39;
def nested():
print(X)
nested()

&gt;&gt;&gt; func()
&gt;&gt;&gt; X

6. How about this code: what is its output in Python 3, and explain?

&gt;&gt;&gt; def func():
X = &#39;NI&#39;
def nested():
nonlocal X
X = &#39;Spam&#39;
nested()
print(X)

&gt;&gt;&gt; func()

**PythonBasics_23**

1. What is the result of the code, and why?
&gt;&gt;&gt; def func(a, b=6, c=8):
print(a, b, c)
&gt;&gt;&gt; func(1, 2)
2. What is the result of this code, and why?
&gt;&gt;&gt; def func(a, b, c=5):
print(a, b, c)
&gt;&gt;&gt; func(1, c=3, b=2)
3. How about this code: what is its result, and why?
&gt;&gt;&gt; def func(a, *pargs):
print(a, pargs)
&gt;&gt;&gt; func(1, 2, 3)
4. What does this code print, and why?
&gt;&gt;&gt; def func(a, **kargs):
print(a, kargs)
&gt;&gt;&gt; func(a=1, c=3, b=2)
5. What gets printed by this, and explain?
&gt;&gt;&gt; def func(a, b, c=8, d=5): print(a, b, c, d)
&gt;&gt;&gt; func(1, *(5, 6))
6. what is the result of this, and explain?
&gt;&gt;&gt; def func(a, b, c): a = 2; b[0] = &#39;x&#39;; c[&#39;a&#39;] = &#39;y&#39;
&gt;&gt;&gt; l=1; m=[1]; n={&#39;a&#39;:0}
&gt;&gt;&gt; func(l, m, n)

&gt;&gt;&gt; l, m, n


**PythonBasics_24**

1. What is the relationship between def statements and lambda expressions ?
2. What is the benefit of lambda?
3. Compare and contrast map, filter, and reduce.
4. What are function annotations, and how are they used?
5. What are recursive functions, and how are they used?
6. What are some general design guidelines for coding functions?
7. Name three or more ways that functions can communicate results to a caller.

**PythonBasics_25**

1) . What is the difference between enclosing a list comprehension in square brackets and
parentheses?
2) What is the relationship between generators and iterators?
3) What are the signs that a function is a generator function?
4) What is the purpose of a yield statement?
5) What is the relationship between map calls and list comprehensions? Make a comparison and
contrast between the two.


