# Exercise 1: Loops for productivity

In Linux, using loops will boost productivity. Here we will discuss how they can be used for routine operations.

## if loops

Classical example for using if loops would be to itireate through a bunch of files, to perform certain operations.
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
