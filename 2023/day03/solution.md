Day 3 Task: Basic Linux Commands

Task: What is the linux command to

1. To view what's written in a file.
$ cat a.txt
hello world

2. To change the access permissions of files.
$ chmod 777 a.txt

3. To check which commands you have run till now.
$ history

4. To remove a directory/ Folder.
$ rm -r B

5. To create a fruits.txt file and to view the content.
$ cat fruits.txt
Apple
Banana
Mango

6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.
$ vi devops.txt
Apple
Mango
Banana
Cherry
Kiwi
Orange
Guava

7. To Show only top three fruits from the file.
$ head -3 devops.txt
Apple
Mango
Banana

8. To Show only bottom three fruits from the file.
$ tail -3 devops.txt
Kiwi
Orange
Guava

9. To create another file Colors.txt and to view the content.
$ vi Colors.txt
$ cat Colors.txt
BLACK
WHITE

10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.
$ vi Colors.txt
Red
Pink
White
Black
Blue
Orange
Purple
Grey

11. To find the difference between fruits.txt and Colors.txt file.
$ diff fruits.txt Colors.txt
1,3c1,8
< Apple
< Banana
< Mango
---
> Red
> Pink
> White
> Black
> Blue
> Orange
> Purple
> Grey