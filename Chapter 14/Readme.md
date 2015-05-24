English Questions

1) Can you remove blah.txt?  (after creating it?)

    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ touch blah.txt
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ ls
    Readme.md	blah.txt	temp
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ rm blah.txt
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ ls
    Readme.md	temp
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$
    
2)  Let's get rid of our development log file.

    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ rm ~/console/log/development.log
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$
    
3) Can you remove everything in the slash temp slash foo directory? (after creating it)

    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ mkdir temp/foo
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ ls -1R
    Readme.md
    temp
    
    ./temp:
    foo
    iamcool.txt
    neat.txt
    something
    thefourthfile.txt
    uncool.txt
    
    ./temp/foo:
    
    ./temp/something:
    awesome.txt
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ rmdir temp/foo
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$ ls temp/
    iamcool.txt		something		uncool.txt
    neat.txt		thefourthfile.txt
    Allens-MacBook-Pro:Chapter 14 allenkrauskopf$

4) DANGER: Why is it dangerous to run "rm -rf /"  ?

    rm  =>  removes file
    
    -r => recursive, meaning to repeat for every file in the directory and its subdrecotories 
    
    -f => force, meaning don't let anything stop me.
    
    / = begin at home directory.
    
    TRANSLATION: I will delete all files in the home directory and I won't have any reason to stop.
    
  Generally, NOT something one wants to do.





    
    
