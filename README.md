# Java Boot Camp

Boot Camp for developers interested to learn Java.

## Plan

### [Primer](01%20-%20Primer.md)

1. [Java](01%20-%20Primer.md#java)
    1. [What is Java?](01%20-%20Primer.md#what-is-java)
    1. [How do we develop Java Applications?](01%20-%20Primer.md#how-do-we-develop-java-applications)
1. [Java Language Specification](01%20-%20Primer.md#java-language-specification)
1. [Setup Environment (SDKMAN)](01%20-%20Primer.md#setup-environment-sdkman)
1. [Gradle and Maven](01%20-%20Primer.md#gradle-and-maven)
    1. [Advantages of Gradle over Maven](01%20-%20Primer.md#advantages-of-gradle-over-maven)
    1. [Install Gradle](01%20-%20Primer.md#install-gradle)
1. [IDE (IntelliJ IDEA and VS Code)](01%20-%20Primer.md#ide-intellij-idea-and-vs-code)
1. [Create a project using Gradle](01%20-%20Primer.md#create-a-project-using-gradle)
    1. [Create Project](01%20-%20Primer.md#create-project)
    1. [Explore Project](01%20-%20Primer.md#explore-project)
1. [Hello World Application (from source to executable application)](01%20-%20Primer.md#hello-world-application-from-source-to-executable-application)
    1. [Gradle Task Dependency Tree](01%20-%20Primer.md#gradle-task-dependency-tree)
    1. [Project Dependencies](01%20-%20Primer.md#project-dependencies)
    1. [Package Project](01%20-%20Primer.md#package-project)
    1. [Make use of third-party libraries](01%20-%20Primer.md#make-use-of-third-party-libraries)
        1. [The Classpath](01%20-%20Primer.md#the-classpath)
    1. [Make a fat JAR](01%20-%20Primer.md#make-a-fat-jar)
1. [Docker](01%20-%20Primer.md#docker)
    1. [What is Docker?](01%20-%20Primer.md#what-is-docker)
    1. [How does this work?](01%20-%20Primer.md#how-does-this-work)
    1. [More than just Containers](01%20-%20Primer.md#more-than-just-containers)
    1. [Setup Docker](01%20-%20Primer.md#setup-docker)
    1. [Working with Docker](01%20-%20Primer.md#working-with-docker)
    1. [Dockerize the Application](01%20-%20Primer.md#dockerize-the-application)
    1. [Multi-Stage Docker Build](01%20-%20Primer.md#multi-stage-docker-build)
1. [Managing Docker Containers](01%20-%20Primer.md#managing-docker-containers)

### [Data Types](02%20-%20Data%20Types.md)

1. [JShell](02%20-%20Data%20Types.md#jshell)
1. [Numbers and Strings (Variables and Scope)](02%20-%20Data%20Types.md#numbers-and-strings-variables-and-scope)
    1. [Puzzle (Time for a change)](02%20-%20Data%20Types.md#puzzle-time-for-a-change)
    1. [Puzzle (Long Division)](02%20-%20Data%20Types.md#puzzle-long-division)
    1. [Puzzle (It's Elementary)](02%20-%20Data%20Types.md#puzzle-its-elementary)
    1. [Puzzle (The Joy of Hex)](02%20-%20Data%20Types.md#puzzle-the-joy-of-hex)
    1. [Puzzle (Hello Whirled)](02%20-%20Data%20Types.md#puzzle-hello-whirled)
    1. [Puzzle (Line Printer)](02%20-%20Data%20Types.md#puzzle-line-printer)
    1. [Puzzle (huh?)](02%20-%20Data%20Types.md#puzzle-huh)
    1. [Puzzle (String Cheese)](02%20-%20Data%20Types.md#puzzle-string-cheese)
    1. [Puzzle (Classy Fire)](02%20-%20Data%20Types.md#puzzle-classy-fire)
    1. [Puzzle (What's my class?)](02%20-%20Data%20Types.md#puzzle-whats-my-class)
    1. [Puzzle (What's my class, Take 2)](02%20-%20Data%20Types.md#puzzle-whats-my-class-take-2)
    1. [Mutable Strings](02%20-%20Data%20Types.md#mutable-strings)
        1. [Puzzle (No Pain, No Gain)](02%20-%20Data%20Types.md#puzzle-no-pain-no-gain)
    1. [Multiline Strings](02%20-%20Data%20Types.md#multiline-strings)
    1. [Primitive Types](02%20-%20Data%20Types.md#primitive-types)
    1. [Signed and Unsigned Integrals](02%20-%20Data%20Types.md#signed-and-unsigned-integrals)
    1. [Reference Types (the rest)](02%20-%20Data%20Types.md#reference-types-the-rest)
    1. [Variables and their Values](02%20-%20Data%20Types.md#variables-and-their-values)
1. [Stack and Heap](02%20-%20Data%20Types.md#stack-and-heap)
    1. [OS Process Memory](02%20-%20Data%20Types.md#os-process-memory)
    1. [What goes in the Java Stack?](02%20-%20Data%20Types.md#what-goes-in-the-java-stack)
    1. [What goes in the Java Heap?](02%20-%20Data%20Types.md#what-goes-in-the-java-heap)
    1. [Variables without a value](02%20-%20Data%20Types.md#variables-without-a-value)
    1. [Can we have a reference variable without the equivalent object in the Java heap (null)?](02%20-%20Data%20Types.md#can-we-have-a-reference-variable-without-the-equivalent-object-in-the-java-heap-null)
        1. [What happens if we try to call a method on a null object?](02%20-%20Data%20Types.md#what-happens-if-we-try-to-call-a-method-on-a-null-object)
        1. [What is NullPointerException?](02%20-%20Data%20Types.md#what-is-nullpointerexception)
    1. [The new operator and the Java Heap](02%20-%20Data%20Types.md#the-new-operator-and-the-java-heap)
    1. [Garbage Collection](02%20-%20Data%20Types.md#garbage-collection)
    1. [String or new String?](02%20-%20Data%20Types.md#string-or-new-string)
    1. [What happens to a variable when it goes out of scope?](02%20-%20Data%20Types.md#what-happens-to-a-variable-when-it-goes-out-of-scope)
1. [Operators](02%20-%20Data%20Types.md#operators)
    1. [Puzzle (Tweedledum)](02%20-%20Data%20Types.md#puzzle-tweedledum)
    1. [Puzzle (Tweedledee)](02%20-%20Data%20Types.md#puzzle-tweedledee)
    1. [Puzzle (The Last Laugh)](02%20-%20Data%20Types.md#puzzle-the-last-laugh)
    1. [Puzzle (Oddity)](02%20-%20Data%20Types.md#puzzle-oddity)
    1. [Puzzle (Swap Meat)](02%20-%20Data%20Types.md#puzzle-swap-meat)
    1. [Puzzle (Escape Rout)](02%20-%20Data%20Types.md#puzzle-escape-rout)
    1. [Puzzle (A Big Delight in Every Byte)](02%20-%20Data%20Types.md#puzzle-a-big-delight-in-every-byte)
    1. [Puzzle (Inclement Increment)](02%20-%20Data%20Types.md#puzzle-inclement-increment)
1. [Mutable and Immutable](02%20-%20Data%20Types.md#mutable-and-immutable)
    1. [The final keyword](02%20-%20Data%20Types.md#the-final-keyword)
1. [Casting](02%20-%20Data%20Types.md#casting)
    1. [Puzzle (Multicast)](02%20-%20Data%20Types.md#puzzle-multicast)
1. [Autoboxing](02%20-%20Data%20Types.md#autoboxing)
    1. [Autoboxing is an easy target for NullPointerException](02%20-%20Data%20Types.md#autoboxing-is-an-easy-target-for-nullpointerexception)
1. [Enumerations](02%20-%20Data%20Types.md#enumerations)
    1. [Enums in Java can have methods](02%20-%20Data%20Types.md#enums-in-java-can-have-methods)
    1. [Enum's Ordinal](02%20-%20Data%20Types.md#enums-ordinal)
    1. [Enums in Java can have state](02%20-%20Data%20Types.md#enums-in-java-can-have-state)
    1. [Enums can extend functionality](02%20-%20Data%20Types.md#enums-can-extend-functionality)
1. [Imports, Static Imports and Packages](02%20-%20Data%20Types.md#imports-static-imports-and-packages)
    1. [Imports](02%20-%20Data%20Types.md#imports)
    1. [Static Imports](02%20-%20Data%20Types.md#static-imports)
    1. [Packages](02%20-%20Data%20Types.md#packages)
1. [Date Time API](02%20-%20Data%20Types.md#date-time-api)
1. [Internationalization](02%20-%20Data%20Types.md#internationalization)

### [Classes, Methods and Objects](03%20-%20Classes%2C%20Methods%20and%20Objects.md)

1. [Classes and methods (static no OOP)](03%20-%20Classes%2C%20Methods%20and%20Objects.md#classes-and-methods-static-no-oop)
    1. [Is void a type?](03%20-%20Classes%2C%20Methods%20and%20Objects.md#is-void-a-type)
1. [Properties (static no OOP)](03%20-%20Classes%2C%20Methods%20and%20Objects.md#properties-static-no-oop)
1. [How can we test functionality that makes use of static?](03%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-test-functionality-that-makes-use-of-static)
1. [Simple Objects](03%20-%20Classes%2C%20Methods%20and%20Objects.md#simple-objects)
    1. [Basic Object](03%20-%20Classes%2C%20Methods%20and%20Objects.md#basic-object)
    1. [Add State](03%20-%20Classes%2C%20Methods%20and%20Objects.md#add-state)
    1. [More State](03%20-%20Classes%2C%20Methods%20and%20Objects.md#more-state)
    1. [Multiple Instances](03%20-%20Classes%2C%20Methods%20and%20Objects.md#multiple-instances)
    1. [Mutable and Immutable](03%20-%20Classes%2C%20Methods%20and%20Objects.md#mutable-and-immutable)
1. [Inheritance](03%20-%20Classes%2C%20Methods%20and%20Objects.md#inheritance)
    1. [Light Box Example](03%20-%20Classes%2C%20Methods%20and%20Objects.md#light-box-example)
    1. [Heavy Box Example](03%20-%20Classes%2C%20Methods%20and%20Objects.md#heavy-box-example)
    1. [The `super` keyword](03%20-%20Classes%2C%20Methods%20and%20Objects.md#the-super-keyword)
    1. [The `final` keyword](03%20-%20Classes%2C%20Methods%20and%20Objects.md#the-final-keyword)
    1. [Private Constructor](03%20-%20Classes%2C%20Methods%20and%20Objects.md#private-constructor)
1. [Abstraction](03%20-%20Classes%2C%20Methods%20and%20Objects.md#abstraction)
    1. [When a class must be abstract?](03%20-%20Classes%2C%20Methods%20and%20Objects.md#when-a-class-must-be-abstract)
    1. [Final Classes](03%20-%20Classes%2C%20Methods%20and%20Objects.md#final-classes)
1. [The Object Class](03%20-%20Classes%2C%20Methods%20and%20Objects.md#the-object-class)
    1. [Puzzle (Animal Farm)](03%20-%20Classes%2C%20Methods%20and%20Objects.md#puzzle-animal-farm)
1. [Interfaces](03%20-%20Classes%2C%20Methods%20and%20Objects.md#interfaces)
    1. [Default methods](03%20-%20Classes%2C%20Methods%20and%20Objects.md#default-methods)
1. [instanceof and cast operators](03%20-%20Classes%2C%20Methods%20and%20Objects.md#instanceof-and-cast-operators)
1. [Inheritance and Composition](03%20-%20Classes%2C%20Methods%20and%20Objects.md#inheritance-and-composition)
1. [Overloading and Overriding](03%20-%20Classes%2C%20Methods%20and%20Objects.md#overloading-and-overriding)
    1. [Overloading](03%20-%20Classes%2C%20Methods%20and%20Objects.md#overloading)
    1. [Overriding](03%20-%20Classes%2C%20Methods%20and%20Objects.md#overriding)
1. [Outer, Inner and Anonymous Classes](03%20-%20Classes%2C%20Methods%20and%20Objects.md#outer-inner-and-anonymous-classes)
    1. [Outer Class](03%20-%20Classes%2C%20Methods%20and%20Objects.md#outer-class)
    1. [Inner Class](03%20-%20Classes%2C%20Methods%20and%20Objects.md#inner-class)
    1. [Inner Anonymous Class](03%20-%20Classes%2C%20Methods%20and%20Objects.md#inner-anonymous-class)
1. [Annotations](03%20-%20Classes%2C%20Methods%20and%20Objects.md#annotations)
    1. [Project Lombok](03%20-%20Classes%2C%20Methods%20and%20Objects.md#project-lombok)
1. [Generics](03%20-%20Classes%2C%20Methods%20and%20Objects.md#generics)
1. [Miscellaneous](03%20-%20Classes%2C%20Methods%20and%20Objects.md#miscellaneous)

### [Collections](04%20-%20Collections.md)

1. [Arrays](04%20-%20Collections.md#arrays)
    1. [Create Arrays](04%20-%20Collections.md#create-arrays)
        1. [Puzzle (ABC)](04%20-%20Collections.md#puzzle-abc)
    1. [Working with Arrays](04%20-%20Collections.md#working-with-arrays)
    1. [Read past the array's length](04%20-%20Collections.md#read-past-the-arrays-length)
    1. [Multidimensional Arrays](04%20-%20Collections.md#multidimensional-arrays)
        1. [Two dimensional array](04%20-%20Collections.md#two-dimensional-array)
        1. [Irregular Arrays](04%20-%20Collections.md#irregular-arrays)
    1. [Arrays are always Mutable](04%20-%20Collections.md#arrays-are-always-mutable)
    1. [Defensive Copying](04%20-%20Collections.md#defensive-copying)
    1. [Arrays of Objects](04%20-%20Collections.md#arrays-of-objects)
    1. [Sorting and Searching](04%20-%20Collections.md#sorting-and-searching)
    1. [An Array of Characters Is Not a String](04%20-%20Collections.md#an-array-of-characters-is-not-a-string)
1. [Lists (Vector, ArrayList and LinkedList)](04%20-%20Collections.md#lists-vector-arraylist-and-linkedlist)
    1. [Create Lists](04%20-%20Collections.md#create-lists)
    1. [Types of Lists](04%20-%20Collections.md#types-of-lists)
        1. [Vector](04%20-%20Collections.md#vector)
        1. [ArrayList](04%20-%20Collections.md#arraylist)
        1. [LinkedList](04%20-%20Collections.md#linkedlist)
        1. [Which List to Use?](04%20-%20Collections.md#which-list-to-use)
    1. [Double Brace Initialization](04%20-%20Collections.md#double-brace-initialization)
    1. [Mutable and Immutable Lists](04%20-%20Collections.md#mutable-and-immutable-lists)
1. [Set (HashSet, LinkedHashSet and TreeSet)](04%20-%20Collections.md#set-hashset-linkedhashset-and-treeset)
    1. [Create Sets](04%20-%20Collections.md#create-sets)
    1. [Set values MUST BE Immutable](04%20-%20Collections.md#set-values-must-be-immutable)
    1. [Types of Sets](04%20-%20Collections.md#types-of-sets)
        1. [HashSet](04%20-%20Collections.md#hashset)
        1. [LinkedHashSet](04%20-%20Collections.md#linkedhashset)
        1. [TreeSet](04%20-%20Collections.md#treeset)
        1. [Which Set to Use?](04%20-%20Collections.md#which-set-to-use)
    1. [Mutable and Immutable Sets](04%20-%20Collections.md#mutable-and-immutable-sets)
1. [Map (Hashtable, HashMap, LinkedHashMap and TreeMap)](04%20-%20Collections.md#map-hashtable-hashmap-linkedhashmap-and-treemap)
    1. [Create Maps](04%20-%20Collections.md#create-maps)
    1. [Map Keys MUST BE Immutable](04%20-%20Collections.md#map-keys-must-be-immutable)
    1. [Types of Maps](04%20-%20Collections.md#types-of-maps)
        1. [Hashtable](04%20-%20Collections.md#hashtable)
        1. [HashMap](04%20-%20Collections.md#hashmap)
        1. [LinkedHashMap](04%20-%20Collections.md#linkedhashmap)
        1. [TreeMap](04%20-%20Collections.md#treemap)
        1. [Which Map to Use?](04%20-%20Collections.md#which-map-to-use)
    1. [Relation between Collections the Objects they contain](04%20-%20Collections.md#relation-between-collections-the-objects-they-contain)
        1. [List and the equals() method](04%20-%20Collections.md#list-and-the-equals-method)
        1. [Hash based Collections and the equals() and hashCode() methods](04%20-%20Collections.md#hash-based-collections-and-the-equals-and-hashcode-methods)
1. [Queue and Stack](04%20-%20Collections.md#queue-and-stack)
    1. [Queues](04%20-%20Collections.md#queues)
    1. [Stacks](04%20-%20Collections.md#stacks)
1. [Java Collections Framework](04%20-%20Collections.md#java-collections-framework)
1. [Google Guava (Collections)](04%20-%20Collections.md#google-guava-collections)

### [Control Flow](05%20-%20Control%20Flow.md)

1. [Access Control](05%20-%20Control%20Flow.md#access-control)
    1. [Classes Access Modifiers Table](05%20-%20Control%20Flow.md#classes-access-modifiers-table)
    1. [Class Members Access Modifiers Table](05%20-%20Control%20Flow.md#class-members-access-modifiers-table)
1. [Control Flow and Loops](05%20-%20Control%20Flow.md#control-flow-and-loops)
    1. [If (if/else) Control Flow Statement](05%20-%20Control%20Flow.md#if-ifelse-control-flow-statement)
        1. [If Example](05%20-%20Control%20Flow.md#if-example)
        1. [If/else Example](05%20-%20Control%20Flow.md#ifelse-example)
        1. [If/else-if/else Example](05%20-%20Control%20Flow.md#ifelse-ifelse-example)
        1. [Java Ternary Operator](05%20-%20Control%20Flow.md#java-ternary-operator)
    1. [Switch Control Flow Statement](05%20-%20Control%20Flow.md#switch-control-flow-statement)
        1. [Switch Example](05%20-%20Control%20Flow.md#switch-example)
        1. [Switch Fallthrough Example](05%20-%20Control%20Flow.md#switch-fallthrough-example)
        1. [Switch Default Example](05%20-%20Control%20Flow.md#switch-default-example)
        1. [Switch Expressions](05%20-%20Control%20Flow.md#switch-expressions)
    1. [For Loop](05%20-%20Control%20Flow.md#for-loop)
        1. [Puzzles (In the Loop)](05%20-%20Control%20Flow.md#puzzles-in-the-loop)
    1. [While Loop](05%20-%20Control%20Flow.md#while-loop)
        1. [Puzzle (Shifty i's)](05%20-%20Control%20Flow.md#puzzle-shifty-is)
        1. [Puzzles (Looper)](05%20-%20Control%20Flow.md#puzzles-looper)
        1. [Puzzle (Bride of Looper)](05%20-%20Control%20Flow.md#puzzle-bride-of-looper)
        1. [Puzzle (Son of Looper)](05%20-%20Control%20Flow.md#puzzle-son-of-looper)
        1. [Puzzle (Ghost of Looper)](05%20-%20Control%20Flow.md#puzzle-ghost-of-looper)
    1. [Do/While Loop](05%20-%20Control%20Flow.md#dowhile-loop)
    1. [Foreach Loop](05%20-%20Control%20Flow.md#foreach-loop)
    1. [Nested Loops](05%20-%20Control%20Flow.md#nested-loops)
    1. [Break, Continue, Labels and Return](05%20-%20Control%20Flow.md#break-continue-labels-and-return)
        1. [Break](05%20-%20Control%20Flow.md#break)
        1. [Label](05%20-%20Control%20Flow.md#label)
            1. [Puzzle (Dupe of URL)](05%20-%20Control%20Flow.md#puzzle-dupe-of-url)
        1. [Continue](05%20-%20Control%20Flow.md#continue)
        1. [Return](05%20-%20Control%20Flow.md#return)
    1. [Loop and Control Flow Examples](05%20-%20Control%20Flow.md#loop-and-control-flow-examples)
        1. [How many rolls it takes to roll a 6?](05%20-%20Control%20Flow.md#how-many-rolls-it-takes-to-roll-a-6)
        1. [A simple game with dice and random numbers](05%20-%20Control%20Flow.md#a-simple-game-with-dice-and-random-numbers)
1. [Exceptions](05%20-%20Control%20Flow.md#exceptions)
    1. [Alternative Approach](05%20-%20Control%20Flow.md#alternative-approach)
1. [Java Single File Execution](05%20-%20Control%20Flow.md#java-single-file-execution)

### [Testing](06%20-%20Testing.md)

1. [Testing with JUnit 5 (Hamcrest and AssertJ)](06%20-%20Testing.md#testing-with-junit-5-hamcrest-and-assertj)
    1. [Add JUnit 5](06%20-%20Testing.md#add-junit-5)
    1. [Parameterized Test](06%20-%20Testing.md#parameterized-test)
    1. [Custom Converters](06%20-%20Testing.md#custom-converters)
    1. [Tests Tagging](06%20-%20Testing.md#tests-tagging)
    1. [Nested Tests](06%20-%20Testing.md#nested-tests)
    1. [Hamcrest](06%20-%20Testing.md#hamcrest)
    1. [AssertJ](06%20-%20Testing.md#assertj)
    1. [JUnit 5, Hamcrest and AssertJ](06%20-%20Testing.md#junit-5-hamcrest-and-assertj)
    1. [Test Lifecycle](06%20-%20Testing.md#test-lifecycle)
1. [Mocking (Mockito and EasyMock)](06%20-%20Testing.md#mocking-mockito-and-easymock)
    1. [What is Mocking (Test Doubles) and Why do we need it?](06%20-%20Testing.md#what-is-mocking-test-doubles-and-why-do-we-need-it)
    1. [Test Doubles](06%20-%20Testing.md#test-doubles)
    1. [Mockito](06%20-%20Testing.md#mockito)
    1. [EasyMock](06%20-%20Testing.md#easymock)
    1. [Which Mocking Framework](06%20-%20Testing.md#which-mocking-framework)
1. [Mutation Testing (PIT)](06%20-%20Testing.md#mutation-testing-pit)
1. [Google Guava (Preconditions)](06%20-%20Testing.md#google-guava-preconditions)

### [SOLID](07%20-%20SOLID.md)

1. [Single-responsibility Principle](07%20-%20SOLID.md#single-responsibility-principle)
1. [Open–closed principle](07%20-%20SOLID.md#open-closed-principle)
1. [Liskov substitution principle](07%20-%20SOLID.md#liskov-substitution-principle)
1. [Interface segregation principle](07%20-%20SOLID.md#interface-segregation-principle)
1. [Dependency inversion principle](07%20-%20SOLID.md#dependency-inversion-principle)

### [Lambda & Streams](08%20-%20Lambda%20&%20Streams.md)

1. [Lambda Expressions](08%20-%20Lambda%20&%20Streams.md#lambda-expressions)
    1. [Function as Parameters](08%20-%20Lambda%20&%20Streams.md#function-as-parameters)
    1. [Constructor as Parameters](08%20-%20Lambda%20&%20Streams.md#constructor-as-parameters)
1. [Multiple Parameters](08%20-%20Lambda%20&%20Streams.md#multiple-parameters)
1. [Dealing with Exceptions](08%20-%20Lambda%20&%20Streams.md#dealing-with-exceptions)
1. [Foreach Loops](08%20-%20Lambda%20&%20Streams.md#foreach-loops)
1. [Streams (Lambda)](08%20-%20Lambda%20&%20Streams.md#streams-lambda)
    1. [Filter](08%20-%20Lambda%20&%20Streams.md#filter)
    1. [ForEach](08%20-%20Lambda%20&%20Streams.md#foreach)
    1. [Map](08%20-%20Lambda%20&%20Streams.md#map)
    1. [FlatMap](08%20-%20Lambda%20&%20Streams.md#flatmap)
    1. [Mapping and Filtering](08%20-%20Lambda%20&%20Streams.md#mapping-and-filtering)
1. [Collectors](08%20-%20Lambda%20&%20Streams.md#collectors)
1. [Common Uses](08%20-%20Lambda%20&%20Streams.md#common-uses)
    1. [Sum numbers in List](08%20-%20Lambda%20&%20Streams.md#sum-numbers-in-list)
    1. [Sum content in List based on property](08%20-%20Lambda%20&%20Streams.md#sum-content-in-list-based-on-property)
    1. [Create Map from List](08%20-%20Lambda%20&%20Streams.md#create-map-from-list)

### [IO & Streams](09%20-%20IO%20&%20Streams.md)

1. [Try with Resources](09%20-%20IO%20&%20Streams.md#try-with-resources)
1. [Java Streams](09%20-%20IO%20&%20Streams.md#java-streams)
    1. [Buffered Streams](09%20-%20IO%20&%20Streams.md#buffered-streams)
1. [Java Readers](09%20-%20IO%20&%20Streams.md#java-readers)
    1. [Consuming an InputStream](09%20-%20IO%20&%20Streams.md#consuming-an-inputstream)
    1. [Writing to an OutputStream](09%20-%20IO%20&%20Streams.md#writing-to-an-outputstream)
1. [Java Non-Blocking IO](09%20-%20IO%20&%20Streams.md#java-non-blocking-io)
1. [HTTP Client (Java)](09%20-%20IO%20&%20Streams.md#http-client-java)

### [Databases](10%20-%20Databases.md)

1. [H2, MySQL and PostgreSQL](10%20-%20Databases.md#h2-mysql-and-postgresql)
1. [Data Sources (Hikari Connection Pool)](10%20-%20Databases.md#data-sources-hikari-connection-pool)
1. [Flyway (Database Migration)](10%20-%20Databases.md#flyway-database-migration)
1. [Statements, Prepared Statements, Result Sets](10%20-%20Databases.md#statements-prepared-statements-result-sets)
1. [Transactions](10%20-%20Databases.md#transactions)
1. [JOOQ](10%20-%20Databases.md#jooq)
1. [Query DSL](10%20-%20Databases.md#query-dsl)
1. [JPA and Hibernate](10%20-%20Databases.md#jpa-and-hibernate)

### [Concurrency](11%20-%20Concurrency.md)

1. [Java Memory Model](11%20-%20Concurrency.md#java-memory-model)
1. [Threads](11%20-%20Concurrency.md#threads)
    1. [Daemons](11%20-%20Concurrency.md#daemons)
    1. [Waiting for a thread to finish (Join)](11%20-%20Concurrency.md#waiting-for-a-thread-to-finish-join)
    1. [ThreadLocal](11%20-%20Concurrency.md#threadlocal)
    1. [Stale Caches](11%20-%20Concurrency.md#stale-caches)
    1. [Race Conditions](11%20-%20Concurrency.md#race-conditions)
    1. [Methods that should never be used.](11%20-%20Concurrency.md#methods-that-should-never-be-used)
1. [Concurrent Data Classes](11%20-%20Concurrency.md#concurrent-data-classes)
    1. [Primitive Wrappers](11%20-%20Concurrency.md#primitive-wrappers)
    1. [List](11%20-%20Concurrency.md#list)
    1. [Set](11%20-%20Concurrency.md#set)
    1. [Map](11%20-%20Concurrency.md#map)
    1. [Queue](11%20-%20Concurrency.md#queue)
    1. [Exchanger](11%20-%20Concurrency.md#exchanger)
1. [Classic Concurrency Control](11%20-%20Concurrency.md#classic-concurrency-control)
    1. [Volatile](11%20-%20Concurrency.md#volatile)
    1. [Synchronized](11%20-%20Concurrency.md#synchronized)
    1. [Deadlocks](11%20-%20Concurrency.md#deadlocks)
1. [New Approach to Concurrency](11%20-%20Concurrency.md#new-approach-to-concurrency)
    1. [Executors and Schedulers](11%20-%20Concurrency.md#executors-and-schedulers)
    1. [Lock and ReentrantLock](11%20-%20Concurrency.md#lock-and-reentrantlock)
    1. [Latch](11%20-%20Concurrency.md#latch)
    1. [CyclicBarrier](11%20-%20Concurrency.md#cyclicbarrier)
    1. [Fork Join Framework](11%20-%20Concurrency.md#fork-join-framework)
1. [Cost of Concurrency](11%20-%20Concurrency.md#cost-of-concurrency)
1. [Miscellaneous](11%20-%20Concurrency.md#miscellaneous)

### [Common Design Patterns](12%20-%20Common%20Design%20Patterns.md)

1. [Creational Design Pattern](12%20-%20Common%20Design%20Patterns.md#creational-design-pattern)
    1. [Factory Pattern](12%20-%20Common%20Design%20Patterns.md#factory-pattern)
    1. [Abstract Factory Pattern](12%20-%20Common%20Design%20Patterns.md#abstract-factory-pattern)
    1. [Singleton Pattern](12%20-%20Common%20Design%20Patterns.md#singleton-pattern)
    1. [Prototype Pattern](12%20-%20Common%20Design%20Patterns.md#prototype-pattern)
    1. [Builder Pattern.](12%20-%20Common%20Design%20Patterns.md#builder-pattern)
1. [Structural Design Pattern](12%20-%20Common%20Design%20Patterns.md#structural-design-pattern)
    1. [Adapter Pattern](12%20-%20Common%20Design%20Patterns.md#adapter-pattern)
    1. [Bridge Pattern](12%20-%20Common%20Design%20Patterns.md#bridge-pattern)
    1. [Composite Pattern](12%20-%20Common%20Design%20Patterns.md#composite-pattern)
    1. [Decorator Pattern](12%20-%20Common%20Design%20Patterns.md#decorator-pattern)
    1. [Facade Pattern](12%20-%20Common%20Design%20Patterns.md#facade-pattern)
    1. [Flyweight Pattern](12%20-%20Common%20Design%20Patterns.md#flyweight-pattern)
    1. [Proxy Pattern](12%20-%20Common%20Design%20Patterns.md#proxy-pattern)
1. [Behavioral Design Pattern](12%20-%20Common%20Design%20Patterns.md#behavioral-design-pattern)
    1. [Chain Of Responsibility Pattern](12%20-%20Common%20Design%20Patterns.md#chain-of-responsibility-pattern)
    1. [Command Pattern](12%20-%20Common%20Design%20Patterns.md#command-pattern)
    1. [Interpreter Pattern](12%20-%20Common%20Design%20Patterns.md#interpreter-pattern)
    1. [Iterator Pattern](12%20-%20Common%20Design%20Patterns.md#iterator-pattern)
    1. [Mediator Pattern](12%20-%20Common%20Design%20Patterns.md#mediator-pattern)
    1. [Memento Pattern](12%20-%20Common%20Design%20Patterns.md#memento-pattern)
    1. [Observer Pattern](12%20-%20Common%20Design%20Patterns.md#observer-pattern)
    1. [State Pattern](12%20-%20Common%20Design%20Patterns.md#state-pattern)
    1. [Strategy Pattern](12%20-%20Common%20Design%20Patterns.md#strategy-pattern)
    1. [Template Pattern](12%20-%20Common%20Design%20Patterns.md#template-pattern)
    1. [Visitor Pattern](12%20-%20Common%20Design%20Patterns.md#visitor-pattern)

### [Recommended Reading](13%20-%20Recommended%20Reading.md)

1. [Java](13%20-%20Recommended%20Reading.md#java)
1. [Gradle](13%20-%20Recommended%20Reading.md#gradle)
1. [Docker](13%20-%20Recommended%20Reading.md#docker)
1. [Kubernetes](13%20-%20Recommended%20Reading.md#kubernetes)
1. [JUnit](13%20-%20Recommended%20Reading.md#junit)
1. [Mockito](13%20-%20Recommended%20Reading.md#mockito)
1. [Miscellaneous](13%20-%20Recommended%20Reading.md#miscellaneous)
