
## About
The `aim` of this projct is creating a function called `get_next_line()` in which when it's called in a loop, it'll read the text within the file descriptor `one line at a time` until the end of the file.

1) The function works both when reading a file and when reading from the `standard input`
2) The project return value is the `line that was read`. However, if there is nothing else to read or if an error occurred, it `returns NULL`.
3) The returned line includes the terminating \n character except if the end of file was reached and does not end with a \n character.


The project directory contains two executables `Mandatory` & `Bonus`, the first is to read from one file descriptors and the second one is to read from multiple file descriptors.

The purpose of this project was learning deeply about open(), read(), close(), static variables and file descriptors.

In this project learning about the buffer and finding the solution to make my function read any amount of text corectly without messing up any character from a file descriptor or from the standard output was challenging. Learning about the functions open(), read() and close() contributed in finding the right path to find the best solution.
