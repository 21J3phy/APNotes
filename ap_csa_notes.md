# AP CSA Exam Review Notes

_by Nirav + ChatGPT_

## Quick Overview

- **Multiple Choice**: 40 questions, 1 hour 30 minutes
- **Free Response**: 4 questions, 1 hour 30 minutes
- Focus on **tracing code**, especially with loops and arrays.
- **Write clean code** in FRQs! Comment if needed.
- Remember, **syntax matters**. If it doesn’t compile, it won’t run.

---

## Java Basics

### Variables

- Variables hold data.
- Data types: `int`, `double`, `boolean`, `String`.

```java
int a = 10;
double b = 3.14;
boolean isTrue = true;
String name = "Java";
```

### Operators

- Arithmetic: `+`, `-`, `*`, `/`, `%`
- Comparison: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Logical: `&&`, `||`, `!`
- Assignment: `=`

---

## Classes and Objects

### Constructor

- A constructor initializes objects.
- Must match the class name.

```java
public class Dog {
  private String name;

  public Dog(String n) {
    name = n;
  }
}
```

### Methods

- Methods define the behavior of an object.

```java
public void bark() {
  System.out.println("Woof!");
}
```

- `this` refers to the current object.

```java
public Dog(String name) {
  this.name = name;
}
```

### Creating Objects

```java
Dog dog = new Dog("Buddy");
```

---

## Loops and Conditionals

### if/else Statements

- Use for decision-making.

```java
if (x > 10) {
  System.out.println("Greater");
} else {
  System.out.println("Smaller or equal");
}
```

### for Loop

- Good for repeating tasks a set number of times.

```java
for (int i = 0; i < 5; i++) {
  System.out.println(i);
}
```

### while Loop

- Good for repeating until a condition is false.

```java
while (x < 5) {
  x++;
}
```

---

## Arrays and ArrayLists

### Arrays

- Store fixed-size lists of elements.

```java
int[] nums = {1, 2, 3};
nums[0] = 10;  // Modifying an array element
```

### ArrayLists

- Store dynamic-size lists.

```java
ArrayList<String> list = new ArrayList<>();
list.add("Hello");
list.get(0);  // Retrieves element at index 0
list.set(0, "Hi");
```

- Don’t forget to import `java.util.ArrayList;`

---

## Inheritance

### Extending a Class

- One class can inherit from another.

```java
public class Dog extends Animal {
  public void bark() {
    System.out.println("Woof!");
  }
}
```

- `super()` is used to call the parent class's constructor or methods.

---

## Important Methods to Remember

- ArrayList Methods: `add()`, `get()`, `set()`, `remove()`, `size()`
- Array Traversal: Loop through with `for` or `for-each`.

```java
for (int i = 0; i < arr.length; i++) {
  System.out.println(arr[i]);
}
```
