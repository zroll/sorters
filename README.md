# my-java-project

This is a simple Java project that contains a class `Sorters` in the package `io.mindit.ai`. The `Sorters` class exposes three methods: `quickSort`, `mergeSort`, and `bubbleSort`. Each method implements the corresponding sorting algorithm.

## Setup

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. If you have Maven installed, you can build the project using the command `mvn clean install`.

## Usage

You can use the `Sorters` class in your code to sort arrays using the quick sort, merge sort, or bubble sort algorithms. Here is an example:

```java
import io.mindit.ai.Sorters;

public class Main {
    public static void main(String[] args) {
        int[] array = {5, 3, 8, 1, 2};
        Sorters.quickSort(array, 0, array.length - 1);
        // array is now sorted
    }
}
```

Replace `quickSort` with `mergeSort` or `bubbleSort` to use a different sorting algorithm.