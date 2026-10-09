# Java Collections — Advanced Programming Assignment 3

DTU advanced programming coursework implementing list structures, sorting and JavaFX-based demonstrations.

## What the repository contains

| Component | Source | Topic |
|---|---|---|
| List interfaces | [`lists/types`](src/main/java/dk/dtu/compute/course02324/assignment3/lists/types) | List and sorted-list contracts |
| Array-based lists | [`ArrayList.java`](src/main/java/dk/dtu/compute/course02324/assignment3/lists/implementations/ArrayList.java) | List implementation |
| Sorted lists | [`SortedArrayList.java`](src/main/java/dk/dtu/compute/course02324/assignment3/lists/implementations/SortedArrayList.java) | Ordered elements |
| Sorting | [`BubbleSort.java`](src/main/java/dk/dtu/compute/course02324/assignment3/lists/implementations/BubbleSort.java) | Elementary sorting algorithm |
| GUI | [`PersonsGUI.java`](src/main/java/dk/dtu/compute/course02324/assignment3/lists/uses/PersonsGUI.java) | JavaFX interface |

The source also includes a generic comparator, person model and example application.

## Tests

The repository contains tests for basic and sorted list implementations:

- [TestArrayLists](src/test/java/dk/dtu/compute/course02324/assignment3/lists/TestArrayLists.java)
- [TestSortedArrayLists](src/test/java/dk/dtu/compute/course02324/assignment3/lists/TestSortedArrayLists.java)
- [TestForAllLists](src/test/java/dk/dtu/compute/course02324/assignment3/lists/TestForAllLists.java)

## Requirements and build

The checked-in [Maven configuration](pom.xml) specifies **JDK 25**, JavaFX and JUnit 4.13.2.

```bash
mvn test
```

This is a coursework implementation rather than a published reusable Java collections library. Read the source and tests to assess functionality; this README does not claim that the tests were executed in CI.
