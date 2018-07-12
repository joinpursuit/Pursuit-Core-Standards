# C4Q - Access Code 
## iOS Development Standards 

## Introduction 

This curriculum standard assumes no type of programming background from the individual fellow. The Pursuit iOS Development course starts out with the fundamentals of the Swift langauge in Unit 1. At the end of the program into commencement the fellow would have built group iOS projects along with a capstone and portfolio project in iOS. In tandem with the iOS development course, fellows will have adequate data structures and algorithms to be prepared for the whiteboarding interviews into landing their first iOS job.  

## Unit 1  - Swift Language Fundamentals

<details>
  <summary>Short history on iOS</summary>
  <p>In this course we will be building iOS apps using the Swift programming language. Prior to Swift being introduced by Apple in 2014, Objective-C was the primary language for writing macOS and iOS apps.</p>
  <ul>
    <li>Brief history about Apple</li>
    <li>Brief history about Next</li>
    <li>History of the iPhone and the iOS SDK</li> 
    <li>Objective-C to Swift evolution</li>
</details>

<details>
<summary>Setting up your development environment</summary>
  <p>Tools we use in iOS Development</p>
  <ul>
    <li>Setting up Xcode</li>
    <li>Getting familiar with the Xcode environment </li>
    <li>Exposure to some basic Terminal commands</li>
    <li>Short introduciton to Github</li>
  </ul>  
</details>

<details>
<summary>Types, Variables, Logic, Numbers and Operations</summary>
  <p>To understand and differentiate among types of data, define constants and variables, print variables to the console using string interpolation, and to solve basic logic questions. 
    
   To be able to differentiate between number types (e.g Int vs Float), solve problems using integer operations, and apply newly learned information about numbers to conditionals.
   
   Swift provides its own versions of all fundamental C and Objective-C types including the following:
  </p>
 
  <ul>
    <li>Int</li>
    <li>Double and Float</li>
    <li>Bool</li>
    <li>String</li>
  </ul>
</details>

<details>
  <summary>Properties</summary>
  <p>Understand how properties associate values with a particular class, structure or enumeration. Create and use stored properties. Create and use computed properties.</p>
</details>

<details>
<summary>Control Flow</summary>
  <p>To understand and determine types of loops and how to use them.</p>
  <ul>
    <li>for-in</li>
    <li>while</li>
    <li>repeat-while</li>
    <li>if-else</li>
    <li>switch</li>
</details>

<details>
<summary>Strings</summary>
  <p>To be able to use the fundamental data type, String by performing simple operations like concatenation & character printing, and to be able to understand what Unicode is and how to print and manipulate Unicode Characters
  
Operations: 
  </p>
  <ul> 
    <li>Working with Characters</li>
    <li>Concatenating Strings and Characters</li>
    <li>String Interpolation</li>
    <li>Comparing Strings</li>
  </ul>
</details>

<details>
<summary>Arrays</summary>
  <p>To understand the Array data structure. Know that Arrays stores values of the same type in an ordered list. Understand the following:</p>
    <ul>
      <li>access and modify arrays</li>
      <li>iterate through arrays</li>
      <li>use common array methods, append(), remove()</li>
   </ul>
</details>

<details>
<summary>Optionals</summary>
  <p>To understand the purpose of optionals in validating if there is a value present or not. Learn how to declare, unwrap, bind and chain optionals. To understand how optionals contribute to the writing of idiomatic Swift.</p>
</details>

<details>
  <summary>Set</summary>
  <p>Understand the difference between and Array and Set. Sets stores distinct values of the same type in a collection with no defined ordering. A Set also ensures that an item is unique in the Set.</p>
</details>

<details>
<summary>Dictionaries</summary>
  <p>Declare and use Dictionaries. Understand common uses of Dictionaries. Contrast and compare Dictionaries with Arrays. Understand that a dictionary stores assoications between keys of the same type and values of the same type in a collections with no defining ordering.</p>
</details>

<details>
<summary>Functions</summary>
  <p>Understand how functions enable us to call a block of reusable code. Define and call functions. Understand the components of a function signature.</p> 
</details>

<details>
  <summary>Overview of Foundation</summary>
  <p>Understand the base layer of Foundation and its use in the functionality of an app. Topics overview: </p>
    <ul> 
      <li>Fundamentals - Numbers, Data, and Basic Values. Collections, Dates and Times etc.</li> 
      <li>App Support - Task Management, Resources, Notifications, Errors etc</li>
      <li>Files and Data Persistence - File Systme, Archives and Serialization, Preferences, etc </li> 
      <li>Netowrking - URL Loading System and Bonjour</li>
      <li>Low-Level Utilities - XPC, Object runtime, Processes and Threads, Streams, Sockets and Ports </li>
    </ul>
</details>

<details>
<summary>Closures</summary>
  <p>To understand the purpose of using closures. Recognize that a function is a type of closure. Understand closure syntax. Solve problems by using functions that take a closure as an argument. Understand that closures can capture and store references to any constants and variables from the context in which they are defined.</p>
</details>

<details>
<summary>Enumerations</summary>
  Understand the usefulness of using enumerations to group common types for a group of related values. Create enumerations with different types of raw and associated values.</p>
</details>

<details>
<summary>Object-Oriented Programming</summary>
  <p>Understand the principles of Object Oriented Programming.</p>
    <ul>
      <li>encapsulation</li>
      <li>polymorphism</li>
      <li>inheritance</li>
    </ul>
</details>

<details>
<summary>Structs and Classes</summary>
  <p>Understand the difference between structs and classes. Create and initialize structs and classes. Understand when to use a struct or a class. Understand that structs are value types and classes are reference types.</p>
</details>

<details>
<summary>Initialization</summary>
  <p>Understand the process the initialization does in preparing an instance of a class, structure or enumeration for use.</p>
</details>

## Unit 2 - MVC Architecture, View Life Cycle

<details>
<summary>Intro to Xcode and App Development</summary>
  <p>At the end of this lesson the fellow will be able to navigate Xcode and now the following: </p> 
  <ul>
    <li>Project Navigator</li>
    <li>Debug area</li>
    <li>Assistant editor</li>
    <li>Version editor</li>
  </ul> 
</details>

<details>
<summary>App architecture - Model, View, Controller (MVC)</summary>
  <p>Understand how to use MVC pattern to design an iOS app. Understand that MVC is a very common app architecture but there are other options used by the industry, e.g MVVM. MVC is used by Apple.
  
Components of MVC: 
</p>

<ul>
  <li>Model: the data needed by your app</li>
  <li>View: visual aspects of the user interface</li>
  <li>Controller: the messenger (glue) between the views and the models</li>
</ul>
</details>

<details>
<summary>Git and Github</summary>
  <p>Know the importance of using version control. Know how to create a git repository and execute basic git commands</p>
  <ul>
    <li>git init</li>
    <li>git add <filename></li>
    <li>git status</li>
    <li>git push</li>
    <li>git pull</li>
    <li>git branch -a</li>
    <li>git branch checkout <new-branch-name></li>
  </ul> 
</details>

<details>
<summary>Unit Testing</summary>
  <p>Understand the importance of writing unit tests</p>
</details>

<details>
<summary>Protocols and Introduction to Delegation</summary>
  <p>Introduction to the Protocol and the Delegation pattern in iOS. Use built in iOS Controls to explore Delegation.</p>
</details>

<details>
<summary>Delegation using UITextField</summary>
  <p>Understand how to implement conformance to a Delegate</p>
</details>

<details>
<summary>Protocol Oriented Programming</summary>
  <p>Understand the difference between Object-Oriented Programming and Protocol Oriented Programming</p>
</details>

<details>
<summary>DSA LinkedLists</summary>
</details>

<details>
<summary>Autolayout</summary>
  <p>Understand the benefits of using Autolayout to layout the app's user interface.</p>
</details>

<details>
<summary>Autolayout II - developing for different size screens</summary>
  <p>Layout views to support all iOS devices including iPad</p>
</details>

<details>
  <summary>UI Testing</summary>
  <p>To know how to test an iOS app's user interface for expected behavior</p>
</details>
 
<details>
<summary>UITableView</summary>
  <p>Use UITableViews to display the data for your app in a list</p>
</details>

<details>
<summary>DSA Arrays</summary>
</details>

<details>
<summary>Using UITableView and UISearchBar</summary>
</details>

<details>
<summary>A look at some UI Controls and View Controller Life Cycle</summary>
</details>

<details>
  <summary>Navigation</summary>
  <p>Be familiar with the various ways to navigate within an app.</p>
</details>

<details>
<summary>Generics</summary>
  <p>The importance of using Generics in making your objects more flexible for any data type</p>
</details>

<details>
<summary>DSA Stacks</summary>
</details>


## Unit 3 - Networking, Concurrency, JSON, APIs

<details>
<summary>HTTP/APIs</summary>
  <p>Here fellows will start making requests to the internet and web APIs. Fellows should have a basic understanding of how the internet works. The basic understanding concepts includes: </p>
  <ul>
    <li>Understand how the internet works</li>
    <li>Know the following HTTP verbs: POST, GET, PUT, DELETE</li>
    <li>Be familiar with response status codes: 100 -> 500</li>
    <li>Understand what is a RESTFul API</li>
    <li>Know how to use URLSession along with URLRequest to make requests to external web APIs</li>
</details>

<details>
<summary>Memory Management / Retain Cycles</summary>
  <p>Understand how to break strong references in your code. Understand there are cases that ARC does not handle all the memory management of your app's needs</p>
</details>

<details>
<summary>Parsing JSON</summary>
  <p>JSON is the popular format in which response data is retrieved from web request. Fellows will be exposed to the JSON format and perform various HTTP request to get back JSON data. </p>
  <ul>
    <li>Know how to use JSONSerialization to parse JSON data through type casting</li>
    <li>Use the more modern JSONDecoder / JSONEncoder along with Codable to parse JSON data</li>
  </ul>
</details>

<details>
<summary>DSA Queues</summary>
</details>

<details>
<summary>Escaping Closures</summary>
  <p>Know why some clousures need to be marked escaping when passed as arguments. Most used examples of escaping closures happen when doing asynchronous network calls</p>
</details>

<details>
<summary>Error handling</summary>
  <p>Know how to process, respond and recover from error conditions in your program.</p>
  <ul>
    <li>Propagating errors using throwing functions</li>
    <li>Handling errors using do-catch</li>
    <li>converting errors to optional values</li>
</details>

<details>
<summary>DSA Hashmaps</summary>
</details>

<details>
<summary>Concurrency</summary>
  <p>Know how concurrency is used on iOS to deliver an optimal experience for the user. Know the following terminalogy:</p>
  <ul>
    <li>Thread</li>
    <li>Concurrent Operation</li>
    <li>Task</li>
    <li>Dispatch Queue</li>
    <li>Grand Central Dispatch</li>
    <li>Main Thread</li>
    <li>Mutex</li>
    <li>Program</li>
    <li>Process</li>
    <li>Run Loop</li>
    <li>Semaphore</li>
    <li>Task</li>
</details>

<details>
<summary>NetworkHelper - (a wrapper around URLSession)</summary>
</details>

<details>
<summary>API keys, Auth, URLRequest</summary>
  <p>Know how to manage API keys and keeping them safe. Know Oauth 2.0 specs and why it's important in the authentication process</p>
</details>

<details>
<summary>POST request</summary>
  <p>Know how to package the necessary components of the POST request and handle with URLSession</p> 
</details>


## Unit 4 - Persistence, Animations, Debugging, Delegation, Programmatic Autolayout

<details>
<summary>UserDefaults</summary>
  <p>Understand the UserDefaults is way to save / persist simple objects and not complex data sets.</p> 
</details>

<details>
<summary>NSKeyedArchiver, JSONSerialization</summary>
  <p>Be able to persist data using NSKeyedArchiver and retrieve using NSKeyedUnarchiver. Parse JSON using JSONSerialization and type casting</p> 
</details>

<details>
<summary>Codable, JSONDecoder</summary>
  <p>Using Codable to parse JSON data. The fellow should be familiar with the following classes:</p>
    <ul>
      <li>Codable</li>
      <li>Encoder</li>
      <li>Decoder</li>
      <li>JSONDecoder</li>
      <li>JSONEncoder</li>
    </ul> 
</details>

<details>
<summary>DSA Recursion</summary>
  <p>Understand how a function can call itself and deliver powerful solutions in problem solving</p>
</details>

<details>
<summary>UICollectionView</summary>
  <p>Understand how to use and customize UICollectionView and UICollectionViewFlowLayout</p>
</details>

<details>
<summary>File Manager</summary>
  <p>Understand how to use FileManager and its role as the gateway to accessing the contents fo the file system. Know how to perfrom the following tasks using the FileManager:</p>
  <ul>
    <li>Accessing user directories</li>
    <li>Location system directories, e.g the documents directory to save app data</li>
    <li>Discovery directory contents</li>
    <li>Creating and deleting items</li> 
    <li>Moving and copying items</li> 
  </ul>
</details>

<details>
<summary>Subclassing UIViews and creating NIBs</summary>
  <p>Understand how to customizing UIView to deliver unique user interfaces.</p> 
  <ul>
    <li>Subclass UIView</li>
    <li>Create and use NIBs</li> 
    <li>Override drawRect for custom drawing of Views</li> 
  </ul> 
</details>

<details>
<summary>NSCache, Images</summary>
  <p>Know how to implement NSCache to deliver your own customize caching persistence for your app's needs. Create a custom wrapper to cache images from an asynchrous network request. Know the difference betwween Dictionary and NSCache.</p>
</details>

<details>
<summary>Custom Delegation</summary>
  <p>Now we have seen how iOS implements built-in delegation through UITableView, UISearchBar etc, the fellow will be able to create their own custom delegation on the objects to trigger events. Understand the necessary steps involved in creating a custom protocol. Be able to handle memory managemnt to avoid retain cycles in custom delegates.</p>
</details>

<details>
<summary>DSA Sorting</summary>
</details>

<details>
<summary>UIImagePickerController</summary>
</details>

<details>
<summary>Debugging</summary>
  <p>Understand the process by which to use debugging tools like breakpoints, instruments in fixing bugs in your app. Understand the following tools and terminology:</p>
  <ul>
    <li>Using breakpoints</li> 
    <li>Symbolicated crash reports vs Unsymbolicated crash reports</li> 
    <li>Finding and using crash reports</li>
    <li>Managing performance and memory</li> 
  </ul>
</details>

<details>
<summary>Programmatic View Management</summary>
  <p>Be able to create user interface's without Storyboards</p> 
    <ul>
      <li>Frame vs Bounds</li> 
      <li>NSLayoutConstraint</li> 
      <li>NSLayoutAnchor</li> 
      <li>Third party libraires e.g SnapKit</li> 
    </ul> 
</details>

<details>
<summary>DSA Sorting II</summary>
</details>

<details>
<summary>Programming View Management II</summary>
</details>

<details>
<summary>Persistence overview and best practices</summary>
</details>

<details>
<summary>Animations</summary>
  <p>To be able to use Core Animation and UIKit animations to deliver status, feedback, direct manipulation and help users visulaize the results of their actions. Know they types of various ways to animate using the following: </p> 
  <ul>
    <li>Core Animation</li> 
    <li>UIKit animiate(withDuration)</li>
    <li>UIKit Dynamics</li>
  </ul> 
</details>

<details>
<summary>DSA Trees</summary>
</details>

## Unit 5 - Core Data, Backend as a Service Providers (e.g Realm, Firebase, AWS) 

<details>
<summary>UIScrollView</summary>
  <p>Know how to use this superclass for several UIKit classes including UITableView, UITextView, UICollectionView. Be able to do the following: </p>
  <ul>
    <li>Managing the content size and offset</li>
    <li>Managing the content inset behavior</li> 
    <li>Managing the scroll indicator and refresh control</li>
    <li>Scrolling to a specific location</li>
    <li>Managing the keyboard</li>
    <li>Zooming and Panning</li> 
    <li>Using UIScrollViewDelegate to respond to messages from the UIScrollView class</li>
  </ul>
</details>

<details>
<summary>NSNotificationCenter</summary>
  <p>Know how to enable the broadcast of information to registered observers. Be able to perform the following: </p>
    <ul>
      <li>Adding and removing notification observers</li>
      <li>Posting Notifications</li>
    <ul>
</details>

<details>
<summary>Notifications - Local and Remote</summary>
  <p>Be able to use push notifications to the user's device from a server, or generate them locally from the app.</p>
</details>

<details>
<summary>Touches, Presses and Gestures</summary>
  <p>Be able to use gesture recognizers to track touches. Be familiar with the following: </p>
    <ul> 
      <li>Phases of a touch: touch begin, touch moved, touch ended, touch cancelled</li>
      <li>UIPress, UIPressesEvent</li>
      <li>UIKit Gestures: UILongPressGestureRecognizer, UIPanGestureRecognizer, UIPinchGestureRecognizer....</li>
    </ul>
</details>

<details>
<summary>DSA Graphs</summary>
</details>

<details>
<summary>Core Location</summary>
</details>

<details>
<summary>MapKit</summary>
</details>

<details>
<summary>Dependecy Managers - Cocoapods, Catharge, Swift Package Manager</summary>
  <p>Now that we have been doing quite a bit of development and problem solving using native iOS frameworks let's take a look at existing third party libraries. Those libraries are ported into our apps using dependency managers such as the popular Cocoapods</p>
</details>

<details>
<summary>SFSafariViewController</summary>
</details>

<details>
<summary>Backend as a Service - Firebase, Realm, AWS, Custom RESTful API using the MEN stack</summary>
</details>

<details>
<summary>Key-Value Observing / Key-Value Coding</summary>
</details>

<details>
<summary>Core Data I</summary>
  <p>Be able to manage object graphs and object lifecycle, including persistence using the Core Data stack</p>
</details>

<details>
<summary>Core Data II</summary>
  <p>Be able to build the Core Data stack from the ground up.</p>
</details>

<details>
<summary>Oauth 2.0</summary>
  <p>Use the Oauth 2.0 spec to authenticate the user through various third parties such as Spotify and Meetup</p>
</details>

## Unit 6 - Practical Exams 

## Unit 7 - Passion Portfolio Project 

## Unit 8 - Hackathon

## Unit 9 - Capstone

## Unit 10 - Job Search / Commencement


