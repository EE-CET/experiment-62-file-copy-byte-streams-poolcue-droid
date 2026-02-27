[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/if_a9KOo)
# Experiment 62: File Copy (Byte Streams)

## Problem Statement

Write a program to copy the contents of `source.txt` to `destination.txt` using `FileInputStream` and `FileOutputStream`. After copying, print "File Copied" and display the content of the destination file.

## Important Note for File I/O
Assume the input file (`source.txt`) is present in the working directory. Your program should create and write to `destination.txt` in the same directory. Do **NOT** use absolute paths.

## Input Format

* No console input. 
* The program reads from `source.txt`.

## Output Format

* `File Copied`
* `(Contents of destination.txt)`

### Example

**Assume `source.txt` contains:**
```text
Copy this text.
```

**Output:**
```text
File Copied
Copy this text.
```
