1. Debit Card Number 

Write a program, which receives **4****integers** on the console and **prints them** in **4-digit
debit card format**. See the examples below for the appropriate
formatting.

#### Examples


**Input**

12

433

1

5331

 **Output**

0012 0433 0001 5331


 
**Input**

9182

4221

12

3

  **Output**

9182 4221 0012 0003

 
 
 **Input**

812

321

123

22

  **Output**

0812 0321 0123 0022





2. Rectangle Area 

Write a program, which calculates a
**rectangle’s area**, based on its **width** and **height**.
The **width** and **height** come as floating point numbers on
the console, **formatted to the 2**

**nd****
character after the decimal point**.

#### Examples

 

**Input**

2

7

 **Output**

14.00

 

 **Input**
 
7

8

  **Output**

56.00



**Input** 

12.33

5

  **Output**

61.65





3. Miles to Kilometers 

Write a program, which **converts****miles** to **kilometers**. **Format** the output to the
**2**

**nd**** decimal place**.

Note: **1 mile == 1.60934 kilometers**

#### Examples

 

**Input**

 60

**Output**

 96.56

**Input**

 1

**Output**

 1.61

**Input**

 52.1113

**Output**

 83.86

 



4. Beverage Labels 

Write a program, which reads a food
product **name**, **volume**, **energy content****per
100ml** and **sugar content per 100ml**. Calculate the **energy**
and **sugar content** for the **given volume** and print them
on the console in the following format:

- Name – as per the input 
- Volume – **integer**,
	**suffixed** by “**ml**” (e.g. “**220ml**”) 
- Energy content – **integer**,
	**suffixed** by “**kcal**” (e.g. “**500kcal**”) 
- Sugar content – **integer**,
	**suffixed** by “**g**” (e.g. “**30g**”) 
	 

#### Examples

 

**Input**

Nuka-Cola

220

300

70

 **Output**

220ml	Nuka-Cola:

660kcal, 154g sugars

 

**Input**

Ice	Cold Nuka-Cola

250

350

65

 **Output**

250ml	Ice Cold Nuka-Cola:

875kcal, 162.5g sugars

 

**Input**

Nuka-Cola	Quantum

350

600

140

 **Output**

350ml	Nuka-Cola Quantum:

2100kcal, 490g sugars





5. * Character Stats 

Write a program, which **displays
information** about a video game character. You will receive their
**name**, **current health**, **maximum health**, **current
energy** and **maximum energy **on separate lines. The **current**
values will **always** be valid (**equal or lower** than their
respective **max** values). Print them in the format as per the
examples.

#### Examples

 

**Input** 

Mayro

5

10

9

10

**Output** 

Name:	Mayro

Health:	||||||.....|

Energy: ||||||||||.|

 **Input**

Bauser

10

10

10

10

 **Output**

Name:	Bauser

Health:	||||||||||||

Energy: ||||||||||||

 

**Input** 

Loogi

8

20

2

14

 **Output**

Name:	Loogi

Health:	|||||||||............|

Energy: |||............|

 **Input**

Toad

0

5

0

10

 **Output**

Name:	Toad

Health:	|.....|

Energy: |..........|

#### Hints

- []()You can
	print a character **multiple** times, using **new
	string(character, count)**.
