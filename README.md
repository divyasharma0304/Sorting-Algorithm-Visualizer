## Sorting Algorithm Visualizer

This project is a C++ program using the SDL2 library to visualize how various sorting algorithms work.

**1. Introduction**

Sorting algorithms arrange elements in a specific order. This program focuses on common algorithms like Insertion Sort, Merge Sort, Quick Sort, and Heap Sort. It can sort a list of 130 elements and randomize them before sorting.

**Visualization Note:** The sorting speed may not perfectly reflect real-world time complexities. Faster algorithms (like Merge Sort) are slowed down for better visualization.

**2. Requirements**

* C++ compiler (supporting C++17)
* SDL2 library

**3. Running the Program**

**Option 1: Pre-built executable**

1. Download and extract the files from the zip folder.
2. Run the `main_final.exe` file directly.

**Option 2: Compiling from source**

1. Install and set up the SDL2 library following this tutorial (up to Step 2 only): [https://www.matsson.com/prog/sdl2-mingw-w64-tutorial.php](https://www.matsson.com/prog/sdl2-mingw-w64-tutorial.php)
2. Open Command Prompt in the directory containing `main_final.cpp`.
3. Paste and run this command (replace paths if necessary):

```
g++ -std=c++17 main_final.cpp -IC:\Project\SDL2\include -LC:\Project\SDL2\lib -Wall -lmingw32 -lSDL2main -lSDL2 -o main_final
```

This creates an executable `main_final.exe`. Run it to start the program.

**4. Available Sorting Algorithms**

* Quick Sort
* Heap Sort
* Insertion Sort
* Merge Sort

**5. Controls**

* `0`: Generate a new randomized list.
* `1`: Start Insertion Sort.
* `2`: Start Merge Sort. (Typo: The readme says Bubble Sort here, which is not listed in available algorithms)
* `3`: Start Heap Sort.
* `4`: Start Quick Sort.
* `5`: (No functionality mentioned for 5)
* `6`: (No functionality mentioned for 6)
* `q`: Exit the program.

**6. Uses and Applications**

* **Educational purposes:** Visualize sorting algorithms to understand their behavior.
* **Research purposes:** Study sorting algorithm performance under different conditions.
* **Development purposes:** Use as a starting point for sorting-based applications (databases, data analysis, machine learning).
* **Benchmarking purposes:** Compare sorting algorithm performance across platforms and hardware.
* **Fun and entertainment:** Learn and explore sorting algorithms in an engaging way.

**7. Made by:**

* Divya Sharma
* Kushagra Pandey
