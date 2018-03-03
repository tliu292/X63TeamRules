
# X-Team 63 Style Guide
Stick to normal conventions of naming methods and classes, and keep it constant in each file. 

## Naming conventions
For interface, class, and exception, the first letter of every phrase should be in uppercase and the remaining letters in lowercase, or written in UpperCaseClass conventions.
For methods, parameters, and local variables, the first phrase should all be lowercase and the first letter of the remaining phrases should be uppercase. For other letters of the remaining phrases, it should be in lowercase. For example, it should be written in oneMethod() conventions.
For all constants including instance constants and class constants, all letters should be in uppercase. Underscores instead of white spaces should be utilized.

### Examples
* interfaces: 
  public interface SearchTreeADT {...}
* classes:
  public class BalancedSearchTree {...}
* exception types:
  IllegalArgumentException, NullPointerException, DuplicateKeyException
* fields:
  private int numberOfStudents;
* methods:
  public void deleteStudent() {...}
* parameters:
  public void deleteStudent(int index) {...}
* local variables:
  String studentName = "Isabella";
* instance constants:
  final int STUDENT_ID = 100;
* class constants:
  private final int STUDENT_ID = 100;
  
## Commenting style for public and private members of a class or interface:
Use Javadoc for every class interface and the methods inside each of those classes and interfaces.
Use in line commenting "//" or "/*/" for longer comments for fields, complex code, or variables.

### Examples

* classes
```java
  /*
  * Implement all the functions of BalancedSearchTree
  */
  ```
* fields
```java
  //Number of total students
  ```
* constructors
```java
  /*
  * Constructor for BalancedSearchTree with parameters for item value and student names
  */
  ```
* methods
```java
  /*
  * Implements the delete function for BalancedSearchTree 
  */
  ```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  ```java
      if(...) {
      }
  ```
  * switch statement
  ```java
      switch() {
        case 1: studentString = "Ben";
                break;
        case 2: studentString = "Abby";
                break;
      }
  ```
  * while loops
  ```java
      while(...) {
      }
  ```
  * for loops
  ```java
      for (int i = 0; i < count; i++) {
      }
  ```
  * enhanced for loops
  ```java
      for (String name : students){
      }
  ```
