Do More

Replicated temp/newplace.   Then I replicates temp and all of its subdirectories.

    Allens-MacBook-Pro:temp allenkrauskopf$ cp -r newplace secondplace
    Allens-MacBook-Pro:temp allenkrauskopf$ cd ..
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ cp -r temp second_temp
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ ls -1R
    Readme.md
    second_temp
    temp
    
    ./second_temp:
    awesome.txt
    iamcool.txt
    neat.txt
    newplace
    secondplace
    something
    thefourthfile.txt
    
    ./second_temp/newplace:
    awesome.txt
    
    ./second_temp/secondplace:
    awesome.txt
    
    ./second_temp/something:
    awesome.txt
    
    ./temp:
    awesome.txt
    iamcool.txt
    neat.txt
    newplace
    secondplace
    something
    thefourthfile.txt
    
    ./temp/newplace:
    awesome.txt
    
    ./temp/secondplace:
    awesome.txt
    
    ./temp/something:
    awesome.txt
    
2) Copy a file to your home directory

    Allens-MacBook-Pro:temp allenkrauskopf$ cp awesome.txt ~/
    Allens-MacBook-Pro:temp allenkrauskopf$
    
3) Find these files in your graphical user interface and open them in a text editor.

   They are empty files
   

What is ROBOCOPY?

   Robocopy stands for 'Robust File Copy.'  It was written for Windows. 
   
   It is supposed to be more reliable than the standard 'cp' command.  How so?  I have no idea.
   

   I finally understand the purpose of the (sometimes) slash at the end of command line commands.  It explicitely identifies the preceding argument as a directory.
