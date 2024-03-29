# Notebook
`Started 03-Dec-2020`

# Links
- Drapstv Python  
    https://www.youtube.com/watch?v=LRlDngwgiuw&list=PL1A2CSdiySGLPTXm0cTxlGYbReGqTcGRA&index=6  

# Questions
- what data structure will you use to store a modfiable collection?
    - https://youtu.be/pYT9F8_LFTM?list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&t=48

# Algorithms
- merge sort algorithym
- permutation algorithm
    - recursive backtrack
        https://www.geeksforgeeks.org/write-a-c-program-to-print-all-permutations-of-a-given-string/

# Theory
- <shallow/deep copy>

- <mutable/immutable>
    - degismez/degisir

- <binary expression tree>

- <memoization>
    - recursion icindeki redundancylere o1 time li ekle

- <dynamic programming>

- <quick sort>

- <trees | tries>
    - traverse: tree ustunde yurumek
    - binary tree: sol node roottan kucuk sag node roottan buyuk
    - red and black tree
    - ayrik matematik | discrete matematik
    - temsil
        - +-- 5
        -     +-- 3
        -         +-- 1
        -     +-- 7
        -         +-- 9 
        # . test cases
        # . ---------- Test case 1
        # . []
        # . ---------- test case 2
        # . +-- 3
        # . ---------- test case 3
        # . +-- 3
        # .     +-- 1
        # . ---------- test case 4
        # . +-- 3
        # .     +-- 4
        # . ---------- test case 5
        # . +-- 3
        # .     +-- 1
        # .     +-- 4
        # . ---------- test case 6
        # . +-- 3
        # .     +-- 1
        
        # .     +-- 4

- <graphs>

- <stacks | queue>

- <breadth-first search>

- <algorith analysis>
    - Time Complexity
    - Space Complexity

- <syntactic sugar>

- <binary search>

- <merge sort>

- <Recursion>
    - functions calling themselves
    - base case, recursive logic, bactracking
    - palindrome, decimal to binary, binary search 

- <abstract data type>
    - dictionary, hashmap | o(1) 

- <Hashing with chaining>
    - dictionary: abstract data type(adt)
    - maintaining set of items, each with a key
    - insert, delete, search | eact search -> either you find or key error | does not exists
    - insert overwrite
    - dict.item(key,value )
    - search = contant time
    - substring stearch, doclist, database, compiler and interpereter, network router
    - file/dir synchronication | hashing 
    - simple approach
        - direct access table
        - store items in array
        - indexed by keys

- <stream>
    - stram is a sequecnce of data elements made available over time potantially unlimited data
    - twitter messages, online news, ideo streams, sensor data, market orders

- <heap>
    - priority que
    - en kucuk/en buyuk k ile ilgilendigin zaman
    - is adt | maximally efficient implementation ?
    - heap is specialized tree based data structure which is esentially an almost complete


# Notes
- fundamentals, projects, networking, interview
- [patching]

# Old
- <Beginner>
    - Variables and data structurees
        - Variable
            - integer
            - real number
            - booleann
            - strings
            - complex types
                - lists
                    - holds an array of values list = []
                - dictionaries
                    - similar to list but uses hash maps store key and value pairs
                    - ex. dict = {'test': 21, 'ssh': 35}
    - Input Output
        - input(): gets a string froom user and puts in a variabe
    - Selection
        - allows program to make choices one of three programming concepts
    - Functions
    - Iteration
    - File I/O
    - Exception handling
        - catches errors
        - avoid hard crashes
        - good for user experience
    - Modules
        - collections of codes written by other people
        - http://docs.python.org/3/library/

- <Intermediate>
    - Classes
        - data structure or type 
        - holds data behaviour called as attributes and methods
        - pattern to create object
            - object is like variable hold whole class info inside
        - Methods
            - basic method (can do almost anything)
            - special methods
                - basic(initiation, new and delete)
                - descriptors(get, set)
                - container(for emulating list like classses)
                - numeric(overriding operators of +-%)
                - all methods in python requires self param
        - Initialization
            - important feature in oop
            - allows for creation of attributes or settings of values
            - allows all obj creation to be done in one line
        - Method Objects
            - the ability to store a function in variable
                - base / super class | sub-class
        - Inheritence
            - concept of class inheriting features from another class
        - Polymorphism
            - concept of dynamic methods chosen runtime
            - subclasses must override the base class method
        - Multiple Inheritence
            - inherit from more than one base separating them with comma
    - Iterators and generators
        - iterators
            - Python uses __iter__() method to return an iterator object of the class
            - then uses __next__() method to get next item
        - generators
            - another way to create iterators
            - uses function rather than separate class
            - uses called yield which saves the state of the generator
            - allows iteration to be handled by single line exp.
    - Modulating code
        - Process of splitting up our program into multiple files
        - Allows complex packages to be made
        - Great for writing tool packs for other developers
        - Packages
            - hierarchical structure to large compilations of modules
            - ex. physic engines, networking tools, gui

- <Advanced>
    - Package Management
        - PIP is a package management system used to install and manage software packages/libraries written in Python. These files are stored in a large “on-line repository” termed as Python Package Index (PyPI).
        - Its automatically installed with python
    - Templates
        - part of string module
        - allows data to change without having to edit the app
        - can be modified with subclass
        - errors
            - key error: no key in template
            - bad placeholder: value error
        - ^ handled by safe_substitute()
        - custom delimeter could be overrided
    - Argparse
        - module allows neat familiar argument parsing for pyth programs
        - Auto formats
        - interface python system module grab args from cli
        - Arg types
            - positional arguments: required arguments
                - does not require dash[-] because its not an option
            - optional arguments: could be used or not
            - mutually exclusive arguments: select one of the discretized options
        - Regular Expression
            - or Regex is pattern matching language
            - search, find, replace, validation
            - Metacharacters > special meaning
            - Regular characters > literal meaning
        - Multithreadding
            - threads can be thought as a separate programs running along side each other
            - however they run with one process, means that they can share data among each other
            - Threads can be used for quick tasks like calculating a result from algorythm with slow process
            - Asyncronous tasks
                - some tasks can require longer time, while some require real timme
                - we can set up threads to run background write or search files while user interacting with interface
            - Locks
                - lock is block to data used by multiple thread at the same time
            - Semaphores
                - restricts access to the thread
        - Networking
            - networking is concept of two programs communicating
                - client to client
                - client to server
                - client to itself
            - client is end device interfacing with human
            - server is a device providing service for clients
            - Client server model
                - constant running
                - ex. browser - google server
            - peer to peer model
                - does not req constant running
                - ex. skype
            - Adress: ip ex. '127.0.0.1'
            - Port: 1-1024 reserved for core protocols 1024 to 65535
                - pigeon holes on network card
                - tell the incoming data what program to go 
            - Sockets: programming abstraction for connections
                - allow to communicate bidirectional
                - TCP, UDP protocols
            - TCP: Transmission control protocol
                - reliable connection based protocol
            - UDP: User datagram protocol
                - unreliable connection-less based protocol
                - low overhead
                - used for voip, online games, streaming
                - does not control the data therefore fast 