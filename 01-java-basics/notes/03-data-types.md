# Java Data Types

## 1. Overview

In Java, **data types** define the type of data that a variable can store. They determine the **size of memory**, the **range of values**, and the **operations** that can be performed on the variable.

Java is a **strongly typed language**, meaning that every variable must be declared with a specific data type before it can be used.

Example:

```java
int age = 20;
double salary = 1500.75;
char grade = 'A';
boolean isStudent = true;
```

---

# 2. Why Data Types Are Important

Data types help the Java compiler to:

- Allocate the correct amount of memory
- Prevent invalid operations
- Improve code readability
- Ensure type safety

Example:

```java
int number = 10;
double price = 12.5;
char letter = 'G';
boolean isActive = true;
```

---

# 3. Classification of Java Data Types

Java data types are divided into two main categories.

```
Java Data Types
│
├── Primitive Data Types
│
└── Non-Primitive Data Types
```

| Category | Description | Examples |
|--------|-------------|----------|
| Primitive | Built-in types that store simple values | int, double, char, boolean |
| Non-Primitive | Reference types that store object references | String, Array, Class |

---

# 4. Primitive Data Types

Primitive data types are **basic data types provided by Java**. They store **single values** and are not objects.

Java defines **8 primitive data types**.

## Primitive Type Categories

| Category | Data Types |
|--------|------------|
| Integer | byte, short, int, long |
| Floating Point | float, double |
| Character | char |
| Boolean | boolean |

---

# 5. Integer Data Types

Integer types are used to store **whole numbers (positive and negative)**.

| Type | Size | Range | Default Value | Example |
|-----|------|------|---------------|--------|
| byte | 8-bit | -128 to 127 | 0 | `byte b = 100;` |
| short | 16-bit | -32,768 to 32,767 | 0 | `short s = 20000;` |
| int | 32-bit | -2³¹ to 2³¹ − 1 | 0 | `int i = 50000;` |
| long | 64-bit | -2⁶³ to 2⁶³ − 1 | 0L | `long l = 9000000000L;` |

### Example

```java
public class IntegerExample {

    public static void main(String[] args) {

        byte b = 120;
        short s = 20000;
        int i = 500000;
        long l = 9000000000L;

        System.out.println(b);
        System.out.println(s);
        System.out.println(i);
        System.out.println(l);
    }
}
```

---

# 6. Floating Point Data Types

Floating point types are used to store **decimal numbers**.

| Type | Size | Precision | Default Value | Example |
|-----|------|-----------|---------------|--------|
| float | 32-bit | Single precision | 0.0f | `float f = 3.14f;` |
| double | 64-bit | Double precision | 0.0d | `double d = 3.14159;` |

### Example

```java
public class FloatExample {

    public static void main(String[] args) {

        float price = 10.5f;
        double salary = 12345.678;

        System.out.println(price);
        System.out.println(salary);
    }
}
```

---

# 7. Character Data Type

The **char** data type stores a **single Unicode character**.

Java uses the **Unicode system**, which allows representation of characters from many languages.

| Type | Size | Range | Example |
|-----|------|------|--------|
| char | 16-bit | '\u0000' to '\uffff' | `char letter = 'A';` |

### Example

```java
public class CharExample {

    public static void main(String[] args) {

        char letter = 'G';

        System.out.println(letter);
    }
}
```

---

# 8. Boolean Data Type

The **boolean** data type represents logical values.

| Type | Possible Values | Example |
|-----|-----------------|--------|
| boolean | true / false | `boolean isLogin = true;` |

### Example

```java
public class BooleanExample {

    public static void main(String[] args) {

        boolean isJavaFun = true;

        if(isJavaFun){
            System.out.println("Java is fun!");
        }
    }
}
```

---

# 9. Summary of Primitive Data Types

| Data Type | Size | Default Value | Description |
|----------|------|---------------|-------------|
| byte | 8-bit | 0 | Small integer values |
| short | 16-bit | 0 | Medium integer values |
| int | 32-bit | 0 | Most commonly used integer type |
| long | 64-bit | 0L | Large integer values |
| float | 32-bit | 0.0f | Single precision decimal |
| double | 64-bit | 0.0d | Double precision decimal |
| char | 16-bit | '\u0000' | Unicode character |
| boolean | JVM dependent | false | True or false value |

---

# 10. Non-Primitive Data Types

Non-primitive data types are also called **reference types**. They store references to objects rather than actual values.

Examples include:

- String
- Array
- Class
- Interface
- Object

### Example

```java
public class NonPrimitiveExample {

    public static void main(String[] args) {

        String name = "Giang";

        int[] numbers = {1,2,3,4,5};

        System.out.println(name);
        System.out.println(numbers[0]);
    }
}
```

---

# 11. Primitive vs Non-Primitive

| Feature | Primitive | Non-Primitive |
|-------|-----------|--------------|
| Storage | Stores actual value | Stores reference |
| Memory | Usually smaller | Usually larger |
| Methods | No methods | Can have methods |
| Examples | int, char, boolean | String, Array |

---

# 12. Best Practices When Using Data Types

When writing Java programs, follow these guidelines:

- Use **int** for most integer values
- Use **long** for very large numbers
- Use **double** for decimal numbers
- Use **boolean** for true/false conditions
- Use **char** for single characters
- Use **String** for text data

Example:

```java
String name = "John";
int age = 25;
double salary = 3000.50;
boolean isEmployee = true;
```

---

# 13. Conclusion

Java provides a rich set of **data types** that allow developers to store and manipulate different kinds of data efficiently.

Understanding Java data types is essential because they:

- Improve program performance
- Ensure type safety
- Help write cleaner and more maintainable code

Mastering data types is one of the **first steps in learning Java programming**.
