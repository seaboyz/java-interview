- [Java Interview Prep](#java-interview-prep)

  - [Coding Interview Questions](#coding-interview-questions)
  - [Conceptial Questions](#conceptial-questions)
    ![Screenshot 2023-05-06 at 10 05 17 AM](https://user-images.githubusercontent.com/46071675/236632394-cae7e0c1-70a8-4c9e-98d2-5ce209d424d7.png)

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
    - https://www.youtube.com/watch?v=rPyqB1l4gko
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
    - [22. What is the difference between float and double?](#22-what-is-the-difference-between-float-and-double)
      - [Motivation](#motivation-19)
      - [Answer](#answer-20)
    - [23. Why would you need a break in a switch statement?](#23-why-would-you-need-a-break-in-a-switch-statement)
      - [Motivation](#motivation-20)
      - [Answer](#answer-21)
    - [24. What are the primitive types in java?](#24-what-are-the-primitive-types-in-java)
      - [Motivation](#motivation-21)
      - [Answer](#answer-22)
    - [25. What is default value of local variables?](#25-what-is-default-value-of-local-variables)
      - [answer](#answer-23)
    - [26. Why does complier complain about local varibles initialization?](#26-why-does-complier-complain-about-local-varibles-initialization)
      - [Answer](#answer-24)
    - [27. Can a double be cast into a byte?](#27-can-a-double-be-cast-into-a-byte)
      - [Motivation](#motivation-22)
      - [Answer](#answer-25)
    - [28. Can a byte be cast into a double?](#28-can-a-byte-be-cast-into-a-double)
      - [Motivation](#motivation-23)
      - [Answer](#answer-26)
    - [29. How do you break a nested loop?](#29-how-do-you-break-a-nested-loop)
      - [Motivation](#motivation-24)
      - [Answer](#answer-27)
    - [30. What are the diffrent access modifiers?](#30-what-are-the-diffrent-access-modifiers)
      - [Motivation](#motivation-25)
      - [Answer](#answer-28)
    - [31. Can you overload constructors? How does it work?](#31-can-you-overload-constructors-how-does-it-work)
      - [Motivation](#motivation-26)
      - [Answer](#answer-29)
    - [32. How to copy a constructor?](#32-how-to-copy-a-constructor)
      - [Motivation](#motivation-27)
      - [Answer](#answer-30)
    - [33. What is constructor chaining?](#33-what-is-constructor-chaining)
      - [Motivation](#motivation-28)
      - [Answer](#answer-31)
    - [34. What is the singleton pattern?](#34-what-is-the-singleton-pattern)
      - [Motivation](#motivation-29)
      - [Answer](#answer-32)
    - [35. What is auto-boxing and unboxing?](#35-what-is-auto-boxing-and-unboxing)
      - [Motivation](#motivation-30)
      - [Answer](#answer-33)
    - [36. What is the final keyword?](#36-what-is-the-final-keyword)
      - [Motivation](#motivation-31)
      - [Answer](#answer-34)
    - [37. What are wrapper classes?](#37-what-are-wrapper-classes)
      - [Motivation](#motivation-32)
      - [Answer](#answer-35)
    - [38. What is **_this_** keyword?](#38-what-is-this-keyword)
      - [Motivation](#motivation-33)
      - [Answer](#answer-36)
    - [39. What is abstraction?](#39-what-is-abstraction)
      - [Motivation](#motivation-34)
      - [Answer](#answer-37)
    - [40. What is encapsulation?](#40-what-is-encapsulation)
      - [Motivation](#motivation-35)
      - [Answer](#answer-38)
    - [41. How does a constructor work?](#41-how-does-a-constructor-work)
      - [Motivation](#motivation-36)
      - [Answer](#answer-39)
    - [42. What is marker interface in java?](#42-what-is-marker-interface-in-java)
      - [Motivation](#motivation-37)
      - [Answer](#answer-40)
    - [43. What is the initial value of instance variables?](#43-what-is-the-initial-value-of-instance-variables)
      - [Motivation](#motivation-38)
      - [Answer](#answer-41)
    - [44. What is method overriding?](#44-what-is-method-overriding)
      - [Motivation](#motivation-39)
      - [Answer](#answer-42)
    - [45. Is java Pass by value or pass by reference?](#45-is-java-pass-by-value-or-pass-by-reference)
      - [Motivation](#motivation-40)
      - [Answer](#answer-43)
    - [46. What is the superclass of all classes in java?](#46-what-is-the-superclass-of-all-classes-in-java)
      - [Motivation](#motivation-41)
      - [Answer](#answer-44)
    - [47. What is static modifier?](#47-what-is-static-modifier)
      - [Motivation](#motivation-42)
      - [Answer](#answer-45)
    - [48. What is the differnce between .equals() and ==?](#48-what-is-the-differnce-between-equals-and-)
      - [Motivation](#motivation-43)
      - [Answer](#answer-46)
    - [49. What are the fifferent varible scopes in java?](#49-what-are-the-fifferent-varible-scopes-in-java)
      - [Motivation](#motivation-44)
      - [Answer](#answer-47)
    - [50. `Overloading` vs `Overriding`](#50-overloading-vs-overriding)
      - [Motivation](#motivation-45)
      - [Answer](#answer-48)
    - [51. `continue` vs `break` in java](#51-continue-vs-break-in-java)
      - [Motivation](#motivation-46)
      - [Answer](#answer-49)
    - [52. Can static methods be overridden?](#52-can-static-methods-be-overridden)
      - [answer](#answer-50)
    - [Core Java and OOP(Infosys questions)](#core-java-and-oopinfosys-questions)
      - [What is DAO?](#what-is-dao)
      - [Difference between abstract classes and interfaces?](#difference-between-abstract-classes-and-interfaces)
      - [What is Encapsulation and Abstraction?](#what-is-encapsulation-and-abstraction)
      - [Analytical question: Difference between method and function..](#analytical-question-difference-between-method-and-function)
      - [How to handle class not found exception](#how-to-handle-class-not-found-exception)
      - [Describe one thin that introduced in the java 8?](#describe-one-thin-that-introduced-in-the-java-8)
      - [Tell me about functional interface?](#tell-me-about-functional-interface)
      - [Do you know Method References?](#do-you-know-method-references)
      - [Difference between lambda expression and method reference?](#difference-between-lambda-expression-and-method-reference)
      - [Tell me about Stream API?](#tell-me-about-stream-api)
      - [When is each method of software development apply?](#when-is-each-method-of-software-development-apply)
      - [What is java 8 features?](#what-is-java-8-features)
      - [Describe Abstract in OOP](#describe-abstract-in-oop)
      - [what is Java streaming?](#what-is-java-streaming)
      - [core java: polymorphism, abstract classes and interfaces(difference), AbstractionAws, aws](#core-java-polymorphism-abstract-classes-and-interfacesdifference-abstractionaws-aws)
      - [storage class](#storage-class)
      - [streams](#streams)
      - [Core java: what is JVM ?](#core-java-what-is-jvm-)
      - [What is polymorphism?](#what-is-polymorphism)
      - [Encapsulation and access modifier,the types of access modifier,Which one is more protective?](#encapsulation-and-access-modifierthe--types-of-access-modifierwhich-one-is-more-protective)
      - [How many constructors you used in java?](#how-many-constructors-you-used-in-java)
      - [Can you do static overriding?](#can-you-do-static-overriding)
      - [How you connected your db in java?](#how-you-connected-your-db-in-java)
      - [Analytical question: Difference between method and function..](#analytical-question-difference-between-method-and-function-1)
      - [How to handle class not found](#how-to-handle-class-not-found)
      - [exception](#exception)
      - [Java 8 interfaces and features](#java-8-interfaces-and-features)
      - [MapException handling](#mapexception-handling)
      - [Difference between string buffer and String Builder](#difference-between-string-buffer-and-string-builder)
      - [What is java 8 features?](#what-is-java-8-features-1)
      - [Describe Abstract in OOP](#describe-abstract-in-oop-1)
      - [what is Java streaming?](#what-is-java-streaming-1)
      - [difrenerence between Throw and Throws?](#difrenerence-between-throw-and-throws)
      - [what is pojo design pattern?](#what-is-pojo-design-pattern)

# Java Interview Prep

## Coding Interview Questions

- https://www.hackerrank.com/dashboard
- https://www.youtube.com/watch?v=h36mQC3JFMo&list=PLqq-6Pq4lTTZgXnsBNQwCWdKR6O6Cgk1Z&ab_channel=JavaBrains

## Conceptial Questions

### 1. What is Java?

##### Motivation

- Familiarity with Java
- Comparison with other languages (C, C++, C#, Python, Ruby, JavaScript, etc.)

##### Answer

- Object-oriented programming language
- Portable - write once, run anywhere
- Very popular today in server-side programming
- Created by Sun Microsystems, released in 1995, and is now widely used in enterprise applications

### 2. What are some freatures of Java?

(Why java is platform independent?)

##### Motivation

- Awareness of what the Java has to offer
- Comparison with other languages (C, C++, C#, Python, Ruby, JavaScript, etc.)
- Importance language characteristics

##### Answer

- Simple, object-oriented, and familiar syntax to c and c++ programmers
- Robust and secure(virtual machine)
- Architecture-neutral and **_platform-independent_**(write once and run anywhere, jvm - another abstraction layer)
- High-performance(JIT compiler)
- Interpreted, threaded and dynamic(compiled, bytecode is interpreted at the runtime, typing is statically checked, behavior is dynamic)

### 3. What is JVM?

##### Motivation

- Diffrence bwtween JVM and JRE
- Characteristics of JVM
- Role it plays in execution

##### Answer

- JVM - Java virtual machine
- It's the runtime environment for Java programs, a extra layer of abstraction over the hardware
- Takes the compiled bytecode and executes it
- input to the JVM is the Bycode, output is the machine code
- Has a specification that outlines how it should work
- Diffrent implementation available
- Essentialy in making Java platform agnostic(write once and run anywhere)

##### List of JVM

- Codename One – uses the open source ParparVM
- Eclipse OpenJ9 – open-source from IBM J9, for Windows, AIX, Linux (x86, Power, and Z), macOS, MVS, OS/400, Pocket PC, z/OS.
- GraalVM – is based on HotSpot/OpenJDK, it has a polyglot feature, to transparently mix and match supported languages.
- HotSpot – the open-source Java VM implementation by Oracle.
  Jikes RVM (Jikes Research Virtual Machine) – research project. PPC and IA-32. Supports Apache Harmony and GNU Classpath libraries. Eclipse Public License.
- leJOS – Robotics suite, a firmware replacement for Lego Mindstorms programmable bricks, provides a Java programming environment for the Lego Mindstorms RCX and NXT robots.
- Maxine – meta-circular open source research VM from Oracle Labs and the University of Manchester.

### 4. What is JRE?

##### Motivation

- Diffrence bwtween JVM and JRE
- Characteristics of JRE
- Role it plays in execution

##### Answer

- JRE - Java run time environment
- It is a set of software elements that together provide the environment in which Java programs are executed
- Constists of
  - Class loader
  - JVM
  - Libraries and utilities
- The JRE orchestrates the activities of these software elements
- Installed on machines that run Java

### 6. What is JDK?

##### Motivation

- Diffrence bwtween JDK and JRE
- Characteristics of JDK
- Role it plays in the development time(Author time)

##### Answer

- JDK - Java development kit
- It is a set of tools to help developers write Java programs
- Comes with a JRE(becuase you need a JRE to run the JDK)
- Based off the Java language specification
- Includes
  - Java compiler
  - Class libraries
  - Utilities

### 7. What is the difference between JVM and JRE and JDK?

##### Motivation

- Characteristics of JVM and JRE and JDK
- How they work together

##### Answer

- JDK - Software used for building Java applications
- JRE - Software used for running Java applications
- JVM - abstract virtual machine that the JRE spins up to run Java applications

### 8. What is Java bytecode?

##### Motivation

- Understanding of how Java bytecode is created/the compile process
- How it suports the portability of Java
- Relation with JVM

##### Answer

- Instructions set for the JVM to execute
- Generated by the process of the compilation of a Java program
- JVM takes the bytecode and executes it
- Can not be run natively on a machine
- Bycode is consistent across machines. But JVM implementation may vary
- This enable the "Write Once, Run Anywhere" property of Java

### 9. What is the difference between Path and classpath?

##### Motivation

- Understanding system variables
- Understanding the classpath concept
- Why we need to set this variables

##### Answer

- Both are enviromenment variables
- Path is an operation system specific variable that infuluesces what binaries(executable) are available for running
- Classpath is a Java construct to indicate where all the compiled classes and jars are available. This could be multiple locations
- Path: when I type `java` in the command line, **_JRE_** will search for the `java` binary in the PATH variable
- classpath: all the directory of packages and classes are available in the classpath, **_compilor_** will search for the class in the classpath at the time of compilation, to see if the class is available

### 10. What is the difference between source path and classpath?

##### Motivation

- Understanding the project structure
- Java IDE folder structure

##### Answer

- Sourcepath is where the classes reside(that you write and compile)
- `src` directory is the default sourcepath
- Classpath is where your dependencies are located - libraries, jars, etc.
- Compile loads these when required for compilation.
- Runtime can use these to load bytecode - class path scan

### 11. What are the memory areas allocated in the JVM?

##### Motivation

- Distinction between heap and stack
- Class area and native area

##### Answer

- Heap
  - Space for objects in the memory
  - "Global" - like shared space
  - When instances of objects are created, they are allocated in the heap
  - Reference variables can point to objects base the the context
  - Largest of the memory spaces
- Stack
  - Holds thread level data
  - Local variables and object references
  - Call frames for each method execution
- Code area(meta space)
  - Holds the bytecode, JIT info
- Implementation / native area
  - Resister
  - C implementation stack
  - a lot JVM are implemented in C and C++, JVM run on C and C++.
  - The low level code to run the JVM

### 12. What is differnecce bwtween Java permgen and metaspace?

##### Motivation

- Undersanding the the changes in memory management
- Awareness of the metaspace

##### Answer

- Memory areas in the JVM
- Before Java 8, there was a memory area called PermGen
- Java 8 onwards, there is a new memory area called Metaspace
- PermGen is gone!
- Memory for the JVM is allocated in the Metaspace
- PermGen had a fiexed max size allocated to it(configurable)
- Metaspace grows dynamically as the program runs
- Has maxMetaSpaceSize configuration. Triggers garbage collection when the metaspace exceeds this size
- Because of class loading / unloading, the metaspace can grow and shrink, no "permanent generation" anymore

### 13. What is garbage collection?

##### Motivation

- Awareness of the process of garbage collection
- Some details of working
- Benefits and drawbacks

##### Answer

- Process of removing unused and orphaned objects from the heap
- Automatic process.Does not need programmer intervention
- Has APIs to trigger programmaticlly(not recommended)
- Generation based approach(young generation, old generation, permanent generation)
- First in first out(FIFO)
- Benefit - no manual memory management
- Drawback - performance intrustion

### 14. What is JIT compiler?

##### Motivation

- Familiarity with the how JVM works
- Bytecode vs native code

##### Answer

- JVM selecctively converts certain bytecode instructions to native code(machine code)
- Converts to the native instruction set of the CPU it is running on
- Makes a judgement call based on usage of the bytecode, and performance characteristics
- Hence "Just in time"

### 15. Explain heap space configuration.

##### Motivation

- Familiarity with the heap space
- Configration flag details
- What informs the setting values?

##### Answer

- Configuration flag: -Xms, -Xmx
- -Xms: initial memery allocation pool size(starting size of the heap)
- -Xmx: maximum memory allocation pool size(don't go beyond this)
- When max heap size is reached
  - The JVM will start to collect garbage
  - or Out of memory errors will be thrown
- You don't want space to be too small(garbage collection will keep happening)
- You don't want space to be too big(waste of memory)

### 16. Explain the stack space configuration.

##### Motivation

- Familiarity with the stack space
- Configration flag details

##### Answer

- Configuration flag: -Xss
- -Xss: initial stack size
- Stack grows dynamically as the program runs
- When all available stack space is used
  - Stack overflow exception will be thrown
- Usually not a big deal
- Stack overflow usually happens when you have a circular invocation

### 17. What is a classloader?

##### Motivation

- Awareness of the class loading concept
- Role of classloader

##### Answer

- Part of the JRE
- It load Java classes into the runtime
- This happens only when needed
  - JVM requests a class
  - Class loader tries to find it and loads it
  - If it can't find it, it will throw a ClassNotFoundException

### 18. What are the diffrent types of classloaders?

##### Motivation

- Awareness of the class loading concept

##### Answer

- Application / System classloader
  - Classes in the class path
- Extension classloader
  - Core Java JDK classes
- Bootstrap classloader
  - Loads the other classloaders
  - Core Java runtime classes
- Custom classloader

### 19. What is `public static void main(String[] args)`?

##### Motivation

- Familiarity with modifiers
- Understanding the application startup process

##### Answer

- `public static void` are modifiers to a method called `main`
- `public` - method is accessible outside the class
- `static` - class instance is not required to run the method
- `void` - method does not return any value
- `main` - special name convention to indicate an execution entry point

### 20. What is the order of the modifiers are switched in the `public static void main`?

##### answer

- order of modifiers doesn't matter
- Modifiers must be before the method

### 21. Can you run code before the main method starts?

##### Motivation

- Understanding static block

##### Answer

- Yes, you can
- This can be done by using static block
- Static block is executed when the class is loaded
- So, this runs before the main method is executed

### 22. What is the difference between float and double?

##### Motivation

- Knowledge of primitive number types
- Familiarity with precision
- Knowledge of sizes allocated

##### Answer

- Both are real numbers
- Both are imprecise(need inifinite precision)
- Float takes 32 bit. Double takes 64 bit.
- Can not use equality operator to compare float and double
- Double is literally double the size of float
- Double has more precision than float
- By default, floating point numbers are double
- Use float mostly for space optimization
- A double can be cast to a float(with possible loss of precision)

### 23. Why would you need a break in a switch statement?

##### Motivation

- understanding the switch statement fall through pattern
- What happens if you don't use a break?
- Possible uses of the fall through behavior

##### Answer

- Switch case statements are't "discrete"
- If / else is discrete(ether if executes or else executes)
- There isn't a one-to-one map between the matched case the block, if there is not break, the next case will be executed
- Case match is for where the execution starts. After that, execution falls through to the next case all the way to the end of the switch.
- One way to break it is using a break statement
- Can be used without break to group serveral matching statements

### 24. What are the primitive types in java?

##### Motivation

- List of primitive types
- Nature of date
- Space consumed

##### Answer

- Primitive types are:
  - byte - 8 bit signed two's complement integer
  - short - 16 bit signed two's complement integer
  - int - 32 bit signed two's complement integer
  - long - 64 bit two's complement integer(signed / unsigned)
  - float - 32 bit floating point
  - double - 64 bit floating point
  - char - 16 bit unicode character
  - boolean - One of two values: true or false, Size unknown

### 25. What is default value of local variables?

##### answer

- The local variable do not have default value.
- They need to be initialized explicitly by the programmer
- Does bot happen automatically.

### 26. Why does complier complain about local varibles initialization?

##### Answer

- Java does not initialize local variables automatically
- If you call the local variable before it is initialized, it will throw a compiler error
- These local varibles could be primitive types or reference types
- Ebore "using" a local variable, you need to have put some value to it first.
- Can be completly uninitialized. As long as it is not used, it will not be initialized.

### 27. Can a double be cast into a byte?

##### Motivation

- Understanding the casting process
- Understanding the precision of floating point numbers

##### Answer

- Yes, you can. A higher precision floating point number can be cast to a lower precision floating point number
- This needs explicit casting

```java
byte b = (byte) d;
```

- Possible loss of data(lossy conversion)

### 28. Can a byte be cast into a double?

##### Motivation

- Understanding the precision
- Implicit casting

##### Answer

- A byte does not need to be cast to a double
- It can be automatically assigned

```java
byte b = 1;
double d = b;
System.out.println(d);
```

- This is called implicit casting
  - When the lower precision number is assigned to a higher precision number
- No possible loss of data(lossless conversion)

### 29. How do you break a nested loop?

##### Motivation

- Break statement with label
- Thoughts on best practice
  - Like a goto statement
  - should be used with caution

##### Answer

- Break statement with label

```java
outer:
for (int i = 0; i < 10; i++) {
  for (int j = 0; j < 10; j++) {
    if (i == 5) {
      break outer;
    }
  }
}
```

- Indicates the statent to break out of, not where to go to
- Not a "bad" thing to use
- Diffrent from goto statement in that you cannot alter the flow of control

### 30. What are the diffrent access modifiers?

##### Motivation

- Familiarity with modifiers
- Java access rules and diffrent types of access modifiers

##### Answer

- Private
  - Within the class only
- Pckage private(default)
  - Within the package only
- Protected
  - Within the same package and subclasses
- Public
  - Cab be accessed by all

### 31. Can you overload constructors? How does it work?

##### Motivation

- Method overloading concept
- Constructor arguments with new operator

##### Answer

- Yes, you can
- Same concept as method overloading.Diffrent is that you can use the new operator to create an object
- diffrent arguments list
- Needs arguments passed via new keyword constructor invocation

```java
class Person {
  String name;
  int age;
  Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
  Person(String name) {
    this.name = name;
  }
}
```

- Overloaded contructor "hides" default no-arg constructor. Can't construct without those args anymore.
- No-arg constructor has to be implemented by the programmer

### 32. How to copy a constructor?

##### Motivation

- Constructor arguments
- What is the pattern and when to use it

##### Answer

- Specific pattern used to create a new object as a copy of another object
- Custtrotor of a class takes as argument of the same class type
- Constructor copies memebers from that instance

```java
class Person {
  String name;
  int age;
  Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
  Person(Person p) {
    this.name = p.name;
    this.age = p.age;
  }
}
```

### 33. What is constructor chaining?

##### Motivation

- What is the pattern and when to use it
- Why do you need it

##### Answer

- Constructor chaining is a pattern that allows you to call a constructor from another constructor to delegate part of the initialization
- Usually constructor with more args delegates to constructor with less args

```java
class Person {
  String name;
  int age;
  Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
  Person(String name) {
    // this has to be the very first line in the constructor
    this(name, 0);
  }
}
```

### 34. What is the singleton pattern?

##### Motivation

- Design pattern
- How to implement it in java
- Benefits of using it

##### Answer

- Singleton pattern is a design pattern that restricts the instantiation of a class to one object.
- Java naturally allows multiple instances. The requirement is to enforce one instance.
- Done by
  - Private constructor
  - Static instance
  - Static method that returns the instance

```java
class Person {
  private static Person instance = new Person();

  private Person() {
  }

  public static Person getInstance() {
    return instance;
  }
}
```

- Benefits and uses
  - Single instance guaranteed
  - Useful for certain objects Example: DB connection
  - Controlled life cycle

### 35. What is auto-boxing and unboxing?

##### Motivation

- Knowledge of diffrent wrapper classes
- Why are they needed
- Boxing and unboxing behavior

##### Answer

- Java has an automatic mechanism for converting primitive types to their corresponding wrapper classes and vice versa.
- you don't need to call the constructor of the wrapper class for create a new object
- Assiemments work with primitive types

```java
int i = 1;
Integer i2 = 2;// equivalent to Integer i2 = new Integer(2);
```

- Method arguments and collections work

```java
List<Integer> list = new ArrayList<Integer>();
list.add(1);
list.add(2);
list.add(3);
```

### 36. What is the final keyword?

##### Motivation

- Understaning of modifiers
- Immutability concept
- Limitations with object references
- Other uses
  - final class
  - final field
  - final method
  - final variable

##### Answer

- Final keyword marks something as in its final state and not to be changed
- On a varibalbe, it means that it is immutable(At least on primitive types)

```java
final int i = 1;
```

- On object refrence, that means the freference is constant, but the object instance is not

```java
final Person p = new Person();// p can not point to another object
```

- On a method, that means the method is final and cannot be overridden in the children class

```java
final void method() {
}
```

- On a class, that means the class is final and cannot be extended in the children class

```java
final class Person {
}// Person can not be extended,can not be inherited
```

- On a field, that means the field is final and cannot be overridden in the children class

```java
final class Person {
  final int age;
}
```

### 37. What are wrapper classes?

##### Motivation

- Knowldge of diffrent wrapper classes
- Why are they are used
- Boxing and unboxing behavior

##### Answer

- Classes corresponding to primitive types - that "wrap" primitive values
- Used to with Collections -Java collections support only reference types only
- byte, short, int, long, float, double, char, boolean
- Byte, Short, Integer, Long, Float, Double, Character, Boolean

### 38. What is **_this_** keyword?

##### Motivation

- The object reference
- Why do you need it?

##### Answer

- This is a reference that points the object whose code (method) is executing.
- Used only in instance methods(Can not be used in static methods)
- Useful for accessing member variables when shadowed

```java
class Person {
  private String name;
  private int age;
  public Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
}
```

```java
class Person {
  private String name;
  private int age;
  public Person(String name){
    this.name = name;
  }
  public Person(String name, int age) {
    this(name);
    this.age = age;
  }
}
```

### 39. What is abstraction?

##### Motivation

- Concept understanding
- How it affects the class design
- Interface vs implementation

##### Answer

- Abstraction is the design principle of separating the interface from the implementation so that the consumer / client only concerned with the interface.
- Example:
  - Button on an electric / electronic device vs internal circuit board
  - Manifests in the class design using interfaces (and sometimes abstract classes)
- abstract classes vs interfaces
  - abstract classes are used for consolidating common methods and variables are exsiting in multiple classes
  - abstract classes are for author
  - interface is for consumer
- Abstraction vs encapuslation
  - Abstracton cab be enforced by encapsulation
  - encapuslation is strict abstraction and is guranteed can not be accessed
  - abstraction hides implementation details
  - encapsulation protects the implementation details from access

### 40. What is encapsulation?

##### Motivation

- Concept understanding

##### Answer

- Encapsulation is the process of restricting access to the inner implementation details of a class. It enforces abstracton concepts by not just **_hiding_** but by guaranteeing the internals are not exposed.
- it is not just the outer do not see it, the outer is imposible to see it.
- Example:

```java
class Person {
  private String name;
  private int age;
  public Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
  public String getName() {
    return name;
  }
  public int getAge() {
    return age;
  }
}
```

- Manifests in class desgin using access modifiers - like private.
- Benefits include ability to refactor/change internals without breaking others

### 41. How does a constructor work?

##### Motivation

- Object creation and memory allocation
- How constructor is called
- Diffrence from methods

##### Answer

- A method that can initialize values of an object
- The runtime creates an instance. You can work on the instance before it is ready
- for doing all the prep work for the instance
- Looks like any instance method but is not.
  - No return
  - specific naming convention
- Invoked by the new operator + object creation process

```java
class Person {
  private String name;
  private int age;
  public Person(String name, int age) {
    this.name = name;
    this.age = age;
  }
}
```

- constructor exits by default(no args constructor)
- You can implement or parameterize the constructor

### 42. What is marker interface in java?

##### Motivation

- Why are they used
- example

##### Answer

- An interface that marks or "tags" classes and their corresponding instances
- Don't have any methods of their own
- Example: Serializable, Cloneable, Comparable
- Formerly used because annotations didn't exist
- Not recommended these days

### 43. What is the initial value of instance variables?

##### Motivation

- Understading of the default values
- Constrast with local variables

##### Answer

- Instance varaibles don't need to be initialized
- Constrasts with local variables that error when used without initialization
- Primitive values take "default" values
  - `0` for numeric types
  - `\000` for char
  - `false` for boolean
  - `null` for reference types
- Recommended initialization in constructor(especially object reference)
  - if you don't initialize, it will be null
  - at the runtime, you will get `NullPointerException`

### 44. What is method overriding?

##### Motivation

- Parent class and sub class concept
- How to override a method
- What it results in (polymorphism)

##### Answer

- Overriding is when a subclass changes the behavior of an inherited method
- Done by the subcalss implementing a method with the same signature as the parent class
- Works for multiple levels too. Methods can be overridden irrespective of where it inherited from.
- It can be overridden the method inherited from the `Object` class
- Actual method gets resolved at runtime. This allows for polymorphism.(runtime polymorphism)

### 45. Is java Pass by value or pass by reference?

##### Motivation

- Familiarity with the java instance
- Understanding of the difference between primitive and reference types

##### Answer

- **_Java is pass by value_**
- for primitive types
  - the variable holds the actual value of the primitive type
  - it is passed by value
- for reference types
  - the variable holds the reference to the object allocated in the heap(never use pointer)
  - it is passed by the value of the reference

### 46. What is the superclass of all classes in java?

##### Motivation

- `Object` superclass
- What it provides

##### Answer

- `Object` is the superclass of all classes in java
- Root of the inheritance hierarchy
- `Object` class contains some handy methods like
  - `toString()`
  - `equals()`
  - `hashCode()`

### 47. What is static modifier?

##### Motivation

- familiarity with the java instance
- Instance value vs "global"

##### Answer

- (static varibles) not associated with any instance
  - When you need to store data that is relivent across instances (static variables)
  - Example:
    `Math.PI`
- static method
  - when you need to provide method before creating the instance
  - `public static main(String[] args){}`
- static block
  - when you need the code to be executed before creating the instance
  - `static { }`
  - Example:
    `static { System.out.println("Hello"); }`

### 48. What is the differnce between .equals() and ==?

##### Motivation

- Object reference comparison vs value comparison

##### Answer

- `==` is an operator that compares two values for equality
- Works with primitive type.
- Does not work with reference type
- Only compare the values of reference to the object
- Every object inherits equals method from the `Object` class
- Classes can implement their own `equals` method to check for equality

### 49. What are the fifferent varible scopes in java?

##### Motivation

- Understanding of scoping
- What forms a scope

##### Answer

- class level scope
  - member variables
- Method level scope
  - local variables
  - parameters
  - return values
- Block level scope
  - loops
  - if blocks

### 50. `Overloading` vs `Overriding`

##### Motivation

- Understanding of the concept
- How overloading works with overriding

##### Answer

- Overloading
  - Overloading is when you have multiple methods with the same name but different signatures(arguments)
  - Argumetns dicide which one to call
- Overriding
  - A child class providing implementation to change the behavior of the inherited method
  - Instance decide which one gets called
- Overriden methods can be overloaded

### 51. `continue` vs `break` in java

##### Motivation

- Understanding of loops and control flow
- When to use continue
- When to use break
- Sample situation

##### Answer

- Both are used in loops
- Break is used to end the loop immediately
- Continue is used to end the particular **_iteration_** of the loop
- Example:
- Looping an array until you find a value

```java
for(int i = 0; i < array.length; i++) {
  if(array[i] == value) {
    break;
  }
}
```

- Example:
- Processing every element, but skipping some on some condition

```java
for(int i = 0; i < array.length; i++) {
  if(array[i] == value) {
    continue;
  }
  // do something with array[i]
}
```

- `break` in `switch`
  - Example:

```java
switch(value) {
  case 1:
    System.out.println("one");
    break;
  case 2:
    System.out.println("two");
    break;
  default:
    System.out.println("other");
}
```

### 52. Can static methods be overridden?

##### answer

- static method can not be overridden in java
- Method overriding has been designed to work with polymorphism

### 53. Java Memory allocations

#### answer

- Class Memory
- Heap Memory
- Stack Memory
- Program Coutner Memory
- Native Method Stack Memory

### Core Java and OOP(Infosys questions)

#### What is DAO?

#### Difference between abstract classes and interfaces?

#### What is Encapsulation and Abstraction?

#### Analytical question: Difference between method and function..

#### How to handle class not found exception

#### Describe one thin that introduced in the java 8?

#### Tell me about functional interface?

#### Do you know Method References?

#### Difference between lambda expression and method reference?

#### Tell me about Stream API?

#### When is each method of software development apply?

#### What is java 8 features?

#### Describe Abstract in OOP

#### what is Java streaming?

#### core java: polymorphism, abstract classes and interfaces(difference), AbstractionAws, aws

#### storage class

#### streams

#### Core java: what is JVM ?

#### What is polymorphism?

#### Encapsulation and access modifier,the types of access modifier,Which one is more protective?

#### How many constructors you used in java?

#### Can you do static overriding?

#### How you connected your db in java?

#### Analytical question: Difference between method and function..

#### How to handle class not found

#### exception

#### Java 8 interfaces and features

#### MapException handling

#### Difference between string buffer and String Builder

#### What is java 8 features?

#### Describe Abstract in OOP

#### what is Java streaming?

### difrenerence between Throw and Throws?

- **throw** is used to explicitly throw an exception within a method. When you encounter an exceptional condition in your code, you can use the throw keyword followed by an instance of an exception class to indicate that an exception has occurred.

```java
throw new IllegalArgumentException("Invalid argument");
```

- **throws** is used in a method declaration to specify the exceptions that might be thrown by that method. When a method declares that it throws a particular exception, it means that the method is capable of generating that exception, but it is not responsible for handling it. The responsibility of handling the exception is delegated to the caller of the method. For example:

```java
public void readFile() throws IOException {
    // Method code that may throw an IOException
}
```

#### what is pojo design pattern?

- **_Transfer Object_** is a simple POJO class having **_getter/setter_** methods and is **_serialized_** so that it can be **_transferred over the network_**. Server Side business class normally fetches data from the database and fills the POJO and sends it to the client or passes it by value. For clients, the transfer object is read-only. The client can create its own transfer object and pass it to the server to update values in the database in one shot.

### What is java?

Java is a high-level, class-based, object-oriented, programming language that is designed to have as few implementation dependencies as possible.
high level - it is compared to low level machine language. No direct memory management, abstracted away from hardware
class based - Everything written is in the form of a class, inheritance based on class.
object oriented - Bundle data and functions into a single logical unit, the class. Use it as a blue to create an object.

### Describe the JDK, JRE, and the JVM

JDK (Java development kit) =
Development Tools(an interpreter/loader (Java), a compiler (javac), an archiver
(jar), a documentation generator (Javadoc), and other tools needed in Java
development )
JRE (to execute your java program)
JRE (Java Runtime Environment) =
Deployment technologies
User interface toolkits
Integration libraries
Java Virtual Machine (JVM)
JVM (Java Virtual Machine)
is responsible for executing the java program line by line, hence it is also known as an interpreter.The JVM reads the compiled Java bytecode and translates it to machine code to be executed on the given system.

List the Java primitive types
byte short int long
char boolean float double

Array
An array is a container object that holds a fixed number of values of a single type.
The elements are stored via index, with an array, each index is located next to one another in the physical memory of our application
Array indexes start at 0, you access specific elements in the array by these indexes
The array must be given a size when instantiated, and it CANNOT be resized
The length property gives programmes access to the size of the array
There are multiple ways to declare an array:
datatype[] arr;
datatype arr[];
There are multiple ways to instantiate an array:
datatype[] arr = new datatype[size];
datatype arr[] = {obj1, obj2, obj3};
To create multi-dimensional arrays we just add more brackets
datatype[][] arr
The first set of indexes in our multidimensional arrays are storing arrays
These are similar to rows and columns
datatype[row][col] arr;
Var Args
ar args is a notation to pass an unset amount of parameters of a single data type
Uses the ... notation
There can only be one var arg in a method, and it must be the last parameter
Var args get converted to arrays behind the scenes, so you can treat them just like arrays
What are wrapper classes?
The way to use primitive data as objects.
For example, the ArrayList can only store objects by definition, to be able to put an int into an ArrayList, we use Integer, the wrapper class converts it to an object. Then we can store it. It is all done automatically through autoboxing by the java compiler.
What is autoboxing and unboxing?
Autoboxing is the automatic conversion that the Java compiler makes between the primitive types and their corresponding object wrapper classes
We store an int into ArrayList<Integer>, we don't have to make an Integer object first then add it to the list. We can just add the primitive type int to the list, then the Java compiler automatically converts the int type into Integer type, then stores it.
Then when we take the integer type object out of the list, we don’t have to get the primitive value out of the object, we can just use it as a primitive value to do other computation.

Public > Protected > Default > Private

Public
Available anywhere

Protected
Same class / subclass / same or different package

Default
Same package same class sub class

Private
Available only within the same class
What does the "final" keyword mean?
final class means the classes can not be extended.
final variables and parameters can not be reassigned.
final method can not be overridden.
What does the "static" keyword mean?
Means the class members are living inside of the class at the run time, not the class instance.
Static fields like global variables that happened live inside the namespace of a class.
And the methods are just functions that live inside the namespace of the class.
In my opinion, static methods and fields have nothing to do with the OOP.
it's just the java way to achieve the global variables and global functions.
What are variable arguments?
Gother all arguments the caller passes into the method to an array.

What are the scopes in which a variable can exist in - in Java?
The scope is where a certain variable and method is accessible in your code.
class level scope(static)(the variable belongs to the class itself)
All instance variables are accessible to the methods in the same class.
If you change the value in one instance, it will change in all instance of that class
Method level scope
Once the method is done executing the variable no longer exists
All parameters and local variables declared inside the method are accessible only inside the method
Block level scope
For loop, while loop, try catch
Once block is stop running, variables are not available
Instance scope(belong to the object itself)
Each individual object instantiated from the class will have its own value for that variable

What is the difference between an object and a class?

Class is the definition and a template of data type, object is an instance of a class.
Is like a factory function in js. At the runtime object is the real entity a class produces.

What is the "new" keyword used for?
Let JVM allocate a space in the memory for creating an object.

What is the "super" keyword used for?
Super in java is a reference variable to refer to the immediate parent class.

What is the "this" keyword used for?
Refer to the current object or current class at the runtime.

What is a constructor?
Is a method to call upon when creating an object.

What is the difference between the == operator and .equals() method?
LHS value == RHS value
For primitive variable, == compare the the values saved in the memory
For reference variables, == compare the reference to see if they refer to the same location in the memory.(reference comparison)

.equals just invoke the .equals method on the object type class.
For different types, .equals have different implications for checking the equality.

What is the Object class's function in the Java language?
Here are some key functions of the Object class in Java:

Identity and Equality: The Object class provides methods to compare objects for equality (equals()) and determine their unique identity (hashCode() and toString()). These methods can be overridden in derived classes to define custom equality and identity behavior.
Type Information: The Object class includes methods to obtain the runtime class of an object (getClass()) and check the type compatibility (instanceof operator). These methods allow you to perform runtime type checks and introspection.
Memory Management: The Object class includes the finalize() method, which can be overridden to define custom cleanup operations when an object is no longer referenced and garbage collected.
Synchronization: The Object class provides methods for thread synchronization, such as wait(), notify(), and notifyAll(). These methods are used for inter-thread communication and coordination.
Cloning: The Object class defines the clone() method, which supports object cloning. By default, it performs a shallow copy, but it can be overridden to implement deep copy behavior.
Object Manipulation: The Object class includes methods to dynamically create instances (newInstance()) and compare objects (compareTo()). These methods enable dynamic object creation and sorting based on natural order.

What is a POJO?
Plain Old Java Object, representing state of a object. No behaviour.

What is method overloading?
Two methods with the same name but different parameter list.

What is method overriding?
Two methods with the same name, same parameter list and compatible return types.
the access modifier in the child class has to be the same or friendlier.

What is type casting?
The process converting one type to another.
For primitive types, it converts both value and types. For example casting double type 3.5 to int,
Truncate 3.5 to 3 and convert it type to int.
For reference types
, it only converts the types of variables.
From parent class to child class is down casting, it expends the properties and methods available to the object.
From child class to parent class is up casting, it narrows the properties and methods available to the object.

What are access modifiers?
Restrict the accessibility and scope of a field, method or class.

Abstract
Abstract class
Class that is partial implementation, can not be instantiated.
It has to be implemented/ extended
They can also contain variables, and constructors like a normal class
The reason we can include a constructor, is to enforce the inheriting class to set some properties of the abstract class

Abstract method
Has no body, it is not implemented
It has to be implemented in the concrete child class
abstract and final
in java, you will never see a class or method declared with both final and abstract keywords
Interfaces(for abstraction)
Classes can not have multiple inheritance, interfaces can.
Interfaces specify what a class must do and not how. It is the blueprint of the class.
The interface in Java is a mechanism to achieve abstraction.
It is used to achieve abstraction and multiple inheritance in Java. In other words, you can say that interfaces can have abstract methods and variables.
All methods are abstract, no body.
Java Interface also represents the IS-A relationship.
Every method in an interface is public and abstract
Interfaces can still have variables, but they will implicitly be public static and final
In Java 8, default methods were added, which allows programmers to add implementation to methods in an interface
You can implement as many interfaces as you wish on a single class
Interfaces extend other interfaces

Default method in Interface
Default Methods and Multiple Inheritance
In case both the implemented interfaces contain default methods with same method signature, the implementing class should explicitly specify which default method is to be used or it should override the default method
.
Transient
marks a variable as non-serializable
If you were to write the object to a file, that field marked as transient would be ignored
transient is a variable modifier used in serialization. At the time of serialization, if we don’t want to save the value of a particular variable in a file, then we use the transient keyword. When the JVM comes across a transient keyword, it ignores the original value of the variable and saves the default value of that variable data type.

List the access modifiers from most visible to least visible
public > protected > default > private

What is the difference in visibility between protected and package-private(default) access level?
Protected - class and subclass accessible
Default - class and subclass accessible in the same package

What are some non-access modifying keywords used in Java?
For functionality.
static final abstract transient synchronized volatile

What is the difference between an interface and an abstract class?
Interface - is a completely “abstract class” to group related methods with empty bodies.
Has to be implemented.
One class can implement multiple class
Abstract class - class has abstract method - can not be instantiated
Type of methods: Interface can have only abstract methods. An abstract class can have abstract and non-abstract methods. From Java 8, it can have default and static methods also.
Final Variables: Variables declared in a Java interface are by default final. An abstract class may contain non-final variables.
Type of variables: Abstract class can have final, non-final, static and non-static variables. The interface has only static and final variables.
Implementation: Abstract class can provide the implementation of the interface. Interface can’t provide the implementation of an abstract class.
Inheritance vs Abstraction: A Java interface can be implemented using the keyword “implements” and an abstract class can be extended using the keyword “extends”.
Multiple implementations:
An interface can extend another Java interface only,
an abstract class can extend another Java class and implement multiple Java interfaces.
Accessibility of Data Members:
Members of a Java interface are public by default.
A Java abstract class can have class members like private, protected, etc.

Scanner
We can do this with the built in scanner class in Java
Most typically we will use System.in as the source for the scanner, this allows us to take input from the console
The Scanner class has methods to get entire lines of text, numbers, letters and more from the console
nextInt()
nextshort()
next() next token/word as String
nextLine() next line as String

What is the purpose of the .finalize() method?
The method garbage collector will call before clear up the object implemented the .finalize() method.

Is multiple inheritance supported in Java?
Through Class - no
Though Interface - yes.

Can garbage collected be forced in Java?
Calling the gc method suggests that the Java Virtual Machine expend effort toward recycling unused objects in order to make the memory they currently occupy available for quick reuse. When control returns from the method call, the Java Virtual Machine has made a best effort to reclaim space from all discarded objects.

What are packages used for?
A package in Java is used to group related classes
Use default access modifier to restrict the access to the certain package

What are imports?

What is the main method signature?
public static void main(String[] args)

What property of a Java primitive array tells us the size of the array?
length.

What are some constructs used in Java for flow control?
Decision

- If else
- switch
  Loop
- do while
- while
- for
- for-each
  Jump
- break
- continue

What is the difference between a while and a do-while loop?
Check the condition at the beginning of the loop.
Check condition at the end of the loop
So do while execute the loop at least one time.

What is the difference between a for loop and an enhanced for loop?
For - iterate part of the program multiple times.(for code)
Enhanced for - iterate a series of items in the iterable.(for data type)

Exception

Autoclosable(try-with-resources)
https://www.baeldung.com/java-try-with-resources

What is the problem?

Exceptions are objects, remember. There’s nothing all that special about one, except that it is a thing that can be thrown.(what they are and what they can do)
Exception the mechanism to tell the caller,what kind of risky thing could happen, you better be prepared for it.either handler it or even you can recover from it.

a throws clause in the risky method’s declaration.

If you wrap the risky code in something called a try/catch, the compiler will relax.(even you didn’t any, try catch you write at the compile time only make compiler happy)
A try/catch block tells the compiler that you know an exceptional thing could happen in the method you’re calling, and that you’re prepared to handle it. That compiler doesn’t care how you handle it; it cares only that you say you’re taking care of it.

In reality, it might be you who wrote both classes. It really doesn’t matter who writes the code... what matters is knowing which method throws the exception and which method catches it.

Runtime exceptions(all exceptions happen at run time) but here the runtime exceptions are series exceptions.
Most RuntimeExceptions
come from a problem in your code logic,
rather than a condition that fails at runtime in ways that you cannot predict or prevent.
You WANT RuntimeExceptions to happen at development and testing time.
A try/catch is for handling exceptional situations, not flaws in your code.
Run time code has to run without exception, it has to happen at the runtime, if you handle it so the code after the exception will not run. Some logic errors will happen.

What is the difference between an exception and an error in Java?
Error can not be recovered from.
Out of memory, stack overflow.
Exceptions can be recovered.

What is the difference between a checked and an unchecked exception?
Checked exception
IO or compile time exception
ClassNotFoundException
CloneNotSupportedException
Unchecked exception
RunTimeException
NullPointerException
ArithmeticException

Check and unchecked is from the compiler point of view.
Check at compile time.Must be handled or the compiler won't be happy.

Runtime exceptions are unchecked exceptions. Because it can not be checked at compile time.

Checked exception: IO or compile time Exception
Unchecked exception: runtime or null pointer exceptions or out of bound

How can exceptions be handled in Java?
try/catch
throws(duck) by declare it(javascript just re-throw it)

try/catch
The try/catch/finally block allows you to enclose code that may throw an exception inside of the try block
The catch block takes in a specific exception that you are expecting, and any logic to run if there is an exception
The finally block is tacked on at the end of the catch, this will run some logic regardless of the result
Multiple catches are allowed, but they must go from most specific exception to specific exception
You can catch more than one exception per catch block with the “|”
Finally is completely optional
try/finally is legal syntax, but a try block by itself is not legal syntax

What is the purpose of the finally block?

Are you required to handle RuntimeExceptions?
If you handle all the exceptions, you lose the ability to track back where the exception errors.
Also when you catch all exceptions, you may get an exception that cannot deal with and prevent code that is upper in the stack to handle it properly. The general principal is to catch the most specific type you can.
catch(Exception) is a bad practice because it catches all RuntimeException (unchecked exception)
You prevent upper in the stack handle it.

Can exceptions be caught by multiple catch blocks in any order?
Yes, and the order has to be from less general to more general.

Custom Exceptions
Extend the Exception class to create a checked exception
Extend the RunTimeException class to create an unchecked exception

Try with resources
try statement that declares one or more resources in it.A resource is an object that must be closed once your program is done using it. For example, a File resource or a Socket connection resource. The try-with-resources statement ensures that each resource is closed at the end of the statement execution. If we don’t close the resources, it may constitute a resource leak and also the program could exhaust the resources available to it

Object life cycle
https://keep.google.com/u/3/#NOTE/1Vy3mlNcQ4U8dUi4aFlWs3FCC_Y92ZBZ58q282w8BwbQ0LlRtJXKatSEOQXOkiQ

Garbage collection
https://keep.google.com/u/3/#NOTE/1ZQ-whqvHMUCqqqhd6cKuol1Ms6MsFd1HOU3CqKld-Dztb8Mjg0Ll9t7NCiaIrw

# QC Questions on Advanced Java

- What are static imports?
- Does Java employ "pass-by-value" or "pass-by-reference"?
- What are short-circuit boolean operators?
  String
  A string is traditionally a sequence of characters, either as a literal constant or as some kind of variable.

What is the String Pool?
String pool is nothing but a storage area in Java heap where string literals store.

What is the difference between String, StringBuilder, and StringBuffer?

Are Java Strings thread-safe? Why?
being immutable, has the specification that the Strings are constant; their values cannot be changed after they are created.

How can a String be created outside of the String Pool?
When we create a String object using the new() operator, it always creates a new object in heap memory.
Object Class
Every class in Java is directly or indirectly derived from the Object class. If a class does not extend any other class then it is a direct child class of Object and if extends another class then it is indirectly derived. Therefore the Object class methods are available to all Java classes. Hence the Object class acts as a root of inheritance hierarchy in any Java Program.

1. toString()
   It is always recommended to override the toString() method to get our own String representation of Object
2. hashCode()
   It converts the internal address of the object to an integer by using an algorithm.
   The hashCode() method is native because in Java it is impossible to find the address of an object, so it uses native languages like C/C++ to find the address of the object.
3. equals(Object obj)
   It compares the given object to “this” object (the object on which the method is called). It gives a generic way to compare objects for equality. It is recommended to override the equals(Object obj) method to get our own equality condition on Objects. For more on override of equals(Object obj) method refer
4. getClass():
   It returns the class object of “this” object and is used to get the actual runtime class of the object. It can also be used to get metadata of this class. The returned Class object is the object that is locked by static synchronized methods of the represented class. As it is final so we don’t override it.
5. finalize() method:
   This method is called just before an object is garbage collected. It is called the Garbage Collector on an object when the garbage collector determines that there are no more references to the object. We should override finalize() method to dispose of system resources, perform clean-up activities and minimize memory leaks. For example, before destroying Servlet objects web container, always called finalize method to perform clean-up activities of the session.
6. clone():
   It returns a new object that is exactly the same as this object. For clone() method refer Clone().
   In Java, there is no operator to create a copy of an object. Unlike C++, in Java, if we use the assignment operator then it will create a copy of the reference variable and not the object.
   Deep copy vs shallow copy https://www.geeksforgeeks.org/clone-method-in-java-2/

Comparable(@compareTo)
https://www.geeksforgeeks.org/comparable-vs-comparator-in-java/
@orverride compareTo()
To compare it self to a instantanse of comparable
The relationship between the two instances of the same type that implements Comparable
Collections.sort(list)

Comparator
External object, a separate class.
Is bound to the comparable type. class RatingCompare implements Comparator<Movie>
Use instance of comparator, to compare a list
Collections.sort(list,comparator)

What is string interning?
String Interning is a method of storing only one copy of each distinct String Value, which must be immutable.
By applying String.intern() on a couple of strings will ensure that all strings having the same contents share the same memory. For example, if a name ‘Amy’ appears 100 times, by interning you ensure only one ‘Amy’ is actually allocated memory.

What causes a NullPointerException?
when program attempts to use an object reference that has the null value.

Annotation
Annotations are used to provide supplemental information about a program.
@
Annotations do not change the action of a compiled program
Annotations help to associate metadata (information) to the program elements i.e. instance variables, constructors, methods, classes, etc.
Annotations are not pure comments as they can change the way a program is treated by the compiler.
Annotations basically are used to provide additional information, so could be an alternative to XML and Java marker interfaces.

Marker Annotations
@TestAnnotation()
Contains no members

Single value Annotations
Only one member is allowed
string
Full Annotations
Names values pairs

Type Annotations
where a type is being used
Repeating Annotations
https://www.geeksforgeeks.org/annotations-in-java/

- What is reflection?
  Reflection is an API that is used to examine or modify the behavior of methods, classes, and interfaces at runtime.
  https://www.geeksforgeeks.org/reflection-in-java/

- Proxy
  https://www.baeldung.com/java-dynamic-proxies
  https://jenkov.com/tutorials/java-reflection/dynamic-proxies.html

- Why do abstract classes have constructors?
  Constructor chain
  When the sub class instantiate a instance. The super() method in the abstract class’s calls the abstract class’s parent class constructor. this way, it establish the chaining between the abstract class’s subclass and abstract class’s parent class.

The main purpose of the constructor is to initialize the newly created object. In abstract class, we have an instance variable, abstract methods, and non-abstract methods. We need to initialize the non-abstract methods and instance variables, therefore abstract classes have a constructor.
Also, even if we don’t provide any constructor the compiler will add default constructor in an abstract class.
An abstract class can be inherited by any number of sub-classes, thus functionality of constructor present in abstract class can be used by them.
The constructor inside the abstract class can only be called during constructor chaining i.e. when we create an instance of sub-classes. This is also one of the reasons abstract class can have a constructor.

- What modifying keywords are implicitly applied to variable members declared within an interface?
  Interface methods are by default abstract and public
  Interface attributes are by default public, static and final
  An interface cannot contain a constructor (as it cannot be used to create objects)

- What are functional interfaces?
  Functional interfaces are interfaces that have only one abstract method.
  Before Java 8, we would usually create a class for every case where we needed to encapsulate a single piece of functionality. This implied a lot of unnecessary boilerplate code to define something that served as a primitive function representation.
  No state
- What are marker interfaces?
  Give it a meaning without adding constraints or methods.
  It’s a indicator.
  A marker interface is an interface that has no methods or constants inside it. It provides run-time type information about objects, so the compiler and JVM have additional information about the object.
  hen calling the ObjectOutputStream.writeObject() method, the JVM checks if the object implements the Serializable marker interface.
  Unlike annotations, interfaces allow us to take advantage of polymorphism. As a result, we can add additional restrictions to the marker interface.

- What are annotations used for in Java?

- What are default interface methods?
  Java annotations are special constructs
  These annotations provide metadata about the source code to the compiler and the JVM
  @class @methods @interface @otherConstructs
  enforce rules in the code
  abstract some functionality provided by a library or framework.
  Java frameworks and libraries often process annotations using the Reflection API (covered in another module) to dynamically provide functionality to developers.
  @Override - declares the method must override an inherited method (otherwise, a compilation error occurs)
  @Deprecated - marks a method as obsolete (compilation warning if used anywhere)
  @SuppressWarnings - instructs compiler to supress compilation warnings
  @FunctionalInterface - designates an interface to be a functional interface (covered in another module)

- Why is the main method declared static in Java?
  The main() method is static so that JVM can invoke it without instantiating the class. This also saves the unnecessary wastage of memory which would have been used by the object declared only for calling the main() method by the JVM.
- Does the logic in a static block member of a class run before or after the class's constructor logic is called?
  static blocks are automatically called as soon as class is loaded in memory
  Can we print something on the console without creating main() method?
  It is very important question from the interview’s perceptive point. The answer is yes we can print if we are using JDK version 1.6 or previous and if after that it will throw an. Error.

- What is a thread in Java?
  Concurrency refers to breaking up a task or piece of computation into different parts that can be executed independently, out of order, or in partial order without affecting the final outcome. One way - but not the only way - of achieving concurrency is by using multiple threads in the same program.
  Without this, any process that took too long in the background, like reading / writing to files or making an HTTP request, would block the GUI and prevent any other user input.
  Most computers these days have multiple cores or CPUs, which means that calculations at the hardware level can be done in parallel. Without multiple cores, operating systems can still achieve concurrency with a process called time splicing - this means running one process for a short time, then switching to another, and back very rapidly. This ensures that no process or application is completely blocked
  A Java Thread is like a virtual CPU that can execute your Java code - inside your Java application. when a Java application is started its main() method is executed by the main thread - a special thread that is created by the Java VM to run your application. From inside your application you can create and start more threads which can execute parts of your application code in parallel with the main thread.
  Java threads are objects like any other Java objects. Threads are instances of class java.lang.Thread, or instances of subclasses of this class. In addition to being objects, java threads can also execute code. In this Java thread tutorial I will explain how to create and start threads.
  A thread is a subset of a process that is also an independent sequence of execution, but threads of the main process run in the same memory space, managed independently by a scheduler. So, we can think of a thread as a "path of execution", but they can access the same objects in memory.
  Every thread that is created in a program is given its own call stack, where it stores local variables references. However, all threads share the same heap, where the objects live in memory.
  Thus, two threads could have separate variable references on two different stacks that still point to the same object in the heap.
  Multithreading(OS level)
  Different threads in different core

In general, it is best to avoid implementing multithreading yourself if possible.
Increase complexity.
web servers like Apache Tomcat have multithreading built-in and provide APIs for dealing with network requests without having to worry about threads.

- How can you create a thread in Java?
  Implementing the java.lang.Runnable interface.
  Extending the java.lang.Thread class.
- What are the states of a thread?
  New: newly created thread that has not started executing
  Runnable: either running or ready for execution but waiting for its resource allocation
  Blocked: waiting to acquire a monitor lock to enter or re-enter a synchronized block/method
  Waiting: waiting for some other thread to perform an action without any time limit
  Timed_Waiting: waiting for some other thread to perform a specific action for a specified time period
  Terminated: has completed its execution

- What is the difference between the .run() and .start() methods?
  Start creates a thread, run starts execution.
  start(): New → Runnable(ready)--> (Runniing)(running)
  run(): Runnable → Running
- What is the keyword "synchronized" used for?
  A piece of logic marked with synchronized becomes a synchronized block, allowing only one thread to execute at any given time.
- What causes a deadlock?
  synchronized keyword is used to make the class or method thread-safe which means only one thread can have lock of synchronized method and use it, other threads have to wait till the lock releases and anyone of them acquire that lock.
  It is important to use if our program is running in multi-threaded environment where two or more threads execute simultaneously. But sometimes it also causes a problem which is called Deadlock. Below is a simple example of Deadlock condition.
- What is the function of the .join() method?
- Describe the characteristics and application of the singleton design pattern
- Describe the characteristics and application of the factory design pattern
- What is a lambda expression?
  lambda expression in computer programming, also called an anonymous function, is a defined function not bound to an identifier
  Pure function
  Fist class citizen.
- What are the differences between a lambda expression and a local anonymous class?
- Are lambda expressions replacements to local anonymous classes?
- What is a functional interface?

- Is the @FunctionalInterface annotation required to denote a functional interface?
- What are some examples of functional interfaces?
- What are method references? Describe their syntax.
- What kinds of methods can be references using method references?
- What is a default method, and why should you use them?
  Default can have a body.

Java Stream API Interview Questions And Answers
In this post Java Stream API Interview Questions and answers are listed. This compilation will help the Java developers in preparing for their interviews.
What is Stream API in Java?
Stream API is added in Java 8 and works very well in conjunction with lambda expressions. You can create a pipeline of stream operations to manipulate data by performing operations like search, filter, sort, count, map etc.
Read more about Stream API in Java here.
What is stream in Stream API?
A stream can be visualized as a pipeline. A stream pipeline consists of a source (which might be an array, a collection, a generator function, an I/O channel, etc.), zero or more intermediate operations (which transform a stream into another stream, such as filter(Predicate)), and a terminal operation (which produces a result or side-effect, such as count() or forEach(Consumer)).
Read more about Stream API in Java here.
Explain stream operations with an example?
In this example let's take an ArrayList as an input. There are two operations - take only those elements of the list which are greater than 5 and then sort the result. After that print the elements of the list.
// Creating the list
List<Integer> numList = Arrays.asList(34, 6, 3, 12, 65, 1, 8);
numList.stream().filter((n) -> n > 5).sorted().forEach(System.out::println);
Here ArrayList is the data source for the stream and there are two intermediate operations–
filter- Filter condition here is; take only those elements of the list which are greater than 5.
sorted- sort that filtered output of the last stream.
Terminal operation here is forEach statement (provided in Java 8) which iterates the sorted result and displays them. Read more about forEach statement in Java 8 here.
How many types of Stream operations are there?
Stream operations are divided into intermediate and terminal operations, and are combined to form stream pipelines.
Intermediate operations return a new stream. They are always lazy; executing an intermediate operation does not actually perform any filtering, but instead creates a new stream that, when traversed, contains the elements of the initial stream that match the given predicate.
Terminal operations such as Stream.forEach or IntStream.sum, may traverse the stream to produce a result or a side-effect. After the terminal operation is performed, the stream pipeline is considered consumed, and can no longer be used.
See some Stream API examples here.
What are Stateless and Stateful operations in Java stream?
Intermediate operations are further divided into stateless and stateful operations.
Stateless operations, such as filter and map, retain no state from previously seen element when processing a new element, each element can be processed independently of operations on other elements.
Stateful operations, such as distinct and sorted, may incorporate state from previously seen elements when processing new elements. Stateful operations may need to process the entire input before producing a result. For example, one cannot produce any results from sorting a stream until one has seen all elements of the stream.
See some Stream API examples here.
What is Parallel Stream in Java Stream API?
You can execute streams in serial or in parallel. When a stream executes in parallel, the Java runtime partitions the stream into multiple sub-streams.
As example - Collection has methods Collection.stream() and Collection.parallelStream(), which produce sequential and parallel streams respectively.
Read more about parallel stream here.
What is the benefit of using parallel stream?
When parallel stream is used the Java runtime partitions the stream into multiple sub-streams. This parallel execution of data, with each sub-stream running in a separate thread, will result in increase in performance.
Read more about parallel stream here.
Can you use streams with primitives?
Streams work only on object references. They can’t work on primitive types so you have two options to use primitives.
You can wrap primitive types into a wrapper object. As example Stream<Integer>, Stream<Long> or Stream<Double>.
Second and better option is to use primitive specializations of Stream like IntStream, LongStream, and DoubleStream that can store primitive values.
As example - IntStream is = IntStream.of(3, 4, 5, 6);
Read more about Primitive type streams in Java here.
How can you transform Stream to primitive type Stream?
Stream interface provides methods mapToInt, mapToDouble and mapToLong that can be used to transform stream of objects to a stream of primitive types.
As example- If you have a list of employee objects and you want to get the maximum salary. In that case you can take the salary field and use mapToInt method to get a stream of primitive types. Then you can use max method on that primmitive type stream.
OptionalInt maxSalary = empList.parallelStream().mapToInt(e -> e.getSalary()).max();
Read more about Primitive type streams in Java Stream API here.
What are Reduction Operations in Java Stream API?
Stream API contains many terminal operations (such as average, sum, min, max, and count) that return one value by combining the contents of a stream. These operations are called reduction operations because these operations reduce the stream to a single non-stream value.
Read more about Reduction Operations in Java Stream API here.
What are Map operation in Java Stream API?
Map operations are used to do the element mapping from one stream to another. Map operation will return a stream consisting of the results of applying the given function to the elements of this stream. So, whatever function is provided is applied on all the elements of the stream.
Since new stream is returned map operation is an intermediate operation.
Read more about Map operation in Java Stream API here.
What is a mutable reduction operation?
A mutable reduction operation can be defined as an operation that accumulates input elements into a mutable result container, such as a Collection or StringBuilder.
Read more about Reduction operation in Java Stream API here.
What is a collect method in Java stream?
Using collect method you can store the result of the stream operation into a collection. This is a terminal operation.
As example - If you have employee objects and you want a list having names of all the employees you can use the toList method of the Collectors class.
List<String> nameList = empList.stream().map(Employee::getName).collect(Collectors.toList());
Read more about Collecting in Java Stream API here.
What is flatMap() method in Java?
In mapping operation the given function is applied to all the elements of the stream. Where as flattening a structure, means bringing all the nested structures at the same level.
As example if you have a list of Strings, list<String> like - [[“a”, “b”, “c”], [“c”, “d”], [“c”, “e”, “f”]] then flattening it will bring everything to the same level and the structure you will have be like this-
[“a”, “b”, “c”, “c”, “d”, “c”, “e”, “f”]
flatMap() method means you are bringing both of them together, function will be applied to all the elements of the stream and then it will be flatten to have a single level structure.
Read more about FlatMap in Java here.
What is a Spliterator in Java?
Spliterators, like iterators, are for traversing the elements of a source. Spliterator can split the source and iterate the splitted parts in parallel. That way a huge data source can be divided into small sized units that can be traversed and processed in parallel.
You can also use spliterator even if you are not using parallel execution.
Read more about Spliterator in Java here.

- When was the java.util.function package introduced?
- What are the main types of functional interfaces?
- What is the method signature of the abstract method in the Supplier interface?
- What is the method signature of the abstract method in the Consumer interface?
- How would you go about composing/combining multiple Consumers together?
- What is the method signature of the abstract method in the Predicate interface?
- What are the default methods of the Predicate interface?
- What is the method signature of the abstract method in the Function interface?
- What is a BiFunction?
- When should you use IntSupplier versus Supplier<Integer>?
- What is a Stream and how is it different than a Collection?
- What are intermediate Stream operations? Name a few.
- What are terminal Stream operations? Name a few.
- What is the function of Stream#map, what does it take as a parameter?
- What is the function of Stream#filter, what does it take as a parameter?
- What is the function of Stream#reduce, what does it take as a parameter?
- What is the function of Stream#flatMap, what does it take as a parameter?
- Articulate the difference between Stream#map and Stream#flatMap.
- Do Stream operations manipulate the collection being streamed?
- How can you convert an array into a Stream?
- What is an Optional?
- What are some ways of making Optional objects, since its constructor is declared as private?

Maven
