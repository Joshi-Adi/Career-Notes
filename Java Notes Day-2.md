**Variables:**

A variable is a named memory location used to store data during program execution.

Why Variables?

we need them because they help to store data,reuse when required,change data accordingly when new info is updated...



Variables are just for defining the data, actual data is stored in the memory address with variable name as reference.

Variables stores diff types of data. Type of data defines the amount of memory can be allocated or a variable can hold.



Data types are dividen in two categories:

Primitive: stores data directly into memory

* Boolean(T/F)
* Byte(8 bits)				Range formula:-2^n to (2^n)-1
* char (2bytes=16bits)					n is no of bits
* short (16bits)
* int (32bit=4bytes)
* long (64 bits=8bytes)
* float(32bit)
* doubtle(64bit)



Non-Primitive: stores references rather than values

* string: Seq of char enclosed in ""
* class: blueprint of obj or variables and methods
* obj: Instance of class
* interface:An interface in Java is a blueprint of a class that specifies what a class should do, but not how it should do it. It is a core concept used to achieve full abstraction and multiple inheritance in Java programming 
* Array:An array stores multiple elements of the same type in a single structure. Arrays are obj in java



Naming rules for variables:

* Start with a Letter, $, or \_ and after first character , use letters,digits,$ or \_.
* No predefined keywords like class..
* Case sensitive i.e.. age and Age are diff variables
* No spaces 



**Scanner class:**



Scanner class belongs to java.util package allows to take or read input.

to use it first import java util package

&#x20; ---> import java.util.Scanner

then create a Scanner obj

&#x20; ---> Scanner sc=new Scanner(System.in)

Diff methods to take input using scanner class

* &#x20;nextBoolean()  Used for reading Boolean value.
* nextByte() Used for reading Byte value.
* nextDouble() Used for reading Double value.
* nextFloat() Used for reading Float value.
* nextInt() Used for reading Int value.
* nextLine() Used for reading Line value.
* nextLong() Used for reading Long value.
* nextShort() Used for reading Short value.
* next() Used for reading a single word

Eg.

Scanner sc=new Scanner(System.in)

int num=sc.nextInt()



**Keywords:**

Keywords are predefined words that has specific operation

Ex: int,class,interface,if,else,return

All datatypes are keywords, control-flow statements(if,else,for,while,..),

Exception handling(try,finally,throw),class,public,private,protected,..etc









































