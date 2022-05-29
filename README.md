- [Java Interview Prep](#java-interview-prep)
  - [Coding Interview Questions](#coding-interview-questions)
  - [Conceptial Questions](#conceptial-questions)
    - [1. What is Java?](#1-what-is-java)
        - [Motivation](#motivation)
        - [Answer](#answer)
    - [2. What are some freatures of Java?](#2-what-are-some-freatures-of-java)
        - [Motivation](#motivation-1)
        - [Answer](#answer-1)
    - [3. What is JVM?](#3-what-is-jvm)
        - [Motivation](#motivation-2)
        - [Answer](#answer-2)
        - [List of JVM](#list-of-jvm)
    - [4. What is JRE?](#4-what-is-jre)
        - [Motivation](#motivation-3)
        - [Answer](#answer-3)
    - [6. What is JDK?](#6-what-is-jdk)
        - [Motivation](#motivation-4)
        - [Answer](#answer-4)
    - [7. What is the difference between JVM and JRE and JDK?](#7-what-is-the-difference-between-jvm-and-jre-and-jdk)
        - [Motivation](#motivation-5)
        - [Answer](#answer-5)
    - [8. What is Java bytecode?](#8-what-is-java-bytecode)
        - [Motivation](#motivation-6)
        - [Answer](#answer-6)
    - [9. What is the difference between Path and classpath?](#9-what-is-the-difference-between-path-and-classpath)
        - [Motivation](#motivation-7)
        - [Answer](#answer-7)
    - [10. What is the difference between source path and classpath?](#10-what-is-the-difference-between-source-path-and-classpath)
        - [Motivation](#motivation-8)
        - [Answer](#answer-8)
    - [11. What are the memory areas allocated in the JVM?](#11-what-are-the-memory-areas-allocated-in-the-jvm)
        - [Motivation](#motivation-9)
        - [Answer](#answer-9)
    - [12. What is differnecce bwtween Java permgen and metaspace?](#12-what-is-differnecce-bwtween-java-permgen-and-metaspace)
        - [Motivation](#motivation-10)
        - [Answer](#answer-10)
    - [13. What is garbage collection?](#13-what-is-garbage-collection)
        - [Motivation](#motivation-11)
        - [Answer](#answer-11)
    - [14. What is JIT compiler?](#14-what-is-jit-compiler)
        - [Motivation](#motivation-12)
        - [Answer](#answer-12)
    - [15. Explain heap space configuration.](#15-explain-heap-space-configuration)
        - [Motivation](#motivation-13)
        - [Answer](#answer-13)
    - [16. Explain the stack space configuration.](#16-explain-the-stack-space-configuration)
        - [Motivation](#motivation-14)
        - [Answer](#answer-14)
    - [17. What is a classloader?](#17-what-is-a-classloader)
        - [Motivation](#motivation-15)
        - [Answer](#answer-15)
    - [18. What are the diffrent types of classloaders?](#18-what-are-the-diffrent-types-of-classloaders)
        - [Motivation](#motivation-16)
        - [Answer](#answer-16)
    - [19. What is `public static void main(String[] args)`?](#19-what-is-public-static-void-mainstring-args)
        - [Motivation](#motivation-17)
        - [Answer](#answer-17)
    - [20. What is the order of the modifiers are switched in the `public static void main`?](#20-what-is-the-order-of-the-modifiers-are-switched-in-the-public-static-void-main)
        - [answer](#answer-18)
    - [21. Can you run code before the main method starts?](#21-can-you-run-code-before-the-main-method-starts)
        - [Motivation](#motivation-18)
        - [Answer](#answer-19)
# Java Interview Prep
## Coding Interview Questions
* https://www.hackerrank.com/dashboard
* https://www.youtube.com/watch?v=h36mQC3JFMo&list=PLqq-6Pq4lTTZgXnsBNQwCWdKR6O6Cgk1Z&ab_channel=JavaBrains

## Conceptial Questions

### 1. What is Java?
##### Motivation
* Familiarity with Java
* Comparison with other languages (C, C++, C#, Python, Ruby, JavaScript, etc.)
##### Answer
* Object-oriented programming language
* Portable - write once, run anywhere
* Very popular today in server-side programming
* Created by Sun Microsystems, released in 1995, and is now widely used in enterprise applications

### 2. What are some freatures of Java?
##### Motivation
* Awareness of what the Java has to offer
* Comparison with other languages (C, C++, C#, Python, Ruby, JavaScript, etc.)
* Importance language characteristics
##### Answer
* Simple, object-oriented, and familiar syntax to c and c++ programmers
* Robust and secure(virtual machine)
* Architecture-neutral and platform-independent(write once and run anywhere, jvm - another abstraction layer)
* High-performance(JIT compiler)
* Interpreted, threaded and dynamic(compiled, bytecode is interpreted at the runtime, typing is statically checked, behavior is dynamic)

### 3. What is JVM?
##### Motivation
* Diffrence bwtween JVM and JRE
* Characteristics of JVM
* Role it plays in execution
##### Answer
* JVM - Java virtual machine
* It's the runtime environment for Java programs, a extra layer of abstraction over the hardware
* Takes the compiled bytecode and executes it
* input to the JVM is the Bycode, output is the machine code
* Has a specification that outlines how it should work
* Diffrent implementation available
* Essentialy in making Java platform agnostic(write once and run anywhere)
##### List of JVM
* Codename One – uses the open source ParparVM
* Eclipse OpenJ9 – open-source from IBM J9, for Windows, AIX, Linux (x86, Power, and Z), macOS, MVS, OS/400, Pocket PC, z/OS.
* GraalVM – is based on HotSpot/OpenJDK, it has a polyglot feature, to transparently mix and match supported languages.
* HotSpot – the open-source Java VM implementation by Oracle.
Jikes RVM (Jikes Research Virtual Machine) – research project. PPC and IA-32. Supports Apache Harmony and GNU Classpath libraries. Eclipse Public License.
* leJOS – Robotics suite, a firmware replacement for Lego Mindstorms programmable bricks, provides a Java programming environment for the Lego Mindstorms RCX and NXT robots.
* Maxine – meta-circular open source research VM from Oracle Labs and the University of Manchester.

### 4. What is JRE?
##### Motivation
* Diffrence bwtween JVM and JRE
* Characteristics of JRE
* Role it plays in execution

##### Answer
* JRE - Java run time environment
* It is a set of software elements that together provide the environment in which Java programs are executed
* Constists of
  * Class loader
  * JVM
  * Libraries and utilities
* The JRE orchestrates the activities of these software elements
* Installed on machines that run Java

### 6. What is JDK?
##### Motivation
* Diffrence bwtween JDK and JRE
* Characteristics of JDK
* Role it plays in the development time(Author time)

##### Answer
* JDK - Java development kit
* It is a set of tools to help developers write Java programs
* Comes with a JRE(becuase you need a JRE to run the JDK)
* Based off the Java language specification
* Includes
  * Java compiler
  * Class libraries
  * Utilities

### 7. What is the difference between JVM and JRE and JDK?
##### Motivation
* Characteristics of JVM and JRE and JDK
* How they work together
##### Answer
* JDK - Software used for building Java applications
* JRE - Software used for running Java applications
* JVM - abstract virtual machine that the JRE spins up to run Java applications

### 8. What is Java bytecode?
##### Motivation
* Understanding of how Java bytecode is created/the compile process
* How it suports the portability of Java
* Relation with JVM

##### Answer
* Instructions set for the JVM to execute
* Generated by the process of the compilation of a Java program
* JVM takes the bytecode and executes it
* Can not be run natively on a machine
* Bycode is consistent across machines. But JVM implementation may vary
* This enable the "Write Once, Run Anywhere" property of Java

### 9. What is the difference between Path and classpath?
##### Motivation
* Understanding system variables
* Understanding the classpath concept
* Why we need to set this variables

##### Answer
* Both are enviromenment variables
* Path is an operation system specific variable that infuluesces what binaries(executable) are available for running
* Classpath is a Java construct to indicate where all the compiled classes and jars are available. This could be multiple locations
* Path: when I type `java` in the command line, ***JRE*** will search for the `java` binary in the PATH variable
* classpath: all the directory of  packages and classes are available in the classpath, ***compilor*** will search for the class in the classpath at the time of compilation, to see if the class is available
  
### 10. What is the difference between source path and classpath?
##### Motivation
* Understanding the project structure
* Java IDE folder structure

##### Answer
* Sourcepath is where the classes reside(that you write and compile)
* `src` directory is the default sourcepath
* Classpath is where your dependencies are located - libraries, jars, etc.
* Compile loads these when required for compilation.
* Runtime can use these to load bytecode - class path scan

### 11. What are the memory areas allocated in the JVM?
##### Motivation
* Distinction between heap and stack
* Class area and native area
##### Answer
* Heap
  * Space for objects in the memory
  * "Global" - like shared space 
  * When instances of objects are created, they are allocated in the heap
  * Reference variables can point to objects base the the context
  * Largest of the memory spaces
* Stack
  * Holds thread level data
  * Local variables and object references
  * Call frames for each method execution
* Code area(meta space)
  * Holds the bytecode, JIT info
* Implementation / native area
  * Resister
  * C implementation stack
  * a lot JVM are implemented in C and C++, JVM run on C and C++.
  * The low level code to run the JVM

### 12. What is differnecce bwtween Java permgen and metaspace?
##### Motivation
* Undersanding the the changes in memory management
* Awareness of the metaspace
  
##### Answer
* Memory areas in the JVM
* Before Java 8, there was a memory area called PermGen
* Java 8 onwards, there is a new memory area called Metaspace
* PermGen is gone!
* Memory for the JVM is allocated in the Metaspace
* PermGen had a fiexed max size allocated to it(configurable)
* Metaspace grows dynamically as the program runs
* Has maxMetaSpaceSize configuration. Triggers garbage collection when the metaspace exceeds this size
* Because of class loading / unloading, the metaspace can grow and shrink, no "permanent generation" anymore
  
### 13. What is garbage collection?
##### Motivation
* Awareness of the process of garbage collection
* Some details of working
* Benefits and drawbacks
  
##### Answer
* Process of removing unused and orphaned objects from the heap
* Automatic process.Does not need programmer intervention
* Has APIs to trigger programmaticlly(not recommended)
* Generation based approach(young generation, old generation, permanent generation)
* First in first out(FIFO)
* Benefit - no manual memory management
* Drawback - performance intrustion

### 14. What is JIT compiler?
##### Motivation
* Familiarity with the how JVM works
* Bytecode vs native code

##### Answer
* JVM selecctively converts certain bytecode instructions to native code(machine code)
* Converts to the native instruction set of the CPU it is running on
* Makes a judgement call based on usage of the bytecode, and performance characteristics
* Hence "Just in time"

### 15. Explain heap space configuration.
##### Motivation
* Familiarity with the heap space
* Configration flag details
* What informs the setting values?

##### Answer
* Configuration flag: -Xms, -Xmx
* -Xms: initial memery allocation pool size(starting size of the heap)
* -Xmx: maximum memory allocation pool size(don't go beyond this)
* When max heap size is reached
  * The JVM will start to collect garbage
  * or Out of memory errors will be thrown
* You don't want space to be too small(garbage collection will keep happening)
* You don't want space to be too big(waste of memory)

### 16. Explain the stack space configuration.
##### Motivation
* Familiarity with the stack space
* Configration flag details

##### Answer
* Configuration flag: -Xss
* -Xss: initial stack size
* Stack grows dynamically as the program runs
* When all available stack space is used
  * Stack overflow exception will be thrown
* Usually not a big deal
* Stack overflow usually happens when you have a circular invocation
  
### 17. What is a classloader?
##### Motivation
* Awareness of the class loading concept
* Role of classloader

##### Answer
* Part of the JRE
* It load Java classes into the runtime
* This happens only when needed
  * JVM requests a class
  * Class loader tries to find it and loads it
  * If it can't find it, it will throw a ClassNotFoundException

### 18. What are the diffrent types of classloaders?
##### Motivation
* Awareness of the class loading concept

##### Answer
* Application / System classloader
  * Classes in the class path
* Extension classloader
  * Core Java JDK classes
* Bootstrap classloader
  * Loads the other classloaders
  * Core Java runtime classes
* Custom classloader

### 19. What is `public static void main(String[] args)`?
##### Motivation
* Familiarity with modifiers
* Understanding the application startup process

##### Answer
* `public static void` are modifiers to a method called `main`
* `public` - method is accessible outside the class
* `static` - class instance is not required to run the method
* `void` - method does not return any value
* `main` - special name convention to indicate an execution entry point
  
### 20. What is the order of the modifiers are switched in the `public static void main`?
##### answer
* order of modifiers doesn't matter
* Modifiers must be before the method

### 21. Can you run code before the main method starts?
##### Motivation
* Understanding static block
##### Answer
* Yes, you can
* This can be done by using static block
* Static block is executed when the class is loaded
* So, this runs before the main method is executed
