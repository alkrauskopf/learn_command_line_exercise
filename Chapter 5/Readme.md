Do More

1)  `Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ cd temp/stuff/things/frank/joe`

2)  `Allens-MacBook-Pro:joe allenkrauskopf$ cd ../../../..`

3)  `Allens-MacBook-Pro:temp allenkrauskopf$ cd ~`

4)  `Allens-MacBook-Pro:~ allenkrauskopf$ cd Documents`

5)  `Allens-MacBook-Pro:Downloads allenkrauskopf$ cd ~/Pictures/iPod\ Photo\ Cache`

6)  `Allens-MacBook-Pro:Pictures allenkrauskopf$ cd "iPod Photo Cache"`

English Questions

1) Can you cd into the temp directory?

    Allens-MacBook-Pro:Chapter 5 allenkrauskopf$ mkdir temp/
    Allens-MacBook-Pro:Chapter 5 allenkrauskopf$ cd ~
    Allens-MacBook-Pro:~ allenkrauskopf$ cd workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/"Chapter 5"/temp
    Allens-MacBook-Pro:temp allenkrauskopf$
    

2)  Why don't we go into the temp directory?

   We can go into the temp directory, but the presumption is that directories and files
   in this directory are temporary. 
     So there may be times when all temp files are removed.

3) Can you go to the slash temp directory?
   
   No.  cd /temp produces and error because the slash is assumed to belong to the directory name.

    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ ls
    Readme.md	temp
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ cd /temp
    bash: cd: /temp: No such file or directory

4) Can you go to the slash temp slash log directory?
   No. because the /temp is assumed to belong to the directory name
   
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ cd /temp/log/
    bash: cd: /temp/log/: No such file or directory
    
   But cd temp/log/  puts me in the log directory
   
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ cd temp/log/
    Allens-MacBook-Pro:log allenkrauskopf$


5) What does the .. argument to cd do?

  the '..' argument moves you to the next highest directory in the directory tree structure.
