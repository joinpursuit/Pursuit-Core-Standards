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
    <li></li>
  </ul>
</details>

<details>
  <summary>REST-ful APIs, JSON, and AJAX</summary>
</details>

<details>
  <summary>React Basics</summary>
</details>

<details>
  <summary>React Routing and Architecture</summary>
</details>

<details>
  <summary>Redux, Context, and Advanced State Management</summary>
</details>

<details>
  <summary>Connecting and Deploying React Applications</summary>
</details>

## Backend Understanding

<details>
  <summary>How the Internet Works</summary>
</details>

<details>
  <summary>Full Stack Application Architecture</summary>
</details>

<details>
  <summary>Node's HTTP module</summary>
</details>

<details>
  <summary>Express Syntax</summary>
</details>

<details>
  <summary>Routing, Middleware, and Error Handling</summary>
</details>

<details>
  <summary>SQL Syntax</summary>
</details>

<details>
  <summary>SQL Database Architecture</summary>
</details>

<details>
  <summary>Postgres and pg-promise</summary>
</details>

<details>
  <summary>Backend-Frontend Integration and Deployment</summary>
</details>
