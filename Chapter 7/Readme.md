
Do More

1)  Create 20 Directories

    Allens-MacBook-Pro:~ allenkrauskopf$ cd ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/"Chapter 7"
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_1
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_2
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_3
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_4
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_5
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_6
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_7
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_8
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_9
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_10
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_11
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_12
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_13
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_14
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_15
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_16
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_17
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_18
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_19
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir do_more_20
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$
    
  ... and remove them all.
  
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_1
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_2
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_3
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_4
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_5
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_6
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_7
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_8
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_9
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_10
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_11
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_12
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_13
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_14
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_15
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_16
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_17
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_18
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_19
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir do_more_20
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$
    
2)  Make a single path of directories that is 10 deep

    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ mkdir -p dm_01/dm_02/dm_03/dm_04/dm_05/dm_06/dm_07/dm_8/dm_09/dm_10
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$
    
   ... and remove them one at a time just like I did above.
   
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ cd dm_01/dm_02/dm_03/dm_04/dm_05/dm_06/dm_07/dm_8/dm_09/
    Allens-MacBook-Pro:dm_09 allenkrauskopf$ rm dm_10
    rm: dm_10: is a directory
    Allens-MacBook-Pro:dm_09 allenkrauskopf$ rmdir dm_10
    Allens-MacBook-Pro:dm_09 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_8 allenkrauskopf$ ls
    dm_09
    Allens-MacBook-Pro:dm_8 allenkrauskopf$ rmdir dm_09
    Allens-MacBook-Pro:dm_8 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_07 allenkrauskopf$ rmdir dm_8
    Allens-MacBook-Pro:dm_07 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_06 allenkrauskopf$ ls
    dm_07
    Allens-MacBook-Pro:dm_06 allenkrauskopf$ rmdir dm_07
    Allens-MacBook-Pro:dm_06 allenkrauskopf$ rmdir dm_06
    rmdir: dm_06: No such file or directory
    Allens-MacBook-Pro:dm_06 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_05 allenkrauskopf$ rmdir dm_06
    Allens-MacBook-Pro:dm_05 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_04 allenkrauskopf$ rmdir dm_05
    Allens-MacBook-Pro:dm_04 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_03 allenkrauskopf$ rmdir dm_04
    Allens-MacBook-Pro:dm_03 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_02 allenkrauskopf$ rmdir dm_03
    Allens-MacBook-Pro:dm_02 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:dm_01 allenkrauskopf$ rmdir dm_02
    Allens-MacBook-Pro:dm_01 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ ls
    Readme.md	dm_01
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ rmdir dm_01
    Allens-MacBook-Pro:Chapter 7 allenkrauskopf$ cd ..
    Allens-MacBook-Pro:learn_command_line_exercise allenkrauskopf$ ls
    Chapter 1	Chapter 3	Chapter 5	Chapter 7
    Chapter 2	Chapter 4	Chapter 6	README.md
    Allens-MacBook-Pro:learn_command_line_exercise allenkrauskopf$
    
English Questions

1)  Can you remove the tmp directory? Let's remove the tmp directory.

   Can't.  'tmp' is not recognized as a directory.
   
    Allens-MacBook-Pro:learn_command_line_exercise allenkrauskopf$ cd /tmp
    Allens-MacBook-Pro:tmp allenkrauskopf$ cd ..
    Allens-MacBook-Pro:/ allenkrauskopf$ rmdir tmp
    rmdir: tmp: Not a directory
    Allens-MacBook-Pro:/ allenkrauskopf$ ls
    Applications		bin			opt
    Library			cores			private
    Network			dev			sbin
    System			etc			tmp
    User Information	home			usr
    Users			mach_kernel		var
    Volumes			net
    Allens-MacBook-Pro:/ allenkrauskopf$ rmdir tmp
    rmdir: tmp: Not a directory
    Allens-MacBook-Pro:/ allenkrauskopf$
    

   
   
