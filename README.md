Brain Academy
============= 
#Java Core Course

##Laboratory Work 2.10
###Theme: Wrapper classes

####Laboratory Work 2.11.1.

Goal: Practice Exception Handling mechanism.

Objectives:

1. Create new project called TestException.
   Add package “com.brainacad.oop.testexcp1”.
2. Create a class Main with a main() that throws
   an object of class Exception inside a try
   block. Give the constructor for Exception
   a String argument.
3. Catch the exception inside a catch clause and
   print the String argument.
4. Add a finally clause and print a message
   to prove you were there.
5. Execute the program.

Here is the solution:
```java
public class Main {

    public static void main(String[] args) {
        labWork_2_10_Solution();
    }

    private static void labWork_2_10_Solution() {
        /*----- Objective 2 -----*/
        try {
            throw new Exception("object of class Exception trowed manually!");
        /*----- Objective 3 -----*/
        } catch(Exception e) {
            System.out.println(e.getMessage());
        /*----- Objective 4 -----*/
        } finally {
            System.out.println("We are in the finally block!");
        }
    }
}
```