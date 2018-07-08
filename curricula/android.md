# Pursuit - Access Code

## AC 5.4 Android Development Standards

## Introduction

This curriculum is developed under the pretense that entering fellows will have no prior knowledge of Software Development (specifically Java or Android) beyond what was introduced to them during the two-day Javascript intensive/workshop prior to the offer of admission. 

The Pursuit Android Development Fellowship Technical Mastery facet begins with the fundamentals of the Java programming language (Java 8), and introductory Object-Oriented Programming (OOP) paradigms in Unit 1, in conjunction with POSIX-styled command line version control (Git and Github) and JetBrains IDE development skills (Intellij IDEA and Android Studio, respectively). 

Units 2 through 6 will focus primarily on the design and development of a number of group-based Android Applications, bookended by a Practical assessment.

From the start of Unit 7, Android fellows will have built a group project under the crucible of a two-day hackathon challenge, along with a group capstone project culminating in a public presentation, and a personal portfolio project up until commencement (the end of Unit 10), to round off their academic prospectus. 

Parallel to the Android development course, fellows will have a competitive level of exposure to data structures and algorithms materials, to prepare them for both whiteboarding interviews and over-the-phone/codeshare technical interviews.

## Unit 1 - Java and OOP Fundamentals

<details>
<summary>Setting up the Java development environment</summary>
<ul>
<li>Installing the JDK/JRE</li>
<li>Installing Intellij IDEA</li>
<li>Installing Android Studio</li>
<li>Signing up for Repl.it, HackerRank, Canvas, Slack, StackOverflow, Trello/Waffle.io, etc.</li>
<li>Setting Up Local Git Environment, including Username, Email, and SSH Keys</li>
</ul>
</details>
<details>
<summary>Introduction To Java: the JVM, variables, and primitive types</summary>
<ul>
<li>The JVM, JRE, and the JDK</li>
	<ul>
	We expect fellows to be aware that:
		<li>Java Virtual Machines are written for almost every computer on the planet</li>
		<li>Java code is compiled to Java ByteCode, and runs on the Java Virtual Machine<li>
		<li>The JVM and libraries that help write Java code are a part of the Java Runtime Environment (JRE)</li>
		<li>The JVM and the JRE are contained in the Java Development Kit (JDK)</li>
	</ul>
<li>Writing Java in a Text Editor</li>
	<ul>
	We expect fellows to know that:
		<li>Java code is just a text file with a .java extension</li>
		<li>Java code must be compiled to bytecode before it can run on the JVM</li>
	</ul>
<li>Compiling Java Code with JavaC</li>
	<ul>
	We expect fellows to know that:
		<li>Java code is compiled to .class files with bytecode by running either javac on the command line, or by an IDE</li>
		<li>Java programs (compiled .class files) can be run directly from the command line</li>
	</ul>
<li>Printing Data from the Main Method</li>
	<ul>
	We expect fellows to understand that:
		<li>Java programs execute the code found in the main(String[] args) method of a java file first</li>
		<li>System.out.print(); is used to print on the same line of the output screen</li>
		<li>System.out.println(); is used to print on the next line of the output screen</li>
		<li>System.out.printf(); is used to print values passed in to placeholders</li>
	</ul>
<li>Concatenating Strings vs. Arithmetic Addition</li>
	<ul>
	We expect fellows to differentiate between:
		<li>printing the result of an evaluated arithmetic expression, and concatenating two string values together</li>
		<li>type inference when concatenating a String to a non-string primitive, and the error that occurs when trying to evaluate the expression of a number added to a String</li>
	</ul>
<li>Writing Comments</li>
	<ul>
	We expect fellows to be able to:
		<li>write single-line comments in code by using //</li>	
		<li>write multi-line comments in code by using /* and */</li>
	</ul>
<li>Variable Assignment, Primitive Types, and Memory Size</li>
	<ul>
	We expect fellows to understand that:
		<li>All variables must be of a certain type</li>
		<li>Java has eight primitive types: byte, short, int, long, float, double, char, and boolean</li>
		<li>Variables are declared by giving them a type and a name</li>
		<li>Variables are assigned by adding =, followed by a value</li>
		<li>Unassigned variables have default values (0, 0.0, false, '\u0000', etc.)</li>
		<li>Assigning too big a primitive value into a variable with too small of a type will result in an error</li>
		<li>All whole numbers are by default int values, unless otherwise defined during assignment by a primitive suffix (b, s, l)
		<li>All decimal numbers are by default double values, unless otherwise defined during assignment by a primitive suffix (f)
		<li>Assigning a primitive value to a variable of a different primitive type will result in an error (unless casted, or modified with a primitive suffix)</li>
		<li>Variables are stored in memory before a program runs, and different types take up different amounts of memory</li>
	</ul>
<li>integer Division vs float Division</li>
	<ul>
	We expect fellows to understand that:
		<li>Division between two whole numbers will result in a whole number (int)</li>
		<li>Division between at least one decimal number will result in a decimal number (double)</li>
	</ul>
<li>Primitive Casting chars to ints, and back</li>
	<ul>
	We expect fellows to be aware that:
		<li>A char can have a raw int value, a unicode value, or be a character wrapped in single quotes 'A'</li>
		<li>A char can be cast into an int, and vice versa</li>
	</ul>
<li>Naming Conventions: camelCase, PascalCase, and SNAKE_CASE</li>
	<ul>
	We expect the fellows to effectively understand that:
		<li>Variable names are declared in camelCase</li>
		<li>Class names (like "Main") are written in PascalCase</li>
		<li>Constant names (variables with immutable or unchanging values) are written in SNAKE_CASE</li>
		<li>The first character of variable names can only be a letter, a dolar sign ($), or an underscore (_), but the latter two are rarely used</li>
		<li>Words from the keyword list can never be used as single variable names</li>
	</ul>
</ul>
</details>
<details>
<summary>Control Structures and Logical Operators</summary>
<ul>
<li>booleans in-depth</li>
	<ul>
	We expect the fellows to know that:
		<li>boolean variables can only be either "true" or "false"</li>
		<li>Arithmetic expressions can result to true or false values</li>
		<li>Arithmetic comparisons like greater than (>), less than (<), equal to (==), greater than or equal to (>=), or less than or equal to (<=) can also result in true or false values</li>
	</ul>
<li>Assignment vs. Comparison</li>
	<ul>
	We expect the fellows to differentiate between:
		<li>Single equals (=) for assignment, and double equals (==) for comparison</li>
	</ul>
<li>Sentential Logical Operators</li>
	<ul>
	We expect the fellows to be aware that:
		<li>AND logical operators are represented with double ampersands (&&), meaning the values evaluated before and after the && must both be true in order for the entire statement to evaluate to true</li>
		<li>OR logical operators are represented with double pipes (||), meaning that either the value evaluated before or after the || must be true in order for the entire statement to evaluate to true</li>
		<li>IS logical operators are represented with double equals (==), meaning that the value evaluated before the == must be equal to the value after the ==, in order for the entire statement to evaluate to true</li>
		<li>NOT logical operators are represented with bang equals (!=), meaning that the value evaluated before the != must NOT be equal to the value after the ==, in order for the entire statement to evaluate to true</li>
		<li>NEGATION logical operators are represented with a single bang (!) placed in front of either a boolean literal wrapped in parentheses, or a variable containing a boolean value, meaning that whatever the current boolean value is, it is now the opposite; i.e.: !(true) == false, or !(false) == true</li>
	</ul>
<li>If Statements</li>
	<ul>
	We expect fellows to:
		<li>Create static code blocks using opening and closing curly brackets</li>
		<li>Create an If statement, and understand that the condition placed within the parentheses must evaluate to true, in order for the code within the code block to run</li>
	</ul>
<li>Else Statements</li>
	<ul>
	We expect fellows to:
		<li>Create an If statement with a following Else statement, to run code in its code block ONLY if the condition within the If statement's parentheses evaluates to false</li>
	</ul>
<li>Else If Statements</li>
	<ul>
	We expect fellows to:
		<li>Create an Else If statement in addition to a preceding If statement, to run code in its code block ONLY if the condition within the If statement's parentheses evaluates to true, AND if the condition within the If statement's parentheses evaluates to false</li>
	</ul>
<li>Ternary operator expressions for Assigning boolean values</li>
	<ul>
	We expect fellows to:
		<li>Create Ternary operator expressions, where the result of the expression is immediately assigned to a boolean type variable</li>
	</ul>
<li>Switch Statements</li>
	<ul>
	We expect fellows to:
		<li>Create switch statements, which evaluate a variable's value, compare it to a predefined list of possible cases, add a break statement to each case (unless otherwise expected), and account for the possibility that a case may appear which is not accounted for, by using a default case</li>
		<li>be able to determine what will happen to the flow of execution should a break statement be left out of a particular case</li>
		<li>be able to determine what will happen to the flow of execution should a default case not be explictly defined</li>
	</ul>
</ul>
</details>
<details>
<summary>While Loops and Do-While Loops</summary>
<li>While Loops as If Statements that run more than once</li>
	<ul>
	We expect fellows to understand that:
		<li>a While loop is essentially an If statement which runs the code within its code block multiple times if its condition evaluates to true, and remains true after the code block is executed in its entirety</li>
	</ul>
<li>While Loop Conditions</li>
	<ul>
	We expect fellows to understand that:
		<li>the code within a While loop will run in its entirety over and over again as long as the condition within the parentheses continues to evaluate to true. Each complete execution of the while loop's code block is called an iteration</li>
	</ul>
<li>Infinite Loops</li>
	<ul>
	We expect fellows to be aware of the fact that:
		<li>the code within a While loop will run for an effectively infinite number of times if the condition for the while loop is not altered in such a way as to eventually evaluate to false</li>
	</ul>
<li>break and continue keywords in Loops</li>
	<ul>
	We expect fellows to understand that:
		<li>non-incrementing flow control for loops can be managed by the use of either continue or break statements</li>
		<li>continue statements are utilized when code below the continue statement within the scope of the while loop should be ignored, and a new iteration should be executed</li>
		<li>break statements are utilized when code below the break statement within the scope of the while loop should be ignored, and the loop should be broken, cancelling all future possible iterations of that particular while loop</li>
	</ul>
<li>Do-While Loops, or Loops that run once before checking a condition</li>
	<ul>
	We expect fellows to understand that:
		<li>Do-While loops are effectively whule loops, with code blocks that are executed at least once, regardless of whether the conditional of the while loop intitially evaluates to true</li>
	</ul>
</details>
<details>
<summary>Strings and For Loops</summary>
<li>Strings vs. primitive types</li>
	<ul>
	We expect fellows to mark the distinction between:
		<li>Object types, like String, which begin with a capital letter (Pascal Case), while primitive types are all written in lower case</li>
	</ul>
<li>Calling Methods on Strings: charAt(), length(), and .equals()</li>
	<ul>
	We expect fellows to write code which can:
		<li>access an individual character from a String utilizing the .charAt() method, and passing in the particular location of that character by its index as an argument, where 0 is the index of the first character, 1 is the index of the second character, etc.</li>
		<li>aquire the number of characters within the String by calling the length() method, and understanding that the index of the last character in the String will always be equal to the value of the .length() method call,minus the integer one (1)</li>
		<li>compare to Strings to see if they are equivalent in value by calling the .equals() method on one of the Strings, then passing in another String as an argument to compare the two</li>
	</ul>
<li>The For Loop, or a more elegant While Loop</li>
	<ul>
	We expect fellows to appreciate the elegance of the For loop, which:
		<li>initializes the counter variable within its parentheses, rather than outside the scope of the loop</li>
		<li>modifies its incremented/decremented counter variable within its parentheses, rather than inside the loop's code block</li>
		<li>avoids the concerns of an infinite loop, or indexOutOfBounds Exception with a termination condition</li>
	</ul>
<li>Parts of a For Loop: counter variable declaration, termination condition, and increment/decrement statement</li>
	<ul>
	We expect fellows to create a for loop where:
		<li>a counter variable of type int is initialized with a positive whole number</li>
		<li>a termination condition which evaluates to true as long as the counter variable is greater than, less than, or equal to a value reachable through eventual iteration within the scope of the loop</li>
		<li>an increment/decrement statement, which intends to either increase or decrease the value of the counter value to a point where the termination condition will eventually evaluate to false</li>
	</ul>
<li>Types of increment/decrement statements</li>
	<ul>
		We expect fellows to understand the distinction between:
		<li>counter = counter + 1: where a counter variable is reassigned a value based on its previous value plus a new value, every time that code block is run</li>
		<li>counter += 1: where a counter variable is reassigned a value based on its previous value plus a new value, every time that code block is run</li>
		<li>++counter: where a counter variable is reassigned a value based on its previous value plus the int one (1), PRIOR to the beginning of every iteration</li>
		<li>counter++: where a counter variable is reassigned a value based on its previous value plus the int one (1), every time that iteration is run ONLY WHEN IT HAS REACHED COMPLETION</li>
	</ul>
</details>
<details>
<summary>Static and Instance Methods and Fields</summary>
<ul>
<li>Classes as Blueprints for "Custom" Types</li>
<li>Static Properties of a Class</li>
<li>Non-Static Properties of a Class</li>
<li>Methods are Functions that can only exist as part of a Class</li>
<li>Method return types, or returning something (primitive/class type) vs. returning nothing (void)</li>
<li>Static Methods vs. Non-Static Methods</li>
<li>Method Parameters and Parameter Types</li>
<li>Method Overloading</li>
<li>Getting input from the user</li>
</ul>
</details>
<details>
<summary>Concrete Classes, Access Modifiers, and Encapsulation</summary>
<li>The Three Pillars of Java OOP</li>
<li>Encapsulation, or "Keeping your Organs in you Body"</li>
<li>"private" fields and "public" getter/setter methods</li>
<li>Instantiation, and creating instance objects with the "new" keyword</li>
<li>Default Constructors, Explicit Constructors, and Overloaded Constructors</li>
<li></li>
</details>
<details>
<summary>Abstract Classes and Inheritance</summary>
</details>
<details>
<summary>Interfaces and Polymorphism</summary>
</details>
<details>
<summary>Immutable Arrays, ArrayLists, Maps, and Sets</summary>
</details>
<details>
<summary>Generics and Type Erasure</summary>
</details>
<details>
<summary>Try/Catch Blocks, and Exception Handling</summary>
</details>
<details>
<summary>Introduction to Version Control and Basic POSIX command line tools (Git, Grep, Bash, etc)</summary>
</details>

## Unit 2 - XML Layout Design, Activity Lifecycle, and RecyclerView Management

## Unit 3 - APIs, JSON, Retrofit, and Threading (Concurrency and Parallelism)

## Unit 4 - Fragments, Services, Animation, and Notifications

## Unit 5 - SQLiteOpenHelper, Firebase, and JetPack (Architecture Components)

## Unit 6 - Practical Exams

## Unit 7 - Personal Portfolio Projects

## Unit 8 - Hackathon and Assessment Retakes (as needed)

## Unit 9 - Capstone Project and Demo Day

## Unit 10 - Job Search, Portfolio Cleanup, and Commencement
