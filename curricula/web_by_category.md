# C4Q - Access Code
## Full Stack Web Development Standards

## Introduction

The purpose of this document is to outline, specifically, standards for the Full Stack Web Development curriculum at Pursuit. This is not meant to be a full-fledged curriculum, nor is it meant to articulate the structure, order, or content of the Full Stack Web Development program.

This outlines, specifically, the information we expect Full Stack Web graduates to know and the things we expect them to be able to do. It will be split into three separate parts:

* Foundational Programming Concepts
* Frontend Understanding
* Backend Understanding

This structure will let us specify what concepts belong where, which will give us a better overview of how to schedule/what to prioritize.

Without further ado:

## Foundational Programming Concepts

<details>
  <summary>The Command Line</summary>
  <p>We expect students to know all important terms and concepts related to the basic implementation and usage of the bash terminal, including:</p>
  <ul>
    <li>The difference between a CLI and a GUI</li>
    <li>Basic filesystem navigation and manipulation (at least: 'ls', 'cd', 'touch', 'mkdir', 'rm')</li>
    <li>System-level environment variables - what they are and how to manipulate them (more on this in the Node section)</li>
    <li>Basic bash commands (e.g. 'sudo', 'which') and shorthand (at least: '-v', '-u', '-a', '--help')</li>
  </ul>

  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Navigate to any folder/file in the terminal when asked</li>
    <li>Create a file/folder anywhere they have permission to in their filesystem</li>
    <li>Install any software with command line support and be able to utilize it with documentation</li>
    <li>Discern what software they have installed globally, what version it is, and how to update/uninstall/reinstall as necessary</li>
  </ul>
</details>

<details>
  <summary>Local Development</summary>
  <p>We expect students to know how to set up and maintain their local development environments, including:</p>
  <ul>
    <li>Installing, configuring, updating, and using text editors, including themes, fonts, and linters</li>
    <li>Installing, configuring, updating, and using technologies important to the local implementation of full-stack web apps (for example, NPM, Express, Postgres, React, Postman, testing frameworks, deployment tools, mock data generators).</li>
  </ul>

  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Independently set up and operate a development environment on a new computer</li>
    <li>Utilize tools to effectively debug/test full-stack web applications</li>
  </ul>
</details>

<details>
  <summary>Git and GitHub</summary>
  <p>We expect students to know all foundational Git commands, best practices, and terminology, including:</p>
  <ul>
    <li>Basic Git commands (at least: 'init', 'add', 'commit', 'diff', 'push', 'status', 'history', 'pull', 'log', 'branch', 'checkout', 'clone', 'remote')</li>
    <li>Basic Git/GitHub terminology and underlying concepts (at least: 'repository', 'clone', 'fork', 'branch', 'staged', 'commit', 'merge', 'merge conflict', '.git', '.gitignore', 'pull request')
    <li>Conceptual understanding of GitHub collaboration and best practices (at least: the difference between Git and GitHub, QA/feature branches versus master branch, the importance of readme files, the pull request/review/approval cycle, how to avoid merge conflicts)</li>
  </ul>

  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Create GitHub accounts and link them to their Git installations in the command line</li>
    <li>Create, clone, and remove Git repositories anywhere they have permission to on their systems</li>
    <li>Add files and commit with descriptive messages to a remote repository</li>
    <li>See changes, commits, and commit history in the command line and revert to previous commits if necessary</li>
    <li>Pull updates from a remote repository</li>
    <li>Create, update, checkout, and push branches</li>
    <li>Submit, annotate, comment on, and approve pull requests on GitHub</li>
  </ul>
</details>

<details>
  <summary>Foundational JavaScript Concepts</summary>
  <p>We expect students to know all core JavaScript/programming concepts, including:</p>
  <ul>
    <li>Data Types (at least: integers, floats, booleans, strings, arrays, objects)</li>
    <li>Core Methods and Operators (including: string methods, array methods, arithmetic operators and Math methods, object methods)</li>
    <li>Variable definition and assignment</li>
    <li>Control Flow (including: if/else logic, switch/case logic, comparison operators, truthiness and falsiness)</li>
    <li>Functions and scope (including: definition vs. invocation, terminology - e.g. 'argument', etc - function and variable scoping, helper functions and the philosophy of conciseness)</li>
    <li>Basic loops (including: for and while loops)</li>
  </ul>
  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Identify different data types accurately, as well as the truthy and falsey conditions for each data type</li>
    <li>Apply methods and other operations based on appropriate data type to produce desired outcomes</li>
    <li>Declare, utilize, and redefine variables</li>
    <li>Navigate intermediate to complex control flow structures to produce desired outcomes for particular inputs</li>
    <li>Define and utilize functions effectively to recycle functionalities across modules and keep code DRY</li>
    <li>Define and utilize variables/functions effectively within their scope</li>
    <li>Access individual elements within sets of information, either directly, by iteration, or using methods such as split and join</li>
  </ul>
</details>

<details>
  <summary>Advanced JS/ES6 Concepts</summary>
  <p>We expect students to understand all advanced JavaScript and ES6 concepts/methods, including:</p>
  <ul>
    <li>ES6 variable and function declaration</li>
    <li>Advanced array methods (at least: forEach, map, filter, reduce)</li>
    <li>Callback functions, Promises, and asynchronicity</li>
    <li>The fs module and other advanced built-in Node libraries</li>
    <li>Advanced object manipulation by way of iteration or direct access (e.g. dot notation)</li>
    <li>Date and time functionalities</li>
    <li>Basic regular expressions</li>
  </ul>
  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Declare variables using const or let as necessary</li>
    <li>Utilize advanced enumerables appropriate to the need while iterating (e.g. using filter when they want to exclude particular items from an array)</li>
    <li>Utilize Promises and callback functions to control when functions/code blocks run</li>
    <li>Read from and write to text and JSON files</li>
    <li>Manipulate and extract information from deeply nested objects</li>
    <li>Utilize date and time to ascertain the current time and compare it to other dates/times</li>
    <li>Ascertain whether specific substrings are utilized in a document via regex</li>
  </ul>
</details>

<details>
  <summary>Debugging and Effective Problem-Solving</summary>
  <p>We expect students to be able to efficiently and independently utilize their resources to resolve gaps in understanding and bugs in their code. Students should be able to:</p>
  <ul>
    <li>Utilize online resources (e.g. the curriculum, Stack Overflow, MDN, Google) to ameliorate gaps in understanding and address bugs in code</li>
    <li>Utilize developer tools (e.g. Chrome's developer tools, Postman, online code formatters) to test functionalities in full stack web projects</li>
    <li>Know when, and how, to ask for help from their peers/instructor when they've exhausted their independent resources</li>
  </ul>
</details>

<details>
  <summary>NPM and Package Management</summary>
  <p>We expect students to know how to utilize and create modules and manage module imports via NPM. Their knowledge should include:</p>
  <ul>
    <li>File structuring and organization</li>
    <li>Creating modules, exporting, importing, and utilizing them appropriately</li>
    <li>NPM and package management via a package.json file</li>
    <li>Familiarity with documentation and module usage</li>
  </ul>
  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Effectively organize, delegate, and group modules and files</li>
    <li>Utilize module.exports, export default, require, and import to make data and functions available across file structures</li>
    <li>Initialize a project with NPM, installing and saving relevant NPM modules</li>
    <li>Familiarize themselves with new NPM modules quickly using documentation and experimentation in projects</li>
  </ul>
</details>

<details>
  <summary>Unit Testing and General TDD</summary>
  <p>We expect students to understand the philosophy and practice behind testing, including:</p>
  <ul>
    <li>What Test Driven Development is and why it's important</li>
    <li>The difference between unit, integration, and end-to-end testing</li>
    <li>How to use testing frameworks to create unit tests for full-stack applications</li>
  </ul>
  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Discuss the pros and cons of TDD in an interview environment effectively</li>
    <li>Utilize Jest to design and implement unit tests for projects, keeping in mind common inputs and edge cases</li>
  </ul>
</details>

## Frontend Understanding

<details>
  <summary>CSS and HTML</summary>
  <p>We expect students to master CSS and HTML, including:</p>
  <ul>
    <li>All common HTML element types</li>
    <li>HTML tagging, including CSS selectors</li>
    <li>HTML inputs, forms, and form behavior</li>
    <li>The CSS box model</li>
    <li>CSS styling and positioning, with a strong emphasis on Flexbox and Grids</li>
    <li>Relative widths, media queries, and responsive web design</li>
    <li>Semantic HTML and frontend accessibility</li>
  </ul>
  <p>Accordingly, we expect students to be able to:</p>
  <ul>
    <li>Precisely clone an existing website (e.g. nytimes.com)</li>
    <li>Implement a design based on mockups/specifications</li>
    <li>Create their own wireframes and implement a design in-browser</li>
    <li>Design and implement responsive sites utilizing relative widths, media queries, and other responsive web design techniques</li>
  </ul>
</details>

<details>
  <summary>The DOM and Static Sites with JavaScript</summary>
  <p>We expect students to know how to combine "vanilla" JavaScript with HTML/CSS via the use of the Document Object Model. Students should know about:</p>
  <ul>
    <li>The conceptual underpinnings of the DOM, including the notion of a tree with nodes and what that represents</li>
    <li>Methods to access and manipulate DOM nodes and their corresponding HTML elements</li>
    <li>The HTML script tag, synchronicity, and the usage of JavaScript on static HTML pages</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Create static sites combining HTML, CSS, and JavaScript</li>
    <li>Manipulate content and styling on the page by utilizing DOM Events and Event Listeners</li>
  </ul>
</details>

<details>
  <summary>REST-ful APIs, JSON, and AJAX</summary>
  <p>Students should have deep knowledge of and familiarity with REST-ful APIs, including:</p>
  <ul>
    <li>HTTP and the request-response cycle</li>
    <li>GET, POST, PATCH, and DELETE requests and the difference between them</li>
    <li>Utilizing various libraries/services to make AJAX requests to APIs (including fetch, axios, XMLHttpRequest)</li>
    <li>API routing, wildcards, and formatting appropriate requests</li>
    <li>Navigating new API documentation to discern how an API might be useful in a project</li>
    <li>Handling, parsing, and representing data received in JSON format</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Query an API in Postman or the browser to get a desired response</li>
    <li>Build a frontend application that queries remote APIs to render information to the user</li>
    <li>Utilize CRUD requests to create, update, or delete information from an API, if possible/desirable</li>
  </ul>
</details>

<details>
  <summary>React Basics</summary>
  <p>Students should be proficient with the basics of React, including:</p>
  <ul>
    <li>The concept of a 'single-page application', how React interacts with the DOM, and what's done behind the scenes to render React components in HTML/CSS</li>
    <li>JSX and component syntax</li>
    <li>Lifecycle methods (including componentDidMount, componentWillMount, componentWillReceiveProps) and the component lifecycle more generally (what runs when)</li>
    <li>State, updating state via setState, and passing state via props to child components</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Set up React applications, from scratch and utilizing build tools like create-react-app</li>
    <li>Render visible HTML inside a react-dom connected element</li>
    <li>Change/update rendered content based on user input, successful AJAX requests, or other triggers</li>
    <li>Set an initial state and update it based on information received from the user or other third-party sources</li>
    <li>Utilize information in state to accomplish tasks for the user, such as fetching from an API or processing and rendering state data in useful ways</li>
    <li>Store a single state and corresponding methods in a parent component and pass down content via props</li>
  </ul>
</details>

<details>
  <summary>React Routing and Architecture</summary>
  <p>Students are expected to be proficient in advanced React routing, including:</p>
  <ul>
    <li>React-router setup in a React project</li>
    <li>The usage of path versus exact path</li>
    <li>Nested routing through multiple components in a React project</li>
    <li>Planning and implementing a sensible structure for a frontend project's routing</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Describe the difference between frontend and backend routing</li>
    <li>Set up a project using react-router that compiles and renders components to users</li>
    <li>Use routing to render desired components on a page for specific URL extensions</li>
    <li>Explain the logic behind their component structure, routing and route naming, and links between routes</li>
  </ul>
</details>

<details>
  <summary>Redux, Context, and Advanced State Management</summary>
  <p>Students are expected to be capable of using Redux, Context, or other state management tools to centralize and manage their state. This includes understanding:</p>
  <ul>
    <li>The problem of 'prop drilling' in a stateful vanilla React application</li>
    <li>The concept and appeal of a 'single source of truth'</li>
    <li>The concept of a centralized, immutable state, updated only via actions</li>
    <li>How to utilize, separate, and recombine reducers to centralize actions and parts of state</li>
    <li>How to discern, based on the scope of a project, whether Redux, Context, or vanilla React is most appropriate</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Describe and utilize Redux, including action creators, reducers, containers, and stores</li>
    <li>Describe the appeal of Context and utilize it to create centralized state on small to medium-sized projects</li>
    <li>Create React apps using routing, centralized state management, and responsive design to seamlessly integrate and standardize the frontend experience</li>
  </ul>
</details>

<details>
  <summary>Build Tools and Connecting React Applications to Backend Servers</summary>
  <p>We expect students to know the fundamentals of transpiling and bundling React applications, including:</p>
  <ul>
    <li>What bundling tools like Webpack do and why they are important</li>
    <li>What Babel does and how to configure it for a production application</li>
    <li>When to use automated build tools, such as create-react-app, and what their purpose is</li>
    <li>How to utilize build tools while deploying a frontend application</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Create and configure a React project, either from scratch or via the usage of create-react-app</li>
    <li>Deploy a React project utilizing platforms like Netlify and Heroku</li>
  </ul>
</details>

## Backend Understanding

<details>
  <summary>How the Internet Works</summary>
  <p>We expect students to have a fulsome understanding of the physical and conceptual structure of the Internet, including:</p>
  <ul>
    <li>An awareness of physical infrastructure, including servers and cables</li>
    <li>DNS routing</li>
    <li>Servers, HTTP, and the request-response cycle</li>
    <li>HTTP error codes</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Explain, in detail, what happens when you type 'www.google.com' into a browser and press enter</li>
    <li>Understand and handle various errors based on specific HTTP error codes</li>
  </ul>
</details>

<details>
  <summary>Full Stack Application Architecture</summary>
  <p>We expect students to understand how to set up and structure a full-stack application. This includes an understanding of:</p>
  <ul>
    <li>The difference between frontend and backend applications</li>
    <li>Servers, ports, and port management</li>
    <li>Connecting and syncing frontend and backend applications and their corresponding states</li>
    <li>NPM and module management across multiple NPM based applications</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Plan and execute a full-stack application skeleton with a structure based on specific needs/design principles</li>
  </ul>
</details>

<details>
  <summary>Node's HTTP module</summary>
  <p>Students are expected to know about and be able to utilize Node's built-in HTTP module. Students should be able to:</p>
  <ul>
    <li>Create an HTTP server on a particular port</li>
    <li>Process requests via URL parameters, returning responses based on the param</li>
    <li>Send text, HTML, images, and other file types</li>
  </ul>
</details>

<details>
  <summary>Express Syntax</summary>
  <p>Students are expected to understand the fundamentals of the Express web framework, including:</p>
  <ul>
    <li>How to set up an Express application manually and using the express-generator tool</li>
    <li>How requests are routed through an Express app, and how to send particular response codes and response types</li>
    <li>The basics of how to set up Express views using a templating language</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Create an Express application that starts via npm start on any port</li>
    <li>Send responses and handle errors through the HTTP request-response cycle</li>
  </ul>
</details>

<details>
  <summary>Routing, Middleware, and Error Handling</summary>
  <p>Students are expected to understand how requests are routed in Express, including:</p>
  <ul>
    <li>Express routing and callback functions connected to routes to send specific responses</li>
    <li>File structuring, nested routing, and the usage of the 'next' keyword to escape undesirable responses</li>
    <li>The purpose and application of Express middleware, including parsers, sockets/streams, and user authenticators</li>
    <li>Error handling in Express, both the philosophy of descriptive HTTP errors and their application</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Set up middleware in an Express application to produce desired outcomes for particular requests from the frontend</li>
    <li>Route specific requests from the frontend to functions that produce intended responses as required by an app's needs</li>
    <li>Throw descriptive errors and utilize the 'next' keyword to route them efficiently to particular responses</li>
  </ul>
</details>

<details>
  <summary>SQL Syntax</summary>
  <p>Students are expected to have an advanced understanding of SQL syntax, including:</p>
  <ul>
    <li>All basic SQL verbs, including SELECT, UPDATE, CREATE, DROP, JOIN, and INSERT</li>
    <li>The usage of WHERE clauses, as well as aggregate functions, including SUM and COUNT</li>
    <li>Data typing in SQL, including all basic types, plus NULL</li>
    <li>Advanced SQL query syntax, including the effective usage/synthesis of JOIN, SELECT within SELECT, and aggregate functions</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>SELECT any columns, from any tables, in any order from a SQL database</li>
    <li>SELECT particular rows based on a given set of conditions</li>
    <li>INSERT, UPDATE, and DROP rows from tables based on specific conditions</li>
    <li>Attain numerical information about tables using aggregate functions (e.g. not iterating)</li>
  </ul>
</details>

<details>
  <summary>SQL Database Architecture</summary>
  <p>Students are expected to understand how to structure a SQL database based on the needs of their application. This includes:</p>
  <ul>
    <li>How to create an .sql file with complete table structure, database-level validations, and seed data</li>
    <li>How to determine whether information should be a column or a separate table, based on access, convenience, and architectural best practice</li>
    <li>What a join table is and how to utilize it to create associations between many-to-many related tables</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Design, structure, and seed a database for a full-stack CRUD application</li>
    <li>Justify the structure of a database they designed to an interviewer</li>
  </ul>
</details>

<details>
  <summary>Postgres and pg-promise</summary>
  <p>Students are expected to understand Postgres and how to integrate Postgres with an Express server. This includes:</p>
  <ul>
    <li>An awareness of what Postgres is and how it's different from similar systems (e.g. MySQL)</li>
    <li>An understanding of the Node package pg-promise and how to utilize it to make SQL requests in promisified ES6 JavaScript</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Set up an Express application that utilizes Postgres and pg-promise to create/extract/update/delete information from a Postgres database, process it as an HTTP response object, and send it to the frontend</li>
  </ul>
</details>

<details>
  <summary>Backend-Frontend Integration and Deployment</summary>
  <p>Students are expected to understand how to integrate and deploy a full-stack application, including separate SQL, Express, and React elements. This includes:</p>
  <ul>
    <li>Setting up proxies for AJAX requests made from the frontend</li>
    <li>Processing requests in Express to ensure that the user consistently sees the React frontend in a production build</li>
    <li>Hosting a full-stack application on Heroku, including a Postgres database, setting up environment variables for the Heroku database URL</li>
    <li>Utilizing tools such as AWS S3 to upload/host media, such as images, audio, and video</li>
  </ul>
  <p>Accordingly, students should be able to:</p>
  <ul>
    <li>Set up, launch, and maintain a full-featured full-stack application on Heroku, utilizing auxiliary services (such as S3) when necessary</li>
  </ul>
</details>
