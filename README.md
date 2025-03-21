# custom-search-engine

# Custom Search Engine in C++

This project implements a **Custom Search Engine** in C++ that allows users to search for keywords across multiple documents. It includes various key concepts such as file handling, web crawling, inverted index creation, ranking algorithms, and much more. The project focuses on fundamental and advanced topics in C++ programming.

## Objective
The goal of this project is to create a basic search engine that indexes documents and allows the user to perform keyword searches. This project will help you understand essential C++ concepts, web crawling, string manipulation, inverted indexing, and more.

---

## Steps and Topics Covered

### 1. **C++ Programming Basics**
   **Objective**: Learn the fundamentals of C++ programming.
   - Variables, Data Types, and Operators
   - Control Flow (if, else, switch)
   - Loops (for, while, do-while)
   - Functions (arguments, return types)
   - Object-Oriented Programming (OOP): Classes, Objects, and Methods

### 2. **File Handling in C++**
   **Objective**: Learn how to read from and write to files in C++.
   - File I/O using `ifstream` and `ofstream`
   - File Opening, Closing, and Error Handling
   - Reading/Writing Text and Binary Files

### 3. **Basic Data Structures in C++**
   **Objective**: Learn how to use and manipulate common data structures in C++.
   - Arrays and Vectors
   - `unordered_map` (hash maps) for key-value storage
   - Strings in C++ and String Manipulation (like `stringstream`)

### 4. **Web Crawling with libcurl**
   **Objective**: Learn how to fetch web pages using `libcurl`.
   - Setting up and installing `libcurl`
   - Sending HTTP Requests (GET, POST)
   - Handling HTTP Responses
   - Extracting raw HTML content

### 5. **HTML Parsing**
   **Objective**: Learn how to extract information from HTML content.
   - Introduction to HTML structure and tags
   - Parsing HTML using simple string manipulation or libraries like **Gumbo**
   - Extracting meaningful content like text, titles, and body sections

### 6. **String Manipulation and Tokenization**
   **Objective**: Learn how to split and process strings into usable data.
   - Splitting strings by delimiters (spaces, punctuation)
   - Tokenizing using `stringstream`
   - String functions for manipulation (e.g., `substr`, `find`, `replace`)

### 7. **Inverted Index Creation**
   **Objective**: Learn how to create an inverted index to map words to documents.
   - Concept of Inverted Index
   - Storing words and their document IDs in an `unordered_map`
   - Efficient indexing techniques

### 8. **Basic Keyword Search**
   **Objective**: Learn how to search for keywords in an index.
   - Searching an inverted index
   - Retrieving documents that contain the search word
   - Basic string matching techniques

### 9. **Ranking Algorithm (TF-IDF)**
   **Objective**: Learn the Term Frequency-Inverse Document Frequency (TF-IDF) ranking method.
   - Concept of TF and IDF
   - Calculating TF-IDF for words in documents
   - Sorting documents based on relevance

### 10. **Sorting and Displaying Results**
   **Objective**: Learn how to sort and display search results.
   - Sorting algorithms (e.g., `sort()`, `quick sort`)
   - Displaying results by ranking or relevance
   - Formatting search results for clarity

### 11. **Command-Line Interface (CLI) Development**
   **Objective**: Learn how to create a simple CLI for your search engine.
   - Accepting user input from the command line
   - Displaying search results on the console
   - Implementing basic user prompts for interaction

### 12. **Performance Optimization**
   **Objective**: Learn how to improve the speed of your search engine.
   - Caching frequently searched terms or results
   - Optimizing data structures for faster search times
   - Using multi-threading for parallel processing

### 13. **Testing and Debugging**
   **Objective**: Learn how to test and debug your search engine.
   - Debugging using `gdb` or IDE debuggers
   - Unit testing your C++ code with Google Test
   - Handling edge cases like no search results, empty documents, etc.

### 14. **Documentation**
   **Objective**: Learn how to document your code and project.
   - Writing comments in code to explain functionality
   - Writing a `README.md` file for your project
   - Using Doxygen for automatic documentation generation

---

## Project Structure

- **src/**: Contains the main source code files for the search engine.
- **data/**: A folder where documents to be indexed are stored.
- **include/**: Contains header files for various components (e.g., indexing, crawling).
- **docs/**: Project documentation, including reports and notes.

## Installation

To build and run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CustomSearchEngine.git
