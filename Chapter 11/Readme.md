
Do More.

1) Move a file in the newplace directory to another directory then move it back.

newplace wasn't created as a directory. Maybe I don't understand something.

So I created the nextplace directory and added a file to be moved.

    Allens-MacBook-Pro:temp allenkrauskopf$ mkdir nextplace
    Allens-MacBook-Pro:temp allenkrauskopf$ touch nextplace/groovy.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ cd nextplace
    Allens-MacBook-Pro:nextplace allenkrauskopf$ ls
    groovy.txt
    Allens-MacBook-Pro:nextplace allenkrauskopf$ cd ..
    Allens-MacBook-Pro:temp allenkrauskopf$
    Allens-MacBook-Pro:temp allenkrauskopf$ mv uncool.txt nextplace/
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -1R
    newplace
    nextplace
    
    ./nextplace:
    groovy.txt
    uncool.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ mv nextplace/groovy.txt groovy.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -1R
    groovy.txt
    newplace
    nextplace
    
    ./nextplace:
    uncool.txt
    Allens-MacBook-Pro:temp allenkrauskopf$
    
English Questions

1) Can you rename foo.txt to blah.txt?

    Allens-MacBook-Pro:temp allenkrauskopf$ touch foo.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ mv foo.txt blah.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ ls
    blah.txt	groovy.txt	newplace	nextplace
    Allens-MacBook-Pro:temp allenkrauskopf$
    

2) Can you move the production.log file in the log directory to slash temp?

   Yes. 
    
    Allens-MacBook-Pro:Chapter 11 allenkrauskopf$ mv log/production.log /tmp
    Allens-MacBook-Pro:Chapter 11 allenkrauskopf$ cd tmp
    bash: cd: tmp: No such file or directory
    Allens-MacBook-Pro:Chapter 11 allenkrauskopf$ cd /tmp
    Allens-MacBook-Pro:tmp allenkrauskopf$ ls
    KSOutOfProcessFetcher.0.r55jifrBu08ZlGAfPLYXKgYad4c=
    KSOutOfProcessFetcher.501.r55jifrBu08ZlGAfPLYXKgYad4c=
    launch-2lDRDP
    launch-bYXwnB
    launch-d10FvB
    launchd-128.b1axVO
    launchd-154.krCBz9
    launchd-157.18cgoV
    launchd-342.auaXFj
    launchd-82818.CLhyw6
    log
    mysql.sock
    production.log
    Allens-MacBook-Pro:tmp allenkrauskopf$
    
3) Can you zero out that file?
    
   didn't know what "zero out" technically means so I looked it up.   And used 'cat/dev/null > /tmp/production.log

    Allens-MacBook-Pro:Chapter 11 allenkrauskopf$ cat /dev/null > /tmp/production.log
    
    
