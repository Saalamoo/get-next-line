# get_next_line

## 📌 About

The goal of this project is to implement a function called `get_next_line()` that reads and returns one line at a time from a given file descriptor. Each call to the function reads the next line until the end of the file is reached.

- The function supports reading from both files and standard input.
- It returns the next line, including the trailing newline character (`\n`), unless the line is the last one in the file and doesn't end with a newline.
- If there is nothing more to read or if an error occurs, it returns `NULL`.

The project is divided into two parts:
- **Mandatory**: Handles reading from a single file descriptor.
- **Bonus**: Adds support for reading from multiple file descriptors simultaneously.

This project was a deep dive into system-level file operations using `open()`, `read()`, and `close()`, as well as managing static variables and handling buffers correctly. One of the main challenges was ensuring the function could handle any buffer size and read input without losing or misplacing characters. Overcoming these challenges helped solidify my understanding of low-level I/O operations in C.

## ⚙️ Usage

To compile and test the project:

```bash
make
./mandatory < your_file.txt
