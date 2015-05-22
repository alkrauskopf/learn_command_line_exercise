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
    

2)  Reworded Question: "Why don't we go into" == "Let's go into" i.e. What command would you run to go into the temp directory?

    Allens-MacBook-Pro:Chapter 5 allenkrauskopf$ cd /tmp
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
    mysql.sock

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

6)  The Process I use for finding the path with my graphical file browser is as follows:

   a)  I click on 'Finder' the smiley face icon on my App Dock.
   
   b) On the left side, I then click on my home directory 'allenkrauskopf' directory.
   
   c) I then expand the subdirectories of 'Workspace'
   
   d) I attached a screen shot to the Pivotal Story.
