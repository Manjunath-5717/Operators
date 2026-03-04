# Builtop – Java Math Built-in Methods Program

## Description

This Java program demonstrates the usage of important built-in methods from the `Math` class such as:

* Math.abs()
* Math.ceil()
* Math.floor()
* Math.max()
* Math.min()
* Math.random()

It also generates a random number between 10 and 100.

---

## Program Code

```java
public class Builtop {

    public static void main(String[] args) {

        double d = -20.20;

        System.out.println("math.abs " + Math.abs(d));
        double e = Math.abs(d);

        System.out.println("math.ceil " + Math.ceil(e));
        System.out.println("math.floor " + Math.floor(e));
        System.out.println("math.max " + Math.max(2, 3));
        System.out.println("math.min " + Math.min(2, 3));

        System.out.println("math.random " + Math.random());

        int random = (int) (10 + Math.random() * 91);
        System.out.println("Random number between 10 and 100: " + random);
    }
}
```

---

## Requirements

* Java JDK 8 or higher

---

## How to Compile and Run

```bash
javac Builtop.java
java Builtop
```

---

## Sample Output

```
math.abs 20.2
math.ceil 21.0
math.floor 20.0
math.max 3
math.min 2
math.random 0.456732
Random number between 10 and 100: 67
```

Note: Random values will be different each time.
