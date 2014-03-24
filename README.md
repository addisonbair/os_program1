New to git? Read this: http://rogerdudler.github.io/git-guide/

The idea here is to write a simple version of the ps command.

For example, consider a command such as:
  
    4323ps -p 1234 -s -U -c 


This command should return something similar to:

    1234: R utime=150 [myprog -x -y file1 myoption] 


Most of the ideas presented so far are researched from this page:
  
    http://pages.cs.wisc.edu/~bart/537/programs/program1.html


What we have so far:

    - Functional getopt to read in command line arguments.
    - Semi-functional readdir to view the /proc filesystem.


What we need:

    - Finish readdir functionality to dive into /proc filesystem
    - Write C main function to include linked getopt and readdir
    - Write makefile to compile under gcc
    - Potentially more
