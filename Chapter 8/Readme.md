
pushd & popd explained

together these two commands allows one to hop back and forth between directories without having

to deal with the intermediate directories.

'pushd  xxx/vvv/sss' adds the current working directory to a directory list, or stack before jumping you to the destination directory xxx/vvv/sss.
 
'popd' takes off the latest entry on directory stack and moves control to that directory.

 When 'pushd' does not have an argument (destination directory) it adds the current working directory to the stack and moves control to the last entry in the stack.   (I think.)
 
 
 
 I tried various combinations of pushd and popd in the the Chapter 8 directory.
 
 I also pushd and popd the stack to/from 2 levels deep.
 
    Allens-MacBook-Pro:temp allenkrauskopf$ pushd stuff/things/frank
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:frank allenkrauskopf$ pushd joe/alex
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank/joe/alex ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:alex allenkrauskopf$ pushd
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank/joe/alex ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:frank allenkrauskopf$ pushd
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank/joe/alex ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:alex allenkrauskopf$ popd
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp/stuff/things/frank ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:frank allenkrauskopf$ popd
    ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 8/temp
    Allens-MacBook-Pro:temp allenkrauskopf$ popd
    bash: popd: directory stack empty
    Allens-MacBook-Pro:temp allenkrauskopf$

 
    
