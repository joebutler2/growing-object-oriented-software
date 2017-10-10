Code examples in this book use Java with jUnit 4, hamcrest, and jMock 2.

Hamcrest provides static factory methods so you don't have to instantiate them
directly. This makes the code more readable.

So instead of:
```java
String s = "we have no bananas today";
Matcher<String> containsBananas = new StringContains("bananas");
assertTrue(containsBananas.matches(s));
```

You can use:
```java
assertTrue(containsString("bananas").matches(s));
```


