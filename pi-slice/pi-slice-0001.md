# Pi Slice 01:  Raspberry Pi School Activity 1
## Using the Linux Command Line Interface (CLI)

Note:  In the examples below, type the commands after the command prompt (**`$`**).

1. Print the current working directory.
```
pi@raspberrypi ~ $ pwd
```

2. List the contents of the directory.
```
pi@raspberrypi ~ $ ls
```
3. List the contents of the directory using the long form.
```
pi@raspberrypi ~ $ ls -l
```
4. Make a new directory called `pi_school`.  The underscore character is the shifted dash or minus character; the key to the right of the zero key (**\[Shift+-\]**).
```
pi@raspberrypi ~ $ mkdir pi_school
```

5. List the contents of the directory, again.  Do you see your new directory?
```
pi@raspberrypi ~ $ ls
```

6. Change to the new `pi_school` directory.  Print the current working directory.
```
pi@raspberrypi ~ $ cd pi_school
pi@raspberrypi ~/pi_school $ pwd
```

7. List the contents of the directory.  Notice that it's empty.
```
pi@raspberrypi ~/pi_school $ ls
```

8. Let's make a text file.  Give your new file a name.
```
pi@raspberrypi ~/pi_school $ nano myfile.txt
```

9. Type something in your text file.

10. When you're finished, type **\[Ctrl+X\]** to exit.  Type **\[Y\]** to save your changes.  Type **\[Enter\]** to accept the name of your text file.

11. List the contents of the directory.  Do you see your new file?

12. Let's view the file.
```
pi@raspberrypi ~/pi_school $ cat myfile.txt
```

13. Sometimes, you want to edit a copy of a file without making changes to the original.  Make a copy of your file.  List the contents of the directory to see your new file.
```
pi@raspberrypi ~/pi_school $ cp myfile.txt mycopy.txt
pi@raspberrypi ~/pi_school $ ls
```

14. You can also change the name of a file.  Renaming a file does _not_ make a copy.  After you rename the file, list the contents of the directory to see the new name.
```
pi@raspberrypi ~/pi_school $ mv mycopy.txt newname.txt
pi@raspberrypi ~/pi_school $ ls
```

15. You can also use the **mv** command to move the file into a different directory.  Move your renamed file to the `~/docs` directory.
```
pi@raspberrypi ~/pi_school $ mv newname.txt ~/docs
```

16. List the contents of the directory.  Where did your file go?

17. Let's find your file.  Change to the `docs` directory and list the contents.
```
pi@raspberrypi ~/pi_school $ cd ~/docs
pi@raspberrypi ~/docs $ ls
```

18. We don't need this file in the `docs` directory any more.  Let's remove it.
```
pi@raspberrypi ~/docs $ rm newname.txt
```

19. List the contents of the directory.  Has the file been deleted?
