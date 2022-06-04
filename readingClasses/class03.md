# class03
One of the most common tasks that you can do with Python is reading and writing files.

We use the command open() to open a file and close() to close it, and we should always close the file after we finish editing it.

There is another argument in the built in function. This argument is a string that contains multiple characters to represent how you want to open the file. The default and most common is 'r', which represents opening the file in read-only mode as a text file.

'r'	Open for reading (default)
'w'	Open for writing, truncating (overwriting) the file first
'rb' or 'wb'	Open in binary mode (read/write using byte data)
There are multiple methods that can be called on a file object to help us out :

|Method|What It Does|
|------|------------|
|.read(size=-1)|This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.|
|.readline(size=-1)|	This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.|
|.readlines()|This reads the remaining lines from the file object and returns them as a list.|

We also can append to a file by using the string 'a' in the second argument.

-----------------------------------------------------------------------

Exceptions
A Python program terminates as soon as it encounters an error. In Python, an error can be a syntax error or an exception.

This time, you ran into an exception error. This type of error occurs whenever syntactically correct Python code results in an error. The last line of the message indicated what type of exception error you ran into.

Instead of showing the message exception error, Python details what type of exception error was encountered.

raise allows you to throw an exception at any time.
assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
In the try clause, all statements are executed until an exception is encountered.
except is used to catch and handle the exception(s) that are encountered in the try clause.
else lets you code sections that should run only when no exceptions are encountered in the try clause.
finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.
