Do More

1) The 'ls -1R'  displays the content of the entire directory structure starting at the current working directory.

Note: I foolishly tried this at the root directory to see what would happen and had to CTRL C to abort the long listing.

English Questions

1) What's in the tmp directory?

   The 'stuff' directory
   
    Allens-MacBook-Pro:tmp allenkrauskopf$ ls
    stuff
    
2)  Can you show me what files are in that directory?

   There are no files in 'tmp'  There is only a directory called 'stuff'

    Allens-MacBook-Pro:tmp allenkrauskopf$ ls
    stuff
    
3)  What files are in your home directory?

   I guess I need clarfication on what is meant by'home' directory.  Is it the cd ~  directory?  I thought that was called the 'root' directory.
   
    Allens-MacBook-Pro:tmp allenkrauskopf$ cd ~
    Allens-MacBook-Pro:~ allenkrauskopf$ ls
    Applications		Movies			TCPJ_Project
    BitTorrent Sync		Music			console
    Desktop			Mysql Dumps		doo
    Documents		Pictures		tcpjdump1301.sql
    Downloads		Public			workspace
    Library			RubymineProjects
    Allens-MacBook-Pro:~ allenkrauskopf$
    
4) What's in slash temp?

   This is an area I need clarity on.
   Do some computers have '/tmp' in the their system directory and others have '/temp' ?
   
   Note the commands below where I,
   
   1)  cd ~  => list shows my root directory structure
   2)  cd /temp   => invalid (because there's no 'temp' directory.)
   3)  then I try   cd /tmp  =>  I go to an existing 'tmp' directory, but not the one found in Chapter 6.
   4)  ls =>  shows files I don't recognize
   5)  cd ..  =>  backs me up to a deeper(?) system directory containing my 'tmp' directory.
   
    Allens-MacBook-Pro:tmp allenkrauskopf$ cd ~
    Allens-MacBook-Pro:~ allenkrauskopf$ ls
    Applications		Movies			TCPJ_Project
    BitTorrent Sync		Music			console
    Desktop			Mysql Dumps		doo
    Documents		Pictures		tcpjdump1301.sql
    Downloads		Public			workspace
    Library			RubymineProjects
    Allens-MacBook-Pro:~ allenkrauskopf$ cd /temp
    bash: cd: /temp: No such file or directory
    Allens-MacBook-Pro:~ allenkrauskopf$ cd /tmp
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
    Allens-MacBook-Pro:tmp allenkrauskopf$ cd ..
    Allens-MacBook-Pro:/ allenkrauskopf$ ls
    Applications		bin			opt
    Library			cores			private
    Network			dev			sbin
    System			etc			tmp
    User Information	home			usr
    Users			mach_kernel		var
    Volumes			net
    Allens-MacBook-Pro:/ allenkrauskopf$
