# Java String Methods for DSA

A quick reference of the most useful `String` methods used in Data
Structures & Algorithms.

## Creating Strings

``` java
String s = "hello";
String str = new String("hello");
```

------------------------------------------------------------------------

## Length

  Method       Example              Output
  ------------ -------------------- --------
  `length()`   `"hello".length()`   `5`

------------------------------------------------------------------------

## Access Characters

  Method                Example
  --------------------- -----------------------
  `charAt(int index)`   `s.charAt(2)` → `'l'`

------------------------------------------------------------------------

## Substrings

  Method                    Example
  ------------------------- --------------------
  `substring(start)`        `s.substring(2)`
  `substring(start, end)`   `s.substring(1,4)`

------------------------------------------------------------------------

## Searching

  Method            Example
  ----------------- ----------------------
  `contains()`      `s.contains("ell")`
  `indexOf()`       `s.indexOf('l')`
  `lastIndexOf()`   `s.lastIndexOf('l')`
  `startsWith()`    `s.startsWith("he")`
  `endsWith()`      `s.endsWith("lo")`

------------------------------------------------------------------------

## Comparison

  Method                    Example
  ------------------------- ----------------------------
  `equals()`                `a.equals(b)`
  `equalsIgnoreCase()`      `a.equalsIgnoreCase(b)`
  `compareTo()`             `a.compareTo(b)`
  `compareToIgnoreCase()`   `a.compareToIgnoreCase(b)`

------------------------------------------------------------------------

## Case Conversion

  Method
  -----------------
  `toUpperCase()`
  `toLowerCase()`

------------------------------------------------------------------------

## Replace

  Method             Example
  ------------------ ----------------------
  `replace()`        `s.replace('a','b')`
  `replaceAll()`     Uses regex
  `replaceFirst()`   Uses regex

------------------------------------------------------------------------

## Split & Join

  Method            Example
  ----------------- -------------------------
  `split()`         `s.split(",")`
  `String.join()`   `String.join("-", arr)`

------------------------------------------------------------------------

## Trimming

  Method
  ------------------------
  `trim()`
  `strip()` *(Java 11+)*

------------------------------------------------------------------------

## Conversion

  Method
  --------------------
  `toCharArray()`
  `getBytes()`
  `String.valueOf()`

------------------------------------------------------------------------

## Matching

  Method
  -----------------------
  `matches()` *(Regex)*

------------------------------------------------------------------------

## Empty & Blank

  Method
  --------------------------
  `isEmpty()`
  `isBlank()` *(Java 11+)*

------------------------------------------------------------------------

## Concatenation

  Method
  --------------
  `concat()`
  `+` operator

------------------------------------------------------------------------

## Repetition

  Method
  ------------------------------
  `repeat(int n)` *(Java 11+)*

------------------------------------------------------------------------

## Useful Static Methods

  Method
  --------------------
  `String.valueOf()`
  `String.format()`
  `String.join()`

------------------------------------------------------------------------

# Frequently Used in DSA

-   `length()`
-   `charAt()`
-   `substring()`
-   `contains()`
-   `indexOf()`
-   `lastIndexOf()`
-   `startsWith()`
-   `endsWith()`
-   `equals()`
-   `compareTo()`
-   `toCharArray()`
-   `split()`
-   `replace()`
-   `String.valueOf()`

------------------------------------------------------------------------

# Time Complexity

  Method            Complexity
  ----------------- ------------
  `length()`        O(1)
  `charAt()`        O(1)
  `substring()`     O(n)
  `contains()`      O(n × m)
  `indexOf()`       O(n)
  `lastIndexOf()`   O(n)
  `startsWith()`    O(m)
  `endsWith()`      O(m)
  `equals()`        O(n)
  `compareTo()`     O(n)
  `replace()`       O(n)
  `split()`         O(n)
  `toCharArray()`   O(n)
  `concat()`        O(n)

------------------------------------------------------------------------

## Interview Tips

-   Strings are **immutable**.
-   Use **StringBuilder** for frequent modifications.
-   Convert to `char[]` when many character updates are needed.
-   `contains()` internally searches for a substring.
-   `compareTo()` is used for lexicographical ordering.
