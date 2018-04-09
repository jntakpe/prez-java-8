## Lambda Declaration
* Declaring the types of the parameters is optional
* Using parentheses around the parameter is optional if you have only one parameter

```java
() -> System.out.println(this)
str -> System.out.println(str)
(String str) -> System.out.println(str)
```

* Using curly braces is optional (unless you need multiple statements)
* The **return** keyword is optional if you have a single expression that returns a value

```java
(s1, s2) -> s2.length() - s1.length()
(String s1, String s2) -> { return s2.length() - s1.length(); }
```