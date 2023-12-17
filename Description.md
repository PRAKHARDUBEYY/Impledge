
## Compound Word Finder

### Overview:

This C++ program is designed to find the longest and second-longest compounded words in a list of input files. A word is considered compounded if it can be formed by concatenating two or more shorter words found in the same file. The program employs a trie data structure to efficiently check whether a word is compounded.

### Steps to Execute:

1.  **Compile the Code:**
    
    -   Ensure you have a C++ compiler installed.
    -   Compile the code using a command like `g++ -o compound_word_finder main.cpp`.
2.  **Run the Executable:**
    
    -   Execute the compiled program by running `./compound_word_finder`.
3.  **Review Results:**
    
    -   The program will process each input file and display the longest and second-longest compounded words, along with the time taken for each file.

### Design Decisions and Approach:

-   **Trie Data Structure:**
    
    -   To optimize the check for compounded words, a trie data structure is used. This reduces the time complexity of checking whether a word is compounded, improving the overall efficiency of the program.
-   **Sorting:**
    
    -   Words are sorted in descending order of length, with lexicographical order as a tiebreaker. This ensures that longer words are considered first during the search for compounded words.
-   **Timing and Target Time:**
    
    -   The program measures the time taken to process each file and waits until the elapsed time matches a target time. This ensures a minimum processing time and allows for consistent performance evaluation.
-   **Error Handling:**
    
    -   The code includes error handling for file opening, providing informative error messages if a file cannot be opened.

### Notes:

-   Ensure that input files are correctly formatted, with one word per line.
-   The program outputs the results for each input file, including the longest and second-longest compounded words and the time taken for processing.

This program is designed to efficiently find compounded words in a set of input files, utilizing trie structures and sorting for optimization. The provided steps guide the user through the process of compiling and executing the program.
