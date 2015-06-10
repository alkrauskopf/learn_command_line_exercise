REJECTION: What command(s) did you run for Q's #1, 2, 3 ?

ANSWER:  I ran 'env' from the command line and saw my answers in the listing that was displayed.

  1) SHELL=/bin/bash
  
  2) PWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 21
  
  3) HOME=/Users/allenkrauskopf
  
  
--------------------------------------------------------------
Below is my environment:

1) What is your shell set to?   SHELL=/bin/bash
    
2) What directory are you in (don't use pwd this time)?   PWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 21

3) What is your home directory set to?   HOME=/Users/allenkrauskopf

4) Can you set your environment to have DEBUG set to true?

    Allens-MacBook-Pro:Chapter 21 allenkrauskopf$ export DEBUG=true
    
   Check second ENV listing below to see DEBUG=true was added.


    Allens-MacBook-Pro:Chapter 21 allenkrauskopf$ env
    rvm_bin_path=/Users/allenkrauskopf/.rvm/bin
    TERM_PROGRAM=iTerm.app
    SHELL=/bin/bash
    TERM=xterm-256color
    TMPDIR=/var/folders/mq/cqygbzm56nj8qm9yhmg704y40000gn/T/
    Apple_PubSub_Socket_Render=/tmp/launch-bYXwnB/Render
    OLDPWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise
    USER=allenkrauskopf
    _system_type=Darwin
    COMMAND_MODE=unix2003
    rvm_path=/Users/allenkrauskopf/.rvm
    SSH_AUTH_SOCK=/tmp/launch-2lDRDP/Listeners
    __CF_USER_TEXT_ENCODING=0x1F5:0:0
    Apple_Ubiquity_Message=/tmp/launch-d10FvB/Apple_Ubiquity_Message
    rvm_prefix=/Users/allenkrauskopf
    PATH=/opt/local/bin:/opt/local/sbin:/usr/local/bin:/opt/local/bin:/usr/bin/env ruby:/usr/local/mysql/bin/mysql:/usr/bin:/bin:/usr/sbin:/sbin:/Users/allenkrauskopf/.rvm/bin
    DESTINATION=/var/folders/mq/cqygbzm56nj8qm9yhmg704y40000gn/T/iTerm 2.0 Update
    PWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 21
    LANG=en_US.UTF-8
    ITERM_PROFILE=Projector - Light
    _system_arch=x86_64
    _system_version=10.8
    rvm_version=1.26.11 (latest)
    SHLVL=1
    COLORFGBG=11;15
    HOME=/Users/allenkrauskopf
    ITERM_SESSION_ID=w0t0p0
    LOGNAME=allenkrauskopf
    _system_name=OSX
    _=/usr/bin/env
    
   below with DEBUG-true
   
    Allens-MacBook-Pro:Chapter 21 allenkrauskopf$ env
    rvm_bin_path=/Users/allenkrauskopf/.rvm/bin
    TERM_PROGRAM=iTerm.app
    SHELL=/bin/bash
    TERM=xterm-256color
    TMPDIR=/var/folders/mq/cqygbzm56nj8qm9yhmg704y40000gn/T/
    Apple_PubSub_Socket_Render=/tmp/launch-bYXwnB/Render
    OLDPWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise
    USER=allenkrauskopf
    _system_type=Darwin
    COMMAND_MODE=unix2003
    rvm_path=/Users/allenkrauskopf/.rvm
    SSH_AUTH_SOCK=/tmp/launch-2lDRDP/Listeners
    __CF_USER_TEXT_ENCODING=0x1F5:0:0
    Apple_Ubiquity_Message=/tmp/launch-d10FvB/Apple_Ubiquity_Message
    rvm_prefix=/Users/allenkrauskopf
    PATH=/opt/local/bin:/opt/local/sbin:/usr/local/bin:/opt/local/bin:/usr/bin/env ruby:/usr/local/mysql/bin/mysql:/usr/bin:/bin:/usr/sbin:/sbin:/Users/allenkrauskopf/.rvm/bin
    DESTINATION=/var/folders/mq/cqygbzm56nj8qm9yhmg704y40000gn/T/iTerm 2.0 Update
    PWD=/Users/allenkrauskopf/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercise/Chapter 21
    LANG=en_US.UTF-8
    ITERM_PROFILE=Projector - Light
    _system_arch=x86_64
    _system_version=10.8
    rvm_version=1.26.11 (latest)
    SHLVL=1
    COLORFGBG=11;15
    HOME=/Users/allenkrauskopf
    ITERM_SESSION_ID=w0t0p0
    LOGNAME=allenkrauskopf
    DEBUG=true
    _system_name=OSX
    _=/usr/bin/env
    
