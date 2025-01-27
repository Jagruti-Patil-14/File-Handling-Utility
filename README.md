# File-Handling-Utility
Company: Codtech It Solutions
Name:Jagruti Patil
Intern ID:CTO81JC
Domain:Java Programming
Duration:4 weeks
Mentor:Neela Santosh
Description:File handling is an essential part of software development that enables applications to interact with data stored in files. Java, as a robust programming language, provides extensive support for file handling through classes in the java.io and java.nio packages. This utility demonstrates how to create a Java program to perform three key operations: reading, writing, and modifying text files. Let’s delve into the details of each operation and how they are implemented in Java.
1. Reading a Text File
Reading a text file involves fetching and displaying its content. In Java, this is typically achieved using classes such as FileReader, BufferedReader, or Files from the java.nio.file package.
Here’s how it works:
FileReader: Reads the file character by character, making it suitable for simple text files.
BufferedReader: Wraps FileReader to provide efficient line-by-line reading.
2. Writing to a Text File
Writing data to a text file creates or overwrites its contents. Java provides classes like FileWriter and BufferedWriter to accomplish this task:
FileWriter: Writes characters to a file, allowing you to append or overwrite content.
BufferedWriter: Wraps FileWriter for efficient writing of large amounts of text.
3. Modifying a Text File
Modifying a file generally involves reading its content, making changes in memory, and writing the updated content back. Java doesn’t allow direct modification of file content, but this can be achieved through temporary files or string manipulation.
This file handling utility demonstrates how Java provides a structured approach to reading, writing, and modifying text files. By leveraging classes like FileReader, BufferedReader, FileWriter, and BufferedWriter, developers can efficiently handle text files. These operations are foundational for various applications, from simple logging systems to complex data processing tools. With modern enhancements in the java.nio package, Java further simplifies file handling, making it more intuitive and efficient.

