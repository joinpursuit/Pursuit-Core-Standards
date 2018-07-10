# Pursuit - Access Code

## AC 5.4 Android Development Standards

## Introduction

This curriculum is developed under the pretense that entering fellows will have no prior knowledge of Software Development (specifically Java or Android) beyond what was introduced to them during the two-day Javascript intensive/workshop prior to the offer of admission. 

The Pursuit Android Development Fellowship Technical Mastery facet begins with the fundamentals of the Java programming language (Java 8), and introductory Object-Oriented Programming (OOP) paradigms in Unit 1, in conjunction with POSIX-styled command line version control (Git and Github) and JetBrains IDE development skills (Intellij IDEA and Android Studio, respectively). 

Units 2 through 6 will focus primarily on the design and development of a number of group-based Android Applications, bookended by a Practical assessment.

From the start of Unit 7, Android fellows will have built a group project under the crucible of a two-day hackathon challenge, along with a group capstone project culminating in a public presentation, and the completion of a personal portfolio project up until commencement (the end of Unit 10), to round off their academic prospectus. 

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
		<li>Java code is compiled to Java ByteCode, and runs on the Java Virtual Machine</li>
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
		<li>Java files exist within unique "packages"</li>
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
		<li>NOT logical operators are represented with bang equals (!=), meaning that the value evaluated before the != must NOT be equal to the value after the !=, in order for the entire statement to evaluate to true</li>
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
		<li>Create Ternary operator expressions, which are less verbose if-else statements, where the result of the expression is immediately assigned to a variable, i.e.: String voterStatus = (age >= 18) ? "voter" : "non-voter"</li>
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
<ul>
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
		<li>Do-While loops are effectively while loops, with code blocks that are executed at least once, regardless of whether the conditional of the while loop intitially evaluates to true</li>
	</ul>
</ul>
</details>
<details>
<summary>Strings and For Loops</summary>
<ul>
<li>Strings vs. primitive types</li>
	<ul>
	We expect fellows to mark the distinction between:
		<li>Object types, like String, begin with a capital letter (Pascal Case), while primitive types are all written in lowercase</li>
	</ul>
<li>Calling Methods on Strings: charAt(), length(), and .equals()</li>
	<ul>
	We expect fellows to write code which can:
		<li>access an individual character from a String utilizing the .charAt() method, and passing in the particular location of that character by its index as an argument, where 0 is the index of the first character, 1 is the index of the second character, etc.</li>
		<li>aquire the number of characters within the String by calling the length() method, and understanding that the index of the last character in the String will always be equal to the value of the .length() method call, minus the integer one (1)</li>
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
</ul>
</details>
<details>
<summary>Static and Instance Methods and Fields</summary>
<ul>
<li>Classes as Blueprints for "Custom" Types</li>
	<ul>
	We expect fellows to analogize the construct of a Class as:
		<li>a blueprint for the composition of an original data type</li>
		<li>a way to create a variable that can store values in other variables</li>
		<li>a way to create a variable that exhibits unique behaviors</li>
	</ul>
<li>Static Properties of a Class</li>
	<ul>
	We expect fellows to discover that:
		<li>properties, or public fields of a class can be accessed statically, but private fields cannot</li>
		<li>static fields belong to a class, which means that you have to call the field on the class itself, i.e.: Main.myField = "hello";</li>
	</ul>
<li>Non-Static Properties of a Class</li>
	<ul>
	We expect fellows to discover that:
		<li>properties, or public fields of a class's instance are called member variables</li>
		<li>properties, or public fields of a class's instance cannot be accessed statically, but instead an instance must be made, i.e.: Main main = new Main(); main.myField = "hello";</li>
		<li>non-static member variables, unless assigned, will have the default values for their data type</li>
		<li>non-static member variables are unique, and different from instance to instance, whereas static fields are shared by all instances of a class</li>
	</ul>
<li>Methods are Functions that can only exist as part of a Class</li>
	<ul>
	We expect fellows to realize that:
		<li>unlike JavaScript, functions cannot exist outside of the constructs of a class</li>
		<li>functions that are defined as part of a class are called Methods</li>
	</ul>
<li>Method return types, or returning something (primitive/class type) vs. returning nothing (void)</li>
	<ul>
	We expect fellows to understand that:
		<li>all methods have return types, which are declared in their Method signatures</li>
		<li>methods that return a value after execution have a return type of either an object or primitive type</li>
		<li>methods that are not expected to return a value after execution have a return type of void</li>
	</ul>
<li>Static Methods vs. Non-Static Methods</li>
	<ul>
	We expect fellows to understand that:
		<li>static methods belong to a class, which means that you have to call the method on the class itself, i.e.: Main.myMethod();</li>
		<li>non-static methods cannot be called on the class, they must only be called on an instance of the class, i.e.: Main main = new Main(); main.myMethod();</li>
	</ul>
</ul>
<li>Method Parameters and Parameter Types</li>
	<ul>
	We expect fellows to create methods:
		<li>that can accept arguments from outside the class passed in through parameters</li>
		<li>that have parameters declared with actual data types</li>
		<li>with the understanding that parameter types are the type of values that can be passed into the method via arguments, and that return types are different from parameter types</li>
	</ul>
<li>Method Overloading</li>
	<ul>
	We expect fellows to understand that:
		<li>a class can have and call multiple methods of the same method signature</li>
		<li>Java can tell the difference between these methods based on the order, number, and type of parameters in the method's signature for each method</li>
	</ul>
<li>Getting input from the user</li>
	<ul>
	We expect the fellows to be able to:
		<li>get input passed to the program as command line arguments through the args parameter in the public static void main(String[] args) method</li>
		<li>get input from the keyboard passed into an instance of the Scanner class</li>
		<li>utilize import statements whenever Java requires it</li>
	</ul>
</ul>
</details>
<details>
<summary>Concrete Classes, Access Modifiers, and Encapsulation</summary>
<ul>
<li>The Three Pillars of Java OOP</li>
	<ul>
	We expect the fellows to be aware of the three pillars of Object Oriented Programming in Java:
		<li>Encapsulation - declaring all methods and variables associated with an object's behavior and state respectively WITHIN the class itself, providing getter/setter methods rather than keeping all its fields publically accessible directly</li>
		<li>Inheritance - passing state and behavior functionality from a parent class to a child class without having to rewrite all the same fields and methods</li>
		<li>Polymorphism - the fact that classes at compile time can be defined statically as being a type of any class of which it is a child, or from which it inherits funtionality ("extends" from a class, or "implements" an interface, respectively)</li>
	</ul>
<li>Access Modifiers</li>
	<ul>
	We expect fellows to differentiate between the four access modifiers:
		<li>private: methods and fields declared as private can only be accessed from within the class they are declared</li>
		<li>public: methods and fields declared as public can be accessed from outside the class</li>
		<li>protected: methods and fields declared as protected can only be accessed from within the class they are declared, and all child classes of said class</li>
		<li>default (package-private): methods and fields declared without a specific access modifier can only be accessed from within the class they are declared, and from any other class within the same package</li>
	</ul>
<li>Encapsulation, or "Keeping your Organs in you Body"</li>
	<ul>
	We expect the fellows to:
		<li>understand that encapsulation allows for a developer to create classes that are designed to produce a desired result, while isolating that code from other blocks of code in the main(String[] args) method</li>
		<li>create classes with non-static fields, and non-static methods that exhibit behaviors upon fields within the same class</li>
	</ul>
<li>"private" fields and "public" getter/setter methods</li>
	<ul>
	We expect the fellows to:
		<li>create code where a class's member fields are declared as private</li>
		<li>compose public methods that expose those fields to code OUTSIDE of the container class (getter methods)</li>
		<li>compose public methods that allow those fields to be assigned or modified by code FROM OUTSIDE of the container class (setter methods)</li>
	</ul
<li>Instantiation, and creating instance objects with the "new" keyword</li>
	<ul>
	We expect fellows to:
		<li>understand that classes are only "blueprints", and that in order for these classes to exist uniquely in memory, we must "instantiate" them</li>
		<li>we instantiate objects or instances of a class by assigning a place for it in a block of memory, by using the "new" keyword, and calling its "constructor"</li>
		<li>understand that constructors are special methods that, when called, create objects with all the characteristics (fields and methods) described in its class definition, as a unique instance</li>
	</ul>
<li>Default Constructors, Explicit Constructors, and Overloaded Constructors</li>
	<ul>
	We expect fellows to understand that:
		<li>default constructors are available to all classes once they are defined, and can be called by using the name of the class, immediately followed by opening and closing parentheses, i.e.: new Main();</li>
		<li>once an explicit contructor is composed within a class, the default constructor becomes inaccessable, and must be replecated within a class explicitly, if so desired</li>
		<li>constructors, like methods, can have typed parameters, that are used to initialize the value of member variables or fields upon instantiation by using the "this" keyword, i.e. this.name = name;</li>
		<li>constructors, like methods, can be "overloaded", meaning a class can have and call multiple constructors with the same signature</li>
		<li>Java can tell the difference between these constructors based on the order, number, and type of parameters in the constructor's signature for each constructor</li>
	</ul>
</ul>
</details>
<details>
<summary>Abstract Classes and Inheritance, or "I have my Mama's eyes, but they're still my eyes"</summary>
<ul>
<li>Inheriting Characteristics from Parent Classes</li>	
	<ul>
	We expect fellows to understand that:
		<li>a developer can compose a class defined as a child of a parent class by using the "extends" keyword</li>
		<li>Inheritance is the act of passing state and behavior functionality from a parent class to a child class without having to rewrite all the same fields and methods</li>
		<li>unless the fields are static, all state and behavior characteristics will only affect change in the child class's instances, not the parent's instances</li>
		<li>if a child class's inherited methods are intended to be updated, they can be "overridden", and modified with a call to "super" to retain the parent method's original funtionality, followed by new code</li>
		<li>if a child class's inherited methods are intended to be replaced, they can be "overridden", and modified WITHOUT a call to "super", followed by new code</li>
		<li>a child class can only inherit characteristics from a single parent class, i.e.: class Child extends Parent</li>
	</ul>
<li>Abstract Classes vs. Concrete Classes</li>	
	<ul>
	We expect fellows to understand that:
		<li>unlike concrete classes, Abstract Classes should NOT be directly instantiated, but rather extended by child classes which are then themselves instantiated</li>
		<li>abstract classes are defined as "abstract" in their class definitions</li>
		<li>abstract classes can have both methods with signatures and definitions, or methods with only method signatures - method signatures without method definitions must be defined as "abstract"</li>
		<li>abstract methods must be implemented in child classes that extend the abstract class by "overriding" them, and adding method definition code blocks that return a value matching the method signature's return type</li>
		<li>abstract classes should never be defined with the "final" keyword, since it would prevent the abstract class from being "extended" by child classes</li>
	</ul>
</ul>
</details>
<details>
<summary>Interfaces and Polymorphism, or "I'm a Human that does Human stuff, but I'm also an Animal that does Animal stuff (sometimes in Human ways), and although a Lizard is also an Animal that does Animal stuff (sometimes in Lizard ways), I'm NOT also a Lizard that does Lizard stuff, NOR am I an Animal that does Animal stuff in Lizard ways"</summary>
<ul>
<li>Polymorphism in Java</li>
	<ul>
	We expect fellows to understand that:
		<li>the static type of an object is the type on the left side of the assignment (known at compile time), and the dynamic type of an object is the type of the class used as the constructor</li>
		<li>a child class, at compile time, can be defined statically as being a type of any class of which it is a child, or from which it inherits funtionality ("extends" from a parent class, or "implements" an interface, respectively), i.e.: Animal human = new Human();</li>
		<li>a child class assigned in this way has limited funtionality, and can only expose the methods it shares with the parent class to which it is statically typed</li>
		<li>a child class previously instantiated with a static type of itself, can be "upcasted" to its parent's type safely, i.e.: Human human = new Human(); Animal animal = (Animal) human;</li>
		<li>a parent class previously instantiated with a static type of itself, can be "downcasted" to its child's type, but with possible risks - since there is no guarantee that the parent will have the child's funtionality at runtime, i.e.: Animal animal = new Human(); Human human = (Human) animal; [OKAY] Animal animal = new Animal(); Human human = (Human) animal; [BAD]</li>
	</ul>
<li>Interfaces vs. Abstract Classes</li>
	<ul>
	We expect fellows to understand that:
		<li>interfaces are similar to abstract classes in that interface methods are simply method signatures, like abstract methods</li>
		<li>interface methods are all only method signatures, and interfaces can only contain method signatures</li>
		<li>interface methods must be implemented in classes that implement the interface by "overriding" the method signatures, and adding method definition code blocks that return a value matching the method signature's return type</li>
		<li>although child classes can only extend from a single class, child classes can implement a countless number of interfaces, i.e.: class Bird extends Animal implements Flight, Feathers, Nests</li>
	</ul>
<li>Anonymous Class Instances</li>
	<ul>
	We expect fellows be aware of the fact that:
		<li>anonymous class instances can be used to override methods within concrete parent classes as-needed without having to subclass them</li>
		<li>anonymous class instances can be used to add definitions to the method signatures of abstract classes or interfaces as-needed without having to subclass them, as they typically should not be instantiated, but rather subclassed</li>
		<li>anonymous classes and lambdas in Java are effectively interchangeable</li>
	</ul>
</ul>
</details>
<details>
<summary>Data Structures and Collections in Java</summary>
<ul>
<li>Arrays in Java</li>
	<ul>
	We expect fellows to understand that:
		<li>array indices, like Strings, begin at index 0 - where the first element of the array is at index 0, the second element is at index 1, etc.</li>
		<li>array static types are defined as the type of the elements the array intends to store, followed by square brackets, i.e.: int[] numArray; String[] stringArray;</li>
		<li>array assignment may be made in two ways - by size: int[] numArray = new int[3]; or by adding elements at assignment: String[] stringArray = {"Adam", "Becky", "Carl"};</li>
		<li>arrays take up a contiguous space in memory, and its size cannot change after assignment (cannot add new elements), only the values of the elements stored at each index. This makes arrays immutable</li>
		<li>array elements can be accessed by passing an index number into square brackets to the right of the variable name: numArray[2] = 42; System.out.println(stringArray[0]);</li>
		<li>where Strings can have the method length() called upon them to return the number of characters, the number of elements in an Array is retreived by calling the actual parameter "length", not a method called "length()</li>
		<li>like Strings, the index of the last element in an Array will always be equal to the value of the .length() property call, minus the integer one (1)</li>
	</ul>
<li>Abstract Data Types</li>
	<ul>
	We expect fellows to be aware of the fact that:
		<li>Abstract Data Types such as Lists, Maps, Sets, Stacks, and Queues are concepts for how a program can store, organize and retrieve data, while actual data structures are the implementations of these concepts in code form</li>
	</ul>
<li>Importing packages in Java</li>
	<ul>
	We expect fellows to understand that:
		<li>the Collections library, and various other data structures come standard in the JDK since Java 6, and can be brought into a project using an import statement, i.e. import java.util.*;</li>
	</ul>
<li>Lists and ArrayLists</li>
	<ul>
	We expect fellows to understand that:
		<li>a List is a way to organize data cardinally in a row, while data structures like ArrayLists and LinkedLists are used to organize a mutable array of objects</li>
		<li>ArrayLists have methods which are different from Arrays or Strings, such as size(), add(), get(), set(), and remove()</li>
		<li>Lists utilize a single parameterized generic type wrapped in angle brackets, to describe the objects stored in them, and primitive type variables are autoboxed to their object forms (char becomes Character, int become Integer, etc.), i.e.: ArrayList&lt;Double&gt; degreesList = new ArrayList&lt;&gt;();</li>
	</ul>
<li>Maps and HashMaps</li>
	<ul>
	We expect fellows to understand that:
		<li>a Map is a way to organize data into key/value pairs like a dictionary word and its corresponding definition, while data structures like HashMaps are an unordered associative array of objects made up of key/value pairs</li>
		<li>HashMaps have methods which are similar to ArrayLists, such as size(), get(), and remove(), but also have a put() method, for adding new entries, keySet(), for retrieving all the keys in a HashMap, and containsValue(), for checking if a value exists in the HashMap()</li>
		<li>when calling get() on a HashMap instance, if the value returned after passing in a key comes back as "null", then the key does not exist in the HashMap</li>
		<li>all keys in a HashMap must be unique, but more than one key can have the same value</li>
		<li>when calling put() on a HashMap, if the key passed into the method already exists in the HashMap, a new entry will not be created - rather, the old entry with that key will have it's value changed to the new value</li>
		<li>Maps utilize two parameterized generic types wrapped in angle brackets, to describe the keys and values stored in them respectively, and primitive type variables are autoboxed to their object forms (char becomes Character, int become Integer, etc.), i.e.: HashMap&lt;String, Integer&gt; nameAgeMap = new HashMap&lt;&gt;();</li>
	</ul>
<li>Sets and HashSets</li>
	<ul>
	We expect fellows to understand that:
		<li>a Set is a way to store a collection of unique items, while data structures like HashSets are collections of unordered, unique objects</li>
		<li>HashSets have methods such as size(), contains(), add(), remove(), isEmpty(), and clear(), and are good alternatives to HashMaps when writing algorithms which require storing unique objects only</li>
		<li>HashSets utilize a single parameterized generic type wrapped in angle brackets, to describe the unique values stored in them, and primitive type variables are autoboxed to their object forms (char becomes Character, int become Integer, etc.), i.e.: HashSet&lt;Integer&gt; primaryKey = new HashSet&lt;&gt;();</li>
	</ul>
<li>Stacks</li>
	<ul>
	We expect fellows to understand that:
		<li>a Stack is a way to store a collection of items where the last item added is the first item to be removed, like bullets in a magazine, or pancakes on a plate - while data structures like Stacks are collections of objects where items are added to the end, and the last object added is the first object removed</li>
		<li>Stacks are often referred to as Last-In-First-Out, or LIFO systems</li>
		<li>Stacks have methods such as peek() to check the value of the last element, pop() to remove the last element and return its value, push() to add an element to the back of the stack, search() to get the position of an element in relation to the last element in the stack, and empty() to check if there are any elements left</li>
		<li>Stacks utilize a single parameterized generic type wrapped in angle brackets, to describe the unique values stored in them, and primitive type variables are autoboxed to their object forms (char becomes Character, int become Integer, etc.), i.e.: Stack&lt;String&gt; newHireLayoffs = new Stack&lt;&gt;();</li>
	</ul>
<li>Queues</li>
	<ul>
	We expect fellows to understand that:
		<li>a Queue is a way to store a collection of items where the first item added is the first item to be removed, like a queue at a fancy delicatessen - while data structures like PriorityQueues are collections of objects where items are added to the end, and the first object added is the first object removed</li>
		<li>Queues are often referred to as First-In-First-Out, or LIFO systems</li>
		<li>Queues have methods such as peek() to check the value of the first element, poll() to remove the last element and return its value, offer() or add() to add an element to the back of the queue, and size()</li>
		<li>PriorityQueues utilize a single parameterized generic type wrapped in angle brackets, to describe the unique values stored in them, and primitive type variables are autoboxed to their object forms (char becomes Character, int become Integer, etc.), i.e.: PriorityQueue&lt;String&gt; retireeCandidates = new PriorityQueue&lt;&gt;();</li>
	</ul>
<li>"Composition over Inheritance"</li>
	<ul>
	We expect the fellows to be aware of the fact that:
		<li>Abstract Data Types like Lists, Maps, Sets, Stacks, and Queues are fundamentally concepts, with Java implementations which may or may not fit ones needs</li>
		<li>although these classes exist, it may become necessary to create classes which behave like Abstract Data types, but to not extend or implement these parent classes</li>
		<li>any of these types or data structures can be replicated using arrays, composed objects, and generics under the hood (like ArrayLists for example)</li>
	</ul>
<li>The Enhanced For Loop</li>
	<ul>
	We expect fellows to create:
		<li>Enhanced For Loops, also known as for-each loops, where data structures are iterated over by the number and type of objects present, rather than any particular index or key, i.e. for (String s in nameAgeMap.keySet()) { System.out.println(nameAgeMap.get(s)); }</li>
	</ul>
</ul>
</details>
<details>
<summary>Generics and Type Erasure</summary>
<ul>
<li>Generics as Parameterized Types</li>
	<ul>
	We expect fellows to understand that:
		<li>much like declaring a type for parameters within constructors, generics allow developers to add a "type" as a parameter as well</li>
		<li>Generics allow classes to reuse constructors/methods without overloading, since the type can be declared at instantiation by passing a type into angle brackets, rather than making a constructor for every possible parameter type in existence</li>
		<li>Generics are often seen in familiar data structures, and can be used in class composition as well</li>
	</ul>
</ul>
</details>
<details>
<summary>Try/Catch Blocks, and Exception Handling</summary>
</details>
<details>
<summary>Introduction to Version Control and Basic POSIX command line tools (Git, Grep, Bash, etc)</summary>
</details>

## Unit 2 - XML Layout Design, Activity Lifecycle, SharedPreferences, and RecyclerView Management

## Unit 3 - APIs, JSON, Retrofit, Picasso, External Libraries, and Threading (Concurrency and Parallelism)

## Unit 4 - Fragments, Services, Animation, MediaPlayer, and Notifications

## Unit 5 - SQLiteOpenHelper, Firebase, and JetPack (Architecture Components)

## Unit 6 - Practical Exams

## Unit 7 - Personal Portfolio Projects

## Unit 8 - Hackathon and Assessment Retakes (as needed)

## Unit 9 - Capstone Project and Demo Day

## Unit 10 - Job Search, Portfolio Cleanup, and Commencement
