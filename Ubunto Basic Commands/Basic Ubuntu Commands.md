# Basic Ubuntu Commands

- To create a file the  touch command is used.
- Two files with names "19f_XXXX.txt" and "bilal.txt" are made using this command in figure 1.

![](.\OSLab2\touch2.PNG "Figure 1")

- Data is populated in these files by using the nano command which serve as a simple text editor for file.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\nano.PNG)

- Data of two of more files can be merged into a new file in the following way.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\merge.PNG)

- To display any number of starting lines of a specific file "head" command can be used.
- Similarly "tail" command can be used to display any number of ending lines of a file.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\headTail.PNG)

- To find a specific string from a file "grep" command can be used. It shows the line in which the specified string is found or do nothing if not.

 ![](C:\Users\Burhan Ahmad\Pictures\OSLab2\grep.PNG)

- To grant the execution permission to the group "chmod" command can be used as shown in figure. 

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\chmod1.PNG)

- To remove the writing permission from the user the same command is used in the following way.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\chmod2.PNG)

- To find your current location "pwd" command is used.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\pwd.PNG)

- To display the list of all files on a specific directory ls "command" is used.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\listOfFiles.PNG)

- To create a folder "mkdir" command is used.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\mkdir.PNG)

- To display the current date and time "date" command is used.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\echo.PNG)

- To display any message "echo" command is used.

#### **File Permissions using Numeric Format**

- Firstly I m creating a file named "19f_XXX_OS-lab_rules.txt" and populated the data in it using the nano command.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\point1.PNG)

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\nanoLast.PNG)

- To set permissions of a file using the numeric format chomd command is used in combination of 3 integers  where first is for user ,second is for group and third is for others.

````Format
 r   w   x
  4  2   1
  For example for rwx-rx-r the number 754 will be used.
  where rwx is for user ,rw is for group and r is for others.
````

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\rwx.PNG)

- The output of the ls command can be appended to a file in the following way. Results can be seen using the cat command.

![](C:\Users\Burhan Ahmad\Pictures\OSLab2\last.PNG)
