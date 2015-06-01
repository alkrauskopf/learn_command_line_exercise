REJECTION:  for: 'Can you output all the txt files in this directory?' - the '1' should be a 'l', otherwise correct, please change this one in the readme and the story will be ready to accept


2)  Can you output all the txt files in this directory?

   Changing the '1 'to a 'l'
   
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -1 *.txt
    bar.txt
    ex12.txt
    ex13.txt
    ex15.txt
    foo.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -l *.txt
    -rw-r--r--  1 allenkrauskopf  staff  19 May 24 14:02 bar.txt
    -rw-r--r--  1 allenkrauskopf  staff  23 May 23 09:55 ex12.txt
    -rw-r--r--  1 allenkrauskopf  staff  80 May 23 09:55 ex13.txt
    -rw-r--r--  1 allenkrauskopf  staff  80 May 24 13:43 ex15.txt
    -rw-r--r--  1 allenkrauskopf  staff  16 May 24 14:02 foo.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ cat *.txt
    This class is fun.
    Hi there this is cool.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    Oh so much fun.
    Allens-MacBook-Pro:temp allenkrauskopf$
    
    

--------------------------------------------------------------------------



English Questions

1) How big are is foo.txt?

   Looks like foo.txt is 16bytes

    Allens-MacBook-Pro:temp allenkrauskopf$ ls -lh foo.txt
    -rw-r--r--  1 allenkrauskopf  staff    16B May 24 14:02 foo.txt
    Allens-MacBook-Pro:temp allenkrauskopf$
    

2)  Can you output all the txt files in this directory?

    Allens-MacBook-Pro:temp allenkrauskopf$ ls -1 *.txt
    bar.txt
    ex12.txt
    ex13.txt
    ex15.txt
    foo.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ cat *.txt
    This class is fun.
    Hi there this is cool.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    Oh so much fun.
    Allens-MacBook-Pro:temp allenkrauskopf$
    
3) Show me the content of the text files in slash temp.
 
   OK. But first I had to put some txt files back into tmp. 

    Allens-MacBook-Pro:temp allenkrauskopf$ cp e*.txt /tmp
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -1 /tmp/*.txt
    /tmp/ex12.txt
    /tmp/ex13.txt
    /tmp/ex15.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ cat /tmp/*.txt
    Hi there this is cool.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    I am a fun guy.
    Don't you know why?
    Because I make poems,
    that make babies cry.
    Allens-MacBook-Pro:temp allenkrauskopf$
    
