# Bug Log

**Name:** Zackary Santos

Fill in one row for every bug you find and fix in `Program.cs`. There are
**33 bugs**: 12 syntax, 5 runtime, 16 logic. Keep the rows in line-number order
if you can.

**Kind** must be one of: `Syntax`, `Runtime`, `Logic`.

The first row is a worked example of the level of detail expected (it is **not** one of the 33 bugs).

| # | Section | Line | Kind | What was wrong | How I fixed it |

1 - Section 1 | 32 | Syntax | Missing Quotation Lines next to Exclamation Mark, causing the program to crash from incomplete code | I added the missing quotating marks
2 - Section 6 | 201 | Syntax | Missing Colon at end of line, causing the program to crash from incomplete code | I added a Colon to fix it
3 - Section 2 | 56 | Syntax | Missing Parenthesis next to ReadLine, causing the program to crash from incomplete code | I added Parenthesis to it
4 - Section 3 | 97 | Syntax | int was capitalized and not lowercase, causing the program to crash since it did not recognize int when it was capitalized | Changed capital I to lowercase
5 - Section 3 | 106 | Syntax | Equal Sign missing in if statement when comparing codeGuess and secretCode, causing a crash due to the code not being able to compare the both of them | added 2nd equal sign to if statement
6 - Section 5 | 104 | Syntax | totalFuel was spelled wrong in the Console.WriteLine(), causing a crash since the program didnt recognize it when it was misspelled | Respelled codeFuel
7 - Section 8 | 241 | Syntax | while loop was missing parenthesis in front of it, causing a crash | added parenthesis between 'pings <= 5'
8 - Section 9 | 263 | Syntax | Line had commas intead of colons, causing a crash when testing | replaced commas with colons
9 - Section 10 | 285 | Syntax | Console.WriteLine was using single quotes and not double quotes, causing a crash since the program did not recognize the WriteLine text | Replaced single quotes with double quotes
10 - Section 10 | 295 | Syntax | missing end bracket for else statement, causing a crash since it was incomplete code | Added end bracket
11 - Section 12 | 329 | Syntax | WriteLine was misspelled. line was not capitalized, causing a crash since the program did not recognize WriteLine when the l was lowercase | changed the lowercase l to an uppercase one
12 - Section 6 | 217 | Syntax | Line had a plus sign instead of an equal sign | replaced the plus sign with an equal sign
13 - Section 1 | 35 | Runtime | line was using char instead of int when using .Length and had .Length in brackets as well, causing the program to break | changed 'char' to int and changed crewName[crewName.Length] to simply crewName.Length
14 - Section 2 | 57 | Runtime | crewName was in .Parse parenthesis, causing the program to break | changed 'crewName' to 'age'
15 - Section 4 | 141 | Runtime | in For Loop, the comparison sign was "greater or equal to" and not "greater then", casuing the program to break since for loops dont use greater or equal to signs | removed the equal sign, turning it into a greater than comparison
16 - Section 5 | 169 | Logic | For Loop only counted 4 tanks instead of 5, causing the 5th tank to be skipped | in the for loop, I changed 'tank < 5' to 'tank < 6'
17 - Section 5 | 174 | Logic | totalFuel = level was missing a +, causing the tanks to not be added | added a + to the code line so tanks can be added
18 - Section 5 | 182 | Logic | averageFuel was dividing by 5 and not 5.0, causing the decimal to not show up | added .0 next to the 5
19 - Section 8 | 244 | Logic | an infinite loop was happening because pings were not counted properly | Added 'pings = pings + 1' under the code line to break the loop and make it count pings properly
20 - Section 7 | 228 | Countdown was ending at 2 instead of 1 because the condition was set to 1 and not 0 | I changed the 1 to a 0
21 - Section 6 | 205 | Logic | subTotal was adding packPrice and quantity, instead of multiplying them, causing the subtotal to be 15 and not 36 | I changed the addition symbol to the multiplication symbol
22
23
24
25
26
27
28
29
30
31
32
33

## Reflection (a few sentences)

Which bug took you the longest to find, and why?

Which kind of bug (syntax, runtime, logic) do you think is the hardest to catch? Why?
