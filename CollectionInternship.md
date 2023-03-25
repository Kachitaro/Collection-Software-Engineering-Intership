---
title: Collection Software Engineering Intership
date: 2022-03-19
---

# Data structures and Algorithms

## Data structures

### Array

- **What is array?**
  => An array is a data structure that stores a collection of elements of the same data type in a contiguous block of memory. Each element in an array can be accessed using an index or a subscript that indicates its position in the array. Arrays can be one-dimensional, two-dimensional, or even multi-dimensional, depending on the number of indices needed to access each element. They can also be static or dynamic, which determines whether the size of the array is fixed at compile time or can be changed at run time.
- **Why is array used?**
  - Storing multiple values
  - Efficient data access
  - Manipulating data
  - Passing data to functions
  - Memory management
- **What are the advantage and disadvantage of an array?**
  - **Advantages of Arrays**
    1. Efficient access
    2. Easy to use
    3. Memory efficient
    4. Versatile
    5. Easy to pass to functions
  - **Disadvantages of Arrays**
    1. Fixed size
    2. Wasted memory
    3. Inefficient insertion and deletion
    4. Homogeneous
    5. Lack of flexibility

### Linked List

- **What is Linked List?**
  - A linked list is a linear data structure used in computer science to hold a set of entries. A linked list stores items in a series of nodes, each of which includes a data element and a reference (or pointer) to the following node in the sequence, as opposed to an array, which stores elements in contiguous memory regions.
  - Each node in a singly linked list contains a single reference to the node after it. Each node in a doubly linked list contains two pointers: one to the node after it in the list and one to the node before it.
  - Linked lists are frequently used in memory management methods like garbage collection as well as data structures like stacks, queues, and hash tables.
- **Why is Linked List used?**
  1. Dynamic size
  2. Efficient insertion and deletion
  3. Memory efficiency
  4. Versatility
  5. Easy to implement
     > Overall, linked lists are a powerful and versatile data structure that can be used in many different applications, from simple data storage to complex algorithms and data analysis. However, linked lists are less efficient than arrays for accessing individual elements, so they may not be suitable for all applications.
- **What are the advantage and disadvantage of Linked List?**
  - **Advantages of Linked Lists**
    - Dynamic size
    - Efficient insertion and deletion
    - Memory efficiency
    - Versatility
    - Easy to implement
  - **Disadvantages of Linked Lists** - Inefficient access - Memory overhead - No random access - Difficulty in reversing - Complexity
    > Overall, linked lists are a powerful and versatile data structure that can be used in many different applications, but they have some disadvantages as well, particularly in terms of access efficiency and memory overhead. As with any data structure, the choice of whether to use a linked list or another data structure depends on the specific requirements of the application.

### Map

- **What is Map?**
  - A map is an abstract data structure in computer science that enables the storing of a collection of key-value pairs, where each key is connected to a matching value. A map is sometimes referred to as a dictionary or associative array.
  - Each key in a map needs to be distinct, and the values can be of any data type. To seek up or obtain the related value from the map, keys are commonly employed.
  - Hash tables, binary search trees, and arrays are just a few examples of the many data structures that may be used to build maps.
  - **Maps are commonly used in programming for a wide range of applications, such as:**
    1. Data indexing and searching
    2. Counting occurrences of objects or values
    3. Mapping objects or values to other objects or values
    4. Storing configuration information or settings
    5. Caching and memoization
    6. Creating look-up tables for mathematical functions
    7. Building parsers and compilers
    8. Storing metadata for files or objects
    9. Implementing graph algorithms and data structures
- **Why is Map used?**
  - **Maps are used in programming for several reasons**
    - Efficient lookup
    - Flexibility
    - Organization
    - Data processing
    - Algorithms and data structures
    - Memory efficiency
      > Overall, maps are a versatile data structure that can be used in a wide range of applications, from simple data storage to complex algorithms and data analysis. Their efficient lookup and flexibility make them an essential tool for many programming tasks.
- **What are the advantage and disadvantage of Map?**
  - **Advantages of Maps**
    1. Efficient search and retrieval
    2. Dynamic size
    3. Organization
    4. Data processing
  - **Disadvantages of Maps** 1. Memory overhead 2. Complexity 3. Inefficient for small data sets 4. Hash collisions
    > Overall, maps are a powerful and versatile data structure that provide efficient search and retrieval of data based on a key, making them ideal for many applications. However, they have some disadvantages, particularly in terms of memory overhead and complexity, which may make them less suitable for some use cases. As with any data structure, the choice of whether to use a map or another data structure depends on the specific requirements of the application.

### Set

- **What is Set?**
  - A set is a data structure that can store unique values of the same type in a sorted order. Each value is a key, which means that we access each value using the value itself. Unlike most other collection types, rather than retrieving a specific element from a set, one typically tests a value for membership in a set. Set objects also support mathematical operations like union, intersection, difference, and symmetric difference.
- **Why is Set used?**
  - Sets are used when you want unique elements in your data structure. They can be implemented using various data structures, which provide different time and space trade-offs for various operations. Some implementations are designed to improve the efficiency of very specialized operations, such as nearest or union. If you want high-performance element lookups, you can use set’s `has()` method.
- **What are the advantage and disadvantage of Set?**
  - **Advantages**
    - Uniqueness
    - Fast search
    - Mathematical operations
    - Efficient membership testing
  - **Disadvantages**
    - Unordered
    - Limited indexing
    - Immutability
    - Overhead
- **What's the difference between `Array` and `Linked List`?**
  | Compare | Array | Linked List |
  |:------------|:-------------|:-------------|
  | Basic | Is a fixed set of elements | A large set of data arranged in some order |
  | Size | Fixed, defined at declaration | It doesn't need to be defined |
  | Sort order | Stored consecutively | Randomly stored |
  | How to access |  Direct or random |  Sequential access |
  | Insert and delete elements |  Relatively slow due to the need to shift the array | Easy, fast and convenient |
  | Search | Binary search and linear search | Easy, fast and convenient |
  | Memory | Low | Medium |
- **What's the difference between `Array` and `Map`?**
  | Array| Map |
  |:------------|:-------------|
  | Is a fixed set of elements | Is a data structure that maps a key (key) to the value of that key (called value) |
  | Fixed, defined at declaration | It doesn't need to be defined |
  | Stored consecutively | Randomly stored |
  | Direct or random | Direct access |
  | Relatively slow due to the need to shift the array | Easy, fast and convenient |
  | Binary search and linear search | Linear Search |
  | Low | High |
- **What's the difference between `Array` and `Set`?**
  | Array | Set |
  |:------------|:-------------|
  | Is a fixed set of elements | Is a type of data structure used to store elements that are not duplicated and sorted in ascending or descending order |
  | Fixed, defined at declaration | It doesn't need to be defined |
  | Can duplicate | Only one value (=== compare) |

## Algorithms
### Algorithm complexity

- **What is time complexity so important?**
  - Time complexity is defined as the amount of time taken by an algorithm to run, as a function of the length of the input. It measures the time taken to execute each statement of code in an algorithm. It is not going to examine the total execution time of an algorithm. Rather, it is going to give information about the variation (increase or decrease) in execution time when the number of operations (increase or decrease) in an algorithm.
- **What is algorithm complexity?**
  - What is algorithm complexity? Algorithm complexity is a relative quantity representing the number of operations of an algorithm compared to the size of the input (n). Ex: The average space complexity of Quick Sort is O(log n) and the worst case space complexity is O(n)

### Sort

- **Quicksort**
  - Time Complexity: Average O(n log n)
  - Worst: O(n2)
  - Data Complexity: Varies depending on implementation
  - Optimal: Occasionally
  - Choose pivot
  - first or last element
  - middle element
  - random element (not recommend)
  - median of the first, last and middle

### Search

  - **What are the advantage and disadvantage of search algorithms?** `Binary search`
  - **Advantage**
    - It is better than a linear search algorithm since its run time complexity is O(logN)
    - At each iteration, the binary search algorithm eliminates half of the list and significantly reduces the search space
    - The binary search algorithm works even when the array is rotated by some position and finds the target element
  - **Disadvantage**
    - The recursive method uses stack space
    - Binary search is error-prone
    - Caching is poor

# Programming

## Data Type

- **Primitive Type**
  - In programming, a primitive type is a data type that is not derived from any other type. Primitive types are the most basic data types available in a programming language and are usually built into the language itself.

  - The set of primitive types varies from language to language, but most languages have a similar set of primitive types, which includes:

    - Numeric types: used to represent numbers, such as integers and floating-point values
    - Boolean type: used to represent a true or false value
    - Character type: used to represent a single character, such as a letter or symbol
    - Void type: used to represent the absence of a value
- **Reference Type**
  - In programming, a reference type is a data type that stores a reference, or memory address, to another value in memory. This is in contrast to a value type, which stores the value itself.
  - In languages that support reference types, variables of reference types do not contain the value itself, but rather a reference to the memory location where the value is stored. This means that when you assign a reference type variable to another variable, both variables refer to the same value in memory. Any changes made to the value through one variable will be reflected in the other variable as well.
- **What is pointer? Why do newer programming languages omit pointers?**
  - In most programming languages, a pointer is a variable that stores the memory address of another variable. Pointers are often used to store the memory addresses of data structures in dynamic memory, and to pass large structures or arrays to functions by reference.
  - Pointers can be used to improve the efficiency of certain operations, such as dynamic memory allocation and manipulation of large data structures. However, pointers can also be difficult to use correctly and can introduce security vulnerabilities if not handled properly.
  - As a result, some newer programming languages, such as Python, Java, and C#, have omitted pointers or made them optional in order to make the language safer and easier to use. These languages often provide alternative ways to achieve the same results as pointers, such as reference variables or garbage collection. 
- **Compiler**
  - **What is compiler?**
    - A compiler is a computer program that converts source code written in a programming language into machine code or binary code that can be executed on a computer.
    - When you write a program in a programming language, you need to use a compiler to compile your source code into machine code or binary code that the computer can understand and execute.
  - **Why is compiler needed?**
    - Compilers are needed because computers only understand machine code, which is a series of low-level instructions that tell the computer what to do at a very basic level. High-level programming languages, on the other hand, are much easier for humans to read and write, because they are written in a form that is more similar to natural language.

- **What is the thread?**
  - A thread is a separate flow of execution within a program. A program can have multiple threads, and these threads can run concurrently, meaning that they can be executing simultaneously.
  - Threads are often used to perform different tasks at the same time, such as checking for input from the user, updating the user interface, and performing calculations in the background. By using threads, a program can perform multiple tasks concurrently, which can make the program more responsive and improve its performance.
  - In some programming languages, such as Java and Python, threads are implemented using a feature called "multithreading". This allows a programmer to create and manage multiple threads within a program, and to synchronize the execution of these threads to avoid race conditions and other synchronization issues.

- **What is a lock? What is deadlock?**
  - A lock is a synchronization mechanism that is used to control access to a shared resource in a multithreaded program. When a thread acquires a lock, it can access the shared resource without interference from other threads. Once the thread is finished with the resource, it releases the lock, allowing other threads to access the resource.
- **What is race condition?**
  - A race condition occurs when two or more threads try to access and modify a shared resource at the same time, and the final result depends on the timing of their execution. This can lead to unpredictable and incorrect behavior, because the value of the shared resource may be different from what was expected.

- **Languages**

  - **C/C++, Java, Javascript,...**
    - source ===> assembly code Assembling: assembly code -> object code files (Ex: 010011010101) Linker: object code files -> shared library, executable file - Advantages: - a low-level language that easily communicates with hardware - Disadvantages: - Object-orientated programming languages have several security issues which means that programs written in C++ aren't as safe as others - Cannot support built-in code threads - The pointers that are used in C++ take up a lot of memory which is not always suitable for some devices
  - **What are advantages and disadvantages of programming language?**
    - **Advantages of programming languages:**
      - They allow humans to write instructions that can be executed by a computer.
      - they provide a way to structure and organize code, making it easier to read and maintain.
      - They allow code to be reused and shared, which can save time and improve efficiency.
      - They provide various features and abstractions that can make it easier to develop complex programs.
    - **Disadvantages of programming languages:**
      - They can be difficult to learn and master, especially for people who are new to programming.
      - Different programming languages have different syntax and conventions, which can make it challenging to switch between languages.
      - Some programming languages are better suited to certain tasks than others, so a programmer may need to learn multiple languages to be able to solve a wide range of problems.
      - The performance of a program can be affected by the choice of programming language, so it is important to choose a language that is appropriate for the task at hand.
  - **Why Javascript?**
    - **There are several reasons why JavaScript has become a popular programming language:**
      1. It is a versatile language that can be used for a wide range of tasks, including web development, mobile app development, and server-side programming.
      2. It is easy to learn and use, especially for people who have some background in programming.
      3. It is supported by all modern web browsers, which makes it easy to build interactive and dynamic websites.
      4. It has a large and active community of developers, which means that there is a lot of support and resources available for learning and using the language.
      5. It has a large number of libraries and frameworks that can be used to speed up development and make it easier to build complex applications.

      >Overall, JavaScript is a powerful and popular programming language that is well-suited for a wide range of tasks and is an excellent choice for anyone who is interested in learning how to code.
- **Software design pattern**
  - **Backend**
    - **What is application programming interface (API)?**
      - The API provides the ability to provide access to a set of commonly used functions. And from there it is possible to exchange data between applications.
      - API Websocket : JSON API Rest: GET, PUT, POST, UPDATE, DELETE
    - **What are web services?**
      - Webservice là tập hợp các giao thức và tiêu chuẩn mở được sử dụng để trao đổi dữ liệu giữa các ứng dụng hoặc giữa các hệ thống.
    - **What is the difference web services and API services?**
      - The key distinction is that web services are a type of API: All web services are APIs, but not all APIs are web services. 'API' is the broader category because, by definition, it refers to any software component that acts as an intermediary between two otherwise disconnected applications.
      - Web services: two computers in a network API: two applications
    - **What is representational state transfer (REST)?**
      - Is an architectural style used in the communication between the client and the web server.
      - Use HTTP
      - **Advantages:** REST-like interactions take place on structures that are familiar to anyone who is used to using the HTTP Protocol.
      - **Disadvantages:** The limitations of HTTP also become limitations of the REST architecture. For example, HTTP does not store state information between cycles when responding to requests, and as such REST-based applications fall into stateless state and any state management tasks must be performed by the server. performed by the customer.
    - **What is Restful API? How does it work?**
      - RESTful API is a standard used in the design of APIs for web applications to manage resources. RESTful is one of the popular API design styles used today to let different applications (web, mobile...) communicate with each other.
      - GET, POST, PUT/PATCH, DELETE,...
      - **How does it work?** REST works mainly on the HTTP protocol. The above basic operations will use their own HTTP methods.
      - These methods or operations are often called CRUD corresponding to Create, Read, Update, Delete - Create, Read, Edit, Delete.
    - **What is the difference REST API and SOAP?**
        | REST API | SOAP |
        |:------------|:-------------|
        | Relies on REST (Representational State Transfer) architecture using HTTP. | Relies on SOAP (Simple Object Access Protocol) |
        | XML, JSON - Stateless | Transports data in standard XML format. |
        | GET, POST, PUT, DELETE | WSDL |
        | HTTP, HTTPS | HTTP, HTTPS, SMTP, XMAP |
        | Less structured -> less bulky data | Highly structured/typed |
    - **What is the difference REST API and GraphAPI API?**
        | REST API | GraphAPI |
        |:------------|:-------------|
        | Follows server-driven architecture | Follows client-driven architecture |
        | arranged in terms of endpoints | organized in terms of a schema |
        | The endpoint you call in REST is the identity of an object | The identity is separated from how you fetch it |
        | The shape and size of the resource are determined by the server in REST | server determines available resources |
        | hard to get consistency across all platforms | high consistency across all platforms |
        | It is difficult to get consistency across all operating systems | Provides consistent and high-quality UX across all operating systems |
        | It offers flexible public API that can easily enable new applications. | Partners of GraphQL require API customization |
    - **What is Hypertext Transfer Protocol (HTTP)?**
      - Is the set of rules for transferring files -- such as text, images, sound, video and other multimedia files -- over the web.
      - HTTP is an application protocol that runs on top of the TCP/IP suite of protocols.
    - **What is the difference HTTP and HTTPS?**
      | HTTP | HTTPS |
      |:------------|:-------------|
      | port 80 | port 443 |
      | Application Layer | Transport Layer |
      | NO Encryption | Encryption |
      | NO Certificates | SSL Certificates |
      | DON'T improve search ranking | improve search ranking |
      | faster | slower |
  - **Frontend**
    - **What is user interface (UI)?**
      - Is what we see on the screen and interact with the computer through coded commands.
      - Simpler than UI is how users see the design of the program on the desktop, laptop, handheld computer (table) or smartphone.
    - **What are UI libraries?**
      > A UI library, in the simplest terms, is a collection of materials, or components, that you can readily use or modify to meet your needs. You can think of UI components as single elements available in that library, such as buttons, input fields, or banners made out of pure HTML and CSS.
    - **What is State Management?**
      > State management refers to the management of the state of one or more user interface controls such as text fields, OK buttons, radio buttons, etc. in a graphical user interface. In this user interface programming technique, the state of one UI control depends on the state of other UI controls.
    - **Why state management required?**
      - When you have state management in place data actually flows from your app to state and vice versa. You know exactly where your data is. These state management tools also give you a point-in-time snapshot of the entire data. In that way, you know exactly where your data is and that makes your development faster.

# Database

- **What is database?**
  - A database is an organized collection of structured information or data, usually stored online in a computer system. A database is usually controlled by a database management system (DBMS). Together, data and the DBMS, and the applications associated with them, is known as a database system, often shortened to a database.
- **What is a database management system (DBMS)?**
  - DBMS is software designed to be able to define, perform operations, retrieve and manage data in a Database. DBMSs are typically capable of manipulating the data itself, data formats, field names, record structures, and file structures. It also defines rules for validating and manipulating data.
- **What is the difference between Database and DBMS?**
  - DBMS used to define, store, retrieve, and administer data of Database
- **What is relation database?**
  - Relational databases organize data in tables and relationships to reduce data redundancy while ensuring efficiency in data storage and retrieval.
  - 1 - 1 : 1 user - account 1 - m : 1 customer - many order (idCustomer - foreignKey) m - m : many writer - many book (linkingTable:(idWriter, idBook))
- **What is Structured Query Language (SQL)?**
  - This structured query language is used to retrieve data or other interface like create, delete in database, get rows and modify rows etc. with relational databases.
- **How do database resolve race conditions?**
  - A race condition is a condition of a program where its behavior depends on relative timing or interleaving of multiple threads or processes. One or more possible outcomes may be undesirable, resulting in a bug1.
  - To avoid race conditions, databases use locks to ensure that only one transaction can modify data at a time2. Locks can be implemented at different levels of granularity, such as row-level locks, page-level locks, or table-level locks2.
  - In addition to locks, databases use transactions to ensure that multiple operations are executed atomically. A transaction is a sequence of operations that are executed as a single unit of work
