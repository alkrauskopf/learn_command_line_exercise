
Do More.

Create a new directory. Put a new file in it. Then try to remove the directory.

Below are my exercises.  I first created a Chapter 9 temp directory (maybe I should have gone to \tmp) to do the instructions.

Then, in 'temp' I created the 'temp_2' directory.

Moved to 'temp_2' and created 'new_file.txt'

Moved back up to 'temp' and tried to delete 'temp_2'

And error message was created because I cannot remove a diretory that is populated with a file ('new_file.txt').  It doesn't matter that the file is empty.

    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ mkdir temp
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ cd temp
    Allens-MacBook-Pro:temp allenkrauskopf$ touch iamcool.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ ls
    iamcool.txt
    Allens-MacBook-Pro:temp allenkrauskopf$ mkdir temp_2
    Allens-MacBook-Pro:temp allenkrauskopf$ cd temp_2
    Allens-MacBook-Pro:temp_2 allenkrauskopf$ touch new_file.txt
    Allens-MacBook-Pro:temp_2 allenkrauskopf$ ls
    new_file.txt
    Allens-MacBook-Pro:temp_2 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:temp allenkrauskopf$ ls
    iamcool.txt	temp_2
    Allens-MacBook-Pro:temp allenkrauskopf$ rmdir temp_2
    rmdir: temp_2: Directory not empty
    Allens-MacBook-Pro:temp allenkrauskopf$

        
English Questions.

1) Can you touch blah.txt?

   Yes. I first created 'blah.txt' in Chapter 9 directory. Then 'touch blah.txt'  No error occurs even though the file already exists.
   
2) Let's create foo txt.

   See below.
   
Explain what happens if you 'touch' and existing file.

   Touching an existing file simply causes the last modification time stamp to be updated to the current time.

    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ ls
    Readme.md	blah.txt	temp
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ touch blah.tx
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ touch blah.txt
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ touch blah.txt
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ touch foo.txt
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$ ls
    Readme.md	blah.tx		blah.txt	foo.txt		temp
    Allens-MacBook-Pro:Chapter 9 allenkrauskopf$
       
        
