# File Handling in Python

This project demonstrates **basic file handling operations in Python**, including creating, reading, writing, appending, and handling missing file errors.

---

##  **Task 1: Read a File and Handle Errors**

###  **Description**

This program creates a text file named **`sample.txt`**, writes a few lines into it, and then reads and prints its content line by line.
If the file does not exist, it displays an appropriate error message.

###  **Concepts Used**

* File creation using **write (`'w'`) mode**
* Reading a file using **read (`'r'`) mode**
* Exception handling using **`try–except`**
* Looping through file content line by line


###  **Sample Output**

```
Reading file content:
Line 1: This is a sample text file.
Line 2: It contains multiple lines.
```

###  **Error Handling Example**

If `sample.txt` is deleted or missing:

```
Error: The file 'sample.txt' was not found.
```

---

##  **Task 2: Write and Append Data to a File**

###  **Description**

This program allows the user to:

1. Enter text to be **written** into a file named `output.txt`.
2. Enter additional text to be **appended** to the same file.
3. Finally, it **reads and displays** the complete content of the file.

###  **Concepts Used**

* Writing to a file using `'w'` mode
* Appending to a file using `'a'` mode
* Reading file content using `'r'` mode
* User input handling


###  **Sample Run**

```
Enter text to write to the file: Hello, Python!
Data successfully written to output.txt.

Enter additional text to append: Learning file handling in Python.
Data successfully appended.

Final content of output.txt:
Hello, Python!
Learning file handling in Python.
```

---

## **Key Takeaways**

* `'w'` → Write mode (creates or overwrites a file)
* `'a'` → Append mode (adds data without erasing existing content)
* `'r'` → Read mode (reads data from an existing file)
* `try-except` → Used to handle missing files or runtime errors gracefully
