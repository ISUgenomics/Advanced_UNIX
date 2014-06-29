# Exercise 1: Loops in UNIX

Most of the text here assumes that you are using BASH shell, in case if you aren't using bash SHELL, please switch to BASH since this hasn't been tested in other SHELLs.

A loop, in programming language means a block of code (several lines of code, performing the same function) that iterates until the condition governing the loop becomes false. A simple example would be, reading a file. Without a loop, you need to open the file read first line, close the file, open the file again, read the second line, close and so on. This will make the program/script really large and will be prone to errors. Now, if you write a simple code for just reading line, and repeat that for the total number of lines in the file, the same task can be completed within few steps.
 
## for loops

Classical example for using if loops would be to iterate through a bunch of files, to perform certain operations.
Typically, the loop will look like this:
```bash
for file in files;  
do
# perfrom someting for $file
done;
```
For example, if have have a bunch of files ending with .txt extension, I want to loop through all of them one by one, I can write the if loop as follows (note, you can write entire loop in one line, too)

```bash
for file in *.txt; do echo "doing something for file $file"; done
```
## if loops

## while loops

plenty of examples and exercises should follow each 