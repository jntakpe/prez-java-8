## Reduction sum

```java
Integer totalAgeReduce = population.stream()
   .map(Person::getAge)
   .reduce(0, (a, b) -> a + b);
```

```java
Integer totalAge = population.stream()
   .mapToInt(Person::getAge)
   .sum();
```