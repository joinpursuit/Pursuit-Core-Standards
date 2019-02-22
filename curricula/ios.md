# Pursuit-Core 
## iOS Development Standards 

## Introduction 

This curriculum standard assumes no type of programming background from the individual fellow. The Pursuit iOS Development course starts out with the fundamentals of the Swift langauge in Unit 1. At the end of the program into commencement the fellow would have built group iOS projects along with a capstone and portfolio projects in iOS. In tandem with the iOS development course, fellows will have adequate data structures and algorithms to be prepared for the whiteboarding interviews into landing their first iOS job.  

## Unit 1  - Swift Language Fundamentals

<details>
<summary>Short history on iOS</summary>
<p>In this course we will be building iOS apps using the Swift programming language. Prior to Swift being introduced by Apple in 2014, Objective-C was the primary language for writing macOS and iOS apps.</p>
<p>We expect fellows to know and be able to discuss:</p>
<ul>
<li>Brief history about Apple</li>
<li>Brief history about Next</li>
<li>History of the iPhone and the iOS SDK</li> 
<li>Objective-C to Swift evolution</li>
</details>

<details>
<summary>Setting up your development environment</summary>
<p>We expect fellows to know how to set up and maintain the tools we use in iOS Development</p>
<ul>
<li>Setting up Xcode</li>
<li>Getting familiar with the Xcode environment </li>
<li>Exposure to some basic Terminal commands</li>
<li>Short introduciton to Github</li>
</ul>  
</details>

<details>
<summary>Types, Variables, Logic, Numbers and Operations</summary>
<p>We expect fellows to understand and differentiate among types of data, define constants and variables, print variables to the console using string interpolation, and to solve basic logic questions. 

As well as, to be able to differentiate between number types (e.g Int vs Float), solve problems using integer operations, and apply newly learned information about numbers to conditionals.

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
<p>We expect fellows to understand how properties associate values with a particular class, structure or enumeration. Create and use stored properties. Create and use computed properties. Know the following: </p>
<ul>
<li>Stored Properties</li> 
<li>Lazy Stored Property</li> 
<li>Computed Properties: setter and getter</li>
<li>Read-Only Computed Properties</li>
<li>Property Observers: willSet, didSet</li>
<li>Type Properties</li>
</details>

<details>
<summary>Control Flow</summary>
<p>We expect fellows to understand and determine types of loops and how to use them.</p>
<ul>
<li>for-in</li>
<li>while</li>
<li>repeat-while</li>
<li>if-else</li>
<li>switch</li>
</details>

<details>
<summary>Strings</summary>
<p>We expect fellows to be able to use the fundamental data type String, by performing operations like concatenation & character printing, and to be able to understand what Unicode is and how to print and manipulate Unicode Characters.

Be able to perform the following operations: 
</p>
<ul> 
<li>Working with Characters</li>
<li>Accessing String elements</li>
<li>Concatenating Strings and Characters</li>
<li>String Interpolation</li>
<li>Comparing Strings</li>
<li>Creating a String from a File or URL</li>
<li>Writing to a File or URL</li>
</ul>
</details>

<details>
<summary>Arrays</summary>
<p>We expect fellows to understand the Array data structure. Know that Arrays stores values of the same type in an ordered list. Understand the following:</p>
<ul>
<li>access and modify arrays</li>
<li>iterate through arrays</li>
<li>use common array methods, append(), remove()</li>
</ul>
</details>

<details>
<summary>Optionals</summary>
<p>We expect fellows to understand the purpose of optionals in validating if there is a value present or not. Learn how to declare, unwrap, bind and chain optionals. To understand how optionals contribute to the writing of idiomatic Swift.</p>
<ul>
<li>nil</li>
<li>Force Unwrapping</li>
<li>Optional Binding</li>
<li>Implicitly Unwrapped Optionals</li>
</ul>
</details>

<details>
<summary>Sets</summary>
<p>We expect fellows to understand the difference between and Array and Set. Sets stores distinct values of the same type in a collection with no defined ordering. A Set also ensures that an item is unique in the Set.</p>
</details>

<details>
<summary>Dictionaries</summary>
<p>We expect fellows to be able to declare and use Dictionaries. Understand common uses of Dictionaries. Contrast and compare Dictionaries with Arrays. Understand that a dictionary stores assoications between keys of the same type and values of the same type in a collections with no defining ordering.</p>
</details>

<details>
<summary>Functions</summary>
<p>We expect fellows to understand how functions enable us to call a block of reusable code. Define and call functions. Understand the components of a function signature.</p> 
</details>

<details>
<summary>Closures</summary>
<p>We expect fellows to understand the purpose of using closures. Recognize that a function is a type of closure. Understand closure syntax. Solve problems by using functions that take a closure as an argument. Understand that closures can capture and store references to any constants and variables from the context in which they are defined.</p>
</details>

<details>
<summary>Enumerations</summary>
<p>We expect fellows to understand the usefulness of using enumerations to group common types for a group of related values. Create enumerations with different types of raw and associated values.</p>
</details>

<details>
<summary>Object-Oriented Programming</summary>
<p>We expect fellows to understand the principles of Object Oriented Programming.</p>
<ul>
<li>encapsulation</li>
<li>polymorphism</li>
<li>inheritance</li>
</ul>
</details>

<details>
<summary>Structs and Classes</summary>
<p>We expect fellows to understand the difference between structs and classes. Create and initialize structs and classes. Understand when to use a struct or a class. Understand that structs are value types and classes are reference types.</p>
</details>

<details>
<summary>Initialization</summary>
<p>We expect fellows to understand the process the initialization does in preparing an instance of a class, structure or enumeration for use.</p>
<ul>
<li>Customizing Initialization</li>
<li>Default Initializers</li>
<li>Class Inheritance and Initialization</li>
<li>Required Initializers</li>
</ul>
</details>

## Unit 2 - MVC Architecture, View Life Cycle

<details>
<summary>Intro to Xcode and App Development</summary>
<p>We expect fellows to be able to navigate Xcode and know the following: </p> 
<ul>
<li>Project Navigator</li>
<li>Debug area</li>
<li>Assistant editor</li>
<li>Version editor</li>
</ul> 
</details>

<details>
<summary>App architecture - Model, View, Controller (MVC)</summary>
<p>We expect fellows to understand how to use MVC pattern to design an iOS app. Understand that MVC is a very common app architecture but there are other options used by the industry, e.g MVVM. MVC is heavily used by Apple.

Components of MVC: 
</p>

<ul>
<li>Model: the data needed by your app</li>
<li>View: visual aspects of the user interface</li>
<li>Controller: the messenger (glue) between the views and the models</li>
</ul>
</details>

<details>
<summary>UIKit Overview</summary>
<p>We expect fellows to understand that UIKit provides the graphical, event-driven user interface for iOS apps</p>
<ul>
<li>App development with UIKit</li>
<li>App Structure</li>
<li>User Interface: Views, Controls, View Controllers, View Layout, Animations, Haptics, Windows, Screens</li>
<li>User Interactions: Touches, Press, Gestures, Drag and Drop, Focus Interactions, Peek and Pop, Keyboards and Menus, Accessibility</li>
<li>Graphics, Drawing and Printing</li>
<li>Text</li>
</ul>
</details>

<details>
<summary>Git and Github</summary>
<p>We expect fellows to know the importance of using version control. Know how to create a git repository and execute basic git commands</p>
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
<summary>Protocols and Introduction to Delegation</summary>
<p>We expect fellows to have an introductory understanding of the Protocol and the Delegation pattern in iOS. Use built in iOS Controls to explore Delegation.</p>
</details>

<details>
<summary>Delegation using UITextField</summary>
<p>We expect fellows to understand how to implement conformance to a Delegate</p>
</details>

<details>
<summary>DSA LinkedLists</summary>
<p>We expect fellows to be able to explain a LinkedList data structure and its runtime. Common operations: </p>
<ul>
<li>Access an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Insert an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
<li>Search for an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Delete an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
</ul>
</details>

<details>
<summary>Big O Notation</summary>
<p>We expect fellows to understand how Big O Notation is used to measure performance of an algorithm</p>
<ul>
<li>Constant: O(1)</li>
<li>Linear time: O(n)</li>
<li>Quadratic time: O(n^2)</li>
</ul>
<p>Other time complexities</p>
<ul>
<li>Logarithmic: O(log(n))</li>
<li>Linearithmic: O(n * log(n))</li>
<li>Exponential: O(2*n)</li>
<li>Factorial: O(n!)</li>
</ul>
</details>

<details>
<summary>Autolayout</summary>
<p>We expect fellows to understand the benefits of using Autolayout to layout the app's user interface. Common time complexities: </p>
</details>

<details>
<summary>Autolayout II - developing for different size screens</summary>
<p>We expect fellows to be able to use layout views to support all iOS devices including iPad</p>
</details>

<details>
<summary>UI Testing</summary>
<p>We expect fellows to know how to test an iOS app's user interface for expected behavior</p>
<ul>
<li>UI Element Queries</li>
<li>UI Elements</li>
<li>Application lifecycle</li>
<li>Screenshots</li>
<li>Device simulation</li>
</ul>
</details>

<details>
<summary>UIKit: UITableView</summary>
<p>We expect fellows to use UITableViews to display the data for your app arranged in rows. Be able to do the following: </p>
<ul>
<li>Provide the Table View data</li>
<li>Customize the Table View behavior</li>
<li>Configure the Table View</li>
<li>Creating Table View Cells</li> 
<li>Accessing Header and Footer Views</li>
<li>Accessing Cells and Sections</li> 
<li>Modifying Rows and Sections</li>
<li>Prefetching data</li>
</ul>
</details>

<details>
<summary>DSA Arrays</summary>
<p>We expect fellows to know the fundamental use of the Array data structure and its runtime.</p>
<ul>
<li>Access an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
<li>Insert an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Search for an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Delete an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
</ul>
<p>Common Multi-Dimensional Arrays</p>
<ul>
<li>Game boards: chess, checkers, bingo, sudoku...</li>
<li>Maps eg. lat, lon</li>
<li>Images (describing the x and y position of a point in the image)</li>
<li>Spreadsheets (uses rows and columns)</li>
<li>3D Animations</li>
</ul>
</details>

<details>
<summary>UIKit: UITableView and UISearchBar</summary>
<p>We expect fellows to be able to integrate a UITableView with a UISearchBar to filter data in their app</p>
</details>

<details>
<summary>UIKit: UI Controls and UIViewController Life Cycle</summary>
<p>Know the UIViewController Life cycle: </p>
<ul>
<li>viewWillAppear</li>
<li>viewDidLoad</li>
<li>viewDidAppear</li>
<li>viewWillDisappear</li>
<li>viewDidDisappear</li>
</ul>
<p>Be familiar with the usage of the following UI Controls</p>
<ul>
<li>UIButton</li>
<li>UIDataPicker</li>
<li>UIPageControl</li>
<li>UISegmentedControl</li>
<li>UISlider</li>
<li>UIStepper</li>
<li>UISwitch</li>
</ul>
</details>

<details>
<summary>Navigation</summary>
<p>We expect fellows to be familiar with the various styles of navigation within an app.</p>
<ul>
<li>Hierarchical Navigation e.g Settings and Mail</li>
<li>Flat Navigation e.g the Music and App Store apps</li>
<li>Content-Driven or Experience-Driven Navigation e.g. games, books and other immersive apps</li>
</ul>
<p>Classes used for Navigation: </p>
<ul>
<li>UINavigationController</li>
<li>UITabBarController</li>
<li>UIPageViewController</li>
</ul>
</details>

<details>
<summary>Generics</summary>
<p>We expect fellows to know the importance of using Generics in making their objects more flexible for any type. Understand the problems Generics sort of to solve.</p>
<ul>
<li>Generic Functions</li>
<li>Generic Types</li>
<li>Extending a Generic Type</li>
<li>Associated Types</li>
</ul>
</details>

<details>
<summary>DSA Stacks</summary>
<p>We expect fellows to understand the use case and Stack data structure along with the runtime for various operations.</p>
<ul>
<li>Access an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Insert an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
<li>Search for an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Delete an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
</ul>
</details>


## Unit 3 - Networking, Concurrency, JSON, APIs

<details>
<summary>HTTP/APIs</summary>
<p>We expect fellows to be abke to start making requests to the internet and web APIs. Fellows should have a basic understanding of how the internet works. The basic understanding concepts includes: </p>
<ul>
<li>Understand how the internet works</li>
<li>Know the following HTTP verbs: POST, GET, PUT, DELETE</li>
<li>Be familiar with response status codes: 100 -> 500</li>
<li>Understand what is a RESTFul API</li>
<li>Know how to use URLSession along with URLRequest to make requests to external web APIs</li>
</details>

<details>
<summary>Memory Management / Retain Cycles</summary>
<p>We expect fellows to understand how to break strong references in your code. Understand there are cases that ARC does not handle all the memory management of your app's needs</p>
</details>

<details>
<summary>Parsing JSON</summary>
<p>JSON is the popular format in which response data is retrieved from web request. We expect fellows to perform various HTTP request to get back JSON data. </p>
<ul>
<li>Use JSONDecoder / JSONEncoder along with Codable to parse JSON data</li>
</ul>
</details>

<details>
<summary>Unit Testing</summary>
<p>We expect fellows to understand the importance of writing unit tests. Be familiar with XCTest.</p>
<ul>
<li>Test cases and Test methods</li>
<li>Test Assertions</li>
<li>Asynchronous Tests</li>
</details>

<details>
<summary>DSA Queues</summary>
<p>We expect fellows to understand the use cases and the Queue data structure.</p>
<p>Performance: </p>
<ul>
<li>Access an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Insert an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
<li>Search for an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Delete an element</li>
<ul>
<li>Runtime: O(1)</li>
</ul>
</ul>
</details>

<details>
<summary>Escaping Closures</summary>
<p>We expect fellows to know why some clousures need to be marked escaping when passed as arguments. Most used examples of escaping closures happen when doing asynchronous network calls</p>
</details>

<details>
<summary>Error handling</summary>
<p>We expect fellows to know how to process, respond and recover from error conditions in your program.</p>
<ul>
<li>Propagating errors using throwing functions</li>
<li>Handling errors using do-catch</li>
<li>converting errors to optional values</li>
</details>

<details>
<summary>DSA Hashmaps / HashTable</summary>
<p>We expect fellows to understand the use cases of a HashMap and its runtime.</p>
<p>Performance: </p>
<ul>
<li>Access an element</li>
<ul>
<li>n/a</li>
</ul>
<li>Insert an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Search for an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
<li>Delete an element</li>
<ul>
<li>Runtime: O(n)</li>
</ul>
</ul>
</details>

<details>
<summary>Concurrency</summary>
<p>We expect fellows to know how concurrency is used on iOS to deliver an optimal experience for the user. Know the following terminalogy:</p>
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
<summary>API keys, Auth, URLRequest</summary>
<p>We expect fellows to know how to manage API keys and keeping them safe. Know Oauth 2.0 specs and why it's important in the authentication process</p>
</details>

<details>
<summary>POST request</summary>
<p>We expect fellows to be able to use URLRequest and URLSession to make a POST request to a Web API</p> 
</details>


## Unit 4 - Persistence, Animations, Debugging, Delegation, Programmatic Autolayout

<details>
<summary>UserDefaults</summary>
<p>We expect fellows to understand the UserDefaults is way to save / persist simple objects and not complex data sets.</p> 
</details>

<details>
<summary>DSA Recursion</summary>
<p>We expect fellows to understand how a function can call itself and deliver powerful solutions in problem solving</p>
<p>Be familiar with the fundamentals of a recursive function: </p>
<ul>
<li>A recursive call</li>
<li>A base case</li>
</ul> 
</details>

<details>
<summary>UICollectionView</summary>
<p>We expect fellows to understand how to use and customize UICollectionView and UICollectionViewFlowLayout</p>
</details>

<details>
<summary>File Manager</summary>
<p>We expect fellows to understand how to use FileManager and its role as the gateway to accessing the contents fo the file system. Know how to perform the following tasks using the FileManager:</p>
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
<p>We expect fellows to understand how to customizing UIView to deliver unique user interfaces.</p> 
<ul>
<li>Subclass UIView</li>
<li>Create and use NIBs</li> 
<li>Override drawRect for custom drawing of Views</li> 
</ul> 
</details>

<details>
<summary>NSCache, Images</summary>
<p>We expect fellows to know how to implement NSCache to deliver your own customize caching persistence for your app's needs. Create a custom wrapper to cache images from an asynchrous network request. Know the difference betwween Dictionary and NSCache.</p>
</details>

<details>
<summary>Custom Delegation</summary>
<p>We expect fellows will be able to create their own custom delegation on the objects to trigger events. Understand the necessary steps involved in creating a custom protocol. Be able to handle memory managemnt to avoid retain cycles in custom delegates.</p>
</details>

<details>
<summary>DSA Sorting</summary>
<p>We expect fellows to know the various array sorting algorithms and their runtimes</p>
<ul> 
<li>Insertion Sort</li>
<ul>
<li>Runtime: O(n ^ 2)</li>
</ul>
<li>Bubble Sort</li>
<ul>
<li>Runtime: O(n ^ 2)</li>
</ul>
<li>Merge Sort</li>
<ul>
<li>Runtime: O(n log(n))</li>
</ul>
<li>Quicksort</li>
<ul>
<li>Runtime: O(n ^ 2)</li>
</ul>
</ul>
</details>

<details>
<summary>UIImagePickerController</summary>
<p>We expect fellows to be able to use the UIImagePickerController in order to take pictures, recording movies, and choosing items from the user's media library.</p>
</details>

<details>
<summary>Debugging</summary>
<p>We expect fellows to understand the process by which to use debugging tools like breakpoints, instruments in fixing bugs in your app. Understand the following tools and terminology:</p>
<ul>
<li>Using breakpoints</li> 
<li>Symbolicated crash reports vs Unsymbolicated crash reports</li> 
<li>Finding and using crash reports</li>
<li>Managing performance and memory</li> 
</ul>
</details>

<details>
<summary>Programmatic View Management</summary>
<p>We expect fellows to be able to create user interface's without Storyboards</p> 
<ul>
<li>Frame vs Bounds</li> 
<li>NSLayoutConstraint</li> 
<li>NSLayoutAnchor</li> 
<li>Third party libraires e.g SnapKit</li> 
</ul> 
</details>

<details>
<summary>Animations</summary>
<p>We expect fellows to be able to use animations to deliver status, feedback, direct manipulation and help users visulaize the results of their actions. Know content animations: </p> 
<ul>
<li>Property-based animations: create animations by changing the properties of a view</li>
<li>View Controller Transitions: define custom transitions from one view controller to another</li>
</ul>
</details>

<details>
<summary>DSA Trees</summary>
<p>We expect fellows to know and understand the various tree data structures and their runtimes.</p>
<p>Tress: </p>
<ul>
<li>Binary Tree</p>
<li>Full Binary Tree</p>
<li>Complete Binary Tree</p>
<li>Balanced Binary Tree</p>
<li>Degenerate Tree</li>
<li>Binary Search Tree</li>
<li>Min Heap</li>
<li>Max Heap</li>
</ul>
<p>Know the various tree traversals</p> 
<ul>
<li>Breadth First Search</li>
<li>Depth First Search</li>
</ul>
<p>Binary Search Tree runtimes: </p>
<ul>
<li>Average runtime: O(log(n))</li>
<li>Worst runtime: O(n)</li>
</ul>
</details>

## Unit 5 - Core Data, Backend as a Service Providers (e.g Realm, Firebase, AWS) 

<details>
<summary>UIScrollView</summary>
<p>We expect fellows to know how to use this superclass for several UIKit classes including UITableView, UITextView, UICollectionView. Be able to do the following: </p>
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
<p>We expect fellows to know how to enable the broadcast of information to registered observers. Be able to perform the following: </p>
<ul>
<li>Adding and removing notification observers</li>
<li>Posting Notifications</li>
<ul>
</details>

<details>
<summary>Local Notifications</summary>
<p>We expect fellows to use local notifications to get the user's attention. You can display an alert, play a sound, or badge your app's icon.</p>
</details>

<details>
<summary>Touches, Presses and Gestures</summary>
<p>We expect fellows to be able to use gesture recognizers to track touches. Be familiar with the following: </p>
<ul> 
<li>Phases of a touch: touch begin, touch moved, touch ended, touch cancelled</li>
<li>UIPress, UIPressesEvent</li>
<li>UIKit Gestures: UILongPressGestureRecognizer, UIPanGestureRecognizer, UIPinchGestureRecognizer....</li>
</ul>
</details>

<details>
<summary>DSA Graphs</summary>
<p>We expect fellows to know the various types of Graphs</p>
<ul>
<li>Directed</li>
<li>Undirected</li>
</ul>
</details>

<details>
<summary>Core Location</summary>
<p>We expect fellows to understand how to use Core Location to obtain the geographic location and orientation of a device. Services provided by Core Location: </p>
<ul>
<li>Geographic location</li> 
<li>Altitude</li>
<li>Orientation</li>
<li>Position relative to a nearby iBeacon<li>
</ul> 
</details>

<details>
<summary>MapKit</summary>
<p>We expect fellows to be able to use the MapKit UI to display call out points of interest, and determine placemark information for map coordinates. Understand how to do the following on a Map: </p>
<ul>
<li>Manipulating the visible portion of the map</li>
<li>Configuring the Map's appearance</li>
<li>Adding overlays to the Map</li>
<li>Displaying the user's location</li>
<li>Specify locations on the map using either geographic coordinates or map-specific points</li>
<li>Place custom content on the map surface using Annotations.</li>
<li>Use MKMapViewDelegate to receive map-related updates</li>
</ul>
</details>

<details>
<summary>Dependecy Managers - Cocoapods, Catharge, Swift Package Manager</summary>
<p>We expect fellows to use existing third party libraries, including porting them into apps using dependency managers such as the Cocoapods</p>
</details>

<details>
<summary>SafariServices</summary>
<p>We expect fellows to be able to use Safari Services framework to integrate Safari behaviors into your iOS app. Understand how to use the following: </p>
<ul>
<li>SFSafariViewController</li>
<li>ASWebAuthenticationSession</li>
</ul>
</details>

<details>
<summary>Core Data</summary>
<p>We expect fellows to be able to manage object graphs and object lifecycle, including persistence using the built-in Core Data stack you get when creating a new app. Be able to do and use the following: </p>
<ul>
<li>Fetch Requests using NSFetchedResultsController</li>
<li><b>Understand the Core Data Stack</b></li>
<ul>
<li>NSPersistentContainer</li>
<li>NSManagedObjectContext</li>
<li>NSPersistenntStoreCoordinator</li>
<li>NSManagedObjectModel</li>
</ul>
</ul>
</details>

<details>
<summary>Backend as a Service</summary>
<p>We expect fellows to have exposure to Backend as a Service using Firebase</p>
<ul>
<li>Be able to create and setup the backend</li>
<li>Perform CRUD funtions on the backend service and manipulate the app's user interface accordingly</li>
</ul> 
<p>Know there are other BaaS providers such as: </p>
<ul>
<li>Realm</li>
<li>AWS</li>
<li>Creating a custom API using MongoDB, Express and Node</li>
</ul>
</details>

<details>
<summary>Key-Value Observing</summary>
<p>We expect fellows to be exposed to and able to use KVO to observe for changes on specified properties of other objects. Be able to perform the following: </p>
<ul>
<li>Registering for observation</li>
<li>Notifying observers of changes</li>
<li>Change notification</li>
</ul>
</details>





