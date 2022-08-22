# Compilation-Execution-of-a-Java-Program

Because Java is a platform-independent programming language, it does not provide one-step compilation.
Instead, it is executed in two steps: first through an OS-independent compiler, and then in a virtual machine(JVM) that is custom-built for each operating system.

![My Remote Image](https://sp-ao.shortpixel.ai/client/to_avif,q_glossy,ret_img,w_839/https://simplesnippets.tech/wp-content/uploads/2018/03/java-execution-flow-diagram.png)

## Compilation

A Java compiler is a computer software that is used to compile Java applications. It is platform agnostic.
It transforms source code (.java files) into bytecode (.class file).
In other words, bytecode is generated by the compiler (javac.exe) during the compilation process.

A bytecode is a binary code that the Java Virtual Machine (JVM) on the underlying operating system understands and interprets.
It is not comparable to machine code.


  ### Responsible tasks for Compiler
  
Apart from compiling a source program, Java compiler is responsible for the following tasks that are as follows:

	
     
  ፩) It converts source code into byte code with the help of Java Virtual Machine (JVM).
  
  ፪) Java compiler checks the syntaxial error (Syntax error).It also generates a list of all error messages when it finds errors 
  
  ፫) It also adds the additional code to your program if required also checks for assignments and reachability.
      
   #### N.B 
       -  A compiler does not detect logical errors in the program.

       -  It only creates an object code and does not execute the program
       
## Execution

JVM(Java Virtual Machine) acts as a run-time engine to run Java applications. JVM is the one that actually calls the main method present in a java code. JVM is a part of JRE(Java Runtime Environment).

Java applications are called WORA (Write Once Run Anywhere). This means a programmer can develop Java code on one system and can expect it to run on any other Java-enabled system without any adjustment. This is all possible because of JVM.
The compiler generates class files that are independent of the machine or the operating system, allowing them to operate on any system.
To run, the main class file (the class containing the function main) is handed to the JVM, which then travels through three major steps before executing the final machine code. 

![My Remote Image](https://www.guru99.com/images/java/052016_0614_WorkingofJa10.jpg)

      

