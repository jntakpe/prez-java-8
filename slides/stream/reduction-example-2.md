## Reduction boolean

````java
boolean atLeastOneKnowsJava = team.stream()
                .map(d -> d.getLanguages())
                .flatMap(l -> l.stream())
                .anyMatch(l -> "java".equals(l));
````