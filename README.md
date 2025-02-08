# Groovy Null-Safe Operator Unexpected Behavior with Strings

This repository demonstrates an uncommon issue in Groovy related to the null-safe operator.  When a `null` value is passed to a method expecting a `String`, the null-safe behavior might not throw a `NullPointerException` as expected in other languages like Java. This can lead to unexpected behavior where instead of an exception, you get an empty string or other default value.

The `bug.groovy` file contains a simple method that showcases this issue.  The `bugSolution.groovy` file provides a solution to handle null values more explicitly.

This example highlights the importance of understanding Groovy's dynamic typing and null-safe operator behavior to prevent unexpected issues in your code.