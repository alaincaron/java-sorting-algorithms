# java-sorting-algorithms
Implementations of sorting algorithms using Java.

[![Build Status](https://travis-ci.org/marioluan/java-sorting-algorithms.svg?branch=master)](https://travis-ci.org/marioluan/java-sorting-algorithms)
[![Coverage Status](https://coveralls.io/repos/github/marioluan/java-sorting-algorithms/badge.svg?branch=master)](https://coveralls.io/github/marioluan/java-sorting-algorithms?branch=master)
[![Dependency Status](https://www.versioneye.com/user/projects/58858fedb194d4003d528a95/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/58858fedb194d4003d528a95)

--

**Pre-requisites:**
- java (v1.8)
- gradle (v3.3)

## Code style & formatter (eclipse users only)
Import the files [code-style.xml](code-style.xml) and [formatter.xml](formatter.xml) into your IDE.

## Test
```bash
gradle clean coberturaCheck check
# Test summary will be located at `build/reports/tests/test/index.html`
# Coverage report will be located at `build/reports/cobertura/index.html`.
# Code style issues report will be located at `build/reports/checkstyle/main.html`
```

## Build
```bash
gradle clean assemble
```

## Available algorithms
- [Insertion Sort](https://github.com/marioluan/java-sorting-algorithms/blob/master/src/main/java/io/github/marioluan/algorithms/sorting/InsertionSort.java)
- [Selection Sort](https://github.com/marioluan/java-sorting-algorithms/blob/master/src/main/java/io/github/marioluan/algorithms/sorting/SelectionSort.java)
- [Shellsort](https://github.com/marioluan/java-sorting-algorithms/blob/master/src/main/java/io/github/marioluan/algorithms/sorting/ShellSort.java)
- Merge Sort  
-- [Recursive](https://github.com/marioluan/java-sorting-algorithms/blob/master/src/main/java/io/github/marioluan/algorithms/sorting/MergeSortRecursive.java)  
-- [Iterative](https://github.com/marioluan/java-sorting-algorithms/blob/master/src/main/java/io/github/marioluan/algorithms/sorting/MergeSortIterative.java)

## References
- [https://www.coursera.org/learn/algorithms-part1](https://www.coursera.org/learn/algorithms-part1)
