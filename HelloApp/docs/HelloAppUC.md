# HelloApp Use Cases

## UC1 – Display Hello World

### Description
The application prints "Hello World" in the console to verify that the Java program runs successfully.

### Disadvantages of Previous Use Case
None, because this is the first use case.

### Preconditions
- Java must be installed
- HelloApp.java file must exist

### Main Flow
1. User runs the program.
2. The program starts execution.
3. The console prints "Hello World".

### Post Conditions
The console displays:

Hello World

### Hints
Use `System.out.println()` to print output in Java.

### Code Example

```java
public class HelloApp {

    public static void main(String[] args) {

        System.out.println("Hello World");

    }

}