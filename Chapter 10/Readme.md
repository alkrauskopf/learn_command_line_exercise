REJECTION:  for: Can you copy .bash_profile in your home directory to the current directory?
you can use '.' for the argument for current directory instead of bashprofile
please update the readme for the above and the story will be ready to accept

I did the following from "Chapter 10/temp" directory as shown below:

- Listed temp to show '.bash_profile' doesn't exist.
 
- Copied .bash_profile into current directory

- Listed temp to show that .bash_profile now exists.


    Allens-MacBook-Pro:temp allenkrauskopf$ ls -a
    .			foo.txt			secondplace
    ..			iamcool.txt		something
    Readme.md		neat.txt		thefourthfile.txt
    awesome.txt		newplace
    Allens-MacBook-Pro:temp allenkrauskopf$ cp ~/.bash_profile .
    Allens-MacBook-Pro:temp allenkrauskopf$ ls -a
    .			awesome.txt		newplace
    ..			foo.txt			secondplace
    .bash_profile		iamcool.txt		something
    Readme.md		neat.txt		thefourthfile.txt
    Allens-MacBook-Pro:temp allenkrauskopf$
    

-----------------------------------------------

REJECTION: Please answer the english questions...'
   
(No explanation for not doing so...)

1) Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)
 
   First create foo.txt in Chapter 10
 
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ echo "Create and Populate foo.txt" > foo.txt
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ ls
    Readme.md	foo.txt		second_temp	temp

   Then copy foo.txt tp slash temp, and show contents of foo.txt in slash temp.
   
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ cp foo.txt /tmp/
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ cd /tmp
    Allens-MacBook-Pro:tmp allenkrauskopf$ ls
    KSOutOfProcessFetcher.0.r55jifrBu08ZlGAfPLYXKgYad4c=
    KSOutOfProcessFetcher.501.r55jifrBu08ZlGAfPLYXKgYad4c=
    foo.txt
    launch-AlKSEF
    launch-SRzxB5
    launch-cni5Hv
    launchd-104.QIhjCV
    launchd-138.g3TYRr
    launchd-146.2d1Fu4
    launchd-343.8i9Yo8
    launchd-702.tM4ZMX
    mysql.sock
    Allens-MacBook-Pro:tmp allenkrauskopf$ cat foo.txt
    Create and Populate foo.txt
    
    
2) Can you copy .bash_profile in your home directory to the current directory?
    
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ cp ~/.bash_profile bash_profile
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ ls
    Readme.md	bp.txt		second_temp
    bash_profile	foo.txt		temp
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$ cat bash_profile
    
    [[ -s "$HOME/.profile" ]] && source "$HOME/.profile" # Load the default .profile
    
    [[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*
    
    if [ -f $(brew --prefix)/etc/bash_completion ]; then
        . $(brew --prefix)/etc/bash_completion
      fi
    
    alias git='hub'
    Allens-MacBook-Pro:Chapter 10 allenkrauskopf$
    

----------------------------------------------------------------------


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
   

   I now understand the purpose of the (sometimes) slash at the end of command line commands.  It explicitely identifies the preceding argument as a directory.
