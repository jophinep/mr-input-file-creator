mr-input-file-creator
===============

This python script allows you to create input file for map reduce program easily.
The concept of this program is, you can enter multiple fields with some sample values. And these sample values will be selected randomly and will be inserted to file. We can also enter number of rows we need to genarate for the file.
For now colon ':' is used as a delmiter.

Program behaviour
===============
The program execution will behave like:

```shel
jophine@jophine-ThinkPad-Edge ~ $ python mr-input-file-creator
Enter field 1 values, like: [val1, val2, val3, ... , valn] ~> ['balck', 'red', 'green', 'blue', 'yellow']
Enter field 2 values, like: [val1, val2, val3, ... , valn] ~> [100, 25, 306, 1]   
Enter field 3 values, like: [val1, val2, val3, ... , valn] ~> ['yes', 'no']
Enter field 4 values, like: [val1, val2, val3, ... , valn] ~> 
Taking above input as empty list '[]' 
NOTE: string should be enclosed in single/double quotes...

Enter number of rows ~> 10
Enter file path, like: "/home/jophine/kaka.txt" ~> "/home/jophine/kaka.txt"
jophine@jophine-ThinkPad-Edge ~ $
```

Output File format
=================
/home/jophine/kaka.txt contents are as follows,

```shel
green:25:yes
blue:100:yes
green:100:no
green:306:yes
yellow:25:no
yellow:1:yes
balck:100:yes
green:1:yes
yellow:1:yes
red:25:yes
```
