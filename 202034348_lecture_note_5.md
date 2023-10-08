# **My Lecture Note** 202034348_정영수

```sh
$ pwd
/home/youngmin/OSS/transformers
$ ls -lh
total 16k
-rw-rw-r--  ........                    README.md
....                                    classification_experiment.py
...                                     hello_world
..                                      test.sh
$ ls -lh > file_list.txt
$ cat file_list.txt
total 16k
-rw-rw-r--  ........                    README.md
....                                    classification_experiment.py
...                                     file_list.txt
...                                     hello_world
..                                      test.sh
```

**you can redirect output using ''>'' after a command to create and save the output in a file**
**Command ''cat'' displays the content of a text a file**

**Using ''>>'' appends output to an exising file (if it already exitsts), or create and write to a new file if it doesn't exist**

```sh
$ cat words.txt
school
class
home
new
lecture
$ sort < words.txt > sorted_words.txt
$ cat sorted_words.txt
class
home
lecture
new
school
```

**you can redirect input from a file using ''<''.**
1. sort '<'words.txt --> sort words.txt file
2. '>'  sorted_words.txt  --> save words.txt file


**pipeline(|) feeds output of previous command to input of next command.**

```sh
$ echo print out the text
print out the text  

$ echo *
README.md classification_experiment.py ..........
....        words.txt

$ echo ~   --> current user home directory
/home/youngmin
$ echo ~youngmin   --> specific user
/home/youngmin
```

***= ls**
**Special characters expand its meaning when given to shell commands**


**Backslah can be used to ignore line change in command (“enter”),
to enter a long command in multiple lines**


```sh
$ chmod 600 some_file
```

**“chmod” changes permissions.8**

***6 = 110 = rw- for owner
0 = 000 = - - - for group
0 = 000 = - - - for others***

```sh
$ sudo some_command  --> Put “sudo” before the command if you are a superuser.

$ sudo-i  --> Continued Administrator Mode
```


**Type “history” to see previous command history**







