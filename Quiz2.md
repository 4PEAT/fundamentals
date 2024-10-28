

### **Data Types, Variables, Constants, Operators, Casting**

**1. Which of these can store the largest range of values?**  
   - A) `int`  
   - B) `short`  
   - C) `byte`  
   - D) `double`  

**2. What will be the result of the following operation: `10 / 4` in Java?**  
   - A) 2.5  
   - B) 2  
   - C) 2.0  
   - D) 3  

**3. Which of the following types can hold a single Unicode character?**  
   - A) `char`  
   - B) `byte`  
   - C) `short`  
   - D) `boolean`  

**4. In Java, what is the modulus operator `%` used for?**  
   - A) Division  
   - B) Addition  
   - C) Subtraction  
   - D) Remainder  

---

### **String Class**

**1. Which method can be used to compare two strings lexicographically in Java?**  
   - A) `compare()`  
   - B) `equals()`  
   - C) `compareTo()`  
   - D) `==`  

**2. What is the output of `"hello".toUpperCase()`?**  
   - A) `hello`  
   - B) `HELLO`  
   - C) `Hello`  
   - D) `hElLo`  

**3. Which method would you use to find the position of the first occurrence of a character in a string?**  
   - A) `charAt()`  
   - B) `substring()`  
   - C) `indexOf()`  
   - D) `contains()`  

**4. What does `"Java".concat("Programming")` return?**  
   - A) `Java Programming`  
   - B) `JavaProgramming`  
   - C) `Java`  
   - D) `ProgrammingJava`  

---

### **Conditional Statements, Visibility**

**1. What will `if ("test" == "test") { ... }` evaluate to?**  
   - A) True  
   - B) False  
   - C) An error  
   - D) It depends on memory allocation  

**2. Which access modifier makes a variable accessible to all classes in all packages?**  
   - A) `protected`  
   - B) `default`  
   - C) `public`  
   - D) `private`  

**3. What is the output of this code if `int y = 9; if (y != 10) { System.out.println("Not Ten"); } else { System.out.println("Ten"); }`?**  
   - A) "Ten"  
   - B) "Not Ten"  
   - C) An error  
   - D) No output  

---

### **Loops**

**1. Which keyword can be used to exit a loop early in Java?**  
   - A) `return`  
   - B) `continue`  
   - C) `break`  
   - D) `exit`  

**2. Which of the following will create an infinite loop?**  
   - A) `for (int i = 0; i < 10; i++)`  
   - B) `while (true)`  
   - C) `for (int i = 0; i >= 0; i--)`  
   - D) `for (int i = 0; i > -10; i++)`  

**3. What does the `continue` statement do in a loop?**  
   - A) Exits the loop  
   - B) Skips to the next iteration  
   - C) Ends the program  
   - D) Starts the loop over  

---

### **Arrays**

**1. Which method will return the length of an array named `arr`?**  
   - A) `arr.length()`  
   - B) `arr.size()`  
   - C) `arr.length`  
   - D) `arr.getLength()`  

**2. What will `int[] arr = {1, 2, 3, 4}; System.out.println(arr[4]);` print?**  
   - A) 4  
   - B) 3  
   - C) An error  
   - D) 0  

**3. How do you create a 2D array with 3 rows and 4 columns?**  
   - A) `int[][] arr = new int[3][4];`  
   - B) `int[][] arr = new int[4][3];`  
   - C) `int arr = new int[3][4];`  
   - D) `int[][] arr = int[3][4];`  

---

### **OOP (Class, Object, State, Behavior)**

**1. Which principle allows the same method name to have different behaviors in Java?**  
   - A) Encapsulation  
   - B) Abstraction  
   - C) Inheritance  
   - D) Polymorphism  

**2. What does the `this` keyword represent in a class?**  
   - A) The current method  
   - B) The superclass  
   - C) The current instance of the class  
   - D) The parent class  

**3. Which of the following best describes encapsulation?**  
   - A) Hiding the internal state and requiring all interactions to be performed through an object's methods  
   - B) Using methods from a superclass  
   - C) Allowing classes to have multiple forms  
   - D) Defining classes without specifying implementation details  

---

### **Fields, Methods, Constructors, Packages, Imports**

**1. Which of these statements is true about constructors?**  
   - A) Constructors must have a return type  
   - B) Constructors cannot be overloaded  
   - C) Constructors are called automatically when an object is created  
   - D) Constructors cannot be declared `public`  

**2. Which import statement is correct for importing only the `List` class from `java.util`?**  
   - A) `import java.util;`  
   - B) `import java.util.List;`  
   - C) `import List from java.util;`  
   - D) `import util.java.List;`  

---

### **Varargs**

**1. How do you declare a method that takes a variable number of `String` arguments?**  
   - A) `public void method(String varargs...)`  
   - B) `public void method(String... varargs)`  
   - C) `public void method(...String varargs)`  
   - D) `public void method(varargs... String)`  

**2. Which of the following correctly calls a method `display(String... values)`?**  
   - A) `display("Hello", "World");`  
   - B) `display(new String[] {"Hello", "World"});`  
   - C) `display("Hello");`  
   - D) All of the above  

---

### **Date, Time**

**1. Which method would you use to get the current date in Java 8?**  
   - A) `LocalDate.now()`  
   - B) `Date.now()`  
   - C) `Calendar.getInstance()`  
   - D) `Instant.now()`  

**2. Which class in Java 8 represents a time zone offset?**  
   - A) `ZoneId`  
   - B) `OffsetTime`  
   - C) `TimeZone`  
   - D) `ZoneOffset`  

---

### **Regular Expressions**

**1. What does the regular expression `\\w+` match?**  
   - A) One or more word characters (letters, digits, underscores)  
   - B) One or more whitespace characters  
   - C) Any digit  
   - D) Any punctuation  

**2. Which method in the `Matcher` class is used to find a pattern in a string?**  
   - A) `matches()`  
   - B) `find()`  
   - C) `group()`  
   - D) `pattern()`  

---

### **Static Fields, Methods, and Classes**

**1. Which of the following statements about a static field is correct?**  
   - A) It is created only once for all instances of a class  
   - B) It is created separately for each instance of the class  
   - C) It cannot be accessed from static methods  
   - D) It must be final  

**2. Which statement will call a static method `printMessage` from class `Printer`?**  
   - A) `Printer.printMessage();`  
   - B) `new Printer().printMessage();`  
   - C) `Printer().printMessage();`  
   - D) `printMessage();`  

